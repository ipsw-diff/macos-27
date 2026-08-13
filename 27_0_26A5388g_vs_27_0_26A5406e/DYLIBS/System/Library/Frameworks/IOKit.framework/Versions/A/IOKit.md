## IOKit

> `/System/Library/Frameworks/IOKit.framework/Versions/A/IOKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__weak_got`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`
- `__DATA_DIRTY.__data`

```diff

-100288.0.8.0.0
-  __TEXT.__text: 0xbc320
+100288.0.9.0.0
+  __TEXT.__text: 0xbc2f8
   __TEXT.__objc_methlist: 0x150
-  __TEXT.__cstring: 0xf1e3
+  __TEXT.__cstring: 0xf208
   __TEXT.__const: 0x10610
   __TEXT.__dlopen_cstrs: 0x57
   __TEXT.__oslogstring: 0x564f
   __TEXT.__gcc_except_tab: 0x578
-  __TEXT.__unwind_info: 0x2668
+  __TEXT.__unwind_info: 0x2670
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2640
+  __DATA_CONST.__const: 0x2660
   __DATA_CONST.__objc_classlist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
   __DATA_CONST.__objc_selrefs: 0x40
   __DATA_CONST.__objc_superrefs: 0x38
   __DATA_CONST.__got: 0x210
-  __AUTH_CONST.__const: 0x27c0
-  __AUTH_CONST.__cfstring: 0x8280
+  __AUTH_CONST.__const: 0x27e0
+  __AUTH_CONST.__cfstring: 0x82a0
   __AUTH_CONST.__objc_const: 0x508
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__auth_got: 0x11c8

   __DATA.__common: 0x100
   __DATA_DIRTY.__objc_data: 0xa0
   __DATA_DIRTY.__data: 0xc0
-  __DATA_DIRTY.__bss: 0x218
+  __DATA_DIRTY.__bss: 0x228
   __DATA_DIRTY.__common: 0xc
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
   - /usr/lib/system/libkxld.dylib
-  Functions: 3895
-  Symbols:   4655
-  CStrings:  2979
+  Functions: 3894
+  Symbols:   4654
+  CStrings:  2980
 
Symbols:
+ ___IOHIDRequestAccess_block_invoke_2
- ___copy_helper_block_8_32r40r
- ___destroy_helper_block_8_32r40r
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.fsZkLG/Sources/IOAVFamily_user/IOAV.cpp"
+ "OSKEXT_BUILD_DATE 20:40:45 Aug  3 2026"
+ "_kTCCAccessRequestOptionSyncCallback"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OqfEDO/Sources/IOAVFamily_user/IOAV.cpp"
- "OSKEXT_BUILD_DATE 22:25:05 Jul 10 2026"
```
