## Mail

> `/System/Library/PrivateFrameworks/Mail.framework/Versions/A/Mail`

```diff

-3901.200.41.0.0
-  __TEXT.__text: 0xa130a8
-  __TEXT.__objc_methlist: 0x198fc
-  __TEXT.__const: 0x61819
-  __TEXT.__cstring: 0x32039
-  __TEXT.__gcc_except_tab: 0x4c41c
-  __TEXT.__oslogstring: 0x22359
+3901.200.66.1.3
+  __TEXT.__text: 0xa16f70
+  __TEXT.__objc_methlist: 0x199b4
+  __TEXT.__const: 0x61b59
+  __TEXT.__cstring: 0x329b9
+  __TEXT.__gcc_except_tab: 0x4c800
+  __TEXT.__oslogstring: 0x22389
   __TEXT.__ustring: 0x44
-  __TEXT.__swift5_typeref: 0xe780
-  __TEXT.__constg_swiftt: 0xbc64
-  __TEXT.__swift5_reflstr: 0xe770
-  __TEXT.__swift5_fieldmd: 0x131fc
+  __TEXT.__swift5_typeref: 0xe7f4
+  __TEXT.__constg_swiftt: 0xbce8
+  __TEXT.__swift5_reflstr: 0xe820
+  __TEXT.__swift5_fieldmd: 0x13304
   __TEXT.__swift5_builtin: 0xc44
-  __TEXT.__swift5_assocty: 0x1b70
-  __TEXT.__swift5_proto: 0x224c
-  __TEXT.__swift5_types: 0x1518
-  __TEXT.__swift5_capture: 0x26020
+  __TEXT.__swift5_assocty: 0x1bb8
+  __TEXT.__swift5_proto: 0x2270
+  __TEXT.__swift5_types: 0x1524
+  __TEXT.__swift5_capture: 0x26040
   __TEXT.__swift5_mpenum: 0x768
   __TEXT.__swift5_protos: 0x60
-  __TEXT.__unwind_info: 0x2da60
-  __TEXT.__eh_frame: 0x15fb0
+  __TEXT.__unwind_info: 0x2dbc8
+  __TEXT.__eh_frame: 0x160a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protolist: 0x5a0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0xe0a8
+  __DATA_CONST.__objc_selrefs: 0xe108
   __DATA_CONST.__objc_protorefs: 0x1d0
   __DATA_CONST.__objc_superrefs: 0x840
   __DATA_CONST.__objc_arraydata: 0x270
-  __DATA_CONST.__got: 0x3790
-  __AUTH_CONST.__const: 0x8a6b8
-  __AUTH_CONST.__cfstring: 0x1a660
-  __AUTH_CONST.__objc_const: 0x2b248
+  __DATA_CONST.__got: 0x37a0
+  __AUTH_CONST.__const: 0x8a8e8
+  __AUTH_CONST.__cfstring: 0x1a7c0
+  __AUTH_CONST.__objc_const: 0x2b2b8
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0xd08
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x270
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_floatobj: 0x20
-  __AUTH_CONST.__auth_got: 0x3490
+  __AUTH_CONST.__auth_got: 0x34d8
   __AUTH.__objc_data: 0x6298
   __AUTH.__data: 0xa130
   __DATA.__objc_ivar: 0x162c
-  __DATA.__data: 0xc7bc
+  __DATA.__data: 0xc81c
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x43ba8
+  __DATA.__bss: 0x44028
   __DATA.__common: 0xdbc
   __DATA_DIRTY.__objc_data: 0x25d0
   __DATA_DIRTY.__data: 0x10

   - /usr/lib/swift/libswift_DarwinFoundation2.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 42871
-  Symbols:   28661
-  CStrings:  7750
+  Functions: 42940
+  Symbols:   28705
+  CStrings:  7787
 
Symbols:
+ -[MFAccount displayNameWithoutPII]
+ -[MFExchangeAccount _graphIDFromEWSID:]
+ -[MFExchangeAccount _migrateFolderId:toGraphFolderId:forMailbox:]
+ -[MFExchangeAccount migrateFolderIDForMailbox:]
+ -[MFExchangeAccount migrateMessageIDsForMailbox:]
+ -[MFExchangeAccount migrateRootFolderID]
+ -[MFIMAPAccount initialSyncCompletedForMailbox:]
+ -[MFLibrary associatedEventIDsForMessageID:]
+ -[MFLibrary migrateEWSFolderId:toGraphFolderId:]
+ -[MFLibrary remoteIDsForMailbox:batchSize:lastRowID:]
+ -[MFLibrary setAssociatedEventID:forRowID:]
+ -[MFLibrary setRemoteID:forRowID:]
+ -[MFMessageChangeManager_macOS hasCompletedInitialSyncForMailboxURL:]
+ GCC_except_table228
+ GCC_except_table276
+ GCC_except_table321
+ GCC_except_table348
+ GCC_except_table353
+ GCC_except_table356
+ GCC_except_table360
+ GCC_except_table364
+ GCC_except_table365
+ GCC_except_table381
+ GCC_except_table382
+ GCC_except_table390
+ GCC_except_table391
+ GCC_except_table392
+ GCC_except_table400
+ GCC_except_table403
+ GCC_except_table404
+ GCC_except_table405
+ GCC_except_table408
+ GCC_except_table412
+ GCC_except_table413
+ GCC_except_table440
+ GCC_except_table445
+ GCC_except_table453
+ GCC_except_table454
+ GCC_except_table456
+ GCC_except_table457
+ GCC_except_table458
+ GCC_except_table459
+ GCC_except_table460
+ GCC_except_table461
+ GCC_except_table462
+ GCC_except_table473
+ GCC_except_table474
+ GCC_except_table475
+ GCC_except_table495
+ GCC_except_table503
+ GCC_except_table509
+ GCC_except_table511
+ GCC_except_table512
+ GCC_except_table514
+ ___34-[MFLibrary setRemoteID:forRowID:]_block_invoke
+ ___43-[MFLibrary setAssociatedEventID:forRowID:]_block_invoke
+ ___44-[MFLibrary associatedEventIDsForMessageID:]_block_invoke
+ ___48-[MFLibrary migrateEWSFolderId:toGraphFolderId:]_block_invoke
+ ___53-[MFLibrary remoteIDsForMailbox:batchSize:lastRowID:]_block_invoke
+ ___block_descriptor_64_ea8_32s40r_e41_B16?0"EDPersistenceDatabaseConnection"8l
+ _associated conformance So17MFExchangeMessageC4MailE0B6Status33_51905892CF2471EB373F9E70C1539825LLOSHACSQ
+ _associated conformance So17MFExchangeMessageC4MailE12FollowupIcon33_51905892CF2471EB373F9E70C1539825LLOSHACSQ
+ _associated conformance So17MFExchangeMessageC4MailE16LastVerbExecuted33_51905892CF2471EB373F9E70C1539825LLOSHACSQ
+ _objc_msgSend$_graphIDFromEWSID:
+ _objc_msgSend$_migrateFolderId:toGraphFolderId:forMailbox:
+ _objc_msgSend$associatedEventIDsForMessageID:
+ _objc_msgSend$initialSyncCompletedForMailbox:
+ _objc_msgSend$isGraphSyncAuthError:
+ _objc_msgSend$migrateEWSFolderId:toGraphFolderId:
+ _objc_msgSend$remoteIDsForMailbox:batchSize:lastRowID:
+ _objc_msgSend$setAssociatedEventID:forRowID:
+ _objc_msgSend$setRemoteID:forRowID:
+ _symbolic SDySS_____G 9GraphSync0aB41SingleValueLegacyExtendedPropertyResourceV
+ _symbolic SS______t 9GraphSync0aB41SingleValueLegacyExtendedPropertyResourceV
+ _symbolic Say_____G 9GraphSync0aB41SingleValueLegacyExtendedPropertyResourceV
+ _symbolic So17MFExchangeMessageC
+ _symbolic _____ So17MFExchangeMessageC4MailE0B6Status33_51905892CF2471EB373F9E70C1539825LLO
+ _symbolic _____ So17MFExchangeMessageC4MailE12FollowupIcon33_51905892CF2471EB373F9E70C1539825LLO
+ _symbolic _____ So17MFExchangeMessageC4MailE16LastVerbExecuted33_51905892CF2471EB373F9E70C1539825LLO
+ _symbolic _____Sg 9GraphSync0aB41SingleValueLegacyExtendedPropertyResourceV
+ _symbolic _____ySay_____GG s16IndexingIteratorV 9GraphSync0cD41SingleValueLegacyExtendedPropertyResourceV
- -[MFIMAPAccount _initialSyncCompletedForMailbox:]
- GCC_except_table206
- GCC_except_table247
- GCC_except_table257
- GCC_except_table282
- GCC_except_table351
- GCC_except_table358
- GCC_except_table359
- GCC_except_table362
- GCC_except_table366
- GCC_except_table370
- GCC_except_table384
- GCC_except_table387
- GCC_except_table388
- GCC_except_table395
- GCC_except_table396
- GCC_except_table397
- GCC_except_table398
- GCC_except_table406
- GCC_except_table414
- GCC_except_table415
- GCC_except_table416
- GCC_except_table417
- GCC_except_table418
- GCC_except_table419
- GCC_except_table450
- GCC_except_table463
- GCC_except_table464
- GCC_except_table465
- GCC_except_table485
- GCC_except_table493
- GCC_except_table499
- GCC_except_table501
- GCC_except_table502
- GCC_except_table504
- _objc_msgSend$_initialSyncCompletedForMailbox:
- _symbolic Spy_____SgG 9IMAP2MIME8BoundaryV
CStrings:
+ "-[MFLibrary associatedEventIDsForMessageID:]"
+ "-[MFLibrary migrateEWSFolderId:toGraphFolderId:]"
+ "-[MFLibrary remoteIDsForMailbox:batchSize:lastRowID:]"
+ "-[MFLibrary setAssociatedEventID:forRowID:]"
+ "-[MFLibrary setRemoteID:forRowID:]"
+ "Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageJunkFlag"
+ "Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageJunkRecordedFlag"
+ "Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageNotJunkFlag"
+ "Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageRedirectedFlag"
+ "Integer 0x1081"
+ "Integer 0x1095"
+ "Integer 0xE17"
+ "Long 0xE08"
+ "SELECT ROWID, associated_id_string FROM events WHERE message_id = ?"
+ "SELECT ROWID, remote_id FROM messages WHERE ROWID > ? AND mailbox = (SELECT ROWID FROM mailboxes WHERE url = ?) AND deleted = 0 AND remote_id NOTNULL ORDER BY ROWID LIMIT ?"
+ "UPDATE events SET associated_id_string = ? WHERE ROWID = ?"
+ "UPDATE ews_folders SET folder_id = ?, sync_state = NULL WHERE folder_id = ?"
+ "UPDATE messages SET remote_id = ? WHERE ROWID = ?"
+ "Unexpected meeting message type %s"
+ "enumerating event IDs for message"
+ "enumerating remote IDs for mailbox"
+ "flag"
+ "hasAttachments"
+ "importance"
+ "internetMessageHeaders"
+ "internetMessageId"
+ "isDraft"
+ "isRead"
+ "microsoft.graph.eventMessage/meetingMessageType"
+ "migrating EWS folder ID to Graph"
+ "receivedDateTime"
+ "replyTo"
+ "sentDateTime"
+ "singleValueExtendedProperties($filter=id eq 'Long 0x0E08' or id eq 'Integer 0x0E17' or id eq 'Integer 0x1095' or id eq 'Integer 0x1081' or id eq 'Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageJunkFlag' or id eq 'Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageNotJunkFlag' or id eq 'Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageJunkRecordedFlag' or id eq 'Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageRedirectedFlag')"
+ "singleValueExtendedProperties($filter=id eq 'Long 0x0E08' or id eq 'String 0x1039' or id eq 'Integer 0x0E17' or id eq 'Integer 0x1095' or id eq 'Integer 0x1081' or id eq 'Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageJunkFlag' or id eq 'Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageNotJunkFlag' or id eq 'Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageJunkRecordedFlag' or id eq 'Boolean {A7B529B5-4B75-47A7-A24F-20743D6C55CD} Name MessageRedirectedFlag')"
+ "updating associated_id_string for event"
+ "updating remote ID for message"
```
