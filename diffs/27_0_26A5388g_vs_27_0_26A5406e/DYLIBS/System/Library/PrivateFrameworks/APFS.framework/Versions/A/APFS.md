## APFS

> `/System/Library/PrivateFrameworks/APFS.framework/Versions/A/APFS`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH.__data`
- `__DATA.__data`

```diff

-3283.0.13.501.1
+3288.1.3.0.0
   __TEXT.__text: 0x57140
   __TEXT.__const: 0x8540
-  __TEXT.__cstring: 0xeae1
+  __TEXT.__cstring: 0xeada
   __TEXT.__oslogstring: 0x1467
   __TEXT.__gcc_except_tab: 0x1c
   __TEXT.__unwind_info: 0xa30
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6Jiwtr/Sources/apfs_framework/nx/obj.c"
+ "3288.1.3"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.t9k12f/Sources/apfs_framework/nx/obj.c"
- "3283.0.13.501.1"
```
