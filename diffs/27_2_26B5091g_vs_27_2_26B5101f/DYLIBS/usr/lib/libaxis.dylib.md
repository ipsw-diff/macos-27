## libaxis.dylib

> `/usr/lib/libaxis.dylib`

```diff

-8.1.13.0.0
-  __TEXT.__text: 0x53670c
-  __TEXT.__gcc_except_tab: 0x4720c
-  __TEXT.__cstring: 0x172d3
-  __TEXT.__const: 0xf5b4
-  __TEXT.__unwind_info: 0x12210
+8.1.15.0.0
+  __TEXT.__text: 0x548864
+  __TEXT.__gcc_except_tab: 0x482d4
+  __TEXT.__cstring: 0x1818b
+  __TEXT.__const: 0xf5e4
+  __TEXT.__unwind_info: 0x124a8
   __TEXT.__eh_frame: 0x88
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0xc0

   __AUTH.__thread_data: 0x10
   __AUTH.__thread_bss: 0x180
   __DATA.__data: 0x1860
-  __DATA.__bss: 0x13ea8
+  __DATA.__bss: 0x13eb8
   __DATA.__common: 0x8
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 9853
+  Functions: 9930
   Symbols:   2774
-  CStrings:  1960
+  CStrings:  2078
 
Symbols:
+ __ZN5terra13GeoTIFFReader11read_memoryEPKhm
- __ZN5terra13GeoTIFFReader11read_memoryEPKh
CStrings:
+ " SHORT values, but holds only "
+ " and StripByteCounts holds "
+ " and a full strip holds "
+ " available"
+ " bytes"
+ " bytes available for that tag"
+ " bytes exceeds the "
+ " bytes from file: "
+ " bytes needed, "
+ " bytes remain"
+ " bytes remaining"
+ " bytes the raster needs"
+ " bytes where the "
+ " coordinates but only "
+ " declares "
+ " exceed the supported maximum"
+ " float raster cannot fit in "
+ " for a "
+ " has type "
+ " hex chars, have "
+ " input bytes"
+ " is out of range for this API"
+ " is supported"
+ " keys, which need "
+ " leaves no room for a coordinate delta"
+ " lies outside the input: offset "
+ " of the "
+ " origin "
+ " points but decoded "
+ " precision cannot be encoded, got "
+ " precision is not usable for decoding, got "
+ " raster"
+ " raster by pixel"
+ " row(s) it covers need "
+ " strips but StripOffsets holds "
+ " value(s)"
+ " value(s) at index "
+ " values, only a single sample per pixel is supported"
+ " where BYTE, SHORT or LONG is required"
+ " x "
+ " x ImageHeight "
+ ") has no value at index "
+ ") is missing"
+ ") value "
+ ", only "
+ ", only 32 is supported"
+ ", which holds only "
+ "-bit target type"
+ "-byte header: "
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AxisGeometry/src/axis/algorithm/AxisCompressionDecoder.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AxisGeometry/src/axis/algorithm/AxisCompressionEncoder.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AxisGeometry/src/axis/misc/BinaryConverters.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AxisGeometry/src/terra/algorithm/MeshCompression.cpp"
+ "; "
+ "ACF "
+ "BitsPerSample"
+ "Compression"
+ "GCL TriangleMeshDecoder: triangle count "
+ "GCL TriangleMeshDecoder: vertex count "
+ "GCL payload is shorter than its "
+ "GCL run declared "
+ "GeoAsciiParams"
+ "GeoDoubleParams"
+ "GeoKeyDirectory"
+ "GeoPixelScale"
+ "GeoTIFFReader: "
+ "GeoTIFFReader: BitsPerSample(258) holds "
+ "GeoTIFFReader: GeoKeyDirectory declares "
+ "GeoTIFFReader: GeoKeyDirectory must hold at least 4 SHORT values, got "
+ "GeoTIFFReader: RowsPerStrip(278) is 0, which describes no strip at all"
+ "GeoTIFFReader: a "
+ "GeoTIFFReader: cannot determine the size of file: "
+ "GeoTIFFReader: cannot open file: "
+ "GeoTIFFReader: empty raster: ImageWidth "
+ "GeoTIFFReader: geo key references "
+ "GeoTIFFReader: null input"
+ "GeoTIFFReader: raster dimensions "
+ "GeoTIFFReader: raster needs "
+ "GeoTIFFReader: read "
+ "GeoTIFFReader: required TIFF tag "
+ "GeoTIFFReader: strip "
+ "GeoTIFFReader: strips cover "
+ "GeoTIFFReader: tag "
+ "GeoTIFFReader: the tie point and pixel scale give a degenerate bounding box, extent "
+ "GeoTIFFReader: the tie point and pixel scale give an extent too large to address a "
+ "GeoTIFFReader: tiled GeoTIFF is not supported (TileWidth(322) is present); only strip layouts are read"
+ "GeoTIFFReader: unsupported "
+ "GeoTIFFReader: unsupported BitsPerSample(258) value "
+ "GeoTiePoints"
+ "ImageHeight"
+ "ImageWidth"
+ "IndexedGeometry::get_de9im()"
+ "PlanarConfiguration"
+ "RowsPerStrip"
+ "SampleFormat"
+ "SamplesPerPixel"
+ "StripByteCounts"
+ "StripOffsets"
+ "TIFF directory"
+ "TIFF directory entry"
+ "TIFF header"
+ "Truncated bytestream: "
+ "Truncated bytestream: ACF header is empty"
+ "Truncated bytestream: ACF header needs 3 bytes, found "
+ "Truncated bytestream: declared payload of "
+ "Truncated bytestream: payload declares "
+ "Truncated bytestream: varint continues past the end of the input"
+ "Unsupported number of tie points values (expected 6 DOUBLEs): "
+ "Unsupported pixel scale values (expect at least 2 DOUBLEs): "
+ "Unsupported pixel scale values (expect finite and positive): "
+ "Unsupported tie points values (expect a finite origin): "
+ "Varint is longer than its "
+ "Varint value does not fit its "
+ "WKBReader: truncated hex WKB, need "
+ "X"
+ "XY"
+ "Y"
+ "Z"
+ "data of strip "
+ "value of tag "
- "Truncated bytestream"
- "Unsupported number of tie points values (expected 6): "
```
