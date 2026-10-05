## IntlPreferences

> `/System/iOSSupport/System/Library/PrivateFrameworks/IntlPreferences.framework/Versions/A/IntlPreferences`

```diff

-498.0.0.0.0
-  __TEXT.__text: 0x18f80
-  __TEXT.__objc_methlist: 0x1114
-  __TEXT.__const: 0x1f0
-  __TEXT.__cstring: 0x1145
-  __TEXT.__oslogstring: 0xd3b
+500.1.1.0.0
+  __TEXT.__text: 0x198a8
+  __TEXT.__objc_methlist: 0x112c
+  __TEXT.__const: 0x200
+  __TEXT.__cstring: 0x11e5
+  __TEXT.__oslogstring: 0x1038
   __TEXT.__gcc_except_tab: 0x134
   __TEXT.__ustring: 0x4
   __TEXT.__swift5_typeref: 0x76
-  __TEXT.__unwind_info: 0x698
+  __TEXT.__unwind_info: 0x6a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf90
+  __DATA_CONST.__objc_selrefs: 0xfa8
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__objc_arraydata: 0x360
-  __DATA_CONST.__got: 0x2c0
+  __DATA_CONST.__got: 0x2d0
   __AUTH_CONST.__const: 0x260
-  __AUTH_CONST.__cfstring: 0x19e0
-  __AUTH_CONST.__objc_const: 0x1518
+  __AUTH_CONST.__cfstring: 0x1a40
+  __AUTH_CONST.__objc_const: 0x1520
   __AUTH_CONST.__objc_intobj: 0xc0
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x1b0
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x5d0
+  __AUTH_CONST.__auth_got: 0x5d8
   __DATA.__objc_ivar: 0x54
   __DATA.__data: 0x148
   __DATA.__bss: 0x148

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 420
-  Symbols:   1303
-  CStrings:  306
+  Functions: 424
+  Symbols:   1311
+  CStrings:  316
 
Symbols:
+ +[IntlUtility _migratePreferredLanguageFromBundleID:sourceContainerPath:toBundleID:destinationContainerPath:carriedLanguages:error:]
+ _NSLocalizedDescriptionKey
+ _OBJC_CLASS_$_NSError
+ _OUTLINED_FUNCTION_2
+ __CFPreferencesSynchronizeWithContainer
+ __appleLanguagesInContainer
+ _objc_msgSend$_updatePerAppLanguageSelectionInPrivateDomainForBundleID:selected:
+ _objc_msgSend$errorWithDomain:code:userInfo:
CStrings:
+ "### [%{public}@]: Per-app language migration failed: could not synchronize AppleLanguages for %{private}@"
+ "Empty bundle identifier or container path"
+ "Failed to synchronize AppleLanguages for the destination app"
+ "[%{public}@]: Per-app language migration complete: %{private}@ -> %{private}@, override language [%{public}@], %lu entries"
+ "[%{public}@]: Per-app language migration complete: [%{public}@] resolves to the default for %{private}@, so nothing was recorded"
+ "[%{public}@]: Per-app language migration complete: source %{private}@ had no override to carry over"
+ "[%{public}@]: Per-app language migration rejected: empty bundle identifier or container path"
+ "[%{public}@]: Per-app language migration skipped: source and destination are the same app"
+ "[IntlUtility]: Per-app language migration could not read the destination bundle for %{private}@; carrying the override over"
+ "com.apple.IntlPreferences.PerAppLanguageMigration"
```
