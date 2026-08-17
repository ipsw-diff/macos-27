## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/Versions/A/ScreenTimeCore`

```diff

-655.0.400.0.0
-  __TEXT.__text: 0x1063c4
+655.0.405.0.0
+  __TEXT.__text: 0x107600
   __TEXT.__objc_methlist: 0xa360
-  __TEXT.__const: 0x3478
-  __TEXT.__cstring: 0xa71c
-  __TEXT.__oslogstring: 0xbefa
+  __TEXT.__const: 0x3488
+  __TEXT.__cstring: 0xa77c
+  __TEXT.__oslogstring: 0xbf9a
   __TEXT.__gcc_except_tab: 0x1ac0
   __TEXT.__swift5_typeref: 0x15ac
   __TEXT.__constg_swiftt: 0xdd4

   __TEXT.__swift5_types: 0xf0
   __TEXT.__swift5_capture: 0xb88
   __TEXT.__swift5_protos: 0x14
-  __TEXT.__swift_as_entry: 0x174
-  __TEXT.__swift_as_ret: 0x1a8
-  __TEXT.__swift_as_cont: 0x248
+  __TEXT.__swift_as_entry: 0x180
+  __TEXT.__swift_as_ret: 0x1c0
+  __TEXT.__swift_as_cont: 0x26c
   __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__unwind_info: 0x4068
-  __TEXT.__eh_frame: 0x42e4
+  __TEXT.__unwind_info: 0x40d0
+  __TEXT.__eh_frame: 0x444c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9d0
+  __DATA_CONST.__const: 0x9d8
   __DATA_CONST.__objc_classlist: 0x6f0
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x240

   __DATA_CONST.__objc_superrefs: 0x4d8
   __DATA_CONST.__objc_arraydata: 0x250
   __DATA_CONST.__got: 0xe40
-  __AUTH_CONST.__const: 0x4d10
-  __AUTH_CONST.__cfstring: 0x9980
+  __AUTH_CONST.__const: 0x4d50
+  __AUTH_CONST.__cfstring: 0x9a20
   __AUTH_CONST.__objc_const: 0x13490
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0xc8
-  __AUTH_CONST.__auth_got: 0x1130
+  __AUTH_CONST.__auth_got: 0x1138
   __AUTH.__objc_data: 0x3248
   __AUTH.__data: 0x518
   __DATA.__objc_ivar: 0x7c4
   __DATA.__data: 0x21b0
-  __DATA.__bss: 0x3ed0
+  __DATA.__bss: 0x3ef0
   __DATA.__common: 0xd0
   __DATA_DIRTY.__objc_data: 0x1f40
   __DATA_DIRTY.__data: 0x288

   - /System/Library/PrivateFrameworks/ScreenTimeSettingsServices.framework/Versions/A/ScreenTimeSettingsServices
   - /System/Library/PrivateFrameworks/URLFormatting.framework/Versions/A/URLFormatting
   - /System/Library/PrivateFrameworks/UsageTracking.framework/Versions/A/UsageTracking
+  - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAccelerate.dylib

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6030
-  Symbols:   8820
-  CStrings:  2264
+  Functions: 6053
+  Symbols:   8834
+  CStrings:  2271
 
Symbols:
+ -[STRegulatoryIntelligenceSiriPolicy presentsOriginalSiriOnly]
+ -[STRegulatoryIntelligenceSiriPolicy setPresentsOriginalSiriOnly:]
+ OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._presentsOriginalSiriOnly
+ STImagePlaygroundBundleIdentifiers
+ STImagePlaygroundBundleIdentifiers.bundleIdentifiers
+ STImagePlaygroundBundleIdentifiers.onceToken
+ STIsDeviceChinaSKU
+ STIsDeviceChinaSKU.isChinaSKURegion
+ STIsDeviceChinaSKU.onceToken
+ _MGCopyAnswer
+ _STImagePlaygroundBundleIdentifiers
+ _STIsImagePlaygroundBundleIdentifier
+ _STShouldHideBundleIdentifierFromUI
+ _STUserDefaultsKeyForceChinaSKU
+ ___STImagePlaygroundBundleIdentifiers_block_invoke
+ ___STIsDeviceChinaSKU_block_invoke
+ _objc_msgSend$regulatoryRestrictions
+ _objc_msgSend$setPresentsOriginalSiriOnly:
- -[STRegulatoryIntelligenceSiriPolicy setSiriAIIsHidden:]
- -[STRegulatoryIntelligenceSiriPolicy siriAIIsHidden]
- OBJC_IVAR_$_STRegulatoryIntelligenceSiriPolicy._siriAIIsHidden
- _objc_msgSend$setSiriAIIsHidden:
CStrings:
+ "CH"
+ "Could not get category for bundleID %{private}s: %{public}@"
+ "Overriding China SKU answer to %{public}@ due to the %{public}@ internal user default."
+ "RegionCode"
+ "STForceChinaSKU"
+ "com.apple.GenerativePlaygroundApp"
+ "com.apple.Posters.ImagePlaygroundPosterApp"
```
