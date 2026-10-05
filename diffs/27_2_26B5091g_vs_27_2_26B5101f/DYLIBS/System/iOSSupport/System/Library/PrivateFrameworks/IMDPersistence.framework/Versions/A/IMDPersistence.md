## IMDPersistence

> `/System/iOSSupport/System/Library/PrivateFrameworks/IMDPersistence.framework/Versions/A/IMDPersistence`

```diff

-1491.200.73.0.0
-  __TEXT.__text: 0x2eaee0
-  __TEXT.__objc_methlist: 0xa3b4
-  __TEXT.__const: 0xc198
-  __TEXT.__cstring: 0x5dae4
-  __TEXT.__oslogstring: 0x3bfe4
-  __TEXT.__gcc_except_tab: 0xc664
+1491.200.95.0.0
+  __TEXT.__text: 0x2ec8b0
+  __TEXT.__objc_methlist: 0xa4a4
+  __TEXT.__const: 0xc188
+  __TEXT.__cstring: 0x5eb54
+  __TEXT.__oslogstring: 0x3be74
+  __TEXT.__gcc_except_tab: 0xc4ec
   __TEXT.__ustring: 0x434
   __TEXT.__dlopen_cstrs: 0x21a
-  __TEXT.__swift5_typeref: 0x5190
-  __TEXT.__swift5_capture: 0x1f0c
-  __TEXT.__constg_swiftt: 0x5868
+  __TEXT.__swift5_typeref: 0x51b2
+  __TEXT.__swift5_capture: 0x1f5c
+  __TEXT.__constg_swiftt: 0x58a4
   __TEXT.__swift5_builtin: 0x348
   __TEXT.__swift5_reflstr: 0x3819
   __TEXT.__swift5_fieldmd: 0x365c

   __TEXT.__swift5_proto: 0x4bc
   __TEXT.__swift5_types: 0x388
   __TEXT.__swift5_protos: 0x4c
-  __TEXT.__swift_as_entry: 0x144
-  __TEXT.__swift_as_ret: 0x170
-  __TEXT.__swift_as_cont: 0x364
+  __TEXT.__swift_as_entry: 0x14c
+  __TEXT.__swift_as_ret: 0x174
+  __TEXT.__swift_as_cont: 0x374
   __TEXT.__swift5_mpenum: 0x44
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xd410
-  __TEXT.__eh_frame: 0x992c
+  __TEXT.__unwind_info: 0xd4b0
+  __TEXT.__eh_frame: 0x99e4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x64c0
-  __DATA_CONST.__objc_classlist: 0x6c8
+  __DATA_CONST.__const: 0x64e0
+  __DATA_CONST.__objc_classlist: 0x6d8
   __DATA_CONST.__objc_catlist: 0x40
-  __DATA_CONST.__objc_protolist: 0x300
+  __DATA_CONST.__objc_protolist: 0x310
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6ab8
+  __DATA_CONST.__objc_selrefs: 0x6af0
   __DATA_CONST.__objc_protorefs: 0x138
   __DATA_CONST.__objc_superrefs: 0x228
   __DATA_CONST.__objc_arraydata: 0x2c0
-  __DATA_CONST.__got: 0x1bc0
-  __AUTH_CONST.__const: 0xe068
+  __DATA_CONST.__got: 0x1bd0
+  __AUTH_CONST.__const: 0xe130
   __AUTH_CONST.__cfstring: 0x13040
-  __AUTH_CONST.__objc_const: 0x137b0
+  __AUTH_CONST.__objc_const: 0x13a10
   __AUTH_CONST.__objc_intobj: 0x168
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x2900
-  __AUTH.__objc_data: 0xf78
+  __AUTH_CONST.__auth_got: 0x2918
+  __AUTH.__objc_data: 0x1018
   __AUTH.__data: 0x1b80
-  __DATA.__objc_ivar: 0x564
-  __DATA.__data: 0x35a8
-  __DATA.__bss: 0x5e08
+  __DATA.__objc_ivar: 0x568
+  __DATA.__data: 0x36f8
+  __DATA.__bss: 0x5e18
   __DATA.__common: 0x1f8
   __DATA_DIRTY.__objc_data: 0x2ff0
-  __DATA_DIRTY.__data: 0x66e0
+  __DATA_DIRTY.__data: 0x6730
   __DATA_DIRTY.__bss: 0x2ff0
   __DATA_DIRTY.__common: 0x178
   - /System/Library/Frameworks/AppIntents.framework/Versions/A/AppIntents

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13668
-  Symbols:   2845
-  CStrings:  7491
+  Functions: 13722
+  Symbols:   2852
+  CStrings:  7488
 
Symbols:
+ _IMAttachmentPreflightPreviewFileURL
+ _IMCoreSpotlightIndexBehaviorFromReason
+ _IMSharedHelperCurrentRegionForcesFilterUnknownSenders
+ _OBJC_CLASS_$_IMDCoreSpotlightIndexerProvider
+ _OBJC_CLASS_$_IMDCoreSpotlightSearchableItemGeneratorDependencyProvider
+ _OBJC_METACLASS_$_IMDCoreSpotlightIndexerProvider
+ _OBJC_METACLASS_$_IMDCoreSpotlightSearchableItemGeneratorDependencyProvider
CStrings:
+ ")) AND\n        mU.is_finished == 1 AND\n        mU.is_from_me == 0 AND\n        mU.item_type == 0 AND\n        mU.is_system_message == 0\n)"
+ "EXISTS (\n    SELECT 1 FROM chat_message_join cmjU\n    INNER JOIN message mU ON mU.rowid = cmjU.message_id\n    WHERE cmjU.chat_id = c.rowid AND\n        mU.is_read == 0 AND\n        NOT (mU.ROWID in (SELECT message_id FROM "
+ "EXISTS (\n    SELECT 1 FROM chat_part cpU\n    INNER JOIN chat_part_message_join cmjU ON cpU.rowid = cmjU.chat_part_id\n    INNER JOIN message mU ON mU.rowid = cmjU.message_id\n    WHERE cpU.chat_id = c.rowid AND\n        mU.is_read == 0 AND\n        NOT (mU.ROWID in (SELECT message_id FROM "
+ "Filename was null (%@) for file transfer %@ -- did not generate attachment preview"
+ "Final preview unavailable, falling back to preview-stage preview for transfer %{private}@"
+ "INSERT OR IGNORE INTO chat_message_join (chat_id, message_id, message_date, filter_action, filter_sub_action) SELECT ?, ?, ?, ?, ? WHERE NOT EXISTS (SELECT 1 FROM chat_recoverable_message_join WHERE chat_id = ? AND message_id = ?);"
+ "INSERT OR IGNORE INTO chat_part_message_join (chat_part_id, message_id, message_date, filter_action, filter_sub_action)\nSELECT ?, ?, ?, ?, ?\nWHERE NOT EXISTS (SELECT 1 FROM chat_part_recoverable_message_join WHERE chat_part_id = ? AND message_id = ?);"
+ "Not attaching a preview for transfer %@ to the notification (sensitive %{BOOL}d, adaptive image glyph %{BOOL}d, rejected %{BOOL}d); with all three false, no preview was on disk"
+ "PersistentTaskBatchTimeoutSeconds"
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON   a.ROWID = ma.attachment_id INNER JOIN chat_message_join cm ON   ma.message_id = cm.message_id INNER JOIN message m ON   ma.message_id = m.ROWID WHERE   m.cache_has_attachments   AND m.expire_state != %d   AND cm.chat_id IN (%@)   AND a.hide_attachment == 0   AND a.ck_sync_state == 1   AND a.transfer_state == 0 ORDER BY m.date DESC limit %d"
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND (m.balloon_bundle_id IS NULL OR m.balloon_bundle_id != 'com.apple.messages.chatbot') AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND (m.balloon_bundle_id IS NULL OR m.balloon_bundle_id != 'com.apple.messages.chatbot') ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND m.balloon_bundle_id == 'com.apple.messages.chatbot' AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND m.balloon_bundle_id == 'com.apple.messages.chatbot' ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
+ "SELECT a.ROWID, a.guid, a.created_date, a.start_date, a.filename, a.uti, a.mime_type, a.transfer_state, a.is_outgoing, a.user_info, a.transfer_name, a.total_bytes, a.is_sticker, a.sticker_user_info, a.attribution_info, a.hide_attachment, a.ck_sync_state, a.ck_server_change_token_blob, a.ck_record_id, a.original_guid, a.is_commsafety_sensitive, a.emoji_image_content_identifier, a.emoji_image_short_description, a.preview_generation_state, a.preflight_info, a.sensitivity_analysis, a.fields_needing_sync  FROM attachment a WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 ORDER BY a.ROWID LIMIT ? "
- ")) AND\nm.is_finished == 1 AND\nm.is_from_me == 0 AND\nm.item_type == 0 AND\nm.is_system_message == 0"
- "Bailing early from _IMDCoreSpotlightNicknameForAddress: Shared Name and Photo is not enabled"
- "Bailing early from _IMDKVStoreForHandledNicknames: Shared Name and Photo is not enabled"
- "Bailing early from _IMDKVStoreForPendingNicknames: Shared Name and Photo is not enabled"
- "Bailing early from _IMDNicknameInfoForAddress: Shared Name and Photo is not enabled"
- "Bailing early from _IMNicknameInfoForKVStore: Shared Name and Photo is not enabled"
- "Bailing early from _nicknameDisplayNameForID: Shared Name and Photo is not enabled"
- "Filename was null (%@) or transfer state was not finished (%@) for file transfer %@ -- did not generate attachment preview"
- "INSERT OR IGNORE INTO chat_message_join (chat_id, message_id, message_date, filter_action, filter_sub_action) VALUES (?, ?, ?, ?, ?);"
- "INSERT OR IGNORE INTO chat_part_message_join (chat_part_id, message_id, message_date, filter_action, filter_sub_action)\nVALUES (?, ?, ?, ?, ?);"
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON   a.ROWID = ma.attachment_id INNER JOIN chat_message_join cm ON   ma.message_id = cm.message_id INNER JOIN message m ON   ma.message_id = m.ROWID WHERE   m.cache_has_attachments   AND m.expire_state != %d   AND cm.chat_id IN (%@)   AND a.hide_attachment == 0   AND a.ck_sync_state == 1   AND a.transfer_state == 0 ORDER BY m.date DESC limit %d"
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND (m.balloon_bundle_id IS NULL OR m.balloon_bundle_id != 'com.apple.messages.chatbot') AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND (m.balloon_bundle_id IS NULL OR m.balloon_bundle_id != 'com.apple.messages.chatbot') ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND m.balloon_bundle_id == 'com.apple.messages.chatbot' AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a INNER JOIN message_attachment_join ma ON a.ROWID = ma.attachment_id INNER JOIN message m ON m.rowid = ma.message_id WHERE a.ck_sync_state == 0 AND m.balloon_bundle_id == 'com.apple.messages.chatbot' ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 AND a.ROWID > ? ORDER BY a.ROWID LIMIT ? "
- "SELECT * FROM attachment a WHERE a.ck_sync_state == 1 AND a.transfer_state == 0 ORDER BY a.ROWID LIMIT ? "
- "We didn't generate a previewFileURL for transfer %@ to generate a notification preview"
- "m.is_read == 0 AND\nNOT (m.ROWID in (SELECT message_id FROM "
```
