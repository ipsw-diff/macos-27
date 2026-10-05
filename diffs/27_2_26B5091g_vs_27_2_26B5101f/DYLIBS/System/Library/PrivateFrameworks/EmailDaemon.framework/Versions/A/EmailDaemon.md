## EmailDaemon

> `/System/Library/PrivateFrameworks/EmailDaemon.framework/Versions/A/EmailDaemon`

```diff

-3901.200.41.0.0
-  __TEXT.__text: 0x2b9384
-  __TEXT.__objc_methlist: 0x1376c
-  __TEXT.__const: 0x538c
-  __TEXT.__gcc_except_tab: 0x4b4b0
-  __TEXT.__cstring: 0x2892a
-  __TEXT.__oslogstring: 0x1b3b4
+3901.200.66.1.3
+  __TEXT.__text: 0x2bafac
+  __TEXT.__objc_methlist: 0x137ec
+  __TEXT.__const: 0x53bc
+  __TEXT.__gcc_except_tab: 0x4b59c
+  __TEXT.__cstring: 0x28a5a
+  __TEXT.__oslogstring: 0x1b434
   __TEXT.__dlopen_cstrs: 0x3bc
   __TEXT.__ustring: 0x26
-  __TEXT.__swift5_typeref: 0x1822
+  __TEXT.__swift5_typeref: 0x186e
   __TEXT.__constg_swiftt: 0x1104
   __TEXT.__swift5_builtin: 0x12c
   __TEXT.__swift5_reflstr: 0x114f

   __TEXT.__swift5_assocty: 0x260
   __TEXT.__swift5_proto: 0x3a4
   __TEXT.__swift5_types: 0x1dc
-  __TEXT.__swift5_capture: 0x840
+  __TEXT.__swift5_capture: 0x85c
   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift_as_entry: 0x40
   __TEXT.__swift_as_ret: 0x48
   __TEXT.__swift_as_cont: 0x60
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__unwind_info: 0x127d0
+  __TEXT.__unwind_info: 0x12860
   __TEXT.__eh_frame: 0x15d0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__const: 0x1bb0
   __DATA_CONST.__objc_classlist: 0x9f8
   __DATA_CONST.__objc_catlist: 0x58
-  __DATA_CONST.__objc_protolist: 0x438
+  __DATA_CONST.__objc_protolist: 0x458
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb3a0
-  __DATA_CONST.__objc_protorefs: 0x120
+  __DATA_CONST.__objc_selrefs: 0xb3c8
+  __DATA_CONST.__objc_protorefs: 0x138
   __DATA_CONST.__objc_superrefs: 0x5f0
   __DATA_CONST.__objc_arraydata: 0x610
   __DATA_CONST.__got: 0x1e70
-  __AUTH_CONST.__const: 0x1040b
-  __AUTH_CONST.__cfstring: 0xfae0
-  __AUTH_CONST.__objc_const: 0x22b00
+  __AUTH_CONST.__const: 0x1045b
+  __AUTH_CONST.__cfstring: 0xfb20
+  __AUTH_CONST.__objc_const: 0x22bd0
   __AUTH_CONST.__objc_intobj: 0x9f0
   __AUTH_CONST.__objc_arrayobj: 0x2b8
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x1660
+  __AUTH_CONST.__auth_got: 0x1668
   __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0x14b8
-  __DATA.__data: 0xcb0
+  __DATA.__objc_ivar: 0x14c4
+  __DATA.__data: 0xd30
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x66c0
   __DATA.__common: 0x8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11751
-  Symbols:   20518
-  CStrings:  5480
+  Functions: 11772
+  Symbols:   20548
+  CStrings:  5487
 
Symbols:
+ +[EDFoundationModelContextGenerator originalContentMessageForMessage:limitOfInReplyToAncestors:condenseEmptyLines:messagePersistence:htmlStringFromMessage:error:]
+ -[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:options:completionPromise:]
+ -[EDDiagnosticInfoGatherer _shouldCollectIndexingDiagnostics:]
+ -[EDMessageChangeManager hasCompletedInitialSyncForMailboxURL:]
+ -[EDPersistenceDatabaseConnection rowIDPropertyForKey:]
+ -[EDPersistenceDatabaseConnection selectLowestUnresolvedAttachmentID]
+ -[EDPersistenceDatabaseConnection setLowestUnresolvedAttachmentID:]
+ -[EDPersistenceDatabaseConnection setRowIDProperty:forKey:]
+ -[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]
+ -[EDSearchableIndexPersistence _noteLowestUnresolvedAttachmentID:]
+ -[EDSearchableIndexPersistence _rewindAttachmentScanToRetryUnresolvedAttachments]
+ -[EDSearchableIndexPersistence lowestUnresolvedAttachmentID]
+ -[EDSearchableIndexPersistence setLowestUnresolvedAttachmentID:]
+ OBJC_IVAR_$_EDSearchableIndexPersistence._lastAttachmentScanRewindDate
+ OBJC_IVAR_$_EDSearchableIndexPersistence._lowestUnresolvedAttachmentID
+ OBJC_IVAR_$_EDSearchableIndexPersistence._lowestUnresolvedAttachmentIDLock
+ __103-[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:options:completionPromise:]_block_invoke
+ __143-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_EDMessageChangeManager(Swift)
+ __OBJC_$_PROP_LIST_EDServerSyncedMessage
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_EDServerSyncedMessage
+ __OBJC_$_PROTOCOL_METHOD_TYPES_EDServerSyncedMessage
+ __OBJC_$_PROTOCOL_REFS_EDServerSyncedMessage
+ __OBJC_LABEL_PROTOCOL_$_EDServerSyncedMessage
+ __OBJC_PROTOCOL_$_EDServerSyncedMessage
+ ___103-[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:options:completionPromise:]_block_invoke
+ ___143-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]_block_invoke
+ ___162+[EDFoundationModelContextGenerator originalContentMessageForMessage:limitOfInReplyToAncestors:condenseEmptyLines:messagePersistence:htmlStringFromMessage:error:]_block_invoke
+ ___60-[EDSearchableIndexPersistence lowestUnresolvedAttachmentID]_block_invoke
+ ___64-[EDSearchableIndexPersistence setLowestUnresolvedAttachmentID:]_block_invoke
+ ___85-[EDPersistenceDatabaseConnection(EDSearchableIndexPersistence) rowIDPropertyForKey:]_block_invoke
+ ___block_descriptor_72_ea8_32s40s48s56s64r_e53_v20?0"EDSearchableIndexAttachmentItemMetadatum"8B16l
+ _flat unique So21EDServerSyncedMessage_p
+ _objc_msgSend$_attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:
+ _objc_msgSend$_copyIndexingDiagnosticsDatabaseIntoDirectoryURL:options:completionPromise:
+ _objc_msgSend$_noteLowestUnresolvedAttachmentID:
+ _objc_msgSend$_rewindAttachmentScanToRetryUnresolvedAttachments
+ _objc_msgSend$_shouldCollectIndexingDiagnostics:
+ _objc_msgSend$hasCompletedInitialSyncForMailboxURL:
+ _objc_msgSend$lowestUnresolvedAttachmentID
+ _objc_msgSend$reportNewMessageLatency:mailboxURL:
+ _objc_msgSend$setLowestUnresolvedAttachmentID:
+ _swift_dynamicCastObjCProtocolConditional
+ _symbolic Say______pG So21EDServerSyncedMessageP
+ _symbolic So22EDMessageChangeManagerC
+ _symbolic ______p So21EDServerSyncedMessageP
- +[EDFoundationModelContextGenerator originalContentMessageForMessage:limitOfInReplyToAncestors:checkForForwardedMessages:condenseEmptyLines:messagePersistence:htmlStringFromMessage:error:]
- -[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:completionPromise:]
- -[EDDiagnosticInfoGatherer _shouldCollectIndexingDiagnostics]
- -[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]
- __90-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]_block_invoke
- __95-[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:completionPromise:]_block_invoke
- __OBJC_$_INSTANCE_METHODS_EDMessageChangeManager
- ___188+[EDFoundationModelContextGenerator originalContentMessageForMessage:limitOfInReplyToAncestors:checkForForwardedMessages:condenseEmptyLines:messagePersistence:htmlStringFromMessage:error:]_block_invoke
- ___90-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]_block_invoke
- ___95-[EDDiagnosticInfoGatherer _copyIndexingDiagnosticsDatabaseIntoDirectoryURL:completionPromise:]_block_invoke
- ___96-[EDPersistenceDatabaseConnection(EDSearchableIndexPersistence) selectLastProcessedAttachmentID]_block_invoke
- ___block_descriptor_64_ea8_32s40s48s56s_e53_v20?0"EDSearchableIndexAttachmentItemMetadatum"8B16l
- _objc_msgSend$_attachmentItemsFromAttachmentData:limit:cancelationToken:
- _objc_msgSend$_copyIndexingDiagnosticsDatabaseIntoDirectoryURL:completionPromise:
- _objc_msgSend$_shouldCollectIndexingDiagnostics
- _objc_msgSend$hasForwardPrefix
CStrings:
+ "-[EDMessageChangeManager hasCompletedInitialSyncForMailboxURL:]"
+ "-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:lastVisitedAttachmentID:lowestUnresolvedAttachmentID:cancelationToken:]"
+ "-[EDSearchableIndexPersistence lowestUnresolvedAttachmentID]"
+ "-[EDSearchableIndexPersistence setLowestUnresolvedAttachmentID:]"
+ "DELETE FROM properties WHERE key = :key"
+ "Reached the end of the attachment table, rewinding indexing cursor to %lld to retry attachments whose data was missing"
+ "Selecting %@ property"
+ "Setting %@ property"
+ "com.apple.mail.IMAP.newMessageLatency"
+ "com.apple.mail.searchableIndex.lowestUnresolvedAttachmentIDKey"
+ "\xb1"
- "-[EDSearchableIndexPersistence _attachmentItemsFromAttachmentData:limit:cancelationToken:]"
- "Replying to forwarded message, failed to generate any original-content messages"
- "Setting latest value for lastProcessAttachmentID"
- "\x81"
```
