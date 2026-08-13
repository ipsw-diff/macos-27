## com.apple.driver.AppleCredentialManager

> `com.apple.driver.AppleCredentialManager`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`

```diff

-949.0.13.0.0
-  __TEXT.__cstring: 0x1c7bc
+949.0.17.0.0
+  __TEXT.__cstring: 0x1cc97
   __TEXT.__const: 0x4a0
-  __TEXT_EXEC.__text: 0x7cdd8
+  __TEXT_EXEC.__text: 0x7dae8
   __TEXT_EXEC.__auth_stubs: 0x750
   __DATA.__data: 0xa501
   __DATA.__common: 0x9c8

   __DATA_CONST.__auth_got: 0x3a8
   __DATA_CONST.__got: 0xb8
   __DATA_CONST.__auth_ptr: 0x30
-  Functions: 1368
-  Symbols:   2070
-  CStrings:  2936
+  Functions: 1370
+  Symbols:   2072
+  CStrings:  2965
 
Symbols:
+ _TRMMultiState_ReplaceInBuffer
+ _Util_ThumbAndPayDefaut
+ copyCredentials.kalloc_type_view_9360
- copyCredentials.kalloc_type_view_9320
Functions:
~ __findValidCredential : 3816 -> 3832
+ _Util_ThumbAndPayDefaut
~ __ZN30ACMRestrictedModeKernelService12_startPolicyEbhhhh : 4412 -> 4504
~ _Env_SetVariableWithParams : 2528 -> 2572
~ _DefaultValueProvider_ThumbAndPayEnabled : 444 -> 448
~ _TRMMultiState_ReadFromBuffer : 3936 -> 4392
~ _TRMMultiState_WriteToBuffer : 1480 -> 1700
+ _TRMMultiState_ReplaceInBuffer
~ __ZN28AppleCredentialManagerShared33_checkRequiredCommandEntitlementsEP13acm_command_tmNS_23CheckEntitlementsLambdaE : 1340 -> 1356
~ _DeserializeCredential : 1520 -> 1524
~ _LibSer_SEPControl_Deserialize : 384 -> 528
~ _LibSer_SEPControlResponse_Deserialize : 216 -> 296
~ _Storage_GetDataProperty : 2392 -> 2416
~ _setData : 1860 -> 1936
~ __ZN32AppleCredentialManagerUserClient17extPerformCommandEP22AppleCredentialManagerPvP25IOExternalMethodArguments : 1308 -> 1768
~ __ZN22AppleCredentialManager19performCommandGatedEP18IOMemoryDescriptorS1_PjPK26ACMPerformCommandContextV3 : 2888 -> 2784
CStrings:
+ "!memcmp(state->cache.header.tag, (uint8_t[3])ACM_TRM_COMPACT_CACHE_TAG, sizeof(state->cache.header.tag))"
+ "!memcmp(state->policy.header.tag, (uint8_t[3])ACM_TRM_COMPACT_POLICY_TAG, sizeof(state->policy.header.tag))"
+ "%s: %s: *%s* replaced (size=%u->%u).\n"
+ "%s: %s: *acc-cache* saved (records=%u skipped=%u).\n"
+ "%s: %s: *config* saved (ver=%u size=%u).\n"
+ "%s: %s: *policy* saved (ver=%u size=%u).\n"
+ "%s: %s: [loaded] inSize=%u -> policyRead=%s configRead=NO accCacheRead=%s.\n"
+ "%s: %s: [replaced] bufSize=%u policyReplaced=%s configReplaced=%s.\n"
+ "%s: %s: [saved] outSize=%u policySaved=%s configSaved=%s accCacheSaved=%s.\n"
+ "*bufInOutSize <= bufCapacity"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/ACMKernelUtils.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/AppleCredentialManager.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/AppleCredentialManagerShared.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/AppleCredentialManagerUserClient.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMAccessoryCacheKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMAnalyticsKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMBridgeKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMFirstResponderKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMKeybagKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMLockdownModeKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMPersistentStoreKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMRestrictedModeAnalyticsKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMRestrictedModeIOState.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMRestrictedModeKernelService.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMRestrictedModeUtil.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMTRMInductivePolicy.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CommonCrypto.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CommonMem.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CommonTRMLegacy.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CommonUtil.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreAuthMethod.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreCmd.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreCred.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreCredSet.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreDER.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreDeveloperMode.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreEnv.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreExec.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreOTI.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CorePrague.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreReqAlgo.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreSEPControl.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreStats.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreStorage.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreStorageProtection.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreTRMAccCache.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreTRMMultiState.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreTimer.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreUserIntent.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CoreUtil.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/CredUtil.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/Credentials.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8yFSaa/Sources/AppleCredentialManager/common/LibSerialization.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ptmhHu/Sources/AppleCredentialManager_KernelLibs/ACMKernelLib/ACMKernelLib.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ptmhHu/Sources/AppleCredentialManager_KernelLibs/ACMKernelLib/ACMKernelTransport.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ptmhHu/Sources/AppleCredentialManager_KernelLibs/common/LibCall.c"
+ "21:56:46"
+ "Aug  5 2026"
+ "Aug  5 2026, 21:57:11"
+ "TRMMultiState_ReplaceInBuffer"
+ "buf"
+ "bufInOutSize"
+ "copied == srcLen"
+ "inData && inSize == sizeof(uid_t)"
+ "multiStateVersion || guardedStateVersion"
+ "newTotalSize <= bufCapacity"
+ "numRecords <= kACMTRMLegacyAccessoryCache_CacheSize"
+ "originalSize == sizeof(acm_command_t)"
+ "payloadOffset + oldPayloadSize <= curSize"
+ "payloadPos <= bufLen"
+ "pos + sizeof(ItemTag) <= curSize"
+ "pos == curSize"
+ "readPos + itemTag.payloadSize <= inBufferSize"
+ "remaining >= cmdSize"
+ "remaining >= respSize"
+ "remaining >= sizeof(uint32_t)"
+ "replaceInMultiStateBuffer"
+ "sizeof(accCacheRecordItem) + accCacheRecordItem.hashLen + accCacheRecordItem.dataLen + accCacheRecordItem.groupLen <= itemTag.payloadSize"
+ "srcLen > 0"
+ "srcRec->dataLen <= kACMTRMLegacyAccessoryCache_MaxDataSize"
+ "srcRec->hashLen <= kACMTRMLegacyAccessoryCache_MaxHashSize"
+ "total <= slot->maxDataSize"
- "%s: %s: [loaded] inSize=%u -> policyRead=%s configRead=%s accCacheRead=%s.\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/ACMKernelUtils.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/AppleCredentialManager.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/AppleCredentialManagerShared.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/AppleCredentialManagerUserClient.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMAccessoryCacheKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMAnalyticsKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMBridgeKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMFirstResponderKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMKeybagKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMLockdownModeKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMPersistentStoreKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMRestrictedModeAnalyticsKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMRestrictedModeIOState.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMRestrictedModeKernelService.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMRestrictedModeUtil.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/AppleCredentialManager/Services/ACMTRMInductivePolicy.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CommonCrypto.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CommonMem.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CommonTRMLegacy.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CommonUtil.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreAuthMethod.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreCmd.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreCred.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreCredSet.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreDER.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreDeveloperMode.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreEnv.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreExec.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreOTI.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CorePrague.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreReqAlgo.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreSEPControl.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreStats.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreStorage.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreStorageProtection.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreTRMAccCache.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreTRMMultiState.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreTimer.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreUserIntent.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CoreUtil.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/CredUtil.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/Credentials.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2fE8jC/Sources/AppleCredentialManager/common/LibSerialization.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.UTBWzh/Sources/AppleCredentialManager_KernelLibs/ACMKernelLib/ACMKernelLib.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.UTBWzh/Sources/AppleCredentialManager_KernelLibs/ACMKernelLib/ACMKernelTransport.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.UTBWzh/Sources/AppleCredentialManager_KernelLibs/common/LibCall.c"
- "21:29:10"
- "Jul 14 2026"
- "Jul 14 2026, 21:29:22"
- "inData && inSize >= sizeof(uid_t)"
- "size > originalSize"
- "state->cache.body.numRecords <= kACMTRMLegacyAccessoryCache_CacheSize"
```
