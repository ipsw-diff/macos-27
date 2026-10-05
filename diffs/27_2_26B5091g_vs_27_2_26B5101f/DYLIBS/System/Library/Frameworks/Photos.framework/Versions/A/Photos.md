## Photos

> `/System/Library/Frameworks/Photos.framework/Versions/A/Photos`

```diff

-916.45.110.0.0
-  __TEXT.__text: 0x2f2f14
-  __TEXT.__objc_methlist: 0x26224
-  __TEXT.__const: 0x17d8
+916.53.100.0.0
+  __TEXT.__text: 0x2f3bd0
+  __TEXT.__objc_methlist: 0x262b4
+  __TEXT.__const: 0x1850
   __TEXT.__dlopen_cstrs: 0x280
-  __TEXT.__constg_swiftt: 0x67c
-  __TEXT.__swift5_typeref: 0x547
+  __TEXT.__constg_swiftt: 0x660
+  __TEXT.__swift5_typeref: 0x5ab
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__swift5_reflstr: 0x191
-  __TEXT.__swift5_fieldmd: 0x23c
-  __TEXT.__swift5_assocty: 0xd0
-  __TEXT.__swift5_proto: 0x4c
-  __TEXT.__swift5_types: 0x44
+  __TEXT.__swift5_reflstr: 0x1a1
+  __TEXT.__swift5_fieldmd: 0x220
+  __TEXT.__swift5_assocty: 0x108
+  __TEXT.__swift5_proto: 0x48
+  __TEXT.__swift5_types: 0x40
   __TEXT.__swift5_capture: 0x198
-  __TEXT.__cstring: 0x3304c
+  __TEXT.__cstring: 0x3329f
   __TEXT.__swift_as_entry: 0x10
   __TEXT.__swift_as_ret: 0x10
   __TEXT.__swift_as_cont: 0x18
-  __TEXT.__oslogstring: 0x22cc6
+  __TEXT.__oslogstring: 0x22da5
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__gcc_except_tab: 0x9344
+  __TEXT.__gcc_except_tab: 0x932c
   __TEXT.__ustring: 0x1e
-  __TEXT.__unwind_info: 0xb808
+  __TEXT.__unwind_info: 0xb880
   __TEXT.__eh_frame: 0x4d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x3218
-  __DATA_CONST.__objc_classlist: 0xee8
+  __DATA_CONST.__objc_classlist: 0xef0
   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x2d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x140f8
+  __DATA_CONST.__objc_selrefs: 0x14158
   __DATA_CONST.__objc_protorefs: 0x40
-  __DATA_CONST.__objc_superrefs: 0xc30
+  __DATA_CONST.__objc_superrefs: 0xc38
   __DATA_CONST.__objc_arraydata: 0x878
-  __DATA_CONST.__got: 0x28d0
-  __AUTH_CONST.__const: 0xb6c8
-  __AUTH_CONST.__cfstring: 0x2cca0
-  __AUTH_CONST.__objc_const: 0x40d48
-  __AUTH_CONST.__objc_intobj: 0x2490
+  __DATA_CONST.__got: 0x28f8
+  __AUTH_CONST.__const: 0xb6a0
+  __AUTH_CONST.__cfstring: 0x2cd20
+  __AUTH_CONST.__objc_const: 0x40e68
+  __AUTH_CONST.__objc_intobj: 0x24a8
   __AUTH_CONST.__objc_arrayobj: 0x7c8
-  __AUTH_CONST.__objc_doubleobj: 0x140
+  __AUTH_CONST.__objc_doubleobj: 0x150
   __AUTH_CONST.__objc_dictobj: 0xf0
   __AUTH_CONST.__objc_floatobj: 0x10
-  __AUTH_CONST.__auth_got: 0x16d8
-  __AUTH.__objc_data: 0x51d8
+  __AUTH_CONST.__auth_got: 0x1700
+  __AUTH.__objc_data: 0x5228
   __AUTH.__data: 0x3c0
-  __DATA.__objc_ivar: 0x34cc
-  __DATA.__data: 0x29c0
+  __DATA.__objc_ivar: 0x34d8
+  __DATA.__data: 0x29e0
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1778
+  __DATA.__bss: 0x16b8
   __DATA.__common: 0x49
   __DATA_DIRTY.__objc_data: 0x4350
   __DATA_DIRTY.__data: 0x1a8
-  __DATA_DIRTY.__bss: 0x3f8
+  __DATA_DIRTY.__bss: 0x438
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AudioUnit.framework/Versions/A/AudioUnit

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 14883
-  Symbols:   33643
-  CStrings:  8727
+  Functions: 14916
+  Symbols:   33684
+  CStrings:  8735
 
Symbols:
+ +[PHAssetExportRequest _provenanceRenderURLToShareForAsset:options:fileURLs:]
+ +[PHAssetExportRequest _shouldCombineProvenanceIntoRenderForAsset:options:fileURLs:]
+ +[PHAssetResource assetResourcesForAsset:resourceTypeGroups:]
+ +[PHAssetResource fetchAssetResourcesForAssets:resourceTypeGroups:]
+ +[PHAssetResource fetchAssetResourcesForAssetsArray:resourceTypeGroups:]
+ +[PHAssetResource resources:matchingTypeGroups:]
+ +[PHAssetResourceFetchResult fetchResultWithAssets:resourceTypeGroups:]
+ +[PHResourceLocalAvailabilityRequest _shouldAddOriginalAsProvenanceSourceForAsset:shouldStripProvenance:]
+ +[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:includeLowConfidenceText:]
+ +[PHSensitiveContentAnalysisUtility sensitiveContentStateForAsset:]
+ -[PHAssetCreationRequest _creationOptionsPreservingOriginalProvenanceFilenameForResource:]
+ -[PHAssetResource prefetchedMediaMetadata]
+ -[PHAssetResource setPrefetchedMediaMetadata:]
+ -[PHAssetResourceFetchResult initWithAssets:resourceTypeGroups:]
+ -[PHAssetResourceFetchResult typeGroups]
+ -[PHCollectionShare _updateAccessRequestForParticipant:toAcceptanceStatus:completion:]
+ -[PHCollectionShare approveAccessRequestForParticipant:completion:]
+ -[PHCollectionShare blockAccessRequestForParticipant:completion:]
+ -[PHCollectionShare denyAccessRequestForParticipant:completion:]
+ -[PHCollectionShare unblockAccessRequestForParticipant:completion:]
+ -[PHPrefetchedMediaMetadata .cxx_destruct]
+ -[PHPrefetchedMediaMetadata data]
+ -[PHPrefetchedMediaMetadata initWithData:type:]
+ -[PHPrefetchedMediaMetadata type]
+ GCC_except_table10112
+ GCC_except_table10122
+ GCC_except_table10137
+ GCC_except_table10144
+ GCC_except_table10147
+ GCC_except_table10177
+ GCC_except_table10192
+ GCC_except_table10202
+ GCC_except_table10278
+ GCC_except_table10279
+ GCC_except_table10280
+ GCC_except_table10281
+ GCC_except_table10282
+ GCC_except_table10283
+ GCC_except_table10284
+ GCC_except_table10285
+ GCC_except_table10286
+ GCC_except_table10287
+ GCC_except_table10288
+ GCC_except_table10408
+ GCC_except_table10409
+ GCC_except_table10410
+ GCC_except_table10411
+ GCC_except_table10412
+ GCC_except_table10413
+ GCC_except_table10425
+ GCC_except_table10443
+ GCC_except_table10476
+ GCC_except_table10477
+ GCC_except_table10478
+ GCC_except_table10480
+ GCC_except_table10490
+ GCC_except_table10508
+ GCC_except_table10509
+ GCC_except_table10510
+ GCC_except_table10511
+ GCC_except_table10512
+ GCC_except_table10513
+ GCC_except_table10514
+ GCC_except_table10515
+ GCC_except_table10516
+ GCC_except_table10517
+ GCC_except_table10554
+ GCC_except_table10555
+ GCC_except_table10559
+ GCC_except_table10580
+ GCC_except_table10587
+ GCC_except_table10669
+ GCC_except_table10762
+ GCC_except_table10930
+ GCC_except_table10950
+ GCC_except_table10953
+ GCC_except_table10954
+ GCC_except_table10980
+ GCC_except_table10982
+ GCC_except_table11072
+ GCC_except_table11090
+ GCC_except_table11609
+ GCC_except_table11766
+ GCC_except_table11769
+ GCC_except_table11775
+ GCC_except_table11783
+ GCC_except_table11787
+ GCC_except_table11789
+ GCC_except_table11793
+ GCC_except_table11799
+ GCC_except_table11905
+ GCC_except_table11925
+ GCC_except_table11927
+ GCC_except_table11929
+ GCC_except_table11931
+ GCC_except_table11966
+ GCC_except_table12022
+ GCC_except_table12024
+ GCC_except_table12026
+ GCC_except_table12032
+ GCC_except_table12069
+ GCC_except_table12200
+ GCC_except_table12226
+ GCC_except_table12238
+ GCC_except_table12280
+ GCC_except_table12294
+ GCC_except_table12380
+ GCC_except_table12384
+ GCC_except_table12425
+ GCC_except_table12429
+ GCC_except_table12438
+ GCC_except_table12439
+ GCC_except_table12446
+ GCC_except_table12484
+ GCC_except_table12491
+ GCC_except_table12501
+ GCC_except_table12506
+ GCC_except_table12556
+ GCC_except_table12651
+ GCC_except_table12657
+ GCC_except_table12659
+ GCC_except_table12699
+ GCC_except_table12729
+ GCC_except_table12794
+ GCC_except_table12802
+ GCC_except_table12808
+ GCC_except_table12810
+ GCC_except_table12875
+ GCC_except_table12953
+ GCC_except_table12957
+ GCC_except_table12961
+ GCC_except_table12998
+ GCC_except_table13023
+ GCC_except_table13030
+ GCC_except_table13161
+ GCC_except_table13174
+ GCC_except_table13269
+ GCC_except_table13336
+ GCC_except_table13542
+ GCC_except_table13621
+ GCC_except_table13663
+ GCC_except_table13712
+ GCC_except_table13722
+ GCC_except_table13742
+ GCC_except_table13757
+ GCC_except_table13785
+ GCC_except_table13787
+ GCC_except_table13800
+ GCC_except_table13802
+ GCC_except_table13804
+ GCC_except_table13823
+ GCC_except_table13980
+ GCC_except_table14007
+ GCC_except_table14013
+ GCC_except_table14029
+ GCC_except_table14099
+ GCC_except_table14101
+ GCC_except_table14147
+ GCC_except_table14149
+ GCC_except_table14176
+ GCC_except_table14180
+ GCC_except_table14181
+ GCC_except_table14193
+ GCC_except_table14210
+ GCC_except_table14213
+ GCC_except_table14367
+ GCC_except_table2215
+ GCC_except_table2217
+ GCC_except_table2220
+ GCC_except_table2223
+ GCC_except_table2332
+ GCC_except_table2337
+ GCC_except_table2355
+ GCC_except_table2369
+ GCC_except_table2409
+ GCC_except_table2582
+ GCC_except_table2595
+ GCC_except_table2623
+ GCC_except_table2640
+ GCC_except_table2659
+ GCC_except_table2669
+ GCC_except_table2707
+ GCC_except_table2712
+ GCC_except_table2774
+ GCC_except_table2879
+ GCC_except_table2890
+ GCC_except_table2892
+ GCC_except_table2898
+ GCC_except_table2906
+ GCC_except_table2938
+ GCC_except_table3020
+ GCC_except_table3026
+ GCC_except_table3034
+ GCC_except_table3043
+ GCC_except_table3057
+ GCC_except_table3063
+ GCC_except_table3071
+ GCC_except_table3196
+ GCC_except_table3200
+ GCC_except_table3270
+ GCC_except_table3278
+ GCC_except_table3313
+ GCC_except_table3317
+ GCC_except_table3322
+ GCC_except_table3444
+ GCC_except_table3481
+ GCC_except_table3489
+ GCC_except_table3502
+ GCC_except_table3506
+ GCC_except_table3517
+ GCC_except_table3530
+ GCC_except_table3534
+ GCC_except_table3548
+ GCC_except_table3554
+ GCC_except_table3565
+ GCC_except_table3566
+ GCC_except_table3583
+ GCC_except_table3592
+ GCC_except_table3689
+ GCC_except_table3696
+ GCC_except_table3717
+ GCC_except_table3719
+ GCC_except_table3721
+ GCC_except_table3768
+ GCC_except_table3796
+ GCC_except_table3827
+ GCC_except_table3829
+ GCC_except_table3847
+ GCC_except_table3849
+ GCC_except_table4012
+ GCC_except_table4046
+ GCC_except_table4054
+ GCC_except_table4056
+ GCC_except_table4071
+ GCC_except_table4076
+ GCC_except_table4109
+ GCC_except_table4114
+ GCC_except_table4115
+ GCC_except_table4382
+ GCC_except_table4389
+ GCC_except_table4423
+ GCC_except_table4445
+ GCC_except_table4448
+ GCC_except_table4453
+ GCC_except_table4458
+ GCC_except_table4469
+ GCC_except_table4473
+ GCC_except_table4495
+ GCC_except_table4508
+ GCC_except_table4509
+ GCC_except_table4569
+ GCC_except_table4894
+ GCC_except_table4904
+ GCC_except_table4967
+ GCC_except_table4971
+ GCC_except_table4976
+ GCC_except_table5046
+ GCC_except_table5051
+ GCC_except_table5083
+ GCC_except_table5213
+ GCC_except_table5217
+ GCC_except_table5573
+ GCC_except_table5605
+ GCC_except_table5652
+ GCC_except_table5678
+ GCC_except_table5711
+ GCC_except_table5716
+ GCC_except_table5744
+ GCC_except_table5748
+ GCC_except_table5778
+ GCC_except_table5792
+ GCC_except_table5795
+ GCC_except_table5798
+ GCC_except_table5821
+ GCC_except_table5872
+ GCC_except_table5883
+ GCC_except_table5925
+ GCC_except_table5957
+ GCC_except_table5960
+ GCC_except_table5966
+ GCC_except_table5970
+ GCC_except_table5981
+ GCC_except_table6012
+ GCC_except_table6041
+ GCC_except_table6068
+ GCC_except_table6070
+ GCC_except_table6083
+ GCC_except_table6153
+ GCC_except_table6231
+ GCC_except_table6236
+ GCC_except_table6241
+ GCC_except_table6399
+ GCC_except_table6404
+ GCC_except_table6418
+ GCC_except_table6443
+ GCC_except_table6453
+ GCC_except_table6456
+ GCC_except_table6495
+ GCC_except_table6532
+ GCC_except_table6534
+ GCC_except_table6934
+ GCC_except_table6954
+ GCC_except_table6967
+ GCC_except_table6980
+ GCC_except_table6999
+ GCC_except_table7030
+ GCC_except_table7033
+ GCC_except_table7035
+ GCC_except_table7037
+ GCC_except_table7039
+ GCC_except_table7048
+ GCC_except_table7096
+ GCC_except_table7110
+ GCC_except_table7148
+ GCC_except_table7150
+ GCC_except_table7189
+ GCC_except_table7442
+ GCC_except_table7445
+ GCC_except_table7467
+ GCC_except_table7474
+ GCC_except_table7492
+ GCC_except_table7494
+ GCC_except_table7495
+ GCC_except_table7496
+ GCC_except_table7497
+ GCC_except_table7498
+ GCC_except_table7499
+ GCC_except_table7510
+ GCC_except_table7511
+ GCC_except_table7512
+ GCC_except_table7669
+ GCC_except_table7889
+ GCC_except_table7934
+ GCC_except_table7952
+ GCC_except_table7953
+ GCC_except_table8012
+ GCC_except_table8037
+ GCC_except_table8041
+ GCC_except_table8048
+ GCC_except_table8102
+ GCC_except_table8314
+ GCC_except_table8316
+ GCC_except_table8363
+ GCC_except_table8403
+ GCC_except_table8407
+ GCC_except_table8411
+ GCC_except_table8423
+ GCC_except_table8428
+ GCC_except_table8468
+ GCC_except_table8496
+ GCC_except_table8538
+ GCC_except_table8623
+ GCC_except_table8681
+ GCC_except_table8702
+ GCC_except_table8705
+ GCC_except_table8724
+ GCC_except_table8789
+ GCC_except_table8795
+ GCC_except_table8796
+ GCC_except_table8797
+ GCC_except_table8798
+ GCC_except_table8799
+ GCC_except_table8801
+ GCC_except_table8807
+ GCC_except_table8818
+ GCC_except_table8821
+ GCC_except_table8846
+ GCC_except_table8894
+ GCC_except_table8961
+ GCC_except_table9118
+ GCC_except_table9159
+ GCC_except_table9165
+ GCC_except_table9168
+ GCC_except_table9428
+ GCC_except_table9432
+ GCC_except_table9436
+ GCC_except_table9460
+ GCC_except_table9461
+ GCC_except_table9559
+ GCC_except_table9569
+ GCC_except_table9602
+ GCC_except_table9654
+ GCC_except_table9699
+ GCC_except_table9719
+ GCC_except_table9745
+ GCC_except_table9773
+ GCC_except_table9806
+ GCC_except_table9808
+ GCC_except_table9899
+ GCC_except_table9990
+ OBJC_IVAR_$_PHAssetResource._prefetchedMediaMetadata
+ OBJC_IVAR_$_PHAssetResourceFetchResult._typeGroups
+ OBJC_IVAR_$_PHPrefetchedMediaMetadata._data
+ OBJC_IVAR_$_PHPrefetchedMediaMetadata._type
+ _OBJC_CLASS_$_PHPrefetchedMediaMetadata
+ _OBJC_CLASS_$_PLMediaMetadataVirtualResource
+ _OBJC_METACLASS_$_PHPrefetchedMediaMetadata
+ _PAMediaConversionErrorIsProvenanceProcessingError
+ _PHAssetResourceTypeGroupsIncludesTargetGroups
+ _PLIsMediaanalysisd
+ __77+[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:includeLowConfidenceText:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_PHPrefetchedMediaMetadata
+ __OBJC_$_INSTANCE_VARIABLES_PHPrefetchedMediaMetadata
+ __OBJC_$_PROP_LIST_PHPrefetchedMediaMetadata
+ __OBJC_CLASS_RO_$_PHPrefetchedMediaMetadata
+ __OBJC_METACLASS_RO_$_PHPrefetchedMediaMetadata
+ ___77+[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:includeLowConfidenceText:]_block_invoke
+ ___86-[PHCollectionShare _updateAccessRequestForParticipant:toAcceptanceStatus:completion:]_block_invoke
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ _associated conformance So26PHAssetResourceFetchResultCSl6Photos11SubSequenceSl_Sl
+ _associated conformance So26PHAssetResourceFetchResultCSl6Photos5IndexSl_SL
+ _associated conformance So26PHAssetResourceFetchResultCSl6Photos7IndicesSl_Sl
+ _associated conformance So26PHAssetResourceFetchResultCSl6PhotosST
+ _objc_msgSend$_creationOptionsPreservingOriginalProvenanceFilenameForResource:
+ _objc_msgSend$_provenanceRenderURLToShareForAsset:options:fileURLs:
+ _objc_msgSend$_shouldAddOriginalAsProvenanceSourceForAsset:shouldStripProvenance:
+ _objc_msgSend$_shouldCombineProvenanceIntoRenderForAsset:options:fileURLs:
+ _objc_msgSend$_updateAccessRequestForParticipant:toAcceptanceStatus:completion:
+ _objc_msgSend$assetResourcesForAsset:resourceTypeGroups:
+ _objc_msgSend$fetchAssetResourcesForAssets:resourceTypeGroups:
+ _objc_msgSend$fetchAssetResourcesForAssetsArray:resourceTypeGroups:
+ _objc_msgSend$fetchResultWithAssets:resourceTypeGroups:
+ _objc_msgSend$initWithAssets:resourceTypeGroups:
+ _objc_msgSend$initWithData:type:
+ _objc_msgSend$isSensitive
+ _objc_msgSend$itemsPerBatch
+ _objc_msgSend$mediaMetadataType
+ _objc_msgSend$ocrTextLinesForAssetUUID:inPhotoLibrary:includeLowConfidenceText:
+ _objc_msgSend$ocrTextLinesFromDocumentObservation:includeLowConfidenceText:
+ _objc_msgSend$predicateToExcludePostsWithoutAssets
+ _objc_msgSend$prefetchedMediaMetadata
+ _objc_msgSend$resources:matchingTypeGroups:
+ _objc_msgSend$setPrefetchedMediaMetadata:
+ _objc_msgSend$setProvenanceMetadataBehavior:withUnprocessedSourceRenderURL:processedOriginalDestinationURL:sidecarURL:
+ _objc_msgSend$typeGroups
+ _objc_msgSend$updateAccessRequestForParticipantWithUUID:toAcceptanceStatus:inCollectionShareWithIdentifier:completionHandler:
+ _simpleDeleteValidatorsWithManagedObjectContext:.pl_once_object_16
+ _simpleDeleteValidatorsWithManagedObjectContext:.pl_once_token_16
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _symbolic $sSl
+ _symbolic SIySo26PHAssetResourceFetchResultCG
+ _symbolic _____ySo26PHAssetResourceFetchResultCG s5SliceV
+ analyticsPropertiesToFetch.pl_once_object_15
+ analyticsPropertiesToFetch.pl_once_token_15
+ corePropertiesToFetch.pl_once_object_15
+ corePropertiesToFetch.pl_once_token_15
+ dateRangeTitleGenerator.pl_once_object_17
+ dateRangeTitleGenerator.pl_once_token_17
+ entityKeyMap.pl_once_object_15
+ entityKeyMap.pl_once_object_16
+ entityKeyMap.pl_once_token_15
+ entityKeyMap.pl_once_token_16
+ propertiesToFetch.pl_once_object_19
+ propertiesToFetch.pl_once_object_23
+ propertiesToFetch.pl_once_object_28
+ propertiesToFetch.pl_once_token_19
+ propertiesToFetch.pl_once_token_23
+ propertiesToFetch.pl_once_token_28
+ propertiesToFetchWithHint:.pl_once_object_15
+ propertiesToFetchWithHint:.pl_once_token_15
+ publicPHObjectChangeClasses.pl_once_object_29
+ publicPHObjectChangeClasses.pl_once_token_29
- +[PHAssetExportRequest _adjustedProvenanceRenderURLToShareForAsset:options:fileURLs:]
- +[PHAssetExportRequest _shouldCombineEditedProvenanceIntoRenderForAsset:options:fileURLs:]
- +[PHAssetResource resources:matchingTypeGroup:]
- +[PHAssetResourceFetchResult fetchResultWithAssets:resourceTypeGroup:]
- +[PHImportAsset scanAssetsForProvenanceData:atEnd:]
- +[PHResourceLocalAvailabilityRequest _shouldAddOriginalProvenanceResourceToResourcesToShareForAsset:shouldStripProvenance:]
- -[PHAssetResourceFetchResult initWithAssets:resourceTypeGroup:]
- -[PHAssetResourceFetchResult typeGroup]
- -[PHImportAsset hasProvenanceMetadata]
- -[PHShareParticipantChangeRequest approveAccessRequest]
- -[PHShareParticipantChangeRequest blockAccessRequest]
- -[PHShareParticipantChangeRequest denyAccessRequest]
- -[PHShareParticipantChangeRequest unblockAccessRequest]
- GCC_except_table10101
- GCC_except_table10111
- GCC_except_table10125
- GCC_except_table10126
- GCC_except_table10133
- GCC_except_table10159
- GCC_except_table10160
- GCC_except_table10161
- GCC_except_table10162
- GCC_except_table10163
- GCC_except_table10164
- GCC_except_table10165
- GCC_except_table10166
- GCC_except_table10169
- GCC_except_table10178
- GCC_except_table10179
- GCC_except_table10188
- GCC_except_table10203
- GCC_except_table10213
- GCC_except_table10388
- GCC_except_table10397
- GCC_except_table10398
- GCC_except_table10400
- GCC_except_table10401
- GCC_except_table10402
- GCC_except_table10403
- GCC_except_table10432
- GCC_except_table10465
- GCC_except_table10466
- GCC_except_table10467
- GCC_except_table10468
- GCC_except_table10469
- GCC_except_table10497
- GCC_except_table10498
- GCC_except_table10499
- GCC_except_table10500
- GCC_except_table10501
- GCC_except_table10502
- GCC_except_table10503
- GCC_except_table10504
- GCC_except_table10505
- GCC_except_table10506
- GCC_except_table10543
- GCC_except_table10544
- GCC_except_table10548
- GCC_except_table10569
- GCC_except_table10576
- GCC_except_table10658
- GCC_except_table10751
- GCC_except_table10919
- GCC_except_table10939
- GCC_except_table10942
- GCC_except_table10943
- GCC_except_table10969
- GCC_except_table10971
- GCC_except_table11061
- GCC_except_table11079
- GCC_except_table11598
- GCC_except_table11755
- GCC_except_table11758
- GCC_except_table11764
- GCC_except_table11772
- GCC_except_table11776
- GCC_except_table11778
- GCC_except_table11782
- GCC_except_table11788
- GCC_except_table11894
- GCC_except_table11914
- GCC_except_table11916
- GCC_except_table11918
- GCC_except_table11920
- GCC_except_table11955
- GCC_except_table12004
- GCC_except_table12011
- GCC_except_table12013
- GCC_except_table12021
- GCC_except_table12058
- GCC_except_table12189
- GCC_except_table12215
- GCC_except_table12227
- GCC_except_table12269
- GCC_except_table12283
- GCC_except_table12369
- GCC_except_table12373
- GCC_except_table12414
- GCC_except_table12418
- GCC_except_table12427
- GCC_except_table12428
- GCC_except_table12435
- GCC_except_table12473
- GCC_except_table12480
- GCC_except_table12490
- GCC_except_table12495
- GCC_except_table12545
- GCC_except_table12637
- GCC_except_table12640
- GCC_except_table12646
- GCC_except_table12688
- GCC_except_table12707
- GCC_except_table12780
- GCC_except_table12783
- GCC_except_table12797
- GCC_except_table12799
- GCC_except_table12864
- GCC_except_table12942
- GCC_except_table12946
- GCC_except_table12950
- GCC_except_table12987
- GCC_except_table13012
- GCC_except_table13019
- GCC_except_table13150
- GCC_except_table13163
- GCC_except_table13258
- GCC_except_table13325
- GCC_except_table13531
- GCC_except_table13610
- GCC_except_table13652
- GCC_except_table13701
- GCC_except_table13711
- GCC_except_table13731
- GCC_except_table13746
- GCC_except_table13774
- GCC_except_table13776
- GCC_except_table13789
- GCC_except_table13791
- GCC_except_table13793
- GCC_except_table13812
- GCC_except_table13958
- GCC_except_table13996
- GCC_except_table14002
- GCC_except_table14018
- GCC_except_table14088
- GCC_except_table14090
- GCC_except_table14136
- GCC_except_table14138
- GCC_except_table14165
- GCC_except_table14169
- GCC_except_table14170
- GCC_except_table14182
- GCC_except_table14199
- GCC_except_table14202
- GCC_except_table14356
- GCC_except_table2216
- GCC_except_table2218
- GCC_except_table2221
- GCC_except_table2224
- GCC_except_table2264
- GCC_except_table2336
- GCC_except_table2341
- GCC_except_table2359
- GCC_except_table2373
- GCC_except_table2413
- GCC_except_table2586
- GCC_except_table2599
- GCC_except_table2627
- GCC_except_table2644
- GCC_except_table2663
- GCC_except_table2673
- GCC_except_table2710
- GCC_except_table2715
- GCC_except_table2777
- GCC_except_table2882
- GCC_except_table2893
- GCC_except_table2895
- GCC_except_table2901
- GCC_except_table2909
- GCC_except_table2941
- GCC_except_table3023
- GCC_except_table3029
- GCC_except_table3037
- GCC_except_table3046
- GCC_except_table3060
- GCC_except_table3066
- GCC_except_table3074
- GCC_except_table3199
- GCC_except_table3206
- GCC_except_table3273
- GCC_except_table3281
- GCC_except_table3316
- GCC_except_table3320
- GCC_except_table3325
- GCC_except_table3447
- GCC_except_table3484
- GCC_except_table3495
- GCC_except_table3505
- GCC_except_table3509
- GCC_except_table3523
- GCC_except_table3533
- GCC_except_table3537
- GCC_except_table3551
- GCC_except_table3557
- GCC_except_table3568
- GCC_except_table3569
- GCC_except_table3586
- GCC_except_table3595
- GCC_except_table3692
- GCC_except_table3699
- GCC_except_table3720
- GCC_except_table3722
- GCC_except_table3724
- GCC_except_table3771
- GCC_except_table3799
- GCC_except_table3830
- GCC_except_table3832
- GCC_except_table3850
- GCC_except_table3855
- GCC_except_table4015
- GCC_except_table4049
- GCC_except_table4057
- GCC_except_table4059
- GCC_except_table4077
- GCC_except_table4079
- GCC_except_table4112
- GCC_except_table4117
- GCC_except_table4118
- GCC_except_table4385
- GCC_except_table4392
- GCC_except_table4425
- GCC_except_table4447
- GCC_except_table4450
- GCC_except_table4455
- GCC_except_table4460
- GCC_except_table4471
- GCC_except_table4475
- GCC_except_table4497
- GCC_except_table4510
- GCC_except_table4511
- GCC_except_table4571
- GCC_except_table4896
- GCC_except_table4906
- GCC_except_table4969
- GCC_except_table4975
- GCC_except_table4978
- GCC_except_table5048
- GCC_except_table5053
- GCC_except_table5085
- GCC_except_table5215
- GCC_except_table5219
- GCC_except_table5566
- GCC_except_table5598
- GCC_except_table5644
- GCC_except_table5670
- GCC_except_table5703
- GCC_except_table5708
- GCC_except_table5732
- GCC_except_table5736
- GCC_except_table5762
- GCC_except_table5784
- GCC_except_table5787
- GCC_except_table5790
- GCC_except_table5813
- GCC_except_table5864
- GCC_except_table5875
- GCC_except_table5917
- GCC_except_table5949
- GCC_except_table5952
- GCC_except_table5958
- GCC_except_table5962
- GCC_except_table5973
- GCC_except_table6004
- GCC_except_table6033
- GCC_except_table6060
- GCC_except_table6062
- GCC_except_table6075
- GCC_except_table6145
- GCC_except_table6223
- GCC_except_table6228
- GCC_except_table6233
- GCC_except_table6391
- GCC_except_table6396
- GCC_except_table6410
- GCC_except_table6435
- GCC_except_table6445
- GCC_except_table6448
- GCC_except_table6487
- GCC_except_table6524
- GCC_except_table6526
- GCC_except_table6926
- GCC_except_table6946
- GCC_except_table6959
- GCC_except_table6972
- GCC_except_table6991
- GCC_except_table7022
- GCC_except_table7025
- GCC_except_table7027
- GCC_except_table7029
- GCC_except_table7031
- GCC_except_table7040
- GCC_except_table7088
- GCC_except_table7102
- GCC_except_table7140
- GCC_except_table7142
- GCC_except_table7181
- GCC_except_table7434
- GCC_except_table7437
- GCC_except_table7459
- GCC_except_table7466
- GCC_except_table7484
- GCC_except_table7486
- GCC_except_table7487
- GCC_except_table7488
- GCC_except_table7489
- GCC_except_table7490
- GCC_except_table7491
- GCC_except_table7502
- GCC_except_table7503
- GCC_except_table7504
- GCC_except_table7661
- GCC_except_table7881
- GCC_except_table7926
- GCC_except_table7944
- GCC_except_table7945
- GCC_except_table8004
- GCC_except_table8029
- GCC_except_table8033
- GCC_except_table8040
- GCC_except_table8094
- GCC_except_table8300
- GCC_except_table8302
- GCC_except_table8349
- GCC_except_table8389
- GCC_except_table8393
- GCC_except_table8395
- GCC_except_table8397
- GCC_except_table8414
- GCC_except_table8454
- GCC_except_table8482
- GCC_except_table8524
- GCC_except_table8608
- GCC_except_table8666
- GCC_except_table8687
- GCC_except_table8690
- GCC_except_table8709
- GCC_except_table8768
- GCC_except_table8774
- GCC_except_table8780
- GCC_except_table8781
- GCC_except_table8782
- GCC_except_table8784
- GCC_except_table8786
- GCC_except_table8788
- GCC_except_table8792
- GCC_except_table8806
- GCC_except_table8831
- GCC_except_table8879
- GCC_except_table8946
- GCC_except_table9103
- GCC_except_table9144
- GCC_except_table9150
- GCC_except_table9153
- GCC_except_table9417
- GCC_except_table9421
- GCC_except_table9425
- GCC_except_table9449
- GCC_except_table9450
- GCC_except_table9548
- GCC_except_table9558
- GCC_except_table9591
- GCC_except_table9643
- GCC_except_table9688
- GCC_except_table9708
- GCC_except_table9734
- GCC_except_table9762
- GCC_except_table9795
- GCC_except_table9797
- GCC_except_table9888
- GCC_except_table9979
- OBJC_IVAR_$_PHAssetResourceFetchResult._typeGroup
- __52+[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:]_block_invoke
- ___51+[PHImportAsset scanAssetsForProvenanceData:atEnd:]_block_invoke
- ___51+[PHImportAsset scanAssetsForProvenanceData:atEnd:]_block_invoke_2
- ___52+[PHSearch ocrTextLinesForAssetUUID:inPhotoLibrary:]_block_invoke
- _associated conformance So26PHAssetResourceFetchResultC6PhotosE5IndexVSLACSQ
- _objc_msgSend$_adjustedProvenanceRenderURLToShareForAsset:options:fileURLs:
- _objc_msgSend$_shouldAddOriginalProvenanceResourceToResourcesToShareForAsset:shouldStripProvenance:
- _objc_msgSend$_shouldCombineEditedProvenanceIntoRenderForAsset:options:fileURLs:
- _objc_msgSend$fetchResultWithAssets:resourceTypeGroup:
- _objc_msgSend$hasProvenanceMetadata
- _objc_msgSend$initWithAssets:resourceTypeGroup:
- _objc_msgSend$ocrTextLinesFromDocumentObservation:
- _objc_msgSend$resources:matchingTypeGroup:
- _objc_msgSend$setProvenanceMetadataBehavior:withUnprocessedSourceAdjustedRenderURL:processedOriginalDestinationURL:sidecarURL:
- _objc_msgSend$setSkipAssetRelationshipValidationOnSave:
- _objc_msgSend$typeGroup
- _simpleDeleteValidatorsWithManagedObjectContext:.pl_once_object_3
- _simpleDeleteValidatorsWithManagedObjectContext:.pl_once_token_3
- _symbolic _____ So26PHAssetResourceFetchResultC6PhotosE5IndexV
- _type_layout_string So26PHAssetResourceFetchResultC6PhotosE5IndexV
- analyticsPropertiesToFetch.pl_once_object_2
- analyticsPropertiesToFetch.pl_once_token_2
- corePropertiesToFetch.pl_once_object_2
- corePropertiesToFetch.pl_once_token_2
- dateRangeTitleGenerator.pl_once_object_4
- dateRangeTitleGenerator.pl_once_token_4
- entityKeyMap.pl_once_object_2
- entityKeyMap.pl_once_object_3
- entityKeyMap.pl_once_token_2
- entityKeyMap.pl_once_token_3
- propertiesToFetch.pl_once_object_10
- propertiesToFetch.pl_once_object_15
- propertiesToFetch.pl_once_object_6
- propertiesToFetch.pl_once_token_10
- propertiesToFetch.pl_once_token_15
- propertiesToFetch.pl_once_token_6
- propertiesToFetchWithHint:.pl_once_object_2
- propertiesToFetchWithHint:.pl_once_token_2
- publicPHObjectChangeClasses.pl_once_object_16
- publicPHObjectChangeClasses.pl_once_token_16
CStrings:
+ "-[PHAssetExportRequest _processResourcesAtFileURLs:forAsset:withOptions:progress:processingUnitCount:replacementLivePhotoPairingIdentifier:completion:]"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/Photos/Projects/PhotoKit/Sources/PHAssetExportRequest.m"
+ "AssetResourceUploadJobConfiguration is not in correct state."
+ "Edited provenance asset has no full-size render to combine its provenance into"
+ "Exceeded permitted number of AssetResourceUploadJobs."
+ "No AssetResourceUploadJobConfiguration is set for this change request."
+ "Provenance asset needs a full-size render to carry its original's provenance, but none was selected"
+ "Share participant has no UUID"
+ "[PHAssetExportRequest] Unable to create asset bundle at directory '%@' due to following error '%@'"
+ "[PHAssetExportRequest] Unable to create live photo bundle at '%@' due to following error '%@'"
+ "[PHAssetExportRequest][ContentProvenance] Provenance processing error while processing resources of asset %{public}@: %@"
+ "[PHResourceLocalAvailabilityRequest] Provenance asset needs its original carried into a full-size render, but none was selected for asset: %@, resources: %@, options: %@"
+ "[PHResourceLocalAvailabilityRequest] Routing provenance render to FullSizePhotoURLKey (keeping original in PhotoURLKey) for asset:%@"
+ "[RM] %@ Media metadata with version: %ld has no type string"
+ "typeGroups != 0"
- "Configuration is not in correct state."
- "Edited provenance asset selected its original as a provenance source but has no full-size render to carry it"
- "Too many jobs."
- "Unable to create asset bundle at directory '%@' due to following error '%@'"
- "Unable to create live photo bundle at '%@' due to following error '%@'"
- "[PHResourceLocalAvailabilityRequest] Routing edited provenance render to FullSizePhotoURLKey (keeping original in PhotoURLKey) for asset:%@"
- "[PHResourceLocalAvailabilityRequest] Selected original as provenance source but no full-size render is available to carry it for asset: %@, resources: %@, options: %@"
```
