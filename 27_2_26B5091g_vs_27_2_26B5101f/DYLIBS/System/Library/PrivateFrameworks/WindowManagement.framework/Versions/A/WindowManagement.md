## WindowManagement

> `/System/Library/PrivateFrameworks/WindowManagement.framework/Versions/A/WindowManagement`

```diff

-462.1.29.0.0
-  __TEXT.__text: 0x13410
-  __TEXT.__objc_methlist: 0x245c
+462.1.36.0.0
+  __TEXT.__text: 0x13b78
+  __TEXT.__objc_methlist: 0x254c
   __TEXT.__const: 0x3ba
   __TEXT.__gcc_except_tab: 0x74
-  __TEXT.__cstring: 0x1226
+  __TEXT.__cstring: 0x123a
   __TEXT.__oslogstring: 0x1be
   __TEXT.__swift5_typeref: 0x169
   __TEXT.__swift5_reflstr: 0x2d

   __TEXT.__swift5_fieldmd: 0xb4
   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_types: 0x18
-  __TEXT.__unwind_info: 0x928
+  __TEXT.__unwind_info: 0x960
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x150
-  __DATA_CONST.__objc_classlist: 0x130
+  __DATA_CONST.__objc_classlist: 0x138
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x40
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xfa0
+  __DATA_CONST.__objc_selrefs: 0xff8
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x100
+  __DATA_CONST.__objc_superrefs: 0x108
   __DATA_CONST.__objc_arraydata: 0xc0
-  __DATA_CONST.__got: 0x290
+  __DATA_CONST.__got: 0x298
   __AUTH_CONST.__const: 0x658
-  __AUTH_CONST.__cfstring: 0x1640
-  __AUTH_CONST.__objc_const: 0x47b0
+  __AUTH_CONST.__cfstring: 0x16e0
+  __AUTH_CONST.__objc_const: 0x49b0
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_arrayobj: 0x240
   __AUTH_CONST.__auth_got: 0x298
-  __AUTH.__objc_data: 0x5a0
-  __DATA.__objc_ivar: 0x31c
+  __AUTH.__objc_data: 0x5f0
+  __DATA.__objc_ivar: 0x334
   __DATA.__data: 0x300
   __DATA.__bss: 0x590
   __DATA_DIRTY.__objc_data: 0x640

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 851
-  Symbols:   1871
-  CStrings:  213
+  Functions: 870
+  Symbols:   1913
+  CStrings:  218
 
Symbols:
+ +[_WMCornerRadii supportsSecureCoding]
+ -[WMClientWindowManager refreshTilingConstraintsWithWindowIdentifier:reply:]
+ -[WMWindowPropertySnapshot cornerRadii]
+ -[WMWindowPropertySnapshot setCornerRadii:]
+ -[_WMCornerRadii copyWithZone:]
+ -[_WMCornerRadii encodeWithCoder:]
+ -[_WMCornerRadii hash]
+ -[_WMCornerRadii initWithCoder:]
+ -[_WMCornerRadii initWithMinXMinY:maxXMinY:minXMaxY:maxXMaxY:]
+ -[_WMCornerRadii initWithUniformRadius:]
+ -[_WMCornerRadii isEqual:]
+ -[_WMCornerRadii maxXMaxY]
+ -[_WMCornerRadii maxXMinY]
+ -[_WMCornerRadii minXMaxY]
+ -[_WMCornerRadii minXMinY]
+ -[_WMWindow cornerRadii]
+ -[_WMWindow setCornerRadii:]
+ GCC_except_table63
+ GCC_except_table64
+ GCC_except_table81
+ OBJC_IVAR_$_WMWindowPropertySnapshot._cornerRadii
+ OBJC_IVAR_$__WMCornerRadii._maxXMaxY
+ OBJC_IVAR_$__WMCornerRadii._maxXMinY
+ OBJC_IVAR_$__WMCornerRadii._minXMaxY
+ OBJC_IVAR_$__WMCornerRadii._minXMinY
+ OBJC_IVAR_$__WMWindow._cornerRadii
+ _OBJC_CLASS_$__WMCornerRadii
+ _OBJC_METACLASS_$__WMCornerRadii
+ __OBJC_$_CLASS_METHODS__WMCornerRadii
+ __OBJC_$_CLASS_PROP_LIST__WMCornerRadii
+ __OBJC_$_INSTANCE_METHODS__WMCornerRadii
+ __OBJC_$_INSTANCE_VARIABLES__WMCornerRadii
+ __OBJC_$_PROP_LIST__WMCornerRadii
+ __OBJC_CLASS_PROTOCOLS_$__WMCornerRadii
+ __OBJC_CLASS_RO_$__WMCornerRadii
+ __OBJC_METACLASS_RO_$__WMCornerRadii
+ ___28-[_WMWindow setCornerRadii:]_block_invoke
+ ___76-[WMClientWindowManager refreshTilingConstraintsWithWindowIdentifier:reply:]_block_invoke
+ _objc_msgSend$allocWithZone:
+ _objc_msgSend$clientWindowManager:refreshTilingConstraintsForWindowWithIdentifier:completion:
+ _objc_msgSend$cornerRadii
+ _objc_msgSend$hash
+ _objc_msgSend$initWithMinXMinY:maxXMinY:minXMaxY:maxXMaxY:
+ _objc_msgSend$initWithUniformRadius:
+ _objc_msgSend$setCornerRadii:
- GCC_except_table61
- GCC_except_table62
- GCC_except_table79
CStrings:
+ "bl"
+ "br"
+ "cradi"
+ "tl"
+ "tr"
```
