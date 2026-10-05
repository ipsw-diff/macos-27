## MediaPlaybackCore

> `/System/iOSSupport/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/Versions/A/MediaPlaybackCore`

```diff

-26200.26.37.501.0
-  __TEXT.__text: 0x43ee0c
-  __TEXT.__objc_methlist: 0x17638
+26200.26.39.301.0
+  __TEXT.__text: 0x4440c4
+  __TEXT.__objc_methlist: 0x17658
   __TEXT.__dlopen_cstrs: 0xbe
-  __TEXT.__const: 0xfa90
-  __TEXT.__cstring: 0x2492b
-  __TEXT.__constg_swiftt: 0x7820
-  __TEXT.__swift5_typeref: 0x5118
+  __TEXT.__const: 0xfb50
+  __TEXT.__cstring: 0x24b27
+  __TEXT.__constg_swiftt: 0x78b4
+  __TEXT.__swift5_typeref: 0x5154
   __TEXT.__swift5_builtin: 0x67c
-  __TEXT.__swift5_reflstr: 0x5722
-  __TEXT.__swift5_fieldmd: 0x52ac
+  __TEXT.__swift5_reflstr: 0x57d2
+  __TEXT.__swift5_fieldmd: 0x5310
   __TEXT.__swift5_assocty: 0xb58
-  __TEXT.__oslogstring: 0x48dc2
-  __TEXT.__swift5_proto: 0x8b8
-  __TEXT.__swift5_types: 0x514
-  __TEXT.__swift5_capture: 0x8444
-  __TEXT.__swift_as_entry: 0x48c
-  __TEXT.__swift_as_ret: 0x590
-  __TEXT.__swift_as_cont: 0xd9c
+  __TEXT.__oslogstring: 0x48f9a
+  __TEXT.__swift5_proto: 0x8c0
+  __TEXT.__swift5_types: 0x518
+  __TEXT.__swift5_capture: 0x86fc
+  __TEXT.__swift_as_entry: 0x498
+  __TEXT.__swift_as_ret: 0x5ac
+  __TEXT.__swift_as_cont: 0xdcc
   __TEXT.__swift5_mpenum: 0xf8
   __TEXT.__swift5_protos: 0xd8
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x5748
+  __TEXT.__gcc_except_tab: 0x5738
   __TEXT.__ustring: 0x4dc
-  __TEXT.__unwind_info: 0xff18
-  __TEXT.__eh_frame: 0xf7ec
+  __TEXT.__unwind_info: 0xfbb8
+  __TEXT.__eh_frame: 0xfa0c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x8f00
+  __DATA_CONST.__const: 0x8fc8
   __DATA_CONST.__objc_classlist: 0xce8
   __DATA_CONST.__objc_catlist: 0x280
   __DATA_CONST.__objc_protolist: 0x7a0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xc658
+  __DATA_CONST.__objc_selrefs: 0xc678
   __DATA_CONST.__objc_protorefs: 0x380
   __DATA_CONST.__objc_superrefs: 0x6c0
-  __DATA_CONST.__objc_arraydata: 0x298
-  __DATA_CONST.__got: 0x30f8
-  __AUTH_CONST.__const: 0x1c318
-  __AUTH_CONST.__cfstring: 0x1e480
-  __AUTH_CONST.__objc_const: 0x334d0
+  __DATA_CONST.__objc_arraydata: 0x290
+  __DATA_CONST.__got: 0x3108
+  __AUTH_CONST.__const: 0x1ca50
+  __AUTH_CONST.__cfstring: 0x1e620
+  __AUTH_CONST.__objc_const: 0x33570
   __AUTH_CONST.__objc_intobj: 0x8a0
-  __AUTH_CONST.__objc_arrayobj: 0x288
+  __AUTH_CONST.__objc_arrayobj: 0x270
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x50
-  __AUTH_CONST.__auth_got: 0x32e0
+  __AUTH_CONST.__auth_got: 0x32f8
   __AUTH.__objc_data: 0x53c8
-  __AUTH.__data: 0x2a70
-  __DATA.__objc_ivar: 0x1a70
-  __DATA.__data: 0x6668
-  __DATA.__bss: 0xdd38
+  __AUTH.__data: 0x2a90
+  __DATA.__objc_ivar: 0x1a74
+  __DATA.__data: 0x66d8
+  __DATA.__bss: 0xde38
   __DATA.__common: 0x200
   __DATA_DIRTY.__objc_data: 0x3900
-  __DATA_DIRTY.__data: 0x5d40
+  __DATA_DIRTY.__data: 0x5db0
   __DATA_DIRTY.__bss: 0x1b28
   __DATA_DIRTY.__common: 0xf0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 22598
-  Symbols:   23604
-  CStrings:  7966
+  Functions: 22769
+  Symbols:   23637
+  CStrings:  7984
 
Symbols:
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:completionHandler:]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:error:]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSMetadataItemInMetadata:]
+ -[AVURLAsset(MPCHLSSessionData) mpc_HLSSessionMetadataItemWithTimeout:completionHandler:]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) _sharedKeySegmentDurationFromHLSSessionDataOfAsset:completionHandler:]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTimeWithCompletionHandler:]
+ -[MPCModelGenericAVItem(KeyDeliveryDeferral) sharedKeySegmentDurationWithCompletionHandler:]
+ -[MPCPlaybackErrorController playbackDidSucceedForItem:]
+ -[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSAudioAssetMetadataDictionary:]
+ GCC_except_table3524
+ GCC_except_table3545
+ GCC_except_table3552
+ GCC_except_table3581
+ GCC_except_table3591
+ GCC_except_table3648
+ GCC_except_table3657
+ GCC_except_table3726
+ GCC_except_table3827
+ GCC_except_table3838
+ GCC_except_table3854
+ GCC_except_table3860
+ GCC_except_table3870
+ GCC_except_table3998
+ GCC_except_table4044
+ GCC_except_table4045
+ GCC_except_table4046
+ GCC_except_table4065
+ GCC_except_table4076
+ GCC_except_table4094
+ GCC_except_table4099
+ GCC_except_table4101
+ GCC_except_table4115
+ GCC_except_table4138
+ GCC_except_table4149
+ GCC_except_table4238
+ GCC_except_table4257
+ GCC_except_table4270
+ GCC_except_table4281
+ GCC_except_table4312
+ GCC_except_table4483
+ GCC_except_table4484
+ GCC_except_table4661
+ GCC_except_table4696
+ GCC_except_table4698
+ GCC_except_table4706
+ GCC_except_table4714
+ GCC_except_table4729
+ GCC_except_table4737
+ GCC_except_table4745
+ GCC_except_table4755
+ GCC_except_table4768
+ GCC_except_table4812
+ GCC_except_table4826
+ GCC_except_table4845
+ GCC_except_table4851
+ GCC_except_table4898
+ GCC_except_table4935
+ GCC_except_table5021
+ GCC_except_table5347
+ GCC_except_table5348
+ GCC_except_table5420
+ GCC_except_table5516
+ GCC_except_table5666
+ GCC_except_table5691
+ GCC_except_table5860
+ GCC_except_table5925
+ GCC_except_table5950
+ GCC_except_table5985
+ GCC_except_table5988
+ GCC_except_table5991
+ GCC_except_table6077
+ GCC_except_table6294
+ GCC_except_table6311
+ GCC_except_table6782
+ GCC_except_table7122
+ GCC_except_table7137
+ GCC_except_table7237
+ GCC_except_table7326
+ GCC_except_table7333
+ GCC_except_table7351
+ GCC_except_table7403
+ GCC_except_table7406
+ GCC_except_table7411
+ GCC_except_table7427
+ OBJC_IVAR_$__MPCMediaRemotePublisher._hostingSharedSessionIDInitialized
+ _MPCHLSAudioAssetMetadataDictionaryKey
+ _MPHomeMonitorCurrentHomeDidChangeNotification
+ _MPHomeMonitorHomeUsersDidChangeNotification
+ _OUTLINED_FUNCTION_468
+ _OUTLINED_FUNCTION_469
+ _OUTLINED_FUNCTION_470
+ _OUTLINED_FUNCTION_471
+ _OUTLINED_FUNCTION_472
+ __89-[AVURLAsset(MPCHLSSessionData) mpc_HLSSessionMetadataItemWithTimeout:completionHandler:]_block_invoke
+ ___115-[MPCModelGenericAVItem(KeyDeliveryDeferral) _sharedKeySegmentDurationFromHLSSessionDataOfAsset:completionHandler:]_block_invoke
+ ___140-[MPCModelGenericAVItem(KeyDeliveryDeferral) shouldPerformKeyDeliveryRequestForKey:isPrefetchKey:isPersistable:isRenewal:completionHandler:]_block_invoke_4
+ ___86-[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:error:]_block_invoke
+ ___88-[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSAudioAssetMetadataDictionary:]_block_invoke
+ ___89-[AVURLAsset(MPCHLSSessionData) mpc_HLSSessionMetadataItemWithTimeout:completionHandler:]_block_invoke
+ ___89-[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTimeWithCompletionHandler:]_block_invoke
+ ___98-[AVURLAsset(MPCHLSSessionData) mpc_HLSAudioAssetMetadataDictionaryWithTimeout:completionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32s40bs_e36_v24?0"AVMetadataItem"8"NSError"16ls40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v16?0d8ls40l8s32l8
+ ___block_descriptor_48_e8_32s40bs_e8_v16?0q8ls32l8s40l8
+ ___block_descriptor_56_e8_32s40r48r_e34_v24?0"NSDictionary"8"NSError"16lr40l8r48l8s32l8
+ ___block_descriptor_56_e8_32s40s48bs_e29_v24?0"NSArray"8"NSError"16ls32l8s40l8s48l8
+ __swift_closure_destructor.70Tm
+ _associated conformance 17MediaPlaybackCore23AudioSignatureProcessorV10SliceRange33_70D6E225C33896E6E4196C32A146759DLLVSHAASQ
+ _objc_msgSend$_audioFormatsDictionaryWithHLSAudioAssetMetadataDictionary:
+ _objc_msgSend$_sharedKeySegmentDurationFromHLSSessionDataOfAsset:completionHandler:
+ _objc_msgSend$keyDeliveryJitterTimeWithCompletionHandler:
+ _objc_msgSend$loadMetadataForFormat:completionHandler:
+ _objc_msgSend$mpc_HLSAudioAssetMetadataDictionaryWithTimeout:completionHandler:
+ _objc_msgSend$mpc_HLSAudioAssetMetadataDictionaryWithTimeout:error:
+ _objc_msgSend$mpc_HLSMetadataItemInMetadata:
+ _objc_msgSend$mpc_HLSSessionMetadataItemWithTimeout:completionHandler:
+ _objc_msgSend$playbackDidSucceedForItem:
+ _objc_msgSend$setupIfNecessary
+ _objc_msgSend$sharedKeySegmentDurationWithCompletionHandler:
+ _symbolic _____ 17MediaPlaybackCore23AudioSignatureProcessorV10SliceRange33_70D6E225C33896E6E4196C32A146759DLLV
+ _symbolic _____Iegr_ 17MediaPlaybackCore12PlayingStateC
+ _symbolic _____ySDy_____So11SHSignatureCGG 2os21OSAllocatedUnfairLockV 17MediaPlaybackCore23AudioSignatureProcessorV10SliceRange33_70D6E225C33896E6E4196C32A146759DLLV
+ _type_layout_string SNySdG
- -[AVURLAsset(MPCHLSSessionData) mpc_HLSAVMetadataItemInMetadata:]
- -[AVURLAsset(MPCHLSSessionData) mpc_synchronousHLSSessionDataWithTimeout:error:]
- -[MPCModelGenericAVItem(KeyDeliveryDeferral) keyDeliveryJitterTime]
- -[MPCModelGenericAVItem(KeyDeliveryDeferral) sharedKeySegmentDuration]
- -[MPCPlayerItemConfigurator _HLSMetadataForAsset:error:]
- -[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSMetadata:]
- GCC_except_table3520
- GCC_except_table3541
- GCC_except_table3548
- GCC_except_table3573
- GCC_except_table3587
- GCC_except_table3644
- GCC_except_table3649
- GCC_except_table3722
- GCC_except_table3819
- GCC_except_table3834
- GCC_except_table3850
- GCC_except_table3856
- GCC_except_table3866
- GCC_except_table3994
- GCC_except_table4039
- GCC_except_table4040
- GCC_except_table4041
- GCC_except_table4061
- GCC_except_table4072
- GCC_except_table4090
- GCC_except_table4095
- GCC_except_table4097
- GCC_except_table4111
- GCC_except_table4134
- GCC_except_table4145
- GCC_except_table4234
- GCC_except_table4253
- GCC_except_table4266
- GCC_except_table4277
- GCC_except_table4308
- GCC_except_table4479
- GCC_except_table4480
- GCC_except_table4657
- GCC_except_table4692
- GCC_except_table4694
- GCC_except_table4702
- GCC_except_table4710
- GCC_except_table4725
- GCC_except_table4733
- GCC_except_table4741
- GCC_except_table4751
- GCC_except_table4764
- GCC_except_table4808
- GCC_except_table4823
- GCC_except_table4839
- GCC_except_table4848
- GCC_except_table4895
- GCC_except_table4932
- GCC_except_table5017
- GCC_except_table5343
- GCC_except_table5344
- GCC_except_table5416
- GCC_except_table5512
- GCC_except_table5662
- GCC_except_table5687
- GCC_except_table5856
- GCC_except_table5921
- GCC_except_table5946
- GCC_except_table5981
- GCC_except_table5984
- GCC_except_table5987
- GCC_except_table6073
- GCC_except_table6290
- GCC_except_table6307
- GCC_except_table6778
- GCC_except_table7118
- GCC_except_table7128
- GCC_except_table7219
- GCC_except_table7317
- GCC_except_table7324
- GCC_except_table7342
- GCC_except_table7393
- GCC_except_table7394
- GCC_except_table7397
- GCC_except_table7418
- ___68-[MPCPlayerItemConfigurator _audioFormatsDictionaryWithHLSMetadata:]_block_invoke
- ___80-[AVURLAsset(MPCHLSSessionData) mpc_synchronousHLSSessionDataWithTimeout:error:]_block_invoke
- _objc_msgSend$_HLSMetadataForAsset:error:
- _objc_msgSend$_audioFormatsDictionaryWithHLSMetadata:
- _objc_msgSend$keyDeliveryJitterTime
- _objc_msgSend$metadataForFormat:
- _objc_msgSend$mpc_HLSAVMetadataItemInMetadata:
- _objc_msgSend$mpc_synchronousHLSSessionDataWithTimeout:error:
- _objc_msgSend$sharedKeySegmentDuration
CStrings:
+ "FIRST-SEGMENT-DURATION"
+ "Failed to decode HLS session data - Asset:%@"
+ "Failed to load HLS session metadata - Asset:%@"
+ "HLSSessionDataDecodingFailed"
+ "HLSSessionDataFetchTimedOut"
+ "HLSSessionDataUnavailable"
+ "MPCModelGenericAVItem+KeyDeliveryDeferral.m"
+ "No HLS session data available - Asset:%@"
+ "Playback queue superseded before response; re-requesting"
+ "SHARED-KEY-SEGMENT-COUNT"
+ "Timed out retrieving HLS session metadata - Asset:%@"
+ "Unexpected nil urlAsset"
+ "[%{public}@]-❗️MPCErrorControllerImplementation %p <%{public}@> - Ending playback [Item failed repeatedly]"
+ "[Chapter/ContentItem] Unable to convert chapter %{private,mask.hash}s to content item without a duration."
+ "[Chapters/%{private,mask.hash}s] Normalizing %{private,mask.hash}ld chapters with duration %{private,mask.hash}s."
+ "[Chapters/%{private,mask.hash}s] Segments changed, re-normalizing chapters with duration %{private,mask.hash}f."
+ "[Chapters/%{private,mask.hash}s] Unable to get duration for episode with %{private,mask.hash}s."
+ "[Chapters/%{private,mask.hash}s] Unable to get duration for episode with error %s."
+ "[Chapters] Finished chapter durations for minimum threshold."
+ "[Chapters] Removing chapter %{private,mask.hash}s."
+ "[Chapters] Verifying chapter durations for minimum threshold %f."
+ "[PL:%{public}s] STACK PROCESSING: setQueueWithInitialItem [new start item %{public}s] - isResend:%{bool,public}d - capturedIntent:%{bool,public}d - shouldPlay:%{bool,public}d"
+ "key-delivery-jitter-window"
+ "v24@?0@\"AVMetadataItem\"8@\"NSError\"16"
- "[%{public}@]-MPCErrorControllerImplementation %p <%{public}@> - Playback has succeeded for at least one item [Ignoring queue failure]"
- "[%{public}@]-MPCPlayerItemConfigurator %p - [AL] - Error decoding HLS metadata [Clearing audioFormatsDictionary] - Error:%{public}@"
- "[%{public}@]-❗️MPCErrorControllerImplementation %p <%{public}@> - Ending playback [Entire queue failure]"
- "[Chapters/%{private,mask.hash}s] Segments changed, re-normalizing chapters with duration %f."
- "[PL:%{public}s] STACK PROCESSING: setQueueWithInitialItem [new start item %{public}s]"
- "\xe1"
```
