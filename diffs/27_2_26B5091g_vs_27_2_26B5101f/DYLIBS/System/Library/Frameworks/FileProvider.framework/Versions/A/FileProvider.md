## FileProvider

> `/System/Library/Frameworks/FileProvider.framework/Versions/A/FileProvider`

```diff

-4838.40.92.501.2
-  __TEXT.__text: 0x13b360
-  __TEXT.__objc_methlist: 0xe974
+4838.40.130.0.2
+  __TEXT.__text: 0x13b700
+  __TEXT.__objc_methlist: 0xe9c4
   __TEXT.__const: 0x8aa
-  __TEXT.__cstring: 0x150af
+  __TEXT.__cstring: 0x1514c
   __TEXT.__gcc_except_tab: 0x8998
   __TEXT.__oslogstring: 0xe0ea
   __TEXT.__dlopen_cstrs: 0x6ba
-  __TEXT.__ustring: 0x21e
+  __TEXT.__ustring: 0x25a
   __TEXT.__swift5_typeref: 0xb4
   __TEXT.__constg_swiftt: 0x60
   __TEXT.__swift5_reflstr: 0x45

   __TEXT.__swift_as_entry: 0x4
   __TEXT.__swift_as_ret: 0x4
   __TEXT.__swift_as_cont: 0xc
-  __TEXT.__unwind_info: 0x6ec0
+  __TEXT.__unwind_info: 0x6ed8
   __TEXT.__eh_frame: 0xa0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1688
+  __DATA_CONST.__const: 0x1698
   __DATA_CONST.__objc_classlist: 0x690
   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x2a8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7068
+  __DATA_CONST.__objc_selrefs: 0x7090
   __DATA_CONST.__objc_protorefs: 0x158
   __DATA_CONST.__objc_superrefs: 0x548
   __DATA_CONST.__objc_arraydata: 0xab0
-  __DATA_CONST.__got: 0xb50
-  __AUTH_CONST.__const: 0x6fb8
-  __AUTH_CONST.__cfstring: 0x119c0
-  __AUTH_CONST.__objc_const: 0x24ff8
+  __DATA_CONST.__got: 0xb58
+  __AUTH_CONST.__const: 0x7008
+  __AUTH_CONST.__cfstring: 0x11a40
+  __AUTH_CONST.__objc_const: 0x250c0
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_arrayobj: 0x198
   __AUTH_CONST.__auth_got: 0xf18
   __AUTH.__objc_data: 0x1a40
   __AUTH.__data: 0x10
-  __DATA.__objc_ivar: 0x10c4
+  __DATA.__objc_ivar: 0x10c8
   __DATA.__data: 0x23f0
-  __DATA.__bss: 0xbd0
+  __DATA.__bss: 0xbe0
   __DATA.__common: 0x2b
   __DATA_DIRTY.__objc_data: 0x2760
   __DATA_DIRTY.__data: 0x1

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
-  Functions: 7539
-  Symbols:   14284
-  CStrings:  4088
+  Functions: 7549
+  Symbols:   14303
+  CStrings:  4094
 
Symbols:
+ +[FPProviderDomain migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]
+ -[FPAccessControlManager transferAccessToAllItemsFromBundle:toBundle:completionHandler:]
+ -[FPAccessControlManager withServicerProxy:]
+ -[NSFileProviderDomain migrationState]
+ -[NSFileProviderDomain setMigrationState:]
+ OBJC_IVAR_$_NSFileProviderDomain._migrationState
+ _GSSTORAGE_FP_PROVIDER_CONTENT_VERSION_XATTR_NAME
+ ___44-[FPAccessControlManager withServicerProxy:]_block_invoke
+ ___88-[FPAccessControlManager transferAccessToAllItemsFromBundle:toBundle:completionHandler:]_block_invoke
+ ___99+[FPProviderDomain migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:]_block_invoke
+ ___block_descriptor_40_e8_32bs_e37_v16?0"<FPDAccessControlServicing>"8l
+ ___block_descriptor_56_e8_32s40s48bs_e37_v16?0"<FPDAccessControlServicing>"8l
+ ___fpfs_supports_appDomainMigration_block_invoke
+ _fpfs_supports_appDomainMigration
+ _kFileProviderSupersededAppReplacementEntitlement
+ _objc_msgSend$migrateAllDomainsFromProviderIdentifier:toProviderIdentifier:completionHandler:
+ _objc_msgSend$migrationState
+ _objc_msgSend$transferAccessToAllItemsFromBundle:toBundle:completionHandler:
+ _objc_msgSend$withServicerProxy:
+ fpfs_supports_appDomainMigration
+ fpfs_supports_appDomainMigration.feature_enabled
+ fpfs_supports_appDomainMigration.once_token
- ___76-[FPAccessControlManager revokeAccessToAllItemsForBundle:completionHandler:]_block_invoke_3
- ___80-[FPAccessControlManager bundleIdentifiersWithAccessToAnyItemCompletionHandler:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48bs_e49_v24?0"<FPDAccessControlServicing>"8"NSError"16l
CStrings:
+ "(⏹  superseded app migration)"
+ ",migrating"
+ "4838.40.130.0.2"
+ "DISCONNECTION_REASON_SUPERSEDED_APP_MIGRATION"
+ "access control servicer"
+ "appDomainMigration"
+ "com.apple.private.fileprovider.superseded-app-replacement"
+ "v16@?0@\"<FPDAccessControlServicing>\"8"
- "4838.40.92.501.2"
- "com.apple.genstore.fp_provider_cver#C"
```
