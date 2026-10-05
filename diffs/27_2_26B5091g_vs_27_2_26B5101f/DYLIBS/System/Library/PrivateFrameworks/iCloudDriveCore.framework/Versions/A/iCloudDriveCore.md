## iCloudDriveCore

> `/System/Library/PrivateFrameworks/iCloudDriveCore.framework/Versions/A/iCloudDriveCore`

```diff

-5168.40.149.0.1
-  __TEXT.__text: 0x33e38c
-  __TEXT.__objc_methlist: 0x1c3dc
+5168.40.162.0.0
+  __TEXT.__text: 0x33e428
+  __TEXT.__objc_methlist: 0x1c3c4
   __TEXT.__const: 0x4f8
-  __TEXT.__cstring: 0x84ea5
-  __TEXT.__oslogstring: 0x40047
-  __TEXT.__gcc_except_tab: 0x17f90
+  __TEXT.__cstring: 0x85267
+  __TEXT.__oslogstring: 0x40031
+  __TEXT.__gcc_except_tab: 0x17f94
   __TEXT.__ustring: 0x36
-  __TEXT.__unwind_info: 0xd930
+  __TEXT.__unwind_info: 0xd940
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2040
+  __DATA_CONST.__const: 0x20c0
   __DATA_CONST.__objc_classlist: 0xae0
   __DATA_CONST.__objc_catlist: 0xd8
   __DATA_CONST.__objc_protolist: 0x2b8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf468
+  __DATA_CONST.__objc_selrefs: 0xf460
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x960
   __DATA_CONST.__objc_arraydata: 0xfd8
   __DATA_CONST.__got: 0x1810
-  __AUTH_CONST.__const: 0xbf38
-  __AUTH_CONST.__cfstring: 0x240e0
-  __AUTH_CONST.__objc_const: 0x422d8
+  __AUTH_CONST.__const: 0xbf98
+  __AUTH_CONST.__cfstring: 0x24100
+  __AUTH_CONST.__objc_const: 0x422f8
   __AUTH_CONST.__objc_intobj: 0xc30
   __AUTH_CONST.__objc_arrayobj: 0x348
   __AUTH_CONST.__objc_dictobj: 0xf0

   __AUTH_CONST.__auth_got: 0xd18
   __AUTH.__objc_data: 0x2738
   __AUTH.__data: 0x38
-  __DATA.__objc_ivar: 0x2078
+  __DATA.__objc_ivar: 0x207c
   __DATA.__data: 0x29a8
   __DATA.__bss: 0x238
   __DATA_DIRTY.__objc_data: 0x4588

   - /usr/lib/libprequelite.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 14624
-  Symbols:   25571
-  CStrings:  12401
+  Functions: 14626
+  Symbols:   25575
+  CStrings:  12407
 
Symbols:
+ -[BRCFetchRecordSubResourcesHandler saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:shareIDsFromDeltaSync:]
+ -[BRCFetchRecordSubResourcesOperation addRecord:fromDeltaSync:]
+ -[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:fromDeltaSync:]
+ -[BRCServerZone _saveEditedRecord:zonesNeedingAllocRanks:fromDeltaSync:error:]
+ -[BRCServerZone _saveEditedShareRecord:fromDeltaSync:error:]
+ -[BRCServerZone _saveEditedShareRecords:deletedShareRecordIDs:zonesNeedingAllocRanks:shareIDsFromDeltaSync:]
+ -[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:fromDeltaSync:]
+ -[BRCServerZone _sendApprovedNotificationIfNeededWithShare:fromDeltaSync:]
+ -[BRCServerZone _shouldSendRequestForAccessNotificationFromDeltaSync:]
+ -[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:shareIDsFromDeltaSync:]
+ GCC_except_table110
+ GCC_except_table113
+ GCC_except_table123
+ GCC_except_table129
+ GCC_except_table132
+ GCC_except_table137
+ GCC_except_table175
+ GCC_except_table186
+ GCC_except_table194
+ GCC_except_table199
+ GCC_except_table206
+ GCC_except_table216
+ GCC_except_table219
+ GCC_except_table234
+ GCC_except_table241
+ GCC_except_table244
+ GCC_except_table249
+ GCC_except_table254
+ GCC_except_table265
+ GCC_except_table268
+ GCC_except_table272
+ GCC_except_table281
+ GCC_except_table308
+ GCC_except_table314
+ GCC_except_table323
+ GCC_except_table371
+ GCC_except_table374
+ GCC_except_table377
+ GCC_except_table381
+ GCC_except_table384
+ GCC_except_table387
+ GCC_except_table408
+ GCC_except_table411
+ GCC_except_table427
+ GCC_except_table435
+ GCC_except_table440
+ GCC_except_table446
+ GCC_except_table451
+ GCC_except_table454
+ GCC_except_table464
+ GCC_except_table469
+ GCC_except_table478
+ GCC_except_table485
+ GCC_except_table488
+ GCC_except_table492
+ GCC_except_table495
+ GCC_except_table498
+ GCC_except_table501
+ GCC_except_table504
+ GCC_except_table510
+ GCC_except_table521
+ GCC_except_table525
+ GCC_except_table532
+ GCC_except_table535
+ GCC_except_table541
+ GCC_except_table553
+ GCC_except_table560
+ GCC_except_table92
+ OBJC_IVAR_$_BRCFetchRecordSubResourcesOperation._shareIDsFromDeltaSync
+ __117-[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:fromDeltaSync:]_block_invoke
+ __170-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:shareIDsFromDeltaSync:]_block_invoke
+ __60-[BRCServerZone _saveEditedShareRecord:fromDeltaSync:error:]_block_invoke
+ ___113-[BRCFSUploader transferStreamOfSyncContext:didBecomeReadyWithMaxRecordsCount:sizeHint:priority:completionBlock:]_block_invoke_2
+ ___117-[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:fromDeltaSync:]_block_invoke
+ ___170-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:shareIDsFromDeltaSync:]_block_invoke
+ ___177-[BRCFetchRecordSubResourcesHandler saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:shareIDsFromDeltaSync:]_block_invoke
+ ___60-[BRCServerZone _saveEditedShareRecord:fromDeltaSync:error:]_block_invoke
+ ___74-[BRCServerZone _sendApprovedNotificationIfNeededWithShare:fromDeltaSync:]_block_invoke
+ ___94-[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:fromDeltaSync:]_block_invoke
+ ___block_descriptor_137_e8_32s40s48s56s64s72s80s88s96s104r112r_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_57_e8_32s40s48s_e33_B24?0"CKRecordID"8"CKRecord"16l
+ ___block_descriptor_72_e8_32s40s_e23_B16?0"PQLConnection"8l
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96s104r112r
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s104r112r
+ _objc_msgSend$_populateParticipantsAndSendUserNotificationsIfNeededWithShare:fromDeltaSync:
+ _objc_msgSend$_saveEditedRecord:zonesNeedingAllocRanks:fromDeltaSync:error:
+ _objc_msgSend$_saveEditedShareRecord:fromDeltaSync:error:
+ _objc_msgSend$_saveEditedShareRecords:deletedShareRecordIDs:zonesNeedingAllocRanks:shareIDsFromDeltaSync:
+ _objc_msgSend$_savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:fromDeltaSync:
+ _objc_msgSend$_sendApprovedNotificationIfNeededWithShare:fromDeltaSync:
+ _objc_msgSend$_shouldSendRequestForAccessNotificationFromDeltaSync:
+ _objc_msgSend$addRecord:fromDeltaSync:
+ _objc_msgSend$didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:shareIDsFromDeltaSync:
+ _objc_msgSend$saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:shareIDsFromDeltaSync:
- -[BRCFetchRecordSubResourcesHandler saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:]
- -[BRCFetchRecordSubResourcesOperation addRecord:]
- -[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:]
- -[BRCServerZone _saveEditedRecord:zonesNeedingAllocRanks:error:]
- -[BRCServerZone _saveEditedShareRecord:error:]
- -[BRCServerZone _saveEditedShareRecords:deletedShareRecordIDs:zonesNeedingAllocRanks:]
- -[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:]
- -[BRCServerZone _sendApprovedNotificationIfNeededWithShare:]
- -[BRCServerZone _shouldSendNotification]
- -[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:]
- -[BRCXPCClient _auditURL:]
- -[BRCXPCClient _auditedURLFromPath:]
- GCC_except_table106
- GCC_except_table145
- GCC_except_table155
- GCC_except_table162
- GCC_except_table165
- GCC_except_table172
- GCC_except_table183
- GCC_except_table203
- GCC_except_table210
- GCC_except_table214
- GCC_except_table221
- GCC_except_table226
- GCC_except_table232
- GCC_except_table233
- GCC_except_table236
- GCC_except_table258
- GCC_except_table269
- GCC_except_table276
- GCC_except_table279
- GCC_except_table306
- GCC_except_table318
- GCC_except_table341
- GCC_except_table344
- GCC_except_table349
- GCC_except_table376
- GCC_except_table379
- GCC_except_table383
- GCC_except_table386
- GCC_except_table389
- GCC_except_table410
- GCC_except_table413
- GCC_except_table418
- GCC_except_table432
- GCC_except_table437
- GCC_except_table442
- GCC_except_table448
- GCC_except_table453
- GCC_except_table456
- GCC_except_table466
- GCC_except_table471
- GCC_except_table475
- GCC_except_table480
- GCC_except_table487
- GCC_except_table490
- GCC_except_table494
- GCC_except_table497
- GCC_except_table500
- GCC_except_table503
- GCC_except_table508
- GCC_except_table516
- GCC_except_table523
- GCC_except_table531
- GCC_except_table534
- GCC_except_table537
- GCC_except_table551
- GCC_except_table561
- GCC_except_table562
- __148-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:]_block_invoke
- __46-[BRCServerZone _saveEditedShareRecord:error:]_block_invoke
- ___103-[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:]_block_invoke
- ___103-[BRCServerZone _savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:]_block_invoke_2
- ___148-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:]_block_invoke
- ___155-[BRCFetchRecordSubResourcesHandler saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:]_block_invoke
- ___46-[BRCServerZone _saveEditedShareRecord:error:]_block_invoke
- ___60-[BRCServerZone _sendApprovedNotificationIfNeededWithShare:]_block_invoke
- ___80-[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:]_block_invoke
- ___block_descriptor_129_e8_32s40s48s56s64s72s80s88s96r104r_e23_B16?0"PQLConnection"8l
- ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96r104r
- _objc_msgSend$_auditURL:
- _objc_msgSend$_populateParticipantsAndSendUserNotificationsIfNeededWithShare:
- _objc_msgSend$_saveEditedRecord:zonesNeedingAllocRanks:error:
- _objc_msgSend$_saveEditedShareRecord:error:
- _objc_msgSend$_saveEditedShareRecords:deletedShareRecordIDs:zonesNeedingAllocRanks:
- _objc_msgSend$_savePendingChangesSharesIgnoringRecordIDs:zonesNeedingAllocRanks:pendingChangeStream:
- _objc_msgSend$_sendApprovedNotificationIfNeededWithShare:
- _objc_msgSend$_shouldSendNotification
- _objc_msgSend$didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:
- _objc_msgSend$saveChangedRecords:deletedRecordIDs:deletedShareRecordIDs:clientChangeToken:serverChangeToken:caughtUp:pendingChanges:
CStrings:
+ "-[BRCFetchRecordSubResourcesOperation addRecord:fromDeltaSync:]"
+ "-[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:fromDeltaSync:]"
+ "-[BRCServerZone _saveEditedRecord:zonesNeedingAllocRanks:fromDeltaSync:error:]"
+ "-[BRCServerZone _saveEditedShareRecord:fromDeltaSync:error:]"
+ "-[BRCServerZone _saveEditedShareRecord:fromDeltaSync:error:]_block_invoke"
+ "-[BRCServerZone _shouldSendRequestForAccessNotificationFromDeltaSync:]"
+ "-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:shareIDsFromDeltaSync:]"
+ "-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:shareIDsFromDeltaSync:]_block_invoke"
+ "SELECT COUNT(*) FROM client_items AS ci WHERE ci.item_localsyncupstate != 0   AND ci.item_localsyncupstate IN (2, 3, 4, 7, 8)   AND ci.item_state = 0   AND ci.item_stat_ckinfo IS NULL   AND ci.item_type IN (0, 9, 10)   AND NOT item_id_is_documents(ci.item_id)   AND NOT EXISTS (SELECT 1 FROM client_items AS p                   WHERE p.zone_rowid = ci.zone_rowid                     AND p.item_id = ci.item_parent_id                     AND p.item_localsyncupstate != 0                     AND p.item_localsyncupstate IN (2, 3, 4, 7, 8)                     AND p.item_state = 0                     AND p.item_stat_ckinfo IS NULL)"
+ "[CRIT] UNREACHABLE: %@ is not owning the container whose metadata it is updating%@"
+ "[DEBUG] AppLibrary %@ added to a new zone. Mark special directories as listed + pristine for doc%@"
+ "[ERROR] Found a key that is not of type String%@"
+ "[ERROR] checksum from bookmark is not equal to expected checksum%@"
+ "[WARNING] Can't find appLibrary%@"
+ "crossZoneMoveNeedsSyncUpMoreThan10"
+ "crossZoneMoveNeedsSyncUpMoreThan25"
+ "crossZoneMoveNeedsSyncUpMoreThan50"
+ "nonIdleItemsMoreThan10"
+ "nonIdleItemsMoreThan25"
+ "nonIdleItemsMoreThan50"
+ "tombstoneNeedsSyncUpMoreThan10"
+ "tombstoneNeedsSyncUpMoreThan25"
+ "tombstoneNeedsSyncUpMoreThan50"
+ "uv2MigrationEstimatedReimports"
+ "uv2MigrationEstimatedReimportsMoreThan10"
+ "uv2MigrationEstimatedReimportsMoreThan100"
+ "uv2MigrationEstimatedReimportsMoreThan25"
+ "uv2MigrationEstimatedReimportsMoreThan50"
- "-[BRCFetchRecordSubResourcesOperation addRecord:]"
- "-[BRCServerZone _populateParticipantsAndSendUserNotificationsIfNeededWithShare:]"
- "-[BRCServerZone _saveEditedRecord:zonesNeedingAllocRanks:error:]"
- "-[BRCServerZone _saveEditedShareRecord:error:]"
- "-[BRCServerZone _saveEditedShareRecord:error:]_block_invoke"
- "-[BRCServerZone _shouldSendNotification]"
- "-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:]"
- "-[BRCServerZone didSyncDownRequestID:serverChangeToken:editedRecords:deletedRecordIDs:deletedShareRecordIDs:allocRankZones:caughtUp:pendingChanges:]_block_invoke"
- "-[BRCXPCClient _auditURL:]"
- "-[BRCXPCRegularIPCsClient _removeSandboxedAttributes:]"
- "[CRIT] UNREACHABLE: %@ is not owning %@ and updating its metadata%@"
- "[DEBUG] AppLibrary %@ added to a new zone. Mark as listed all + pristine for doc%@"
- "[ERROR] Client %@ gave us a non-existing fault URL path %@%@"
- "[ERROR] key: %@ is not of class NSString%@"
- "[WARNING] Can't find appLibrary for id %@%@"
- "[WARNING] Stripping attributes request from %@ to %@%@"
- "crossZoneMoveNeedsSyncUpMoreThan1000"
- "crossZoneMoveNeedsSyncUpMoreThan10000"
- "nonIdleItemsMoreThan1000"
- "nonIdleItemsMoreThan10000"
- "tombstoneNeedsSyncUpMoreThan1000"
- "tombstoneNeedsSyncUpMoreThan10000"
```
