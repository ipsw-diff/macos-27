## apfs_shrink_diskimage

> `/System/Library/Filesystems/apfs.fs/Contents/Resources/apfs_shrink_diskimage`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__data`

```diff

-3283.0.13.501.1
-  __TEXT.__text: 0x59884
+3288.1.3.0.0
+  __TEXT.__text: 0x598c0
   __TEXT.__auth_stubs: 0x7e0
   __TEXT.__cstring: 0x12f3c
   __TEXT.__const: 0x230
Functions:
~ sub_100010a2c : 488 -> 524
~ sub_100019d7c -> sub_100019da0 : 516 -> 512
~ sub_100023334 -> sub_100023354 : 492 -> 520
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8xHb0Q/Sources/apfs_executables/nx/jobj.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8xHb0Q/Sources/apfs_executables/nx/nx.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8xHb0Q/Sources/apfs_executables/nx/obj.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.XQJT3Z/Sources/apfs_executables/nx/jobj.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.XQJT3Z/Sources/apfs_executables/nx/nx.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.XQJT3Z/Sources/apfs_executables/nx/obj.c"
```
