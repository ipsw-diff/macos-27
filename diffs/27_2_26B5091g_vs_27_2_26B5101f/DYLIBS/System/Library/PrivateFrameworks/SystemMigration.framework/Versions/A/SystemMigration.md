## SystemMigration

> `/System/Library/PrivateFrameworks/SystemMigration.framework/Versions/A/SystemMigration`

```diff

-6164.40.7.0.0
-  __TEXT.__text: 0xfe188
-  __TEXT.__objc_methlist: 0x109a0
+6164.40.8.0.0
+  __TEXT.__text: 0xfea7c
+  __TEXT.__objc_methlist: 0x109f8
   __TEXT.__const: 0x214
-  __TEXT.__gcc_except_tab: 0x3bf0
-  __TEXT.__cstring: 0x23aca
+  __TEXT.__gcc_except_tab: 0x3c20
+  __TEXT.__cstring: 0x23e3a
   __TEXT.__oslogstring: 0x402
   __TEXT.__ustring: 0x147c
   __TEXT.__constg_swiftt: 0x8c
   __TEXT.__swift5_typeref: 0x1a
   __TEXT.__swift5_fieldmd: 0x20
   __TEXT.__swift5_types: 0x8
-  __TEXT.__unwind_info: 0x3cd8
+  __TEXT.__unwind_info: 0x3cf8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x188
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x85b8
+  __DATA_CONST.__objc_selrefs: 0x8608
   __DATA_CONST.__objc_protorefs: 0x88
   __DATA_CONST.__objc_superrefs: 0x4b0
   __DATA_CONST.__objc_arraydata: 0x778
   __DATA_CONST.__got: 0xed0
   __AUTH_CONST.__const: 0x1bd0
-  __AUTH_CONST.__cfstring: 0x19be0
-  __AUTH_CONST.__objc_const: 0x174f8
+  __AUTH_CONST.__cfstring: 0x19d80
+  __AUTH_CONST.__objc_const: 0x17528
   __AUTH_CONST.__objc_intobj: 0x780
   __AUTH_CONST.__objc_arrayobj: 0x438
   __AUTH_CONST.__objc_dictobj: 0xa0

   __AUTH_CONST.__auth_got: 0x9a0
   __AUTH.__objc_data: 0x3ab0
   __AUTH.__data: 0x98
-  __DATA.__objc_ivar: 0x12a4
+  __DATA.__objc_ivar: 0x12a8
   __DATA.__data: 0x1310
   __DATA.__bss: 0x158
   __DATA.__common: 0x28

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5703
-  Symbols:   13239
-  CStrings:  4066
+  Functions: 5710
+  Symbols:   13258
+  CStrings:  4083
 
Symbols:
+ -[SMMigrationRequest sessionID]
+ -[SMMigrationRequest setSessionID:]
+ -[SMTelemetryHandler acceptSessionID:]
+ -[SMTelemetryHandler currentSessionID]
+ -[SMTelemetryHandler deletePersistedSessionID]
+ -[SMTelemetryHandler loadPersistedSessionID]
+ -[SMTelemetryHandler persistSessionID]
+ OBJC_IVAR_$_SMMigrationRequest._sessionID
+ _objc_msgSend$acceptSessionID:
+ _objc_msgSend$currentSessionID
+ _objc_msgSend$decodeInt32ForKey:
+ _objc_msgSend$deletePersistedSessionID
+ _objc_msgSend$encodeInt32:forKey:
+ _objc_msgSend$loadPersistedSessionID
+ _objc_msgSend$persistSessionID
+ _objc_msgSend$setSessionID:
+ _objc_msgSend$stringWithContentsOfFile:encoding:error:
+ _objc_msgSend$unsignedIntValue
+ _objc_msgSend$writeToFile:atomically:encoding:error:
CStrings:
+ "-[SMTelemetryHandler acceptSessionID:]"
+ "-[SMTelemetryHandler deletePersistedSessionID]"
+ "-[SMTelemetryHandler loadPersistedSessionID]"
+ "-[SMTelemetryHandler persistSessionID]"
+ "/var/db/.SMTelemetrySessionID"
+ "Accepting upstream SessionID %u from migration request"
+ "Persisting SessionID %u to migration request (request had %u)"
+ "[SMTelemetryHandler] Accepting upstream SessionID: %u (replacing internal: %u)"
+ "[SMTelemetryHandler] Deleted persisted SessionID at %@"
+ "[SMTelemetryHandler] Failed to delete persisted SessionID at %@: %@"
+ "[SMTelemetryHandler] Failed to persist SessionID to %@: %@"
+ "[SMTelemetryHandler] Failed to read persisted SessionID from %@: %@"
+ "[SMTelemetryHandler] Loaded persisted SessionID %u from %@"
+ "[SMTelemetryHandler] No persisted SessionID at %@"
+ "[SMTelemetryHandler] Persisted SessionID %u to %@"
+ "[SMTelemetryHandler] Persisted SessionID was 0, ignoring"
+ "sessionID"
```
