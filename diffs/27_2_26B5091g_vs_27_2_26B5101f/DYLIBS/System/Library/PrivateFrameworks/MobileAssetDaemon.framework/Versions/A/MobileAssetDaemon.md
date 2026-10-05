## MobileAssetDaemon

> `/System/Library/PrivateFrameworks/MobileAssetDaemon.framework/Versions/A/MobileAssetDaemon`

```diff

-2215.40.19.0.0
-  __TEXT.__text: 0x27f8a0
-  __TEXT.__objc_methlist: 0x12bd4
+2215.40.21.501.1
+  __TEXT.__text: 0x281504
+  __TEXT.__objc_methlist: 0x12c34
   __TEXT.__const: 0x154a
-  __TEXT.__cstring: 0x3f723
-  __TEXT.__oslogstring: 0x59297
-  __TEXT.__gcc_except_tab: 0xd2e8
+  __TEXT.__cstring: 0x3f943
+  __TEXT.__oslogstring: 0x59827
+  __TEXT.__gcc_except_tab: 0xd388
   __TEXT.__constg_swiftt: 0xf0
   __TEXT.__swift5_typeref: 0x146
   __TEXT.__swift5_fieldmd: 0x3c

   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_proto: 0x24
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x5938
+  __TEXT.__unwind_info: 0x5990
   __TEXT.__eh_frame: 0x10c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1100
+  __DATA_CONST.__const: 0x1120
   __DATA_CONST.__objc_classlist: 0x490
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xae58
+  __DATA_CONST.__objc_selrefs: 0xae90
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x360
   __DATA_CONST.__objc_arraydata: 0x1038
   __DATA_CONST.__got: 0x1210
-  __AUTH_CONST.__const: 0x3300
-  __AUTH_CONST.__cfstring: 0x32ee0
-  __AUTH_CONST.__objc_const: 0x18d80
+  __AUTH_CONST.__const: 0x3340
+  __AUTH_CONST.__cfstring: 0x33080
+  __AUTH_CONST.__objc_const: 0x18db0
   __AUTH_CONST.__objc_arrayobj: 0x390
   __AUTH_CONST.__objc_intobj: 0x13b0
   __AUTH_CONST.__objc_dictobj: 0x2d0
-  __AUTH_CONST.__auth_got: 0x1160
+  __AUTH_CONST.__auth_got: 0x1168
   __AUTH.__objc_data: 0x878
   __AUTH.__data: 0xc0
-  __DATA.__objc_ivar: 0x17f8
+  __DATA.__objc_ivar: 0x17fc
   __DATA.__data: 0x10b0
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x570

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 7376
-  Symbols:   16564
-  CStrings:  10941
+  Functions: 7393
+  Symbols:   16594
+  CStrings:  10969
 
Symbols:
+ +[MAAutoAssetMigrationManager cleanupPreinstalledDirectoryAtPath:]
+ +[MAAutoAssetMigrationManager cleanupPreinstalledDirectory]
+ +[MAAutoAssetMigrationManager deleteDirectoryIfEmpty:error:]
+ -[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]
+ -[ControlManager maAutoAssetScheduledCleanup]
+ -[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:maAutoAssetScheduledCleanup:then:]
+ -[ControlManager setMaAutoAssetScheduledCleanup:]
+ -[MADAutoAssetControlManager formLatestAssetVersionBySelector:]
+ -[MADAutoAssetControlManager schedulerReferencesDescriptor:withLatestVersionBySelector:]
+ -[MADAutoAssetControlManager setConfigurationReferencesDescriptor:withLatestVersionBySelector:]
+ GCC_except_table175
+ GCC_except_table176
+ GCC_except_table839
+ GCC_except_table842
+ OBJC_IVAR_$_ControlManager._maAutoAssetScheduledCleanup
+ __134-[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:maAutoAssetScheduledCleanup:then:]_block_invoke
+ __53-[MobileAssetHealthReport scheduleReportWithReports:]_block_invoke_2
+ __OBJC_$_CLASS_METHODS_MAAutoAssetMigrationManager
+ ___134-[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:maAutoAssetScheduledCleanup:then:]_block_invoke
+ ___174-[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]_block_invoke
+ ___174-[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]_block_invoke_2
+ ___174-[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:]_block_invoke_3
+ ___53-[MobileAssetHealthReport scheduleReportWithReports:]_block_invoke_2
+ ___block_descriptor_32_e8_v16?0q8l
+ ___block_descriptor_80_e8_32s40s48s56bs_e5_v8?0l
+ ___clearXattrKey_block_invoke
+ ___updateXattrKeyWithDate_block_invoke
+ _clearXattrKey
+ _getDateOnXattrKey
+ _objc_msgSend$alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:existingNumberOfSeconds:logString:
+ _objc_msgSend$cleanupPreinstalledDirectory
+ _objc_msgSend$cleanupPreinstalledDirectoryAtPath:
+ _objc_msgSend$deleteDirectoryIfEmpty:error:
+ _objc_msgSend$formLatestAssetVersionBySelector:
+ _objc_msgSend$maAutoAssetScheduledCleanup
+ _objc_msgSend$respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:maAutoAssetScheduledCleanup:then:
+ _objc_msgSend$schedulerReferencesDescriptor:withLatestVersionBySelector:
+ _objc_msgSend$setConfigurationReferencesDescriptor:withLatestVersionBySelector:
+ _objc_msgSend$setMaAutoAssetScheduledCleanup:
+ _removexattr
+ _updateXattrKeyWithDate
- -[ControlManager alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:logString:]
- -[MADAutoAssetControlManager schedulerReferencesDescriptor:]
- -[MADAutoAssetControlManager setConfigurationReferencesDescriptor:]
- GCC_except_table835
- GCC_except_table841
- __106-[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:then:]_block_invoke
- ___106-[ControlManager respondToCacheDelete:targetingPurgeAmount:cacheDeleteResults:withUrgency:forVolume:then:]_block_invoke
- ___block_descriptor_79_e8_32s40s48s56bs_e5_v8?0l
- _objc_msgSend$alterSecondsBeforeCollection:forAssetTypeDir:determinedDescriptorType:fromDescriptors:autoAssetDescriptor:retentionPolicy:logString:
- _objc_msgSend$schedulerReferencesDescriptor:
- _objc_msgSend$setConfigurationReferencesDescriptor:
CStrings:
+ " | IGNORED - not UnlockedUnreferenced, not removed"
+ " | UnlockedUnreferenced for less than 24 hours - not removed"
+ " | UnlockedUnreferenced for more than 24 hours - immediate remove"
+ " | last UnlockedUnreferenced not set - not removed"
+ " | maCleanupMode"
+ " | used within 24 hours - not removed"
+ "Attempted to delete a directory that does not exists"
+ "Cannot clear xattr key %@ with %@ location"
+ "Cannot get xattr key %@ with %@ location"
+ "Cannot update xattr key %@ with %@ location"
+ "Directory is not empty"
+ "Failed to remove xattr '%@' on path '%s' with errno %lld (%s)"
+ "Loaded built-in MobileAssetDaemon_Framework Sep 29 2026 21:31:09"
+ "MADaemonAssetCleanupCheck"
+ "MobileAssetScheduledCleanUp"
+ "Provided path is a file instead of a directory"
+ "XPC activity %s performing AutoAsset clean up freed up %@ space"
+ "[AUTO-PRE-INSTALLED] {cleanupPreInstalledDirectory} Error removing empty directory at path(%@) error:%@"
+ "[AUTO-PRE-INSTALLED] {cleanupPreInstalledDirectory} Successfully removed empty directory at path(%@) error:%@"
+ "[AUTO-PRE-INSTALLED] {preInstalledRelocateAutoAssets} deleted pre-installed asset directory %{public}@"
+ "[AUTO-PRE-INSTALLED] {preInstalledRelocateAutoAssets} failed to delete pre-installed asset directory %{public}@ Error: %{public}@"
+ "clean up mode - not ready to be cleaned up"
+ "deleteDirectoryIfEmpty:error:"
+ "{copyCurrentDownloadedDescriptors} build container copies for auto-asset descriptor categories (with latest asset-version considered referenced) | dispatch..."
+ "{formLatestAssetVersionBySelector} unable to compare restore versions | assetDescriptorKey:%{public}@"
+ "{formLatestAssetVersionBySelector} unable to form withoutVersionKey | nextDownloadedDescriptor:%{public}@"
+ "{formLatestAssetVersionBySelector} unable to load nextDownloadedDescriptor | assetDescriptorKey:%{public}@"
+ "{respondToCacheDelete} %{public}@... | targetingPurgeAmount:%{public}@ | urgency:%{public}d(%{public}@) | volume:%{public}@ | assetTypeDirs:%{public}ld | preciousInterval:%{public}@%{public}@, defaultInterval:%{public}@%{public}@%{public}@ | autoAssetStatus:%{public}@ | maCleanup: %d"
+ "{respondToCacheDelete} ...%{public}@ | targetingPurgeAmount:%{public}@ | urgency:%{public}d(%{public}@) | volume:%{public}@ | assetTypeDirs:%{public}ld | preciousInterval:%{public}@%{public}@, defaultInterval:%{public}@%{public}@%{public}@ | autoAssetStatus:%{public}@ | %{public}@ | maCleanup: %d | MA_MILESTONE"
+ "{respondToCacheDelete} performing cache-delete triggered operation for volume %{public}@ at urgency %d, maCleanup %d ..."
+ "{schedulerReferencesDescriptor} missing latestVersionBySelector | withoutVersionKey:%{public}@"
+ "{setConfigurationReferencesDescriptor} missing latestVersionBySelector | withoutVersionKey:%{public}@"
+ "{setConfigurationReferencesDescriptor} unable to load set descriptor for discovered-in-flight | setConfiguration:%{public}@"
- "Loaded built-in MobileAssetDaemon_Framework Sep 13 2026 21:42:03"
- "{copyCurrentDownloadedDescriptors} build container copies for auto-asset descriptor categories | dispatch..."
- "{respondToCacheDelete} %{public}@... | targetingPurgeAmount:%{public}@ | urgency:%{public}d(%{public}@) | volume:%{public}@ | assetTypeDirs:%{public}ld | preciousInterval:%{public}@%{public}@, defaultInterval:%{public}@%{public}@%{public}@ | autoAssetStatus:%{public}@"
- "{respondToCacheDelete} ...%{public}@ | targetingPurgeAmount:%{public}@ | urgency:%{public}d(%{public}@) | volume:%{public}@ | assetTypeDirs:%{public}ld | preciousInterval:%{public}@%{public}@, defaultInterval:%{public}@%{public}@%{public}@ | autoAssetStatus:%{public}@ | %{public}@ | MA_MILESTONE"
- "{respondToCacheDelete} performing cache-delete triggered operation for volume %{public}@ at urgency %d ..."
```
