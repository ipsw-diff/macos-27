## AppStoreDaemon

> `/System/Library/PrivateFrameworks/AppStoreDaemon.framework/Versions/A/AppStoreDaemon`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_arraydata`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_dictobj`
- `__DATA_DIRTY.__objc_data`

```diff

-13.0.43.0.0
-  __TEXT.__text: 0x5f9f4
-  __TEXT.__objc_methlist: 0x945c
-  __TEXT.__const: 0x2c8
-  __TEXT.__cstring: 0x10a57
-  __TEXT.__constg_swiftt: 0x50
-  __TEXT.__swift5_typeref: 0x4a
-  __TEXT.__swift5_builtin: 0x14
-  __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__swift5_reflstr: 0x89
-  __TEXT.__swift5_fieldmd: 0x5c
-  __TEXT.__swift5_types: 0x8
-  __TEXT.__swift5_proto: 0xc
-  __TEXT.__gcc_except_tab: 0x940
-  __TEXT.__oslogstring: 0x3046
-  __TEXT.__unwind_info: 0x1bb0
+13.0.52.1.2
+  __TEXT.__text: 0x66d00
+  __TEXT.__objc_methlist: 0x95a4
+  __TEXT.__const: 0x11a8
+  __TEXT.__cstring: 0x10a89
+  __TEXT.__constg_swiftt: 0x1a8
+  __TEXT.__swift5_typeref: 0x324
+  __TEXT.__swift5_builtin: 0x28
+  __TEXT.__swift5_mpenum: 0x10
+  __TEXT.__swift5_reflstr: 0xf8
+  __TEXT.__swift5_fieldmd: 0x278
+  __TEXT.__swift5_types: 0x38
+  __TEXT.__swift5_proto: 0xf0
+  __TEXT.__gcc_except_tab: 0x950
+  __TEXT.__oslogstring: 0x3003
+  __TEXT.__unwind_info: 0x1e20
+  __TEXT.__eh_frame: 0xa8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x378
-  __DATA_CONST.__objc_classlist: 0x538
+  __DATA_CONST.__objc_classlist: 0x548
   __DATA_CONST.__objc_catlist: 0x50
-  __DATA_CONST.__objc_protolist: 0x168
+  __DATA_CONST.__objc_protolist: 0x170
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3c00
-  __DATA_CONST.__objc_protorefs: 0xd0
-  __DATA_CONST.__objc_superrefs: 0x2a8
+  __DATA_CONST.__objc_selrefs: 0x3c78
+  __DATA_CONST.__objc_protorefs: 0xd8
+  __DATA_CONST.__objc_superrefs: 0x2b0
   __DATA_CONST.__objc_arraydata: 0x30
-  __DATA_CONST.__got: 0x450
-  __AUTH_CONST.__const: 0x2310
-  __AUTH_CONST.__cfstring: 0x4a40
-  __AUTH_CONST.__objc_const: 0x134e8
+  __DATA_CONST.__got: 0x4d0
+  __AUTH_CONST.__const: 0x29c8
+  __AUTH_CONST.__cfstring: 0x4920
+  __AUTH_CONST.__objc_const: 0x13630
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__auth_got: 0x3b8
-  __AUTH.__objc_data: 0x14f0
-  __DATA.__objc_ivar: 0xd24
-  __DATA.__data: 0x10f8
-  __DATA.__bss: 0x190
+  __AUTH_CONST.__auth_got: 0x578
+  __AUTH.__objc_data: 0x15b0
+  __AUTH.__data: 0x28
+  __DATA.__objc_ivar: 0xd2c
+  __DATA.__data: 0x1428
+  __DATA.__bss: 0x1e10
   __DATA_DIRTY.__objc_ivar: 0x90
   __DATA_DIRTY.__objc_data: 0x1f40
   __DATA_DIRTY.__data: 0xc

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3617
-  Symbols:   7252
-  CStrings:  1163
+  Functions: 3840
+  Symbols:   7395
+  CStrings:  1162
 
Symbols:
+ +[ASDAppQuery queryForAllAppClips]
+ +[ASDAppQuery queryForAllApps]
+ +[ASDAppQuery queryForNoApps]
+ +[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]
+ +[ASDMacDaemonCallback interface]
+ -[ASDAppQuery _executeQueryWithConditionsData:onDeviceWithPairingID:withCompletion:]
+ -[ASDAppQuery initWithConditionsData:]
+ -[ASDAppQuery initWithConditionsData:queryExecutor:serviceBroker:notificationCenter:]
+ -[ASDAppQueryExecutor executeQueryWithConditionsData:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]
+ -[ASDMacDaemonCallback .cxx_destruct]
+ -[ASDMacDaemonCallback init]
+ -[ASDPurchase isDSIDlessThatUpdates]
+ -[ASDPurchase setIsDSIDlessThatUpdates:]
+ -[ASDServiceBroker getMacDaemonCallbackServiceWithCompletionHandler:]
+ -[ASDServiceBroker getMacDaemonCallbackServiceWithError:]
+ GCC_except_table70
+ GCC_except_table84
+ GCC_except_table87
+ GCC_except_table90
+ OBJC_IVAR_$_ASDAppQuery._conditions
+ OBJC_IVAR_$_ASDMacDaemonCallback._serviceBroker
+ OBJC_IVAR_$_ASDPurchase._isDSIDlessThatUpdates
+ _OBJC_CLASS_$_ASDAppQueryConditions
+ _OBJC_CLASS_$_ASDMacDaemonCallback
+ _OBJC_METACLASS_$_ASDAppQueryConditions
+ _OBJC_METACLASS_$_ASDMacDaemonCallback
+ __109-[ASDAppQueryExecutor executeQueryWithConditionsData:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]_block_invoke
+ __162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke
+ __162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_2
+ __162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_3
+ __84-[ASDAppQuery _executeQueryWithConditionsData:onDeviceWithPairingID:withCompletion:]_block_invoke
+ __CLASS_METHODS_ASDAppQueryConditions
+ __CLASS_PROPERTIES_ASDAppQueryConditions
+ __DATA_ASDAppQueryConditions
+ __INSTANCE_METHODS_ASDAppQueryConditions
+ __METACLASS_DATA_ASDAppQueryConditions
+ __OBJC_$_CLASS_METHODS_ASDMacDaemonCallback
+ __OBJC_$_INSTANCE_METHODS_ASDMacDaemonCallback
+ __OBJC_$_INSTANCE_VARIABLES_ASDMacDaemonCallback
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_ASDMacDaemonCallbackServiceProtocol
+ __OBJC_$_PROTOCOL_METHOD_TYPES_ASDMacDaemonCallbackServiceProtocol
+ __OBJC_CLASS_RO_$_ASDMacDaemonCallback
+ __OBJC_LABEL_PROTOCOL_$_ASDMacDaemonCallbackServiceProtocol
+ __OBJC_METACLASS_RO_$_ASDMacDaemonCallback
+ __OBJC_PROTOCOL_$_ASDMacDaemonCallbackServiceProtocol
+ __OBJC_PROTOCOL_REFERENCE_$_ASDMacDaemonCallbackServiceProtocol
+ ___109-[ASDAppQueryExecutor executeQueryWithConditionsData:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]_block_invoke
+ ___162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke
+ ___162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_2
+ ___162+[ASDAppQueryExecutor _executeQueryWithConditionsData:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_3
+ ___33-[ASDExtensionMonitor invalidate]_block_invoke
+ ___57-[ASDServiceBroker getMacDaemonCallbackServiceWithError:]_block_invoke
+ ___57-[ASDServiceBroker getMacDaemonCallbackServiceWithError:]_block_invoke_2
+ ___69-[ASDServiceBroker getMacDaemonCallbackServiceWithCompletionHandler:]_block_invoke
+ ___84-[ASDAppQuery _executeQueryWithConditionsData:onDeviceWithPairingID:withCompletion:]_block_invoke
+ ___ErrorWithUnderlyingErrorAndConditionsData
+ ___block_descriptor_48_e8_32r40r_e79_v24?0"<ASDMacDaemonCallbackServiceProtocol><NSXPCProxyCreating>"8"NSError"16l
+ ___swift_instantiateConcreteTypeFromMangledNameAbstractV2
+ ___swift_instantiateConcreteTypeFromMangledNameV2
+ ___swift_memcpy17_8
+ ___swift_memcpy1_1
+ ___swift_project_boxed_opaque_existential_1
+ __swiftImmortalRefCount
+ __swift_stdlib_malloc_size
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaA10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaA10CodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaA10CodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotA10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotA10CodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotA10CodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemA10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemA10CodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemA10CodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0A14ClipCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0A14ClipCodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0A14ClipCodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0B17ItemIDsCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0B17ItemIDsCodingKeysOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0B17ItemIDsCodingKeysOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0bA10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0bA10CodingKeysOs0L3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0bA10CodingKeysOs0L3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysOs0L3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysOs0L3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysOs0M3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysOs0M3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysOSHAASQ
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysOs0N3KeyAAs23CustomStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysOs0N3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLOSHAASQ
+ _get_enum_tag_for_layout_string 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
+ _malloc_size
+ _memcpy
+ _memmove
+ _objc_msgSend$conditionsData:matchesApp:
+ _objc_msgSend$conditionsDataByCombining:
+ _objc_msgSend$conditionsDataForAppClip:
+ _objc_msgSend$conditionsDataForBetaApp:
+ _objc_msgSend$conditionsDataForBundleIDs:
+ _objc_msgSend$conditionsDataForBundlePath:
+ _objc_msgSend$conditionsDataForOcelotApp:
+ _objc_msgSend$conditionsDataForSoftwarePlatform:
+ _objc_msgSend$conditionsDataForStoreApp:
+ _objc_msgSend$conditionsDataForStoreItemIDs:
+ _objc_msgSend$conditionsDataMatchingAllApps
+ _objc_msgSend$conditionsDataMatchingNoApps
+ _objc_msgSend$descriptionForConditionsData:
+ _objc_msgSend$executeQueryWithConditionsData:onDeviceWithPairingID:remoteDeviceID:withResultHandler:
+ _objc_msgSend$executeQueryWithConditionsData:onRemoteDevice:withReplyHandler:
+ _objc_msgSend$executeQueryWithConditionsData:withReplyHandler:
+ _objc_msgSend$getMacDaemonCallbackServiceWithReplyHandler:
+ _objc_msgSend$initWithBool:
+ _objc_msgSend$initWithConditionsData:queryExecutor:serviceBroker:notificationCenter:
+ _objc_msgSend$isBetaApp
+ _objc_msgSend$isOcelot
+ _objc_msgSend$isSystemApp
+ _objc_msgSend$shared
+ _swift_allocError
+ _swift_allocObject
+ _swift_arrayInitWithCopy
+ _swift_errorRelease
+ _swift_getObjCClassFromMetadata
+ _swift_getObjCClassMetadata
+ _swift_getTypeByMangledNameInContext2
+ _swift_getTypeByMangledNameInContextInMetadataState2
+ _swift_isUniquelyReferenced_nonNull_native
+ _swift_once
+ _swift_retain
+ _swift_unexpectedError
+ _swift_unknownObjectRelease
+ _swift_willThrow
+ _symbolic Say_____G 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
+ _symbolic Say_____G s5Int64V
+ _symbolic Sb
+ _symbolic Si
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaA10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotA10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemA10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0A14ClipCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0B17ItemIDsCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0bA10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysO
+ _symbolic _____ 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaD10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotD10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemD10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0D14ClipCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0E17ItemIDsCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0eD10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysO
+ _symbolic _____y_____G s22KeyedDecodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO04BetaD10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06OcelotD10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO06SystemD10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0D14ClipCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0E17ItemIDsCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO0eD10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO10CodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO15NeverCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO19BundleIDsCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO20BundlePathCodingKeysO
+ _symbolic _____y_____G s22KeyedEncodingContainerV 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO26SoftwarePlatformCodingKeysO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC s5Int64V
+ _symbolic _____y______pG s23_ContiguousArrayStorageC s7CVarArgP
+ _symbolic ypXmT______t s13DecodingErrorO7ContextV
+ _type_layout_string 14AppStoreDaemon9Condition33_B5A07C0485326B1035FBF74A41596CB2LLO
- +[ASDAppQuery _defaultExecutor]
- +[ASDAppQuery anyWithPredicate:withResultHandler:]
- +[ASDAppQuery queryDefaultPairedWatchForBetaApps]
- +[ASDAppQuery queryForBetaAppsOnDeviceWithPairingID:]
- +[ASDAppQuery queryForSystemAppsOnDeviceWithPairingID:]
- +[ASDAppQuery queryWithPredicate:]
- +[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]
- -[ASDAppQuery _executeQueryWithPredicate:onDeviceWithPairingID:withCompletion:]
- -[ASDAppQuery initWithPredicate:]
- -[ASDAppQuery initWithPredicate:queryExecutor:serviceBroker:notificationCenter:]
- -[ASDAppQuery predicate]
- -[ASDAppQueryExecutor executeQueryWithPredicate:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]
- GCC_except_table74
- GCC_except_table82
- GCC_except_table85
- OBJC_IVAR_$_ASDAppQuery._predicate
- __104-[ASDAppQueryExecutor executeQueryWithPredicate:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]_block_invoke
- __157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke
- __157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_2
- __157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_3
- __79-[ASDAppQuery _executeQueryWithPredicate:onDeviceWithPairingID:withCompletion:]_block_invoke
- ___104-[ASDAppQueryExecutor executeQueryWithPredicate:onDeviceWithPairingID:remoteDeviceID:withResultHandler:]_block_invoke
- ___157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke
- ___157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_2
- ___157+[ASDAppQueryExecutor _executeQueryWithPredicate:isForUpdates:reloadingFromServer:onDeviceWithPairingID:remoteDeviceID:usingServiceBroker:withResultHandler:]_block_invoke_3
- ___50+[ASDAppQuery anyWithPredicate:withResultHandler:]_block_invoke
- ___79-[ASDAppQuery _executeQueryWithPredicate:onDeviceWithPairingID:withCompletion:]_block_invoke
- ___ErrorWithUnderlyingErrorAndPredicate
- _objc_msgSend$executeQueryWithPredicate:onDeviceWithPairingID:remoteDeviceID:withResultHandler:
- _objc_msgSend$executeQueryWithPredicate:onRemoteDevice:withReplyHandler:
- _objc_msgSend$executeQueryWithPredicate:withReplyHandler:
- _objc_msgSend$filteredArrayUsingPredicate:
- _objc_msgSend$initWithPredicate:
- _objc_msgSend$initWithPredicate:onDeviceWithPairingID:
- _objc_msgSend$initWithPredicate:queryExecutor:serviceBroker:notificationCenter:
- _objc_msgSend$notPredicateWithSubpredicate:
- _objc_msgSend$predicateWithFormat:
- _objc_msgSend$reportDeprecatedAPIToLibraryService:
CStrings:
+ " isDSIDlessThatUpdates: 1"
+ "<invalid conditions>"
+ "AppStoreDaemon/ASDAppQuery.swift"
+ "Invalid number of keys found, expected one."
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Services/InstallApps/Metadata/ASDWatchAppMetadata.m:156 : Unsupported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Services/InstallApps/Metadata/ASDWatchAppMetadata.m:162 : Unsupported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Services/InstallApps/Metadata/ASDWatchAppMetadata.m:167 : Unsupported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Services/InstallApps/Metadata/ASDWatchAppMetadata.m:172 : Unsupported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupRequest_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupResponse_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupResponse_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupResponse_macOS.m:32 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupResponse_macOS.m:38 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:102 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:106 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:112 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:116 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:120 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:136 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:140 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:148 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:30 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:34 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:40 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:44 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:48 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:52 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:58 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:62 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:66 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:70 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:76 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:80 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:84 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:88 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:94 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:98 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAppClusterMapping_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAppClusterMapping_macOS.m:28 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAppClusterMapping_macOS.m:40 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAppClusterMapping_macOS.m:44 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequestOptions_macOS.m:30 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequest_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCoding_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCoding_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCoding_macOS.m:32 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCoding_macOS.m:38 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCompleteCoordinatorsRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCompleteCoordinatorsRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCreatePlaceholdersRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCreatePlaceholdersRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCreatePlaceholdersRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCreatePlaceholdersRequest_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:28 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:36 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:42 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:48 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:52 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:56 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:61 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:65 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:69 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDownloadQueueRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDownloadQueueRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDEphemeralRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestRequest_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestResponse_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestResponse_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestResponse_macOS.m:30 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoResponse_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoResponse_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoResponse_macOS.m:30 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoUpdateRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequestResponse_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequestResponse_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequest_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:34 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:46 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:50 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobAsset_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobAsset_macOS.m:28 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobAsset_macOS.m:40 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobAsset_macOS.m:44 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManagerOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManagerOptions_macOS.m:28 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManagerOptions_macOS.m:40 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManagerOptions_macOS.m:44 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManager_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManager_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:34 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:46 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:50 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobOptions_macOS.m:32 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobOptions_macOS.m:36 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJob_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJob_macOS.m:28 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJob_macOS.m:40 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJob_macOS.m:44 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsRequest_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsRequest_macOS.m:32 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsResponse_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsResponse_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDManagedApplicationRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDManagedApplicationRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDManagedApplicationRequest_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDManagedApplicationRequest_macOS.m:32 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequest_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequest_macOS.m:34 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPersistentRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPersistentRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPersistentRequest_macOS.m:30 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPersonalizationStore_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPostBulletinRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPostBulletinRequest_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPostBulletinRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurchaseRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurchaseRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurchaseRequest_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurchaseRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsRequest_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsResponse_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsResponse_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsResponse_macOS.m:30 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsResponse_macOS.m:35 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppRequest_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppResponse_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppResponse_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppResponse_macOS.m:29 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppResponse_macOS.m:35 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:34 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:46 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:50 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPushCacheDeleteUpdateRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPushCacheDeleteUpdateRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRegisterListenerOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRegisterListenerOptions_macOS.m:32 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRegisterListenerOptions_macOS.m:36 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequestBroker_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequestBroker_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequestBroker_macOS.m:28 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequest_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequest_macOS.m:36 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequest_macOS.m:40 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequestResponse_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequestResponse_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequest_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequestOptions_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequestOptions_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequestOptions_macOS.m:30 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequest_macOS.m:20 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequest_macOS.m:28 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRollableLog_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRollableLog_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSoftwareUpdateMetrics_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSoftwareUpdateMetrics_macOS.m:28 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSoftwareUpdateMetrics_macOS.m:40 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSoftwareUpdateMetrics_macOS.m:44 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSystemAppRequest_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSystemAppRequest_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSystemAppRequest_macOS.m:30 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateMetricsStore_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateMetricsStore_macOS.m:26 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateMetricsStore_macOS.m:30 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdatePollMetrics_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdatePollMetrics_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdatePollMetrics_macOS.m:32 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateWatchApps_macOS.m:18 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateWatchApps_macOS.m:24 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/XPC/Updates/ASDSoftwareUpdatesStore_macOS.m:169 : Not supported on macOS"
+ "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GNiMKK/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/XPC/Updates/ASDSoftwareUpdatesStore_macOS.m:200 : Not supported on macOS"
+ "isDSIDlessThatUpdates"
+ "isStoreApp == %@"
+ "isSystemApp == %@"
+ "storeItemID IN %@"
+ "v24@?0@\"<ASDMacDaemonCallbackServiceProtocol><NSXPCProxyCreating>\"8@\"NSError\"16"
- "+[ASDAppQuery queryDefaultPairedWatchForBetaApps:]"
- "Please note that this ASDAppQuery doesn't return real results yet."
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Services/InstallApps/Metadata/ASDWatchAppMetadata.m:156 : Unsupported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Services/InstallApps/Metadata/ASDWatchAppMetadata.m:162 : Unsupported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Services/InstallApps/Metadata/ASDWatchAppMetadata.m:167 : Unsupported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Services/InstallApps/Metadata/ASDWatchAppMetadata.m:172 : Unsupported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupRequest_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupResponse_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupResponse_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupResponse_macOS.m:32 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAccountLookupResponse_macOS.m:38 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:102 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:106 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:112 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:116 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:120 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:136 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:140 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:148 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:30 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:34 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:40 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:44 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:48 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:52 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:58 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:62 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:66 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:70 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:76 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:80 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:84 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:88 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:94 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAggregateClusterMappingData_macOS.m:98 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAppClusterMapping_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAppClusterMapping_macOS.m:28 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAppClusterMapping_macOS.m:40 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDAppClusterMapping_macOS.m:44 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequestOptions_macOS.m:30 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDClaimApplicationsRequest_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCoding_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCoding_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCoding_macOS.m:32 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCoding_macOS.m:38 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCompleteCoordinatorsRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCompleteCoordinatorsRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCreatePlaceholdersRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCreatePlaceholdersRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCreatePlaceholdersRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDCreatePlaceholdersRequest_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:28 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:36 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:42 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:48 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:52 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:56 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:61 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:65 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDebug_macOS.m:69 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDownloadQueueRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDDownloadQueueRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDEphemeralRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestRequest_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestResponse_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestResponse_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDExternalManifestResponse_macOS.m:30 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoResponse_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoResponse_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoResponse_macOS.m:30 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDIAPInfoUpdateRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequestResponse_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequestResponse_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDInstallManifestRequest_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:34 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:46 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobActivity_macOS.m:50 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobAsset_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobAsset_macOS.m:28 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobAsset_macOS.m:40 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobAsset_macOS.m:44 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManagerOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManagerOptions_macOS.m:28 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManagerOptions_macOS.m:40 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManagerOptions_macOS.m:44 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManager_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManager_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:34 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:46 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobManifest_macOS.m:50 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobOptions_macOS.m:32 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJobOptions_macOS.m:36 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJob_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJob_macOS.m:28 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJob_macOS.m:40 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDJob_macOS.m:44 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsRequest_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsRequest_macOS.m:32 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsResponse_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDLaunchableAppsResponse_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDManagedApplicationRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDManagedApplicationRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDManagedApplicationRequest_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDManagedApplicationRequest_macOS.m:32 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequest_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDMigrationRequest_macOS.m:34 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPersistentRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPersistentRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPersistentRequest_macOS.m:30 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPersonalizationStore_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPostBulletinRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPostBulletinRequest_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPostBulletinRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurchaseRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurchaseRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurchaseRequest_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurchaseRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsRequest_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsResponse_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsResponse_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsResponse_macOS.m:30 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeAppsResponse_macOS.m:35 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppRequest_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppResponse_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppResponse_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppResponse_macOS.m:29 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableAppResponse_macOS.m:35 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:34 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:46 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPurgeableApp_macOS.m:50 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPushCacheDeleteUpdateRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDPushCacheDeleteUpdateRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRegisterListenerOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRegisterListenerOptions_macOS.m:32 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRegisterListenerOptions_macOS.m:36 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequestBroker_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequestBroker_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequestBroker_macOS.m:28 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequest_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequest_macOS.m:36 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRequest_macOS.m:40 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequestResponse_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequestResponse_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreApplicationsRequest_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequestOptions_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequestOptions_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequestOptions_macOS.m:30 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequest_macOS.m:20 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRestoreDemotedApplicationsRequest_macOS.m:28 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRollableLog_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDRollableLog_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSoftwareUpdateMetrics_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSoftwareUpdateMetrics_macOS.m:28 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSoftwareUpdateMetrics_macOS.m:40 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSoftwareUpdateMetrics_macOS.m:44 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSystemAppRequest_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSystemAppRequest_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDSystemAppRequest_macOS.m:30 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateMetricsStore_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateMetricsStore_macOS.m:26 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateMetricsStore_macOS.m:30 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdatePollMetrics_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdatePollMetrics_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdatePollMetrics_macOS.m:32 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateWatchApps_macOS.m:18 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/Stubs/ASDUpdateWatchApps_macOS.m:24 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/XPC/Updates/ASDSoftwareUpdatesStore_macOS.m:169 : Not supported on macOS"
- "Unimplemented at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.uT7COR/Sources/AppStoreDaemon/Libraries/AppStoreDaemon/XPC/Updates/ASDSoftwareUpdatesStore_macOS.m:200 : Not supported on macOS"
- "bundleID IN %@"
- "isAppClip == NO AND isBetaApp == YES AND storeItemID IN %@"
- "isAppClip == NO AND isStoreApp == YES"
- "isAppClip == NO AND isStoreApp == YES AND storeItemID IN %@"
- "isAppClip == YES AND isStoreApp == YES AND storeItemID == %lld"
- "isBetaApp == YES"
- "isOcelot == YES"
- "isSystemApp == YES"
```
