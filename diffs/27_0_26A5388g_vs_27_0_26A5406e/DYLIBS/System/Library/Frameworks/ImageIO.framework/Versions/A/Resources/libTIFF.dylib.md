## libTIFF.dylib

> `/System/Library/Frameworks/ImageIO.framework/Versions/A/Resources/libTIFF.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__DATA_DIRTY.__data`

```diff

-2847.1.0.0.0
-  __TEXT.__text: 0x3c2a4
+2851.0.0.0.0
+  __TEXT.__text: 0x3c2dc
   __TEXT.__const: 0x1a784
-  __TEXT.__cstring: 0x9749
+  __TEXT.__cstring: 0x97b4
   __TEXT.__unwind_info: 0x7a8
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x2f60

   - /usr/lib/libz.1.dylib
   Functions: 1006
   Symbols:   1069
-  CStrings:  1263
+  CStrings:  1265
 
Functions:
~ __TIFFGetStrileOffsetOrByteCountValue : 1404 -> 1412
~ _OJPEGPreDecode : 2284 -> 2300
~ _PixarLogEncode : 3820 -> 3852
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.tFtPZA/Sources/ImageIO/FileFormats/libTIFF/tif_dir.c"
+ "Inconsistent directory count between StripOffsets and StripByteCounts"
+ "_TIFFGetStrileOffsetOrByteCountValue"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.Oxl67Y/Sources/ImageIO/FileFormats/libTIFF/tif_dir.c"
```
