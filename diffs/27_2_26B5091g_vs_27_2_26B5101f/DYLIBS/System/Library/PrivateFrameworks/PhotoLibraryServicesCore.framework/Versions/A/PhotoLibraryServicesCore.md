## PhotoLibraryServicesCore

> `/System/Library/PrivateFrameworks/PhotoLibraryServicesCore.framework/Versions/A/PhotoLibraryServicesCore`

```diff

-916.45.110.0.0
-  __TEXT.__text: 0xd025c
-  __TEXT.__objc_methlist: 0x84ac
+916.53.100.0.0
+  __TEXT.__text: 0xd153c
+  __TEXT.__objc_methlist: 0x851c
   __TEXT.__const: 0x22b4
   __TEXT.__dlopen_cstrs: 0xe1
-  __TEXT.__gcc_except_tab: 0x5760
-  __TEXT.__cstring: 0x15884
-  __TEXT.__oslogstring: 0xb788
+  __TEXT.__gcc_except_tab: 0x57f4
+  __TEXT.__cstring: 0x158ea
+  __TEXT.__oslogstring: 0xb8e3
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x41f0
+  __TEXT.__unwind_info: 0x4230
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x160
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x50a0
+  __DATA_CONST.__objc_selrefs: 0x50f0
   __DATA_CONST.__objc_protorefs: 0xc8
   __DATA_CONST.__objc_superrefs: 0x258
   __DATA_CONST.__objc_arraydata: 0x440
-  __DATA_CONST.__got: 0xa08
-  __AUTH_CONST.__const: 0x52b0
-  __AUTH_CONST.__cfstring: 0x11b80
-  __AUTH_CONST.__objc_const: 0xac28
+  __DATA_CONST.__got: 0xa18
+  __AUTH_CONST.__const: 0x5310
+  __AUTH_CONST.__cfstring: 0x11c20
+  __AUTH_CONST.__objc_const: 0xac78
   __AUTH_CONST.__objc_intobj: 0x918
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_arrayobj: 0x2b8
-  __AUTH_CONST.__auth_got: 0xd10
+  __AUTH_CONST.__auth_got: 0xd18
   __AUTH.__objc_data: 0xf0
-  __DATA.__objc_ivar: 0x694
+  __DATA.__objc_ivar: 0x698
   __DATA.__data: 0x10e0
-  __DATA.__bss: 0x888
+  __DATA.__bss: 0x898
   __DATA_DIRTY.__objc_data: 0x2710
   __DATA_DIRTY.__data: 0x8
   __DATA_DIRTY.__bss: 0x8b8

   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
   - /System/Library/Frameworks/_LocationEssentials.framework/Versions/A/_LocationEssentials
   - /System/Library/PrivateFrameworks/AppSupport.framework/Versions/A/AppSupport
+  - /System/Library/PrivateFrameworks/AuthKit.framework/Versions/A/AuthKit
   - /System/Library/PrivateFrameworks/CMPhoto.framework/Versions/A/CMPhoto
   - /System/Library/PrivateFrameworks/CoreAnalytics.framework/Versions/A/CoreAnalytics
   - /System/Library/PrivateFrameworks/PhotoFoundation.framework/Versions/A/PhotoFoundation

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libperfcheck.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 4067
-  Symbols:   9762
-  CStrings:  3663
+  Functions: 4085
+  Symbols:   9796
+  CStrings:  3672
 
Symbols:
+ +[PLAppPrivateData _isOptedIntoLibraryPrivateDataCreationTracking]
+ -[PLAppPrivateData clearWasCreatedFlag]
+ -[PLAppPrivateData setWasNewlyCreated:]
+ -[PLAppPrivateData wasCreated]
+ -[PLAppPrivateData wasNewlyCreated]
+ -[PLAssetsdCloudInternalClient updateAccessRequestForParticipantWithUUID:toAcceptanceStatus:inCollectionShareWithIdentifier:completionHandler:]
+ -[PLAssetsdLibraryInternalClient migrateLimitedLibraryAccessFromApplication:toApplication:completionHandler:]
+ -[PLAssetsdLibraryInternalClient transferAssetsWithUuids:fromLibraryURL:transferOptions:completionHandler:]
+ -[PLAssetsdLibraryInternalClient transferPersonsWithUuids:fromLibraryURL:transferOptions:completionHandler:]
+ GCC_except_table1034
+ GCC_except_table1036
+ GCC_except_table1038
+ GCC_except_table1055
+ GCC_except_table1077
+ GCC_except_table1081
+ GCC_except_table1098
+ GCC_except_table1157
+ GCC_except_table1198
+ GCC_except_table1524
+ GCC_except_table1539
+ GCC_except_table1548
+ GCC_except_table1665
+ GCC_except_table1698
+ GCC_except_table1705
+ GCC_except_table1741
+ GCC_except_table1759
+ GCC_except_table1785
+ GCC_except_table1787
+ GCC_except_table1794
+ GCC_except_table1797
+ GCC_except_table1800
+ GCC_except_table1803
+ GCC_except_table1806
+ GCC_except_table1809
+ GCC_except_table1812
+ GCC_except_table1815
+ GCC_except_table1821
+ GCC_except_table1825
+ GCC_except_table1828
+ GCC_except_table1831
+ GCC_except_table1842
+ GCC_except_table1845
+ GCC_except_table1848
+ GCC_except_table1851
+ GCC_except_table1854
+ GCC_except_table1857
+ GCC_except_table1860
+ GCC_except_table1863
+ GCC_except_table1866
+ GCC_except_table1869
+ GCC_except_table1876
+ GCC_except_table1880
+ GCC_except_table1883
+ GCC_except_table1886
+ GCC_except_table1889
+ GCC_except_table1900
+ GCC_except_table1903
+ GCC_except_table1906
+ GCC_except_table1909
+ GCC_except_table1935
+ GCC_except_table2037
+ GCC_except_table2056
+ GCC_except_table2208
+ GCC_except_table2216
+ GCC_except_table2266
+ GCC_except_table2271
+ GCC_except_table2272
+ GCC_except_table2274
+ GCC_except_table2277
+ GCC_except_table2417
+ GCC_except_table2498
+ GCC_except_table2539
+ GCC_except_table256
+ GCC_except_table2573
+ GCC_except_table2578
+ GCC_except_table2581
+ GCC_except_table2584
+ GCC_except_table2604
+ GCC_except_table2607
+ GCC_except_table2610
+ GCC_except_table262
+ GCC_except_table2633
+ GCC_except_table265
+ GCC_except_table2681
+ GCC_except_table2685
+ GCC_except_table2689
+ GCC_except_table2692
+ GCC_except_table2697
+ GCC_except_table270
+ GCC_except_table2700
+ GCC_except_table2703
+ GCC_except_table2707
+ GCC_except_table2718
+ GCC_except_table2720
+ GCC_except_table2724
+ GCC_except_table2728
+ GCC_except_table2732
+ GCC_except_table2736
+ GCC_except_table2740
+ GCC_except_table2744
+ GCC_except_table2748
+ GCC_except_table2752
+ GCC_except_table2756
+ GCC_except_table276
+ GCC_except_table2760
+ GCC_except_table2764
+ GCC_except_table2768
+ GCC_except_table2772
+ GCC_except_table2776
+ GCC_except_table2780
+ GCC_except_table2783
+ GCC_except_table2787
+ GCC_except_table2791
+ GCC_except_table2795
+ GCC_except_table2799
+ GCC_except_table2807
+ GCC_except_table2813
+ GCC_except_table2816
+ GCC_except_table2819
+ GCC_except_table2823
+ GCC_except_table2827
+ GCC_except_table2831
+ GCC_except_table2835
+ GCC_except_table2839
+ GCC_except_table284
+ GCC_except_table2843
+ GCC_except_table2851
+ GCC_except_table2860
+ GCC_except_table2863
+ GCC_except_table2865
+ GCC_except_table2866
+ GCC_except_table2868
+ GCC_except_table2871
+ GCC_except_table2875
+ GCC_except_table2877
+ GCC_except_table2880
+ GCC_except_table2883
+ GCC_except_table2886
+ GCC_except_table2889
+ GCC_except_table2892
+ GCC_except_table2895
+ GCC_except_table2898
+ GCC_except_table2901
+ GCC_except_table2904
+ GCC_except_table2907
+ GCC_except_table2910
+ GCC_except_table2913
+ GCC_except_table2916
+ GCC_except_table2918
+ GCC_except_table292
+ GCC_except_table2974
+ GCC_except_table3041
+ GCC_except_table3044
+ GCC_except_table307
+ GCC_except_table3101
+ GCC_except_table315
+ GCC_except_table3156
+ GCC_except_table3168
+ GCC_except_table3170
+ GCC_except_table3174
+ GCC_except_table3176
+ GCC_except_table3194
+ GCC_except_table3202
+ GCC_except_table3208
+ GCC_except_table323
+ GCC_except_table3365
+ GCC_except_table3367
+ GCC_except_table3376
+ GCC_except_table3379
+ GCC_except_table3382
+ GCC_except_table3385
+ GCC_except_table3388
+ GCC_except_table3391
+ GCC_except_table3443
+ GCC_except_table3445
+ GCC_except_table3480
+ GCC_except_table3585
+ GCC_except_table3655
+ GCC_except_table3659
+ GCC_except_table3666
+ GCC_except_table3720
+ GCC_except_table3723
+ GCC_except_table3729
+ GCC_except_table3732
+ GCC_except_table3735
+ GCC_except_table3738
+ GCC_except_table3744
+ GCC_except_table3750
+ GCC_except_table3754
+ GCC_except_table3758
+ GCC_except_table3762
+ GCC_except_table3766
+ GCC_except_table3787
+ GCC_except_table3790
+ GCC_except_table3812
+ GCC_except_table3830
+ GCC_except_table3838
+ GCC_except_table384
+ GCC_except_table3840
+ GCC_except_table3845
+ GCC_except_table3849
+ GCC_except_table385
+ GCC_except_table3855
+ GCC_except_table3863
+ GCC_except_table3866
+ GCC_except_table3873
+ GCC_except_table3880
+ GCC_except_table3883
+ GCC_except_table3895
+ GCC_except_table3901
+ GCC_except_table3904
+ GCC_except_table3907
+ GCC_except_table3911
+ GCC_except_table3915
+ GCC_except_table3929
+ GCC_except_table3932
+ GCC_except_table3976
+ GCC_except_table4002
+ GCC_except_table4003
+ GCC_except_table4005
+ GCC_except_table4007
+ GCC_except_table4009
+ GCC_except_table4012
+ GCC_except_table4015
+ GCC_except_table4016
+ GCC_except_table4046
+ GCC_except_table405
+ GCC_except_table4054
+ GCC_except_table4059
+ GCC_except_table411
+ GCC_except_table420
+ GCC_except_table433
+ GCC_except_table489
+ GCC_except_table494
+ GCC_except_table514
+ GCC_except_table527
+ GCC_except_table531
+ GCC_except_table538
+ GCC_except_table542
+ GCC_except_table548
+ GCC_except_table559
+ GCC_except_table563
+ GCC_except_table573
+ GCC_except_table632
+ GCC_except_table694
+ GCC_except_table728
+ GCC_except_table733
+ GCC_except_table745
+ GCC_except_table749
+ GCC_except_table759
+ GCC_except_table919
+ GCC_except_table924
+ GCC_except_table928
+ GCC_except_table961
+ GCC_except_table989
+ GCC_except_table993
+ OBJC_IVAR_$_PLAppPrivateData._wasNewlyCreated
+ _OBJC_CLASS_$_AKAccountManager
+ _PLGetSandboxExtensionTokenCanonical
+ _PLGetSandboxExtensionTokenForProcessCanonical
+ _PLIsChinaAccount
+ _PLNoFollowPath
+ _PLPlatformBackgroundSearchIndexingSupported
+ _PLVettedResourcePath
+ _SANDBOX_EXTENSION_CANONICAL
+ __143-[PLAssetsdCloudInternalClient updateAccessRequestForParticipantWithUUID:toAcceptanceStatus:inCollectionShareWithIdentifier:completionHandler:]_block_invoke
+ ___107-[PLAssetsdLibraryInternalClient transferAssetsWithUuids:fromLibraryURL:transferOptions:completionHandler:]_block_invoke
+ ___108-[PLAssetsdLibraryInternalClient transferPersonsWithUuids:fromLibraryURL:transferOptions:completionHandler:]_block_invoke
+ ___109-[PLAssetsdLibraryInternalClient migrateLimitedLibraryAccessFromApplication:toApplication:completionHandler:]_block_invoke
+ ___109-[PLAssetsdLibraryInternalClient migrateLimitedLibraryAccessFromApplication:toApplication:completionHandler:]_block_invoke_2
+ ___143-[PLAssetsdCloudInternalClient updateAccessRequestForParticipantWithUUID:toAcceptanceStatus:inCollectionShareWithIdentifier:completionHandler:]_block_invoke
+ ___block_descriptor_112_e8_32s40s48bs56n18_8_8_t0w1_s8_t16w32_e51_v16?0"<PLAssetsdLibraryInternalServiceProtocol>"8l
+ ___block_descriptor_120_e8_32s40s48bs56n18_8_8_t0w1_s8_t16w32_e49_v16?0"<PLAssetsdCloudInternalServiceProtocol>"8l
+ _objc_msgSend$_isOptedIntoLibraryPrivateDataCreationTracking
+ _objc_msgSend$appleIDCountryCodeForAccount:
+ _objc_msgSend$migrateLimitedLibraryAccessFromApplication:toApplication:completionHandler:
+ _objc_msgSend$primaryAuthKitAccount
+ _objc_msgSend$setWasNewlyCreated:
+ _objc_msgSend$updateAccessRequestForParticipantWithUUID:toAcceptanceStatus:inCollectionShareWithIdentifier:reply:
+ _objc_msgSend$wasNewlyCreated
+ _sLibraryURLsCreatedThisLaunch
+ _sLibraryURLsCreatedThisLaunchLock
+ _sandbox_check_by_audit_token
- -[PLAssetsdLibraryClient transferAssetsWithUuids:fromLibraryURL:transferOptions:completionHandler:]
- -[PLAssetsdLibraryClient transferPersonsWithUuids:fromLibraryURL:transferOptions:completionHandler:]
- GCC_except_table1032
- GCC_except_table1037
- GCC_except_table1039
- GCC_except_table1056
- GCC_except_table1076
- GCC_except_table1080
- GCC_except_table1099
- GCC_except_table1101
- GCC_except_table1160
- GCC_except_table1197
- GCC_except_table1523
- GCC_except_table1538
- GCC_except_table1547
- GCC_except_table1664
- GCC_except_table1697
- GCC_except_table1704
- GCC_except_table1740
- GCC_except_table1758
- GCC_except_table1784
- GCC_except_table1792
- GCC_except_table1795
- GCC_except_table1798
- GCC_except_table1801
- GCC_except_table1804
- GCC_except_table1807
- GCC_except_table1810
- GCC_except_table1813
- GCC_except_table1816
- GCC_except_table1820
- GCC_except_table1826
- GCC_except_table1829
- GCC_except_table1832
- GCC_except_table1843
- GCC_except_table1846
- GCC_except_table1849
- GCC_except_table1852
- GCC_except_table1855
- GCC_except_table1858
- GCC_except_table1861
- GCC_except_table1864
- GCC_except_table1868
- GCC_except_table1875
- GCC_except_table1878
- GCC_except_table1881
- GCC_except_table1884
- GCC_except_table1887
- GCC_except_table1890
- GCC_except_table1901
- GCC_except_table1911
- GCC_except_table2029
- GCC_except_table2048
- GCC_except_table2199
- GCC_except_table2207
- GCC_except_table2257
- GCC_except_table2262
- GCC_except_table2263
- GCC_except_table2265
- GCC_except_table2268
- GCC_except_table2408
- GCC_except_table2489
- GCC_except_table2530
- GCC_except_table255
- GCC_except_table2564
- GCC_except_table2569
- GCC_except_table2572
- GCC_except_table2575
- GCC_except_table2580
- GCC_except_table2583
- GCC_except_table2586
- GCC_except_table261
- GCC_except_table2615
- GCC_except_table264
- GCC_except_table266
- GCC_except_table2672
- GCC_except_table2676
- GCC_except_table268
- GCC_except_table2680
- GCC_except_table2683
- GCC_except_table2688
- GCC_except_table2691
- GCC_except_table2694
- GCC_except_table2698
- GCC_except_table2702
- GCC_except_table2706
- GCC_except_table2709
- GCC_except_table2719
- GCC_except_table2723
- GCC_except_table2727
- GCC_except_table273
- GCC_except_table2731
- GCC_except_table2735
- GCC_except_table2739
- GCC_except_table2743
- GCC_except_table2747
- GCC_except_table2751
- GCC_except_table2755
- GCC_except_table2759
- GCC_except_table2763
- GCC_except_table2767
- GCC_except_table2770
- GCC_except_table2774
- GCC_except_table2778
- GCC_except_table2782
- GCC_except_table2786
- GCC_except_table2790
- GCC_except_table2794
- GCC_except_table2797
- GCC_except_table2800
- GCC_except_table2806
- GCC_except_table2814
- GCC_except_table2818
- GCC_except_table282
- GCC_except_table2822
- GCC_except_table2826
- GCC_except_table2830
- GCC_except_table2834
- GCC_except_table2838
- GCC_except_table2842
- GCC_except_table2845
- GCC_except_table2850
- GCC_except_table2852
- GCC_except_table2853
- GCC_except_table2862
- GCC_except_table2864
- GCC_except_table2867
- GCC_except_table2870
- GCC_except_table2873
- GCC_except_table2876
- GCC_except_table2879
- GCC_except_table2882
- GCC_except_table2885
- GCC_except_table2888
- GCC_except_table2891
- GCC_except_table2894
- GCC_except_table2897
- GCC_except_table290
- GCC_except_table2900
- GCC_except_table2903
- GCC_except_table2905
- GCC_except_table2961
- GCC_except_table301
- GCC_except_table3028
- GCC_except_table3031
- GCC_except_table3088
- GCC_except_table310
- GCC_except_table3143
- GCC_except_table3155
- GCC_except_table3157
- GCC_except_table3161
- GCC_except_table3163
- GCC_except_table318
- GCC_except_table3181
- GCC_except_table3189
- GCC_except_table3195
- GCC_except_table3350
- GCC_except_table3352
- GCC_except_table3354
- GCC_except_table3359
- GCC_except_table3366
- GCC_except_table3369
- GCC_except_table3375
- GCC_except_table3378
- GCC_except_table338
- GCC_except_table3430
- GCC_except_table3432
- GCC_except_table3467
- GCC_except_table3572
- GCC_except_table3642
- GCC_except_table3646
- GCC_except_table3653
- GCC_except_table3707
- GCC_except_table3710
- GCC_except_table3716
- GCC_except_table3719
- GCC_except_table3722
- GCC_except_table3725
- GCC_except_table3731
- GCC_except_table3737
- GCC_except_table3741
- GCC_except_table3745
- GCC_except_table3749
- GCC_except_table3753
- GCC_except_table3774
- GCC_except_table3777
- GCC_except_table3786
- GCC_except_table3817
- GCC_except_table3825
- GCC_except_table3827
- GCC_except_table3832
- GCC_except_table3836
- GCC_except_table3842
- GCC_except_table3847
- GCC_except_table3850
- GCC_except_table3853
- GCC_except_table3857
- GCC_except_table3867
- GCC_except_table387
- GCC_except_table3875
- GCC_except_table3878
- GCC_except_table388
- GCC_except_table3882
- GCC_except_table3885
- GCC_except_table3894
- GCC_except_table3902
- GCC_except_table3916
- GCC_except_table3919
- GCC_except_table3963
- GCC_except_table3986
- GCC_except_table3987
- GCC_except_table3988
- GCC_except_table3990
- GCC_except_table3992
- GCC_except_table3994
- GCC_except_table3995
- GCC_except_table3997
- GCC_except_table4000
- GCC_except_table4023
- GCC_except_table4036
- GCC_except_table408
- GCC_except_table414
- GCC_except_table423
- GCC_except_table436
- GCC_except_table492
- GCC_except_table512
- GCC_except_table523
- GCC_except_table530
- GCC_except_table537
- GCC_except_table541
- GCC_except_table545
- GCC_except_table554
- GCC_except_table562
- GCC_except_table566
- GCC_except_table576
- GCC_except_table635
- GCC_except_table697
- GCC_except_table731
- GCC_except_table742
- GCC_except_table748
- GCC_except_table761
- GCC_except_table765
- GCC_except_table922
- GCC_except_table927
- GCC_except_table958
- GCC_except_table988
- GCC_except_table992
- ___100-[PLAssetsdLibraryClient transferPersonsWithUuids:fromLibraryURL:transferOptions:completionHandler:]_block_invoke
- ___99-[PLAssetsdLibraryClient transferAssetsWithUuids:fromLibraryURL:transferOptions:completionHandler:]_block_invoke
CStrings:
+ "/.nofollow"
+ "CN"
+ "PLXPC Client: migrateLimitedLibraryAccessFromApplication:toApplication:completionHandler:"
+ "PLXPC Client: updateAccessRequestForParticipantWithUUID:toAcceptanceStatus:inCollectionShareWithIdentifier:completionHandler:"
+ "Refusing to map '%@': redirected or non-regular."
+ "Unable to update access request (%@)"
+ "Unable to update access request for participant in collection share with identifier: %@. (%@)"
+ "XCTestCase"
+ "newBundleIdentifier"
+ "oldBundleIdentifier"
- "XCTestProbe"
```
