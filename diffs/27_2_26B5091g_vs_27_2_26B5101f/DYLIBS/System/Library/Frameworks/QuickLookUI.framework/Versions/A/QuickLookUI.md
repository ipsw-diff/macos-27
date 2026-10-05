## QuickLookUI

> `/System/Library/Frameworks/QuickLookUI.framework/Versions/A/QuickLookUI`

```diff

-1114.1.1.0.0
-  __TEXT.__text: 0xcb78c
-  __TEXT.__objc_methlist: 0x10f40
-  __TEXT.__gcc_except_tab: 0x10d4
-  __TEXT.__const: 0xf24
-  __TEXT.__cstring: 0x7ae6
-  __TEXT.__oslogstring: 0x39b8
+1114.1.6.0.0
+  __TEXT.__text: 0xcd4ac
+  __TEXT.__objc_methlist: 0x110a0
+  __TEXT.__gcc_except_tab: 0x10f4
+  __TEXT.__const: 0x1144
+  __TEXT.__cstring: 0x7b66
+  __TEXT.__oslogstring: 0x39f7
   __TEXT.__ustring: 0x26
-  __TEXT.__swift5_typeref: 0x390
-  __TEXT.__swift5_reflstr: 0xc9
-  __TEXT.__swift5_assocty: 0x108
-  __TEXT.__constg_swiftt: 0x148
-  __TEXT.__swift5_fieldmd: 0xcc
-  __TEXT.__swift5_proto: 0x84
-  __TEXT.__swift5_types: 0x18
-  __TEXT.__swift_as_entry: 0x24
+  __TEXT.__swift5_typeref: 0x470
+  __TEXT.__swift5_reflstr: 0xe9
+  __TEXT.__swift5_assocty: 0x128
+  __TEXT.__constg_swiftt: 0x18c
+  __TEXT.__swift5_fieldmd: 0xe8
+  __TEXT.__swift5_proto: 0x9c
+  __TEXT.__swift5_types: 0x1c
+  __TEXT.__swift_as_entry: 0x28
   __TEXT.__swift_as_ret: 0x24
-  __TEXT.__swift_as_cont: 0x14
+  __TEXT.__swift_as_cont: 0x18
   __TEXT.__swift5_capture: 0x20
   __TEXT.__dof_QLSeamles: 0x8e7
-  __TEXT.__unwind_info: 0x4dc8
+  __TEXT.__unwind_info: 0x4e88
   __TEXT.__eh_frame: 0x2b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5e0
-  __DATA_CONST.__objc_classlist: 0x690
+  __DATA_CONST.__const: 0x620
+  __DATA_CONST.__objc_classlist: 0x698
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x210
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x87b0
+  __DATA_CONST.__objc_selrefs: 0x8868
   __DATA_CONST.__objc_protorefs: 0x70
   __DATA_CONST.__objc_superrefs: 0x4b0
   __DATA_CONST.__objc_arraydata: 0x38
-  __DATA_CONST.__got: 0x1100
-  __AUTH_CONST.__const: 0x21d8
-  __AUTH_CONST.__cfstring: 0x7ee0
-  __AUTH_CONST.__objc_const: 0x17b78
+  __DATA_CONST.__got: 0x1138
+  __AUTH_CONST.__const: 0x22b0
+  __AUTH_CONST.__cfstring: 0x7ea0
+  __AUTH_CONST.__objc_const: 0x17ce8
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x14a0
-  __AUTH.__objc_data: 0x3a90
+  __AUTH_CONST.__auth_got: 0x1550
+  __AUTH.__objc_data: 0x3ae0
   __AUTH.__data: 0x128
-  __DATA.__objc_ivar: 0x1050
-  __DATA.__data: 0x1b50
-  __DATA.__bss: 0x1490
-  __DATA.__common: 0x1
+  __DATA.__objc_ivar: 0x1060
+  __DATA.__data: 0x1bd8
+  __DATA.__bss: 0x17b0
+  __DATA.__common: 0x28
   __DATA_DIRTY.__objc_data: 0x748
   __DATA_DIRTY.__data: 0x28
   __DATA_DIRTY.__bss: 0x70

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 6039
-  Symbols:   13361
-  CStrings:  1562
+  Functions: 6105
+  Symbols:   13464
+  CStrings:  1567
 
Symbols:
+ +[QLPreviewOverlayController temporaryControlsRevealDuration]
+ -[NSScrollView(QLPanGestureUtilities) ql_updatePanTouchesForSwipeAvailable:inMarkup:]
+ -[NSView(QLScrollViewUtilities) ql_updateAllScrollViewPanTouchesForSwipeAvailable:inMarkup:]
+ -[QLControlButton mouseMoved:]
+ -[QLControlSegmentedControl mouseMoved:]
+ -[QLFullscreenController _dragControlsPanelWithGesture:]
+ -[QLFullscreenController _ensureControlsPanelOrderedAboveContent]
+ -[QLFullscreenController _installControlsPanelDragDetection]
+ -[QLFullscreenController _orderControlsPanelAboveContent]
+ -[QLFullscreenController _synchronizeControlsPanelPosition]
+ -[QLFullscreenController controlsPanelDragRecognizer]
+ -[QLFullscreenController enteringFullscreen]
+ -[QLFullscreenController gestureRecognizerShouldBegin:]
+ -[QLFullscreenController lastControlsToggleTime]
+ -[QLFullscreenController setControlsPanelDragRecognizer:]
+ -[QLFullscreenController setEnteringFullscreen:]
+ -[QLFullscreenController setLastControlsToggleTime:]
+ -[QLFullscreenHUDContentView acceptsFirstMouse:]
+ -[QLFullscreenHUDWindow _childWindowOrderingPriority]
+ -[QLFullscreenHUDWindow _doOrderWindow:]
+ -[QLInlinePreviewController hideOverlay]
+ -[QLInlinePreviewController showOverlayMomentarily]
+ -[QLPreviewOverlayController _cancelTemporaryControlsReveal]
+ -[QLPreviewOverlayController hideOverlay]
+ -[QLPreviewOverlayController showOverlayMomentarily]
+ -[QLPreviewPanelController _isShowingShareSheet]
+ -[QLPreviewPanelController beginControlsInteraction]
+ -[QLPreviewPanelController endControlsInteraction]
+ -[QLPreviewPanelController isShowingShareSheet]
+ -[QLPreviewPanelController set_isShowingShareSheet:]
+ -[QLPreviewView dragTouchGestureRecognizer]
+ -[QLPreviewView setDragTouchGestureRecognizer:]
+ -[QLUIServiceBaseViewController dragTouchRecognizer]
+ -[QLUIServiceBaseViewController gestureRecognizer:shouldAttemptToRecognizeWithEvent:]
+ -[QLUIServiceBaseViewController setDragTouchRecognizer:]
+ GCC_except_table117
+ GCC_except_table121
+ GCC_except_table231
+ GCC_except_table358
+ OBJC_IVAR_$_QLFullscreenController._controlsPanelDragRecognizer
+ OBJC_IVAR_$_QLFullscreenController._enteringFullscreen
+ OBJC_IVAR_$_QLFullscreenController._lastControlsToggleTime
+ OBJC_IVAR_$_QLPreviewOverlayController._controlsTemporarilyRevealed
+ OBJC_IVAR_$_QLPreviewPanelController.__isShowingShareSheet
+ OBJC_IVAR_$_QLPreviewViewReserved.dragTouchGestureRecognizer
+ OBJC_IVAR_$_QLUIServiceBaseViewController._dragTouchRecognizer
+ QLControlObservePointerInputMode.onceToken
+ _OBJC_CLASS_$_QLFullscreenHUDContentView
+ _OBJC_METACLASS_$_QLFullscreenHUDContentView
+ __OBJC_$_INSTANCE_METHODS_QLFullscreenHUDContentView
+ __OBJC_CLASS_RO_$_QLFullscreenHUDContentView
+ __OBJC_METACLASS_RO_$_QLFullscreenHUDContentView
+ ___44-[QLPreviewPanelController shareFromButton:]_block_invoke
+ ___QLControlObservePointerInputMode_block_invoke
+ ___QLControlObservePointerInputMode_block_invoke_2
+ ___QLControlObservePointerInputMode_block_invoke_3
+ ___QLControlObservePointerInputMode_block_invoke_4
+ ___block_descriptor_32_e26_"NSEvent"16?0"NSEvent"8l
+ ___block_descriptor_32_e29_B24?0"NSTouch"8"NSEvent"16l
+ ___block_descriptor_40_e8_32w_e8_v16?08l
+ ___swift_allocate_value_buffer
+ ___swift_project_value_buffer
+ __swiftEmptySetSingleton
+ _associated conformance 11QuickLookUI14DocumentEntityV10AppIntents015SystemFrameworkE0AaD0fE0
+ _associated conformance 11QuickLookUI14DocumentEntityV10AppIntents04FileE0AaD0fE0
+ _associated conformance 11QuickLookUI14DocumentEntityV5QueryV10AppIntents0eF16ValidationBypassAaF0eF0
+ _associated conformance 11QuickLookUI21ResolveDocumentIntentV10AppIntents0gF0AA13PerformResultAdEP_AD0fJ0
+ _associated conformance 11QuickLookUI21ResolveDocumentIntentV10AppIntents0gF0AA14SummaryContentAdEP_AD09ParameterI0
+ _associated conformance 11QuickLookUI21ResolveDocumentIntentV10AppIntents0gF0AaD09_SupportsG12Dependencies
+ _associated conformance 11QuickLookUI21ResolveDocumentIntentV10AppIntents0gF0AaD24PersistentlyIdentifiable
+ _objc_msgSend$_cancelTemporaryControlsReveal
+ _objc_msgSend$_dragWindowRelativeToMouseDown:
+ _objc_msgSend$_ensureControlsPanelOrderedAboveContent
+ _objc_msgSend$_glassWindowBackingGlassView
+ _objc_msgSend$_installControlsPanelDragDetection
+ _objc_msgSend$_isShowingShareSheet
+ _objc_msgSend$_lastInteractionWasDirectTouch
+ _objc_msgSend$_orderControlsPanelAboveContent
+ _objc_msgSend$_setCornerRadius:
+ _objc_msgSend$_synchronizeControlsPanelPosition
+ _objc_msgSend$addLocalMonitorForTouchBegan:
+ _objc_msgSend$anchorRect
+ _objc_msgSend$controlsPanelDragRecognizer
+ _objc_msgSend$dragTouchGestureRecognizer
+ _objc_msgSend$dragTouchRecognizer
+ _objc_msgSend$enteringFullscreen
+ _objc_msgSend$hideOverlay
+ _objc_msgSend$isShowingShareSheet
+ _objc_msgSend$lastControlsToggleTime
+ _objc_msgSend$mouseDownCanMoveWindow
+ _objc_msgSend$mouseEventWithType:location:modifierFlags:timestamp:windowNumber:context:eventNumber:clickCount:pressure:
+ _objc_msgSend$options
+ _objc_msgSend$ql_updateAllScrollViewPanTouchesForSwipeAvailable:inMarkup:
+ _objc_msgSend$ql_updatePanTouchesForSwipeAvailable:inMarkup:
+ _objc_msgSend$setControlsPanelDragRecognizer:
+ _objc_msgSend$setDragTouchGestureRecognizer:
+ _objc_msgSend$setDragTouchRecognizer:
+ _objc_msgSend$setEnteringFullscreen:
+ _objc_msgSend$setLastControlsToggleTime:
+ _objc_msgSend$set_isShowingShareSheet:
+ _objc_msgSend$sheetParent
+ _objc_msgSend$showOverlayMomentarily
+ _objc_msgSend$temporaryControlsRevealDuration
+ _sLastDirectTouchTimestamp
+ _sPointerMovedSinceDirectTouch
+ _sTooltipOwner
+ _swift_once
+ _swift_slowAlloc
+ _symbolic $s10AppIntents0A6IntentP
+ _symbolic _____ 11QuickLookUI21ResolveDocumentIntentV
+ _symbolic _____Sg 10AppIntents12IntentDialogV
+ _symbolic _____Sg 10Foundation23LocalizedStringResourceV
+ _symbolic _____Sg 11QuickLookUI14DocumentEntityV
+ _symbolic _____y_____A3BG 10AppIntents21IntentResultContainerV s5NeverO
+ _symbolic _____y_____G s11_SetStorageC 10AppIntents22IntentExecutionTargetsV9ConditionV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10AppIntents22IntentExecutionTargetsV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 10AppIntents22IntentExecutionTargetsV9ConditionV
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 22UniformTypeIdentifiers6UTTypeV
+ _symbolic _____y_____SgG 10AppIntents15IntentParameterC 11QuickLookUI14DocumentEntityV
+ _symbolic _____y______Qo_ 10AppIntents0A6IntentPAAE16parameterSummaryQrvpZQO 11QuickLookUI015ResolveDocumentC0V
+ _type_layout_string 11QuickLookUI21ResolveDocumentIntentV
+ get_witness_table 10AppIntents21IntentResultContainerVys5NeverOA3EGAA0cD0HPyHC
- -[NSScrollView(QLPanGestureUtilities) ql_updatePanTouchesForSwipeAvailable:]
- -[NSView(QLScrollViewUtilities) ql_updateAllScrollViewPanTouchesForSwipeAvailable:]
- -[QLPreviewTitleBarView gestureRecognizer:shouldReceiveTouch:]
- -[QLPreviewTitleBarView handleLongPress:]
- -[QLPreviewTitleBarView handleTap:]
- -[QLPreviewTitleBarView showStopLightZoomUI]
- GCC_except_table108
- GCC_except_table119
- GCC_except_table229
- OBJC_IVAR_$_QLPreviewTitleBarView._clickRecognizer
- OBJC_IVAR_$_QLPreviewTitleBarView._longPressRecognizer
- OBJC_IVAR_$_QLPreviewTitleBarView._stoplightZoomUIController
- _objc_msgSend$allTouches
- _objc_msgSend$numberOfTouchesRequired
- _objc_msgSend$ql_updateAllScrollViewPanTouchesForSwipeAvailable:
- _objc_msgSend$ql_updatePanTouchesForSwipeAvailable:
- _objc_msgSend$setWindowServerAware:
- _objc_msgSend$showMenu
- _objc_msgSend$showStopLightZoomUI
CStrings:
+ "B24@?0@\"NSTouch\"8@\"NSEvent\"16"
+ "QLFullscreenController.controlsPanelDragRecognizer"
+ "QLInlinePreviewTemporaryControlsRevealDuration"
+ "QLPreviewView.dragTouch"
+ "QLUIServiceBaseViewController.dragTouch"
+ "Resolve Document"
+ "_NSGlassTrackingWindow"
+ "com.apple.MobileSMS"
+ "com.apple.Preview"
+ "com.apple.QuickLookUIFramework"
+ "v16@?0@8"
+ "\xf0\xf0\xc1"
- "%@ handleLongPress state is %lx"
- "%@ handleTap"
- "NSStoplightZoomUIController"
- "QLFullscreenController.m"
- "QLPreviewTitleBarView.clickGestureRecognizer"
- "QLPreviewTitleBarView.longPressGestureRecognizer"
- "\xf0\xf0\xb1"
```
