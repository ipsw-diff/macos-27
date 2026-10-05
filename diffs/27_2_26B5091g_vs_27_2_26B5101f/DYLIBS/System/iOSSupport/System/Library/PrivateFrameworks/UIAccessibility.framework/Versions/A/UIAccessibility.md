## UIAccessibility

> `/System/iOSSupport/System/Library/PrivateFrameworks/UIAccessibility.framework/Versions/A/UIAccessibility`

```diff

-3245.7.0.0.0
-  __TEXT.__text: 0x66bc0
-  __TEXT.__objc_methlist: 0x67dc
+3245.8.4.0.0
+  __TEXT.__text: 0x66d50
+  __TEXT.__objc_methlist: 0x67e4
   __TEXT.__const: 0x218
   __TEXT.__dlopen_cstrs: 0x162
-  __TEXT.__gcc_except_tab: 0xbe0
+  __TEXT.__gcc_except_tab: 0xbf8
   __TEXT.__cstring: 0x6ab9
-  __TEXT.__oslogstring: 0x2c41
+  __TEXT.__oslogstring: 0x2c8f
   __TEXT.__ustring: 0x14
-  __TEXT.__unwind_info: 0x1e80
+  __TEXT.__unwind_info: 0x1e88
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x14b8
+  __DATA_CONST.__const: 0x1490
   __DATA_CONST.__objc_classlist: 0x1b8
   __DATA_CONST.__objc_catlist: 0xa8
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5360
+  __DATA_CONST.__objc_selrefs: 0x5370
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0xe8
   __DATA_CONST.__objc_arraydata: 0x128

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2546
-  Symbols:   6460
-  CStrings:  1134
+  Functions: 2547
+  Symbols:   6463
+  CStrings:  1135
 
Symbols:
+ -[UIWindowScene(UIAccessibilityElementTraversal) _accessibilityChildrenByAddingMultitaskingElements:]
+ GCC_except_table1027
+ GCC_except_table1035
+ GCC_except_table1040
+ GCC_except_table1076
+ GCC_except_table1093
+ GCC_except_table1200
+ GCC_except_table1303
+ GCC_except_table1311
+ GCC_except_table1313
+ GCC_except_table1315
+ GCC_except_table1326
+ GCC_except_table1338
+ GCC_except_table1371
+ GCC_except_table1381
+ GCC_except_table1383
+ GCC_except_table1458
+ GCC_except_table1461
+ GCC_except_table1526
+ GCC_except_table1529
+ GCC_except_table1551
+ GCC_except_table1591
+ GCC_except_table1603
+ GCC_except_table1606
+ GCC_except_table1619
+ GCC_except_table1655
+ GCC_except_table1685
+ GCC_except_table1697
+ GCC_except_table1699
+ GCC_except_table1703
+ GCC_except_table1707
+ GCC_except_table1731
+ GCC_except_table1734
+ GCC_except_table1736
+ GCC_except_table1741
+ GCC_except_table1744
+ GCC_except_table1748
+ GCC_except_table1840
+ GCC_except_table1933
+ GCC_except_table1951
+ GCC_except_table2105
+ GCC_except_table2152
+ GCC_except_table2158
+ GCC_except_table2167
+ GCC_except_table2381
+ GCC_except_table2400
+ GCC_except_table245
+ GCC_except_table2483
+ GCC_except_table272
+ GCC_except_table275
+ GCC_except_table290
+ GCC_except_table334
+ GCC_except_table348
+ GCC_except_table526
+ GCC_except_table755
+ GCC_except_table918
+ GCC_except_table950
+ GCC_except_table981
+ GCC_except_table992
+ _AXUIKeyboardVisibleInputScreenFrame
+ _objc_msgSend$_accessibilityChildrenByAddingMultitaskingElements:
+ _objc_msgSend$accessibilityApplyScrollContentOverride:sendScrollStatus:animateWithDuration:animationCurve:allowDelegateTargetRedirect:
- GCC_except_table1026
- GCC_except_table1034
- GCC_except_table1039
- GCC_except_table1075
- GCC_except_table1092
- GCC_except_table1199
- GCC_except_table1302
- GCC_except_table1310
- GCC_except_table1312
- GCC_except_table1314
- GCC_except_table1325
- GCC_except_table1337
- GCC_except_table1370
- GCC_except_table1379
- GCC_except_table1382
- GCC_except_table1457
- GCC_except_table1460
- GCC_except_table1525
- GCC_except_table1528
- GCC_except_table1550
- GCC_except_table1590
- GCC_except_table1602
- GCC_except_table1605
- GCC_except_table1618
- GCC_except_table1654
- GCC_except_table1684
- GCC_except_table1696
- GCC_except_table1698
- GCC_except_table1702
- GCC_except_table1706
- GCC_except_table1730
- GCC_except_table1733
- GCC_except_table1735
- GCC_except_table1740
- GCC_except_table1743
- GCC_except_table1747
- GCC_except_table1839
- GCC_except_table1932
- GCC_except_table1950
- GCC_except_table2104
- GCC_except_table2151
- GCC_except_table2157
- GCC_except_table2165
- GCC_except_table2380
- GCC_except_table2399
- GCC_except_table244
- GCC_except_table2482
- GCC_except_table271
- GCC_except_table274
- GCC_except_table289
- GCC_except_table333
- GCC_except_table347
- GCC_except_table525
- GCC_except_table754
- GCC_except_table917
- GCC_except_table949
- GCC_except_table980
- GCC_except_table991
- ___block_descriptor_48_e8_32bs_e8_B16?08ls32l8
Functions:
~ __copyElementAtPositionCallback : 3876 -> 4008
~ -[NSObject(UIAccessibilityElementTraversal) _accessibilityEnumerateSiblingsWithParent:options:usingBlock:] : 2888 -> 2928
~ -[UIWindowScene(UIAccessibilityElementTraversal) _accessibilityViewChildrenWithOptions:] : 860 -> 764
+ -[UIWindowScene(UIAccessibilityElementTraversal) _accessibilityChildrenByAddingMultitaskingElements:]
~ -[NSObject(AXPrivCategory) _accessibilityKeyboardFrame] : 56 -> 116
~ -[UIAccessibilityAutoscrollManager pause] : 268 -> 272
~ +[UIAccessibilityHitTestOptions dwellControlElementHighlightOptions] : 340 -> 328
~ ___68+[UIAccessibilityHitTestOptions dwellControlElementHighlightOptions]_block_invoke_4 : 196 -> 224
CStrings:
+ "Hit testing for Dwell Control, so only elements it can highlight are eligible"
```
