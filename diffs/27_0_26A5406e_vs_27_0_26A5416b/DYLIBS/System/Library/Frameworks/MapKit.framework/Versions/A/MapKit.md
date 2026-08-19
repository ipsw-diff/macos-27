## MapKit

> `/System/Library/Frameworks/MapKit.framework/Versions/A/MapKit`

```diff

-2552.20.6.12.11
-  __TEXT.__text: 0x21cb70
+2552.20.6.12.13
+  __TEXT.__text: 0x21cb5c
   __TEXT.__objc_methlist: 0x21e8c
   __TEXT.__const: 0x6578
   __TEXT.__dlopen_cstrs: 0x62

   __TEXT.__swift_as_entry: 0x13c
   __TEXT.__swift_as_ret: 0x134
   __TEXT.__swift_as_cont: 0x1cc
-  __TEXT.__gcc_except_tab: 0x46b0
+  __TEXT.__gcc_except_tab: 0x46b4
   __TEXT.__ustring: 0x156
   __TEXT.__unwind_info: 0x9080
   __TEXT.__eh_frame: 0x241c
Symbols:
+ +[MKPolygon _polygonWithCoordinates:count:interiorPolygons:vectorOverlayStyle:]
+ GCC_except_table7885
+ GCC_except_table7889
+ _objc_msgSend$_polygonWithCoordinates:count:interiorPolygons:vectorOverlayStyle:
- -[MKPolygon _initWithCoordinates:count:interiorPolygons:vectorOverlayStyle:]
- GCC_except_table7883
- GCC_except_table7888
- _objc_msgSend$_initWithCoordinates:count:interiorPolygons:vectorOverlayStyle:
Functions:
~ -[MKPolygon _initWithCoordinates:count:interiorPolygons:vectorOverlayStyle:] -> +[MKPolygon _polygonWithCoordinates:count:interiorPolygons:vectorOverlayStyle:] : 288 -> 276
~ +[MKPolygon polygonWithCoordinates:count:] : 80 -> 72
```
