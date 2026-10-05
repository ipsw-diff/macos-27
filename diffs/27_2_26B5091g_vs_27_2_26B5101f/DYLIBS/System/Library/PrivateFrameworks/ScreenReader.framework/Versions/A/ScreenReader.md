## ScreenReader

> `/System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/ScreenReader`

```diff

-1050.3.0.0.0
-  __TEXT.__text: 0x2cba2c
-  __TEXT.__objc_methlist: 0x25c58
+1050.3.3.0.0
+  __TEXT.__text: 0x2cd8a4
+  __TEXT.__objc_methlist: 0x25dc0
   __TEXT.__dlopen_cstrs: 0x6c9
   __TEXT.__const: 0x1470
   __TEXT.__swift5_typeref: 0x664

   __TEXT.__swift5_reflstr: 0x1d4
   __TEXT.__swift5_fieldmd: 0x258
   __TEXT.__swift5_builtin: 0x14
-  __TEXT.__cstring: 0x1e391
+  __TEXT.__cstring: 0x1e605
   __TEXT.__oslogstring: 0x1475
   __TEXT.__swift5_types: 0x34
   __TEXT.__swift_as_entry: 0x7c
   __TEXT.__swift_as_ret: 0x90
   __TEXT.__swift_as_cont: 0xd0
   __TEXT.__swift5_proto: 0x20
-  __TEXT.__gcc_except_tab: 0x354c
+  __TEXT.__gcc_except_tab: 0x3564
   __TEXT.__ustring: 0x48
   __TEXT.__dof_SCRMapEle: 0x47e
   __TEXT.__dof_SCRSpeech: 0x21a
-  __TEXT.__unwind_info: 0xb450
-  __TEXT.__eh_frame: 0x10f0
+  __TEXT.__unwind_info: 0xb4b8
+  __TEXT.__eh_frame: 0x1120
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1fa0
-  __DATA_CONST.__objc_classlist: 0xd18
+  __DATA_CONST.__const: 0x1fc0
+  __DATA_CONST.__objc_classlist: 0xd20
   __DATA_CONST.__objc_catlist: 0x78
   __DATA_CONST.__objc_protolist: 0x268
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x13e10
+  __DATA_CONST.__objc_selrefs: 0x13ef8
   __DATA_CONST.__objc_protorefs: 0x58
-  __DATA_CONST.__objc_superrefs: 0x9a8
-  __DATA_CONST.__objc_arraydata: 0x8c8
-  __DATA_CONST.__got: 0x2140
+  __DATA_CONST.__objc_superrefs: 0x9b0
+  __DATA_CONST.__objc_arraydata: 0x8e8
+  __DATA_CONST.__got: 0x2148
   __AUTH_CONST.__const: 0x4a08
-  __AUTH_CONST.__cfstring: 0x23700
-  __AUTH_CONST.__objc_const: 0x253e8
-  __AUTH_CONST.__objc_arrayobj: 0x1e0
+  __AUTH_CONST.__cfstring: 0x23a60
+  __AUTH_CONST.__objc_const: 0x25548
+  __AUTH_CONST.__objc_arrayobj: 0x1f8
   __AUTH_CONST.__objc_intobj: 0x15d8
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0xb0
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x1fd0
-  __AUTH.__objc_data: 0x8650
+  __AUTH_CONST.__auth_got: 0x1fd8
+  __AUTH.__objc_data: 0x86a0
   __AUTH.__data: 0x560
-  __DATA.__objc_ivar: 0x1a90
+  __DATA.__objc_ivar: 0x1aa0
   __DATA.__data: 0x2290
-  __DATA.__bss: 0x1318
+  __DATA.__bss: 0x1328
   __DATA.__common: 0x8
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13757
-  Symbols:   29255
-  CStrings:  5102
+  Functions: 13789
+  Symbols:   29326
+  CStrings:  5130
 
Symbols:
+ +[SCRBrailleUtilities brailleLineIsEmptyContentPlaceholder:]
+ +[SCRBrailleUtilities refreshSelectionOnCurrentBrailleTextLineKeepingWindow:]
+ +[SCRElement(SCRElementEventHandling) isScreenRecordingInProgress]
+ -[AXFUIElement(SCRExtensions) isHostedViewSceneWindow]
+ -[SCRApplication echoPassThroughValueForElement:]
+ -[SCRApplication navigationSelectionAwaitingEcho]
+ -[SCRApplication setNavigationSelectionAwaitingEcho:]
+ -[SCRBrailleManager refreshSelectionOnCurrentTextLineKeepingWindow:]
+ -[SCRElement(SCRElementDescription) _spokenStringValueForRawStringValue:role:subrole:traits:]
+ -[SCRElement(SCRElementEventHandling) _bringUpSiriDispatchHandler:]
+ -[SCRElement(SCRElementEventHandling) _intelligenceOptionsDispatchHandler:]
+ -[SCRElement(SCRElementEventHandling) _startScreenRecording:]
+ -[SCRElement(SCRElementEventHandling) _stopScreenRecording:]
+ -[SCRElement(SCRElementInteraction) intelligenceOptionsGuide]
+ -[SCRElement(SCRElementInteraction) performBringUpSiriWithRequest:]
+ -[SCRElement(SCRElementInteraction) presentIntelligenceOptionsForRequest:]
+ -[SCRElement(SCRElementInteraction) shouldEchoValueDuringPassThroughDrag]
+ -[SCREventFactory(Gesture) _processPreCommand:]
+ -[SCREventFactory(Gesture) _processPressEventWithGestureString:factory:failSilently:modifierMask:ignoreHelp:]
+ -[SCRLiveActivity _appendContentDescriptionsOfElement:toArray:hostPid:depth:]
+ -[SCRLiveActivity _owningApplicationTitle]
+ -[SCRLiveActivity _remoteDescendantPidOfElement:hostPid:depth:]
+ -[SCRLiveActivity roleDescription]
+ -[SCRLiveActivity valueDescription]
+ -[SCROutputBrailleComponent handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROutputBrailleComponent handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCRPassThroughManager lastEchoedValue]
+ -[SCRPassThroughManager lastNotificationEchoTime]
+ -[SCRPassThroughManager lastPollTime]
+ -[SCRPassThroughManager setLastEchoedValue:]
+ -[SCRPassThroughManager setLastNotificationEchoTime:]
+ -[SCRPassThroughManager setLastPollTime:]
+ -[SCRSlider shouldEchoValueDuringPassThroughDrag]
+ -[SCRSystemUIServerApplication _expandedOverflowIndicatorFromMenuExtras:]
+ -[SCRSystemUIServerApplication _overflowIndicatorFromMenuExtras:]
+ -[SCRSystemUIServerApplication classForChildUIElement:parent:]
+ -[SCRSystemUIServerApplication isMenuExtraFrame:inMenubarFrame:]
+ -[SCRTextArea _refreshSelectionOnCurrentBrailleTextLineKeepingWindow:]
+ -[SCRTextArea navigationSelectionAwaitingEcho]
+ -[SCRTextArea setNavigationSelectionAwaitingEcho:]
+ -[SCRWindow _siriUIAffordanceBoundsChanged:]
+ -[SCRWindow isWritingToolsPanelWindow]
+ -[SCRWindowManagerApplication isShowingDesktop]
+ -[SCRWorkspace createBrailleManagerForTesting]
+ -[SCRWritingToolsManager _focusIntoPanel:fromElement:request:event:]
+ -[SCRWritingToolsManager lastPanelFocusedUIElement]
+ -[SCRWritingToolsManager panelVisible]
+ -[SCRWritingToolsManager panel]
+ -[SCRWritingToolsManager setLastPanelFocusedUIElement:]
+ -[SCRWritingToolsManager setPanel:]
+ GCC_except_table10386
+ GCC_except_table10390
+ GCC_except_table10394
+ GCC_except_table10535
+ GCC_except_table10540
+ GCC_except_table11164
+ GCC_except_table11187
+ GCC_except_table11473
+ GCC_except_table11477
+ GCC_except_table11580
+ GCC_except_table1160
+ GCC_except_table1173
+ GCC_except_table11802
+ GCC_except_table12036
+ GCC_except_table1207
+ GCC_except_table12083
+ GCC_except_table1215
+ GCC_except_table12152
+ GCC_except_table12154
+ GCC_except_table12281
+ GCC_except_table12358
+ GCC_except_table12447
+ GCC_except_table12451
+ GCC_except_table12452
+ GCC_except_table12459
+ GCC_except_table1251
+ GCC_except_table1255
+ GCC_except_table1258
+ GCC_except_table12678
+ GCC_except_table12767
+ GCC_except_table1472
+ GCC_except_table1656
+ GCC_except_table1843
+ GCC_except_table1882
+ GCC_except_table1916
+ GCC_except_table1920
+ GCC_except_table2034
+ GCC_except_table2175
+ GCC_except_table2179
+ GCC_except_table2181
+ GCC_except_table2183
+ GCC_except_table2185
+ GCC_except_table2187
+ GCC_except_table2189
+ GCC_except_table2191
+ GCC_except_table2253
+ GCC_except_table2361
+ GCC_except_table2365
+ GCC_except_table2584
+ GCC_except_table2601
+ GCC_except_table2658
+ GCC_except_table2862
+ GCC_except_table3119
+ GCC_except_table3121
+ GCC_except_table3197
+ GCC_except_table3273
+ GCC_except_table3403
+ GCC_except_table3407
+ GCC_except_table3491
+ GCC_except_table3595
+ GCC_except_table3673
+ GCC_except_table3696
+ GCC_except_table3815
+ GCC_except_table3906
+ GCC_except_table3909
+ GCC_except_table3933
+ GCC_except_table3938
+ GCC_except_table3952
+ GCC_except_table4056
+ GCC_except_table4100
+ GCC_except_table4502
+ GCC_except_table4511
+ GCC_except_table4514
+ GCC_except_table4639
+ GCC_except_table4681
+ GCC_except_table4685
+ GCC_except_table4691
+ GCC_except_table4695
+ GCC_except_table4765
+ GCC_except_table4779
+ GCC_except_table4824
+ GCC_except_table4828
+ GCC_except_table4854
+ GCC_except_table4860
+ GCC_except_table5693
+ GCC_except_table5729
+ GCC_except_table5832
+ GCC_except_table6107
+ GCC_except_table6113
+ GCC_except_table6282
+ GCC_except_table6332
+ GCC_except_table6369
+ GCC_except_table6464
+ GCC_except_table6651
+ GCC_except_table6752
+ GCC_except_table6762
+ GCC_except_table6782
+ GCC_except_table6788
+ GCC_except_table6792
+ GCC_except_table6901
+ GCC_except_table6904
+ GCC_except_table6909
+ GCC_except_table6935
+ GCC_except_table6942
+ GCC_except_table6973
+ GCC_except_table6976
+ GCC_except_table7010
+ GCC_except_table7011
+ GCC_except_table7129
+ GCC_except_table7135
+ GCC_except_table7156
+ GCC_except_table7157
+ GCC_except_table7224
+ GCC_except_table7250
+ GCC_except_table7252
+ GCC_except_table7366
+ GCC_except_table7404
+ GCC_except_table7406
+ GCC_except_table7423
+ GCC_except_table7424
+ GCC_except_table7451
+ GCC_except_table7452
+ GCC_except_table7530
+ GCC_except_table7537
+ GCC_except_table7538
+ GCC_except_table7681
+ GCC_except_table7974
+ GCC_except_table7996
+ GCC_except_table8172
+ GCC_except_table8261
+ GCC_except_table8267
+ GCC_except_table8268
+ GCC_except_table8269
+ GCC_except_table8270
+ GCC_except_table8274
+ GCC_except_table8275
+ GCC_except_table8396
+ GCC_except_table8407
+ GCC_except_table8411
+ GCC_except_table8439
+ GCC_except_table8543
+ GCC_except_table8689
+ GCC_except_table8695
+ GCC_except_table8790
+ GCC_except_table8864
+ GCC_except_table8946
+ GCC_except_table9020
+ GCC_except_table9038
+ GCC_except_table9048
+ GCC_except_table9058
+ GCC_except_table9059
+ GCC_except_table9066
+ GCC_except_table9069
+ GCC_except_table9070
+ GCC_except_table9225
+ GCC_except_table9555
+ GCC_except_table9601
+ GCC_except_table9606
+ GCC_except_table9940
+ GCC_except_table9944
+ GCC_except_table9949
+ OBJC_IVAR_$_SCRApplication._navigationSelectionAwaitingEcho
+ OBJC_IVAR_$_SCRPassThroughManager._lastEchoedValue
+ OBJC_IVAR_$_SCRPassThroughManager._lastNotificationEchoTime
+ OBJC_IVAR_$_SCRPassThroughManager._lastPollTime
+ OBJC_IVAR_$_SCRWritingToolsManager._lastPanelFocusedUIElement
+ OBJC_IVAR_$_SCRWritingToolsManager._panel
+ _OBJC_CLASS_$_NSTask
+ _OBJC_CLASS_$_SCRLiveActivity
+ _OBJC_METACLASS_$_SCRLiveActivity
+ __OBJC_$_INSTANCE_METHODS_SCRLiveActivity
+ __OBJC_CLASS_RO_$_SCRLiveActivity
+ __OBJC_METACLASS_RO_$_SCRLiveActivity
+ __SCRProcessExecutableIsWithinBundle
+ __ScreenRecordingTask
+ ___61-[SCRElement(SCRElementEventHandling) _startScreenRecording:]_block_invoke
+ ___61-[SCRElement(SCRElementInteraction) intelligenceOptionsGuide]_block_invoke
+ ___block_descriptor_32_e16_v16?0"NSTask"8l
+ ___block_descriptor_33_e39_q24?0"AXFUIElement"8"AXFUIElement"16l
+ _objc_msgSend$_appendContentDescriptionsOfElement:toArray:hostPid:depth:
+ _objc_msgSend$_expandedOverflowIndicatorFromMenuExtras:
+ _objc_msgSend$_focusIntoPanel:fromElement:request:event:
+ _objc_msgSend$_overflowIndicatorFromMenuExtras:
+ _objc_msgSend$_owningApplicationTitle
+ _objc_msgSend$_processPreCommand:
+ _objc_msgSend$_processPressEventWithGestureString:factory:failSilently:modifierMask:ignoreHelp:
+ _objc_msgSend$_refreshSelectionOnCurrentBrailleTextLineKeepingWindow:
+ _objc_msgSend$_remoteDescendantPidOfElement:hostPid:depth:
+ _objc_msgSend$_spokenStringValueForRawStringValue:role:subrole:traits:
+ _objc_msgSend$_supportsAccessibilityRelativeIndexForTextMarker
+ _objc_msgSend$brailleLineIsEmptyContentPlaceholder:
+ _objc_msgSend$echoPassThroughValueForElement:
+ _objc_msgSend$intelligenceOptionsGuide
+ _objc_msgSend$interrupt
+ _objc_msgSend$isHostedViewSceneWindow
+ _objc_msgSend$isMenuExtraFrame:inMenubarFrame:
+ _objc_msgSend$isScreenRecordingInProgress
+ _objc_msgSend$isWritingToolsPanelWindow
+ _objc_msgSend$lastEchoedValue
+ _objc_msgSend$lastNotificationEchoTime
+ _objc_msgSend$lastPollTime
+ _objc_msgSend$launchAndReturnError:
+ _objc_msgSend$navigationSelectionAwaitingEcho
+ _objc_msgSend$panel
+ _objc_msgSend$panelVisible
+ _objc_msgSend$performBringUpSiriWithRequest:
+ _objc_msgSend$presentIntelligenceOptionsForRequest:
+ _objc_msgSend$refreshSelectionOnCurrentBrailleTextLineKeepingWindow:
+ _objc_msgSend$refreshSelectionOnCurrentTextLineKeepingWindow:
+ _objc_msgSend$setArguments:
+ _objc_msgSend$setLastEchoedValue:
+ _objc_msgSend$setLastNotificationEchoTime:
+ _objc_msgSend$setLastPanelFocusedUIElement:
+ _objc_msgSend$setLastPollTime:
+ _objc_msgSend$setLaunchPath:
+ _objc_msgSend$setNavigationSelectionAwaitingEcho:
+ _objc_msgSend$setPanel:
+ _objc_msgSend$setPlaceholderValue:
+ _objc_msgSend$setTerminationHandler:
+ _objc_msgSend$shouldEchoValueDuringPassThroughDrag
+ _proc_pidpath
- +[SCRBrailleUtilities refreshSelectionOnCurrentBrailleTextLine]
- -[SCRApplication _lastGlobalValueChangedOutputTime]
- -[SCRApplication set_lastGlobalValueChangedOutputTime:]
- -[SCRBrailleManager refreshSelectionOnCurrentTextLine]
- -[SCRElement(SCRElementDescription) _spokenStringValueForRawStringValue:role:traits:]
- -[SCRElement(SCRElementEventHandling) _showRecognitionOptionsDispatchHandler:]
- -[SCRElement(SCRElementInteraction) presentRecognitionOptionsForRequest:]
- -[SCRElement(SCRElementInteraction) recognitionOptionsGuide]
- -[SCREventFactory(Gesture) _processPreCommand]
- -[SCREventFactory(Gesture) _processPressEventWithGestureString:failSilently:modifierMask:ignoreHelp:]
- -[SCRMenuBarAgentApplication handleLayoutChangeWithInfo:]
- -[SCROutputBrailleComponent handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROutputBrailleComponent handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCRSiriUIManager _performSettleForWindow:]
- -[SCRSiriUIManager _settleAppearance]
- -[SCRSiriUIManager affordanceSummonedByAction]
- -[SCRSiriUIManager setAffordanceSummonedByAction:]
- -[SCRSiriUIManager wasAffordanceSummonedByAction]
- -[SCRSystemUIServerApplication _focusIntoLiveActivity]
- -[SCRSystemUIServerApplication _menuExtraIndexForLiveActivity]
- -[SCRSystemUIServerApplication dispatchFocusIntoLiveActivity]
- -[SCRTextArea _refreshSelectionOnCurrentBrailleTextLine]
- GCC_except_table10366
- GCC_except_table10370
- GCC_except_table10374
- GCC_except_table10515
- GCC_except_table10520
- GCC_except_table11144
- GCC_except_table11167
- GCC_except_table11453
- GCC_except_table11457
- GCC_except_table11559
- GCC_except_table1158
- GCC_except_table1171
- GCC_except_table11781
- GCC_except_table12013
- GCC_except_table1205
- GCC_except_table12060
- GCC_except_table12129
- GCC_except_table1213
- GCC_except_table12131
- GCC_except_table12257
- GCC_except_table12334
- GCC_except_table12423
- GCC_except_table12427
- GCC_except_table12428
- GCC_except_table12435
- GCC_except_table1249
- GCC_except_table1253
- GCC_except_table1256
- GCC_except_table12648
- GCC_except_table12737
- GCC_except_table1470
- GCC_except_table1655
- GCC_except_table1842
- GCC_except_table1881
- GCC_except_table1915
- GCC_except_table1919
- GCC_except_table2033
- GCC_except_table2174
- GCC_except_table2178
- GCC_except_table2180
- GCC_except_table2182
- GCC_except_table2184
- GCC_except_table2186
- GCC_except_table2188
- GCC_except_table2190
- GCC_except_table2252
- GCC_except_table2360
- GCC_except_table2364
- GCC_except_table2583
- GCC_except_table2600
- GCC_except_table2657
- GCC_except_table2861
- GCC_except_table3118
- GCC_except_table3120
- GCC_except_table3196
- GCC_except_table3272
- GCC_except_table3402
- GCC_except_table3406
- GCC_except_table3486
- GCC_except_table3589
- GCC_except_table3667
- GCC_except_table3690
- GCC_except_table3809
- GCC_except_table3899
- GCC_except_table3902
- GCC_except_table3925
- GCC_except_table3930
- GCC_except_table3944
- GCC_except_table4048
- GCC_except_table4092
- GCC_except_table4494
- GCC_except_table4503
- GCC_except_table4506
- GCC_except_table4631
- GCC_except_table4669
- GCC_except_table4673
- GCC_except_table4679
- GCC_except_table4683
- GCC_except_table4757
- GCC_except_table4771
- GCC_except_table4816
- GCC_except_table4820
- GCC_except_table4846
- GCC_except_table4852
- GCC_except_table5684
- GCC_except_table5720
- GCC_except_table5823
- GCC_except_table6093
- GCC_except_table6099
- GCC_except_table6268
- GCC_except_table6318
- GCC_except_table6354
- GCC_except_table6449
- GCC_except_table6636
- GCC_except_table6722
- GCC_except_table6747
- GCC_except_table6767
- GCC_except_table6773
- GCC_except_table6777
- GCC_except_table6886
- GCC_except_table6889
- GCC_except_table6894
- GCC_except_table6920
- GCC_except_table6927
- GCC_except_table6958
- GCC_except_table6961
- GCC_except_table6995
- GCC_except_table6996
- GCC_except_table7114
- GCC_except_table7120
- GCC_except_table7141
- GCC_except_table7142
- GCC_except_table7209
- GCC_except_table7235
- GCC_except_table7237
- GCC_except_table7351
- GCC_except_table7389
- GCC_except_table7391
- GCC_except_table7393
- GCC_except_table7409
- GCC_except_table7422
- GCC_except_table7436
- GCC_except_table7515
- GCC_except_table7522
- GCC_except_table7523
- GCC_except_table7666
- GCC_except_table7958
- GCC_except_table7980
- GCC_except_table8156
- GCC_except_table8245
- GCC_except_table8251
- GCC_except_table8252
- GCC_except_table8253
- GCC_except_table8254
- GCC_except_table8258
- GCC_except_table8259
- GCC_except_table8380
- GCC_except_table8391
- GCC_except_table8395
- GCC_except_table8423
- GCC_except_table8527
- GCC_except_table8672
- GCC_except_table8678
- GCC_except_table8773
- GCC_except_table8847
- GCC_except_table8929
- GCC_except_table9003
- GCC_except_table9004
- GCC_except_table9031
- GCC_except_table9041
- GCC_except_table9042
- GCC_except_table9049
- GCC_except_table9052
- GCC_except_table9053
- GCC_except_table9207
- GCC_except_table9537
- GCC_except_table9581
- GCC_except_table9586
- GCC_except_table9920
- GCC_except_table9924
- GCC_except_table9929
- OBJC_IVAR_$_SCRApplication.__lastGlobalValueChangedOutputTime
- OBJC_IVAR_$_SCRSiriUIManager._affordanceSummonedByAction
- ___60-[SCRElement(SCRElementInteraction) recognitionOptionsGuide]_block_invoke
- ___block_descriptor_32_e39_q24?0"AXFUIElement"8"AXFUIElement"16l
- _objc_msgSend$_menuExtraIndexForLiveActivity
- _objc_msgSend$_processPreCommand
- _objc_msgSend$_processPressEventWithGestureString:failSilently:modifierMask:ignoreHelp:
- _objc_msgSend$_refreshSelectionOnCurrentBrailleTextLine
- _objc_msgSend$_spokenStringValueForRawStringValue:role:traits:
- _objc_msgSend$dispatchFocusIntoLiveActivity
- _objc_msgSend$getRange:ofAttribute:
- _objc_msgSend$presentRecognitionOptionsForRequest:
- _objc_msgSend$recognitionOptionsGuide
- _objc_msgSend$refreshSelectionOnCurrentBrailleTextLine
- _objc_msgSend$refreshSelectionOnCurrentTextLine
- _objc_msgSend$setFocusedChildAtIndex:
- _objc_msgSend$wasAffordanceSummonedByAction
CStrings:
+ "-A"
+ "-u"
+ "-v"
+ "/usr/sbin/screencapture"
+ "3!"
+ "AXHostedViewSceneWindow"
+ "AXResized"
+ "AXWritingToolsPanel"
+ "Failed to launch screencapture for screen recording: %@"
+ "Global.bringUpSiri"
+ "Global.bringUpSiri.title"
+ "Global.intelligenceOptions"
+ "Global.intelligenceOptions.title"
+ "Global.startScreenRecording"
+ "Global.startedScreenRecording.failure"
+ "Global.startingScreenRecording.message"
+ "Global.stopScreenRecording"
+ "Global.stoppedScreenRecording.failure"
+ "Navigation echo rejected: %@ marker could not be placed"
+ "SCRElement.bringUpSiri"
+ "SCRElement.intelligenceOptions"
+ "Sync'd selection change: navigation echo = %@"
+ "arrived"
+ "awaited"
+ "identifier"
+ "liveActivity"
+ "menu-bar-overflow-indicator-expanded"
+ "no, following the cursor"
+ "subrole"
+ "v16@?0@\"NSTask\"8"
+ "yes, keeping the window"
- "Global.showRecognitionOptions"
- "Global.showRecognitionOptions.title"
- "SCRElement.showRecognitionOptions"
```
