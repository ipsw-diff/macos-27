## CoreData

> `/System/Library/Frameworks/CoreData.framework/Versions/A/CoreData`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_doubleobj`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`
- `__DATA_DIRTY.__data`

```diff

-1627.0.0.0.0
-  __TEXT.__text: 0x38e6e0
-  __TEXT.__objc_methlist: 0x10cb0
+1629.1.0.0.0
+  __TEXT.__text: 0x38edb4
+  __TEXT.__objc_methlist: 0x10cd0
   __TEXT.__const: 0x2e20
-  __TEXT.__cstring: 0x3d48d
+  __TEXT.__cstring: 0x3d4d2
   __TEXT.__swift5_typeref: 0x12d0
   __TEXT.__constg_swiftt: 0x9d8
   __TEXT.__swift5_reflstr: 0x773

   __TEXT.__swift_as_entry: 0xc
   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x2c
-  __TEXT.__oslogstring: 0x36d90
-  __TEXT.__gcc_except_tab: 0x1a94c
-  __TEXT.__unwind_info: 0x7738
+  __TEXT.__oslogstring: 0x36d80
+  __TEXT.__gcc_except_tab: 0x1a9cc
+  __TEXT.__unwind_info: 0x7760
   __TEXT.__eh_frame: 0x9d0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x138
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6498
+  __DATA_CONST.__objc_selrefs: 0x64b0
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0xbf8
   __DATA_CONST.__objc_arraydata: 0x8910
   __DATA_CONST.__got: 0xcf0
-  __AUTH_CONST.__const: 0x6a78
+  __AUTH_CONST.__const: 0x6ad8
   __AUTH_CONST.__cfstring: 0x20b40
-  __AUTH_CONST.__objc_const: 0x26328
+  __AUTH_CONST.__objc_const: 0x26358
   __AUTH_CONST.__objc_dictobj: 0x2698
   __AUTH_CONST.__objc_arrayobj: 0x8fb8
   __AUTH_CONST.__objc_intobj: 0x570

   __AUTH_CONST.__auth_got: 0x1650
   __AUTH.__objc_data: 0x31e8
   __AUTH.__data: 0x208
-  __DATA.__objc_ivar: 0x18b4
+  __DATA.__objc_ivar: 0x18b8
   __DATA.__data: 0x16a0
   __DATA.__bss: 0x16d8
   __DATA.__common: 0x488

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 9248
-  Symbols:   20167
-  CStrings:  8469
+  Functions: 9254
+  Symbols:   20178
+  CStrings:  8470
 
Symbols:
+ -[NSPersistentCloudKitContainerOptions initWithContainer:scheduler:]
+ -[NSPersistentCloudKitContainerOptions setTestSchedulerOverride:]
+ -[NSPersistentCloudKitContainerOptions testSchedulerOverride]
+ -[NSXPCStoreConnection reconnect]
+ OBJC_IVAR_$_NSPersistentCloudKitContainerOptions._testSchedulerOverride
+ _$s8CoreData13CDSwiftResultV8populate4from5using14columnMetadata16compositeIndices14requestContext11moidFactory03oidO0ySo18FetchResultsRow_stVz_So0Q10EntityPlanazSayAA06ColumnI0VGs15ContiguousArrayVySiGSo017NSSQLFetchRequestM0CSo17NSManagedObjectIDCs5Int64VXEAYA_cSo11NSSQLEntityCXEtF49$ss5Int64VSo17NSManagedObjectIDCIegnr_AbDIegyo_TRA_AYIegnr_105$sSo11NSSQLEntityCxq_Ri_zRi0_zRi__Ri0__r0_lys5Int64VSo17NSManagedObjectIDCIsegnr_Iegnr_AbdFIegyo_Ieggo_TRA1_xq_Ri_zRi0_zRi__Ri0__r0_lyA_AYIsegnr_Iegnr_Tf1nnnnnEEn_n
+ __77-[NSCoreDataCoreSpotlightDelegate deleteSpotlightIndexWithCompletionHandler:]_block_invoke
+ ___77-[NSCoreDataCoreSpotlightDelegate _resetSpotlightIndexWithCompletionHandler:]_block_invoke
+ ___block_descriptor_48_e8_32b40r_e17_v16?0"NSError"8l
+ ___block_descriptor_56_e8_32o40b48r_e5_v8?0l
+ _objc_msgSend$initWithContainer:scheduler:
+ _objc_msgSend$testSchedulerOverride
- _$s8CoreData13CDSwiftResultV8populate4from5using14columnMetadata16compositeIndices14requestContext11moidFactory03oidO0ySo18FetchResultsRow_stVz_So0Q10EntityPlanazSayAA06ColumnI0VGs15ContiguousArrayVySiGSo017NSSQLFetchRequestM0CSo17NSManagedObjectIDCs5Int64VXEAYA_cSo11NSSQLEntityCXEtF49$ss5Int64VSo17NSManagedObjectIDCIegnr_AbDIegyo_TRA_AYIegnr_105$sSo11NSSQLEntityCxq_Ri_zRi0_zRi__Ri0__r0_lys5Int64VSo17NSManagedObjectIDCIsegnr_Iegnr_AbdFIegyo_Ieggo_TRA1_xq_Ri_zRi0_zRi__Ri0__r0_lyA_AYIsegnr_Iegnr_Tf1nnnnnccn_n
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/Classes/Persistency/CloudKit/Metadata/Entities/NSCKMetadataAsset.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/Classes/Persistency/CloudKit/PFCloudKitSetupAssistant.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCKEvent.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCKHistoryAnalyzerState.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCKImportPendingRelationship.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCKMetadataEntry.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCKMirroredRelationship.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCKRecordMetadata.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCKRecordZoneMetadata.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCKRecordZoneMoveReceipt.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCloudKitMirroringDelegate+CLI.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCloudKitMirroringDelegate.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCloudKitMirroringDelegatePreJazzkonMetadata.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCloudKitMirroringFetchRecordsRequest.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSCloudKitMirroringRequestManager.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSManagedObjectContext.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSPersistentCloudKitContainer.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSPersistentHistoryToken.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSPersistentStoreCoordinator.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSSQLAttributeExtensionFactory.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSSQLAttributeTrigger.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSSQLKeypathTriggerAttributeExtension.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSSQLLocationAttributeRTreeExtension.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/NSStoreMigrationPolicy.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitArchivingUtilities.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitCKQueryBackedImportWorkItem.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitExportContext.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitExporter.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitHistoryAnalyzer.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitHistoryAnalyzerContext.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitImportRecordsWorkItem.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitImportZoneContext.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitImporterZoneChangedWorkItem.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitMetadataCache.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitMetadataModel.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitMetadataModelMigrator.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitMetadataPurger.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitModelValidator.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitOptionsValidator.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitSchemaGenerator.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitSerializer.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitStoreComparer.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFCloudKitStoreComparisonCache.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFHistoryAnalyzer.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFHistoryAnalyzerContext.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/PFMirroredRelationship.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/XPCStore/NSXPCStore.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/XPCStore/_NSXPCStoreUtilities.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/_NSMappingModelBuilder.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/_PFRoutines.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/coredatad/CloudKit/CDDCloudKitServer.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/source/NSFileBackedFuture.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/sqlcore/NSSQLCore.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/sqlcore/NSSQLCore_Functions.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.DIjHbz/Sources/Persistence/sqlcore/NSSQLEntity.m"
+ "CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@): %@"
+ "CREATE TRIGGER IF NOT EXISTS %@_DELETE AFTER DELETE ON %@ FOR EACH ROW BEGIN DELETE FROM %@ WHERE rowid = OLD.Z_PK; END"
+ "CREATE TRIGGER IF NOT EXISTS %@_UPDATE AFTER UPDATE ON %@ FOR EACH ROW BEGIN DELETE FROM %@ WHERE rowid = OLD.Z_PK; INSERT INTO %@ (rowid, %@) VALUES (NEW.Z_PK, %@); END"
+ "CREATE VIRTUAL TABLE IF NOT EXISTS %@ USING fts5(%@, content='', contentless_delete=1, tokenize = '_CoreDataTokenizer')"
+ "CoreData: error: CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@): %@\n"
+ "CoreData: error: Timed out waiting for pre-reindex domain wipe to complete (index %@)\n"
+ "CoreData: error: disconnectAllConnections reconnect failed with exception: %@\n"
+ "INSERT INTO %@ (rowid, %@) SELECT Z_PK, %@ FROM %@"
+ "Timed out waiting for CoreSpotlight domain wipe"
+ "Timed out waiting for pre-reindex domain wipe to complete (index %@)"
+ "com.apple.coredata.tokenizer.default.v2"
+ "disconnectAllConnections reconnect failed with exception: %@"
- "%@OLD.%@"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/Classes/Persistency/CloudKit/Metadata/Entities/NSCKMetadataAsset.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/Classes/Persistency/CloudKit/PFCloudKitSetupAssistant.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCKEvent.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCKHistoryAnalyzerState.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCKImportPendingRelationship.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCKMetadataEntry.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCKMirroredRelationship.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCKRecordMetadata.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCKRecordZoneMetadata.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCKRecordZoneMoveReceipt.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCloudKitMirroringDelegate+CLI.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCloudKitMirroringDelegate.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCloudKitMirroringDelegatePreJazzkonMetadata.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCloudKitMirroringFetchRecordsRequest.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSCloudKitMirroringRequestManager.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSManagedObjectContext.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSPersistentCloudKitContainer.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSPersistentHistoryToken.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSPersistentStoreCoordinator.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSSQLAttributeExtensionFactory.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSSQLAttributeTrigger.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSSQLKeypathTriggerAttributeExtension.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSSQLLocationAttributeRTreeExtension.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/NSStoreMigrationPolicy.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitArchivingUtilities.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitCKQueryBackedImportWorkItem.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitExportContext.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitExporter.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitHistoryAnalyzer.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitHistoryAnalyzerContext.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitImportRecordsWorkItem.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitImportZoneContext.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitImporterZoneChangedWorkItem.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitMetadataCache.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitMetadataModel.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitMetadataModelMigrator.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitMetadataPurger.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitModelValidator.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitOptionsValidator.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitSchemaGenerator.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitSerializer.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitStoreComparer.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFCloudKitStoreComparisonCache.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFHistoryAnalyzer.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFHistoryAnalyzerContext.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/PFMirroredRelationship.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/XPCStore/NSXPCStore.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/XPCStore/_NSXPCStoreUtilities.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/_NSMappingModelBuilder.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/_PFRoutines.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/coredatad/CloudKit/CDDCloudKitServer.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/source/NSFileBackedFuture.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/sqlcore/NSSQLCore.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/sqlcore/NSSQLCore_Functions.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vAznQf/Sources/Persistence/sqlcore/NSSQLEntity.m"
- "CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@)"
- "CREATE TRIGGER IF NOT EXISTS %@_DELETE AFTER DELETE ON %@ FOR EACH ROW BEGIN INSERT INTO %@(%@, rowid, %@) VALUES('delete', OLD.Z_PK, %@); END"
- "CREATE TRIGGER IF NOT EXISTS %@_UPDATE AFTER UPDATE ON %@ FOR EACH ROW BEGIN INSERT INTO %@(%@, rowid, %@) VALUES('delete', OLD.Z_PK, %@); INSERT INTO %@ (rowid, %@) VALUES (NEW.Z_PK, %@); END"
- "CREATE VIRTUAL TABLE IF NOT EXISTS %@ USING fts5(%@, content='%@', content_rowid='Z_PK', tokenize = '_CoreDataTokenizer')"
- "CoreData: error: CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@)\n"
- "CoreData: error: Error while resetting the client spotlight index before re-index, %@.\n"
- "CoreData: warning: CDCS pre-reindex wipe reported error; continuing to reindex anyway (index %@)\n"
- "Error while resetting the client spotlight index before re-index, %@."
- "INSERT INTO %@(%@) VALUES('rebuild')"
- "com.apple.coredata.tokenizer.default.v1"
```
