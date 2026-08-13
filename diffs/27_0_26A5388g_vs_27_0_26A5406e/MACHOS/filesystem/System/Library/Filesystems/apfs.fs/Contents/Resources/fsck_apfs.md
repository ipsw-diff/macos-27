## fsck_apfs

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/fsck_apfs`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`
- `__DATA.__bss`

```diff

-3283.0.13.501.1
-  __TEXT.__text: 0x55ee4
+3288.1.3.0.0
+  __TEXT.__text: 0x56278
   __TEXT.__auth_stubs: 0xb90
-  __TEXT.__cstring: 0x1a75c
+  __TEXT.__cstring: 0x1a750
   __TEXT.__const: 0x8720
-  __TEXT.__unwind_info: 0xb98
+  __TEXT.__unwind_info: 0xbb0
   __DATA_CONST.__const: 0x620
   __DATA_CONST.__cfstring: 0x200
   __DATA_CONST.__auth_got: 0x5c8

   - /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libutil.dylib
-  Functions: 991
+  Functions: 994
   Symbols:   202
   CStrings:  1998
 
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.iN3TKM/Sources/AppleKeyStore_libs/aeskeywrap.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.iN3TKM/Sources/AppleKeyStore_libs/platform/platform.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.iN3TKM/Sources/AppleKeyStore_libs/platform/platform_lib.c"
+ "3288.1.3"
+ "The volume %s with UUID %s was found to have minor issues that can be repaired."
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.tSt0vh/Sources/AppleKeyStore_libs/aeskeywrap.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.tSt0vh/Sources/AppleKeyStore_libs/platform/platform.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.tSt0vh/Sources/AppleKeyStore_libs/platform/platform_lib.c"
- "3283.0.13.501.1"
- "The volume %s with UUID %s could not be verified completely and can not be repaired."
```
