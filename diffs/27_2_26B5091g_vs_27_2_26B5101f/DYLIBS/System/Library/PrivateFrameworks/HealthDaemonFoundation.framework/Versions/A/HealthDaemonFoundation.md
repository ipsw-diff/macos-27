## HealthDaemonFoundation

> `/System/Library/PrivateFrameworks/HealthDaemonFoundation.framework/Versions/A/HealthDaemonFoundation`

```diff

-7027.1.45.0.0
-  __TEXT.__text: 0x7770c
-  __TEXT.__objc_methlist: 0x3e0c
+7027.1.54.0.0
+  __TEXT.__text: 0x786c4
+  __TEXT.__objc_methlist: 0x3e34
   __TEXT.__const: 0x2372
-  __TEXT.__cstring: 0x4afb
-  __TEXT.__oslogstring: 0x36d5
-  __TEXT.__gcc_except_tab: 0x3084
+  __TEXT.__cstring: 0x4b1b
+  __TEXT.__oslogstring: 0x3745
+  __TEXT.__gcc_except_tab: 0x30f8
   __TEXT.__swift5_typeref: 0xd2c
   __TEXT.__swift5_reflstr: 0x90b
   __TEXT.__swift5_assocty: 0xa8
-  __TEXT.__constg_swiftt: 0xce4
+  __TEXT.__constg_swiftt: 0xcec
   __TEXT.__swift5_builtin: 0xa0
   __TEXT.__swift5_fieldmd: 0xa04
   __TEXT.__swift5_proto: 0x100

   __TEXT.__swift5_protos: 0x38
   __TEXT.__swift5_mpenum: 0x24
   __TEXT.__swift5_types2: 0xc
-  __TEXT.__unwind_info: 0x3190
+  __TEXT.__unwind_info: 0x31c8
   __TEXT.__eh_frame: 0x1510
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2190
+  __DATA_CONST.__objc_selrefs: 0x21a8
   __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x1e0
   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__got: 0x6b0
-  __AUTH_CONST.__const: 0x38c8
-  __AUTH_CONST.__cfstring: 0x40a0
-  __AUTH_CONST.__objc_const: 0x8950
+  __AUTH_CONST.__const: 0x38f8
+  __AUTH_CONST.__cfstring: 0x40e0
+  __AUTH_CONST.__objc_const: 0x8968
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_doubleobj: 0x10

   __AUTH.__data: 0x2d0
   __DATA.__objc_ivar: 0x568
   __DATA.__data: 0xbf0
-  __DATA.__bss: 0x1d10
+  __DATA.__bss: 0x1d30
   __DATA_DIRTY.__objc_data: 0x16d8
   __DATA_DIRTY.__data: 0xae8
   __DATA_DIRTY.__bss: 0xe0

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3169
-  Symbols:   4722
-  CStrings:  906
+  Functions: 3183
+  Symbols:   4733
+  CStrings:  910
 
Symbols:
+ +[HDSQLiteSchemaEntity hasStaticJoinClauses]
+ -[HDSQLiteQueryDescriptor _uncachedJoinClauseForProperties:predicateJoinClauses:]
+ -[HDXPCProcess isFirstParty]
+ -[HDXPCProcess unitTest_copyProcessWithBundleIdentifier:]
+ GCC_except_table112
+ GCC_except_table124
+ GCC_except_table130
+ GCC_except_table44
+ GCC_except_table78
+ GCC_except_table79
+ GCC_except_table96
+ GCC_except_table98
+ __ZZL25_HDSQLiteCachedJoinClauseP10objc_classP7NSArrayIP8NSStringEU13block_pointerFS3_vEE15joinClauseCache
+ __ZZL25_HDSQLiteCachedJoinClauseP10objc_classP7NSArrayIP8NSStringEU13block_pointerFS3_vEE19joinClauseCacheLock
+ __ZZL25_HDSQLiteCachedJoinClauseP10objc_classP7NSArrayIP8NSStringEU13block_pointerFS3_vEE25reportedSaturatedEntities
+ ___52-[HDSQLiteQueryDescriptor _joinClauseForProperties:]_block_invoke
+ ___block_descriptor_56_ea8_32s40s48s_e15_"NSString"8?0l
+ _objc_msgSend$hasStaticJoinClauses
- GCC_except_table100
- GCC_except_table103
- GCC_except_table107
- GCC_except_table126
- GCC_except_table128
- GCC_except_table20
- GCC_except_table83
CStrings:
+ "@\"NSString\"8@?0"
+ "Join clause memo reached its ceiling of %lu shapes for %{public}@; fragments for this entity are now rebuilt per query"
+ "[%s] Unable to open or prepare database due to error: %@"
+ "com.apple."
+ "com.appleinternal."
- "[%s] Unable to prepare database due to error: %@"
```
