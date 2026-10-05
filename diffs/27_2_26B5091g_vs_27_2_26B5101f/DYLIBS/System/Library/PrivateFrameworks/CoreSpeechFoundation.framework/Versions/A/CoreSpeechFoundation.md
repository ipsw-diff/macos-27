## CoreSpeechFoundation

> `/System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/Versions/A/CoreSpeechFoundation`

```diff

-3605.25.2.0.0
-  __TEXT.__text: 0xc6d64
-  __TEXT.__objc_methlist: 0xd8c8
-  __TEXT.__const: 0xb38
+3605.31.3.0.0
+  __TEXT.__text: 0xc8508
+  __TEXT.__objc_methlist: 0xda60
+  __TEXT.__const: 0xb48
   __TEXT.__dlopen_cstrs: 0x18c
   __TEXT.__constg_swiftt: 0x25c
   __TEXT.__swift5_typeref: 0x19d
   __TEXT.__swift5_builtin: 0x28
   __TEXT.__swift5_types: 0x20
-  __TEXT.__cstring: 0x15b8b
+  __TEXT.__cstring: 0x15ca7
   __TEXT.__swift5_reflstr: 0x174
   __TEXT.__swift5_assocty: 0x18
   __TEXT.__swift5_fieldmd: 0x180
   __TEXT.__swift5_proto: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__gcc_except_tab: 0x3c64
-  __TEXT.__oslogstring: 0x10499
-  __TEXT.__unwind_info: 0x4790
+  __TEXT.__gcc_except_tab: 0x3c70
+  __TEXT.__oslogstring: 0x106cc
+  __TEXT.__unwind_info: 0x47e8
   __TEXT.__eh_frame: 0xe0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xff0
-  __DATA_CONST.__objc_classlist: 0x768
+  __DATA_CONST.__const: 0xff8
+  __DATA_CONST.__objc_classlist: 0x770
   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0x210
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x18
-  __DATA_CONST.__objc_selrefs: 0x72e0
+  __DATA_CONST.__objc_selrefs: 0x73d0
   __DATA_CONST.__objc_protorefs: 0x30
-  __DATA_CONST.__objc_superrefs: 0x560
+  __DATA_CONST.__objc_superrefs: 0x568
   __DATA_CONST.__objc_arraydata: 0x1e0
-  __DATA_CONST.__got: 0xc60
-  __AUTH_CONST.__const: 0x3ac0
-  __AUTH_CONST.__cfstring: 0x9760
-  __AUTH_CONST.__objc_const: 0x14ed8
+  __DATA_CONST.__got: 0xc68
+  __AUTH_CONST.__const: 0x3b20
+  __AUTH_CONST.__cfstring: 0x9780
+  __AUTH_CONST.__objc_const: 0x15130
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_dictobj: 0x1e0
   __AUTH_CONST.__objc_intobj: 0x498
   __AUTH_CONST.__objc_arrayobj: 0xc0
   __AUTH_CONST.__objc_floatobj: 0x1a0
-  __AUTH_CONST.__auth_got: 0xec8
-  __AUTH.__objc_data: 0x268
+  __AUTH_CONST.__auth_got: 0xed0
+  __AUTH.__objc_data: 0x2b8
   __AUTH.__data: 0x18
-  __DATA.__objc_ivar: 0xda0
+  __DATA.__objc_ivar: 0xdc4
   __DATA.__data: 0x1908
-  __DATA.__bss: 0x980
+  __DATA.__bss: 0x9b0
   __DATA_DIRTY.__objc_data: 0x4860
   __DATA_DIRTY.__data: 0x310
-  __DATA_DIRTY.__bss: 0x660
+  __DATA_DIRTY.__bss: 0x650
   __DATA_DIRTY.__common: 0x70
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5260
-  Symbols:   12128
-  CStrings:  3617
+  Functions: 5295
+  Symbols:   12209
+  CStrings:  3634
 
Symbols:
+ +[CSAudioStreamHoldRequestOption defaultOptionWithTimeout:requestExclaveAudio:]
+ +[CSConfig inputRecordingDurationInSecsAttentive]
+ +[CSFModelConfigDecoder purgeCachedConfigs]
+ +[CSFModelConfigDecoder(Test) cachedConfigPathsForTesting]
+ +[CSUtils allowAttentiveRingBufferSize]
+ +[CSUtils supportEarlyRecordingStartNotification]
+ -[CSAudioProvider _acquirePowerMeterLockFrom:option:needsBoost12dB:]
+ -[CSAudioProvider _anyPowerMeterLockNeedsBoost12dB]
+ -[CSAudioProvider _clientIdentityQualifiesForPowerMeter:]
+ -[CSAudioProvider _forceReleaseAllPowerMeterLocks]
+ -[CSAudioProvider _forceReleasePowerMeterLockFrom:]
+ -[CSAudioProvider _setStreamStateStreamingForTesting]
+ -[CSAudioProvider exfiltratingStreamHolderCountLock]
+ -[CSAudioProvider exfiltratingStreamHolderCount]
+ -[CSAudioProvider hasPowerMeterLock]
+ -[CSAudioProvider isLinwoodEnabledForPowerMeter]
+ -[CSAudioProvider powerMeterLocks]
+ -[CSAudioProvider powerMeterNeedsBoost12dB]
+ -[CSAudioProvider setExfiltratingStreamHolderCount:]
+ -[CSAudioProvider setExfiltratingStreamHolderCountLock:]
+ -[CSAudioProvider setHasPowerMeterLock:]
+ -[CSAudioProvider setIsLinwoodEnabledForPowerMeter:]
+ -[CSAudioProvider setPowerMeterLocks:]
+ -[CSAudioProvider setPowerMeterNeedsBoost12dB:]
+ -[CSAudioProviderPowerMeterLock initWithClientIdentity:needsBoost12dB:]
+ -[CSAudioProviderPowerMeterLock needsBoost12dB]
+ -[CSAudioRecordContext canCreateContinuousConversationProfile]
+ -[CSAudioStreamHoldRequestOption initWithTimeout:clientIdentity:requireRecordModeLock:requireListeningMicIndicatorLock:requestExclaveAudio:]
+ -[CSAudioStreamHoldRequestOption requestExclaveAudio]
+ -[CSAudioStreamHolding initWithName:clientIdentity:requestExclaveAudio:]
+ -[CSAudioStreamHolding requestExclaveAudio]
+ -[CSEventMonitor _removeObserverOnQueue:]
+ GCC_except_table1007
+ GCC_except_table1008
+ GCC_except_table1014
+ GCC_except_table1019
+ GCC_except_table1028
+ GCC_except_table1029
+ GCC_except_table1030
+ GCC_except_table1044
+ GCC_except_table1114
+ GCC_except_table1116
+ GCC_except_table1117
+ GCC_except_table1127
+ GCC_except_table1445
+ GCC_except_table1476
+ GCC_except_table1563
+ GCC_except_table1564
+ GCC_except_table1565
+ GCC_except_table1566
+ GCC_except_table1567
+ GCC_except_table1568
+ GCC_except_table1569
+ GCC_except_table1577
+ GCC_except_table1580
+ GCC_except_table1588
+ GCC_except_table1592
+ GCC_except_table1594
+ GCC_except_table1596
+ GCC_except_table1600
+ GCC_except_table1778
+ GCC_except_table1991
+ GCC_except_table1992
+ GCC_except_table1998
+ GCC_except_table2001
+ GCC_except_table2004
+ GCC_except_table2016
+ GCC_except_table2018
+ GCC_except_table2019
+ GCC_except_table2085
+ GCC_except_table2090
+ GCC_except_table2153
+ GCC_except_table2206
+ GCC_except_table2207
+ GCC_except_table2209
+ GCC_except_table2210
+ GCC_except_table2216
+ GCC_except_table2227
+ GCC_except_table2240
+ GCC_except_table2283
+ GCC_except_table2301
+ GCC_except_table2382
+ GCC_except_table2482
+ GCC_except_table2519
+ GCC_except_table2690
+ GCC_except_table2694
+ GCC_except_table274
+ GCC_except_table2770
+ GCC_except_table2781
+ GCC_except_table2783
+ GCC_except_table2788
+ GCC_except_table2790
+ GCC_except_table2812
+ GCC_except_table2814
+ GCC_except_table2832
+ GCC_except_table284
+ GCC_except_table2853
+ GCC_except_table2902
+ GCC_except_table2964
+ GCC_except_table2966
+ GCC_except_table2967
+ GCC_except_table3130
+ GCC_except_table3270
+ GCC_except_table3278
+ GCC_except_table3288
+ GCC_except_table3297
+ GCC_except_table3300
+ GCC_except_table3302
+ GCC_except_table3303
+ GCC_except_table3342
+ GCC_except_table3348
+ GCC_except_table3395
+ GCC_except_table346
+ GCC_except_table3488
+ GCC_except_table3500
+ GCC_except_table3506
+ GCC_except_table3513
+ GCC_except_table3525
+ GCC_except_table3550
+ GCC_except_table3551
+ GCC_except_table3552
+ GCC_except_table3553
+ GCC_except_table3578
+ GCC_except_table3591
+ GCC_except_table3762
+ GCC_except_table3822
+ GCC_except_table3836
+ GCC_except_table3879
+ GCC_except_table388
+ GCC_except_table3915
+ GCC_except_table3919
+ GCC_except_table3920
+ GCC_except_table3940
+ GCC_except_table3946
+ GCC_except_table3947
+ GCC_except_table3948
+ GCC_except_table3953
+ GCC_except_table3977
+ GCC_except_table4003
+ GCC_except_table4024
+ GCC_except_table4045
+ GCC_except_table4046
+ GCC_except_table4047
+ GCC_except_table4048
+ GCC_except_table412
+ GCC_except_table413
+ GCC_except_table4135
+ GCC_except_table4136
+ GCC_except_table414
+ GCC_except_table4150
+ GCC_except_table4155
+ GCC_except_table4156
+ GCC_except_table4159
+ GCC_except_table4160
+ GCC_except_table4161
+ GCC_except_table4162
+ GCC_except_table4165
+ GCC_except_table4166
+ GCC_except_table4168
+ GCC_except_table4172
+ GCC_except_table4184
+ GCC_except_table4186
+ GCC_except_table4187
+ GCC_except_table419
+ GCC_except_table4192
+ GCC_except_table4193
+ GCC_except_table4198
+ GCC_except_table4199
+ GCC_except_table4202
+ GCC_except_table4204
+ GCC_except_table4205
+ GCC_except_table4208
+ GCC_except_table4209
+ GCC_except_table4210
+ GCC_except_table4212
+ GCC_except_table4213
+ GCC_except_table4215
+ GCC_except_table4216
+ GCC_except_table4217
+ GCC_except_table4218
+ GCC_except_table422
+ GCC_except_table4246
+ GCC_except_table4296
+ GCC_except_table4302
+ GCC_except_table4358
+ GCC_except_table4394
+ GCC_except_table4402
+ GCC_except_table4404
+ GCC_except_table4428
+ GCC_except_table4431
+ GCC_except_table4432
+ GCC_except_table4433
+ GCC_except_table4434
+ GCC_except_table4435
+ GCC_except_table4436
+ GCC_except_table4438
+ GCC_except_table4440
+ GCC_except_table4441
+ GCC_except_table4442
+ GCC_except_table4445
+ GCC_except_table4450
+ GCC_except_table4454
+ GCC_except_table4456
+ GCC_except_table4458
+ GCC_except_table4465
+ GCC_except_table4478
+ GCC_except_table4479
+ GCC_except_table4481
+ GCC_except_table4482
+ GCC_except_table4484
+ GCC_except_table4486
+ GCC_except_table4487
+ GCC_except_table4488
+ GCC_except_table4495
+ GCC_except_table4501
+ GCC_except_table4502
+ GCC_except_table4532
+ GCC_except_table4644
+ GCC_except_table4651
+ GCC_except_table4734
+ GCC_except_table474
+ GCC_except_table475
+ GCC_except_table476
+ GCC_except_table477
+ GCC_except_table4795
+ GCC_except_table4805
+ GCC_except_table4853
+ GCC_except_table4854
+ GCC_except_table4855
+ GCC_except_table4857
+ GCC_except_table4858
+ GCC_except_table4861
+ GCC_except_table4862
+ GCC_except_table4864
+ GCC_except_table4865
+ GCC_except_table4867
+ GCC_except_table4869
+ GCC_except_table4870
+ GCC_except_table4872
+ GCC_except_table4908
+ GCC_except_table4974
+ GCC_except_table4979
+ GCC_except_table5020
+ GCC_except_table5086
+ GCC_except_table582
+ GCC_except_table585
+ GCC_except_table620
+ GCC_except_table746
+ GCC_except_table748
+ GCC_except_table751
+ GCC_except_table757
+ GCC_except_table913
+ GCC_except_table922
+ GCC_except_table984
+ GCC_except_table985
+ GCC_except_table992
+ OBJC_IVAR_$_CSAudioProvider._exfiltratingStreamHolderCount
+ OBJC_IVAR_$_CSAudioProvider._exfiltratingStreamHolderCountLock
+ OBJC_IVAR_$_CSAudioProvider._hasPowerMeterLock
+ OBJC_IVAR_$_CSAudioProvider._isLinwoodEnabledForPowerMeter
+ OBJC_IVAR_$_CSAudioProvider._powerMeterLocks
+ OBJC_IVAR_$_CSAudioProvider._powerMeterNeedsBoost12dB
+ OBJC_IVAR_$_CSAudioProviderPowerMeterLock._needsBoost12dB
+ OBJC_IVAR_$_CSAudioStreamHoldRequestOption._requestExclaveAudio
+ OBJC_IVAR_$_CSAudioStreamHolding._requestExclaveAudio
+ _OBJC_CLASS_$_CSAudioProviderPowerMeterLock
+ _OBJC_METACLASS_$_CSAudioProviderPowerMeterLock
+ __OBJC_$_CLASS_METHODS_CSFModelConfigDecoder(Test)
+ __OBJC_$_INSTANCE_METHODS_CSAudioProviderPowerMeterLock
+ __OBJC_$_INSTANCE_VARIABLES_CSAudioProviderPowerMeterLock
+ __OBJC_$_PROP_LIST_CSAudioProviderPowerMeterLock
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CSAudioSessionProviding
+ __OBJC_CLASS_RO_$_CSAudioProviderPowerMeterLock
+ __OBJC_METACLASS_RO_$_CSAudioProviderPowerMeterLock
+ ___50-[CSAudioProvider _forceReleaseAllPowerMeterLocks]_block_invoke
+ ___51-[CSAudioProvider _forceReleasePowerMeterLockFrom:]_block_invoke
+ ___68-[CSAudioProvider _acquirePowerMeterLockFrom:option:needsBoost12dB:]_block_invoke
+ ___block_descriptor_42_e8_32s_e5_v8?0l
+ ___block_descriptor_51_e8_32s40s_e5_v8?0l
+ _kCSEventMonitorQueueKey
+ _objc_msgSend$_acquirePowerMeterLockFrom:option:needsBoost12dB:
+ _objc_msgSend$_anyPowerMeterLockNeedsBoost12dB
+ _objc_msgSend$_clientIdentityQualifiesForPowerMeter:
+ _objc_msgSend$_forceReleaseAllPowerMeterLocks
+ _objc_msgSend$_forceReleasePowerMeterLockFrom:
+ _objc_msgSend$_removeObserverOnQueue:
+ _objc_msgSend$allowAttentiveRingBufferSize
+ _objc_msgSend$configureForRecordRoute:preferUseSelfTap:
+ _objc_msgSend$defaultOptionWithTimeout:requestExclaveAudio:
+ _objc_msgSend$exfiltratingStreamHolderCount
+ _objc_msgSend$hasPowerMeterLock
+ _objc_msgSend$initWithClientIdentity:needsBoost12dB:
+ _objc_msgSend$initWithName:clientIdentity:requestExclaveAudio:
+ _objc_msgSend$initWithTimeout:clientIdentity:requireRecordModeLock:requireListeningMicIndicatorLock:requestExclaveAudio:
+ _objc_msgSend$inputRecordingDurationInSecsAttentive
+ _objc_msgSend$isDictation
+ _objc_msgSend$isVoiceTriggered
+ _objc_msgSend$isiOSButtonPress
+ _objc_msgSend$powerMeterLocks
+ _objc_msgSend$powerMeterNeedsBoost12dB
+ _objc_msgSend$processAudioChunkForTV:
+ _objc_msgSend$setExfiltratingStreamHolderCount:
+ _objc_msgSend$setHasPowerMeterLock:
+ _objc_msgSend$setPowerMeterNeedsBoost12dB:
+ _sConfigCache
+ _sConfigCacheLock
+ _sConfigStamp
+ _stat
- GCC_except_table1003
- GCC_except_table1004
- GCC_except_table1005
- GCC_except_table1010
- GCC_except_table1011
- GCC_except_table1012
- GCC_except_table1022
- GCC_except_table1040
- GCC_except_table1110
- GCC_except_table1112
- GCC_except_table1113
- GCC_except_table1123
- GCC_except_table1439
- GCC_except_table1470
- GCC_except_table1550
- GCC_except_table1554
- GCC_except_table1555
- GCC_except_table1556
- GCC_except_table1558
- GCC_except_table1559
- GCC_except_table1560
- GCC_except_table1570
- GCC_except_table1573
- GCC_except_table1574
- GCC_except_table1579
- GCC_except_table1582
- GCC_except_table1585
- GCC_except_table1587
- GCC_except_table1770
- GCC_except_table1983
- GCC_except_table1984
- GCC_except_table1985
- GCC_except_table1986
- GCC_except_table1990
- GCC_except_table1996
- GCC_except_table2008
- GCC_except_table2011
- GCC_except_table2077
- GCC_except_table2082
- GCC_except_table2145
- GCC_except_table2198
- GCC_except_table2199
- GCC_except_table2201
- GCC_except_table2202
- GCC_except_table2208
- GCC_except_table2219
- GCC_except_table2232
- GCC_except_table2275
- GCC_except_table2293
- GCC_except_table2372
- GCC_except_table2470
- GCC_except_table2507
- GCC_except_table2663
- GCC_except_table2667
- GCC_except_table272
- GCC_except_table2743
- GCC_except_table2754
- GCC_except_table2756
- GCC_except_table2761
- GCC_except_table2763
- GCC_except_table2778
- GCC_except_table2785
- GCC_except_table2787
- GCC_except_table282
- GCC_except_table2826
- GCC_except_table2867
- GCC_except_table2929
- GCC_except_table2931
- GCC_except_table2932
- GCC_except_table3095
- GCC_except_table3235
- GCC_except_table3243
- GCC_except_table3253
- GCC_except_table3262
- GCC_except_table3265
- GCC_except_table3267
- GCC_except_table3268
- GCC_except_table3307
- GCC_except_table3313
- GCC_except_table3360
- GCC_except_table344
- GCC_except_table3453
- GCC_except_table3465
- GCC_except_table3471
- GCC_except_table3478
- GCC_except_table3490
- GCC_except_table3515
- GCC_except_table3516
- GCC_except_table3517
- GCC_except_table3518
- GCC_except_table3543
- GCC_except_table3556
- GCC_except_table3727
- GCC_except_table3787
- GCC_except_table3801
- GCC_except_table384
- GCC_except_table3843
- GCC_except_table3844
- GCC_except_table3877
- GCC_except_table3880
- GCC_except_table3883
- GCC_except_table3884
- GCC_except_table3885
- GCC_except_table3905
- GCC_except_table3907
- GCC_except_table3911
- GCC_except_table3968
- GCC_except_table3989
- GCC_except_table4010
- GCC_except_table4011
- GCC_except_table4012
- GCC_except_table4013
- GCC_except_table404
- GCC_except_table406
- GCC_except_table409
- GCC_except_table4100
- GCC_except_table4101
- GCC_except_table4112
- GCC_except_table4114
- GCC_except_table4115
- GCC_except_table4116
- GCC_except_table4117
- GCC_except_table4120
- GCC_except_table4121
- GCC_except_table4124
- GCC_except_table4125
- GCC_except_table4126
- GCC_except_table4127
- GCC_except_table4130
- GCC_except_table4131
- GCC_except_table4132
- GCC_except_table4133
- GCC_except_table4134
- GCC_except_table4137
- GCC_except_table4140
- GCC_except_table4146
- GCC_except_table415
- GCC_except_table4157
- GCC_except_table4158
- GCC_except_table4163
- GCC_except_table4164
- GCC_except_table4170
- GCC_except_table4173
- GCC_except_table4174
- GCC_except_table4177
- GCC_except_table4178
- GCC_except_table418
- GCC_except_table4180
- GCC_except_table4183
- GCC_except_table4211
- GCC_except_table4261
- GCC_except_table4267
- GCC_except_table4323
- GCC_except_table4324
- GCC_except_table4331
- GCC_except_table4332
- GCC_except_table4333
- GCC_except_table4334
- GCC_except_table4336
- GCC_except_table4337
- GCC_except_table4361
- GCC_except_table4362
- GCC_except_table4363
- GCC_except_table4365
- GCC_except_table4370
- GCC_except_table4384
- GCC_except_table4393
- GCC_except_table4395
- GCC_except_table4399
- GCC_except_table4408
- GCC_except_table4409
- GCC_except_table4410
- GCC_except_table4412
- GCC_except_table4414
- GCC_except_table4415
- GCC_except_table4417
- GCC_except_table4421
- GCC_except_table4423
- GCC_except_table4446
- GCC_except_table4451
- GCC_except_table4453
- GCC_except_table4460
- GCC_except_table4462
- GCC_except_table4466
- GCC_except_table4467
- GCC_except_table4609
- GCC_except_table4616
- GCC_except_table465
- GCC_except_table4699
- GCC_except_table470
- GCC_except_table471
- GCC_except_table472
- GCC_except_table4760
- GCC_except_table4770
- GCC_except_table4818
- GCC_except_table4819
- GCC_except_table4820
- GCC_except_table4822
- GCC_except_table4823
- GCC_except_table4826
- GCC_except_table4827
- GCC_except_table4829
- GCC_except_table4830
- GCC_except_table4832
- GCC_except_table4834
- GCC_except_table4835
- GCC_except_table4837
- GCC_except_table4873
- GCC_except_table4939
- GCC_except_table4944
- GCC_except_table4985
- GCC_except_table5051
- GCC_except_table578
- GCC_except_table581
- GCC_except_table616
- GCC_except_table738
- GCC_except_table744
- GCC_except_table747
- GCC_except_table753
- GCC_except_table909
- GCC_except_table918
- GCC_except_table980
- GCC_except_table981
- GCC_except_table988
- __OBJC_$_CLASS_METHODS_CSFModelConfigDecoder
- _objc_msgSend$initWithName:clientIdentity:
- _objc_msgSend$initWithTimeout:clientIdentity:requireRecordModeLock:requireListeningMicIndicatorLock:
CStrings:
+ "%ld.%09ld:%lld"
+ "%s Acquiring power meter lock from : %{public}@ %@"
+ "%s CSAudioProvider[%{public}@]:%{public}@ ask for audio hold stream from %{public}@ for %{public}.2f secs, requestExclaveAudio = %{public}s"
+ "%s CSAudioProvider[%{public}@]:Remaining audio stream holder requesting audio exfiltration: %{public}lu stream holders"
+ "%s Cached decoded model config %{public}@ (%{public}lu top-level keys, %{public}lu cached)"
+ "%s ERR: could not decode model config %{public}@: %{public}@"
+ "%s ERR: could not read model config %{public}@"
+ "%s ERR: model config %{public}@ is %{public}@, expected a dictionary"
+ "%s Force releasing all %tu power meter locks"
+ "%s Purged %{public}lu cached model config(s)"
+ "%s RecordSettings received from AVVC: %@"
+ "%s Releasing power meter lock from : %{public}@"
+ "+[CSFModelConfigDecoder purgeCachedConfigs]"
+ "-[CSAudioProvider _acquirePowerMeterLockFrom:option:needsBoost12dB:]"
+ "-[CSAudioProvider _forceReleaseAllPowerMeterLocks]"
+ "-[CSAudioProvider _forceReleasePowerMeterLockFrom:]"
+ "-[CSAudioRecorder recordSettingsWithStreamHandleId:]"
+ "SiriRecordStartAlert"
+ "startAlertBehavior=%ld"
+ "\xf0\"1"
- "%s CSAudioProvider[%{public}@]:%{public}@ ask for audio hold stream from %{public}@ for %{public}.2f secs"
- "%s ERR: metaData is nil, defaulting to NO for %{public}@"
- "%s ERR: read metafile %{public}@ failed with %{public}@ - defaulting to NO"
```
