## HomeKitMatter

> `/System/Library/PrivateFrameworks/HomeKitMatter.framework/Versions/A/HomeKitMatter`

```diff

-1516.0.0.0.0
-  __TEXT.__text: 0x18dec4
-  __TEXT.__objc_methlist: 0xacec
-  __TEXT.__const: 0x290
+1520.2.3.0.2
+  __TEXT.__text: 0x18f37c
+  __TEXT.__objc_methlist: 0xadfc
+  __TEXT.__const: 0x2b0
   __TEXT.__dlopen_cstrs: 0x58
-  __TEXT.__gcc_except_tab: 0x30e4
-  __TEXT.__cstring: 0x6c64
-  __TEXT.__oslogstring: 0x4c512
+  __TEXT.__gcc_except_tab: 0x30ec
+  __TEXT.__cstring: 0x6c80
+  __TEXT.__oslogstring: 0x4c73c
   __TEXT.__ustring: 0x68
-  __TEXT.__unwind_info: 0x3d28
+  __TEXT.__unwind_info: 0x3d70
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0xbc0
-  __DATA_CONST.__objc_classlist: 0x458
+  __DATA_CONST.__objc_classlist: 0x460
   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6f18
+  __DATA_CONST.__objc_selrefs: 0x6f80
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x310
+  __DATA_CONST.__objc_superrefs: 0x318
   __DATA_CONST.__objc_arraydata: 0x240
-  __DATA_CONST.__got: 0x970
-  __AUTH_CONST.__const: 0x5720
-  __AUTH_CONST.__cfstring: 0x6c40
-  __AUTH_CONST.__objc_const: 0x103c0
+  __DATA_CONST.__got: 0x980
+  __AUTH_CONST.__const: 0x5710
+  __AUTH_CONST.__cfstring: 0x6d60
+  __AUTH_CONST.__objc_const: 0x106d0
   __AUTH_CONST.__objc_intobj: 0x16b0
   __AUTH_CONST.__objc_arrayobj: 0x168
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x1e50
-  __DATA.__objc_ivar: 0xb84
+  __AUTH.__objc_data: 0x1ea0
+  __DATA.__objc_ivar: 0xbb8
   __DATA.__data: 0xea0
-  __DATA.__bss: 0x498
+  __DATA.__bss: 0x4a8
   __DATA_DIRTY.__objc_data: 0xd20
   __DATA_DIRTY.__bss: 0xa0
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth

   - /System/Library/PrivateFrameworks/UARPKit.framework/Versions/A/UARPKit
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 4540
-  Symbols:   10396
-  CStrings:  5582
+  Functions: 4569
+  Symbols:   10459
+  CStrings:  5596
 
Symbols:
+ +[HMMTRAsyncMutex logCategory]
+ -[HMMTRAccessoryServerBrowser _makeAccessoryServerFactory]
+ -[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]
+ -[HMMTRAccessoryServerBrowser discoveredAccessoryServersAsyncMutex]
+ -[HMMTRAccessoryServerBrowser updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]
+ -[HMMTRAccessoryServerBrowser workQueueFactory]
+ -[HMMTRAccessoryServerFactory workQueueFactory]
+ -[HMMTRAsyncMutex .cxx_destruct]
+ -[HMMTRAsyncMutex initWithQueue:]
+ -[HMMTRAsyncMutex lockWithCompletion:]
+ -[HMMTRAsyncMutex locked]
+ -[HMMTRAsyncMutex pendingCompletions]
+ -[HMMTRAsyncMutex queue]
+ -[HMMTRAsyncMutex setLocked:]
+ -[HMMTRAsyncMutex unlock]
+ -[HMMTRControllerFactory workQueueFactory]
+ -[HMMTRControllerFactoryStorage initWithWorkQueueFactory:]
+ -[HMMTRControllerFactoryStorage workQueueFactory]
+ -[HMMTRDescriptorClusterManager workQueueFactory]
+ -[HMMTRExclusiveServerActionQueue workQueueFactory]
+ -[HMMTRFirmwareUpdateStatus workQueueFactory]
+ -[HMMTRSystemCommissionerControllerParams workQueueFactory]
+ -[HMMTRThreadRadioManager workQueueFactory]
+ GCC_except_table1003
+ GCC_except_table1007
+ GCC_except_table1009
+ GCC_except_table1011
+ GCC_except_table1013
+ GCC_except_table1017
+ GCC_except_table1081
+ GCC_except_table1087
+ GCC_except_table1089
+ GCC_except_table1211
+ GCC_except_table1279
+ GCC_except_table1325
+ GCC_except_table1333
+ GCC_except_table1386
+ GCC_except_table1394
+ GCC_except_table1431
+ GCC_except_table1469
+ GCC_except_table1496
+ GCC_except_table1695
+ GCC_except_table1738
+ GCC_except_table1892
+ GCC_except_table1893
+ GCC_except_table1894
+ GCC_except_table1897
+ GCC_except_table1917
+ GCC_except_table1918
+ GCC_except_table1919
+ GCC_except_table1920
+ GCC_except_table1921
+ GCC_except_table1924
+ GCC_except_table1927
+ GCC_except_table1928
+ GCC_except_table1929
+ GCC_except_table1930
+ GCC_except_table1931
+ GCC_except_table1932
+ GCC_except_table1933
+ GCC_except_table1992
+ GCC_except_table1998
+ GCC_except_table2086
+ GCC_except_table2204
+ GCC_except_table2206
+ GCC_except_table2237
+ GCC_except_table2248
+ GCC_except_table2250
+ GCC_except_table2306
+ GCC_except_table2352
+ GCC_except_table2377
+ GCC_except_table2449
+ GCC_except_table2738
+ GCC_except_table2740
+ GCC_except_table2742
+ GCC_except_table2746
+ GCC_except_table2807
+ GCC_except_table2840
+ GCC_except_table2887
+ GCC_except_table2889
+ GCC_except_table2944
+ GCC_except_table2945
+ GCC_except_table2946
+ GCC_except_table2947
+ GCC_except_table2948
+ GCC_except_table2950
+ GCC_except_table2951
+ GCC_except_table2961
+ GCC_except_table2963
+ GCC_except_table2975
+ GCC_except_table2996
+ GCC_except_table3011
+ GCC_except_table3017
+ GCC_except_table3032
+ GCC_except_table3039
+ GCC_except_table3054
+ GCC_except_table3057
+ GCC_except_table3061
+ GCC_except_table3063
+ GCC_except_table3093
+ GCC_except_table3102
+ GCC_except_table3107
+ GCC_except_table3119
+ GCC_except_table3173
+ GCC_except_table3174
+ GCC_except_table3564
+ GCC_except_table3590
+ GCC_except_table3591
+ GCC_except_table3596
+ GCC_except_table3602
+ GCC_except_table3605
+ GCC_except_table3621
+ GCC_except_table3636
+ GCC_except_table3705
+ GCC_except_table3706
+ GCC_except_table3739
+ GCC_except_table3748
+ GCC_except_table3752
+ GCC_except_table3786
+ GCC_except_table3790
+ GCC_except_table3798
+ GCC_except_table3820
+ GCC_except_table3824
+ GCC_except_table3867
+ GCC_except_table3869
+ GCC_except_table3871
+ GCC_except_table3890
+ GCC_except_table3892
+ GCC_except_table3913
+ GCC_except_table3990
+ GCC_except_table4037
+ GCC_except_table4057
+ GCC_except_table4080
+ GCC_except_table4084
+ GCC_except_table4099
+ GCC_except_table4100
+ GCC_except_table4101
+ GCC_except_table4107
+ GCC_except_table4114
+ GCC_except_table4119
+ GCC_except_table4156
+ GCC_except_table4178
+ GCC_except_table4220
+ GCC_except_table4226
+ GCC_except_table4229
+ GCC_except_table4315
+ GCC_except_table4316
+ GCC_except_table4374
+ GCC_except_table4377
+ GCC_except_table4441
+ GCC_except_table4501
+ GCC_except_table4505
+ GCC_except_table4511
+ GCC_except_table4515
+ GCC_except_table4549
+ GCC_except_table594
+ GCC_except_table600
+ GCC_except_table602
+ GCC_except_table606
+ GCC_except_table776
+ GCC_except_table777
+ GCC_except_table834
+ GCC_except_table835
+ GCC_except_table836
+ GCC_except_table909
+ GCC_except_table951
+ OBJC_IVAR_$_HMMTRAccessoryServerBrowser._discoveredAccessoryServersAsyncMutex
+ OBJC_IVAR_$_HMMTRAccessoryServerBrowser._workQueueFactory
+ OBJC_IVAR_$_HMMTRAccessoryServerFactory._workQueueFactory
+ OBJC_IVAR_$_HMMTRAsyncMutex._locked
+ OBJC_IVAR_$_HMMTRAsyncMutex._pendingCompletions
+ OBJC_IVAR_$_HMMTRAsyncMutex._queue
+ OBJC_IVAR_$_HMMTRControllerFactory._workQueueFactory
+ OBJC_IVAR_$_HMMTRControllerFactoryStorage._workQueueFactory
+ OBJC_IVAR_$_HMMTRDescriptorClusterManager._workQueueFactory
+ OBJC_IVAR_$_HMMTRExclusiveServerActionQueue._workQueueFactory
+ OBJC_IVAR_$_HMMTRFirmwareUpdateStatus._workQueueFactory
+ OBJC_IVAR_$_HMMTRSystemCommissionerControllerParams._workQueueFactory
+ OBJC_IVAR_$_HMMTRThreadRadioManager._workQueueFactory
+ _HAPWorkQueueFactoryOrDefault
+ _HMErrorDomain
+ _HMMTRIsSecondPartyProduct
+ _OBJC_CLASS_$_HMMTRAsyncMutex
+ _OBJC_METACLASS_$_HMMTRAsyncMutex
+ __177-[HMMTRAccessoryServerBrowser setOperationalFabricData:operationalCertIssuer:storageDataSource:allTargetFabricUUIDs:entityIdentifier:accessoryServerNodeIDs:forTargetFabricUUID:]_block_invoke
+ __83-[HMMTRAccessoryServerBrowser invalidateAllDiscoveredServersWithReason:completion:]_block_invoke
+ __96-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]_block_invoke
+ __OBJC_$_CLASS_METHODS_HMMTRAsyncMutex
+ __OBJC_$_INSTANCE_METHODS_HMMTRAsyncMutex
+ __OBJC_$_INSTANCE_VARIABLES_HMMTRAsyncMutex
+ __OBJC_$_PROP_LIST_HMMTRAsyncMutex
+ __OBJC_CLASS_RO_$_HMMTRAsyncMutex
+ __OBJC_METACLASS_RO_$_HMMTRAsyncMutex
+ ___177-[HMMTRAccessoryServerBrowser setOperationalFabricData:operationalCertIssuer:storageDataSource:allTargetFabricUUIDs:entityIdentifier:accessoryServerNodeIDs:forTargetFabricUUID:]_block_invoke_2
+ ___25-[HMMTRAsyncMutex unlock]_block_invoke
+ ___30+[HMMTRAsyncMutex logCategory]_block_invoke
+ ___38-[HMMTRAsyncMutex lockWithCompletion:]_block_invoke
+ ___95-[HMMTRAccessoryServerBrowser updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]_block_invoke
+ ___96-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:]_block_invoke
+ _objc_msgSend$_makeAccessoryServerFactory
+ _objc_msgSend$_updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:
+ _objc_msgSend$discoveredAccessoryServersAsyncMutex
+ _objc_msgSend$initWithWorkQueueFactory:
+ _objc_msgSend$lockWithCompletion:
+ _objc_msgSend$locked
+ _objc_msgSend$newQueueWithLabel:attributes:
+ _objc_msgSend$newQueueWithLabel:attributes:target:
+ _objc_msgSend$pendingCompletions
+ _objc_msgSend$setLocked:
+ _objc_msgSend$stringWithUTF8String:
+ _objc_msgSend$unlock
+ _objc_msgSend$updateDiscoveredAccessoryServersWithNodes:fabricUUID:completion:
+ _objc_msgSend$workQueueFactory
+ _secondPartyProducts
- -[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:]
- GCC_except_table1002
- GCC_except_table1066
- GCC_except_table1072
- GCC_except_table1074
- GCC_except_table1196
- GCC_except_table1264
- GCC_except_table1310
- GCC_except_table1318
- GCC_except_table1369
- GCC_except_table1377
- GCC_except_table1414
- GCC_except_table1451
- GCC_except_table1478
- GCC_except_table1676
- GCC_except_table1719
- GCC_except_table1873
- GCC_except_table1874
- GCC_except_table1875
- GCC_except_table1878
- GCC_except_table1898
- GCC_except_table1899
- GCC_except_table1900
- GCC_except_table1901
- GCC_except_table1902
- GCC_except_table1905
- GCC_except_table1908
- GCC_except_table1909
- GCC_except_table1910
- GCC_except_table1911
- GCC_except_table1912
- GCC_except_table1913
- GCC_except_table1914
- GCC_except_table1973
- GCC_except_table1979
- GCC_except_table2067
- GCC_except_table2185
- GCC_except_table2187
- GCC_except_table2217
- GCC_except_table2227
- GCC_except_table2229
- GCC_except_table2285
- GCC_except_table2331
- GCC_except_table2356
- GCC_except_table2427
- GCC_except_table2714
- GCC_except_table2716
- GCC_except_table2718
- GCC_except_table2722
- GCC_except_table2783
- GCC_except_table2816
- GCC_except_table2862
- GCC_except_table2864
- GCC_except_table2895
- GCC_except_table2896
- GCC_except_table2897
- GCC_except_table2919
- GCC_except_table2923
- GCC_except_table2924
- GCC_except_table2925
- GCC_except_table2926
- GCC_except_table2936
- GCC_except_table2938
- GCC_except_table2970
- GCC_except_table2985
- GCC_except_table2991
- GCC_except_table3006
- GCC_except_table3009
- GCC_except_table3013
- GCC_except_table3028
- GCC_except_table3031
- GCC_except_table3037
- GCC_except_table3065
- GCC_except_table3074
- GCC_except_table3079
- GCC_except_table3091
- GCC_except_table3144
- GCC_except_table3145
- GCC_except_table3535
- GCC_except_table3561
- GCC_except_table3562
- GCC_except_table3563
- GCC_except_table3567
- GCC_except_table3573
- GCC_except_table3576
- GCC_except_table3607
- GCC_except_table3676
- GCC_except_table3677
- GCC_except_table3710
- GCC_except_table3719
- GCC_except_table3723
- GCC_except_table3757
- GCC_except_table3761
- GCC_except_table3769
- GCC_except_table3791
- GCC_except_table3795
- GCC_except_table3838
- GCC_except_table3840
- GCC_except_table3842
- GCC_except_table3861
- GCC_except_table3863
- GCC_except_table3884
- GCC_except_table3961
- GCC_except_table4008
- GCC_except_table4028
- GCC_except_table4051
- GCC_except_table4055
- GCC_except_table4070
- GCC_except_table4071
- GCC_except_table4072
- GCC_except_table4078
- GCC_except_table4085
- GCC_except_table4090
- GCC_except_table4127
- GCC_except_table4149
- GCC_except_table4191
- GCC_except_table4197
- GCC_except_table4200
- GCC_except_table4286
- GCC_except_table4287
- GCC_except_table4345
- GCC_except_table4348
- GCC_except_table4412
- GCC_except_table4472
- GCC_except_table4476
- GCC_except_table4482
- GCC_except_table4486
- GCC_except_table4520
- GCC_except_table593
- GCC_except_table599
- GCC_except_table601
- GCC_except_table605
- GCC_except_table762
- GCC_except_table763
- GCC_except_table820
- GCC_except_table821
- GCC_except_table822
- GCC_except_table895
- GCC_except_table937
- GCC_except_table988
- GCC_except_table992
- GCC_except_table994
- GCC_except_table996
- GCC_except_table998
- __85-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:]_block_invoke
- ___84-[HMMTRAccessoryServerBrowser updateDiscoveredAccessoryServersWithNodes:fabricUUID:]_block_invoke
- ___85-[HMMTRAccessoryServerBrowser _updateDiscoveredAccessoryServersWithNodes:fabricUUID:]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSArray"8l
- _dispatch_queue_create_with_target$V2
- _objc_msgSend$_updateDiscoveredAccessoryServersWithNodes:fabricUUID:
- _objc_msgSend$updateDiscoveredAccessoryServersWithNodes:fabricUUID:
CStrings:
+ "Firmware update connection attempt for an accessory with nodeID %@, error = %@"
+ "Lock acquired"
+ "Lock handed to next waiter (pending=%lu)"
+ "Lock is held; queued waiter (pending=%lu)"
+ "Lock released"
+ "ProxPairing"
+ "Refusing to commission vendor %@ product %@: pairing this accessory is not supported"
+ "Unlock called while not locked; ignoring"
+ "[%{public}@] Firmware update connection attempt for an accessory with nodeID %@, error = %@"
+ "[%{public}@] Lock acquired"
+ "[%{public}@] Lock handed to next waiter (pending=%lu)"
+ "[%{public}@] Lock is held; queued waiter (pending=%lu)"
+ "[%{public}@] Lock released"
+ "[%{public}@] Refusing to commission vendor %@ product %@: pairing this accessory is not supported"
+ "[%{public}@] Unlock called while not locked; ignoring"
+ "hmmtr.asyncmutex"
- "Firmware update connection attempt for a accessory with nodeID %@, error = %@"
- "[%{public}@] Firmware update connection attempt for a accessory with nodeID %@, error = %@"
```
