## FileProviderDaemon

> `/System/Library/PrivateFrameworks/FileProviderDaemon.framework/Versions/A/FileProviderDaemon`

```diff

-4838.40.92.501.2
-  __TEXT.__text: 0xa99500
-  __TEXT.__objc_methlist: 0x9e04
-  __TEXT.__const: 0x2e280
-  __TEXT.__cstring: 0x50765
-  __TEXT.__oslogstring: 0x21382
-  __TEXT.__gcc_except_tab: 0xd934
+4838.40.130.0.2
+  __TEXT.__text: 0xaaad64
+  __TEXT.__objc_methlist: 0x9f8c
+  __TEXT.__const: 0x2e2c0
+  __TEXT.__cstring: 0x50f25
+  __TEXT.__oslogstring: 0x21c32
+  __TEXT.__gcc_except_tab: 0xdafc
   __TEXT.__ustring: 0x1830
   __TEXT.__dlopen_cstrs: 0x114
-  __TEXT.__constg_swiftt: 0x14a7c
-  __TEXT.__swift5_typeref: 0x14d8e
-  __TEXT.__swift5_builtin: 0x8fc
-  __TEXT.__swift5_reflstr: 0xfb3d
-  __TEXT.__swift5_fieldmd: 0xd26c
+  __TEXT.__constg_swiftt: 0x14b48
+  __TEXT.__swift5_typeref: 0x14e2a
+  __TEXT.__swift5_builtin: 0x910
+  __TEXT.__swift5_reflstr: 0xfb9d
+  __TEXT.__swift5_fieldmd: 0xd2a0
   __TEXT.__swift5_mpenum: 0x144
   __TEXT.__swift5_assocty: 0x29c0
-  __TEXT.__swift5_capture: 0x1aab8
+  __TEXT.__swift5_capture: 0x1ac18
   __TEXT.__swift5_proto: 0x1c70
-  __TEXT.__swift5_types: 0xc60
+  __TEXT.__swift5_types: 0xc68
   __TEXT.__swift5_types2: 0x8
   __TEXT.__swift_as_entry: 0x1d4
   __TEXT.__swift_as_ret: 0x190
   __TEXT.__swift_as_cont: 0x3d8
   __TEXT.__swift5_protos: 0xbc
-  __TEXT.__unwind_info: 0x1b900
-  __TEXT.__eh_frame: 0x2dae0
+  __TEXT.__unwind_info: 0x1bee0
+  __TEXT.__eh_frame: 0x2d6f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9d0
-  __DATA_CONST.__objc_classlist: 0x5d0
+  __DATA_CONST.__const: 0xa08
+  __DATA_CONST.__objc_classlist: 0x5d8
   __DATA_CONST.__objc_catlist: 0x58
-  __DATA_CONST.__objc_protolist: 0x300
+  __DATA_CONST.__objc_protolist: 0x310
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x63f0
-  __DATA_CONST.__objc_protorefs: 0x170
+  __DATA_CONST.__objc_selrefs: 0x64c0
+  __DATA_CONST.__objc_protorefs: 0x178
   __DATA_CONST.__objc_superrefs: 0x2b8
-  __DATA_CONST.__objc_arraydata: 0x158
-  __DATA_CONST.__got: 0x1a28
-  __AUTH_CONST.__const: 0x503e8
-  __AUTH_CONST.__cfstring: 0x7a20
-  __AUTH_CONST.__objc_const: 0x286c8
-  __AUTH_CONST.__objc_arrayobj: 0x120
-  __AUTH_CONST.__objc_intobj: 0x180
+  __DATA_CONST.__objc_arraydata: 0x168
+  __DATA_CONST.__got: 0x19e8
+  __AUTH_CONST.__const: 0x50878
+  __AUTH_CONST.__cfstring: 0x7b40
+  __AUTH_CONST.__objc_const: 0x28898
+  __AUTH_CONST.__objc_arrayobj: 0x138
+  __AUTH_CONST.__objc_intobj: 0x1b0
   __AUTH_CONST.__objc_dictobj: 0xf0
-  __AUTH_CONST.__auth_got: 0x30a0
-  __AUTH.__objc_data: 0x1d20
-  __AUTH.__data: 0x2698
-  __DATA.__objc_ivar: 0xbe4
-  __DATA.__data: 0x8080
+  __AUTH_CONST.__auth_got: 0x30e0
+  __AUTH.__objc_data: 0x1e38
+  __AUTH.__data: 0x26b8
+  __DATA.__objc_ivar: 0xbf4
+  __DATA.__data: 0x8120
   __DATA.__bss: 0x26750
   __DATA.__common: 0x20b
   __DATA_DIRTY.__objc_data: 0x3578
-  __DATA_DIRTY.__data: 0x110b0
+  __DATA_DIRTY.__data: 0x110a0
   __DATA_DIRTY.__bss: 0x101a0
   __DATA_DIRTY.__common: 0x958
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 31875
-  Symbols:   15928
-  CStrings:  8349
+  Functions: 32001
+  Symbols:   16017
+  CStrings:  8409
 
Symbols:
+ -[FPDAccessControlServicer transferAccessToAllItemsFromBundle:toBundle:completionHandler:]
+ -[FPDAccessControlStore getSupersededBundleIdentifier:installSessionIdentifier:forBundleIdentifier:installSession:]
+ -[FPDAccessControlStore transferAccessFromBundle:toBundle:error:]
+ -[FPDDomain migrationState]
+ -[FPDDomain setMigrationState:]
+ -[FPDExtensionManager _isProviderInMigration:]
+ -[FPDExtensionManager _resumePendingMigrationsForEachPersona]
+ -[FPDExtensionManager beginMigrationForProviderIdentifiers:]
+ -[FPDExtensionManager currentDomainForSupersededProviderDomainIdentifier:]
+ -[FPDExtensionManager endMigrationForProviderIdentifiers:]
+ -[FPDXPCServicer migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]
+ -[FPFSChangeMonitor didResumeHandler]
+ -[FPFSChangeMonitor isSuspended]
+ -[FPFSChangeMonitor setDidResumeHandler:]
+ GCC_except_table236
+ GCC_except_table254
+ GCC_except_table261
+ GCC_except_table263
+ GCC_except_table283
+ GCC_except_table285
+ GCC_except_table290
+ GCC_except_table295
+ GCC_except_table296
+ GCC_except_table297
+ GCC_except_table301
+ GCC_except_table305
+ GCC_except_table306
+ GCC_except_table310
+ GCC_except_table311
+ GCC_except_table318
+ GCC_except_table322
+ GCC_except_table324
+ GCC_except_table333
+ GCC_except_table343
+ GCC_except_table350
+ GCC_except_table351
+ GCC_except_table352
+ GCC_except_table356
+ GCC_except_table361
+ GCC_except_table375
+ GCC_except_table401
+ GCC_except_table402
+ GCC_except_table403
+ GCC_except_table432
+ GCC_except_table457
+ GCC_except_table464
+ GCC_except_table473
+ GCC_except_table474
+ GCC_except_table475
+ GCC_except_table479
+ GCC_except_table480
+ GCC_except_table481
+ OBJC_IVAR_$_FPDAccessControlStore._openError
+ OBJC_IVAR_$_FPDDomain._migrationState
+ OBJC_IVAR_$_FPDExtensionManager._providersInMigration
+ OBJC_IVAR_$_FPFSChangeMonitor._didResumeHandler
+ _FPDomainMigrationDestinationKey
+ _FPDomainMigrationKey
+ _FPDomainMigrationSourcesKey
+ _OBJC_CLASS_$_FPDDomainMigrationState
+ _OBJC_METACLASS_$_FPDDomainMigrationState
+ _PROTOCOLS_FPDDomainMigrationState
+ __97-[FPDXPCServicer migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]_block_invoke
+ __DATA_FPDDomainMigrationState
+ __INSTANCE_METHODS_FPDDomainMigrationState
+ __IVARS_FPDDomainMigrationState
+ __METACLASS_DATA_FPDDomainMigrationState
+ __OBJC_$_INSTANCE_METHODS_FPDExtensionManager(FileProviderDaemon)
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_NSCopying
+ __OBJC_$_PROTOCOL_METHOD_TYPES_NSCopying
+ __OBJC_LABEL_PROTOCOL_$_NSCopying
+ __OBJC_PROTOCOL_$_NSCopying
+ __PROPERTIES_FPDDomainMigrationState
+ __PROTOCOLS_FPDDomainMigrationState
+ __ZL27containingApplicationRecordP8NSString
+ ___115-[FPDAccessControlStore getSupersededBundleIdentifier:installSessionIdentifier:forBundleIdentifier:installSession:]_block_invoke
+ ___115-[FPDAccessControlStore getSupersededBundleIdentifier:installSessionIdentifier:forBundleIdentifier:installSession:]_block_invoke_2
+ ___61-[FPDExtensionManager _resumePendingMigrationsForEachPersona]_block_invoke
+ ___65-[FPDAccessControlStore transferAccessFromBundle:toBundle:error:]_block_invoke
+ ___65-[FPDAccessControlStore transferAccessFromBundle:toBundle:error:]_block_invoke_2
+ ___97-[FPDXPCServicer migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48r56r_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_64_e8_32s40s48r56r_e35_v24?0"PQLConnection"8"NSError"16l
+ ___block_descriptor_72_e8_32s40s48s56s64r_e23_B16?0"PQLConnection"8l
+ ___block_descriptor_80_e8_32s40s48s56s64r72r_e35_v24?0"PQLConnection"8"NSError"16l
+ ___swift_assign_boxed_opaque_existential_0
+ ___unnamed_117
+ __swift_closure_destructor.1025Tm
+ __swift_closure_destructor.1028Tm
+ __swift_closure_destructor.1031Tm
+ __swift_closure_destructor.1034Tm
+ __swift_closure_destructor.106Tm
+ __swift_closure_destructor.113Tm
+ __swift_closure_destructor.1237Tm
+ __swift_closure_destructor.1602Tm
+ __swift_closure_destructor.1646Tm
+ __swift_closure_destructor.1697Tm
+ __swift_closure_destructor.1700Tm
+ __swift_closure_destructor.175Tm
+ __swift_closure_destructor.1777Tm
+ __swift_closure_destructor.1787Tm
+ __swift_closure_destructor.1793Tm
+ __swift_closure_destructor.1886Tm
+ __swift_closure_destructor.1914Tm
+ __swift_closure_destructor.1975Tm
+ __swift_closure_destructor.2108Tm
+ __swift_closure_destructor.218Tm
+ __swift_closure_destructor.221Tm
+ __swift_closure_destructor.233Tm
+ __swift_closure_destructor.2561Tm
+ __swift_closure_destructor.257Tm
+ __swift_closure_destructor.260Tm
+ __swift_closure_destructor.262Tm
+ __swift_closure_destructor.277Tm
+ __swift_closure_destructor.2869Tm
+ __swift_closure_destructor.2982Tm
+ __swift_closure_destructor.307Tm
+ __swift_closure_destructor.3119Tm
+ __swift_closure_destructor.3126Tm
+ __swift_closure_destructor.312Tm
+ __swift_closure_destructor.3136Tm
+ __swift_closure_destructor.3139Tm
+ __swift_closure_destructor.3213Tm
+ __swift_closure_destructor.3244Tm
+ __swift_closure_destructor.3350Tm
+ __swift_closure_destructor.338Tm
+ __swift_closure_destructor.344Tm
+ __swift_closure_destructor.3488Tm
+ __swift_closure_destructor.3518Tm
+ __swift_closure_destructor.3594Tm
+ __swift_closure_destructor.3604Tm
+ __swift_closure_destructor.3607Tm
+ __swift_closure_destructor.3610Tm
+ __swift_closure_destructor.363Tm
+ __swift_closure_destructor.367Tm
+ __swift_closure_destructor.3686Tm
+ __swift_closure_destructor.3692Tm
+ __swift_closure_destructor.3701Tm
+ __swift_closure_destructor.38Tm
+ __swift_closure_destructor.39Tm
+ __swift_closure_destructor.401Tm
+ __swift_closure_destructor.4187Tm
+ __swift_closure_destructor.4231Tm
+ __swift_closure_destructor.4237Tm
+ __swift_closure_destructor.427Tm
+ __swift_closure_destructor.4331Tm
+ __swift_closure_destructor.4356Tm
+ __swift_closure_destructor.436Tm
+ __swift_closure_destructor.446Tm
+ __swift_closure_destructor.4569Tm
+ __swift_closure_destructor.4572Tm
+ __swift_closure_destructor.4576Tm
+ __swift_closure_destructor.4579Tm
+ __swift_closure_destructor.4694Tm
+ __swift_closure_destructor.4720Tm
+ __swift_closure_destructor.4759Tm
+ __swift_closure_destructor.4876Tm
+ __swift_closure_destructor.4882Tm
+ __swift_closure_destructor.489Tm
+ __swift_closure_destructor.512Tm
+ __swift_closure_destructor.513Tm
+ __swift_closure_destructor.519Tm
+ __swift_closure_destructor.527Tm
+ __swift_closure_destructor.5285Tm
+ __swift_closure_destructor.537Tm
+ __swift_closure_destructor.544Tm
+ __swift_closure_destructor.5558Tm
+ __swift_closure_destructor.5590Tm
+ __swift_closure_destructor.559Tm
+ __swift_closure_destructor.571Tm
+ __swift_closure_destructor.5893Tm
+ __swift_closure_destructor.589Tm
+ __swift_closure_destructor.6104Tm
+ __swift_closure_destructor.617Tm
+ __swift_closure_destructor.624Tm
+ __swift_closure_destructor.630Tm
+ __swift_closure_destructor.6395Tm
+ __swift_closure_destructor.6409Tm
+ __swift_closure_destructor.648Tm
+ __swift_closure_destructor.656Tm
+ __swift_closure_destructor.6615Tm
+ __swift_closure_destructor.6622Tm
+ __swift_closure_destructor.6647Tm
+ __swift_closure_destructor.68Tm
+ __swift_closure_destructor.703Tm
+ __swift_closure_destructor.730Tm
+ __swift_closure_destructor.739Tm
+ __swift_closure_destructor.742Tm
+ __swift_closure_destructor.753Tm
+ __swift_closure_destructor.762Tm
+ __swift_closure_destructor.783Tm
+ __swift_closure_destructor.835Tm
+ __swift_closure_destructor.83Tm
+ __swift_closure_destructor.852Tm
+ __swift_closure_destructor.896Tm
+ __swift_closure_destructor.90Tm
+ __swift_closure_destructor.936Tm
+ _errorInjectionDefaultsKeyForCategory
+ _errorInjectionMigrationCrashAfterMarkEnabled
+ _errorInjectionMigrationCrashAfterRenameEnabled
+ _errorInjectionMigrationCrashBeforeHandoverEnabled
+ _errorInjectionMigrationCrashBeforeMarkEnabled
+ _errorInjectionMigrationCrashBetweenDomainsEnabled
+ _errorInjectionMigrationCrashBetweenStorageKindsEnabled
+ _fpfs_supports_appDomainMigration
+ _kFileProviderSupersededAppReplacementEntitlement
+ _kill
+ _objc_msgSend$_isProviderInMigration:
+ _objc_msgSend$_resumePendingMigrationsForEachPersona
+ _objc_msgSend$beginMigrationForProviderIdentifiers:
+ _objc_msgSend$currentDomainForSupersededProviderDomainIdentifier:
+ _objc_msgSend$didResumeHandler
+ _objc_msgSend$endMigrationForProviderIdentifiers:
+ _objc_msgSend$fp_errorWithPOSIXCode:description:
+ _objc_msgSend$getSupersededBundleIdentifier:installSessionIdentifier:forBundleIdentifier:installSession:
+ _objc_msgSend$initWithPlistDictionary:
+ _objc_msgSend$isFinishedForRecordOwnedBy:
+ _objc_msgSend$isSuspended
+ _objc_msgSend$migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:request:completionHandler:
+ _objc_msgSend$migrationState
+ _objc_msgSend$resumePendingMigrationsOn:
+ _objc_msgSend$setDidResumeHandler:
+ _objc_msgSend$setMigrationState:
+ _objc_msgSend$synchronize
+ _objc_msgSend$transferAccessFromBundle:toBundle:error:
+ _resolveInstallSessionIdentifier
+ _symbolic SDy_____ypG s11AnyHashableV
+ _symbolic Say_____G So12FPProviderIDa
+ _symbolic Sb_____yxq_GcSg 18FileProviderDaemon11SchedulableC
+ _symbolic _____ 18FileProviderDaemon23FPDDomainMigrationStateC
+ _symbolic _____ So30FPDVolumeDomainStorageLocationV
+ _symbolic _____3key_yp5valuet So30NSFileProviderDomainIdentifiera
+ _symbolic _____6source_AA11destinationt So12FPProviderIDa
+ _symbolic _____y_____6source_AB11destinationtG s23_ContiguousArrayStorageC So12FPProviderIDa
+ _symbolic _____y_____G s23_ContiguousArrayStorageC So12FPProviderIDa
+ _symbolic _____y_____SgG s23_ContiguousArrayStorageC So28NSFileProviderItemIdentifiera
+ _symbolic _____y_____ypG s18_DictionaryStorageC So30NSFileProviderDomainIdentifiera
- GCC_except_table242
- GCC_except_table257
- GCC_except_table264
- GCC_except_table266
- GCC_except_table292
- GCC_except_table293
- GCC_except_table294
- GCC_except_table298
- GCC_except_table299
- GCC_except_table300
- GCC_except_table304
- GCC_except_table308
- GCC_except_table309
- GCC_except_table313
- GCC_except_table317
- GCC_except_table321
- GCC_except_table330
- GCC_except_table331
- GCC_except_table336
- GCC_except_table346
- GCC_except_table353
- GCC_except_table358
- GCC_except_table360
- GCC_except_table362
- GCC_except_table364
- GCC_except_table378
- GCC_except_table404
- GCC_except_table405
- GCC_except_table406
- GCC_except_table435
- GCC_except_table463
- GCC_except_table467
- GCC_except_table476
- GCC_except_table477
- GCC_except_table478
- __OBJC_$_INSTANCE_METHODS_FPDExtensionManager
- ___unnamed_115
- __swift_closure_destructor.1023Tm
- __swift_closure_destructor.1026Tm
- __swift_closure_destructor.1029Tm
- __swift_closure_destructor.1032Tm
- __swift_closure_destructor.103Tm
- __swift_closure_destructor.1235Tm
- __swift_closure_destructor.143Tm
- __swift_closure_destructor.1559Tm
- __swift_closure_destructor.1644Tm
- __swift_closure_destructor.1695Tm
- __swift_closure_destructor.1698Tm
- __swift_closure_destructor.1724Tm
- __swift_closure_destructor.1754Tm
- __swift_closure_destructor.1785Tm
- __swift_closure_destructor.179Tm
- __swift_closure_destructor.1884Tm
- __swift_closure_destructor.189Tm
- __swift_closure_destructor.1912Tm
- __swift_closure_destructor.1952Tm
- __swift_closure_destructor.2071Tm
- __swift_closure_destructor.220Tm
- __swift_closure_destructor.240Tm
- __swift_closure_destructor.24Tm
- __swift_closure_destructor.2500Tm
- __swift_closure_destructor.261Tm
- __swift_closure_destructor.264Tm
- __swift_closure_destructor.276Tm
- __swift_closure_destructor.2808Tm
- __swift_closure_destructor.2921Tm
- __swift_closure_destructor.3058Tm
- __swift_closure_destructor.3065Tm
- __swift_closure_destructor.3075Tm
- __swift_closure_destructor.3078Tm
- __swift_closure_destructor.311Tm
- __swift_closure_destructor.3152Tm
- __swift_closure_destructor.3183Tm
- __swift_closure_destructor.3289Tm
- __swift_closure_destructor.337Tm
- __swift_closure_destructor.33Tm
- __swift_closure_destructor.3427Tm
- __swift_closure_destructor.343Tm
- __swift_closure_destructor.3457Tm
- __swift_closure_destructor.3533Tm
- __swift_closure_destructor.3543Tm
- __swift_closure_destructor.3546Tm
- __swift_closure_destructor.3549Tm
- __swift_closure_destructor.3625Tm
- __swift_closure_destructor.362Tm
- __swift_closure_destructor.3631Tm
- __swift_closure_destructor.3640Tm
- __swift_closure_destructor.366Tm
- __swift_closure_destructor.400Tm
- __swift_closure_destructor.4126Tm
- __swift_closure_destructor.4170Tm
- __swift_closure_destructor.4176Tm
- __swift_closure_destructor.426Tm
- __swift_closure_destructor.4270Tm
- __swift_closure_destructor.4295Tm
- __swift_closure_destructor.431Tm
- __swift_closure_destructor.440Tm
- __swift_closure_destructor.445Tm
- __swift_closure_destructor.4502Tm
- __swift_closure_destructor.4505Tm
- __swift_closure_destructor.4509Tm
- __swift_closure_destructor.4512Tm
- __swift_closure_destructor.4626Tm
- __swift_closure_destructor.4652Tm
- __swift_closure_destructor.4691Tm
- __swift_closure_destructor.4808Tm
- __swift_closure_destructor.4814Tm
- __swift_closure_destructor.511Tm
- __swift_closure_destructor.514Tm
- __swift_closure_destructor.520Tm
- __swift_closure_destructor.5217Tm
- __swift_closure_destructor.531Tm
- __swift_closure_destructor.535Tm
- __swift_closure_destructor.542Tm
- __swift_closure_destructor.5490Tm
- __swift_closure_destructor.5522Tm
- __swift_closure_destructor.563Tm
- __swift_closure_destructor.569Tm
- __swift_closure_destructor.575Tm
- __swift_closure_destructor.57Tm
- __swift_closure_destructor.5825Tm
- __swift_closure_destructor.599Tm
- __swift_closure_destructor.6036Tm
- __swift_closure_destructor.623Tm
- __swift_closure_destructor.627Tm
- __swift_closure_destructor.629Tm
- __swift_closure_destructor.6326Tm
- __swift_closure_destructor.6340Tm
- __swift_closure_destructor.646Tm
- __swift_closure_destructor.6546Tm
- __swift_closure_destructor.6553Tm
- __swift_closure_destructor.6578Tm
- __swift_closure_destructor.66Tm
- __swift_closure_destructor.702Tm
- __swift_closure_destructor.729Tm
- __swift_closure_destructor.72Tm
- __swift_closure_destructor.740Tm
- __swift_closure_destructor.743Tm
- __swift_closure_destructor.750Tm
- __swift_closure_destructor.759Tm
- __swift_closure_destructor.78Tm
- __swift_closure_destructor.815Tm
- __swift_closure_destructor.836Tm
- __swift_closure_destructor.849Tm
- __swift_closure_destructor.84Tm
- __swift_closure_destructor.917Tm
- __swift_closure_destructor.933Tm
- __swift_closure_destructor.94Tm
CStrings:
+ "\v"
+ "%{public}s already has domains of its own"
+ "%{public}s has no domains to hand over"
+ "-[FPDXPCServicer migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]"
+ "-[FPDXPCServicer migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]_block_invoke"
+ "CREATE TABLE superseded_apps ( bundle_identifier TEXT NOT NULL, install_session_identifier BLOB NOT NULL, superseded_bundle_identifier TEXT NOT NULL, superseded_install_session_identifier BLOB NOT NULL, PRIMARY KEY (bundle_identifier, install_session_identifier) )"
+ "CREATE TRIGGER \"donation_status/fp_snapshot/app_container_bundle_identifier_arrival\"\n  AFTER UPDATE OF decoration_app_container_bundle_identifier ON fp_snapshot\n  WHEN (OLD.decoration_app_container_bundle_identifier IS NULL\n        OR length(OLD.decoration_app_container_bundle_identifier) = 0)\n    AND NEW.decoration_app_container_bundle_identifier IS NOT NULL\n    AND length(NEW.decoration_app_container_bundle_identifier) > 0\n    AND NEW.decoration_is_container = 1\nBEGIN\n  UPDATE reconciliation_table\n    SET donation_status = "
+ "Destination"
+ "FileProviderDaemon.FPDDomainMigrationState"
+ "INSERT OR REPLACE INTO superseded_apps (bundle_identifier, install_session_identifier, superseded_bundle_identifier, superseded_install_session_identifier) VALUES (%@, %@, %@, %@)"
+ "Migration"
+ "PRAGMA auto_vacuum = none"
+ "SELECT 1 FROM manifest LIMIT 1"
+ "SELECT superseded_bundle_identifier, superseded_install_session_identifier FROM superseded_apps WHERE bundle_identifier = %@ AND install_session_identifier = %@"
+ "Sources"
+ "UPDATE OR REPLACE bundle_keys SET identifier = %@ WHERE identifier = %@"
+ "[DEBUG] [incomplete migration] Initializing disconnected provider for %@"
+ "[DEBUG] itemID %@ predates the hand-over to %@"
+ "[NOTICE] %@: not starting the indexer (invalidated=%{bool}d indexerStopped=%{bool}d activeProvider=%{bool}d)"
+ "[NOTICE] Not registering %{public}@ while its domains are being migrated"
+ "[NOTICE] no access to transfer from %@ to %@"
+ "[NOTICE] refusing to migrate domains: the appDomainMigration feature flag is off"
+ "[NOTICE] transferred access from %@ (%@) to %@ (%@)"
+ "after marking the records"
+ "after-mark"
+ "after-rename"
+ "before marking the records"
+ "before-handover"
+ "before-mark"
+ "between-domains"
+ "between-storage-kinds"
+ "cannot hand %{public}s storage over to %{public}s: it owns one already"
+ "cannot look for unfinished migrations under %{public}s: %{public}@"
+ "cannot mark the record of %{public}s for hand-over: it is not a dictionary"
+ "cannot open access control database"
+ "cannot read the records of %{public}s: %{public}@"
+ "crash-injection: killing fileproviderd at %s"
+ "destinationProviderIdentifier"
+ "domains are being handed over to another provider"
+ "folder is being populated"
+ "found %ld unfinished hand-over(s) under %{public}s"
+ "handing %{public}s storage at %{public}s over to %{public}s"
+ "ignoring malformed migration state with keys %s"
+ "marked %ld record(s) of %{public}s; a later launch can finish this hand-over from here"
+ "marking %ld record(s) of %{public}s for hand-over to %{public}s"
+ "migrated %ld domain(s) from %{public}s to %{public}s; both providers are registered again"
+ "migrating %{public}s to %{public}s failed %{public}s: %{public}@"
+ "moved the records over to %{public}s, which is what finishes the hand-over"
+ "moving the records of %{public}s over to %{public}s"
+ "pre-flight passed, handing over %ld domain(s) from %{public}s to %{public}s"
+ "re-stamped the storage of %{public}s"
+ "re-stamping the storage of %{public}s from %{public}s to %{public}s"
+ "refusing to migrate %{public}s to %{public}s: %{public}@"
+ "removed the existing records of %{public}s"
+ "resumed migration of %{public}s to %{public}s"
+ "resuming migration of %{public}s to %{public}s"
+ "resuming migration of %{public}s to %{public}s failed: %{public}@"
+ "starting request to migrate %{public}s to %{public}s from %{public}s"
+ "stopped %{public}s for the duration of the hand-over"
+ "update_v13_6_appContainerBundleIdentifierArrivalTrigger(with:)"
+ "\xb1"
+ "\xf0\xb1"
- "\xa1"
- "\xf0\xa1"
```
