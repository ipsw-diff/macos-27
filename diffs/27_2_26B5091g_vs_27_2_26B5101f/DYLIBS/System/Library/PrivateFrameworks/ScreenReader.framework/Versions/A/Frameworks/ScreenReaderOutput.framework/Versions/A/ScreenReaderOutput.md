## ScreenReaderOutput

> `/System/Library/PrivateFrameworks/ScreenReader.framework/Versions/A/Frameworks/ScreenReaderOutput.framework/Versions/A/ScreenReaderOutput`

```diff

-1050.3.0.0.0
-  __TEXT.__text: 0xa4518
-  __TEXT.__objc_methlist: 0x95c0
+1050.3.3.0.0
+  __TEXT.__text: 0xa4f58
+  __TEXT.__objc_methlist: 0x9610
   __TEXT.__const: 0x1938
-  __TEXT.__cstring: 0x65ee
+  __TEXT.__cstring: 0x65f9
   __TEXT.__swift5_typeref: 0xeec
   __TEXT.__constg_swiftt: 0x960
   __TEXT.__swift5_builtin: 0xb4
   __TEXT.__swift5_types: 0xa4
-  __TEXT.__oslogstring: 0x285a
+  __TEXT.__oslogstring: 0x28a1
   __TEXT.__swift5_reflstr: 0x605
   __TEXT.__swift5_assocty: 0x78
   __TEXT.__swift5_fieldmd: 0x7f8

   __TEXT.__swift_as_ret: 0x5c
   __TEXT.__swift_as_cont: 0x9c
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__gcc_except_tab: 0x1954
+  __TEXT.__gcc_except_tab: 0x1964
   __TEXT.__ustring: 0x9e
-  __TEXT.__unwind_info: 0x3578
+  __TEXT.__unwind_info: 0x3590
   __TEXT.__eh_frame: 0xa28
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x140
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4a18
+  __DATA_CONST.__objc_selrefs: 0x4a38
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x218
   __DATA_CONST.__objc_arraydata: 0x3f8
   __DATA_CONST.__got: 0x808
   __AUTH_CONST.__const: 0x44f8
   __AUTH_CONST.__cfstring: 0x6580
-  __AUTH_CONST.__objc_const: 0xc238
+  __AUTH_CONST.__objc_const: 0xc290
   __AUTH_CONST.__objc_intobj: 0x1218
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0x10

   __AUTH_CONST.__auth_got: 0xef0
   __AUTH.__objc_data: 0x400
   __AUTH.__data: 0x70
-  __DATA.__objc_ivar: 0x918
+  __DATA.__objc_ivar: 0x920
   __DATA.__data: 0x1690
   __DATA.__bss: 0x1100
   __DATA.__common: 0x20

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4119
-  Symbols:   7983
-  CStrings:  1185
+  Functions: 4126
+  Symbols:   7997
+  CStrings:  1186
 
Symbols:
+ -[SCROBrailleClientXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleClientXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleDisplay _cancelPendingCellWrites]
+ -[SCROBrailleHandler handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandler handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]
+ -[SCROMobileBrailleDisplayInputManager _storedUserDefaultsForModelIdentifier:]
+ -[SCROMobileBrailleDisplayInputManager _userDefaultsForDisplayWithToken:]
+ -[SCROMobileBrailleDisplayInputManager userDefaultsForModelIdentifier:productName:driverIdentifier:]
+ -[SCROMobileBrailleDisplayInputManagerCacheObject modelIdentifierForPlist]
+ -[SCROMobileBrailleDisplayInputManagerCacheObject setModelIdentifierForPlist:]
+ GCC_except_table1109
+ GCC_except_table1173
+ GCC_except_table1175
+ GCC_except_table1177
+ GCC_except_table1179
+ GCC_except_table1245
+ GCC_except_table1275
+ GCC_except_table1282
+ GCC_except_table1289
+ GCC_except_table1291
+ GCC_except_table1321
+ GCC_except_table1328
+ GCC_except_table1458
+ GCC_except_table1667
+ GCC_except_table1791
+ GCC_except_table1932
+ GCC_except_table1934
+ GCC_except_table1943
+ GCC_except_table1955
+ GCC_except_table2039
+ GCC_except_table2084
+ GCC_except_table2090
+ GCC_except_table2204
+ GCC_except_table2225
+ GCC_except_table2234
+ GCC_except_table2242
+ GCC_except_table2345
+ GCC_except_table2529
+ GCC_except_table2550
+ GCC_except_table2660
+ GCC_except_table2661
+ GCC_except_table2662
+ GCC_except_table2666
+ GCC_except_table2673
+ GCC_except_table2677
+ GCC_except_table2678
+ GCC_except_table2679
+ GCC_except_table2683
+ GCC_except_table2688
+ GCC_except_table2693
+ GCC_except_table3041
+ GCC_except_table3059
+ GCC_except_table3078
+ GCC_except_table3079
+ GCC_except_table3080
+ GCC_except_table3147
+ GCC_except_table3148
+ GCC_except_table3150
+ GCC_except_table3152
+ GCC_except_table458
+ GCC_except_table491
+ GCC_except_table515
+ GCC_except_table525
+ GCC_except_table527
+ GCC_except_table550
+ GCC_except_table552
+ GCC_except_table556
+ GCC_except_table559
+ GCC_except_table569
+ GCC_except_table589
+ GCC_except_table592
+ GCC_except_table600
+ GCC_except_table602
+ GCC_except_table610
+ GCC_except_table627
+ GCC_except_table629
+ GCC_except_table634
+ GCC_except_table638
+ GCC_except_table642
+ GCC_except_table661
+ GCC_except_table664
+ GCC_except_table928
+ GCC_except_table969
+ GCC_except_table971
+ OBJC_IVAR_$_SCROBrailleDisplay._driverModelIdentifierForAnalytics
+ OBJC_IVAR_$_SCROMobileBrailleDisplayInputManagerCacheObject._modelIdentifierForPlist
+ ___95-[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:]_block_invoke
+ ___96-[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56s64s_e41_v16?0"<SCROBrailleClientCallbacksXPC>"8l
+ ___block_descriptor_80_e8_32s40s48s56s64s72s_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64s72s
+ ___destroy_helper_block_e8_32s40s48s56s64s72s
+ _kSCROBrailleDisplayModelIdentifierForAnalytics
+ _objc_msgSend$_cancelPendingCellWrites
+ _objc_msgSend$_storedUserDefaultsForModelIdentifier:
+ _objc_msgSend$_userDefaultsForDisplayWithToken:
+ _objc_msgSend$handleBrailleDidPanLeft:elementToken:appToken:lineOffset:displayToken:
+ _objc_msgSend$handleBrailleDidPanRight:elementToken:appToken:lineOffset:displayToken:
+ _objc_msgSend$modelIdentifierForAnalytics
+ _objc_msgSend$userDefaultsForModelIdentifier:productName:driverIdentifier:
- -[SCROBrailleClientXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROBrailleClientXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandler handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandler handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]
- -[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:]
- -[SCROMobileBrailleDisplayInputManager userDefaultsForModelIdentifier:]
- GCC_except_table1108
- GCC_except_table1172
- GCC_except_table1174
- GCC_except_table1176
- GCC_except_table1178
- GCC_except_table1242
- GCC_except_table1272
- GCC_except_table1279
- GCC_except_table1283
- GCC_except_table1288
- GCC_except_table1318
- GCC_except_table1325
- GCC_except_table1455
- GCC_except_table1664
- GCC_except_table1788
- GCC_except_table1929
- GCC_except_table1931
- GCC_except_table1940
- GCC_except_table1952
- GCC_except_table2036
- GCC_except_table2081
- GCC_except_table2087
- GCC_except_table2201
- GCC_except_table2222
- GCC_except_table2231
- GCC_except_table2239
- GCC_except_table2342
- GCC_except_table2526
- GCC_except_table2547
- GCC_except_table2657
- GCC_except_table2658
- GCC_except_table2659
- GCC_except_table2663
- GCC_except_table2668
- GCC_except_table2669
- GCC_except_table2670
- GCC_except_table2676
- GCC_except_table2680
- GCC_except_table2685
- GCC_except_table2687
- GCC_except_table3034
- GCC_except_table3052
- GCC_except_table3071
- GCC_except_table3072
- GCC_except_table3073
- GCC_except_table3136
- GCC_except_table3138
- GCC_except_table3140
- GCC_except_table3141
- GCC_except_table457
- GCC_except_table489
- GCC_except_table513
- GCC_except_table524
- GCC_except_table526
- GCC_except_table548
- GCC_except_table551
- GCC_except_table554
- GCC_except_table558
- GCC_except_table568
- GCC_except_table588
- GCC_except_table590
- GCC_except_table599
- GCC_except_table601
- GCC_except_table609
- GCC_except_table623
- GCC_except_table628
- GCC_except_table632
- GCC_except_table637
- GCC_except_table641
- GCC_except_table659
- GCC_except_table663
- GCC_except_table927
- GCC_except_table968
- GCC_except_table970
- ___82-[SCROBrailleHandlerXPC handleBrailleDidPanLeft:elementToken:appToken:lineOffset:]_block_invoke
- ___83-[SCROBrailleHandlerXPC handleBrailleDidPanRight:elementToken:appToken:lineOffset:]_block_invoke
- ___block_descriptor_64_e8_32s40s48s56s_e41_v16?0"<SCROBrailleClientCallbacksXPC>"8l
- ___block_descriptor_72_e8_32s40s48s56s64s_e5_v8?0l
- _objc_msgSend$handleBrailleDidPanLeft:elementToken:appToken:lineOffset:
- _objc_msgSend$handleBrailleDidPanRight:elementToken:appToken:lineOffset:
- _objc_msgSend$userDefaultsForModelIdentifier:
CStrings:
+ "Braille: copied %lu command assignments for %{public}@ from %{public}@"
+ "BrailleDisplayModelIdentifierForAnalytics"
+ "SCRBrailleAssignmentsMigratedFrom"
- "NLS eReader Humanware"
- "com.apple.scrod.braille.driver.nls.ereader"
```
