## IntlPreferences

> `/System/Library/PrivateFrameworks/IntlPreferences.framework/Versions/A/IntlPreferences`

```diff

-498.0.0.0.0
-  __TEXT.__text: 0x2b188
-  __TEXT.__objc_methlist: 0x26f4
-  __TEXT.__const: 0x228
+500.1.1.0.0
+  __TEXT.__text: 0x2bb48
+  __TEXT.__objc_methlist: 0x270c
+  __TEXT.__const: 0x238
   __TEXT.__gcc_except_tab: 0x348
-  __TEXT.__cstring: 0x2a35
-  __TEXT.__oslogstring: 0x126d
+  __TEXT.__cstring: 0x2ad5
+  __TEXT.__oslogstring: 0x156a
   __TEXT.__dlopen_cstrs: 0xea
   __TEXT.__ustring: 0x58
   __TEXT.__swift5_typeref: 0x66
-  __TEXT.__unwind_info: 0xb18
+  __TEXT.__unwind_info: 0xb28
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2270
+  __DATA_CONST.__objc_selrefs: 0x2280
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x60
   __DATA_CONST.__objc_arraydata: 0x890
-  __DATA_CONST.__got: 0x518
+  __DATA_CONST.__got: 0x520
   __AUTH_CONST.__const: 0xa60
-  __AUTH_CONST.__cfstring: 0x3a60
-  __AUTH_CONST.__objc_const: 0x4730
+  __AUTH_CONST.__cfstring: 0x3ac0
+  __AUTH_CONST.__objc_const: 0x4738
   __AUTH_CONST.__objc_arrayobj: 0x1c8
   __AUTH_CONST.__objc_dictobj: 0x168
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x650
+  __AUTH_CONST.__auth_got: 0x658
   __AUTH.__objc_data: 0x280
   __DATA.__objc_ivar: 0x1cc
   __DATA.__data: 0x380

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 836
-  Symbols:   2472
-  CStrings:  613
+  Functions: 840
+  Symbols:   2478
+  CStrings:  623
 
Symbols:
+ +[IntlUtility _migratePreferredLanguageFromBundleID:sourceContainerPath:toBundleID:destinationContainerPath:carriedLanguages:error:]
+ _NSLocalizedDescriptionKey
+ _OUTLINED_FUNCTION_4
+ __CFPreferencesSynchronizeWithContainer
+ __appleLanguagesInContainer
+ _objc_msgSend$_updatePerAppLanguageSelectionInPrivateDomainForBundleID:selected:
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
