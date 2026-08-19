## Safari

> `/System/Library/PrivateFrameworks/Safari.framework/Versions/A/Safari`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-625.1.29.11.2
-  __TEXT.__text: 0x7ebba4
-  __TEXT.__objc_methlist: 0x5e0fc
+625.1.29.11.24
+  __TEXT.__text: 0x7ec81c
+  __TEXT.__objc_methlist: 0x5e134
   __TEXT.__cstring: 0x45da8
-  __TEXT.__gcc_except_tab: 0xcfbf8
+  __TEXT.__gcc_except_tab: 0xcfde0
   __TEXT.__const: 0xa8e8
   __TEXT.__ustring: 0x11390
   __TEXT.__oslogstring: 0x2439c

   __TEXT.__swift_as_cont: 0x1c8
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_mpenum: 0x10
-  __TEXT.__unwind_info: 0x3ee60
+  __TEXT.__unwind_info: 0x3eef8
   __TEXT.__eh_frame: 0x3230
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_nlcatlist: 0x8
   __DATA_CONST.__objc_protolist: 0x1258
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x33e10
+  __DATA_CONST.__objc_selrefs: 0x33e50
   __DATA_CONST.__objc_protorefs: 0x2d0
   __DATA_CONST.__objc_superrefs: 0x1958
   __DATA_CONST.__objc_arraydata: 0xc28
-  __DATA_CONST.__got: 0x4ac0
+  __DATA_CONST.__got: 0x4ac8
   __AUTH_CONST.__const: 0x20b78
   __AUTH_CONST.__cfstring: 0x38de0
-  __AUTH_CONST.__objc_const: 0x89ba8
+  __AUTH_CONST.__objc_const: 0x89ca8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x14d0
   __AUTH_CONST.__objc_dictobj: 0x5f0

   __AUTH_CONST.__auth_got: 0x4028
   __AUTH.__objc_data: 0x101b8
   __AUTH.__data: 0x1e80
-  __DATA.__objc_ivar: 0x65b0
+  __DATA.__objc_ivar: 0x65d0
   __DATA.__data: 0xfd70
   __DATA.__objc_stublist: 0x20
   __DATA.__bss: 0x56d0

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 41714
-  Symbols:   83593
+  Functions: 41725
+  Symbols:   83620
   CStrings:  10998
 
Symbols:
+ -[BrowserWindowController _canCloseTabsWithoutClosingWindow:]
+ -[CombinedFavoritesController _sendPendingFavoritesContentsChange]
+ -[ReadingListDataStore _bookmarksDidChange:]
+ -[ReadingListDataStore _bookmarksWereAddedOrRemoved:]
+ -[StartPageCollectionViewController _applyPendingDiffableSnapshotRebuildIfNeeded]
+ -[StartPageCollectionViewController _setNeedsRebuildAndApplyDiffableSnapshotAnimatingDifferences:]
+ -[StartPageReadingListSectionProvider _reloadCachedReadingListItems]
+ GCC_except_table1202
+ GCC_except_table1249
+ GCC_except_table1268
+ GCC_except_table1287
+ GCC_except_table1310
+ GCC_except_table1316
+ GCC_except_table1337
+ GCC_except_table1339
+ GCC_except_table1353
+ GCC_except_table1399
+ GCC_except_table1404
+ GCC_except_table1407
+ GCC_except_table1413
+ GCC_except_table1425
+ GCC_except_table1442
+ GCC_except_table1472
+ GCC_except_table1484
+ GCC_except_table1487
+ GCC_except_table1493
+ GCC_except_table1498
+ GCC_except_table1503
+ GCC_except_table1506
+ GCC_except_table1511
+ GCC_except_table1515
+ GCC_except_table1528
+ GCC_except_table1532
+ GCC_except_table1536
+ GCC_except_table1554
+ GCC_except_table1563
+ GCC_except_table1572
+ GCC_except_table1574
+ GCC_except_table1579
+ GCC_except_table1589
+ GCC_except_table1592
+ GCC_except_table1595
+ GCC_except_table1602
+ GCC_except_table1604
+ GCC_except_table1613
+ GCC_except_table1615
+ GCC_except_table1622
+ GCC_except_table1628
+ GCC_except_table1630
+ GCC_except_table1634
+ GCC_except_table1637
+ GCC_except_table1639
+ GCC_except_table1643
+ GCC_except_table1658
+ GCC_except_table1680
+ GCC_except_table1682
+ GCC_except_table1698
+ GCC_except_table1709
+ GCC_except_table1712
+ GCC_except_table1716
+ GCC_except_table1718
+ GCC_except_table1723
+ GCC_except_table1730
+ GCC_except_table1736
+ GCC_except_table1741
+ GCC_except_table1743
+ GCC_except_table1753
+ GCC_except_table1763
+ OBJC_IVAR_$_CombinedFavoritesController._pendingFavoritesContentsChange
+ OBJC_IVAR_$_CombinedFavoritesController._pendingFavoritesContentsChangeHasMultipleModifiedBookmarks
+ OBJC_IVAR_$_CombinedFavoritesController._pendingFavoritesContentsChangeModifiedBookmark
+ OBJC_IVAR_$_ReadingListDataStore._pendingItemsUpdate
+ OBJC_IVAR_$_StartPageCollectionViewController._isApplyingDiffableSnapshot
+ OBJC_IVAR_$_StartPageCollectionViewController._pendingDiffableSnapshotRebuildAnimatesDifferences
+ OBJC_IVAR_$_StartPageCollectionViewController._pendingSnapshotRebuild
+ OBJC_IVAR_$_StartPageReadingListSectionProvider._pendingItemsReload
+ _OBJC_CLASS_$_WBSRunLoopCoalescedUpdate
+ __73-[CombinedFavoritesController initWithTouchIconCache:topSitesController:]_block_invoke
+ __ZL27bookmarkIsReadingListFolderP17SafariWebBookmark
+ ___44-[ReadingListDataStore initWithStoredTitle:]_block_invoke
+ ___61-[StartPageCollectionViewController _setupDiffableDataSource]_block_invoke_2
+ ___65-[StartPageReadingListSectionProvider initWithCompactAppearance:]_block_invoke
+ ___66-[CombinedFavoritesController _sendPendingFavoritesContentsChange]_block_invoke
+ _objc_msgSend$_applyPendingDiffableSnapshotRebuildIfNeeded
+ _objc_msgSend$_canCloseTabsWithoutClosingWindow:
+ _objc_msgSend$_reloadCachedReadingListItems
+ _objc_msgSend$_sendPendingFavoritesContentsChange
+ _objc_msgSend$_setNeedsRebuildAndApplyDiffableSnapshotAnimatingDifferences:
+ _objc_msgSend$isScheduled
+ _objc_msgSend$performIfScheduled
+ _objc_msgSend$schedule
- -[ReadingListDataStore _readingListModelDataDidChange:]
- GCC_except_table1203
- GCC_except_table1208
- GCC_except_table1221
- GCC_except_table1224
- GCC_except_table1236
- GCC_except_table1242
- GCC_except_table1246
- GCC_except_table1251
- GCC_except_table1278
- GCC_except_table1312
- GCC_except_table1335
- GCC_except_table1351
- GCC_except_table1354
- GCC_except_table1366
- GCC_except_table1402
- GCC_except_table1430
- GCC_except_table1447
- GCC_except_table1460
- GCC_except_table1483
- GCC_except_table1485
- GCC_except_table1492
- GCC_except_table1494
- GCC_except_table1499
- GCC_except_table1504
- GCC_except_table1508
- GCC_except_table1512
- GCC_except_table1519
- GCC_except_table1529
- GCC_except_table1534
- GCC_except_table1537
- GCC_except_table1555
- GCC_except_table1565
- GCC_except_table1573
- GCC_except_table1575
- GCC_except_table1582
- GCC_except_table1590
- GCC_except_table1593
- GCC_except_table1596
- GCC_except_table1603
- GCC_except_table1606
- GCC_except_table1614
- GCC_except_table1616
- GCC_except_table1623
- GCC_except_table1629
- GCC_except_table1632
- GCC_except_table1635
- GCC_except_table1638
- GCC_except_table1640
- GCC_except_table1644
- GCC_except_table1661
- GCC_except_table1681
- GCC_except_table1683
- GCC_except_table1701
- GCC_except_table1704
- GCC_except_table1708
- GCC_except_table1711
- GCC_except_table1717
- GCC_except_table1719
- GCC_except_table1725
- GCC_except_table1731
- GCC_except_table1742
- GCC_except_table1758
- ___77-[CombinedFavoritesController _favoritesContentsChangedWithModifiedBookmark:]_block_invoke
CStrings:
+ "Q\xf0\xf0\xf0!3"
- "Q\xf0\xf0\xf13"
```
