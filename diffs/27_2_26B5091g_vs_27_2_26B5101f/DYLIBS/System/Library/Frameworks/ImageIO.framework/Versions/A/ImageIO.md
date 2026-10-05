## ImageIO

> `/System/Library/Frameworks/ImageIO.framework/Versions/A/ImageIO`

```diff

-2851.1.5.0.0
-  __TEXT.__text: 0x3cc618
+2851.1.6.0.0
+  __TEXT.__text: 0x3cd314
   __TEXT.__objc_methlist: 0xd68
   __TEXT.__const: 0x2b620
-  __TEXT.__gcc_except_tab: 0x1d7d4
-  __TEXT.__cstring: 0x77ca5
+  __TEXT.__gcc_except_tab: 0x1d848
+  __TEXT.__cstring: 0x781a5
   __TEXT.__oslogstring: 0x17
   __TEXT.__constg_swiftt: 0x26a4
   __TEXT.__swift5_typeref: 0x3d88

   __TEXT.__swift_as_cont: 0x10
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__ustring: 0x30
-  __TEXT.__unwind_info: 0x14828
-  __TEXT.__eh_frame: 0x90cc
+  __TEXT.__unwind_info: 0x14848
+  __TEXT.__eh_frame: 0x90dc
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x47808
+  __DATA_CONST.__const: 0x47880
   __DATA_CONST.__objc_classlist: 0x60
   __DATA_CONST.__objc_protolist: 0x18
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_selrefs: 0xb08
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__objc_arraydata: 0x470
-  __DATA_CONST.__got: 0xaf0
-  __AUTH_CONST.__const: 0x4eec8
-  __AUTH_CONST.__cfstring: 0x35f60
+  __DATA_CONST.__got: 0xaf8
+  __AUTH_CONST.__const: 0x4efc0
+  __AUTH_CONST.__cfstring: 0x36060
   __AUTH_CONST.__objc_const: 0x11d0
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_intobj: 0x6d8
   __AUTH_CONST.__objc_floatobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x32a0
+  __AUTH_CONST.__auth_got: 0x32c0
   __AUTH.__objc_data: 0x370
   __AUTH.__data: 0x15c8
   __AUTH.__thread_vars: 0x18

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 19849
-  Symbols:   23067
-  CStrings:  15218
+  Functions: 19862
+  Symbols:   23084
+  CStrings:  15246
 
Symbols:
+ _CGColorSpaceContainsISO5Metadata
+ _CGImageGetContentAverageLightLevelNits
+ _ColorSyncProfileGetContentHeadroom
+ _ColorSyncProfileGetISO5AverageLightLevel
+ _IIO_CreateISO5MetadataInfo
+ _ZN15KTX2WritePlugin8writeOneEP25IIOImagePixelDataProviderP13IIODictionaryS3_j
+ __ZL21IIO_ApplyCheckNonZeroPKvS0_Pv
+ __ZL24IIO_CreateNeutralISO5KeyPK10__CFString
+ __ZL25IIO_ApplyNeutralISO5EntryPKvS0_Pv
+ __ZL29IIO_ApplyNeutralISO5KeyRenamePKvS0_Pv
+ __ZN10IIO_Reader19updateImageAVLLNitsEP7CGImageP19IIOImageReadSessionP12CGColorSpace20CGImageComponentTypej
+ __ZN15IIO_Reader_HEIF19updateImageAVLLNitsEP7CGImageP19IIOImageReadSessionP12CGColorSpace20CGImageComponentTypej
+ _iptc_AIPromptInformation
+ _iptc_AIPromptWriterName
+ _kCGImagePropertyIPTCExtAIPromptInformation
+ _kCGImagePropertyIPTCExtAIPromptWriterName
+ _kColorSyncDerivedISO5Metadata
+ _kIIOICCISO5MetadataPropertyKey
- _ZN12IIOImagePlus11setGeometryEPv19CGImagePlusGeometry
CStrings:
+ "*** BMP - writePrefix failed, not writing pixel data\n"
+ "*** ERROR: CFURLCreateWithFileSystemPath returned nil.\n"
+ "*** ERROR: CGImageReadCreateWithURL returned nil.\n"
+ "*** ERROR: could not create the image reader for the given path.\n"
+ "*** ERROR: decodeStripPlanar destination row is %u bytes, the scatter needs %llu\n"
+ "*** ERROR: decodeTilePlanar destination row is %u bytes, the scatter needs %llu\n"
+ "*** ERROR: failed to read %zu bytes of pixel data for 420f\n"
+ "*** ERROR: updateTiffStruct failed after the codec data format was set\n"
+ "*** can't write KTX - failed to read %zu bytes of pixel data\n"
+ "*** can't write KTX - unsupported image size (%u x %u, rowBytes %zu)\n"
+ "*** can't write KTX2 - bad image size (%zu x %zu)\n"
+ "*** can't write KTX2 - failed to read %zu bytes of pixel data\n"
+ "*** failed to read %zu bytes of pixel data\n"
+ "AIPromptInformation"
+ "AIPromptWriterName"
+ "AverageLightLevelNits"
+ "ColorPrimaries"
+ "MetadataDisplayName"
+ "Primaries"
+ "com.apple.cmm."
+ "decodeStripPlanar"
+ "ico image %zu: %zu bytes is too small for a BITMAPINFOHEADER\n"
+ "ico image %zu: header %u + pixels %zu + mask %zu exceeds %zu bytes\n"
+ "updateImageAVLLNits"
+ "write420fData"
+ "{ICC ISO-5}"
+ "☀️  %s - failed to update image avll: %d  [colorspace: '%s']\n"
+ "☀️  %s - not setting image avll: %d for SDR [colorspace: '%s']\n"
+ "☀️  %s - updating image AVLL: %d [colorspace: '%s']\n"
- "CGImageReadCreateWithURL returned nil.\n"
```
