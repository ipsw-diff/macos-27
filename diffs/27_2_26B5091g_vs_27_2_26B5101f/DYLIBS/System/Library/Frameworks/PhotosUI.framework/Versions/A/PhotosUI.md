## PhotosUI

> `/System/Library/Frameworks/PhotosUI.framework/Versions/A/PhotosUI`

```diff

-916.45.110.0.0
-  __TEXT.__text: 0x50734
-  __TEXT.__objc_methlist: 0x4ccc
+916.53.100.0.0
+  __TEXT.__text: 0x511ac
+  __TEXT.__objc_methlist: 0x4d8c
   __TEXT.__const: 0x3088
-  __TEXT.__oslogstring: 0xf48
+  __TEXT.__oslogstring: 0x1135
   __TEXT.__swift5_typeref: 0xe08
   __TEXT.__swift5_fieldmd: 0xafc
   __TEXT.__constg_swiftt: 0xc34
   __TEXT.__swift5_builtin: 0x154
   __TEXT.__swift5_reflstr: 0xae1
   __TEXT.__swift5_assocty: 0x348
-  __TEXT.__cstring: 0x5b39
+  __TEXT.__cstring: 0x5b75
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_proto: 0x1a0
   __TEXT.__swift5_types: 0xf8

   __TEXT.__swift_as_ret: 0x8
   __TEXT.__gcc_except_tab: 0x2cc
   __TEXT.__ustring: 0xd8
-  __TEXT.__unwind_info: 0x2558
+  __TEXT.__unwind_info: 0x2588
   __TEXT.__eh_frame: 0xef8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x7d8
-  __DATA_CONST.__objc_classlist: 0x2c8
+  __DATA_CONST.__objc_classlist: 0x2d0
   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x190
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2758
+  __DATA_CONST.__objc_selrefs: 0x27c0
   __DATA_CONST.__objc_protorefs: 0xf0
-  __DATA_CONST.__objc_superrefs: 0x188
+  __DATA_CONST.__objc_superrefs: 0x190
   __DATA_CONST.__objc_arraydata: 0x28
-  __DATA_CONST.__got: 0x658
-  __AUTH_CONST.__const: 0x3530
-  __AUTH_CONST.__cfstring: 0x3100
-  __AUTH_CONST.__objc_const: 0x9160
+  __DATA_CONST.__got: 0x670
+  __AUTH_CONST.__const: 0x3550
+  __AUTH_CONST.__cfstring: 0x31a0
+  __AUTH_CONST.__objc_const: 0x9370
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH_CONST.__auth_got: 0x840
-  __AUTH.__objc_data: 0x2288
+  __AUTH_CONST.__auth_got: 0x8f0
+  __AUTH.__objc_data: 0x22d8
   __AUTH.__data: 0x558
-  __DATA.__objc_ivar: 0x438
+  __DATA.__objc_ivar: 0x458
   __DATA.__data: 0x1880
   __DATA.__common: 0x178
-  __DATA.__bss: 0x3300
+  __DATA.__bss: 0x3310
   __DATA_DIRTY.__objc_data: 0x430
   __DATA_DIRTY.__data: 0xe8
   __DATA_DIRTY.__bss: 0x200

   - /System/Library/Frameworks/CoreMedia.framework/Versions/A/CoreMedia
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
+  - /System/Library/Frameworks/IOSurface.framework/Versions/A/IOSurface
   - /System/Library/Frameworks/Photos.framework/Versions/A/Photos
   - /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3479
-  Symbols:   4422
-  CStrings:  670
+  Functions: 3493
+  Symbols:   4487
+  CStrings:  683
 
Symbols:
+ +[PVSAdjustedImageSurface supportsSecureCoding]
+ -[PVSAdjustedImageSurface .cxx_destruct]
+ -[PVSAdjustedImageSurface allocationSize]
+ -[PVSAdjustedImageSurface createImage]
+ -[PVSAdjustedImageSurface dealloc]
+ -[PVSAdjustedImageSurface encodeWithCoder:]
+ -[PVSAdjustedImageSurface height]
+ -[PVSAdjustedImageSurface holdSurfaceInUse]
+ -[PVSAdjustedImageSurface initWithCoder:]
+ -[PVSAdjustedImageSurface initWithImage:]
+ -[PVSAdjustedImageSurface initWithSurface:width:height:bitsPerComponent:bitsPerPixel:bitmapInfo:colorSpaceData:]
+ -[PVSAdjustedImageSurface width]
+ GCC_except_table1170
+ GCC_except_table1183
+ GCC_except_table1188
+ GCC_except_table1191
+ GCC_except_table1271
+ GCC_except_table261
+ GCC_except_table288
+ GCC_except_table357
+ GCC_except_table554
+ GCC_except_table561
+ GCC_except_table569
+ GCC_except_table573
+ GCC_except_table773
+ OBJC_IVAR_$_PVSAdjustedImageSurface._bitmapInfo
+ OBJC_IVAR_$_PVSAdjustedImageSurface._bitsPerComponent
+ OBJC_IVAR_$_PVSAdjustedImageSurface._bitsPerPixel
+ OBJC_IVAR_$_PVSAdjustedImageSurface._colorSpaceData
+ OBJC_IVAR_$_PVSAdjustedImageSurface._height
+ OBJC_IVAR_$_PVSAdjustedImageSurface._holdsUseCount
+ OBJC_IVAR_$_PVSAdjustedImageSurface._surface
+ OBJC_IVAR_$_PVSAdjustedImageSurface._width
+ PVSAdjustedImageSurfaceLog.log
+ PVSAdjustedImageSurfaceLog.onceToken
+ _CFRelease
+ _CGColorSpaceCopyPropertyList
+ _CGColorSpaceCreateWithPropertyList
+ _CGColorSpaceRelease
+ _CGContextRelease
+ _CGIOSurfaceContextCreate
+ _CGIOSurfaceContextCreateImageReference
+ _CGImageGetBitmapInfo
+ _CGImageGetBitsPerComponent
+ _CGImageGetBitsPerPixel
+ _CGImageGetHeight
+ _CGImageGetImageProvider
+ _CGImageGetProperty
+ _CGImageGetWidth
+ _CGImageProviderCopyIOSurface
+ _IOSurfaceGetAllocSize
+ _IOSurfaceGetBytesPerElement
+ _IOSurfaceGetHeight
+ _IOSurfaceGetPlaneCount
+ _IOSurfaceGetWidth
+ _OBJC_CLASS_$_IOSurface
+ _OBJC_CLASS_$_NSPropertyListSerialization
+ _OBJC_CLASS_$_PVSAdjustedImageSurface
+ _OBJC_METACLASS_$_PVSAdjustedImageSurface
+ _PVSAdjustedImageSurfaceLog
+ __OBJC_$_CLASS_METHODS_PVSAdjustedImageSurface
+ __OBJC_$_CLASS_PROP_LIST_PVSAdjustedImageSurface
+ __OBJC_$_INSTANCE_METHODS_PVSAdjustedImageSurface
+ __OBJC_$_INSTANCE_VARIABLES_PVSAdjustedImageSurface
+ __OBJC_$_PROP_LIST_PVSAdjustedImageSurface
+ __OBJC_CLASS_PROTOCOLS_$_PVSAdjustedImageSurface
+ __OBJC_CLASS_RO_$_PVSAdjustedImageSurface
+ __OBJC_METACLASS_RO_$_PVSAdjustedImageSurface
+ ___PVSAdjustedImageSurfaceLog_block_invoke
+ __os_log_debug_impl
+ _kCGImagePropertyIOSurface
+ _objc_msgSend$dataWithPropertyList:format:options:error:
+ _objc_msgSend$decrementUseCount
+ _objc_msgSend$holdSurfaceInUse
+ _objc_msgSend$incrementUseCount
+ _objc_msgSend$initWithSurface:width:height:bitsPerComponent:bitsPerPixel:bitmapInfo:colorSpaceData:
+ _objc_msgSend$propertyListWithData:options:format:error:
+ _os_log_create
- GCC_except_table1156
- GCC_except_table1169
- GCC_except_table1174
- GCC_except_table1177
- GCC_except_table1257
- GCC_except_table247
- GCC_except_table274
- GCC_except_table343
- GCC_except_table540
- GCC_except_table547
- GCC_except_table555
- GCC_except_table559
- GCC_except_table759
CStrings:
+ "Adjusted image has no IOSurface behind it."
+ "Adjusted image has no color space that can be flattened for transport."
+ "Adjusted image is %ld bits per pixel but its surface is %zu bytes per element."
+ "Adjusted image is %ldx%ld but its surface is %zux%zu."
+ "Adjusted image reports %ld bits per component and %ld per pixel."
+ "Adjusted image's color space didn't survive transport."
+ "Adjusted image's surface has %zu planes."
+ "CoreGraphics won't read a %ldx%ld surface as %ld bits per pixel with bitmap info %u."
+ "bitmapInfo"
+ "bitsPerComponent"
+ "bitsPerPixel"
+ "colorSpace"
+ "surface"
```
