## PencilKit

> `/System/iOSSupport/System/Library/Frameworks/PencilKit.framework/Versions/A/PencilKit`

```diff

-621.0.0.0.0
-  __TEXT.__text: 0x31aa60
-  __TEXT.__objc_methlist: 0x2e53c
-  __TEXT.__const: 0x8a94
+622.1.1.0.0
+  __TEXT.__text: 0x31a4ac
+  __TEXT.__objc_methlist: 0x2e59c
+  __TEXT.__const: 0x8aa4
   __TEXT.__dlopen_cstrs: 0x351
   __TEXT.__constg_swiftt: 0x1d40
   __TEXT.__swift5_typeref: 0x1e02

   __TEXT.__swift5_assocty: 0x6e0
   __TEXT.__swift5_proto: 0x388
   __TEXT.__swift5_types: 0x1c0
-  __TEXT.__cstring: 0xc93a
+  __TEXT.__cstring: 0xc95e
   __TEXT.__swift5_capture: 0xa30
-  __TEXT.__oslogstring: 0xca71
+  __TEXT.__oslogstring: 0xc9fd
   __TEXT.__swift_as_entry: 0xf0
   __TEXT.__swift_as_cont: 0x218
   __TEXT.__swift_as_ret: 0xac
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x26138
+  __TEXT.__gcc_except_tab: 0x261b4
   __TEXT.__ustring: 0x23a
-  __TEXT.__unwind_info: 0x12cc0
+  __TEXT.__unwind_info: 0x12c88
   __TEXT.__eh_frame: 0x2af8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x6860
+  __DATA_CONST.__const: 0x6838
   __DATA_CONST.__objc_classlist: 0x1018
   __DATA_CONST.__objc_catlist: 0x88
-  __DATA_CONST.__objc_protolist: 0x770
+  __DATA_CONST.__objc_protolist: 0x778
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x17ec8
+  __DATA_CONST.__objc_selrefs: 0x17ed8
   __DATA_CONST.__objc_protorefs: 0x108
-  __DATA_CONST.__objc_superrefs: 0xc70
-  __DATA_CONST.__objc_arraydata: 0x918
-  __DATA_CONST.__got: 0x2058
-  __AUTH_CONST.__const: 0x7e80
-  __AUTH_CONST.__cfstring: 0xe000
-  __AUTH_CONST.__objc_const: 0x47b40
+  __DATA_CONST.__objc_superrefs: 0xc68
+  __DATA_CONST.__objc_arraydata: 0x950
+  __DATA_CONST.__got: 0x2060
+  __AUTH_CONST.__const: 0x7ec0
+  __AUTH_CONST.__cfstring: 0xe040
+  __AUTH_CONST.__objc_const: 0x47b00
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_intobj: 0x8b8
-  __AUTH_CONST.__objc_arrayobj: 0x6a8
-  __AUTH_CONST.__objc_dictobj: 0x460
+  __AUTH_CONST.__objc_arrayobj: 0x6c0
+  __AUTH_CONST.__objc_dictobj: 0x488
   __AUTH_CONST.__objc_doubleobj: 0xb0
   __AUTH_CONST.__auth_got: 0x1c80
   __AUTH.__objc_data: 0x9878
   __AUTH.__data: 0xb80
-  __DATA.__objc_ivar: 0x283c
-  __DATA.__data: 0x6540
+  __DATA.__objc_ivar: 0x2820
+  __DATA.__data: 0x65a0
   __DATA.__bss: 0x6c70
   __DATA.__common: 0x100
-  __DATA_DIRTY.__objc_ivar: 0x10d0
+  __DATA_DIRTY.__objc_ivar: 0x10d4
   __DATA_DIRTY.__objc_data: 0x1630
   __DATA_DIRTY.__data: 0x28
-  __DATA_DIRTY.__bss: 0x900
+  __DATA_DIRTY.__bss: 0x938
   __DATA_DIRTY.__common: 0x20
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 19518
-  Symbols:   43304
-  CStrings:  3298
+  Functions: 19510
+  Symbols:   43290
+  CStrings:  3297
 
Symbols:
+ +[PKDataDetectorRevealHighlighter sharedHighlighter]
+ +[PKTextInputLanguageSelectionController _scriptQualifiedLocaleIdentifiers]
+ +[PKTextInputLanguageSelectionController _transliterationInputModeRules]
+ -[PKDataDetectorRevealHighlighter completeHighlightingItem:]
+ -[PKDataDetectorRevealHighlighter highlightItem:withProgress:]
+ -[PKDataDetectorRevealHighlighter highlightRangeChangedForItem:]
+ -[PKDataDetectorRevealHighlighter highlightRectsForItem:]
+ -[PKDataDetectorRevealHighlighter highlighting]
+ -[PKDataDetectorRevealHighlighter startHighlightingItem:]
+ -[PKDataDetectorRevealHighlighter stopHighlightingItem:]
+ -[PKDrawingPaletteView _contentViewForTesting]
+ -[PKDrawingPaletteView _toolPickerViewForTesting]
+ -[PKMetalRenderer newComputeVertexBufferWithLength:outOffset:commandBuffer:]
+ -[PKMetalResourceHandlerBuffer initWithSize:options:device:purgeable:initialReusableBufferCount:]
+ -[PKPaletteHostView _usesCompactPaletteWidth]
+ -[PKPaletteHostView compactPaletteAvailableWidth]
+ -[PKPaletteToolPickerAndColorPickerView compactPaletteWidth]
+ -[PKPaletteToolPickerAndColorPickerView setCompactPaletteWidth:]
+ -[PKPaletteToolPickerView _ensureFirstToolVisibleForRTLIfNeeded]
+ -[PKPaletteView compactPaletteWidth]
+ -[PKTextInputLanguageSelectionController ensureKeyboardLanguageConsistencyIfNeededWhileWriting:]
+ OBJC_IVAR_$_PKMetalRenderer._computeVertexBuffer
+ OBJC_IVAR_$_PKMetalResourceHandlerBuffer._lock
+ OBJC_IVAR_$_PKPaletteToolPickerAndColorPickerView._compactPaletteWidth
+ _OBJC_CLASS_$_PKDataDetectorRevealHighlighter
+ _OBJC_METACLASS_$_PKDataDetectorRevealHighlighter
+ __OBJC_$_CLASS_METHODS_PKDataDetectorRevealHighlighter
+ __OBJC_$_CLASS_PROP_LIST_PKDataDetectorRevealHighlighter
+ __OBJC_$_INSTANCE_METHODS_PKDataDetectorRevealHighlighter
+ __OBJC_$_PROP_LIST_PKDataDetectorRevealHighlighter
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_UIRVPresenterHighlightDelegate
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_UIRVPresenterHighlightDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_UIRVPresenterHighlightDelegate
+ __OBJC_$_PROTOCOL_REFS_UIRVPresenterHighlightDelegate
+ __OBJC_CLASS_PROTOCOLS_$_PKDataDetectorRevealHighlighter
+ __OBJC_CLASS_RO_$_PKDataDetectorRevealHighlighter
+ __OBJC_LABEL_PROTOCOL_$_UIRVPresenterHighlightDelegate
+ __OBJC_METACLASS_RO_$_PKDataDetectorRevealHighlighter
+ __OBJC_PROTOCOL_$_UIRVPresenterHighlightDelegate
+ ___52+[PKDataDetectorRevealHighlighter sharedHighlighter]_block_invoke
+ ___72+[PKTextInputLanguageSelectionController _transliterationInputModeRules]_block_invoke
+ ___75+[PKTextInputLanguageSelectionController _scriptQualifiedLocaleIdentifiers]_block_invoke
+ ___76-[PKMetalRenderer newComputeVertexBufferWithLength:outOffset:commandBuffer:]_block_invoke
+ ___block_descriptor_48_ea8_32s40s_e28_v16?0"<MTLCommandBuffer>"8ls32l8s40l8
+ ___getkDDHighlighterKeySymbolLoc_block_invoke
+ _objc_msgSend$_ensureFirstToolVisibleForRTLIfNeeded
+ _objc_msgSend$_scriptQualifiedLocaleIdentifiers
+ _objc_msgSend$_transliterationInputModeRules
+ _objc_msgSend$_usesCompactPaletteWidth
+ _objc_msgSend$compactPaletteAvailableWidth
+ _objc_msgSend$compactPaletteWidth
+ _objc_msgSend$constant
+ _objc_msgSend$ensureKeyboardLanguageConsistencyIfNeededWhileWriting:
+ _objc_msgSend$initWithSize:options:device:purgeable:initialReusableBufferCount:
+ _objc_msgSend$newComputeVertexBufferWithLength:outOffset:commandBuffer:
+ _objc_msgSend$setCompactPaletteWidth:
+ _objc_msgSend$sharedHighlighter
- -[PKMetalResourceHandler deallocateReusableBuffers]
- -[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]
- -[PKPaletteToolPickerAndColorPickerView didMoveToWindow]
- -[PKPaletteToolPickerAndColorPickerView safeAreaInsetsDidChange]
- -[PKPaletteToolPickerView _ensureCorrectToolSelectionForRTLIfNeeded]
- -[PKPaletteToolReorderController .cxx_destruct]
- -[PKPaletteToolReorderController _allowedCenterRectForVisibleToolsRect:liftedSize:]
- -[PKPaletteToolReorderController _beginDraggingToolView:atLocation:]
- -[PKPaletteToolReorderController _containerLocationOfRecognizer:]
- -[PKPaletteToolReorderController _draggedToolCenter]
- -[PKPaletteToolReorderController _endDragAnimated:]
- -[PKPaletteToolReorderController _endReordering]
- -[PKPaletteToolReorderController _longPressGestureHandler:]
- -[PKPaletteToolReorderController _reorderableToolViewAtLocationOfRecognizer:]
- -[PKPaletteToolReorderController _updateDragAtLocation:]
- -[PKPaletteToolReorderController beginReordering]
- -[PKPaletteToolReorderController delegate]
- -[PKPaletteToolReorderController endReorderingAnimated:]
- -[PKPaletteToolReorderController gestureRecognizer:shouldRecognizeSimultaneouslyWithGestureRecognizer:]
- -[PKPaletteToolReorderController gestureRecognizerShouldBegin:]
- -[PKPaletteToolReorderController initWithDelegate:]
- -[PKPaletteToolReorderController isActive]
- -[PKPaletteToolReorderController isDragging]
- -[PKPaletteToolReorderController longPressGestureRecognizer]
- -[PKTextInputLanguageSelectionController ensureKeyboardLanguageConsistencyIfNeeded]
- OBJC_IVAR_$_PKMetalResourceHandler._gpuResourceBuffer
- OBJC_IVAR_$_PKPaletteToolReorderController._active
- OBJC_IVAR_$_PKPaletteToolReorderController._delegate
- OBJC_IVAR_$_PKPaletteToolReorderController._dragAllowedCenterRect
- OBJC_IVAR_$_PKPaletteToolReorderController._dragDesiredCenter
- OBJC_IVAR_$_PKPaletteToolReorderController._dragLiftedSize
- OBJC_IVAR_$_PKPaletteToolReorderController._dragTouchOffset
- OBJC_IVAR_$_PKPaletteToolReorderController._draggedSnapshotView
- OBJC_IVAR_$_PKPaletteToolReorderController._draggedToolView
- OBJC_IVAR_$_PKPaletteToolReorderController._longPressGestureRecognizer
- _OBJC_CLASS_$_PKPaletteToolReorderController
- _OBJC_METACLASS_$_PKPaletteToolReorderController
- __OBJC_$_INSTANCE_METHODS_PKPaletteToolReorderController
- __OBJC_$_INSTANCE_VARIABLES_PKPaletteToolReorderController
- __OBJC_$_PROP_LIST_PKPaletteToolReorderController
- __OBJC_CLASS_PROTOCOLS_$_PKPaletteToolReorderController
- __OBJC_CLASS_RO_$_PKPaletteToolReorderController
- __OBJC_METACLASS_RO_$_PKPaletteToolReorderController
- ___51-[PKMetalResourceHandler deallocateReusableBuffers]_block_invoke
- ___51-[PKPaletteToolReorderController _endDragAnimated:]_block_invoke
- ___51-[PKPaletteToolReorderController _endDragAnimated:]_block_invoke_2
- ___51-[PKPaletteToolReorderController _endDragAnimated:]_block_invoke_3
- ___68-[PKPaletteToolPickerView _ensureCorrectToolSelectionForRTLIfNeeded]_block_invoke
- ___68-[PKPaletteToolReorderController _beginDraggingToolView:atLocation:]_block_invoke
- ___73-[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]_block_invoke
- ___73-[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]_block_invoke_2
- ___73-[PKMetalResourceHandler newGPUBufferWithLength:outOffset:commandBuffer:]_block_invoke_3
- ___block_descriptor_48_ea8_32s40w_e28_v16?0"<MTLCommandBuffer>"8lw40l8s32l8
- ___block_descriptor_72_ea8_32s40s48r_e5_v8?0lr48l8s32l8s40l8
- _objc_msgSend$_allowedCenterRectForVisibleToolsRect:liftedSize:
- _objc_msgSend$_beginDraggingToolView:atLocation:
- _objc_msgSend$_containerLocationOfRecognizer:
- _objc_msgSend$_endDragAnimated:
- _objc_msgSend$_endReordering
- _objc_msgSend$_ensureCorrectToolSelectionForRTLIfNeeded
- _objc_msgSend$_reorderableToolViewAtLocationOfRecognizer:
- _objc_msgSend$_updateDragAtLocation:
- _objc_msgSend$beginReordering
- _objc_msgSend$dragContainerViewForReorderController:
- _objc_msgSend$ensureKeyboardLanguageConsistencyIfNeeded
- _objc_msgSend$newGPUBufferWithLength:outOffset:commandBuffer:
- _objc_msgSend$reorderControllerDidChangeActive:
- _objc_msgSend$reorderControllerShouldBeginReordering:
- _objc_msgSend$reorderableToolViewsForReorderController:
- _objc_msgSend$snapshotViewAfterScreenUpdates:
- _objc_msgSend$visibleToolsRectForReorderController:
CStrings:
+ "LanguageController: Skipping keyboard language propagation while writing."
+ "kDDHighlighterKey"
+ "mr-Translit"
+ "mr_Latn"
+ "\xf0a"
- "Couldn't snapshot the tool being dragged; falling back to a placeholder."
- "Did begin dragging a tool."
- "Did begin reordering tools."
- "Did end reordering tools."
- "Reordering refused by the delegate."
- "\xf0!"
```
