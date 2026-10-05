## CoreSpeech

> `/System/Library/PrivateFrameworks/CoreSpeech.framework/Versions/A/CoreSpeech`

```diff

-3605.25.2.0.0
-  __TEXT.__text: 0x139958
+3605.31.3.0.0
+  __TEXT.__text: 0x13a9c0
   __TEXT.__lazy_helpers: 0x54
-  __TEXT.__objc_methlist: 0x13f64
+  __TEXT.__objc_methlist: 0x1407c
   __TEXT.__const: 0x3fc
   __TEXT.__dlopen_cstrs: 0x4e
-  __TEXT.__gcc_except_tab: 0x31d8
-  __TEXT.__cstring: 0x2550f
-  __TEXT.__oslogstring: 0x1e08d
-  __TEXT.__unwind_info: 0x5ca8
+  __TEXT.__gcc_except_tab: 0x321c
+  __TEXT.__cstring: 0x2564f
+  __TEXT.__oslogstring: 0x1e2de
+  __TEXT.__unwind_info: 0x5d00
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xd40
+  __DATA_CONST.__const: 0xd48
   __DATA_CONST.__objc_classlist: 0x830
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x4a8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xa4e8
+  __DATA_CONST.__objc_selrefs: 0xa5b8
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x650
   __DATA_CONST.__objc_arraydata: 0x3f8
-  __DATA_CONST.__got: 0x1888
-  __AUTH_CONST.__const: 0x5890
-  __AUTH_CONST.__cfstring: 0x9100
-  __AUTH_CONST.__objc_const: 0x1fae0
+  __DATA_CONST.__got: 0x1898
+  __AUTH_CONST.__const: 0x5950
+  __AUTH_CONST.__cfstring: 0x9120
+  __AUTH_CONST.__objc_const: 0x1fc58
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__lazy_load_got: 0x8
   __AUTH_CONST.__objc_intobj: 0x900

   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__auth_got: 0xc10
   __AUTH.__objc_data: 0x3b10
-  __DATA.__objc_ivar: 0x182c
+  __DATA.__objc_ivar: 0x184c
   __DATA.__data: 0x3774
   __DATA.__bss: 0x5d0
   __DATA.__common: 0x10

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 7771
-  Symbols:   17093
-  CStrings:  5159
+  Functions: 7802
+  Symbols:   17156
+  CStrings:  5174
 
Symbols:
+ -[CSEndpointDelayReporter analytics]
+ -[CSEndpointDelayReporter selfLoggingStream]
+ -[CSEndpointDelayReporter setAnalytics:]
+ -[CSEndpointDelayReporter setSelfLoggingStream:]
+ -[CSSiriAudioActivationInfo myriadElectionIdentity]
+ -[CSSiriSpeechRecorder _playStopAlertWithError:]
+ -[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]
+ -[CSSiriSpeechRecorder electionLedger]
+ -[CSSiriSpeechRecorder setElectionLedger:]
+ -[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]
+ -[CSSpeechController _invalidateRecordSessionActivationState]
+ -[CSSpeechController _noteAudioSessionActivatedForRecord:]
+ -[CSSpeechController _notifyDelegateDidStartRecordingSuccessfully:error:]
+ -[CSSpeechController didActivateAudioSessionForRecord]
+ -[CSSpeechController prefetchedAudioDeviceInfo]
+ -[CSSpeechController setDidActivateAudioSessionForRecord:]
+ -[CSSpeechController setPrefetchedAudioDeviceInfo:]
+ -[CSVoiceTriggerSecondPass requestExclaveAudio]
+ -[CSVoiceTriggerSecondPass setRequestExclaveAudio:]
+ -[CSXPCClient _sendMessageAndReplySync:reply:error:]
+ -[CSXPCClient activateAudioSessionWithReason:dynamicAttribute:bundleID:audioDeviceInfo:error:]
+ GCC_except_table1241
+ GCC_except_table1255
+ GCC_except_table1462
+ GCC_except_table1536
+ GCC_except_table1588
+ GCC_except_table1612
+ GCC_except_table1616
+ GCC_except_table1632
+ GCC_except_table1635
+ GCC_except_table1661
+ GCC_except_table1668
+ GCC_except_table1677
+ GCC_except_table1780
+ GCC_except_table1786
+ GCC_except_table180
+ GCC_except_table1846
+ GCC_except_table1872
+ GCC_except_table1878
+ GCC_except_table1959
+ GCC_except_table1981
+ GCC_except_table2085
+ GCC_except_table210
+ GCC_except_table2222
+ GCC_except_table2225
+ GCC_except_table2228
+ GCC_except_table2233
+ GCC_except_table2245
+ GCC_except_table2250
+ GCC_except_table2253
+ GCC_except_table2256
+ GCC_except_table2259
+ GCC_except_table2352
+ GCC_except_table2397
+ GCC_except_table2402
+ GCC_except_table2409
+ GCC_except_table2427
+ GCC_except_table2457
+ GCC_except_table2562
+ GCC_except_table261
+ GCC_except_table2621
+ GCC_except_table2633
+ GCC_except_table2664
+ GCC_except_table2689
+ GCC_except_table2700
+ GCC_except_table272
+ GCC_except_table2737
+ GCC_except_table2738
+ GCC_except_table2742
+ GCC_except_table2745
+ GCC_except_table2748
+ GCC_except_table2749
+ GCC_except_table2752
+ GCC_except_table2753
+ GCC_except_table2762
+ GCC_except_table2770
+ GCC_except_table2771
+ GCC_except_table2799
+ GCC_except_table286
+ GCC_except_table289
+ GCC_except_table3071
+ GCC_except_table3146
+ GCC_except_table3183
+ GCC_except_table3213
+ GCC_except_table3216
+ GCC_except_table3219
+ GCC_except_table3250
+ GCC_except_table3310
+ GCC_except_table3467
+ GCC_except_table3493
+ GCC_except_table3521
+ GCC_except_table3559
+ GCC_except_table3560
+ GCC_except_table3562
+ GCC_except_table3564
+ GCC_except_table3580
+ GCC_except_table3584
+ GCC_except_table3586
+ GCC_except_table3588
+ GCC_except_table3592
+ GCC_except_table3595
+ GCC_except_table3603
+ GCC_except_table3619
+ GCC_except_table3621
+ GCC_except_table3629
+ GCC_except_table3633
+ GCC_except_table3635
+ GCC_except_table3636
+ GCC_except_table3637
+ GCC_except_table3638
+ GCC_except_table3641
+ GCC_except_table3642
+ GCC_except_table3653
+ GCC_except_table3658
+ GCC_except_table3659
+ GCC_except_table3660
+ GCC_except_table3661
+ GCC_except_table3773
+ GCC_except_table3797
+ GCC_except_table3863
+ GCC_except_table3879
+ GCC_except_table3900
+ GCC_except_table395
+ GCC_except_table3992
+ GCC_except_table4245
+ GCC_except_table4302
+ GCC_except_table4303
+ GCC_except_table4307
+ GCC_except_table4310
+ GCC_except_table4314
+ GCC_except_table4339
+ GCC_except_table4342
+ GCC_except_table4397
+ GCC_except_table4403
+ GCC_except_table4760
+ GCC_except_table4920
+ GCC_except_table4930
+ GCC_except_table4954
+ GCC_except_table4974
+ GCC_except_table5058
+ GCC_except_table5072
+ GCC_except_table5090
+ GCC_except_table5096
+ GCC_except_table5101
+ GCC_except_table5109
+ GCC_except_table5113
+ GCC_except_table5119
+ GCC_except_table5121
+ GCC_except_table5139
+ GCC_except_table5146
+ GCC_except_table5151
+ GCC_except_table5155
+ GCC_except_table5158
+ GCC_except_table5163
+ GCC_except_table5167
+ GCC_except_table5168
+ GCC_except_table5169
+ GCC_except_table5172
+ GCC_except_table5174
+ GCC_except_table5175
+ GCC_except_table5176
+ GCC_except_table5195
+ GCC_except_table5226
+ GCC_except_table5335
+ GCC_except_table5365
+ GCC_except_table5368
+ GCC_except_table5458
+ GCC_except_table5472
+ GCC_except_table5479
+ GCC_except_table5499
+ GCC_except_table5503
+ GCC_except_table5513
+ GCC_except_table5757
+ GCC_except_table5763
+ GCC_except_table5796
+ GCC_except_table5801
+ GCC_except_table5838
+ GCC_except_table5847
+ GCC_except_table5877
+ GCC_except_table5963
+ GCC_except_table597
+ GCC_except_table6187
+ GCC_except_table6195
+ GCC_except_table6215
+ GCC_except_table6220
+ GCC_except_table6329
+ GCC_except_table6399
+ GCC_except_table6421
+ GCC_except_table6422
+ GCC_except_table6432
+ GCC_except_table6433
+ GCC_except_table6445
+ GCC_except_table6476
+ GCC_except_table6487
+ GCC_except_table6492
+ GCC_except_table6497
+ GCC_except_table6529
+ GCC_except_table655
+ GCC_except_table6611
+ GCC_except_table6637
+ GCC_except_table6648
+ GCC_except_table6651
+ GCC_except_table6674
+ GCC_except_table6686
+ GCC_except_table6729
+ GCC_except_table6875
+ GCC_except_table6911
+ GCC_except_table6962
+ GCC_except_table7017
+ GCC_except_table7040
+ GCC_except_table7076
+ GCC_except_table7095
+ GCC_except_table7105
+ GCC_except_table7115
+ GCC_except_table7156
+ GCC_except_table7163
+ GCC_except_table7185
+ GCC_except_table720
+ GCC_except_table7234
+ GCC_except_table724
+ GCC_except_table728
+ GCC_except_table7325
+ GCC_except_table7326
+ GCC_except_table7327
+ GCC_except_table7328
+ GCC_except_table7329
+ GCC_except_table7334
+ GCC_except_table735
+ GCC_except_table7398
+ GCC_except_table7446
+ GCC_except_table7452
+ GCC_except_table7455
+ GCC_except_table7494
+ GCC_except_table7500
+ GCC_except_table7506
+ GCC_except_table7638
+ GCC_except_table903
+ GCC_except_table921
+ GCC_except_table926
+ OBJC_IVAR_$_CSEndpointDelayReporter._analytics
+ OBJC_IVAR_$_CSEndpointDelayReporter._selfLoggingStream
+ OBJC_IVAR_$_CSSiriAudioActivationInfo._myriadElectionIdentity
+ OBJC_IVAR_$_CSSiriSpeechRecorder._electionLedgerOverride
+ OBJC_IVAR_$_CSSiriSpeechRecordingContext._electionIdentity
+ OBJC_IVAR_$_CSSpeechController._didActivateAudioSessionForRecord
+ OBJC_IVAR_$_CSSpeechController._prefetchedAudioDeviceInfo
+ OBJC_IVAR_$_CSVoiceTriggerSecondPass._requestExclaveAudio
+ _OBJC_CLASS_$_CSFModelConfigDecoder
+ _OBJC_CLASS_$_SCDAElectionLedger
+ __70-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]_block_invoke
+ __79-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke
+ __97-[CSSiriSpeechRecorder speechControllerDidDetectVoiceTriggerTwoShot:atTime:wantsAudibleFeedback:]_block_invoke_2
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CSAudioSessionProviding
+ ___52-[CSXPCClient _sendMessageAndReplySync:reply:error:]_block_invoke
+ ___58-[CSSpeechController _noteAudioSessionActivatedForRecord:]_block_invoke
+ ___70-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]_block_invoke
+ ___70-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]_block_invoke_2
+ ___79-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke
+ ___79-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke_2
+ ___block_descriptor_40_e8_32bs_e32_v20?0B8"SCDAElectionOutcome"12l
+ ___block_descriptor_40_e8_32bs_e8_v12?0B8l
+ ___block_descriptor_41_e8_32bs_e5_v8?0l
+ ___block_descriptor_49_e8_32s40w_e8_v12?0B8l
+ ___block_descriptor_59_e8_32s40r_e20_v20?0B8"NSError"12l
+ ___block_descriptor_68_e8_32s40s48r_e5_v8?0l
+ _objc_msgSend$_invalidateRecordSessionActivationState
+ _objc_msgSend$_noteAudioSessionActivatedForRecord:
+ _objc_msgSend$_notifyDelegateDidStartRecordingSuccessfully:error:
+ _objc_msgSend$_playStopAlertWithError:
+ _objc_msgSend$_sendMessageAndReplySync:reply:error:
+ _objc_msgSend$_waitForElectionThenPlayStopAlertWithError:recordRoute:
+ _objc_msgSend$activateAudioSessionWithReason:dynamicAttribute:bundleID:audioDeviceInfo:error:
+ _objc_msgSend$analytics
+ _objc_msgSend$candidates
+ _objc_msgSend$decisionForElection:reason:detail:deliverOn:completion:
+ _objc_msgSend$decodeJsonFromFile:
+ _objc_msgSend$defaultOptionWithTimeout:requestExclaveAudio:
+ _objc_msgSend$electionLedger
+ _objc_msgSend$initWithTimeout:clientIdentity:requireRecordModeLock:requireListeningMicIndicatorLock:requestExclaveAudio:
+ _objc_msgSend$myriadElectionIdentity
+ _objc_msgSend$purgeCachedConfigs
+ _objc_msgSend$requestExclaveAudio
+ _objc_msgSend$selfLoggingStream
+ _objc_msgSend$sharedLedger
+ _objc_msgSend$streamRequest
+ _objc_msgSend$supportEarlyRecordingStartNotification
+ _objc_msgSend$suppressUtteranceGradingIfRequiredForElection:
- GCC_except_table1239
- GCC_except_table1253
- GCC_except_table1460
- GCC_except_table1534
- GCC_except_table1586
- GCC_except_table1610
- GCC_except_table1614
- GCC_except_table1630
- GCC_except_table1633
- GCC_except_table1659
- GCC_except_table1666
- GCC_except_table1675
- GCC_except_table1774
- GCC_except_table178
- GCC_except_table1784
- GCC_except_table1844
- GCC_except_table1870
- GCC_except_table1876
- GCC_except_table1957
- GCC_except_table1979
- GCC_except_table208
- GCC_except_table2083
- GCC_except_table2220
- GCC_except_table2223
- GCC_except_table2226
- GCC_except_table2231
- GCC_except_table2243
- GCC_except_table2248
- GCC_except_table2251
- GCC_except_table2254
- GCC_except_table2257
- GCC_except_table2350
- GCC_except_table2395
- GCC_except_table2400
- GCC_except_table2407
- GCC_except_table2425
- GCC_except_table2455
- GCC_except_table2560
- GCC_except_table259
- GCC_except_table2619
- GCC_except_table2631
- GCC_except_table2662
- GCC_except_table2687
- GCC_except_table2698
- GCC_except_table270
- GCC_except_table2732
- GCC_except_table2733
- GCC_except_table2740
- GCC_except_table2743
- GCC_except_table2746
- GCC_except_table2747
- GCC_except_table2750
- GCC_except_table2751
- GCC_except_table2760
- GCC_except_table2766
- GCC_except_table2769
- GCC_except_table2797
- GCC_except_table284
- GCC_except_table287
- GCC_except_table3065
- GCC_except_table3139
- GCC_except_table3176
- GCC_except_table3203
- GCC_except_table3206
- GCC_except_table3209
- GCC_except_table3240
- GCC_except_table3300
- GCC_except_table3457
- GCC_except_table3483
- GCC_except_table3511
- GCC_except_table3546
- GCC_except_table3547
- GCC_except_table3549
- GCC_except_table3551
- GCC_except_table3567
- GCC_except_table3569
- GCC_except_table3571
- GCC_except_table3573
- GCC_except_table3575
- GCC_except_table3577
- GCC_except_table3579
- GCC_except_table3593
- GCC_except_table3600
- GCC_except_table3602
- GCC_except_table3604
- GCC_except_table3608
- GCC_except_table3610
- GCC_except_table3611
- GCC_except_table3612
- GCC_except_table3616
- GCC_except_table3620
- GCC_except_table3622
- GCC_except_table3627
- GCC_except_table3631
- GCC_except_table3646
- GCC_except_table3647
- GCC_except_table3759
- GCC_except_table3783
- GCC_except_table3849
- GCC_except_table3865
- GCC_except_table3886
- GCC_except_table393
- GCC_except_table3978
- GCC_except_table4231
- GCC_except_table4288
- GCC_except_table4289
- GCC_except_table4293
- GCC_except_table4296
- GCC_except_table4300
- GCC_except_table4325
- GCC_except_table4328
- GCC_except_table4383
- GCC_except_table4389
- GCC_except_table4745
- GCC_except_table4905
- GCC_except_table4915
- GCC_except_table4939
- GCC_except_table4959
- GCC_except_table5043
- GCC_except_table5057
- GCC_except_table5066
- GCC_except_table5075
- GCC_except_table5083
- GCC_except_table5086
- GCC_except_table5094
- GCC_except_table5104
- GCC_except_table5106
- GCC_except_table5124
- GCC_except_table5131
- GCC_except_table5136
- GCC_except_table5138
- GCC_except_table5140
- GCC_except_table5142
- GCC_except_table5143
- GCC_except_table5144
- GCC_except_table5145
- GCC_except_table5148
- GCC_except_table5152
- GCC_except_table5154
- GCC_except_table5161
- GCC_except_table5165
- GCC_except_table5211
- GCC_except_table5320
- GCC_except_table5350
- GCC_except_table5353
- GCC_except_table5443
- GCC_except_table5457
- GCC_except_table5464
- GCC_except_table5486
- GCC_except_table5490
- GCC_except_table5500
- GCC_except_table5744
- GCC_except_table5750
- GCC_except_table5783
- GCC_except_table5788
- GCC_except_table5825
- GCC_except_table5834
- GCC_except_table5864
- GCC_except_table5946
- GCC_except_table595
- GCC_except_table6170
- GCC_except_table6178
- GCC_except_table6198
- GCC_except_table6203
- GCC_except_table6312
- GCC_except_table6382
- GCC_except_table6404
- GCC_except_table6405
- GCC_except_table6415
- GCC_except_table6416
- GCC_except_table6428
- GCC_except_table6459
- GCC_except_table6470
- GCC_except_table6475
- GCC_except_table6480
- GCC_except_table6512
- GCC_except_table653
- GCC_except_table6594
- GCC_except_table6620
- GCC_except_table6631
- GCC_except_table6634
- GCC_except_table6657
- GCC_except_table6669
- GCC_except_table6712
- GCC_except_table6858
- GCC_except_table6894
- GCC_except_table6945
- GCC_except_table7000
- GCC_except_table7023
- GCC_except_table7064
- GCC_except_table7074
- GCC_except_table7084
- GCC_except_table7125
- GCC_except_table7132
- GCC_except_table7154
- GCC_except_table718
- GCC_except_table7203
- GCC_except_table722
- GCC_except_table726
- GCC_except_table7294
- GCC_except_table7295
- GCC_except_table7296
- GCC_except_table7297
- GCC_except_table7298
- GCC_except_table7303
- GCC_except_table733
- GCC_except_table7367
- GCC_except_table7415
- GCC_except_table7421
- GCC_except_table7424
- GCC_except_table7432
- GCC_except_table7438
- GCC_except_table7475
- GCC_except_table7607
- GCC_except_table901
- GCC_except_table919
- GCC_except_table924
- ___45-[CSXPCClient sendMessageAndReplySync:error:]_block_invoke
- ___58-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequired]_block_invoke
- ___block_descriptor_58_e8_32s40r_e20_v20?0B8"NSError"12l
- ___block_descriptor_67_e8_32s40s48r_e5_v8?0l
- _objc_msgSend$defaultOptionWithTimeout:
- _objc_msgSend$didWin
- _objc_msgSend$isMonitoring
CStrings:
+ "%s Audio session activated for record, audioDeviceInfo = %{public}@"
+ "%s Audio session was already activated for record, skipping activation in startRecording"
+ "%s Audio stream failed to start after reporting didStartRecording early, will report didStop : %{public}@"
+ "%s Audio stream started, didStartRecording was already reported early"
+ "%s BTLE Myriad loss; not playing speech stop alert"
+ "%s BTLE recorder is gone; not playing speech stop alert"
+ "%s BTLE request was cancelled; not playing speech stop alert"
+ "%s BTLE speech controller began waiting for Myriad decision (identity %@)"
+ "%s Invalidating cached record session activation state"
+ "%s Reporting didStartRecording early, ahead of the audio stream start"
+ "%s isSiriMode=%d, speechEvent=%ld, wasRequestCancelled=%d, shouldSuppressAlert=%d, recordRoute=%@"
+ "%s stop alert: didWin=%d, withError=%d, recordRoute=%@"
+ "-[CSSiriSpeechRecorder _playStopAlertWithError:]"
+ "-[CSSiriSpeechRecorder _waitForElectionThenPlayStopAlertWithError:recordRoute:]_block_invoke"
+ "-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequiredForElection:]_block_invoke"
+ "-[CSSpeechController _invalidateRecordSessionActivationState]"
+ "-[CSSpeechController _noteAudioSessionActivatedForRecord:]_block_invoke"
+ "-[CSSpeechController _notifyDelegateDidStartRecordingSuccessfully:error:]"
+ "Recording stop alert"
+ "requestAudioDeviceInfo"
+ "v20@?0B8@\"SCDAElectionOutcome\"12"
+ "\xa5"
+ "\xf03"
- "%s BTLE Myriad Not explicitly playing speech stop alert"
- "%s BTLE speech controller began waiting for Myriad decision"
- "%s isSiriMode=%d, speechEvent=%ld, wasRequestCancelled=%d, shouldSuppressAlert=%d, isMonitoringMyriadEvents=%d, didMyriadWin=%d, recordRoute=%@"
- "-[CSEndpointAnalyzerBase getHybridEndpointerConfigForAsset:]"
- "-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequired]"
- "-[CSSiriSpeechRecorder suppressUtteranceGradingIfRequired]_block_invoke"
- "\xa3"
- "\xf0#"
```
