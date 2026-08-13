## PrintKitUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/PrintKitUI.framework/Versions/A/PrintKitUI`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_doubleobj`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH.__objc_data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-93.0.0.0.0
-  __TEXT.__text: 0x1df98
+96.3.0.0.0
+  __TEXT.__text: 0x1df5c
   __TEXT.__objc_methlist: 0x239c
   __TEXT.__const: 0x238
   __TEXT.__cstring: 0xdc0
-  __TEXT.__gcc_except_tab: 0xaac
+  __TEXT.__gcc_except_tab: 0xa8c
   __TEXT.__ustring: 0x8
-  __TEXT.__unwind_info: 0x828
+  __TEXT.__unwind_info: 0x820
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x528
+  __DATA_CONST.__const: 0x500
   __DATA_CONST.__objc_classlist: 0xc0
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x38

   - /System/Library/PrivateFrameworks/PrintKit.framework/Versions/A/PrintKit
   - /System/Library/PrivateFrameworks/UIKitMacHelper.framework/Versions/A/UIKitMacHelper
   - /System/iOSSupport/System/Library/Frameworks/PDFKit.framework/Versions/A/PDFKit
+  - /System/iOSSupport/System/Library/Frameworks/UIKit.framework/UIKit
   - /System/iOSSupport/System/Library/PrivateFrameworks/UIKitCore.framework/Versions/A/UIKitCore
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 773
-  Symbols:   2247
+  Symbols:   2245
   CStrings:  148
 
Symbols:
- GCC_except_table115
- ___block_descriptor_48_e8_32s40w_e5_v8?0lw40l8s32l8
Functions:
~ -[UIPrintInteractionController _updatePrintPaper] : 412 -> 392
~ -[UIPrintInteractionController _printPageWithDelay:] : 216 -> 204
~ -[UIPrintPageRenderer _drawPageAtIndex:withScale:drawingToPDF:] : 264 -> 236
```
