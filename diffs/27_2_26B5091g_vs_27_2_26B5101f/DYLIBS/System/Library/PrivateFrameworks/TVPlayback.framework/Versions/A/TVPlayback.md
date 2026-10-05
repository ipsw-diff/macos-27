## TVPlayback

> `/System/Library/PrivateFrameworks/TVPlayback.framework/Versions/A/TVPlayback`

```diff

-635.10.12.0.0
-  __TEXT.__text: 0x1485e8
-  __TEXT.__objc_methlist: 0x5a38
+635.10.14.0.0
+  __TEXT.__text: 0x148b0c
+  __TEXT.__objc_methlist: 0x5ad8
   __TEXT.__const: 0x22e90
-  __TEXT.__cstring: 0x67fe
-  __TEXT.__oslogstring: 0x5996
+  __TEXT.__cstring: 0x6848
+  __TEXT.__oslogstring: 0x59a2
   __TEXT.__gcc_except_tab: 0x1d84
-  __TEXT.__unwind_info: 0x1c90
+  __TEXT.__unwind_info: 0x1ca0
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3c68
+  __DATA_CONST.__objc_selrefs: 0x3cc0
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x160
   __DATA_CONST.__objc_arraydata: 0x10
   __DATA_CONST.__got: 0x770
   __AUTH_CONST.__const: 0xbac0
   __AUTH_CONST.__cfstring: 0x6700
-  __AUTH_CONST.__objc_const: 0x8ba8
+  __AUTH_CONST.__objc_const: 0x8c68
   __AUTH_CONST.__objc_intobj: 0x4e0
   __AUTH_CONST.__objc_arrayobj: 0x30
-  __AUTH_CONST.__auth_got: 0x3a0
+  __AUTH_CONST.__auth_got: 0x3a8
   __AUTH.__objc_data: 0x7d0
-  __DATA.__objc_ivar: 0x6d8
+  __DATA.__objc_ivar: 0x6e8
   __DATA.__data: 0x1040
   __DATA.__bss: 0x110
   __DATA.__common: 0x9f0

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2371
-  Symbols:   5472
-  CStrings:  1308
+  Functions: 2384
+  Symbols:   5502
+  CStrings:  1309
 
Symbols:
+ +[TVPPlayer _downloadedOptionsInGroup:ofAsset:]
+ +[TVPPlayer _updateVideoSelectionCriteriaForAVQueuePlayer:isInterstitialPlayer:preferredSignLanguage:]
+ +[TVPPlayer savedPreferredSignLanguage]
+ -[TVPPlayer _downloadedSignLanguageOptions]
+ -[TVPPlayer _effectiveSignLanguage]
+ -[TVPPlayer _signLanguageForSelectionCriteria]
+ -[TVPPlayer allowsSignLanguageSelection]
+ -[TVPPlayer preferredSignLanguage]
+ -[TVPPlayer setAllowsSignLanguageSelection:]
+ -[TVPPlayer setPreferredSignLanguage:]
+ -[TVPPlayer setSignLanguageChosenByViewer:]
+ -[TVPPlayer signLanguageChosenByViewer]
+ -[TVPVideoOption initWithOption:isDefault:isDownloaded:]
+ -[TVPVideoOption isDownloaded]
+ -[TVPVideoOption setIsDownloaded:]
+ GCC_except_table255
+ GCC_except_table261
+ GCC_except_table265
+ GCC_except_table268
+ GCC_except_table317
+ GCC_except_table349
+ GCC_except_table367
+ GCC_except_table394
+ GCC_except_table398
+ GCC_except_table408
+ GCC_except_table416
+ GCC_except_table440
+ GCC_except_table448
+ GCC_except_table453
+ GCC_except_table460
+ GCC_except_table461
+ GCC_except_table463
+ GCC_except_table470
+ GCC_except_table474
+ GCC_except_table479
+ GCC_except_table483
+ GCC_except_table488
+ GCC_except_table496
+ GCC_except_table498
+ GCC_except_table500
+ GCC_except_table527
+ GCC_except_table529
+ GCC_except_table531
+ GCC_except_table540
+ GCC_except_table549
+ GCC_except_table551
+ GCC_except_table554
+ GCC_except_table559
+ GCC_except_table569
+ GCC_except_table577
+ GCC_except_table580
+ GCC_except_table592
+ GCC_except_table594
+ GCC_except_table597
+ GCC_except_table601
+ OBJC_IVAR_$_TVPPlayer._allowsSignLanguageSelection
+ OBJC_IVAR_$_TVPPlayer._preferredSignLanguage
+ OBJC_IVAR_$_TVPPlayer._signLanguageChosenByViewer
+ OBJC_IVAR_$_TVPVideoOption._isDownloaded
+ _TVPSignLanguageDownloadLanguage
+ _notify_post
+ _objc_msgSend$_downloadedOptionsInGroup:ofAsset:
+ _objc_msgSend$_downloadedSignLanguageOptions
+ _objc_msgSend$_effectiveSignLanguage
+ _objc_msgSend$_signLanguageForSelectionCriteria
+ _objc_msgSend$_updateVideoSelectionCriteriaForAVQueuePlayer:isInterstitialPlayer:preferredSignLanguage:
+ _objc_msgSend$allowsSignLanguageSelection
+ _objc_msgSend$hasSignLanguage
+ _objc_msgSend$initWithOption:isDefault:isDownloaded:
+ _objc_msgSend$preferredSignLanguage
+ _objc_msgSend$savedPreferredSignLanguage
+ _objc_msgSend$setPreferredSignLanguage:
+ _objc_msgSend$setSignLanguageChosenByViewer:
+ _objc_msgSend$signLanguageChosenByViewer
+ _objc_msgSend$videoOptions
- +[TVPPlayer _updateVideoSelectionCriteriaForAVQueuePlayer:isInterstitialPlayer:]
- -[TVPVideoOption initWithOption:isDefault:]
- GCC_except_table253
- GCC_except_table259
- GCC_except_table263
- GCC_except_table266
- GCC_except_table315
- GCC_except_table347
- GCC_except_table361
- GCC_except_table388
- GCC_except_table392
- GCC_except_table402
- GCC_except_table410
- GCC_except_table434
- GCC_except_table441
- GCC_except_table442
- GCC_except_table446
- GCC_except_table451
- GCC_except_table454
- GCC_except_table455
- GCC_except_table468
- GCC_except_table473
- GCC_except_table477
- GCC_except_table482
- GCC_except_table490
- GCC_except_table492
- GCC_except_table494
- GCC_except_table521
- GCC_except_table523
- GCC_except_table525
- GCC_except_table528
- GCC_except_table543
- GCC_except_table545
- GCC_except_table548
- GCC_except_table553
- GCC_except_table557
- GCC_except_table571
- GCC_except_table574
- GCC_except_table586
- GCC_except_table588
- GCC_except_table591
- GCC_except_table595
- _TVPSignLanguageSetSettingEnabled
- _objc_msgSend$_updateVideoSelectionCriteriaForAVQueuePlayer:isInterstitialPlayer:
- _objc_msgSend$initWithOption:isDefault:
CStrings:
+ "%@ isDefault: %@ isDownloaded: %@"
+ "Not the same show; clearing the preferred sign language"
+ "PreferredSignLanguageDownload"
+ "com.apple.AppleTV.signLanguageSettingDidChange"
- "%@ isDefault: %@"
- "Setting prefs for video language code to %@"
- "SignLanguageEnabled"
```
