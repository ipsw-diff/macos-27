## AccessibilityVisuals

> `/System/Library/PrivateFrameworks/AccessibilitySupport.framework/Versions/A/Frameworks/AccessibilityVisuals.framework/Versions/A/AccessibilityVisuals`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-455.1.0.0.0
-  __TEXT.__text: 0x389dc
-  __TEXT.__objc_methlist: 0x6630
+455.1.3.0.0
+  __TEXT.__text: 0x39438
+  __TEXT.__objc_methlist: 0x66f8
   __TEXT.__const: 0x378
   __TEXT.__cstring: 0xd05
   __TEXT.__gcc_except_tab: 0x1d0
   __TEXT.__dlopen_cstrs: 0x5c
   __TEXT.__oslogstring: 0x403
   __TEXT.__ustring: 0x14
-  __TEXT.__unwind_info: 0x1490
+  __TEXT.__unwind_info: 0x14c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x148
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4440
+  __DATA_CONST.__objc_selrefs: 0x44c8
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x228
   __DATA_CONST.__objc_arraydata: 0x30
   __DATA_CONST.__got: 0x5c8
-  __AUTH_CONST.__const: 0x870
+  __AUTH_CONST.__const: 0x8b0
   __AUTH_CONST.__cfstring: 0x1480
-  __AUTH_CONST.__objc_const: 0xcc88
+  __AUTH_CONST.__objc_const: 0xcd38
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_doubleobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x510
   __AUTH.__objc_data: 0x11d0
-  __DATA.__objc_ivar: 0x6a0
+  __DATA.__objc_ivar: 0x6ac
   __DATA.__data: 0xfb0
-  __DATA.__bss: 0x148
+  __DATA.__bss: 0x168
   __DATA_DIRTY.__objc_data: 0x6e0
   __DATA_DIRTY.__bss: 0x58
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1929
-  Symbols:   5179
+  Functions: 1951
+  Symbols:   5219
   CStrings:  207
 
Symbols:
+ +[AXVBorderedZoomWindow _dragHandleFillColor]
+ +[AXVBorderedZoomWindow _dragHandleStrokeColor]
+ -[AXVBorderedZoomWindow _addDragHandleLayerToOverlayWindow:]
+ -[AXVBorderedZoomWindow _dragHandleCenterPoint]
+ -[AXVBorderedZoomWindow _dragHandleEdgeIsVertical]
+ -[AXVBorderedZoomWindow _dragHandleLayer]
+ -[AXVBorderedZoomWindow _dragHandleOffsetForEdge:]
+ -[AXVBorderedZoomWindow _syncBorderedLayerFrameToCurrentFrame]
+ -[AXVBorderedZoomWindow _updateDragHandleLayerGeometry]
+ -[AXVBorderedZoomWindow cornerResizeTargetsForLocation:]
+ -[AXVBorderedZoomWindow dragHandleEdge]
+ -[AXVBorderedZoomWindow locationIsOnDraggableBorder:]
+ -[AXVBorderedZoomWindow locationIsOnDraggableHandleEdge:]
+ -[AXVBorderedZoomWindow setDragHandleEdge:]
+ -[AXVBorderedZoomWindow setShowsDragHandle:]
+ -[AXVBorderedZoomWindow set_dragHandleLayer:]
+ -[AXVBorderedZoomWindow showsDragHandle]
+ OBJC_IVAR_$_AXVBorderedZoomWindow.__dragHandleLayer
+ OBJC_IVAR_$_AXVBorderedZoomWindow._dragHandleEdge
+ OBJC_IVAR_$_AXVBorderedZoomWindow._showsDragHandle
+ ___44-[AXVBorderedZoomWindow setShowsDragHandle:]_block_invoke
+ ___45+[AXVBorderedZoomWindow _dragHandleFillColor]_block_invoke
+ ___47+[AXVBorderedZoomWindow _dragHandleStrokeColor]_block_invoke
+ _dragHandleFillColor.__dragHandleFillColor
+ _dragHandleFillColor.once
+ _dragHandleStrokeColor.__dragHandleStrokeColor
+ _dragHandleStrokeColor.once
+ _objc_msgSend$_addDragHandleLayerToOverlayWindow:
+ _objc_msgSend$_dragHandleCenterPoint
+ _objc_msgSend$_dragHandleEdgeIsVertical
+ _objc_msgSend$_dragHandleFillColor
+ _objc_msgSend$_dragHandleLayer
+ _objc_msgSend$_dragHandleOffsetForEdge:
+ _objc_msgSend$_dragHandleStrokeColor
+ _objc_msgSend$_syncBorderedLayerFrameToCurrentFrame
+ _objc_msgSend$_updateDragHandleLayerGeometry
+ _objc_msgSend$dragHandleEdge
+ _objc_msgSend$locationIsOnDraggableBorder:
+ _objc_msgSend$set_dragHandleLayer:
+ _objc_msgSend$showsDragHandle
```
