## AccessibilityUtilities

> `/System/Library/PrivateFrameworks/AccessibilityUtilities.framework/Versions/A/AccessibilityUtilities`

```diff

-3245.7.0.0.0
-  __TEXT.__text: 0x1ac9f4
-  __TEXT.__objc_methlist: 0xc160
-  __TEXT.__dlopen_cstrs: 0x748
-  __TEXT.__const: 0x7b48
-  __TEXT.__swift5_typeref: 0x2264
+3245.8.4.0.0
+  __TEXT.__text: 0x1ad914
+  __TEXT.__objc_methlist: 0xc320
+  __TEXT.__dlopen_cstrs: 0x6da
+  __TEXT.__const: 0x7b88
+  __TEXT.__swift5_typeref: 0x2270
   __TEXT.__swift5_capture: 0x2440
-  __TEXT.__cstring: 0x18876
+  __TEXT.__cstring: 0x18837
   __TEXT.__constg_swiftt: 0x1348
   __TEXT.__swift5_reflstr: 0x9a02
   __TEXT.__swift5_fieldmd: 0x3c00

   __TEXT.__swift_as_entry: 0xf4
   __TEXT.__swift_as_ret: 0x13c
   __TEXT.__swift_as_cont: 0x190
-  __TEXT.__oslogstring: 0x554c
+  __TEXT.__oslogstring: 0x559e
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__gcc_except_tab: 0xf3c
+  __TEXT.__gcc_except_tab: 0xf38
   __TEXT.__ustring: 0x68
-  __TEXT.__unwind_info: 0xa1c0
+  __TEXT.__unwind_info: 0xa218
   __TEXT.__eh_frame: 0x6b10
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3938
-  __DATA_CONST.__objc_classlist: 0x3b8
+  __DATA_CONST.__const: 0x3920
+  __DATA_CONST.__objc_classlist: 0x3c0
   __DATA_CONST.__objc_catlist: 0x40
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7ce0
+  __DATA_CONST.__objc_selrefs: 0x7e18
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x240
-  __DATA_CONST.__objc_arraydata: 0x658
-  __DATA_CONST.__got: 0x2380
-  __AUTH_CONST.__const: 0xa0b8
-  __AUTH_CONST.__cfstring: 0xedc0
-  __AUTH_CONST.__objc_const: 0x16a80
-  __AUTH_CONST.__objc_intobj: 0x1290
-  __AUTH_CONST.__objc_arrayobj: 0x210
+  __DATA_CONST.__objc_arraydata: 0x690
+  __DATA_CONST.__got: 0x2388
+  __AUTH_CONST.__const: 0xa0e8
+  __AUTH_CONST.__cfstring: 0xeec0
+  __AUTH_CONST.__objc_const: 0x16d48
+  __AUTH_CONST.__objc_intobj: 0x1350
+  __AUTH_CONST.__objc_arrayobj: 0x240
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x23a0
-  __AUTH.__objc_data: 0x1ee0
+  __AUTH_CONST.__auth_got: 0x23a8
+  __AUTH.__objc_data: 0x1f30
   __AUTH.__data: 0x610
-  __DATA.__objc_ivar: 0x988
-  __DATA.__data: 0x4300
-  __DATA.__bss: 0x80f8
+  __DATA.__objc_ivar: 0x9a8
+  __DATA.__data: 0x4330
+  __DATA.__bss: 0x80e8
   __DATA_DIRTY.__objc_data: 0x2d58
   __DATA_DIRTY.__data: 0x888
   __DATA_DIRTY.__bss: 0x3720

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12724
-  Symbols:   10918
-  CStrings:  3499
+  Functions: 12760
+  Symbols:   10997
+  CStrings:  3504
 
Symbols:
+ +[AXLiveRecognitionAskParameters current]
+ +[AXTripleClickHelpers _handleToggleTripleClickTriggeredFromAppIntent:completion:]
+ +[AXTripleClickHelpers _localToggleAccessibilityShortcutOption:completion:]
+ +[AXTripleClickHelpers _localToggleTripleClickOption:completion:]
+ +[AXTripleClickHelpers _toggleClassicInvertColorsOffMainThreadWithCompletion:]
+ +[AXTripleClickHelpers _toggleSmartInvertColorsOffMainThreadWithCompletion:]
+ +[AXTripleClickHelpers toggleAccessibilityShortcutOptionFromAppIntent:completion:]
+ -[AXLiveRecognitionAskParameters .cxx_destruct]
+ -[AXLiveRecognitionAskParameters activity]
+ -[AXLiveRecognitionAskParameters allowsFollowUpQuestions]
+ -[AXLiveRecognitionAskParameters automaticCaptureEnabled]
+ -[AXLiveRecognitionAskParameters defaultQuestionText]
+ -[AXLiveRecognitionAskParameters preferredInputType]
+ -[AXLiveRecognitionAskParameters setActivity:]
+ -[AXLiveRecognitionAskParameters useDefaultQuestion]
+ -[AXLiveRecognitionAskParameters volumeButtonRecaptureEnabled]
+ -[AXSettings(LegacyImplementation) liveRecognitionAskSessionUsesActivity]
+ -[AXSettings(LegacyImplementation) setLiveRecognitionAskSessionUsesActivity:]
+ -[AXSettings(LegacyImplementation) switchControlMenuItemTypeEnabled:]
+ -[AXVOLiveRecognitionActivity askAllowsFollowUpQuestions]
+ -[AXVOLiveRecognitionActivity askAutomaticCaptureEnabled]
+ -[AXVOLiveRecognitionActivity askDefaultQuestionText]
+ -[AXVOLiveRecognitionActivity askPreferredInputType]
+ -[AXVOLiveRecognitionActivity askUseDefaultQuestion]
+ -[AXVOLiveRecognitionActivity askVolumeButtonRecaptureEnabled]
+ -[AXVOLiveRecognitionActivity ask]
+ -[AXVOLiveRecognitionActivity isAskOnly]
+ -[AXVOLiveRecognitionActivity setAsk:]
+ -[AXVOLiveRecognitionActivity setAskAllowsFollowUpQuestions:]
+ -[AXVOLiveRecognitionActivity setAskAutomaticCaptureEnabled:]
+ -[AXVOLiveRecognitionActivity setAskDefaultQuestionText:]
+ -[AXVOLiveRecognitionActivity setAskPreferredInputType:]
+ -[AXVOLiveRecognitionActivity setAskUseDefaultQuestion:]
+ -[AXVOLiveRecognitionActivity setAskVolumeButtonRecaptureEnabled:]
+ GCC_except_table1003
+ GCC_except_table1022
+ GCC_except_table103
+ GCC_except_table1049
+ GCC_except_table108
+ GCC_except_table1115
+ GCC_except_table112
+ GCC_except_table114
+ GCC_except_table1143
+ GCC_except_table1146
+ GCC_except_table1232
+ GCC_except_table1241
+ GCC_except_table1252
+ GCC_except_table1259
+ GCC_except_table1262
+ GCC_except_table1268
+ GCC_except_table1271
+ GCC_except_table1273
+ GCC_except_table1339
+ GCC_except_table1341
+ GCC_except_table1344
+ GCC_except_table1351
+ GCC_except_table1364
+ GCC_except_table1369
+ GCC_except_table1370
+ GCC_except_table1616
+ GCC_except_table1627
+ GCC_except_table1629
+ GCC_except_table1717
+ GCC_except_table1755
+ GCC_except_table1790
+ GCC_except_table1823
+ GCC_except_table1868
+ GCC_except_table1888
+ GCC_except_table192
+ GCC_except_table2029
+ GCC_except_table218
+ GCC_except_table2206
+ GCC_except_table2278
+ GCC_except_table2289
+ GCC_except_table2291
+ GCC_except_table2300
+ GCC_except_table2610
+ GCC_except_table2628
+ GCC_except_table2688
+ GCC_except_table2692
+ GCC_except_table2801
+ GCC_except_table2814
+ GCC_except_table2824
+ GCC_except_table2920
+ GCC_except_table2925
+ GCC_except_table334
+ GCC_except_table3359
+ GCC_except_table3368
+ GCC_except_table3371
+ GCC_except_table3372
+ GCC_except_table3385
+ GCC_except_table3454
+ GCC_except_table3658
+ GCC_except_table366
+ GCC_except_table3662
+ GCC_except_table3667
+ GCC_except_table3689
+ GCC_except_table3711
+ GCC_except_table383
+ GCC_except_table3833
+ GCC_except_table429
+ GCC_except_table436
+ GCC_except_table442
+ GCC_except_table491
+ GCC_except_table558
+ GCC_except_table59
+ GCC_except_table606
+ GCC_except_table621
+ GCC_except_table627
+ GCC_except_table640
+ GCC_except_table654
+ GCC_except_table766
+ GCC_except_table87
+ GCC_except_table874
+ GCC_except_table93
+ GCC_except_table955
+ GCC_except_table976
+ OBJC_IVAR_$_AXLiveRecognitionAskParameters._activity
+ OBJC_IVAR_$_AXVOLiveRecognitionActivity._ask
+ OBJC_IVAR_$_AXVOLiveRecognitionActivity._askAllowsFollowUpQuestions
+ OBJC_IVAR_$_AXVOLiveRecognitionActivity._askAutomaticCaptureEnabled
+ OBJC_IVAR_$_AXVOLiveRecognitionActivity._askDefaultQuestionText
+ OBJC_IVAR_$_AXVOLiveRecognitionActivity._askPreferredInputType
+ OBJC_IVAR_$_AXVOLiveRecognitionActivity._askUseDefaultQuestion
+ OBJC_IVAR_$_AXVOLiveRecognitionActivity._askVolumeButtonRecaptureEnabled
+ _AXGenerativeModelAssetsReady
+ _AXIPCMessageKeyCarouselCanShowAppSwitcher
+ _AXIPCMessageKeyCarouselIsStingPresentingBlockingContent
+ _OBJC_CLASS_$_AXLiveRecognitionAskParameters
+ _OBJC_METACLASS_$_AXLiveRecognitionAskParameters
+ __OBJC_$_CLASS_METHODS_AXLiveRecognitionAskParameters
+ __OBJC_$_CLASS_PROP_LIST_AXLiveRecognitionAskParameters
+ __OBJC_$_INSTANCE_METHODS_AXLiveRecognitionAskParameters
+ __OBJC_$_INSTANCE_VARIABLES_AXLiveRecognitionAskParameters
+ __OBJC_$_PROP_LIST_AXLiveRecognitionAskParameters
+ __OBJC_CLASS_RO_$_AXLiveRecognitionAskParameters
+ __OBJC_METACLASS_RO_$_AXLiveRecognitionAskParameters
+ ___76+[AXTripleClickHelpers _toggleSmartInvertColorsOffMainThreadWithCompletion:]_block_invoke
+ ___block_descriptor_49_e8_32bs40r_e5_v8?0l
+ ___copy_helper_block_e8_32b40r
+ _objc_msgSend$_handleToggleTripleClickTriggeredFromAppIntent:completion:
+ _objc_msgSend$_localToggleAccessibilityShortcutOption:completion:
+ _objc_msgSend$_localToggleTripleClickOption:completion:
+ _objc_msgSend$_toggleClassicInvertColorsOffMainThreadWithCompletion:
+ _objc_msgSend$_toggleSmartInvertColorsOffMainThreadWithCompletion:
+ _objc_msgSend$activity
+ _objc_msgSend$ask
+ _objc_msgSend$askAllowsFollowUpQuestions
+ _objc_msgSend$askAutomaticCaptureEnabled
+ _objc_msgSend$askDefaultQuestionText
+ _objc_msgSend$askPreferredInputType
+ _objc_msgSend$askUseDefaultQuestion
+ _objc_msgSend$askVolumeButtonRecaptureEnabled
+ _objc_msgSend$assetIsNotReadyWithUseCaseIdentifiers:language:
+ _objc_msgSend$liveRecognitionActivity
+ _objc_msgSend$liveRecognitionAskSessionUsesActivity
+ _objc_msgSend$liveRecognitionDefaultQuestionText
+ _objc_msgSend$liveRecognitionPreferredAskInputType
+ _objc_msgSend$liveRecognitionUseDefaultQuestion
+ _objc_msgSend$liveRecognitionVolumeButtonRecaptureEnabled
+ _objc_msgSend$setActivity:
+ _objc_msgSend$setAsk:
+ _objc_msgSend$setAskAllowsFollowUpQuestions:
+ _objc_msgSend$setAskAutomaticCaptureEnabled:
+ _objc_msgSend$setAskDefaultQuestionText:
+ _objc_msgSend$setAskPreferredInputType:
+ _objc_msgSend$setAskUseDefaultQuestion:
+ _objc_msgSend$setAskVolumeButtonRecaptureEnabled:
+ _symbolic _____Sg_ABt s11AnyHashableV
- AccessibilityUIUtilitiesLibraryCore.frameworkLibrary
- GCC_except_table100
- GCC_except_table1018
- GCC_except_table102
- GCC_except_table104
- GCC_except_table1045
- GCC_except_table1111
- GCC_except_table1135
- GCC_except_table1142
- GCC_except_table1228
- GCC_except_table1237
- GCC_except_table1244
- GCC_except_table1255
- GCC_except_table1258
- GCC_except_table1260
- GCC_except_table1267
- GCC_except_table1269
- GCC_except_table1335
- GCC_except_table1337
- GCC_except_table1340
- GCC_except_table1343
- GCC_except_table1360
- GCC_except_table1362
- GCC_except_table1365
- GCC_except_table1608
- GCC_except_table1615
- GCC_except_table1621
- GCC_except_table1713
- GCC_except_table1751
- GCC_except_table1786
- GCC_except_table1819
- GCC_except_table1864
- GCC_except_table187
- GCC_except_table1884
- GCC_except_table2024
- GCC_except_table213
- GCC_except_table2201
- GCC_except_table2273
- GCC_except_table2284
- GCC_except_table2286
- GCC_except_table2295
- GCC_except_table2605
- GCC_except_table2623
- GCC_except_table2683
- GCC_except_table2687
- GCC_except_table2794
- GCC_except_table2807
- GCC_except_table2817
- GCC_except_table2913
- GCC_except_table2918
- GCC_except_table329
- GCC_except_table3326
- GCC_except_table3335
- GCC_except_table3338
- GCC_except_table3339
- GCC_except_table3352
- GCC_except_table3421
- GCC_except_table361
- GCC_except_table3625
- GCC_except_table3629
- GCC_except_table3634
- GCC_except_table3656
- GCC_except_table3678
- GCC_except_table378
- GCC_except_table3800
- GCC_except_table424
- GCC_except_table432
- GCC_except_table438
- GCC_except_table487
- GCC_except_table554
- GCC_except_table58
- GCC_except_table602
- GCC_except_table617
- GCC_except_table623
- GCC_except_table636
- GCC_except_table650
- GCC_except_table762
- GCC_except_table85
- GCC_except_table870
- GCC_except_table95
- GCC_except_table951
- GCC_except_table972
- GCC_except_table98
- GCC_except_table999
- ___61+[AXTripleClickHelpers _toggleSmartInvertColorsOffMainThread]_block_invoke
- ___AccessibilityUIUtilitiesLibraryCore_block_invoke
- ___getAXUIAssistiveTouchStringForNameSymbolLoc_block_invoke
- _audit_stringAccessibilityUIUtilities
- _soft_AXUIAssistiveTouchStringForName
- getAXUIAssistiveTouchStringForNameSymbolLoc.ptr
CStrings:
+ "AXMagnifierGenerativeModelsAvailable: partnerAllowedInRegion=%d status=%ld assetsReady=%d"
+ "AXSLiveRecognitionAskSessionUsesActivity"
+ "Giving up on Guided Access session request: out of retry attempts."
+ "R"
+ "ask"
+ "askAllowsFollowUpQuestions"
+ "askAutomaticCaptureEnabled"
+ "askDefaultQuestionText"
+ "askPreferredInputType"
+ "askUseDefaultQuestion"
+ "askVolumeButtonRecaptureEnabled"
+ "com.apple.FoundationModels"
- "/System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/Contents/MacOS/AccessibilityUIUtilities"
- "AXMagnifierGenerativeModelsAvailable: partnerAllowedInRegion=%d status=%ld"
- "AXUIAssistiveTouchStringForName"
- "NSString *soft_AXUIAssistiveTouchStringForName(NSString *__strong, BOOL)"
- "ask.sheet.option.detection.mode"
- "softlink:r:path:/System/Library/PrivateFrameworks/AccessibilityUIUtilities.framework/AccessibilityUIUtilities"
- "void *AccessibilityUIUtilitiesLibrary(void)"
```
