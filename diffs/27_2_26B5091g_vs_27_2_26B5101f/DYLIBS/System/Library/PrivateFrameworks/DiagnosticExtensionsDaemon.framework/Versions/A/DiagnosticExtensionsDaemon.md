## DiagnosticExtensionsDaemon

> `/System/Library/PrivateFrameworks/DiagnosticExtensionsDaemon.framework/Versions/A/DiagnosticExtensionsDaemon`

```diff

-224.0.0.0.0
-  __TEXT.__text: 0x7b950
-  __TEXT.__objc_methlist: 0x7004
+225.0.0.0.0
+  __TEXT.__text: 0x7b3ac
+  __TEXT.__objc_methlist: 0x6ff4
   __TEXT.__const: 0x372
-  __TEXT.__cstring: 0x5530
+  __TEXT.__cstring: 0x54b0
   __TEXT.__gcc_except_tab: 0x1ad0
-  __TEXT.__oslogstring: 0x9738
+  __TEXT.__oslogstring: 0x95f8
   __TEXT.__ustring: 0xc
   __TEXT.__constg_swiftt: 0x8c
   __TEXT.__swift5_typeref: 0x48

   __TEXT.__swift5_reflstr: 0x80
   __TEXT.__swift5_proto: 0x4
   __TEXT.__swift5_types: 0xc
-  __TEXT.__unwind_info: 0x26e0
+  __TEXT.__unwind_info: 0x26b8
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xad8
-  __DATA_CONST.__objc_classlist: 0x278
+  __DATA_CONST.__const: 0xae8
+  __DATA_CONST.__objc_classlist: 0x270
   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3bb0
+  __DATA_CONST.__objc_selrefs: 0x3ba0
   __DATA_CONST.__objc_protorefs: 0x28
   __DATA_CONST.__objc_superrefs: 0x1b0
   __DATA_CONST.__objc_arraydata: 0x48
-  __DATA_CONST.__got: 0x6c8
-  __AUTH_CONST.__const: 0x2270
-  __AUTH_CONST.__cfstring: 0x4e00
-  __AUTH_CONST.__objc_const: 0x13ac8
+  __DATA_CONST.__got: 0x6b8
+  __AUTH_CONST.__const: 0x2220
+  __AUTH_CONST.__cfstring: 0x4da0
+  __AUTH_CONST.__objc_const: 0x13a68
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0x360
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x548
   __AUTH.__objc_data: 0x90
   __AUTH.__data: 0x90
-  __DATA.__objc_ivar: 0x5ec
+  __DATA.__objc_ivar: 0x5f0
   __DATA.__data: 0xad0
-  __DATA.__bss: 0x1c0
-  __DATA_DIRTY.__objc_data: 0x18e0
+  __DATA.__bss: 0x1d0
+  __DATA_DIRTY.__objc_data: 0x1890
   __DATA_DIRTY.__data: 0x50
-  __DATA_DIRTY.__bss: 0x2b8
+  __DATA_DIRTY.__bss: 0x2a8
   - /System/Library/Frameworks/CloudKit.framework/Versions/A/CloudKit
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CryptoKit.framework/Versions/A/CryptoKit

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 2982
-  Symbols:   5951
-  CStrings:  1764
+  Functions: 2976
+  Symbols:   5943
+  CStrings:  1750
 
Symbols:
+ +[DEDSeedingFinisher(SecurityResearchDevice) isERMCommPageCheckCompiledIn]
+ -[DEDConfiguration protectedDefaults]
+ -[DEDPersistence discardLegacyStoreKeys]
+ -[DEDPersistence protectedDefaults]
+ -[DEDPersistence setProtectedDefaults:]
+ GCC_except_table158
+ OBJC_IVAR_$_DEDPersistence._protectedDefaults
+ _DEDDeferredExtensionUserDefaultsKey
+ _DEDGroupContainerName
+ __37-[DEDConfiguration protectedDefaults]_block_invoke
+ __OBJC_$_CLASS_METHODS_DEDSeedingFinisher(SecurityResearchDevice)
+ ___37-[DEDConfiguration protectedDefaults]_block_invoke
+ _objc_msgSend$discardLegacyStoreKeys
+ _objc_msgSend$persistentDomainForName:
+ _objc_msgSend$protectedDefaults
+ protectedDefaults.onceToken
+ protectedDefaults.protectedDefaults
- +[DEDDirectoriesCleanup didRun]
- +[DEDDirectoriesCleanup isDryRun]
- +[DEDDirectoriesCleanup run]
- +[DEDDirectoriesCleanup shouldRun]
- -[DEDController upgradeToClassCDataProtectionIfNeeded]
- GCC_except_table162
- _NSURLFileProtectionCompleteUntilFirstUserAuthentication
- _OBJC_CLASS_$_DEDDirectoriesCleanup
- _OBJC_METACLASS_$_DEDDirectoriesCleanup
- __28+[DEDDirectoriesCleanup run]_block_invoke
- __54-[DEDController upgradeToClassCDataProtectionIfNeeded]_block_invoke
- __OBJC_$_CLASS_METHODS_DEDDirectoriesCleanup
- __OBJC_$_CLASS_METHODS_DEDSeedingFinisher
- __OBJC_CLASS_RO_$_DEDDirectoriesCleanup
- __OBJC_METACLASS_RO_$_DEDDirectoriesCleanup
- ___28+[DEDDirectoriesCleanup run]_block_invoke
- ___54-[DEDController upgradeToClassCDataProtectionIfNeeded]_block_invoke
- ___block_descriptor_48_e8_32s_e5_v8?0l
- _objc_msgSend$didRun
- _objc_msgSend$findAllItems:includeDirs:
- _objc_msgSend$isDryRun
- _objc_msgSend$lsDir:sorted:
- _objc_msgSend$setBool:forKey:
- _objc_msgSend$shouldRun
- _objc_msgSend$upgradeToClassCDataProtectionIfNeeded
CStrings:
+ "bugsession:"
+ "discarded [%lu] legacy keys"
+ "failed to archive bug session [%{public}@], not updating the store: [%{public}@]"
+ "group.com.apple.diagnosticextensionsd"
+ "no group container for [%{public}@]; protected defaults will not be protected"
+ "overrideDevice"
- "%@.c-data-class-upgrade"
- "Cleaning up group containers"
- "Could not find feedback group container."
- "DEDUpgradedToClassC"
- "Error setting file protection key: %@"
- "Failed to cleanup directory with error [%{public}@]"
- "Finished: Cleaning up group containers"
- "Group directories cleanup is already done."
- "Removed [%{public}@]"
- "Removing [%{public}@]"
- "Upgrading: [%{public}@]"
- "com.apple.diagnosticextensions"
- "com.apple.diagnosticextensionsd-group-containers-cleanup"
- "dir-cleanup"
- "directoriesCleanupDone"
- "directoriesCleanupDryRun"
- "failed to archive bug session with error: [%{public}@]"
- "upgradeToClassCDataProtectionIfNeeded already done"
- "upgradeToClassCDataProtectionIfNeeded end"
- "upgradeToClassCDataProtectionIfNeeded start"
```
