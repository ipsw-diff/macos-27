## CloudDocs

> `/System/Library/PrivateFrameworks/CloudDocs.framework/Versions/A/CloudDocs`

```diff

-5168.40.149.0.1
-  __TEXT.__text: 0x85090
+5168.40.162.0.0
+  __TEXT.__text: 0x84fe8
   __TEXT.__objc_methlist: 0x6764
-  __TEXT.__const: 0x1c0
+  __TEXT.__const: 0x1b0
   __TEXT.__gcc_except_tab: 0x3ef0
-  __TEXT.__cstring: 0xb21c
-  __TEXT.__oslogstring: 0x8a63
+  __TEXT.__cstring: 0xb202
+  __TEXT.__oslogstring: 0x8a53
   __TEXT.__dlopen_cstrs: 0x4c
   __TEXT.__ustring: 0x10
   __TEXT.__unwind_info: 0x30f8

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 3086
+  Functions: 3087
   Symbols:   6739
   CStrings:  2152
 
Functions:
~ -[BRMangledID initWithMangledString:] : 248 -> 244
~ -[BRMangledID initWithCoder:] : 292 -> 276
~ +[BRMangledID _mangledIDStringFromZoneName:ownerName:validate:] : 444 -> 376
- _OUTLINED_FUNCTION_7
~ +[NSError(BRAdditions) brc_errorUnknownKey:] : 72 -> 36
~ +[NSError(BRAdditions) brc_errorAppLibraryNotFound:] : 72 -> 36
~ +[NSError(BRAdditions) brc_errorClientZoneNotFound:] : 72 -> 36
+ _OUTLINED_FUNCTION_0
~ -[NSString(BRCAdditions) br_obfuscateAliasTarget] : 420 -> 416
~ -[BRMangledID initWithMangledString:].cold.1 : 60 -> 56
~ -[BRMangledID initWithCoder:].cold.1 : 76 -> 56
~ +[BRMangledID validateOwnerName:].cold.2 : 100 -> 108
~ +[BRMangledID validateOwnerName:].cold.3 : 100 -> 108
+ +[BRMangledID _mangledIDStringFromZoneName:ownerName:validate:].cold.2
~ -[NSString(BRCAdditions) br_obfuscateAliasTarget].cold.1 : 92 -> 76
CStrings:
+ "5168.40.162"
+ "App library not found"
+ "Client zone not found"
+ "Invalid parameter '%@'"
+ "Unknown key"
+ "[CRIT] UNREACHABLE: encoded object has bogus mangledID%@"
+ "[CRIT] UNREACHABLE: invalid mangled string%@"
+ "[CRIT] UNREACHABLE: invalid zone or owner name%@"
+ "[CRIT] UNREACHABLE: malformed alias target%@"
- "5168.40.149.0.1"
- "App library not found: '%@'"
- "Client zone not found: '%@'"
- "Invalid parameter '%@': %@"
- "Unknown key: '%@'"
- "[CRIT] UNREACHABLE: encoded object has bogus mangledID %@%@"
- "[CRIT] UNREACHABLE: invalid mangled string %@%@"
- "[CRIT] UNREACHABLE: invalid zone %@ or owner name %@%@"
- "[CRIT] UNREACHABLE: malformed alias target: %@%@"
```
