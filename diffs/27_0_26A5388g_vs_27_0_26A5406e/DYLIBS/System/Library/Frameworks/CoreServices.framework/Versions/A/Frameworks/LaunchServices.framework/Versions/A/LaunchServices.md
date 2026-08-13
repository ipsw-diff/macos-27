## LaunchServices

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/LaunchServices.framework/Versions/A/LaunchServices`

### Sections with Same Size but Changed Content

- `__TEXT.__dof_LSFSNode`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__lazy_load_got`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`
- `__DATA_DIRTY.__data`

```diff

-1510.400.0.0.0
-  __TEXT.__text: 0x252f9c
+1517.401.0.0.0
+  __TEXT.__text: 0x253f04
   __TEXT.__lazy_helpers: 0xa8
-  __TEXT.__objc_methlist: 0xedbc
+  __TEXT.__objc_methlist: 0xede4
   __TEXT.__const: 0xab0
-  __TEXT.__cstring: 0x33486
-  __TEXT.__oslogstring: 0x222b0
-  __TEXT.__gcc_except_tab: 0x3444c
+  __TEXT.__cstring: 0x33623
+  __TEXT.__oslogstring: 0x22495
+  __TEXT.__gcc_except_tab: 0x345c4
   __TEXT.__ustring: 0x1be
   __TEXT.__dof_LSFSNode: 0x2b6
-  __TEXT.__unwind_info: 0xeaf0
+  __TEXT.__unwind_info: 0xeb60
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x3e98
+  __DATA_CONST.__const: 0x3ed8
   __DATA_CONST.__objc_classlist: 0x7a8
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x190
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6e60
+  __DATA_CONST.__objc_selrefs: 0x6e70
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x638
   __DATA_CONST.__objc_arraydata: 0xa10
   __DATA_CONST.__got: 0xe40
-  __AUTH_CONST.__const: 0xaaa8
-  __AUTH_CONST.__cfstring: 0x1df00
-  __AUTH_CONST.__objc_const: 0x16668
+  __AUTH_CONST.__const: 0xab58
+  __AUTH_CONST.__cfstring: 0x1df20
+  __AUTH_CONST.__objc_const: 0x16680
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x750

   __AUTH.__data: 0x248
   __DATA.__objc_ivar: 0xc68
   __DATA.__data: 0x15ec
-  __DATA.__bss: 0x1a70
+  __DATA.__bss: 0x1a80
   __DATA.__common: 0x5
   __DATA_DIRTY.__objc_data: 0x1130
   __DATA_DIRTY.__data: 0x250

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 11147
-  Symbols:   19519
-  CStrings:  7906
+  Functions: 11169
+  Symbols:   19543
+  CStrings:  7930
 
Symbols:
+ -[FSMimic bundleInfoDictionaryWithError:]
+ -[FSMimicPopulator populateBundleInfoDictionaryWithError:]
+ -[LSApplicationRecord(MobileInstall) originalInstallDate]
+ GCC_except_table301
+ GCC_except_table318
+ GCC_except_table323
+ GCC_except_table326
+ GCC_except_table335
+ GCC_except_table338
+ GCC_except_table352
+ _ZL25_LSBundleApplyCheckUpdate24LSBundleCheckUpdateStylePKcU13block_pointerFvP9LSContextE
+ __LSBundleCopyNodeWithCheckStyle
+ __Z21CFTypeGetAsDictionaryPKv
+ __ZL19_LSBundleCreateNodeP11_LSDatabasej24LSBundleCheckUpdateStylePbPU15__autoreleasingP7NSError
+ __ZL24_LSBundleCopyOrCheckNodeP11_LSDatabasejj24LSBundleCheckUpdateStylePU8__strongP6FSNode
+ __ZL25_LSBundleApplyCheckUpdate24LSBundleCheckUpdateStylePKcU13block_pointerFvP9LSContextE
+ __ZZL31_LSBundleCheckUpdateClientQueuevE5queue
+ __ZZL31_LSBundleCheckUpdateClientQueuevE9onceToken
+ ___ZL24_LSBundleCopyOrCheckNodeP11_LSDatabasejj24LSBundleCheckUpdateStylePU8__strongP6FSNode_block_invoke
+ ___ZL25_LSBundleApplyCheckUpdate24LSBundleCheckUpdateStylePKcU13block_pointerFvP9LSContextE_block_invoke
+ ____ZL19_LSBundleCreateNodeP11_LSDatabasej24LSBundleCheckUpdateStylePbPU15__autoreleasingP7NSError_block_invoke
+ ____ZL24_LSBundleCopyOrCheckNodeP11_LSDatabasejj24LSBundleCheckUpdateStylePU8__strongP6FSNode_block_invoke
+ ____ZL25_LSBundleApplyCheckUpdate24LSBundleCheckUpdateStylePKcU13block_pointerFvP9LSContextE_block_invoke
+ ____ZL31_LSBundleCheckUpdateClientQueuev_block_invoke
+ ____ZN14LaunchServices10ContainersL7displayEP9LSContextjjP29CSStoreAttributedStringWriter_block_invoke
+ ___block_descriptor_36_e21_v16?0^{LSContext=}8l
+ ___block_descriptor_40_ea8_32s_e21_v16?0^{LSContext=}8l
+ ___block_descriptor_48_ea8_32bs_e9_v16?0r*8l
+ ___block_descriptor_64_ea8_32r40r_e14_v24?0I8I12*16l
+ __kLSApplicationDisclaimAsParentApplicationKey
+ __kLSApplicationHasReExecedItselfKey
+ __kLSApplicationPossibleForegroundOwnerApplicationsASNsArrayKey
+ __kLSURLIsHiddenBySystemChangedNotificationsKey
+ __kLSURLIsHiddenBySystemKey
+ _objc_msgSend$populateBundleInfoDictionaryWithError:
- GCC_except_table300
- GCC_except_table317
- GCC_except_table320
- GCC_except_table324
- GCC_except_table332
- GCC_except_table336
- _ZL24_LSBundleCopyOrCheckNodeP11_LSDatabasejjhPU8__strongP6FSNode
- __ZL19_LSBundleCreateNodeP11_LSDatabasejbPbPU15__autoreleasingP7NSError
- __ZL24_LSBundleCopyOrCheckNodeP11_LSDatabasejjhPU8__strongP6FSNode
- ____ZL24_LSBundleCopyOrCheckNodeP11_LSDatabasejjhPU8__strongP6FSNode_block_invoke
- __kLSApplicationHasAVisibleOwnerApplicationASNsArrayKey
CStrings:
+ "%{public}s: finished %{public}s database update (%{public}s)"
+ "%{public}s: performing synchronous (client) database update (%{public}s)"
+ "%{public}s: performing synchronous (server) database update (%{public}s)"
+ "%{public}s: scheduling asynchronous (client) database update (%{public}s)"
+ "%{public}s: scheduling asynchronous (server) database update (%{public}s)"
+ "-[FSMimic bundleInfoDictionaryWithError:]"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/FSMimic.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/FSUtils.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSAESupport.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSDMFSupport.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSDispatchUtils.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSDisplayNameConstructor.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSUtils.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSValidationToken.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSAlias.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSBundle.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSBundleBase.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSBundleBase.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSContainer.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSDatabase.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSPluginBundle.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSServerDBExecutionContext.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/DefaultApps/LSDefaultAppsCore.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSAppPlaceholders.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSBindingEvaluator.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSBundleRecordBuilder.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSBundleRecordUpdater.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSCapability.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSClaimedTypes.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSCore.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSCryptexUtils.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSDataContainerPersonality.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSEligibility.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSExternal.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSExternalPriv.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSInternetLocator.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSOpenWithMenu.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSRegistrants.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSRegistration.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSStrongBinding.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSURLPropertyProvider.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/_LSPersonaDatabase.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSLaunchRunningBoard.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSOpenCall.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSOpenCore.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSOpenGenericReadMe.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSOpenNewWorld.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSTranslocation.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/Enumerator/LSApplicationRecordEnumerator.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/Enumerator/LSEnumerator.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/Enumerator/LSServiceEnumerator.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSApplicationExtensionRecord.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSApplicationRecord.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSBundleRecord.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSClaimBindingConfiguration.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSClaimRecord.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSDatabaseContext.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSExtensionPointRecord.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSRecord.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSServiceRecord.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSiTunesMetadata.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/UTTypeRecord.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/RunIdentity/LSApplicationIdentity.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Security/CodeEvaluation/LSCodeEvaluationClientManager.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Security/LSDTrustedSignatureService.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Security/LSTrustedSignature.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Security/LSTrustedSignatureDatabase.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDDeviceEncryptionService.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDDisseminationClient.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDModifyService.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDOpenService.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDReadService.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDService.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDXPCClient.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSServerInterface.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/SettingsStore/LSSettingsStore.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Type/UTTypeEvaluator.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Visualization/LSDatabaseVisualization.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSAppLink.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSAppLinkPlugIn.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSApplicationIsInstalledQuery.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSApplicationRestrictionsManager.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSApplicationState.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSApplicationWorkspace.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSBundleProxy.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSBundleQuery.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSBundleWrapper.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSContainerHelpers.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSDefaultApplicationQuery.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSDiskUsage.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSDocumentProxy.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSEligibilityPredicateEvaluator.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSExtensionLaunchConfiguration.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSExtensionLaunchConfigurationResolver.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSFeatureFlagPredicateEvaluator+LSData.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSFeatureFlagPredicateEvaluator.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPersonaAssociationMutation.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPlugInQuery.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPlugInQueryAll.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPlugInQueryWithIdentifier.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPlugInQueryWithURL.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSQuery/LSQuery.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSQuery/LSQueryContext.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSStatePlist.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSTranslocationHelpers.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/NSCoder+LaunchServicesAdditions.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/TemplateApplications/LSTemplateApplicationCreation.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/TemplateApplications/LSTemplateApplicationLaunch.mm"
+ "LSApplicationDisclaimAsParentApplicationKey"
+ "LSApplicationHasReExecedItselfKey"
+ "LSApplicationPossibleForegroundOwnerApplicationsASNsArrayKey"
+ "OSStatus _LSBundleCopyOrCheckNode(__strong LSDatabaseRef, LSBundleID, CSStringID, LSBundleCheckUpdateStyle, FSNodeHandle)"
+ "_LSBundleApplyCheckUpdate"
+ "_LSBundleCopyOrCheckNode_block_invoke"
+ "asynchronous (client)"
+ "asynchronous (server)"
+ "bundleInfoDictionary"
+ "com.apple.LaunchServices.bundle-check-update"
+ "failed to get node for %@ but had no error"
+ "failed to prepare value for %@ but had no error"
+ "kLSNotificationApplicationReExeced"
+ "kLSNotifyApplicationRebirth"
+ "mimic selector %{public}@ returned false without setting an error"
+ "mimic selector %{public}@ returned nil without setting an error"
+ "re-registering changed bundle"
+ "registering changed bundle"
+ "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1498:63)]"
+ "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1529:65)]"
+ "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1536:65)]"
+ "static id LaunchServices::PrefsStorage::_GetValueInPrefsArrayWithPredicate(NSArray *__strong, __unsafe_unretained Class, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1529:65)]"
+ "static id LaunchServices::PrefsStorage::_GetValueInPrefsArrayWithPredicate(NSArray *__strong, __unsafe_unretained Class, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1536:65)]"
+ "synchronous (client)"
+ "synchronous (server)"
+ "unregistering bundle missing from disk"
+ "unregistering changed bundle"
+ "v16@?0r*8"
+ "void LaunchServices::UTTypeEnumerateFlavoredDisplayNames(__strong LSDatabaseRef, const _UTTypeData *, const F &) [F = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.GrnLuk/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/UTTypeCore.mm:159:55)]"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/FSMimic.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/FSUtils.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSAESupport.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSDMFSupport.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSDispatchUtils.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSDisplayNameConstructor.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSUtils.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Base/LSValidationToken.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSAlias.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSBundle.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSBundleBase.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSBundleBase.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSContainer.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSDatabase.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSPluginBundle.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/LSServerDBExecutionContext.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/DefaultApps/LSDefaultAppsCore.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSAppPlaceholders.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSBindingEvaluator.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSBundleRecordBuilder.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSBundleRecordUpdater.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSCapability.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSClaimedTypes.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSCore.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSCryptexUtils.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSDataContainerPersonality.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSEligibility.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSExternal.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSExternalPriv.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSInternetLocator.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSOpenWithMenu.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSRegistrants.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSRegistration.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSStrongBinding.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSURLPropertyProvider.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/_LSPersonaDatabase.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSLaunchRunningBoard.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSOpenCall.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSOpenCore.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSOpenGenericReadMe.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSOpenNewWorld.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Open/LSTranslocation.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/Enumerator/LSApplicationRecordEnumerator.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/Enumerator/LSEnumerator.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/Enumerator/LSServiceEnumerator.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSApplicationExtensionRecord.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSApplicationRecord.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSBundleRecord.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSClaimBindingConfiguration.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSClaimRecord.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSDatabaseContext.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSExtensionPointRecord.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSRecord.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSServiceRecord.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/LSiTunesMetadata.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Record/UTTypeRecord.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/RunIdentity/LSApplicationIdentity.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Security/CodeEvaluation/LSCodeEvaluationClientManager.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Security/LSDTrustedSignatureService.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Security/LSTrustedSignature.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Security/LSTrustedSignatureDatabase.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDDeviceEncryptionService.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDDisseminationClient.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDModifyService.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDOpenService.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDReadService.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDService.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSDXPCClient.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Server/LSServerInterface.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/SettingsStore/LSSettingsStore.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Type/UTTypeEvaluator.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Visualization/LSDatabaseVisualization.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSAppLink.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSAppLinkPlugIn.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSApplicationIsInstalledQuery.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSApplicationRestrictionsManager.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSApplicationState.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSApplicationWorkspace.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSBundleProxy.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSBundleQuery.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSBundleWrapper.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSContainerHelpers.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSDefaultApplicationQuery.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSDiskUsage.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSDocumentProxy.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSEligibilityPredicateEvaluator.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSExtensionLaunchConfiguration.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSExtensionLaunchConfigurationResolver.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSFeatureFlagPredicateEvaluator+LSData.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSFeatureFlagPredicateEvaluator.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPersonaAssociationMutation.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPlugInQuery.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPlugInQueryAll.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPlugInQueryWithIdentifier.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSPlugInQueryWithURL.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSQuery/LSQuery.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSQuery/LSQueryContext.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSStatePlist.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/LSTranslocationHelpers.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Workspace/NSCoder+LaunchServicesAdditions.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/TemplateApplications/LSTemplateApplicationCreation.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/TemplateApplications/LSTemplateApplicationLaunch.mm"
- "LAUNCH: Disclaiming parent relationship for launch of %{public}@ by application %{public}s"
- "LSApplicationHasAVisibleOwnerApplicationASNsArrayKey"
- "OSStatus _LSBundleCopyOrCheckNode(__strong LSDatabaseRef, LSBundleID, CSStringID, Boolean, FSNodeHandle)"
- "node had unregistered bundle type but can't issue IO to localize its name"
- "node had unregistered personality but cannot do IO to localize its name"
- "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1498:63)]"
- "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1529:65)]"
- "static NSInteger LaunchServices::PrefsStorage::_GetIndexOfValueInPrefsArrayWithPredicate(NSArray *__strong, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1536:65)]"
- "static id LaunchServices::PrefsStorage::_GetValueInPrefsArrayWithPredicate(NSArray *__strong, __unsafe_unretained Class, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1529:65)]"
- "static id LaunchServices::PrefsStorage::_GetValueInPrefsArrayWithPredicate(NSArray *__strong, __unsafe_unretained Class, const Pred &) [Pred = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Info/LSPrefs.mm:1536:65)]"
- "void LaunchServices::UTTypeEnumerateFlavoredDisplayNames(__strong LSDatabaseRef, const _UTTypeData *, const F &) [F = (lambda at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.irL9K9/Sources/CoreServicesSubFrameworks/LaunchServices.subprj/Source/LaunchServices/Database/UTTypeCore.mm:159:55)]"
```
