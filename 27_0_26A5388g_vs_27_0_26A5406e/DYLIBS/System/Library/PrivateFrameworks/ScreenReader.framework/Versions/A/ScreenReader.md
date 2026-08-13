## ScreenReader

> `/System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/ScreenReader`

### Sections with Same Size but Changed Content

- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_types`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_proto`
- `__TEXT.__dof_SCRMapEle`
- `__TEXT.__dof_SCRSpeech`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH_CONST.__objc_doubleobj`
- `__AUTH_CONST.__objc_floatobj`
- `__AUTH.__data`

```diff

-1045.0.0.0.0
-  __TEXT.__text: 0x2d4a4c
-  __TEXT.__objc_methlist: 0x25838
+1048.2.0.0.0
+  __TEXT.__text: 0x2d8d9c
+  __TEXT.__objc_methlist: 0x25ab8
   __TEXT.__dlopen_cstrs: 0x6c9
-  __TEXT.__const: 0x1450
-  __TEXT.__swift5_typeref: 0x650
-  __TEXT.__swift5_capture: 0x4c0
+  __TEXT.__const: 0x1470
+  __TEXT.__swift5_typeref: 0x664
+  __TEXT.__swift5_capture: 0x4f0
   __TEXT.__constg_swiftt: 0x5d4
   __TEXT.__swift5_reflstr: 0x1d4
   __TEXT.__swift5_fieldmd: 0x258
   __TEXT.__swift5_builtin: 0x14
-  __TEXT.__cstring: 0x1dec5
+  __TEXT.__cstring: 0x1e15c
   __TEXT.__oslogstring: 0x1441
   __TEXT.__swift5_types: 0x34
   __TEXT.__swift_as_entry: 0x7c
   __TEXT.__swift_as_ret: 0x90
   __TEXT.__swift_as_cont: 0xd0
   __TEXT.__swift5_proto: 0x20
-  __TEXT.__gcc_except_tab: 0x337c
-  __TEXT.__ustring: 0x10a
+  __TEXT.__gcc_except_tab: 0x3564
+  __TEXT.__ustring: 0x48
   __TEXT.__dof_SCRMapEle: 0x47e
   __TEXT.__dof_SCRSpeech: 0x21a
-  __TEXT.__unwind_info: 0x8a80
+  __TEXT.__unwind_info: 0x8b28
   __TEXT.__eh_frame: 0x1098
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1f80
-  __DATA_CONST.__objc_classlist: 0xd10
+  __DATA_CONST.__objc_classlist: 0xd18
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x268
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x13bc0
+  __DATA_CONST.__objc_selrefs: 0x13d18
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0x9a8
   __DATA_CONST.__objc_arraydata: 0x8b0
-  __DATA_CONST.__got: 0x2110
-  __AUTH_CONST.__const: 0x4948
-  __AUTH_CONST.__cfstring: 0x23480
-  __AUTH_CONST.__objc_const: 0x25130
+  __DATA_CONST.__got: 0x2130
+  __AUTH_CONST.__const: 0x49b8
+  __AUTH_CONST.__cfstring: 0x23640
+  __AUTH_CONST.__objc_const: 0x25358
   __AUTH_CONST.__objc_arrayobj: 0x1c8
   __AUTH_CONST.__objc_intobj: 0x1590
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0xb0
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x1f48
-  __AUTH.__objc_data: 0x8600
+  __AUTH_CONST.__auth_got: 0x1f60
+  __AUTH.__objc_data: 0x8650
   __AUTH.__data: 0x560
-  __DATA.__objc_ivar: 0x1a58
-  __DATA.__data: 0x2268
-  __DATA.__bss: 0x12f8
+  __DATA.__objc_ivar: 0x1a80
+  __DATA.__data: 0x2270
+  __DATA.__bss: 0x1318
   __DATA.__common: 0x8
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
+  - /System/Library/Frameworks/Accessibility.framework/Versions/A/Accessibility
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13657
-  Symbols:   29073
-  CStrings:  5071
+  Functions: 13720
+  Symbols:   29182
+  CStrings:  5088
 
Symbols:
+ +[SCRBrailleManager _textLineRangeForFirstLineIndex:lastLineIndex:currentLineIndex:]
+ +[SCREventSender postMouseMovedEventAtLocation:]
+ +[SCRSiriUIManager shared]
+ -[SCRApplication _windowsForGuideCount]
+ -[SCRApplication hasWindowsForGuideWithWait:]
+ -[SCRElement(SCRElementDescription) _embeddedImageDescription]
+ -[SCRElement(SCRElementEventHandling) _intelligentScreenDescriptionDispatchHandler:]
+ -[SCRElement(SCRElementEventHandling) _showRecognitionOptionsDispatchHandler:]
+ -[SCRElement(SCRElementInteraction) _addRecognitionItemForCommand:title:toGuide:]
+ -[SCRElement(SCRElementInteraction) presentRecognitionOptionsForRequest:]
+ -[SCRElement(SCRElementInteraction) recognitionOptionsGuide]
+ -[SCRElement(SCRElementInteraction) speakScreenDescriptionForRequest:]
+ -[SCRMenuBarAgentApplication _layoutChanged:]
+ -[SCRMenuBarAgentApplication connectToApp]
+ -[SCRMenuBarAgentApplication handleLayoutChangeWithInfo:]
+ -[SCRMenuBarAgentApplication isCatalystApplication]
+ -[SCRSiriUIManager .cxx_destruct]
+ -[SCRSiriUIManager _beginFocusIntoAffordance]
+ -[SCRSiriUIManager _clearFocusIntoAffordanceOnAppearance]
+ -[SCRSiriUIManager _jumpIntoAffordance]
+ -[SCRSiriUIManager _performJumpIntoAffordanceForWindow:]
+ -[SCRSiriUIManager _performSettleForWindow:]
+ -[SCRSiriUIManager _settleAppearance]
+ -[SCRSiriUIManager affordanceSummonedByAction]
+ -[SCRSiriUIManager affordanceWindowVisible]
+ -[SCRSiriUIManager affordanceWindow]
+ -[SCRSiriUIManager focusIntoAffordanceOnAppearance]
+ -[SCRSiriUIManager focusIntoAffordanceWhenItAppears]
+ -[SCRSiriUIManager isVirtualFocusInAffordanceWindow]
+ -[SCRSiriUIManager moveToSiriUIWithRequest:fromElement:]
+ -[SCRSiriUIManager setAffordanceSummonedByAction:]
+ -[SCRSiriUIManager setAffordanceWindow:]
+ -[SCRSiriUIManager setFocusIntoAffordanceOnAppearance:]
+ -[SCRSiriUIManager wasAffordanceSummonedByAction]
+ -[SCRSystemUIServerApplication _focusIntoLiveActivity]
+ -[SCRSystemUIServerApplication _menuExtraIndexForLiveActivity]
+ -[SCRSystemUIServerApplication _menuExtrasExcludingOverflowOverlap:]
+ -[SCRSystemUIServerApplication _reloadMenuExtras]
+ -[SCRSystemUIServerApplication dispatchFocusIntoLiveActivity]
+ -[SCRSystemUIServerApplication dispatchReloadMenuExtras]
+ -[SCRTextArea _handleSelectedTextChangeForUIElement:command:sync:focusChange:selectedTextMarkerRange:]
+ -[SCRTextArea _refreshBrailleLineForSelectionChange:uiElement:]
+ -[SCRWebAreaNoEchoTextField _markerByAdvancingMarker:byCharacters:textArea:]
+ -[SCRWebAreaNoEchoTextField actionNames]
+ -[SCRWindow isSiriUIAffordanceWindow]
+ -[SCRXcodeTextElement _jumpToLineZeroDeltaFallbackFired]
+ -[SCRXcodeTextElement _lineAnnouncementDedupOwner]
+ -[SCRXcodeTextElement _sourceEditorDidJumpToLine:]
+ -[SCRXcodeTextElement dealloc]
+ -[SCRXcodeTextElement setIsEventHandler:isKeyboardHandler:]
+ GCC_except_table10339
+ GCC_except_table10343
+ GCC_except_table10347
+ GCC_except_table10489
+ GCC_except_table10494
+ GCC_except_table11118
+ GCC_except_table11141
+ GCC_except_table11427
+ GCC_except_table11431
+ GCC_except_table11533
+ GCC_except_table1158
+ GCC_except_table1171
+ GCC_except_table11755
+ GCC_except_table11987
+ GCC_except_table12034
+ GCC_except_table1205
+ GCC_except_table12103
+ GCC_except_table12105
+ GCC_except_table1213
+ GCC_except_table12231
+ GCC_except_table12308
+ GCC_except_table12397
+ GCC_except_table12401
+ GCC_except_table12402
+ GCC_except_table12409
+ GCC_except_table1249
+ GCC_except_table1253
+ GCC_except_table1256
+ GCC_except_table12622
+ GCC_except_table12702
+ GCC_except_table1470
+ GCC_except_table1652
+ GCC_except_table1839
+ GCC_except_table1878
+ GCC_except_table1912
+ GCC_except_table1916
+ GCC_except_table2030
+ GCC_except_table2183
+ GCC_except_table2185
+ GCC_except_table2187
+ GCC_except_table2249
+ GCC_except_table2357
+ GCC_except_table2361
+ GCC_except_table2580
+ GCC_except_table2597
+ GCC_except_table2654
+ GCC_except_table2858
+ GCC_except_table3113
+ GCC_except_table3115
+ GCC_except_table3191
+ GCC_except_table3267
+ GCC_except_table3391
+ GCC_except_table3395
+ GCC_except_table3475
+ GCC_except_table3578
+ GCC_except_table3656
+ GCC_except_table3678
+ GCC_except_table3792
+ GCC_except_table3882
+ GCC_except_table3885
+ GCC_except_table3908
+ GCC_except_table3913
+ GCC_except_table3927
+ GCC_except_table4028
+ GCC_except_table4072
+ GCC_except_table4472
+ GCC_except_table4481
+ GCC_except_table4484
+ GCC_except_table4609
+ GCC_except_table4651
+ GCC_except_table4655
+ GCC_except_table4657
+ GCC_except_table4661
+ GCC_except_table4665
+ GCC_except_table4735
+ GCC_except_table4749
+ GCC_except_table4794
+ GCC_except_table4798
+ GCC_except_table4824
+ GCC_except_table4830
+ GCC_except_table5304
+ GCC_except_table5661
+ GCC_except_table5697
+ GCC_except_table5800
+ GCC_except_table6070
+ GCC_except_table6076
+ GCC_except_table6245
+ GCC_except_table6295
+ GCC_except_table6331
+ GCC_except_table6425
+ GCC_except_table6612
+ GCC_except_table6698
+ GCC_except_table6713
+ GCC_except_table6723
+ GCC_except_table6743
+ GCC_except_table6749
+ GCC_except_table6753
+ GCC_except_table6862
+ GCC_except_table6870
+ GCC_except_table6903
+ GCC_except_table6937
+ GCC_except_table6971
+ GCC_except_table6972
+ GCC_except_table7090
+ GCC_except_table7096
+ GCC_except_table7117
+ GCC_except_table7118
+ GCC_except_table7185
+ GCC_except_table7211
+ GCC_except_table7213
+ GCC_except_table727
+ GCC_except_table7365
+ GCC_except_table7367
+ GCC_except_table7369
+ GCC_except_table7384
+ GCC_except_table7385
+ GCC_except_table7398
+ GCC_except_table7412
+ GCC_except_table7413
+ GCC_except_table7491
+ GCC_except_table7498
+ GCC_except_table7499
+ GCC_except_table7642
+ GCC_except_table788
+ GCC_except_table7934
+ GCC_except_table7956
+ GCC_except_table8132
+ GCC_except_table8221
+ GCC_except_table8227
+ GCC_except_table8228
+ GCC_except_table8229
+ GCC_except_table8230
+ GCC_except_table8234
+ GCC_except_table8235
+ GCC_except_table8356
+ GCC_except_table8367
+ GCC_except_table8371
+ GCC_except_table8398
+ GCC_except_table8502
+ GCC_except_table8647
+ GCC_except_table8653
+ GCC_except_table8748
+ GCC_except_table8822
+ GCC_except_table8904
+ GCC_except_table8996
+ GCC_except_table9006
+ GCC_except_table9016
+ GCC_except_table9017
+ GCC_except_table9024
+ GCC_except_table9027
+ GCC_except_table9028
+ GCC_except_table9182
+ GCC_except_table9512
+ GCC_except_table9555
+ GCC_except_table9560
+ GCC_except_table9893
+ GCC_except_table9897
+ GCC_except_table9902
+ OBJC_IVAR_$_SCROutputBrailleComponent._currentBrlElementIsSecureField
+ OBJC_IVAR_$_SCRSiriUIManager._affordanceSummonedByAction
+ OBJC_IVAR_$_SCRSiriUIManager._affordanceWindow
+ OBJC_IVAR_$_SCRSiriUIManager._focusIntoAffordanceOnAppearance
+ OBJC_IVAR_$_SCRXcodeTextElement._jumpToLineZeroDeltaTimer
+ OBJC_IVAR_$_SCRXcodeTextElement._lastFindAnnouncedLine
+ OBJC_IVAR_$_SCRXcodeTextElement._lastFindAnnouncedTime
+ OBJC_IVAR_$_SCRXcodeTextElement._lastJumpAnnouncedLine
+ OBJC_IVAR_$_SCRXcodeTextElement._lastJumpAnnouncedTime
+ OBJC_IVAR_$_SCRXcodeTextElement._registeredJumpToLineNotification
+ _AXAskShouldHideOptions
+ _AXSpeechAttributeSSML
+ _AccessibilityUtilitiesLibrary
+ _OBJC_CLASS_$_SCRSiriUIManager
+ _OBJC_METACLASS_$_SCRSiriUIManager
+ _SCRAskIsHiddenByRestriction
+ __70-[SCRElement(SCRElementInteraction) _addAudiographGuideItemsForGuide:]_block_invoke
+ __70-[SCRElement(SCRElementInteraction) _addAudiographGuideItemsForGuide:]_block_invoke_2
+ __OBJC_$_CLASS_METHODS_SCRBrailleManager
+ __OBJC_$_CLASS_METHODS_SCRSiriUIManager
+ __OBJC_$_CLASS_PROP_LIST_SCRSiriUIManager
+ __OBJC_$_INSTANCE_METHODS_SCRSiriUIManager
+ __OBJC_$_INSTANCE_VARIABLES_SCRSiriUIManager
+ __OBJC_$_PROP_LIST_SCRSiriUIManager
+ __OBJC_CLASS_RO_$_SCRSiriUIManager
+ __OBJC_METACLASS_RO_$_SCRSiriUIManager
+ __SCRWebElementHasDescriptionCustomContent
+ ___26+[SCRSiriUIManager shared]_block_invoke
+ ___60-[SCRElement(SCRElementInteraction) recognitionOptionsGuide]_block_invoke
+ ___block_descriptor_49_e8_32s40r_e41_v40?0"NSDictionary"8{_NSRange=QQ}16^B32l
+ ___getAXAskShouldHideOptionsSymbolLoc_block_invoke
+ __swift_closure_destructor.56Tm
+ _objc_msgSend$_addRecognitionItemForCommand:title:toGuide:
+ _objc_msgSend$_beginFocusIntoAffordance
+ _objc_msgSend$_embeddedImageDescription
+ _objc_msgSend$_handleSelectedTextChangeForUIElement:command:sync:focusChange:selectedTextMarkerRange:
+ _objc_msgSend$_lineAnnouncementDedupOwner
+ _objc_msgSend$_markerByAdvancingMarker:byCharacters:textArea:
+ _objc_msgSend$_menuExtraIndexForLiveActivity
+ _objc_msgSend$_menuExtrasExcludingOverflowOverlap:
+ _objc_msgSend$_refreshBrailleLineForSelectionChange:uiElement:
+ _objc_msgSend$_resetMenubarForTracking
+ _objc_msgSend$_textLineRangeForFirstLineIndex:lastLineIndex:currentLineIndex:
+ _objc_msgSend$affordanceWindowVisible
+ _objc_msgSend$categoryOrder
+ _objc_msgSend$dispatchFocusIntoLiveActivity
+ _objc_msgSend$dispatchReloadMenuExtras
+ _objc_msgSend$focusIntoAffordanceWhenItAppears
+ _objc_msgSend$hasWindowsForGuideWithWait:
+ _objc_msgSend$isImageElement:
+ _objc_msgSend$isSiriUIAffordanceWindow
+ _objc_msgSend$isVirtualFocusInAffordanceWindow
+ _objc_msgSend$moveToSiriUIWithRequest:fromElement:
+ _objc_msgSend$postMouseMovedEventAtLocation:
+ _objc_msgSend$presentRecognitionOptionsForRequest:
+ _objc_msgSend$recognitionOptionsGuide
+ _objc_msgSend$setCategoryOrder:
+ _objc_msgSend$setFocusedChildAtIndex:
+ _objc_msgSend$setIsSecureText:
+ _objc_msgSend$speakScreenDescriptionForRequest:
+ _objc_msgSend$speakScreenDescriptionWithData:
+ _objc_msgSend$wasAffordanceSummonedByAction
+ _soft_AXImageExplorerGenerativeModelsAvailable
+ _symbolic _____3key_yp5valuet s11AnyHashableV
+ getAXAskShouldHideOptionsSymbolLoc.ptr
+ shared.siriUIManager
- -[SCRWebAreaNoEchoTextField _staticTextSupportingTextMarkerRangeSelectRange:withStartingIndexOffset:textArea:]
- GCC_except_table10293
- GCC_except_table10297
- GCC_except_table10301
- GCC_except_table10442
- GCC_except_table10447
- GCC_except_table11070
- GCC_except_table11093
- GCC_except_table11378
- GCC_except_table11382
- GCC_except_table11484
- GCC_except_table1156
- GCC_except_table1169
- GCC_except_table11706
- GCC_except_table11937
- GCC_except_table11984
- GCC_except_table1203
- GCC_except_table12053
- GCC_except_table12055
- GCC_except_table1211
- GCC_except_table12181
- GCC_except_table12258
- GCC_except_table12347
- GCC_except_table12351
- GCC_except_table12352
- GCC_except_table12359
- GCC_except_table1247
- GCC_except_table1251
- GCC_except_table1254
- GCC_except_table12572
- GCC_except_table12647
- GCC_except_table1468
- GCC_except_table1646
- GCC_except_table1833
- GCC_except_table1872
- GCC_except_table1906
- GCC_except_table1910
- GCC_except_table2024
- GCC_except_table2165
- GCC_except_table2169
- GCC_except_table2173
- GCC_except_table2243
- GCC_except_table2351
- GCC_except_table2355
- GCC_except_table2574
- GCC_except_table2591
- GCC_except_table2648
- GCC_except_table2852
- GCC_except_table3107
- GCC_except_table3109
- GCC_except_table3185
- GCC_except_table3261
- GCC_except_table3460
- GCC_except_table3506
- GCC_except_table3565
- GCC_except_table3643
- GCC_except_table3665
- GCC_except_table3778
- GCC_except_table3863
- GCC_except_table3866
- GCC_except_table3890
- GCC_except_table3895
- GCC_except_table3909
- GCC_except_table4010
- GCC_except_table4054
- GCC_except_table4454
- GCC_except_table4463
- GCC_except_table4466
- GCC_except_table4591
- GCC_except_table4629
- GCC_except_table4633
- GCC_except_table4637
- GCC_except_table4639
- GCC_except_table4643
- GCC_except_table4717
- GCC_except_table4731
- GCC_except_table4776
- GCC_except_table4780
- GCC_except_table4806
- GCC_except_table4812
- GCC_except_table5266
- GCC_except_table5623
- GCC_except_table5659
- GCC_except_table5762
- GCC_except_table6032
- GCC_except_table6038
- GCC_except_table6207
- GCC_except_table6257
- GCC_except_table6293
- GCC_except_table6387
- GCC_except_table6574
- GCC_except_table6660
- GCC_except_table6675
- GCC_except_table6685
- GCC_except_table6705
- GCC_except_table6711
- GCC_except_table6715
- GCC_except_table6824
- GCC_except_table6827
- GCC_except_table6832
- GCC_except_table6858
- GCC_except_table6899
- GCC_except_table6933
- GCC_except_table7052
- GCC_except_table7058
- GCC_except_table7079
- GCC_except_table7080
- GCC_except_table7147
- GCC_except_table7173
- GCC_except_table7175
- GCC_except_table725
- GCC_except_table7289
- GCC_except_table7329
- GCC_except_table7331
- GCC_except_table7346
- GCC_except_table7347
- GCC_except_table7360
- GCC_except_table7374
- GCC_except_table7375
- GCC_except_table7453
- GCC_except_table7460
- GCC_except_table7461
- GCC_except_table7604
- GCC_except_table786
- GCC_except_table7896
- GCC_except_table7918
- GCC_except_table8094
- GCC_except_table8183
- GCC_except_table8189
- GCC_except_table8190
- GCC_except_table8191
- GCC_except_table8192
- GCC_except_table8196
- GCC_except_table8197
- GCC_except_table8318
- GCC_except_table8329
- GCC_except_table8333
- GCC_except_table8360
- GCC_except_table8464
- GCC_except_table8609
- GCC_except_table8615
- GCC_except_table8710
- GCC_except_table8784
- GCC_except_table8866
- GCC_except_table8940
- GCC_except_table8941
- GCC_except_table8958
- GCC_except_table8968
- GCC_except_table8986
- GCC_except_table8989
- GCC_except_table8990
- GCC_except_table9138
- GCC_except_table9468
- GCC_except_table9509
- GCC_except_table9514
- GCC_except_table9847
- GCC_except_table9851
- GCC_except_table9856
- __94-[SCRElement(SCRElementInteraction) _addActionsToGuide:forCategory:includeElementDescription:]_block_invoke
- ___70-[SCRElement(SCRElementInteraction) _addAudiographGuideItemsForGuide:]_block_invoke_3
- ___70-[SCRElement(SCRElementInteraction) _addAudiographGuideItemsForGuide:]_block_invoke_4
- ___block_descriptor_41_e8_32s_e41_v40?0"NSDictionary"8{_NSRange=QQ}16^B32l
- __sLastFindAnnouncedLine
- __sLastFindAnnouncedTime
- _objc_msgSend$_staticTextSupportingTextMarkerRangeSelectRange:withStartingIndexOffset:textArea:
CStrings:
+ "!q"
+ "%ld items enclosed."
+ "%ld rows, %ld columns"
+ "%ld selections."
+ "%ld updated items"
+ "%lu columns, %lu rows"
+ "%lu: %@ %@ (heading level)"
+ "%lu: %@ (heading level)"
+ "(%ld items)"
+ "AXAskShouldHideOptions"
+ "AXLiveActivity"
+ "AXReloadSystemUIServer"
+ "AXShowWritingTools"
+ "AXSiriUIAffordance"
+ "AXSourceEditorDidJumpToLineNotification"
+ "BOOL soft_AXAskShouldHideOptions(void)"
+ "Global.askAboutImage.recognition.item.title"
+ "Global.askAboutImage.title"
+ "Global.askAboutScreen.title"
+ "Global.imageDescription.recognition.image.title"
+ "Global.imageDescription.recognition.item.title"
+ "Global.imageExplorer"
+ "Global.imageExplorer.recognition.item.title"
+ "Global.imageExplorer.title"
+ "Global.intelligentScreenDescription"
+ "Global.intelligentScreenDescription.recognition.title"
+ "Global.screenExplorer.title"
+ "Global.showRecognitionOptions"
+ "Global.showRecognitionOptions.title"
+ "Hot Spot %lu"
+ "SCRElement.intelligentScreenDescription"
+ "SCRElement.showRecognitionOptions"
+ "line %ld"
+ "menu-bar-overflow-indicator"
+ "quote level %ld"
+ "row %lu, column %lu"
+ "table, column %lu"
+ "table, row %lu"
+ "table, row %lu, column %lu"
- "%ld columns, %ld rows"
- "%ld: %@ %@ (heading level)"
- "%ld: %@ (heading level)"
- "%lu items enclosed."
- "%lu lines"
- "%lu rows, %lu columns"
- "%lu selections."
- "%lu updated items"
- "(%lu items)"
- "Hot Spot %ld"
- "SCRWebAreaNoEchoTextField.m"
- "_elementRangeIfContainedIn: precondition violated — range endpoints must lie outside the element"
- "column %ld"
- "column %ld of %ld"
- "line %lu"
- "quote level %lu"
- "row %ld"
- "row %ld of %ld"
- "row %ld, column %ld"
- "table, column %ld"
- "table, row %ld"
- "table, row %ld, column %ld"
```
