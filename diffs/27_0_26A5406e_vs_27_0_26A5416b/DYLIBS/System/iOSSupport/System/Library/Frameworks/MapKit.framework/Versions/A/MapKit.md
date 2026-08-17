## MapKit

> `/System/iOSSupport/System/Library/Frameworks/MapKit.framework/Versions/A/MapKit`

```diff

-2552.20.6.12.11
-  __TEXT.__text: 0x25b1fc
+2552.20.6.12.13
+  __TEXT.__text: 0x25b1e8
   __TEXT.__objc_methlist: 0x26984
   __TEXT.__const: 0x69a0
   __TEXT.__dlopen_cstrs: 0x62

   __TEXT.__swift_as_entry: 0x13c
   __TEXT.__swift_as_ret: 0x134
   __TEXT.__swift_as_cont: 0x1cc
-  __TEXT.__gcc_except_tab: 0x605c
+  __TEXT.__gcc_except_tab: 0x6060
   __TEXT.__ustring: 0x19c
   __TEXT.__unwind_info: 0xa078
   __TEXT.__eh_frame: 0x241c
Symbols:
+ +[MKPolygon _polygonWithCoordinates:count:interiorPolygons:vectorOverlayStyle:]
+ GCC_except_table9844
+ GCC_except_table9848
+ _objc_msgSend$_polygonWithCoordinates:count:interiorPolygons:vectorOverlayStyle:
- -[MKPolygon _initWithCoordinates:count:interiorPolygons:vectorOverlayStyle:]
- GCC_except_table9842
- GCC_except_table9847
- _objc_msgSend$_initWithCoordinates:count:interiorPolygons:vectorOverlayStyle:
Functions:
~ -[MKPolygon _initWithCoordinates:count:interiorPolygons:vectorOverlayStyle:] -> +[MKPolygon _polygonWithCoordinates:count:interiorPolygons:vectorOverlayStyle:] : 256 -> 244
~ +[MKPolygon polygonWithCoordinates:count:] : 80 -> 72
```
