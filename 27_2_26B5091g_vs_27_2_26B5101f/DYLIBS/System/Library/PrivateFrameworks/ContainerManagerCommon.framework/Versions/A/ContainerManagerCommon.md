## ContainerManagerCommon

> `/System/Library/PrivateFrameworks/ContainerManagerCommon.framework/Versions/A/ContainerManagerCommon`

```diff

-833.40.16.0.0
-  __TEXT.__text: 0x10bcd8
-  __TEXT.__objc_methlist: 0xb314
+833.40.18.0.1
+  __TEXT.__text: 0x10e2bc
+  __TEXT.__objc_methlist: 0xb4dc
   __TEXT.__const: 0x15d0
   __TEXT.__swift5_typeref: 0x871
-  __TEXT.__oslogstring: 0xecbc
-  __TEXT.__cstring: 0xa8c3
+  __TEXT.__oslogstring: 0xef96
+  __TEXT.__cstring: 0xa958
   __TEXT.__constg_swiftt: 0x790
   __TEXT.__swift5_reflstr: 0x52a
   __TEXT.__swift5_fieldmd: 0x5d4

   __TEXT.__swift5_capture: 0x88
   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__swift5_protos: 0x18
-  __TEXT.__gcc_except_tab: 0x2400
+  __TEXT.__gcc_except_tab: 0x2408
   __TEXT.__ustring: 0x16c
-  __TEXT.__unwind_info: 0x3e20
-  __TEXT.__eh_frame: 0x9dc
+  __TEXT.__unwind_info: 0x3ea8
+  __TEXT.__eh_frame: 0xaac
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x450
-  __DATA_CONST.__objc_classlist: 0x5d8
+  __DATA_CONST.__const: 0x458
+  __DATA_CONST.__objc_classlist: 0x5e0
   __DATA_CONST.__objc_catlist: 0x30
-  __DATA_CONST.__objc_protolist: 0x618
+  __DATA_CONST.__objc_protolist: 0x628
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x38b8
-  __DATA_CONST.__objc_protorefs: 0x1a8
+  __DATA_CONST.__objc_selrefs: 0x3968
+  __DATA_CONST.__objc_protorefs: 0x1b0
   __DATA_CONST.__objc_superrefs: 0x4a8
   __DATA_CONST.__objc_arraydata: 0x3d0
-  __DATA_CONST.__got: 0x550
+  __DATA_CONST.__got: 0x558
   __AUTH_CONST.__const: 0x2c10
-  __AUTH_CONST.__cfstring: 0x5740
-  __AUTH_CONST.__objc_const: 0x179b0
+  __AUTH_CONST.__cfstring: 0x5760
+  __AUTH_CONST.__objc_const: 0x17cb8
   __AUTH_CONST.__objc_dictobj: 0x3e8
   __AUTH_CONST.__objc_intobj: 0x15d8
   __AUTH_CONST.__objc_arrayobj: 0xc0
-  __AUTH_CONST.__auth_got: 0x1280
-  __AUTH.__objc_data: 0xd98
-  __AUTH.__data: 0x188
-  __DATA.__objc_ivar: 0xc38
-  __DATA.__data: 0x3d40
+  __AUTH_CONST.__auth_got: 0x1288
+  __AUTH.__objc_data: 0xe08
+  __AUTH.__data: 0x1b8
+  __DATA.__objc_ivar: 0xc48
+  __DATA.__data: 0x3de0
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0xc98
   __DATA.__common: 0x48
   __DATA_DIRTY.__objc_data: 0x31e8
-  __DATA_DIRTY.__data: 0x550
+  __DATA_DIRTY.__data: 0x570
   __DATA_DIRTY.__bss: 0x990
   __DATA_DIRTY.__common: 0x50
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3877
-  Symbols:   8635
-  CStrings:  2133
+  Functions: 3918
+  Symbols:   8689
+  CStrings:  2143
 
Symbols:
+ +[MCMContainerCacheEntry metadataReadErrorIsInconclusive:]
+ +[MCMContainerFactory lookupErrorPermitsCreation:]
+ -[MCMCommandQuery coexistingInstances]
+ -[MCMContainerCache _missingContainerErrorForClassCache:]
+ -[MCMContainerCache _unreadableContainerError]
+ -[MCMContainerCache entryForContainerIdentity:classCache:mutationAllowed:coexistingInstances:error:]
+ -[MCMContainerClassCache _concurrent_slowGenerateCacheEntryWithFileHandle:URL:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:containerPath:out_deferred:]
+ -[MCMContainerClassCache _noteUnreadableContainer]
+ -[MCMContainerClassCache _resetUnreadableContainers]
+ -[MCMContainerClassCache hasUnreadableContainers]
+ -[MCMContainerConfiguration exclusiveInstance]
+ -[MCMContainerFactory containerForContainerIdentity:createIfNecessary:coexistingInstances:error:]
+ -[MCMContainerMigrator queueUnlockDeferredMigrationsWithContext:]
+ -[MCMXPCMessageQuery coexistingInstances]
+ GCC_except_table1003
+ GCC_except_table1039
+ GCC_except_table1050
+ GCC_except_table1093
+ GCC_except_table1102
+ GCC_except_table1108
+ GCC_except_table1158
+ GCC_except_table1175
+ GCC_except_table1182
+ GCC_except_table1188
+ GCC_except_table1199
+ GCC_except_table1201
+ GCC_except_table1204
+ GCC_except_table1209
+ GCC_except_table1211
+ GCC_except_table1219
+ GCC_except_table1222
+ GCC_except_table1224
+ GCC_except_table1234
+ GCC_except_table1253
+ GCC_except_table1255
+ GCC_except_table1310
+ GCC_except_table1320
+ GCC_except_table1351
+ GCC_except_table1592
+ GCC_except_table1742
+ GCC_except_table1746
+ GCC_except_table1899
+ GCC_except_table1905
+ GCC_except_table2009
+ GCC_except_table2149
+ GCC_except_table2301
+ GCC_except_table2318
+ GCC_except_table2319
+ GCC_except_table2384
+ GCC_except_table2431
+ GCC_except_table2445
+ GCC_except_table2466
+ GCC_except_table2535
+ GCC_except_table2547
+ GCC_except_table2613
+ GCC_except_table2627
+ GCC_except_table2652
+ GCC_except_table2679
+ GCC_except_table2703
+ GCC_except_table2706
+ GCC_except_table2709
+ GCC_except_table2716
+ GCC_except_table2769
+ GCC_except_table2773
+ GCC_except_table2944
+ GCC_except_table2948
+ GCC_except_table3028
+ GCC_except_table947
+ OBJC_IVAR_$_MCMCommandQuery._coexistingInstances
+ OBJC_IVAR_$_MCMContainerClassCache._lock_unreadableCount
+ OBJC_IVAR_$_MCMContainerConfiguration._exclusiveInstance
+ OBJC_IVAR_$_MCMXPCMessageQuery._coexistingInstances
+ _MCMCompareDataProtectionClassTarget
+ _MCMGetDataProtectionClass
+ _MCMMigrationTypeRepairMetadataDataProtection
+ _MCMSetDataProtectionClass
+ _OBJC_CLASS_$_MCMMetadataDataProtectionRepair
+ _OBJC_METACLASS_$_MCMMetadataDataProtectionRepair
+ _PROTOCOLS_MCMMetadataDataProtectionRepair
+ __DATA_MCMMetadataDataProtectionRepair
+ __INSTANCE_METHODS_MCMMetadataDataProtectionRepair
+ __IVARS_MCMMetadataDataProtectionRepair
+ __METACLASS_DATA_MCMMetadataDataProtectionRepair
+ __OBJC_$_CLASS_METHODS_MCMContainerFactory
+ __OBJC_$_PROP_LIST_MCMMetadataDataProtectionRepair
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_MCMMetadataDataProtectionRepair
+ __OBJC_$_PROTOCOL_METHOD_TYPES_MCMMetadataDataProtectionRepair
+ __OBJC_$_PROTOCOL_REFS_MCMMetadataDataProtectionRepair
+ __OBJC_LABEL_PROTOCOL_$_MCMMetadataDataProtectionRepair
+ __OBJC_PROTOCOL_$_MCMMetadataDataProtectionRepair
+ __PROPERTIES_MCMMetadataDataProtectionRepair
+ __PROTOCOLS_MCMMetadataDataProtectionRepair
+ _objc_msgSend$_concurrent_slowGenerateCacheEntryWithFileHandle:URL:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:containerPath:out_deferred:
+ _objc_msgSend$_examinedCount
+ _objc_msgSend$_missingContainerErrorForClassCache:
+ _objc_msgSend$_noteUnreadableContainer
+ _objc_msgSend$_repairedCount
+ _objc_msgSend$_resetUnreadableContainers
+ _objc_msgSend$_unreadableContainerError
+ _objc_msgSend$coexistingInstances
+ _objc_msgSend$containerClassURLs
+ _objc_msgSend$containerForContainerIdentity:createIfNecessary:coexistingInstances:error:
+ _objc_msgSend$entryForContainerIdentity:classCache:mutationAllowed:coexistingInstances:error:
+ _objc_msgSend$exclusiveInstance
+ _objc_msgSend$hasUnreadableContainers
+ _objc_msgSend$initWithContext:identities:createIfNecessary:fuzzyMatchTransient:coexistingInstances:
+ _objc_msgSend$lookupErrorPermitsCreation:
+ _objc_msgSend$metadataReadErrorIsInconclusive:
+ _objc_msgSend$queueUnlockDeferredMigrationsWithContext:
+ _objc_msgSend$set_examinedCount:
+ _objc_msgSend$set_repairedCount:
- -[MCMContainerClassCache _concurrent_slowGenerateCacheEntryWithFileHandle:URL:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:containerPath:]
- GCC_except_table1031
- GCC_except_table1046
- GCC_except_table1089
- GCC_except_table1098
- GCC_except_table1104
- GCC_except_table1154
- GCC_except_table1171
- GCC_except_table1174
- GCC_except_table1184
- GCC_except_table1187
- GCC_except_table1193
- GCC_except_table1200
- GCC_except_table1203
- GCC_except_table1205
- GCC_except_table1215
- GCC_except_table1218
- GCC_except_table1220
- GCC_except_table1230
- GCC_except_table1245
- GCC_except_table1251
- GCC_except_table1306
- GCC_except_table1316
- GCC_except_table1347
- GCC_except_table1588
- GCC_except_table1735
- GCC_except_table1739
- GCC_except_table1892
- GCC_except_table1898
- GCC_except_table2001
- GCC_except_table2140
- GCC_except_table2292
- GCC_except_table2309
- GCC_except_table2310
- GCC_except_table2375
- GCC_except_table2421
- GCC_except_table2435
- GCC_except_table2456
- GCC_except_table2525
- GCC_except_table2537
- GCC_except_table2603
- GCC_except_table2615
- GCC_except_table2640
- GCC_except_table2667
- GCC_except_table2691
- GCC_except_table2694
- GCC_except_table2697
- GCC_except_table2704
- GCC_except_table2754
- GCC_except_table2758
- GCC_except_table2929
- GCC_except_table2933
- GCC_except_table3013
- GCC_except_table946
- GCC_except_table999
- _objc_msgSend$_concurrent_slowGenerateCacheEntryWithFileHandle:URL:identifier:uuid:schemaVersion:posixOwnership:instanceUUID:containerPath:
- _objc_msgSend$initWithContext:identities:createIfNecessary:fuzzyMatchTransient:
CStrings:
+ "20:22:26"
+ "<Metadata DP Repair: classes = "
+ "ContainerManagerCommon_Internal.MCMMetadataDataProtectionRepair"
+ "Could not list containers to repair metadata data protection; path = 🔒%{private}s, error = %@"
+ "Could not restore class D on container metadata; path = 🔒%{private}s, error = %@"
+ "Deferring container whose metadata cannot be read yet; path = %@, error = %@"
+ "MobileContainerManager-833.40.18.0.1~18"
+ "Refusing to claim an un-instanced container while [%@] holds a container whose metadata cannot be read; requested = [%@]"
+ "Refusing to delete a mismatched instance while [%@] holds a container whose metadata cannot be read; requested = [%@], existing = [%@]"
+ "RepairMetadataDataProtection"
+ "Reporting a lookup miss in [%@] as unavailable rather than absent; the class holds a container whose metadata cannot be read"
+ "Restored class D on container metadata; path = 🔒%{private}s"
+ "Sep 27 2026"
- "22:57:49"
- "MobileContainerManager-833.40.16~68"
- "Sep 11 2026"
```
