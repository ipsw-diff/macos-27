## diskimagespawner

> `/usr/libexec/diskimagespawner`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-598.0.0.0.0
+598.0.1.0.0
   __TEXT.__text: 0x24f5c
   __TEXT.__auth_stubs: 0xa50
   __TEXT.__objc_stubs: 0x760
CStrings:
+ "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.CCoaOu/Sources/DiskImages2/app/backends/sg_vec.cpp:455:28)]"
+ "ssize_t transform(Fn &&, sg_vec_ref::iterator, const sg_vec_ref::iterator &, sg_vec_ref::iterator) [Fn = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.CCoaOu/Sources/DiskImages2/app/utils.cpp:179:13)]"
- "io_result_t details::for_each_sg_in_vec_internal(Fn &&, sg_vec_ref::iterator, sg_vec::iterator, size_t, bool) [Fn = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ujPbJ8/Sources/DiskImages2/app/backends/sg_vec.cpp:455:28)]"
- "ssize_t transform(Fn &&, sg_vec_ref::iterator, const sg_vec_ref::iterator &, sg_vec_ref::iterator) [Fn = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ujPbJ8/Sources/DiskImages2/app/utils.cpp:179:13)]"
```
