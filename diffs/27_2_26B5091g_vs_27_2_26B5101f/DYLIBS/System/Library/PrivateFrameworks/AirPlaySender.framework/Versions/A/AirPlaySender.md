## AirPlaySender

> `/System/Library/PrivateFrameworks/AirPlaySender.framework/Versions/A/AirPlaySender`

```diff

-1005.8.1.0.0
-  __TEXT.__text: 0x1cd438
-  __TEXT.__objc_methlist: 0x92c
+1005.12.1.0.0
+  __TEXT.__text: 0x1ce134
+  __TEXT.__objc_methlist: 0x95c
   __TEXT.__const: 0xd530
-  __TEXT.__gcc_except_tab: 0x62c
-  __TEXT.__cstring: 0x71a1d
+  __TEXT.__gcc_except_tab: 0x64c
+  __TEXT.__cstring: 0x71b15
   __TEXT.__dlopen_cstrs: 0x164
   __TEXT.__oslogstring: 0xb55
-  __TEXT.__unwind_info: 0x71f8
+  __TEXT.__unwind_info: 0x7270
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4328
+  __DATA_CONST.__const: 0x4358
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb08
+  __DATA_CONST.__objc_selrefs: 0xb40
   __DATA_CONST.__objc_superrefs: 0x20
   __DATA_CONST.__objc_arraydata: 0x170
-  __DATA_CONST.__got: 0x1de0
-  __AUTH_CONST.__const: 0x7220
-  __AUTH_CONST.__cfstring: 0x105c0
+  __DATA_CONST.__got: 0x1df0
+  __AUTH_CONST.__const: 0x72b0
+  __AUTH_CONST.__cfstring: 0x10600
   __AUTH_CONST.__objc_const: 0xc58
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_dictobj: 0x1b8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 9073
-  Symbols:   8807
-  CStrings:  9270
+  Functions: 9102
+  Symbols:   8844
+  CStrings:  9247
 
Symbols:
+ -[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]
+ -[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeer:groupID:]
+ -[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeersForGroup:peers:]
+ -[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]
+ GCC_except_table33
+ GCC_except_table37
+ GCC_except_table39
+ GCC_except_table41
+ _APEndpointPayloadRequiresCompositionRefresh
+ _APPairingClientCoreUtilsCopyMigratableUngroupedPeers
+ _APPairingClientCoreUtilsCreateOrphanedPeersFromGroupInfo
+ _APPairingClientCoreUtilsPatchUnpairedPeerWithGroupID
+ _APSAudioHoseMetricCollectorSetSenderRTMetrics
+ _FigCFSetGetCount
+ _FigSignalErrorAtGM
+ __60-[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]_block_invoke
+ __63-[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]_block_invoke
+ __APPairingClientCoreUtilsCreateOrphanedPeersFromGroupInfo_block_invoke
+ ___60-[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]_block_invoke
+ ___63-[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]_block_invoke
+ ___APPairingClientCoreUtilsCreateOrphanedPeersFromGroupInfo_block_invoke
+ ___block_descriptor_40_e8_32o_e15_v24?0r^v8r^v16l
+ ___block_descriptor_48_e8_32o40o_e29_v32?0"CUPairedPeer"8Q16^B24l
+ ___block_descriptor_48_e8_32o40r_e29_v24?0"NSArray"8"NSError"16l
+ ___coreUtilsPairing_updatePairingGroupInfoIfNeeded_block_invoke_2
+ ___endpointCluster_reconcileResponsiveAudioTransports_block_invoke
+ __coreUtilsPairing_updatePairingGroupInfoIfNeeded_block_invoke_2
+ _endpointCluster_activateSubEndpointForcingTransportIfNeeded
+ _endpointCluster_copyActivatedSubEndpointsByTransportType
+ _endpointCluster_copyActivationOptionsForcingTransportType
+ _endpointCluster_copyForcedTransportForResponsiveAudio
+ _kAPEndpointAggregateCreationOptionKey_ClusterType
+ _kFigEndpointActivateOptionKey_ForcedTransportType
+ _kFigEndpointForcedTransportType_Infra
+ _objc_msgSend$UUIDString
+ _objc_msgSend$getPairedPeersWithOptions:completion:
+ _objc_msgSend$migrateUngroupedPeer:groupID:
+ _objc_msgSend$removePairedPeer:
+ _objc_msgSend$removePairedPeer:options:completion:
+ endpointCluster_copyActivatedSubEndpointsByTransportType
+ endpointCluster_copyActivationOptionsForcingTransportType
- GCC_except_table26
- _FigSignalErrorAt3
- __coreUtilsPairing_updatePairingGroupInfoIfNeeded_block_invoke
- _endpointCluster_getNumSubEndpointsActivated
CStrings:
+ "\t[indexed] identifier: %@ infoKeys: %@\n"
+ "\t[ungrouped] identifier: %@  publicKey: %@\n"
+ "%s signalled err=%d at <>:%d"
+ "-[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]"
+ "-[CUPairingManager(APPairingClientCoreUtils) allPairedPeers]_block_invoke"
+ "-[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeer:groupID:]"
+ "-[CUPairingManager(APPairingClientCoreUtils) migrateUngroupedPeersForGroup:peers:]"
+ "-[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]"
+ "-[CUPairingManager(APPairingClientCoreUtils) removePairedPeer:]_block_invoke"
+ "1005.12.1"
+ "APPairingClientCoreUtilsPatchUnpairedPeerWithGroupID"
+ "Failed to get all paired peers: %#m\n"
+ "Failed to patch ungrouped peer %@ for migration\n"
+ "Failed to remove paired peer [%{ptr}]: %#m\n"
+ "Failed to save migrated peer %@ — migration skipped: %#m\n"
+ "Getting all paired peers\n"
+ "Got %d paired peers\n"
+ "Migrated ungrouped peer %@ to group-indexed entry\n"
+ "OSStatus endpointCluster_activateSubEndpointForcingTransportIfNeeded(FigEndpointRef, FigEndpointRef)"
+ "Removed paired peer [%{ptr}]: %@\n"
+ "Removing paired peer [%{ptr}]: %@\n"
+ "[%{ptr}] Forcing %@ transport for activating subEndpoint [%{ptr}]"
+ "[%{ptr}] RA Reconcile: Migrating subEndpoint [%{ptr}] from NAN to Infra"
+ "[%{ptr}] RA Reconcile: Reactivate subEndpoint [%{ptr}] error: %m"
+ "[%{ptr}] RA Reconcile: all subEndpoints already using %@"
+ "[%{ptr}] Removing orphaned pairing group peer [%{ptr}] with identifier %@\n"
+ "[%{ptr}] SubEndpointStream(%{ptr}) is dissociated, excluding it from aggregate capabilities"
+ "aggregateClusterType"
+ "endpointCluster_copyActivatedSubEndpointsByTransportType"
+ "endpointCluster_copyActivationOptionsForcingTransportType"
+ "endpointCluster_reconcileResponsiveAudioTransports"
+ "endpointCluster_reconcileResponsiveAudioTransports_block_invoke"
+ "group info member count: %lu\n"
+ "group-indexed peers: %lu\n"
+ "senderClusterType"
+ "ungrouped peers to migrate: %lu\n"
+ "void coreUtilsPairing_updatePairingGroupInfoIfNeeded(APPairingClientRef, CFDictionaryRef, CUPairedPeer *)_block_invoke_2"
+ "void endpointCluster_reconcileResponsiveAudioTransports(FigEndpointRef, CFDictionaryRef *)"
+ "void endpointCluster_reconcileResponsiveAudioTransports(FigEndpointRef, CFDictionaryRef *)_block_invoke"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "-108"
- "-876"
- "-877"
- "-878"
- "-879"
- "-880"
- "1005.8.1"
- "APAudioEngineBufferedAdapter.c"
- "APAudioSourceSharedMemory.c"
- "APEndpoint.m"
- "APEndpointPlaybackSessionRemoteControl.m"
- "APEndpointStreamAggregateAudio.c"
- "APSampleBufferConsumerForEndpointStreamAudioEngine.c"
- "APVirtualDisplayTestSink.c"
- "Action not supported"
- "Allocation error"
- "Audio source has been invalidated"
- "Cannot register path"
- "Failed allocating audio buffer"
- "Failed to create bufferMemObject"
- "Failed to create deep copy"
- "Failed to create stateMemObject"
- "Failed to de-serialize"
- "Failed to serialize"
- "Invalid Trigger Token"
- "Item is NULL"
- "NULL audioEngine"
- "NULL bufferMemObject in message"
- "NULL stateMemObject in message"
- "NULL trigger"
- "NULL triggerTokenOut"
- "No data in response"
- "No incoming message"
- "No matched request found"
- "No trigger installed"
- "Object invalidated"
- "Only support one trigger installed at a time"
- "[%{ptr}] Activate SubEndpoint [%{ptr}] on reconcile transports failed %m"
- "[%{ptr}] RA stereo pair transport mismatch detected, [%{ptr}] on %@, [%{ptr}] on %@, forcing [%{ptr}] to Infra"
- "[%{ptr}] RA stereo pair, no transport mismatch [%{ptr}] on %@, [%{ptr}] on %@"
- "alloc failed"
- "bufferMemory region maps to NULL"
- "bufferMemorySize is zero"
- "can't find valid video track"
- "endpointCluster_reconcileSubEndpointTransportsIfNeeded"
- "err"
- "kCMBaseObjectError_AllocationFailed"
- "kCMBaseObjectError_Invalidated"
- "kCMBaseObjectError_ParamErr"
- "kCMBaseObjectError_ValueNotAvailable"
- "kFigEndpointError_AllocationFailed"
- "kFigEndpointPlaybackSessionError_AllocationFailed"
- "kFigEndpointPlaybackSessionError_InvalidParameter"
- "kFigEndpointStreamAudioEngineError_AllocationFailed"
- "messageID is missing in response event"
- "sbceas_InstallLowWaterTrigger_block_invoke"
- "sbceas_RemoveLowWaterTrigger_block_invoke"
- "stateMemObject maps to NULL"
- "stateMemoryLength < sizeof(RingState)"
- "type is missing in response event"
- "void endpointCluster_reconcileSubEndpointTransportsIfNeeded(FigEndpointRef, FigEndpointRef)"
```
