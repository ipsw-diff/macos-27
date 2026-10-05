## ScreenTimeCore

> `/System/Library/PrivateFrameworks/ScreenTimeCore.framework/Versions/A/ScreenTimeCore`

```diff

-655.1.9.1.0
-  __TEXT.__text: 0x101ecc
-  __TEXT.__objc_methlist: 0xa3e8
+655.1.12.0.0
+  __TEXT.__text: 0x102430
+  __TEXT.__objc_methlist: 0xa438
   __TEXT.__const: 0x3538
-  __TEXT.__cstring: 0xa7fc
-  __TEXT.__oslogstring: 0xc1ea
-  __TEXT.__gcc_except_tab: 0x1b14
+  __TEXT.__cstring: 0xa80c
+  __TEXT.__oslogstring: 0xc29a
+  __TEXT.__gcc_except_tab: 0x1b44
   __TEXT.__constg_swiftt: 0xe00
   __TEXT.__swift5_typeref: 0x1600
   __TEXT.__swift5_builtin: 0xf0

   __TEXT.__swift_as_ret: 0x1d0
   __TEXT.__swift_as_cont: 0x274
   __TEXT.__swift5_mpenum: 0x18
-  __TEXT.__unwind_info: 0x5590
+  __TEXT.__unwind_info: 0x55b0
   __TEXT.__eh_frame: 0x46dc
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0x240
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5420
+  __DATA_CONST.__objc_selrefs: 0x5450
   __DATA_CONST.__objc_protorefs: 0x138
   __DATA_CONST.__objc_superrefs: 0x4d8
   __DATA_CONST.__objc_arraydata: 0x250
   __DATA_CONST.__got: 0xe40
   __AUTH_CONST.__const: 0x4ff8
-  __AUTH_CONST.__cfstring: 0x99a0
-  __AUTH_CONST.__objc_const: 0x134b8
+  __AUTH_CONST.__cfstring: 0x99c0
+  __AUTH_CONST.__objc_const: 0x13500
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_arrayobj: 0x180

   __AUTH_CONST.__auth_got: 0x11a8
   __AUTH.__objc_data: 0x3248
   __AUTH.__data: 0x4f8
-  __DATA.__objc_ivar: 0x7c4
+  __DATA.__objc_ivar: 0x7c8
   __DATA.__data: 0x21b0
   __DATA.__bss: 0x3f00
   __DATA.__common: 0xd0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6112
-  Symbols:   8877
-  CStrings:  2280
+  Functions: 6119
+  Symbols:   8889
+  CStrings:  2282
 
Symbols:
+ -[STAppInfoCache isMigratedToNewScreenTime]
+ -[STConversation _allHandlesAreManagingParents:]
+ -[STConversation _isManagingParentHandle:]
+ -[STConversation allowableByContactsHandles:allowingManagingParentsWhenBlocked:]
+ -[STConversationContext allowsManagingParentsWhenBlocked]
+ -[STConversationContext setAllowsManagingParentsWhenBlocked:]
+ -[STConversationContext updateShouldBeAllowedDuringGeneralScreenTime:shouldBeAllowedByScreenTimeWhenLimited:shouldBeAllowedWhenBlocked:currentApplicationState:emergencyModeEnabled:]
+ GCC_except_table29
+ GCC_except_table39
+ GCC_except_table56
+ GCC_except_table57
+ GCC_except_table62
+ GCC_except_table73
+ GCC_except_table81
+ OBJC_IVAR_$_STConversationContext._allowsManagingParentsWhenBlocked
+ _STDisplayableBundleIdentifiers
+ _objc_msgSend$_allHandlesAreManagingParents:
+ _objc_msgSend$_isManagingParentHandle:
+ _objc_msgSend$allowableByContactsHandles:
+ _objc_msgSend$allowsManagingParentsWhenBlocked
+ _objc_msgSend$setAllowsManagingParentsWhenBlocked:
+ _objc_msgSend$updateShouldBeAllowedDuringGeneralScreenTime:shouldBeAllowedByScreenTimeWhenLimited:shouldBeAllowedWhenBlocked:currentApplicationState:emergencyModeEnabled:
- -[STConversationContext updateShouldBeAllowedDuringGeneralScreenTime:shouldBeAllowedByScreenTimeWhenLimited:currentApplicationState:emergencyModeEnabled:]
- GCC_except_table24
- GCC_except_table27
- GCC_except_table33
- GCC_except_table54
- GCC_except_table61
- GCC_except_table70
- GCC_except_table77
- GCC_except_table80
- _objc_msgSend$updateShouldBeAllowedDuringGeneralScreenTime:shouldBeAllowedByScreenTimeWhenLimited:currentApplicationState:emergencyModeEnabled:
CStrings:
+ "Requested %{public}@ context allowing managing parents when blocked for handles:%{private}@. currentApplicationState:%lu allowedByScreenTime:%d managingParentAppleIDs:%{private}@"
+ "com.apple.SiriApp"
```
