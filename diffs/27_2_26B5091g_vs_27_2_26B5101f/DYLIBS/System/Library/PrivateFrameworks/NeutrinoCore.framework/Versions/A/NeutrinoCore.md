## NeutrinoCore

> `/System/Library/PrivateFrameworks/NeutrinoCore.framework/Versions/A/NeutrinoCore`

```diff

-916.45.110.0.0
-  __TEXT.__text: 0x345fe8
-  __TEXT.__objc_methlist: 0x210fc
+916.53.100.0.0
+  __TEXT.__text: 0x354c2c
+  __TEXT.__objc_methlist: 0x216f4
   __TEXT.__const: 0x27a8
   __TEXT.__dlopen_cstrs: 0x45
-  __TEXT.__swift5_typeref: 0x3c9
+  __TEXT.__swift5_typeref: 0x52b
   __TEXT.__swift5_reflstr: 0x93
   __TEXT.__swift5_assocty: 0x78
   __TEXT.__constg_swiftt: 0x158

   __TEXT.__swift5_fieldmd: 0x15c
   __TEXT.__swift5_proto: 0x64
   __TEXT.__swift5_types: 0x28
-  __TEXT.__cstring: 0x40712
-  __TEXT.__swift5_capture: 0x1f0
-  __TEXT.__gcc_except_tab: 0x8194
-  __TEXT.__oslogstring: 0x5930
+  __TEXT.__cstring: 0x4116b
+  __TEXT.__swift5_capture: 0x350
+  __TEXT.__gcc_except_tab: 0x81c8
+  __TEXT.__oslogstring: 0x594f
   __TEXT.__ustring: 0x2e
-  __TEXT.__unwind_info: 0xa458
-  __TEXT.__eh_frame: 0x400
+  __TEXT.__unwind_info: 0xa660
+  __TEXT.__eh_frame: 0x650
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1660
-  __DATA_CONST.__objc_classlist: 0x1600
+  __DATA_CONST.__const: 0x1670
+  __DATA_CONST.__objc_classlist: 0x1618
   __DATA_CONST.__objc_catlist: 0xa8
-  __DATA_CONST.__objc_protolist: 0x4d8
+  __DATA_CONST.__objc_protolist: 0x4e0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb738
+  __DATA_CONST.__objc_selrefs: 0xb880
   __DATA_CONST.__objc_protorefs: 0x68
-  __DATA_CONST.__objc_superrefs: 0x1018
-  __DATA_CONST.__objc_arraydata: 0xac0
-  __DATA_CONST.__got: 0x2290
-  __AUTH_CONST.__const: 0x80e8
-  __AUTH_CONST.__cfstring: 0x1d040
-  __AUTH_CONST.__objc_const: 0x37a10
+  __DATA_CONST.__objc_superrefs: 0x1028
+  __DATA_CONST.__objc_arraydata: 0xad0
+  __DATA_CONST.__got: 0x22f8
+  __AUTH_CONST.__const: 0x87e0
+  __AUTH_CONST.__cfstring: 0x1d500
+  __AUTH_CONST.__objc_const: 0x37ed0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x8d0
-  __AUTH_CONST.__objc_dictobj: 0x320
+  __AUTH_CONST.__objc_dictobj: 0x348
   __AUTH_CONST.__objc_doubleobj: 0x210
   __AUTH_CONST.__objc_floatobj: 0x70
   __AUTH_CONST.__objc_arrayobj: 0xf0
-  __AUTH_CONST.__auth_got: 0xfd0
-  __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0x1a78
-  __DATA.__data: 0x1c0
+  __AUTH_CONST.__auth_got: 0xfe0
+  __AUTH.__objc_data: 0x190
+  __DATA.__objc_ivar: 0x1aa4
+  __DATA.__data: 0x248
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x1010
-  __DATA_DIRTY.__objc_data: 0xdbb0
+  __DATA.__bss: 0x1020
+  __DATA_DIRTY.__objc_data: 0xdb60
   __DATA_DIRTY.__data: 0x3780
   __DATA_DIRTY.__bss: 0x158
   __DATA_DIRTY.__common: 0x40

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 12022
-  Symbols:   25803
-  CStrings:  7309
+  Functions: 12231
+  Symbols:   26041
+  CStrings:  7384
 
Symbols:
+ +[NUAssetCapability rawDecodeCapabilityFormat]
+ +[NUChannelData nullDataWithOptionalFormat:]
+ +[NUPipelineFactory optionalSelectorPipelineWithFormat:includeFallback:]
+ +[NUPixelFormat YCC8f420]
+ +[NUPixelFormat YCC8v420]
+ -[NSArray(NUControlDataRepresentable) nu_cardinality]
+ -[NSArray(NUControlDataRepresentable) nu_subdataAtIndex:format:error:]
+ -[NSObject(NUControlDataRepresentable) nu_cardinality]
+ -[NSObject(NUControlDataRepresentable) nu_subdataAtIndex:format:error:]
+ -[NSObject(NUControlDataRepresentable) nu_subdataForKey:format:error:]
+ -[NUArrayDescriptor defaultValueType]
+ -[NUBrushStrokeMaskIntersector initWithBrushMask:mask:strokeScale:ciContext:]
+ -[NUChannelArrayFormat genericFormat]
+ -[NUChannelAudioMediaFormat genericFormat]
+ -[NUChannelComponentMediaFormat genericFormat]
+ -[NUChannelComputedDataMediaFormat genericFormat]
+ -[NUChannelControlFormat optionalFormat]
+ -[NUChannelElementFormat arrayItemFormat]
+ -[NUChannelElementFormat elementChannel]
+ -[NUChannelElementFormat genericFormat]
+ -[NUChannelElementFormat isArray]
+ -[NUChannelFormat genericFormat]
+ -[NUChannelFormat isUnknown]
+ -[NUChannelFormat optionalFormat]
+ -[NUChannelGenericMediaFormat genericFormat]
+ -[NUChannelImageMediaFormat genericFormat]
+ -[NUChannelMetadataMediaFormat genericFormat]
+ -[NUChannelNullData isNull]
+ -[NUChannelOptionalFormat genericFormat]
+ -[NUChannelOptionalFormat optionalFormat]
+ -[NUClosureExpression .cxx_destruct]
+ -[NUClosureExpression compactDescription]
+ -[NUClosureExpression copyWithArguments:]
+ -[NUClosureExpression description]
+ -[NUClosureExpression evaluateWithArgumentData:format:error:]
+ -[NUClosureExpression formatWithArgumentData:error:]
+ -[NUClosureExpression hash]
+ -[NUClosureExpression initWithName:format:arguments:evaluate:]
+ -[NUClosureExpression isEqualToExpression:]
+ -[NUClosureExpression name]
+ -[NUClosureExpression nu_updateDigest:]
+ -[NUClosureExpression resultFormat]
+ -[NUCropModel cropRectFittingSize:nearCenter:]
+ -[NUFactory _evictVisionSessionIfUsed]
+ -[NUHistogramCalculator .cxx_destruct]
+ -[NUHistogramCalculator ciContext]
+ -[NUHistogramCalculator setCiContext:]
+ -[NUImageExportRequest _commonInit]
+ -[NUImageExportRequest progress]
+ -[NULivePhotoExportRequest progress]
+ -[NUOptionalDescriptor descriptorForKey:]
+ -[NUOptionalDescriptor valueForKey:data:]
+ -[NUUnknownChannelFormat canAcceptDataWithFormat:]
+ -[NUUnknownChannelFormat canSpecializeFormat:]
+ -[NUUnknownChannelFormat channelType]
+ -[NUUnknownChannelFormat hash]
+ -[NUUnknownChannelFormat isComparableToChannelFormat:]
+ -[NUUnknownChannelFormat isEqualToChannelFormat:]
+ -[NUUnknownChannelFormat isGeneric]
+ -[NUUnknownChannelFormat isUnknown]
+ -[NUUnknownChannelFormat specializedWithFormat:]
+ -[NUVectorDescriptor defaultValueType]
+ -[NUVideoCompositor maximumPendingVideoCompositionRequests]
+ -[NUVideoCompositor setMaximumPendingVideoCompositionRequests:]
+ -[NUVideoExportRequest maximumPendingVideoCompositionRequests]
+ -[NUVideoExportRequest setMaximumPendingVideoCompositionRequests:]
+ -[NUVideoExporterTrack maximumPendingVideoCompositionRequests]
+ -[NUVideoExporterTrack setMaximumPendingVideoCompositionRequests:]
+ -[_NUAsset addCapability:data:]
+ -[_NUChannelPort isElement]
+ -[_NUMapPipeline addElementOutputFormat:]
+ -[_NUMapPipeline initWithArrayFormat:]
+ -[_NUOptionalSelectorPipeline _evaluateInputsWithContext:error:]
+ -[_NUOptionalSelectorPipeline _evaluateOutputPort:context:error:]
+ -[_NUOptionalSelectorPipeline _genericInputPortsMatchingOutputPort:]
+ -[_NUOptionalSelectorPipeline _genericOutputPortsMatchingInputPort:]
+ -[_NUOptionalSelectorPipeline alias]
+ -[_NUOptionalSelectorPipeline initWithChannelFormat:]
+ -[_NUOptionalSelectorPipeline initWithChannelFormat:includeFallback:]
+ -[_NUOptionalSelectorPipeline initWithName:opaque:]
+ -[_NUOptionalSelectorPipeline isInline]
+ -[_NUPipeline _addOptionalSelectorWithInput:fallback:error:]
+ -[_NUPipeline ifNotNil:else:]
+ -[_NUPipeline ifNotNil:else:error:]
+ -[_NUPipeline insertMap:at:block:error:]
+ -[_NUPipeline insertMapAt:format:block:error:]
+ -[_NUPipeline insertMapAt:input:block:error:]
+ -[_NUPipeline insertMapWithFormat:at:block:error:]
+ -[_NUPipeline insertReduce:with:at:block:error:]
+ -[_NUPipeline insertReduceAt:arrayFormat:resultFormat:block:error:]
+ -[_NUPipeline insertReduceAt:input:initialResult:block:error:]
+ -[_NUPipeline insertReduceWithArrayFormat:resultFormat:at:block:error:]
+ -[_NUPipeline insertSwitchAt:format:unwrappingChannels:block:error:]
+ -[_NUPipeline insertSwitchAt:on:with:block:error:]
+ -[_NUPipeline insertSwitchAt:on:with:unwrappingChannels:block:error:]
+ -[_NUPipeline insertSwitchAt:on:with:unwrappingPorts:block:error:]
+ -[_NUPipeline insertUnwrapAt:withBlock:error:]
+ -[_NUPipeline mapInput:block:error:]
+ -[_NUPipeline switchOn:with:unwrappingPorts:block:]
+ -[_NUPipeline switchOn:with:unwrappingPorts:block:error:]
+ -[_NUPipeline unwrapInputs:block:]
+ -[_NUPipeline unwrapInputs:block:error:]
+ -[_NUPipeline unwrapOptional:]
+ -[_NUPipeline unwrapOptional:error:]
+ -[_NUReducePipeline initWithArrayFormat:resultFormat:]
+ -[_NUReducePipeline resultInputPort]
+ -[_NUReducePipeline resultOutputPort]
+ -[_NUSwitchPipeline _addOptionalInputChannel:]
+ -[_NUSwitchPipeline _evaluateOutputPort:context:error:]
+ -[_NUSwitchPipeline initWithSingleChannelMode:]
+ -[_NUSwitchPipeline isDynamic]
+ -[_NUTagPipeline _genericInputPortsMatchingOutputPort:]
+ -[_NUTagPipeline _genericOutputPortsMatchingInputPort:]
+ -[_NUUnwrapPipeline _addInputChannel:]
+ -[_NUUnwrapPipeline _addOutputChannel:]
+ -[_NUUnwrapPipeline _evaluateOutputPort:context:error:]
+ -[_NUUnwrapPipeline alias]
+ -[_NUUnwrapPipeline initWithName:opaque:]
+ -[_NUUnwrapPipeline init]
+ -[_NUUnwrapPipeline isDynamic]
+ -[_NUUnwrapPipeline isInline]
+ GCC_except_table10017
+ GCC_except_table10024
+ GCC_except_table10150
+ GCC_except_table10174
+ GCC_except_table10175
+ GCC_except_table10179
+ GCC_except_table10180
+ GCC_except_table10181
+ GCC_except_table10182
+ GCC_except_table10189
+ GCC_except_table10190
+ GCC_except_table10199
+ GCC_except_table10209
+ GCC_except_table10215
+ GCC_except_table10216
+ GCC_except_table10217
+ GCC_except_table10219
+ GCC_except_table10221
+ GCC_except_table10224
+ GCC_except_table10225
+ GCC_except_table10226
+ GCC_except_table10298
+ GCC_except_table10308
+ GCC_except_table10530
+ GCC_except_table10531
+ GCC_except_table10534
+ GCC_except_table10635
+ GCC_except_table10636
+ GCC_except_table10637
+ GCC_except_table10638
+ GCC_except_table10639
+ GCC_except_table10640
+ GCC_except_table10642
+ GCC_except_table10645
+ GCC_except_table10646
+ GCC_except_table10648
+ GCC_except_table10649
+ GCC_except_table10650
+ GCC_except_table10652
+ GCC_except_table10653
+ GCC_except_table10663
+ GCC_except_table10664
+ GCC_except_table10669
+ GCC_except_table10670
+ GCC_except_table10671
+ GCC_except_table10672
+ GCC_except_table10674
+ GCC_except_table10675
+ GCC_except_table10676
+ GCC_except_table10677
+ GCC_except_table10679
+ GCC_except_table10680
+ GCC_except_table10681
+ GCC_except_table10682
+ GCC_except_table10683
+ GCC_except_table10684
+ GCC_except_table10687
+ GCC_except_table10691
+ GCC_except_table10694
+ GCC_except_table10697
+ GCC_except_table10698
+ GCC_except_table10706
+ GCC_except_table10707
+ GCC_except_table10708
+ GCC_except_table10709
+ GCC_except_table10710
+ GCC_except_table10711
+ GCC_except_table10713
+ GCC_except_table10715
+ GCC_except_table10716
+ GCC_except_table10717
+ GCC_except_table10722
+ GCC_except_table10723
+ GCC_except_table10724
+ GCC_except_table10725
+ GCC_except_table10726
+ GCC_except_table10728
+ GCC_except_table10729
+ GCC_except_table10730
+ GCC_except_table10731
+ GCC_except_table10732
+ GCC_except_table10733
+ GCC_except_table10734
+ GCC_except_table10735
+ GCC_except_table10740
+ GCC_except_table10742
+ GCC_except_table10743
+ GCC_except_table10744
+ GCC_except_table10745
+ GCC_except_table10803
+ GCC_except_table10854
+ GCC_except_table10943
+ GCC_except_table10947
+ GCC_except_table1117
+ GCC_except_table11455
+ GCC_except_table11618
+ GCC_except_table11664
+ GCC_except_table11718
+ GCC_except_table11726
+ GCC_except_table11733
+ GCC_except_table11734
+ GCC_except_table11738
+ GCC_except_table1312
+ GCC_except_table1316
+ GCC_except_table1326
+ GCC_except_table1329
+ GCC_except_table1330
+ GCC_except_table1333
+ GCC_except_table1354
+ GCC_except_table1363
+ GCC_except_table1388
+ GCC_except_table1392
+ GCC_except_table1394
+ GCC_except_table1395
+ GCC_except_table1396
+ GCC_except_table1406
+ GCC_except_table1456
+ GCC_except_table1458
+ GCC_except_table1678
+ GCC_except_table1692
+ GCC_except_table1704
+ GCC_except_table1727
+ GCC_except_table173
+ GCC_except_table1739
+ GCC_except_table1744
+ GCC_except_table1834
+ GCC_except_table1837
+ GCC_except_table1846
+ GCC_except_table1871
+ GCC_except_table1963
+ GCC_except_table2091
+ GCC_except_table2092
+ GCC_except_table2093
+ GCC_except_table2094
+ GCC_except_table2095
+ GCC_except_table2097
+ GCC_except_table2122
+ GCC_except_table2175
+ GCC_except_table2285
+ GCC_except_table2286
+ GCC_except_table2762
+ GCC_except_table2842
+ GCC_except_table2988
+ GCC_except_table3000
+ GCC_except_table3163
+ GCC_except_table3310
+ GCC_except_table3397
+ GCC_except_table3398
+ GCC_except_table3401
+ GCC_except_table3402
+ GCC_except_table3406
+ GCC_except_table3407
+ GCC_except_table3410
+ GCC_except_table3413
+ GCC_except_table3418
+ GCC_except_table3422
+ GCC_except_table3423
+ GCC_except_table3424
+ GCC_except_table3425
+ GCC_except_table3426
+ GCC_except_table3427
+ GCC_except_table3428
+ GCC_except_table3436
+ GCC_except_table3441
+ GCC_except_table3442
+ GCC_except_table3447
+ GCC_except_table3476
+ GCC_except_table3479
+ GCC_except_table3482
+ GCC_except_table3487
+ GCC_except_table349
+ GCC_except_table3490
+ GCC_except_table3491
+ GCC_except_table3494
+ GCC_except_table3495
+ GCC_except_table3498
+ GCC_except_table3500
+ GCC_except_table3502
+ GCC_except_table3503
+ GCC_except_table3504
+ GCC_except_table3505
+ GCC_except_table3506
+ GCC_except_table3510
+ GCC_except_table3516
+ GCC_except_table359
+ GCC_except_table376
+ GCC_except_table4083
+ GCC_except_table4154
+ GCC_except_table4158
+ GCC_except_table4160
+ GCC_except_table421
+ GCC_except_table4300
+ GCC_except_table4310
+ GCC_except_table4311
+ GCC_except_table4318
+ GCC_except_table4323
+ GCC_except_table4328
+ GCC_except_table4351
+ GCC_except_table4358
+ GCC_except_table4363
+ GCC_except_table4365
+ GCC_except_table449
+ GCC_except_table4492
+ GCC_except_table4494
+ GCC_except_table4497
+ GCC_except_table4498
+ GCC_except_table4499
+ GCC_except_table4504
+ GCC_except_table4506
+ GCC_except_table4511
+ GCC_except_table4512
+ GCC_except_table4513
+ GCC_except_table4515
+ GCC_except_table4517
+ GCC_except_table4532
+ GCC_except_table455
+ GCC_except_table4559
+ GCC_except_table4595
+ GCC_except_table4596
+ GCC_except_table4599
+ GCC_except_table4600
+ GCC_except_table4605
+ GCC_except_table4606
+ GCC_except_table4609
+ GCC_except_table4610
+ GCC_except_table4611
+ GCC_except_table4612
+ GCC_except_table4613
+ GCC_except_table4614
+ GCC_except_table4615
+ GCC_except_table4617
+ GCC_except_table4623
+ GCC_except_table4627
+ GCC_except_table4631
+ GCC_except_table4632
+ GCC_except_table4633
+ GCC_except_table4635
+ GCC_except_table4642
+ GCC_except_table4644
+ GCC_except_table4645
+ GCC_except_table4720
+ GCC_except_table5039
+ GCC_except_table506
+ GCC_except_table5155
+ GCC_except_table5161
+ GCC_except_table5164
+ GCC_except_table5174
+ GCC_except_table5178
+ GCC_except_table5179
+ GCC_except_table5193
+ GCC_except_table5303
+ GCC_except_table5407
+ GCC_except_table5410
+ GCC_except_table5412
+ GCC_except_table5451
+ GCC_except_table5533
+ GCC_except_table5825
+ GCC_except_table593
+ GCC_except_table5955
+ GCC_except_table5991
+ GCC_except_table5993
+ GCC_except_table5995
+ GCC_except_table6000
+ GCC_except_table6009
+ GCC_except_table6010
+ GCC_except_table6014
+ GCC_except_table6050
+ GCC_except_table6071
+ GCC_except_table6092
+ GCC_except_table6118
+ GCC_except_table6119
+ GCC_except_table6125
+ GCC_except_table6127
+ GCC_except_table6128
+ GCC_except_table6160
+ GCC_except_table6162
+ GCC_except_table6165
+ GCC_except_table6171
+ GCC_except_table6173
+ GCC_except_table6176
+ GCC_except_table6179
+ GCC_except_table6180
+ GCC_except_table6181
+ GCC_except_table6182
+ GCC_except_table6183
+ GCC_except_table6188
+ GCC_except_table6189
+ GCC_except_table6195
+ GCC_except_table6196
+ GCC_except_table620
+ GCC_except_table6201
+ GCC_except_table6202
+ GCC_except_table6203
+ GCC_except_table6205
+ GCC_except_table6206
+ GCC_except_table6207
+ GCC_except_table6208
+ GCC_except_table6209
+ GCC_except_table6214
+ GCC_except_table6215
+ GCC_except_table6216
+ GCC_except_table6217
+ GCC_except_table6219
+ GCC_except_table6220
+ GCC_except_table6224
+ GCC_except_table6225
+ GCC_except_table6226
+ GCC_except_table6227
+ GCC_except_table6228
+ GCC_except_table6229
+ GCC_except_table6230
+ GCC_except_table6231
+ GCC_except_table6233
+ GCC_except_table6235
+ GCC_except_table6238
+ GCC_except_table6239
+ GCC_except_table6240
+ GCC_except_table6241
+ GCC_except_table6242
+ GCC_except_table6244
+ GCC_except_table6246
+ GCC_except_table6247
+ GCC_except_table6249
+ GCC_except_table6250
+ GCC_except_table6358
+ GCC_except_table6362
+ GCC_except_table6422
+ GCC_except_table644
+ GCC_except_table6454
+ GCC_except_table6455
+ GCC_except_table6493
+ GCC_except_table6499
+ GCC_except_table6507
+ GCC_except_table6532
+ GCC_except_table654
+ GCC_except_table6612
+ GCC_except_table6624
+ GCC_except_table6629
+ GCC_except_table6636
+ GCC_except_table6654
+ GCC_except_table6672
+ GCC_except_table6675
+ GCC_except_table6676
+ GCC_except_table6680
+ GCC_except_table6681
+ GCC_except_table6785
+ GCC_except_table6794
+ GCC_except_table6814
+ GCC_except_table6831
+ GCC_except_table6905
+ GCC_except_table6971
+ GCC_except_table6976
+ GCC_except_table6979
+ GCC_except_table7002
+ GCC_except_table7046
+ GCC_except_table7189
+ GCC_except_table7265
+ GCC_except_table7280
+ GCC_except_table7281
+ GCC_except_table7282
+ GCC_except_table7295
+ GCC_except_table7296
+ GCC_except_table7297
+ GCC_except_table7298
+ GCC_except_table7313
+ GCC_except_table7314
+ GCC_except_table7328
+ GCC_except_table7329
+ GCC_except_table7334
+ GCC_except_table7374
+ GCC_except_table7447
+ GCC_except_table7448
+ GCC_except_table7452
+ GCC_except_table7454
+ GCC_except_table7458
+ GCC_except_table7460
+ GCC_except_table7462
+ GCC_except_table7463
+ GCC_except_table7467
+ GCC_except_table7471
+ GCC_except_table7472
+ GCC_except_table7475
+ GCC_except_table7476
+ GCC_except_table7477
+ GCC_except_table7479
+ GCC_except_table7480
+ GCC_except_table7482
+ GCC_except_table7483
+ GCC_except_table7553
+ GCC_except_table7590
+ GCC_except_table7629
+ GCC_except_table7630
+ GCC_except_table7680
+ GCC_except_table8390
+ GCC_except_table8393
+ GCC_except_table8463
+ GCC_except_table8602
+ GCC_except_table8606
+ GCC_except_table8611
+ GCC_except_table8614
+ GCC_except_table8616
+ GCC_except_table8621
+ GCC_except_table8635
+ GCC_except_table8637
+ GCC_except_table8638
+ GCC_except_table8643
+ GCC_except_table8644
+ GCC_except_table8664
+ GCC_except_table8671
+ GCC_except_table8672
+ GCC_except_table8673
+ GCC_except_table8674
+ GCC_except_table8687
+ GCC_except_table8876
+ GCC_except_table8923
+ GCC_except_table9302
+ GCC_except_table9387
+ GCC_except_table9565
+ GCC_except_table9774
+ GCC_except_table9811
+ GCC_except_table9818
+ GCC_except_table9858
+ GCC_except_table9859
+ GCC_except_table9860
+ GCC_except_table9861
+ GCC_except_table9866
+ GCC_except_table9872
+ GCC_except_table9873
+ GCC_except_table9880
+ GCC_except_table9883
+ GCC_except_table9890
+ GCC_except_table9892
+ GCC_except_table9893
+ GCC_except_table9895
+ GCC_except_table9896
+ GCC_except_table9897
+ GCC_except_table9898
+ GCC_except_table9903
+ GCC_except_table9905
+ GCC_except_table9906
+ GCC_except_table9907
+ GCC_except_table9908
+ GCC_except_table9912
+ GCC_except_table9913
+ GCC_except_table9915
+ GCC_except_table9917
+ GCC_except_table9919
+ GCC_except_table9921
+ GCC_except_table9927
+ GCC_except_table9930
+ GCC_except_table9934
+ GCC_except_table9935
+ GCC_except_table9937
+ GCC_except_table9938
+ GCC_except_table9939
+ GCC_except_table9940
+ GCC_except_table9941
+ GCC_except_table9943
+ GCC_except_table9944
+ GCC_except_table9945
+ GCC_except_table9946
+ GCC_except_table9947
+ GCC_except_table9948
+ GCC_except_table9949
+ GCC_except_table9950
+ GCC_except_table9951
+ GCC_except_table9952
+ GCC_except_table9953
+ GCC_except_table9954
+ GCC_except_table9955
+ GCC_except_table9956
+ GCC_except_table9957
+ GCC_except_table9958
+ GCC_except_table9959
+ GCC_except_table9960
+ OBJC_IVAR_$_NUClosureExpression._evaluate
+ OBJC_IVAR_$_NUClosureExpression._name
+ OBJC_IVAR_$_NUClosureExpression._resultFormat
+ OBJC_IVAR_$_NUHistogramCalculator._ciContext
+ OBJC_IVAR_$_NUImageExportRequest._progress
+ OBJC_IVAR_$_NULivePhotoExportRequest._progress
+ OBJC_IVAR_$_NUVideoCompositor._maximumPendingVideoCompositionRequests
+ OBJC_IVAR_$_NUVideoExportRequest._maximumPendingVideoCompositionRequests
+ OBJC_IVAR_$_NUVideoExporterTrack._maximumPendingVideoCompositionRequests
+ OBJC_IVAR_$__NUOptionalSelectorPipeline._fallback
+ OBJC_IVAR_$__NUReducePipeline._resultChannel
+ OBJC_IVAR_$__NUReducePipeline._resultInputPort
+ OBJC_IVAR_$__NUReducePipeline._resultOutputPort
+ OBJC_IVAR_$__NUSwitchPipeline._singleMode
+ _CIRAWDecoderVersion6
+ _CIRAWDecoderVersion6DNG
+ _CIRAWDecoderVersion7
+ _CIRAWDecoderVersion7DNG
+ _CIRAWDecoderVersion8
+ _CIRAWDecoderVersion8DNG
+ _CIRAWDecoderVersion9
+ _CIRAWDecoderVersion9DNG
+ _NUAssetOptionUseOriginalExtent
+ _NUChannelNameCondition
+ _NUChannelNameFallback
+ _NUChannelNameInput
+ _NUChannelNameOutput
+ _NUChannelNameResult
+ _NUMediaAttachmentKeyPixelFormat
+ _OBJC_CLASS_$_NUClosureExpression
+ _OBJC_CLASS_$_NUUnknownChannelFormat
+ _OBJC_CLASS_$__NUOptionalSelectorPipeline
+ _OBJC_CLASS_$__NUUnwrapPipeline
+ _OBJC_METACLASS_$_NUClosureExpression
+ _OBJC_METACLASS_$_NUUnknownChannelFormat
+ _OBJC_METACLASS_$__NUOptionalSelectorPipeline
+ _OBJC_METACLASS_$__NUUnwrapPipeline
+ _OUTLINED_FUNCTION_25
+ _OUTLINED_FUNCTION_26
+ _OUTLINED_FUNCTION_27
+ _OUTLINED_FUNCTION_28
+ _OUTLINED_FUNCTION_29
+ _OUTLINED_FUNCTION_30
+ _OUTLINED_FUNCTION_31
+ _OUTLINED_FUNCTION_32
+ _OUTLINED_FUNCTION_33
+ _OUTLINED_FUNCTION_34
+ _OUTLINED_FUNCTION_35
+ _OUTLINED_FUNCTION_36
+ _OUTLINED_FUNCTION_37
+ _OUTLINED_FUNCTION_38
+ _OUTLINED_FUNCTION_39
+ _OUTLINED_FUNCTION_40
+ _OUTLINED_FUNCTION_41
+ _OUTLINED_FUNCTION_42
+ _OUTLINED_FUNCTION_43
+ _OUTLINED_FUNCTION_44
+ _OUTLINED_FUNCTION_45
+ _OUTLINED_FUNCTION_46
+ __OBJC_$_INSTANCE_METHODS_NSArray(NUDigest|NURenderPipelineFunction|NUControlDataRepresentable)
+ __OBJC_$_INSTANCE_METHODS_NUClosureExpression
+ __OBJC_$_INSTANCE_METHODS_NUUnknownChannelFormat
+ __OBJC_$_INSTANCE_METHODS__NUOptionalSelectorPipeline
+ __OBJC_$_INSTANCE_METHODS__NUUnwrapPipeline
+ __OBJC_$_INSTANCE_VARIABLES_NUClosureExpression
+ __OBJC_$_INSTANCE_VARIABLES__NUOptionalSelectorPipeline
+ __OBJC_$_PROP_LIST_AVVideoCompositingPrivate
+ __OBJC_$_PROP_LIST_NUClosureExpression
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_AVVideoCompositingPrivate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_AVVideoCompositingPrivate
+ __OBJC_$_PROTOCOL_REFS_AVVideoCompositingPrivate
+ __OBJC_CLASS_RO_$_NUClosureExpression
+ __OBJC_CLASS_RO_$_NUUnknownChannelFormat
+ __OBJC_CLASS_RO_$__NUOptionalSelectorPipeline
+ __OBJC_CLASS_RO_$__NUUnwrapPipeline
+ __OBJC_LABEL_PROTOCOL_$_AVVideoCompositingPrivate
+ __OBJC_METACLASS_RO_$_NUClosureExpression
+ __OBJC_METACLASS_RO_$_NUUnknownChannelFormat
+ __OBJC_METACLASS_RO_$__NUOptionalSelectorPipeline
+ __OBJC_METACLASS_RO_$__NUUnwrapPipeline
+ __OBJC_PROTOCOL_$_AVVideoCompositingPrivate
+ __ZL19NUCropClosestCenterPK15NUCropHalfPlaneDv2_dPS2_
+ ___34-[NUClosureExpression description]_block_invoke
+ ___34-[_NUPipeline unwrapInputs:block:]_block_invoke
+ ___40-[_NUPipeline unwrapInputs:block:error:]_block_invoke
+ ___41-[NUClosureExpression compactDescription]_block_invoke
+ ___44-[NUFactory _applicationWillBecomeInactive:]_block_invoke
+ ___45-[_NUPipeline insertMapAt:input:block:error:]_block_invoke
+ ___46+[NUAssetCapability rawDecodeCapabilityFormat]_block_invoke
+ ___46-[_NUPipeline insertMapAt:format:block:error:]_block_invoke
+ ___50-[_NUPipeline insertSwitchAt:on:with:block:error:]_block_invoke
+ ___51-[_NUPipeline switchOn:with:unwrappingPorts:block:]_block_invoke
+ ___62+[_NURawAssetPipeline rawDecodeVersionForAsset:options:error:]_block_invoke_2
+ ___62+[_NURawAssetPipeline rawDecodeVersionForAsset:options:error:]_block_invoke_3
+ ___62+[_NURawAssetPipeline rawDecodeVersionForAsset:options:error:]_block_invoke_4
+ ___62-[_NUPipeline insertReduceAt:input:initialResult:block:error:]_block_invoke
+ ___66-[_NUPipeline insertSwitchAt:on:with:unwrappingPorts:block:error:]_block_invoke
+ ___67-[_NUPipeline insertReduceAt:arrayFormat:resultFormat:block:error:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e64_"NSDictionary"32?0"<NUMutablePipeline>"8"NSDictionary"16^24l
+ ___block_descriptor_40_e8_32bs_e84_"NUChannelPortRef"40?0"<NUMutablePipeline>"8"NUChannelPortRef"16"NSArray"24^32l
+ ___block_descriptor_48_e8_32s40bs_e82_"<NUChannelOutputPort>"32?0"<NUMutablePipeline>"8"<NUChannelOutputPort>"16^24l
+ ___block_descriptor_56_e8_32s40s48s_e26_v32?0"NUChannel"8Q16^B24l
+ ___block_descriptor_64_e8_32s40s48s56bs_e33_B24?0"<NUMutablePipeline>"8^16l
+ ___block_descriptor_64_e8_32s40s48s56s_e36_v32?0"NSString"8"<NUMedia>"16^B24l
+ ___copy_helper_block_e8_32s40s48s56b
+ _kCIFormat420f
+ _kCIFormat420v
+ _objc_msgSend$YCC8f420
+ _objc_msgSend$YCC8v420
+ _objc_msgSend$_addOptionalInputChannel:
+ _objc_msgSend$_addOptionalSelectorWithInput:fallback:error:
+ _objc_msgSend$_evictVisionSessionIfUsed
+ _objc_msgSend$addCapability:data:
+ _objc_msgSend$addElementOutputFormat:
+ _objc_msgSend$ciContext
+ _objc_msgSend$customVideoCompositor
+ _objc_msgSend$genericFormat
+ _objc_msgSend$genericMetadataFormat
+ _objc_msgSend$ifNotNil:else:error:
+ _objc_msgSend$initWithArrayFormat:
+ _objc_msgSend$initWithArrayFormat:resultFormat:
+ _objc_msgSend$initWithBrushMask:mask:strokeScale:ciContext:
+ _objc_msgSend$initWithChannelFormat:includeFallback:
+ _objc_msgSend$initWithSingleChannelMode:
+ _objc_msgSend$insertMap:at:block:error:
+ _objc_msgSend$insertMapAt:format:block:error:
+ _objc_msgSend$insertMapAt:input:block:error:
+ _objc_msgSend$insertMapWithFormat:at:block:error:
+ _objc_msgSend$insertReduce:with:at:block:error:
+ _objc_msgSend$insertReduceAt:arrayFormat:resultFormat:block:error:
+ _objc_msgSend$insertReduceAt:input:initialResult:block:error:
+ _objc_msgSend$insertReduceWithArrayFormat:resultFormat:at:block:error:
+ _objc_msgSend$insertSwitchAt:format:unwrappingChannels:block:error:
+ _objc_msgSend$insertSwitchAt:on:with:block:error:
+ _objc_msgSend$insertSwitchAt:on:with:unwrappingChannels:block:error:
+ _objc_msgSend$insertSwitchAt:on:with:unwrappingPorts:block:error:
+ _objc_msgSend$insertUnwrapAt:withBlock:error:
+ _objc_msgSend$integer:
+ _objc_msgSend$isUnknown
+ _objc_msgSend$maximumPendingVideoCompositionRequests
+ _objc_msgSend$nu_cardinality
+ _objc_msgSend$nu_subdataAtIndex:format:error:
+ _objc_msgSend$nu_subdataForKey:format:error:
+ _objc_msgSend$optionalFormat
+ _objc_msgSend$rawDecodeCapabilityFormat
+ _objc_msgSend$resultInputPort
+ _objc_msgSend$resultOutputPort
+ _objc_msgSend$setCiContext:
+ _objc_msgSend$setMaximumPendingVideoCompositionRequests:
+ _objc_msgSend$setSourceOptions:
+ _objc_msgSend$switchOn:with:unwrappingPorts:block:error:
+ _objc_msgSend$unwrapInputs:block:error:
+ _objc_msgSend$unwrapOptional:error:
+ _symbolic ______pSDy_____So16NUChannelPortRefCGAE______pIgggozo_ So17NUMutablePipelineP So13NUChannelNamea s5ErrorP
+ _symbolic ______pSDy_____So16NUChannelPortRefCGSAySo7NSErrorCSgGSgAESgIgggyo_ So17NUMutablePipelineP So13NUChannelNamea
+ _symbolic ______pSo16NUChannelPortRefCA2C______pIggggozo_ So17NUMutablePipelineP s5ErrorP
+ _symbolic ______pSo16NUChannelPortRefCACSAySo7NSErrorCSgGSgACSgIggggyo_ So17NUMutablePipelineP
+ _symbolic ______pSo16NUChannelPortRefCSayACGAC______pIggggozo_ So17NUMutablePipelineP s5ErrorP
+ _symbolic ______pSo16NUChannelPortRefCSayACGSAySo7NSErrorCSgGSgACSgIggggyo_ So17NUMutablePipelineP
+ rawDecodeCapabilityFormat.format
+ rawDecodeCapabilityFormat.onceToken
- +[NUAssetCapability rawDecode_v6]
- +[NUAssetCapability rawDecode_v7]
- +[NUAssetCapability rawDecode_v8]
- +[NUAssetCapability rawDecode_v9]
- +[NUChannelFormat null]
- -[NSObject(NUControlDataRepresentable) nu_valueForKey:format:error:]
- -[NUChannelFormat isNull]
- -[NUChannelNullData initWithFormat:]
- -[NUChannelNullFormat canAcceptDataWithFormat:]
- -[NUChannelNullFormat channelType]
- -[NUChannelNullFormat hash]
- -[NUChannelNullFormat isComparableToChannelFormat:]
- -[NUChannelNullFormat isEqualToChannelFormat:]
- -[NUChannelNullFormat isNull]
- -[NUVideoExportRequest setProgress:]
- -[_NUMapPipeline addElementOutputChannel:]
- -[_NUMapPipeline initWithArrayChannel:]
- -[_NUReducePipeline accumulatorInputPort]
- -[_NUReducePipeline accumulatorOutputPort]
- -[_NUReducePipeline initWithArrayChannel:accumulatorChannel:]
- GCC_except_table10037
- GCC_except_table10061
- GCC_except_table10062
- GCC_except_table10066
- GCC_except_table10067
- GCC_except_table10068
- GCC_except_table10069
- GCC_except_table10076
- GCC_except_table10077
- GCC_except_table10086
- GCC_except_table10096
- GCC_except_table10103
- GCC_except_table10104
- GCC_except_table10106
- GCC_except_table10108
- GCC_except_table10111
- GCC_except_table10112
- GCC_except_table10113
- GCC_except_table10185
- GCC_except_table10195
- GCC_except_table10410
- GCC_except_table10411
- GCC_except_table10417
- GCC_except_table10418
- GCC_except_table10420
- GCC_except_table10421
- GCC_except_table10518
- GCC_except_table10519
- GCC_except_table10522
- GCC_except_table10525
- GCC_except_table10526
- GCC_except_table10527
- GCC_except_table10529
- GCC_except_table10532
- GCC_except_table10535
- GCC_except_table10536
- GCC_except_table10537
- GCC_except_table10539
- GCC_except_table10540
- GCC_except_table10550
- GCC_except_table10551
- GCC_except_table10556
- GCC_except_table10557
- GCC_except_table10558
- GCC_except_table10559
- GCC_except_table10561
- GCC_except_table10562
- GCC_except_table10563
- GCC_except_table10564
- GCC_except_table10566
- GCC_except_table10567
- GCC_except_table10568
- GCC_except_table10569
- GCC_except_table10570
- GCC_except_table10571
- GCC_except_table10574
- GCC_except_table10577
- GCC_except_table10578
- GCC_except_table10581
- GCC_except_table10584
- GCC_except_table10585
- GCC_except_table10593
- GCC_except_table10594
- GCC_except_table10595
- GCC_except_table10596
- GCC_except_table10597
- GCC_except_table10598
- GCC_except_table10600
- GCC_except_table10602
- GCC_except_table10603
- GCC_except_table10604
- GCC_except_table10609
- GCC_except_table10610
- GCC_except_table10611
- GCC_except_table10612
- GCC_except_table10613
- GCC_except_table10615
- GCC_except_table10616
- GCC_except_table10617
- GCC_except_table10618
- GCC_except_table10619
- GCC_except_table10620
- GCC_except_table10621
- GCC_except_table10622
- GCC_except_table10627
- GCC_except_table10628
- GCC_except_table10629
- GCC_except_table10630
- GCC_except_table10830
- GCC_except_table10834
- GCC_except_table1112
- GCC_except_table11337
- GCC_except_table11498
- GCC_except_table11500
- GCC_except_table11546
- GCC_except_table11600
- GCC_except_table11608
- GCC_except_table11615
- GCC_except_table11620
- GCC_except_table1307
- GCC_except_table1311
- GCC_except_table1319
- GCC_except_table1320
- GCC_except_table1321
- GCC_except_table1328
- GCC_except_table1349
- GCC_except_table1358
- GCC_except_table1383
- GCC_except_table1387
- GCC_except_table1389
- GCC_except_table1390
- GCC_except_table1391
- GCC_except_table1401
- GCC_except_table1449
- GCC_except_table1451
- GCC_except_table1670
- GCC_except_table1684
- GCC_except_table1696
- GCC_except_table170
- GCC_except_table1719
- GCC_except_table1731
- GCC_except_table1736
- GCC_except_table1826
- GCC_except_table1829
- GCC_except_table1838
- GCC_except_table1863
- GCC_except_table1955
- GCC_except_table2081
- GCC_except_table2082
- GCC_except_table2083
- GCC_except_table2084
- GCC_except_table2085
- GCC_except_table2087
- GCC_except_table2112
- GCC_except_table2165
- GCC_except_table2275
- GCC_except_table2276
- GCC_except_table2817
- GCC_except_table2885
- GCC_except_table2935
- GCC_except_table2947
- GCC_except_table3130
- GCC_except_table3277
- GCC_except_table3357
- GCC_except_table3364
- GCC_except_table3365
- GCC_except_table3368
- GCC_except_table3369
- GCC_except_table3370
- GCC_except_table3373
- GCC_except_table3374
- GCC_except_table3377
- GCC_except_table3380
- GCC_except_table3381
- GCC_except_table3385
- GCC_except_table3388
- GCC_except_table3389
- GCC_except_table3391
- GCC_except_table3392
- GCC_except_table3393
- GCC_except_table3394
- GCC_except_table3395
- GCC_except_table3408
- GCC_except_table3409
- GCC_except_table3437
- GCC_except_table3438
- GCC_except_table3443
- GCC_except_table3444
- GCC_except_table3446
- GCC_except_table3449
- GCC_except_table3450
- GCC_except_table3457
- GCC_except_table3458
- GCC_except_table346
- GCC_except_table3461
- GCC_except_table3462
- GCC_except_table3465
- GCC_except_table3467
- GCC_except_table3469
- GCC_except_table3472
- GCC_except_table3473
- GCC_except_table356
- GCC_except_table373
- GCC_except_table4017
- GCC_except_table4088
- GCC_except_table4092
- GCC_except_table4094
- GCC_except_table418
- GCC_except_table4231
- GCC_except_table4241
- GCC_except_table4242
- GCC_except_table4249
- GCC_except_table4257
- GCC_except_table4262
- GCC_except_table4285
- GCC_except_table4292
- GCC_except_table4297
- GCC_except_table4299
- GCC_except_table4426
- GCC_except_table4427
- GCC_except_table4428
- GCC_except_table4431
- GCC_except_table4432
- GCC_except_table4433
- GCC_except_table4438
- GCC_except_table4440
- GCC_except_table4445
- GCC_except_table4446
- GCC_except_table4447
- GCC_except_table4449
- GCC_except_table4451
- GCC_except_table446
- GCC_except_table4466
- GCC_except_table4468
- GCC_except_table452
- GCC_except_table4529
- GCC_except_table4530
- GCC_except_table4533
- GCC_except_table4539
- GCC_except_table4540
- GCC_except_table4543
- GCC_except_table4544
- GCC_except_table4545
- GCC_except_table4546
- GCC_except_table4547
- GCC_except_table4548
- GCC_except_table4549
- GCC_except_table4551
- GCC_except_table4557
- GCC_except_table4561
- GCC_except_table4565
- GCC_except_table4566
- GCC_except_table4567
- GCC_except_table4569
- GCC_except_table4576
- GCC_except_table4578
- GCC_except_table4579
- GCC_except_table4654
- GCC_except_table4971
- GCC_except_table503
- GCC_except_table5086
- GCC_except_table5092
- GCC_except_table5095
- GCC_except_table5105
- GCC_except_table5109
- GCC_except_table5110
- GCC_except_table5124
- GCC_except_table5234
- GCC_except_table5340
- GCC_except_table5342
- GCC_except_table5344
- GCC_except_table5383
- GCC_except_table5465
- GCC_except_table5757
- GCC_except_table5860
- GCC_except_table5885
- GCC_except_table590
- GCC_except_table5921
- GCC_except_table5923
- GCC_except_table5925
- GCC_except_table5939
- GCC_except_table5940
- GCC_except_table5944
- GCC_except_table5980
- GCC_except_table5999
- GCC_except_table6020
- GCC_except_table6025
- GCC_except_table6044
- GCC_except_table6046
- GCC_except_table6047
- GCC_except_table6052
- GCC_except_table6053
- GCC_except_table6055
- GCC_except_table6056
- GCC_except_table6070
- GCC_except_table6083
- GCC_except_table6086
- GCC_except_table6087
- GCC_except_table6088
- GCC_except_table6090
- GCC_except_table6093
- GCC_except_table6094
- GCC_except_table6095
- GCC_except_table6096
- GCC_except_table6099
- GCC_except_table6100
- GCC_except_table6101
- GCC_except_table6102
- GCC_except_table6103
- GCC_except_table6104
- GCC_except_table6105
- GCC_except_table6106
- GCC_except_table6107
- GCC_except_table6108
- GCC_except_table6109
- GCC_except_table6110
- GCC_except_table6111
- GCC_except_table6117
- GCC_except_table6123
- GCC_except_table6129
- GCC_except_table6130
- GCC_except_table6131
- GCC_except_table6133
- GCC_except_table6134
- GCC_except_table6135
- GCC_except_table6136
- GCC_except_table6137
- GCC_except_table6143
- GCC_except_table6144
- GCC_except_table6145
- GCC_except_table6147
- GCC_except_table6148
- GCC_except_table6152
- GCC_except_table6153
- GCC_except_table6154
- GCC_except_table6156
- GCC_except_table6157
- GCC_except_table6161
- GCC_except_table6163
- GCC_except_table617
- GCC_except_table6170
- GCC_except_table6286
- GCC_except_table6290
- GCC_except_table6350
- GCC_except_table6382
- GCC_except_table6383
- GCC_except_table641
- GCC_except_table6421
- GCC_except_table6427
- GCC_except_table6435
- GCC_except_table6460
- GCC_except_table651
- GCC_except_table6540
- GCC_except_table6552
- GCC_except_table6557
- GCC_except_table6564
- GCC_except_table6582
- GCC_except_table6600
- GCC_except_table6603
- GCC_except_table6604
- GCC_except_table6608
- GCC_except_table6609
- GCC_except_table6713
- GCC_except_table6722
- GCC_except_table6742
- GCC_except_table6759
- GCC_except_table6833
- GCC_except_table6899
- GCC_except_table6904
- GCC_except_table6907
- GCC_except_table6930
- GCC_except_table6974
- GCC_except_table7117
- GCC_except_table7193
- GCC_except_table7208
- GCC_except_table7209
- GCC_except_table7210
- GCC_except_table7223
- GCC_except_table7224
- GCC_except_table7225
- GCC_except_table7226
- GCC_except_table7241
- GCC_except_table7242
- GCC_except_table7256
- GCC_except_table7257
- GCC_except_table7262
- GCC_except_table7302
- GCC_except_table7375
- GCC_except_table7376
- GCC_except_table7380
- GCC_except_table7382
- GCC_except_table7386
- GCC_except_table7388
- GCC_except_table7390
- GCC_except_table7391
- GCC_except_table7395
- GCC_except_table7399
- GCC_except_table7400
- GCC_except_table7403
- GCC_except_table7404
- GCC_except_table7405
- GCC_except_table7407
- GCC_except_table7408
- GCC_except_table7410
- GCC_except_table7411
- GCC_except_table7481
- GCC_except_table7518
- GCC_except_table7557
- GCC_except_table7558
- GCC_except_table7608
- GCC_except_table8301
- GCC_except_table8304
- GCC_except_table8374
- GCC_except_table8513
- GCC_except_table8517
- GCC_except_table8522
- GCC_except_table8525
- GCC_except_table8527
- GCC_except_table8532
- GCC_except_table8546
- GCC_except_table8548
- GCC_except_table8549
- GCC_except_table8554
- GCC_except_table8555
- GCC_except_table8575
- GCC_except_table8582
- GCC_except_table8583
- GCC_except_table8584
- GCC_except_table8585
- GCC_except_table8598
- GCC_except_table8787
- GCC_except_table8834
- GCC_except_table9189
- GCC_except_table9274
- GCC_except_table9452
- GCC_except_table9646
- GCC_except_table9661
- GCC_except_table9698
- GCC_except_table9705
- GCC_except_table9745
- GCC_except_table9746
- GCC_except_table9747
- GCC_except_table9748
- GCC_except_table9753
- GCC_except_table9760
- GCC_except_table9767
- GCC_except_table9770
- GCC_except_table9777
- GCC_except_table9779
- GCC_except_table9780
- GCC_except_table9782
- GCC_except_table9783
- GCC_except_table9784
- GCC_except_table9785
- GCC_except_table9790
- GCC_except_table9792
- GCC_except_table9793
- GCC_except_table9794
- GCC_except_table9795
- GCC_except_table9799
- GCC_except_table9800
- GCC_except_table9802
- GCC_except_table9804
- GCC_except_table9806
- GCC_except_table9808
- GCC_except_table9814
- GCC_except_table9817
- GCC_except_table9821
- GCC_except_table9822
- GCC_except_table9824
- GCC_except_table9825
- GCC_except_table9826
- GCC_except_table9827
- GCC_except_table9828
- GCC_except_table9830
- GCC_except_table9831
- GCC_except_table9832
- GCC_except_table9833
- GCC_except_table9834
- GCC_except_table9835
- GCC_except_table9836
- GCC_except_table9837
- GCC_except_table9838
- GCC_except_table9839
- GCC_except_table9840
- GCC_except_table9841
- GCC_except_table9842
- GCC_except_table9843
- GCC_except_table9844
- GCC_except_table9845
- GCC_except_table9846
- GCC_except_table9847
- GCC_except_table9904
- GCC_except_table9911
- GCC_except_table9989
- OBJC_IVAR_$__NUReducePipeline._accumulatorChannel
- OBJC_IVAR_$__NUReducePipeline._accumulatorInputPort
- OBJC_IVAR_$__NUReducePipeline._accumulatorOutputPort
- _OBJC_CLASS_$_NUChannelNullFormat
- _OBJC_METACLASS_$_NUChannelNullFormat
- __OBJC_$_CLASS_METHODS_NUChannelFormat
- __OBJC_$_CLASS_PROP_LIST_NUChannelFormat
- __OBJC_$_INSTANCE_METHODS_NSArray(NUDigest|NURenderPipelineFunction)
- __OBJC_$_INSTANCE_METHODS_NUChannelNullFormat
- __OBJC_CLASS_RO_$_NUChannelNullFormat
- __OBJC_METACLASS_RO_$_NUChannelNullFormat
- ___44-[_NUPipeline reduce:withInput:block:error:]_block_invoke
- ___block_descriptor_40_e18_B16?0"NSString"8l
- ___block_descriptor_56_e8_32s40s48s_e36_v32?0"NSString"8"<NUMedia>"16^B24l
- _objc_msgSend$accumulatorInputPort
- _objc_msgSend$accumulatorOutputPort
- _objc_msgSend$addElementOutputChannel:
- _objc_msgSend$initWithArrayChannel:
- _objc_msgSend$initWithArrayChannel:accumulatorChannel:
- _objc_msgSend$nu_valueForKey:format:error:
- _objc_msgSend$rawDecode_v6
- _objc_msgSend$rawDecode_v7
- _objc_msgSend$rawDecode_v8
- _objc_msgSend$rawDecode_v9
CStrings:
+ "$some"
+ "+[NUChannelData nullDataWithOptionalFormat:]"
+ "-[NUClosureExpression initWithName:format:arguments:evaluate:]"
+ "-[NUUnknownChannelFormat canSpecializeFormat:]"
+ "-[NUUnknownChannelFormat specializedWithFormat:]"
+ "-[_NUMapPipeline addElementOutputFormat:]"
+ "-[_NUMapPipeline initWithArrayFormat:]"
+ "-[_NUOptionalSelectorPipeline initWithChannelFormat:includeFallback:]"
+ "-[_NUOptionalSelectorPipeline initWithName:opaque:]"
+ "-[_NUPipeline ifNotNil:else:]"
+ "-[_NUPipeline ifNotNil:else:error:]"
+ "-[_NUPipeline insertMap:at:block:error:]"
+ "-[_NUPipeline insertMapAt:input:block:error:]"
+ "-[_NUPipeline insertMapWithFormat:at:block:error:]"
+ "-[_NUPipeline insertReduce:with:at:block:error:]"
+ "-[_NUPipeline insertReduceWithArrayFormat:resultFormat:at:block:error:]"
+ "-[_NUPipeline insertSwitchAt:format:unwrappingChannels:block:error:]"
+ "-[_NUPipeline insertSwitchAt:on:with:block:error:]"
+ "-[_NUPipeline insertSwitchAt:on:with:unwrappingChannels:block:error:]"
+ "-[_NUPipeline insertSwitchAt:on:with:unwrappingPorts:block:error:]"
+ "-[_NUPipeline insertUnwrapAt:withBlock:error:]"
+ "-[_NUPipeline switchOn:with:unwrappingPorts:block:]"
+ "-[_NUPipeline unwrapInputs:block:]"
+ "-[_NUPipeline unwrapInputs:block:error:]"
+ "-[_NUPipeline unwrapOptional:]"
+ "-[_NUPipeline unwrapOptional:error:]"
+ "-[_NUReducePipeline initWithArrayFormat:resultFormat:]"
+ "-[_NUSwitchPipeline _addOptionalInputChannel:]"
+ "-[_NUSwitchPipeline _evaluateOutputPort:context:error:]"
+ "-[_NUUnwrapPipeline _evaluateOutputPort:context:error:]"
+ "-[_NUUnwrapPipeline initWithName:opaque:]"
+ "8"
+ "@\"NSDictionary\"32@?0@\"<NUMutablePipeline>\"8@\"NSDictionary\"16^@24"
+ "@\"NUChannelPortRef\"40@?0@\"<NUMutablePipeline>\"8@\"NUChannelPortRef\"16@\"NSArray\"24^@32"
+ "Cannot add an element input channel"
+ "Cannot add an element output channel"
+ "Cannot unwrap a channel named after the switch's own"
+ "Crop rect should be known at evaluation time"
+ "Failed to add ifNotNil/else pipeline: %@"
+ "Failed to add switch input"
+ "Failed to add switch output"
+ "Failed to add switch unwrapped input"
+ "Failed to add unwrap input"
+ "Failed to add unwrap pipeline: %@"
+ "Failed to add unwrapOptional pipeline: %@"
+ "Failed to build unwrap pipeline"
+ "Failed to connect optional selector pipeline"
+ "Failed to connect unwrap input"
+ "Failed to evaluate fallback input"
+ "Failed to evaluate optional input"
+ "Failed to insert map pipeline"
+ "Failed to insert reduce pipeline"
+ "Failed to insert switch pipeline"
+ "Failed to insert unwrap pipeline"
+ "Failed to resolve port to unwrap"
+ "Failed to resolve unwrap input"
+ "Failed to unwrap optional input"
+ "Fallback input is null"
+ "Missing switch input port"
+ "Missing unwrap input port"
+ "Missing unwrapped input port"
+ "NUHistogramCalculator"
+ "Not an array format"
+ "Output channel cannot be optional"
+ "Unexpected custom compositor %{public}@, leaving the composition request depth alone"
+ "Unwrap has no input to unwrap"
+ "Unwrap input is not optional"
+ "Value is not a collection"
+ "YCC8f420"
+ "YCC8v420"
+ "[channel.name isEqualToString:NUChannelNameOutput]"
+ "arrayFormat != nil"
+ "arrayFormat.isArray"
+ "arrayFormat.isOptional == NO"
+ "closure"
+ "closure<%@,%@>"
+ "elementFormat != nil"
+ "evaluate != nil"
+ "fallback"
+ "fallback != nil"
+ "format.isOptional"
+ "optionalInput != nil"
+ "optionalInputs != nil"
+ "optionalSelector"
+ "ports != nil"
+ "result"
+ "resultFormat != nil"
+ "s!"
+ "s?"
+ "u"
+ "unwrap"
+ "unwrapped%lu"
+ "v32@?0@\"NUChannel\"8Q16^B24"
- "-[NUChannelNullData initWithFormat:]"
- "-[_NUMapPipeline addElementOutputChannel:]"
- "-[_NUMapPipeline initWithArrayChannel:]"
- "-[_NUPipeline map:block:error:]"
- "-[_NUPipeline reduce:with:block:error:]"
- "-[_NUReducePipeline initWithArrayChannel:accumulatorChannel:]"
- "Duplicate input name"
- "Duplicate input name: %@"
- "Failed to reduce"
- "Unsupported RAW decoder version: %{public}@, ignored."
- "accumulatorChannel != nil"
- "arrayChannel != nil"
- "arrayChannel.format.isArray"
- "elementChannel != nil"
- "rawDecode_v6"
- "rawDecode_v7"
- "rawDecode_v8"
- "rawDecode_v9"
```
