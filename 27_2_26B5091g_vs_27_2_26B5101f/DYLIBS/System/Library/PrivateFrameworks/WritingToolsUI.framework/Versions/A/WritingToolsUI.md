## WritingToolsUI

> `/System/Library/PrivateFrameworks/WritingToolsUI.framework/Versions/A/WritingToolsUI`

```diff

-151.1.6.0.0
-  __TEXT.__text: 0x5883c
-  __TEXT.__objc_methlist: 0x3454
+151.1.9.0.0
+  __TEXT.__text: 0x5935c
+  __TEXT.__objc_methlist: 0x3514
   __TEXT.__const: 0x2cc4
-  __TEXT.__cstring: 0x2ae2
-  __TEXT.__gcc_except_tab: 0x86c
-  __TEXT.__oslogstring: 0x10b5
+  __TEXT.__cstring: 0x2b92
+  __TEXT.__gcc_except_tab: 0x898
+  __TEXT.__oslogstring: 0x10bc
   __TEXT.__dlopen_cstrs: 0xb4
   __TEXT.__swift5_typeref: 0x9260
-  __TEXT.__swift5_reflstr: 0x9ac
+  __TEXT.__swift5_reflstr: 0x9cc
   __TEXT.__swift5_assocty: 0x1e8
   __TEXT.__constg_swiftt: 0xae0
-  __TEXT.__swift5_fieldmd: 0x864
+  __TEXT.__swift5_fieldmd: 0x870
   __TEXT.__swift5_builtin: 0xa0
   __TEXT.__swift5_capture: 0x364
   __TEXT.__swift5_proto: 0x170

   __TEXT.__swift_as_entry: 0x48
   __TEXT.__swift_as_cont: 0x40
   __TEXT.__swift_as_ret: 0x24
-  __TEXT.__unwind_info: 0x1d70
-  __TEXT.__eh_frame: 0xa68
+  __TEXT.__unwind_info: 0x1da8
+  __TEXT.__eh_frame: 0xac0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x248
+  __DATA_CONST.__const: 0x258
   __DATA_CONST.__objc_classlist: 0x150
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2918
+  __DATA_CONST.__objc_selrefs: 0x29a8
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0xb0
   __DATA_CONST.__objc_arraydata: 0x88
-  __DATA_CONST.__got: 0x978
+  __DATA_CONST.__got: 0x990
   __AUTH_CONST.__const: 0x28f8
-  __AUTH_CONST.__cfstring: 0xfc0
-  __AUTH_CONST.__objc_const: 0x4de8
+  __AUTH_CONST.__cfstring: 0x1000
+  __AUTH_CONST.__objc_const: 0x4ee8
   __AUTH_CONST.__objc_doubleobj: 0x80
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__auth_got: 0xe60
   __AUTH.__objc_data: 0xd90
   __AUTH.__data: 0x808
-  __DATA.__objc_ivar: 0x2e8
+  __DATA.__objc_ivar: 0x2fc
   __DATA.__data: 0x15d0
   __DATA.__bss: 0x30f0
   __DATA.__common: 0x38

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2170
-  Symbols:   3809
-  CStrings:  404
+  Functions: 2189
+  Symbols:   3857
+  CStrings:  406
 
Symbols:
+ +[WTWritingToolsViewController _responderTargetForAction:inWindow:]
+ -[WTWritingTools _updateUserInterfaceVisibilityIfNeeded]
+ -[WTWritingTools dealloc]
+ -[WTWritingTools isUserInterfaceVisible]
+ -[WTWritingTools lastKnownUserInterfaceVisible]
+ -[WTWritingTools noteUserInterfaceVisibilityMayHaveChanged]
+ -[WTWritingTools popoverVisibilityObservers]
+ -[WTWritingTools setLastKnownUserInterfaceVisible:]
+ -[WTWritingTools setPopoverVisibilityObservers:]
+ -[WTWritingToolsViewController(WTWritingToolsPanel) isVisible]
+ -[_WTReplaceTextEffect clipsToDestinationRect]
+ -[_WTReplaceTextEffect setClipsToDestinationRect:]
+ -[_WTTextEffectView hasManagedFrame]
+ -[_WTTextEffectView replaceSourceEffect]
+ -[_WTTextEffectView setHasManagedFrame:]
+ -[_WTTextEffectView setReplaceSourceEffect:]
+ GCC_except_table112
+ GCC_except_table173
+ GCC_except_table187
+ GCC_except_table218
+ GCC_except_table6
+ GCC_except_table80
+ GCC_except_table84
+ GCC_except_table93
+ GCC_except_table99
+ OBJC_IVAR_$_WTWritingTools._lastKnownUserInterfaceVisible
+ OBJC_IVAR_$_WTWritingTools._popoverVisibilityObservers
+ OBJC_IVAR_$__WTReplaceTextEffect._clipsToDestinationRect
+ OBJC_IVAR_$__WTTextEffectView._hasManagedFrame
+ OBJC_IVAR_$__WTTextEffectView._replaceSourceEffect
+ _NSPopoverDidCloseNotification
+ _NSPopoverDidShowNotification
+ _NSPopoverWillCloseNotification
+ _WTWritingToolsUserInterfaceVisibilityDidChangeNotification
+ _WTWritingToolsViewControllerEnhancedSiriAvailabilityDidChangeNotification
+ ___29-[WTWritingTools setPopover:]_block_invoke
+ _objc_msgSend$_responderTargetForAction:inWindow:
+ _objc_msgSend$_updateUserInterfaceVisibilityIfNeeded
+ _objc_msgSend$clipsToDestinationRect
+ _objc_msgSend$hasManagedFrame
+ _objc_msgSend$isUserInterfaceVisible
+ _objc_msgSend$isVisible
+ _objc_msgSend$lastKnownUserInterfaceVisible
+ _objc_msgSend$noteUserInterfaceVisibilityMayHaveChanged
+ _objc_msgSend$popoverVisibilityObservers
+ _objc_msgSend$postNotificationName:object:
+ _objc_msgSend$replaceSourceEffect
+ _objc_msgSend$setClipsToDestinationRect:
+ _objc_msgSend$setLastKnownUserInterfaceVisible:
+ _objc_msgSend$setMasksToBounds:
+ _objc_msgSend$setPopoverVisibilityObservers:
+ _objc_msgSend$setReplaceSourceEffect:
+ _objc_msgSend$supplementalTargetForAction:sender:
- GCC_except_table111
- GCC_except_table172
- GCC_except_table186
- GCC_except_table217
- GCC_except_table92
CStrings:
+ "DebugForceUnsafeOutput"
+ "WTWritingToolsUserInterfaceVisibilityDidChangeNotification"
+ "WTWritingToolsViewControllerEnhancedSiriAvailabilityDidChangeNotification"
- "3"
```
