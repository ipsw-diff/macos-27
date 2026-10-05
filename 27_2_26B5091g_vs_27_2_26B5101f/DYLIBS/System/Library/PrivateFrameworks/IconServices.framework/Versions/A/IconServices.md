## IconServices

> `/System/Library/PrivateFrameworks/IconServices.framework/Versions/A/IconServices`

```diff

-793.1.7.0.0
-  __TEXT.__text: 0x808ec
+793.1.10.0.0
+  __TEXT.__text: 0x81190
   __TEXT.__delay_stubs: 0x80
   __TEXT.__delay_helper: 0xa4
-  __TEXT.__objc_methlist: 0x7924
-  __TEXT.__cstring: 0x55e6
-  __TEXT.__const: 0x9570
+  __TEXT.__objc_methlist: 0x79cc
+  __TEXT.__cstring: 0x55f9
+  __TEXT.__const: 0x96b0
   __TEXT.__oslogstring: 0x4030
   __TEXT.__gcc_except_tab: 0x96c
-  __TEXT.__unwind_info: 0x2580
+  __TEXT.__unwind_info: 0x25b0
   __TEXT.__eh_frame: 0x88
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x6f0
-  __DATA_CONST.__objc_classlist: 0x5c8
+  __DATA_CONST.__objc_classlist: 0x5d0
   __DATA_CONST.__objc_catlist: 0xe8
   __DATA_CONST.__objc_protolist: 0x148
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3818
+  __DATA_CONST.__objc_selrefs: 0x3880
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x488
+  __DATA_CONST.__objc_superrefs: 0x490
   __DATA_CONST.__objc_arraydata: 0xb0
-  __DATA_CONST.__got: 0x848
+  __DATA_CONST.__got: 0x850
   __AUTH_CONST.__const: 0x1b68
-  __AUTH_CONST.__cfstring: 0x5fa0
-  __AUTH_CONST.__objc_const: 0x16b98
+  __AUTH_CONST.__cfstring: 0x5fc0
+  __AUTH_CONST.__objc_const: 0x16cc0
   __AUTH_CONST.__weak_auth_got: 0x10
-  __AUTH_CONST.__objc_intobj: 0x6a8
+  __AUTH_CONST.__objc_intobj: 0x6c0
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__auth_got: 0xb48
-  __AUTH.__objc_data: 0x500
+  __AUTH_CONST.__auth_got: 0xb60
+  __AUTH.__objc_data: 0x550
   __AUTH.__data: 0x8
-  __DATA.__objc_ivar: 0x79c
+  __DATA.__objc_ivar: 0x7a8
   __DATA.__data: 0x211c
   __DATA.__bss: 0x738
   __DATA_DIRTY.__objc_data: 0x34d0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3058
-  Symbols:   7348
-  CStrings:  1301
+  Functions: 3074
+  Symbols:   7392
+  CStrings:  1302
 
Symbols:
+ +[OKLChColor cuspLightnessAtHue:]
+ +[OKLChColor maxChromaAtLightness:hue:]
+ -[OKLChColor chroma]
+ -[OKLChColor convertToSRGBRed:green:blue:]
+ -[OKLChColor hue]
+ -[OKLChColor ifColor]
+ -[OKLChColor initFromIFColor:]
+ -[OKLChColor initWithLightness:chroma:hue:]
+ -[OKLChColor initWithSRGBRed:green:blue:]
+ -[OKLChColor lightness]
+ -[OKLChColor setChroma:]
+ -[OKLChColor setHue:]
+ -[OKLChColor setLightness:]
+ -[OKLChColor(FolderAdjustment) adjustForFolder]
+ OBJC_IVAR_$_OKLChColor._chroma
+ OBJC_IVAR_$_OKLChColor._hue
+ OBJC_IVAR_$_OKLChColor._lightness
+ _OBJC_CLASS_$_OKLChColor
+ _OBJC_METACLASS_$_OKLChColor
+ __OBJC_$_CLASS_METHODS_OKLChColor
+ __OBJC_$_INSTANCE_METHODS_OKLChColor(FolderAdjustment)
+ __OBJC_$_INSTANCE_VARIABLES_OKLChColor
+ __OBJC_$_PROP_LIST_OKLChColor
+ __OBJC_CLASS_RO_$_OKLChColor
+ __OBJC_METACLASS_RO_$_OKLChColor
+ _atan2
+ _cbrt
+ _hypot
+ _maxChroma
+ _objc_msgSend$adjustForFolder
+ _objc_msgSend$chroma
+ _objc_msgSend$convertToSRGBRed:green:blue:
+ _objc_msgSend$cuspLightnessAtHue:
+ _objc_msgSend$hue
+ _objc_msgSend$ifColor
+ _objc_msgSend$initFromIFColor:
+ _objc_msgSend$initWithLightness:chroma:hue:
+ _objc_msgSend$initWithSRGBRed:green:blue:
+ _objc_msgSend$lightness
+ _objc_msgSend$maxChromaAtLightness:hue:
+ _objc_msgSend$setChroma:
+ _objc_msgSend$setHue:
+ _objc_msgSend$setLightness:
+ _okLabToLinearSRGB
CStrings:
+ "badge_pointerarrow"
```
