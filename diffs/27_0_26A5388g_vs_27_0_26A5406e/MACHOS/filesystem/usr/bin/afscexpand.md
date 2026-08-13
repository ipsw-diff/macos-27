## afscexpand

> `/usr/bin/afscexpand`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`

```diff
Functions:
~ sub_100000fc0 : 2220 -> 2236
~ sub_100002cf4 -> sub_100002d04 : 332 -> 316
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.IhU5XM/Sources/AppleFSCompression_executables/Common/ChunkCompression.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.IhU5XM/Sources/AppleFSCompression_executables/Common/commonUtilsUser.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.IhU5XM/Sources/AppleFSCompression_executables/Libraries/CompressData/CompressData.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.qw0iSJ/Sources/AppleFSCompression_executables/Common/ChunkCompression.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.qw0iSJ/Sources/AppleFSCompression_executables/Common/commonUtilsUser.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.qw0iSJ/Sources/AppleFSCompression_executables/Libraries/CompressData/CompressData.c"
```
