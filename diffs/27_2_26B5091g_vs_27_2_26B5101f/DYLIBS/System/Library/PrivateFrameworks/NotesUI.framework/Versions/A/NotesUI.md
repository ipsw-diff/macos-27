## NotesUI

> `/System/Library/PrivateFrameworks/NotesUI.framework/Versions/A/NotesUI`

```diff

-3195.41.8.101.1
-  __TEXT.__text: 0x269ef4
+3195.41.14.101.1
+  __TEXT.__text: 0x265f3c
   __TEXT.__init_offsets: 0x4
-  __TEXT.__objc_methlist: 0x121e8
-  __TEXT.__const: 0x9354
-  __TEXT.__cstring: 0x118f4
+  __TEXT.__objc_methlist: 0x12258
+  __TEXT.__const: 0x9304
+  __TEXT.__cstring: 0x118e4
   __TEXT.__gcc_except_tab: 0x4338
-  __TEXT.__oslogstring: 0x8d52
+  __TEXT.__oslogstring: 0x8ef2
   __TEXT.__ustring: 0x149c0
   __TEXT.__constg_swiftt: 0x32ec
-  __TEXT.__swift5_typeref: 0xc11e
+  __TEXT.__swift5_typeref: 0xc0e6
   __TEXT.__swift5_builtin: 0x21c
   __TEXT.__swift5_reflstr: 0x1ccb
   __TEXT.__swift5_fieldmd: 0x1f9c
   __TEXT.__swift5_assocty: 0x7d8
   __TEXT.__swift5_proto: 0x3c8
   __TEXT.__swift5_types: 0x290
-  __TEXT.__swift5_capture: 0x1a30
+  __TEXT.__swift5_capture: 0x1ab0
   __TEXT.__swift5_protos: 0x1c
-  __TEXT.__swift_as_entry: 0xc8
-  __TEXT.__swift_as_ret: 0xec
-  __TEXT.__swift_as_cont: 0x194
-  __TEXT.__unwind_info: 0xa830
-  __TEXT.__eh_frame: 0x3e20
+  __TEXT.__swift_as_entry: 0xd0
+  __TEXT.__swift_as_ret: 0xf4
+  __TEXT.__swift_as_cont: 0x1a0
+  __TEXT.__unwind_info: 0xa8b0
+  __TEXT.__eh_frame: 0x3f90
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1658
-  __DATA_CONST.__objc_classlist: 0x830
+  __DATA_CONST.__objc_classlist: 0x838
   __DATA_CONST.__objc_catlist: 0x268
   __DATA_CONST.__objc_protolist: 0x298
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd548
+  __DATA_CONST.__objc_selrefs: 0xd5a0
   __DATA_CONST.__objc_protorefs: 0xf8
-  __DATA_CONST.__objc_superrefs: 0x530
-  __DATA_CONST.__objc_arraydata: 0x2e0
-  __DATA_CONST.__got: 0x2800
-  __AUTH_CONST.__const: 0xd370
-  __AUTH_CONST.__cfstring: 0xa960
-  __AUTH_CONST.__objc_const: 0x1c9c0
-  __AUTH_CONST.__objc_arrayobj: 0x1c8
+  __DATA_CONST.__objc_superrefs: 0x538
+  __DATA_CONST.__objc_arraydata: 0x2f0
+  __DATA_CONST.__got: 0x2790
+  __AUTH_CONST.__const: 0xd488
+  __AUTH_CONST.__cfstring: 0xa9a0
+  __AUTH_CONST.__objc_const: 0x1caa0
+  __AUTH_CONST.__objc_arrayobj: 0x1e0
   __AUTH_CONST.__objc_intobj: 0x4f8
   __AUTH_CONST.__objc_doubleobj: 0x190
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x2be0
-  __AUTH.__objc_data: 0x23d8
+  __AUTH_CONST.__auth_got: 0x2ba8
+  __AUTH.__objc_data: 0x2428
   __AUTH.__data: 0x17d8
   __DATA.__objc_ivar: 0xed8
-  __DATA.__data: 0x46b0
+  __DATA.__data: 0x4658
   __DATA.__objc_stublist: 0x20
-  __DATA.__bss: 0x3c00
+  __DATA.__bss: 0x3bd0
   __DATA.__common: 0x40
   __DATA_DIRTY.__objc_data: 0x3a88
   __DATA_DIRTY.__data: 0x25b0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12820
-  Symbols:   18606
-  CStrings:  2870
+  Functions: 12853
+  Symbols:   18633
+  CStrings:  2878
 
Symbols:
+ +[NSColor(IC) ic_unselectedNotesListDragBackgroundColor]
+ +[NSEvent(NSEvent_IC) ic_fakeRightClickAtLocation:inWindow:]
+ -[AVAsset(IC_UI) ic_generatePreviewImageWithCompletion:]
+ -[AVAsset(IC_UI) ic_previewImageWithCompletion:]
+ -[ICAuthenticationPrompt(StringsPrivate) cloudAccountName]
+ -[ICAuthenticationPrompt(StringsPrivate) customAccountName]
+ -[ICAuthenticationPrompt(StringsPrivate) deviceAccountName]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForAddLock]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForChangeModeFrom]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForChangeModeTo]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForChangeMode]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForChangePassword]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForDeleteMixedNotes]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForDeleteMultipleNotes]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForDeleteNotes]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForDeleteSingleNote]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForRemoveLock]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForResetPassword]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForToggleBiometrics]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForViewAttachment]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStringsForViewNote]
+ -[ICAuthenticationPrompt(StringsPrivate) updateStrings]
+ -[ICTextController isListOrFixedWidthTextView:forRanges:]
+ -[ICTextController isListTextView:forRanges:]
+ -[ICTextController textView:hasListInRanges:orFixedWidth:]
+ -[ICTouchPressGestureRecognizer commonInit]
+ -[ICTouchPressGestureRecognizer initWithCoder:]
+ -[ICTouchPressGestureRecognizer initWithTarget:action:]
+ GCC_except_table100
+ GCC_except_table109
+ GCC_except_table115
+ GCC_except_table125
+ GCC_except_table142
+ GCC_except_table154
+ GCC_except_table173
+ GCC_except_table180
+ GCC_except_table186
+ GCC_except_table50
+ GCC_except_table78
+ GCC_except_table90
+ _OBJC_CLASS_$_ICTouchPressGestureRecognizer
+ _OBJC_CLASS_$_NSPressGestureRecognizer
+ _OBJC_CLASS_$_NSProcessInfo
+ _OBJC_METACLASS_$_ICTouchPressGestureRecognizer
+ _OBJC_METACLASS_$_NSPressGestureRecognizer
+ __41-[ICAttachmentImageLoadingOperation main]_block_invoke_2
+ __56-[AVAsset(IC_UI) ic_generatePreviewImageWithCompletion:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_ICAuthenticationPrompt(StringsPrivate)
+ __OBJC_$_INSTANCE_METHODS_ICTouchPressGestureRecognizer
+ __OBJC_CLASS_RO_$_ICTouchPressGestureRecognizer
+ __OBJC_METACLASS_RO_$_ICTouchPressGestureRecognizer
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_5
+ ___45-[ICAttachment(UI) imageActivityItemProvider]_block_invoke_6
+ ___48-[AVAsset(IC_UI) ic_previewImageWithCompletion:]_block_invoke
+ ___56-[AVAsset(IC_UI) ic_generatePreviewImageWithCompletion:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e40_v48?0^{CGImage=}8{?=qiIq}16"NSError"40l
+ _objc_msgSend$documentVisibleRect
+ _objc_msgSend$generateCGImageAsynchronouslyForTime:completionHandler:
+ _objc_msgSend$ic_fakeRightClickAtLocation:inWindow:
+ _objc_msgSend$ic_generatePreviewImageWithCompletion:
+ _objc_msgSend$ic_previewImageWithCompletion:
+ _objc_msgSend$processInfo
+ _objc_msgSend$setAllowedTouchTypes:
+ _objc_msgSend$setButtonMask:
+ _objc_msgSend$systemUptime
+ _objc_msgSend$textView:hasListInRanges:orFixedWidth:
+ _objc_msgSend$underPageBackgroundColor
+ _symbolic Sny_____G 10Foundation16AttributedStringV5IndexV
+ _symbolic Sny_____GSg 10Foundation16AttributedStringV5IndexV
+ _symbolic _____ 10Foundation16AttributedStringV
+ _symbolic _____ 8PaperKit26CanvasElementImageRendererC
+ _symbolic _____y______SbQo_ 7SwiftUI4ViewPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQO AA24ButtonStyleConfigurationV5LabelV
+ _symbolic _____z_Xx So6CGRectV
+ get_witness_table qd0__7SwiftUI4ViewHD3_AaBPAAE8onChange2of7initial_Qrqd___Sbyqd___qd__tctSQRd__lFQOyAA24ButtonStyleConfigurationV5LabelV_SbQo_HO
- -[AVAsset(IC_UI) ic_previewImage]
- -[ICAuthenticationPrompt(Strings) cloudAccountName]
- -[ICAuthenticationPrompt(Strings) customAccountName]
- -[ICAuthenticationPrompt(Strings) deviceAccountName]
- -[ICAuthenticationPrompt(Strings) updateStringsForAddLock]
- -[ICAuthenticationPrompt(Strings) updateStringsForChangeModeFrom]
- -[ICAuthenticationPrompt(Strings) updateStringsForChangeModeTo]
- -[ICAuthenticationPrompt(Strings) updateStringsForChangeMode]
- -[ICAuthenticationPrompt(Strings) updateStringsForChangePassword]
- -[ICAuthenticationPrompt(Strings) updateStringsForDeleteMixedNotes]
- -[ICAuthenticationPrompt(Strings) updateStringsForDeleteMultipleNotes]
- -[ICAuthenticationPrompt(Strings) updateStringsForDeleteNotes]
- -[ICAuthenticationPrompt(Strings) updateStringsForDeleteSingleNote]
- -[ICAuthenticationPrompt(Strings) updateStringsForRemoveLock]
- -[ICAuthenticationPrompt(Strings) updateStringsForResetPassword]
- -[ICAuthenticationPrompt(Strings) updateStringsForToggleBiometrics]
- -[ICAuthenticationPrompt(Strings) updateStringsForViewAttachment]
- -[ICAuthenticationPrompt(Strings) updateStringsForViewNote]
- -[ICAuthenticationPrompt(Strings) updateStrings]
- GCC_except_table106
- GCC_except_table112
- GCC_except_table170
- GCC_except_table177
- GCC_except_table183
- GCC_except_table51
- GCC_except_table58
- GCC_except_table68
- GCC_except_table75
- GCC_except_table97
- __OBJC_$_INSTANCE_METHODS_ICAuthenticationPrompt(Strings)
- ___block_descriptor_40_e8_32bs_e63_v32?0?<v?"<NSSecureCoding>""NSError">8#16"NSDictionary"24l
- _currMarkdownStyleLocation
- _didMarkdownStyle
- _objc_msgSend$copyCGImageAtTime:actualTime:error:
- _objc_msgSend$ic_previewImage
- _objc_msgSend$registerItemForTypeIdentifier:loadHandler:
- _objc_msgSend$undo
- _symbolic So6ICNoteCSgXw
- _symbolic So6ICNoteCSgXwz_Xx
- _symbolic _____ 10Foundation15AttributeScopesO
- _symbolic _____Sg 11NotesShared24ActivityEventParticipantV5NamesO
- _symbolic _____m 10Foundation15AttributeScopesO6AppKitE0dE10AttributesV
- _symbolic _____ySbG 7SwiftUI20_ValueActionModifierV
- _symbolic _____y______G 10Foundation16AttributedStringV26SingleAttributeTransformerV AA0E6ScopesO6AppKitE0hI10AttributesV015ForegroundColorE0O
- _symbolic _____y______G 10Foundation16AttributedStringV26SingleAttributeTransformerV AA0E6ScopesO6AppKitE0hI10AttributesV04FontE0O
- _symbolic _____y__________ySbGG 7SwiftUI15ModifiedContentV AA24ButtonStyleConfigurationV5LabelV AA20_ValueActionModifierV
- get_witness_table 7SwiftUI15ModifiedContentVyAA24ButtonStyleConfigurationV5LabelVAA20_ValueActionModifierVySbGGAA4ViewHPAgaLHPyHC_AjA0lK0HPyHCHC
CStrings:
+ "Failed to generate preview image for asset: %@"
+ "Unknown activity — falling back to activityItemIdParts"
+ "Unknown activity — falling back to empty title"
+ "Unknown activity — falling back to nil destination"
+ "Unknown activity — falling back to nil subtitle"
+ "Unknown activity — treating as not cacheable"
+ "Unknown activity — treating as not visible"
+ "commonMetadata"
+ "duration"
+ "parent attachment was deallocated before saveEverything could run"
+ "v48@?0^{CGImage=}8{?=qiIq}16@\"NSError\"40"
- "Cannot convert activity digest string to text {error: %s}"
- "PaperChromeOverlay"
- "v32@?0@?<v@?@\"<NSSecureCoding>\"@\"NSError\">8#16@\"NSDictionary\"24"
```
