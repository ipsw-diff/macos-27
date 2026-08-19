## AppKit

> `/System/Library/Frameworks/AppKit.framework/Versions/C/AppKit`

```diff

-2775.0.0.0.0
-  __TEXT.__text: 0x129829c
-  __TEXT.__objc_methlist: 0xe6210
+2775.10.103.0.0
+  __TEXT.__text: 0x1297ff8
+  __TEXT.__objc_methlist: 0xe61c8
   __TEXT.__const: 0x36d98
   __TEXT.__dlopen_cstrs: 0x1a51
-  __TEXT.__cstring: 0xccc1b
+  __TEXT.__cstring: 0xcccdd
   __TEXT.__swift5_typeref: 0x13ca2
-  __TEXT.__swift5_reflstr: 0xc6f8
+  __TEXT.__swift5_reflstr: 0xc6b8
   __TEXT.__swift5_assocty: 0x3918
-  __TEXT.__constg_swiftt: 0x159c8
-  __TEXT.__swift5_fieldmd: 0xe6b0
+  __TEXT.__constg_swiftt: 0x159b0
+  __TEXT.__swift5_fieldmd: 0xe698
   __TEXT.__swift5_builtin: 0xbf4
   __TEXT.__swift5_proto: 0x1f78
   __TEXT.__swift5_types: 0x12a8
   __TEXT.__swift5_capture: 0x4ee0
   __TEXT.__swift5_protos: 0x1c0
-  __TEXT.__gcc_except_tab: 0xd1af8
+  __TEXT.__gcc_except_tab: 0xd1b18
   __TEXT.__swift5_mpenum: 0xb0
   __TEXT.__oslogstring: 0x25e73
   __TEXT.__swift_as_entry: 0x154

   __TEXT.__dof_NSTrackin: 0x7e7
   __TEXT.__dof_NSApplica: 0x809
   __TEXT.__dof_NSAccessi: 0x1eb
-  __TEXT.__unwind_info: 0x66390
+  __TEXT.__unwind_info: 0x66388
   __TEXT.__eh_frame: 0x7ea4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xb9a0
+  __DATA_CONST.__const: 0xb9c0
   __DATA_CONST.__objc_classlist: 0x5540
   __DATA_CONST.__objc_nlclslist: 0x20
   __DATA_CONST.__objc_catlist: 0x228
   __DATA_CONST.__objc_protolist: 0x1580
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x55720
+  __DATA_CONST.__objc_selrefs: 0x55708
   __DATA_CONST.__objc_protorefs: 0x880
   __DATA_CONST.__objc_superrefs: 0x4118
   __DATA_CONST.__objc_arraydata: 0x5220
-  __DATA_CONST.__got: 0x6b80
-  __AUTH_CONST.__const: 0x50768
-  __AUTH_CONST.__cfstring: 0xa01c0
-  __AUTH_CONST.__objc_const: 0x11f570
+  __DATA_CONST.__got: 0x6b88
+  __AUTH_CONST.__const: 0x50760
+  __AUTH_CONST.__cfstring: 0xa0200
+  __AUTH_CONST.__objc_const: 0x11f4a0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x2eb0
   __AUTH_CONST.__objc_dictobj: 0x820

   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x3bf80
   __DATA.__common: 0x15ab
-  __DATA_DIRTY.__objc_ivar: 0x48b4
-  __DATA_DIRTY.__objc_data: 0xb6c8
+  __DATA_DIRTY.__objc_ivar: 0x48a0
+  __DATA_DIRTY.__objc_data: 0xb688
   __DATA_DIRTY.__data: 0x3820
   __DATA_DIRTY.__common: 0x1d0
   __DATA_DIRTY.__bss: 0x8360

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 107367
-  Symbols:   166251
-  CStrings:  27591
+  Functions: 107360
+  Symbols:   166247
+  CStrings:  27595
 
Symbols:
+ +[NSMenuUtils revealedBarBoundsOnSpace:]
+ -[NSColorPanel _setColor:skipIfTracking:]
+ -[_NSSliderTrackingPanGestureRecognizer _shouldReceiveTouch:]
+ ___55+[NSMenuBarPresentationInstance _activeDisplayChanged:]_block_invoke
+ ___61-[NSPopupMenuWindow _orderFrontWithParentWindow:screenFrame:]_block_invoke
+ ___block_descriptor_40_e39_v16?0"NSMenuBarPresentationInstance"8l
+ ___block_descriptor_50_ea8_32s40s_e5_v8?0l
+ _objc_msgSend$_setColor:skipIfTracking:
+ _objc_msgSend$revealedBarBoundsOnSpace:
+ _objc_msgSend$withHostContextInvoke:
- -[NSColorPanel applyingColorFromTrackedControl]
- -[NSColorPanel setApplyingColorFromTrackedControl:]
- -[NSTextFieldCell _invalidateCachedCellSizes]
- -[NSTextFieldCell _invalidateContent]
- -[NSTextFieldCell _naturalCellSize]
- -[NSTextFieldCell _titleWrapsToMultipleLinesForWidth:]
- -[_NSThemeWidget didChangeValueForKey:]
- -[_NSThemeWidgetCell wantsUpdateLayerInView:]
- ___block_descriptor_48_e8_32o40o_e47_v24?0"NSTitlebarAccessoryViewController"8^B16l
- _objc_msgSend$_invalidateCachedCellSizes
- _objc_msgSend$_invalidateContent
- _objc_msgSend$_naturalCellSize
- _objc_msgSend$_titleWrapsToMultipleLinesForWidth:
- _objc_msgSend$setApplyingColorFromTrackedControl:
CStrings:
+ "CGDirectDisplayID _NSDisplayForActiveMenuBar(void)"
+ "NSMenuUtils.m"
+ "This implementation assumes spacePerDisplay=NO."
+ "_NSDisplayForActiveMenuBar may not work correctly for spaces-span-displays mode."
```
