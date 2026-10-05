## libobjc.A.dylib

> `/usr/lib/libobjc.A.dylib`

```diff

 973.1.0.0.0
-  __TEXT.__text: 0x39050
+  __TEXT.__text: 0x39040
   __TEXT.__lazy_helpers: 0xa8
   __TEXT.__objc_methlist: 0x5ec
   __TEXT.__const: 0x4130

   __DATA.__bss: 0x71d
   __DATA.__common: 0x18
   __DATA_DIRTY.__objc_data: 0x140
-  __DATA_DIRTY.__data: 0x8dc
+  __DATA_DIRTY.__data: 0x8d4
   __DATA_DIRTY.__crash_info: 0x148
   __DATA_DIRTY.__bss: 0x5a50
   __DATA_DIRTY.__common: 0x28

   - /usr/lib/libobjc-env.dylib
   - /usr/lib/objc/libobjcMsgSend.dylib
   Functions: 911
-  Symbols:   1504
+  Symbols:   1503
   CStrings:  490
 
Symbols:
- __ZZ16get_xprr_versionvE19cached_xprr_version
Functions:
~ __objc_init : 2848 -> 2836
~ _map_images_nolock : 9056 -> 9088
~ _NXNextHashState : 136 -> 128
~ __ZL11getProtocolPKc : 140 -> 148
~ __thisThreadIsInitializingClass : 156 -> 152
~ +[NSObject initialize] : 8 -> 12
~ __objc_rootRetain : 128 -> 124
~ __objc_rootDealloc : 76 -> 80
~ __ZN11objc_object27sidetable_clearDeallocatingEv : 252 -> 264
~ +[NSObject class] : 16 -> 4
~ _objc_autoreleasePoolPush : 296 -> 292
~ __ZN19AutoreleasePoolPage17autoreleaseNoPageEP11objc_object : 324 -> 328
~ _objc_alloc : 52 -> 48
~ +[NSObject self] : 4 -> 8
~ __ZL14_mapStrIsEqualP11_NXMapTablePKvS2_ : 108 -> 120
~ +[NSObject new] : 72 -> 76
~ __objc_rootAllocWithZone : 268 -> 280
~ -[NSObject init] : 16 -> 4
~ _object_getIndexedIvars : 188 -> 184
~ __ZN11objc_object16rootAutorelease2Ev : 144 -> 132
~ _objc_allocWithZone : 56 -> 52
~ +[NSObject allocWithZone:] : 16 -> 4
~ _objc_storeWeak : 540 -> 536
~ __objc_rootAutorelease : 300 -> 304
~ _objc_autoreleaseReturnValue : 312 -> 308
~ -[NSObject mutableCopy] : 20 -> 24
~ __ZL20resolveMethod_lockedP11objc_objectP13objc_selectorP10objc_classi : 824 -> 820
~ +[NSObject resolveInstanceMethod:] : 12 -> 16
~ _class_initialize : 112 -> 108
~ +[NSObject superclass] : 40 -> 44
~ _class_getInstanceMethod : 292 -> 288
~ +[NSObject resolveClassMethod:] : 20 -> 8
~ _class_getVersion : 140 -> 136
~ -[NSObject copy] : 28 -> 16
~ _class_respondsToSelector : 24 -> 20
~ +[NSObject respondsToSelector:] : 20 -> 24
~ -[NSObject retainWeakReference] : 12 -> 24
~ +[NSObject zone] : 8 -> 12
~ _protocol_getName : 32 -> 24
~ __ZN10protocol_t13demangledNameEv : 124 -> 132
~ __ZL32getExtendedTypesIndexesForMethodP10protocol_tPK8method_tbbRjS4_ : 160 -> 172
~ +[NSObject hash] : 4 -> 8
~ _objc_getAssociatedObject : 356 -> 368
~ +[NSObject isSubclassOfClass:] : 88 -> 76
~ -[NSObject forwardingTargetForSelector:] : 20 -> 16
~ +[NSObject isProxy] : 20 -> 8
~ _method_getDescription : 72 -> 68
~ __ZL27_allocateTrampolinesAndDatav : 516 -> 520
~ _objc_setProperty_nonatomic : 120 -> 116
~ +[NSObject copyWithZone:] : 8 -> 12
~ _objc_constructInstance : 208 -> 204
~ +[NSObject isKindOfClass:] : 80 -> 84
~ __ZN11objc_object22clearDeallocating_slowEv : 256 -> 252
~ +[NSObject methodForSelector:] : 76 -> 80
~ _class_copyMethodList : 3932 -> 3928
~ __ZN19AutoreleasePoolPage19autoreleaseFullPageEP11objc_objectPS_ : 200 -> 204
~ __ZL17_class_lookUpIvarP10objc_classP6ivar_tRlR29objc_ivar_memory_management_t : 740 -> 736
~ _imp_removeBlock : 336 -> 340
~ __ZL26_objc_exception_destructorPv : 108 -> 104
~ +[NSObject release] : 8 -> 12
~ __ZL27protocol_getProperty_nolockP10protocol_tPKcbb : 300 -> 312
~ +[NSObject instancesRespondToSelector:] : 24 -> 28
~ __objc_rootReleaseWasZero : 168 -> 164
~ +[NSObject isMemberOfClass:] : 20 -> 24
~ _object_getIvar : 120 -> 116
~ +[NSObject autorelease] : 16 -> 4
~ __ZL16scanMangledFieldRPKcS0_S1_Ri : 156 -> 152
~ __objc_atfork_parent : 740 -> 744
~ _objc_opt_isKindOfClass : 204 -> 216
~ +[NSObject retainWeakReference] : 8 -> 12
~ __category_getLoadMethod : 1556 -> 1552
~ _weak_unregister_no_lock : 488 -> 492
~ _class_getIvarLayout : 64 -> 60
~ +[NSObject isAncestorOfObject:] : 120 -> 124
~ ___copy_helper_block_e8_32c67_ZTSKZL25_method_setImplementationP10objc_classP8method_tPFvvEE3$_0 : 12 -> 20
~ __ZL13fixupProtocolP10protocol_tjbU13block_pointerFvjE : 1264 -> 1272
~ _objc_addLoadImageFunc2 : 380 -> 376
~ __ZL24hasSignedClassROPointersPK14mach_header_64P29_dyld_section_location_info_s : 100 -> 88
~ __ZN17loadImageCallbackaSERKS_ : 144 -> 140
~ _weak_entry_for_referent : 164 -> 168
~ __ZL13weakTableScanv : 364 -> 360
~ _objc_autoreleaseNoPool : 4 -> 8
~ _objc_autoreleasePoolInvalid : 16 -> 12
~ __ZNK11objc_object14sidetable_lockEv : 72 -> 60
~ __ZN4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrIK11objc_objectEmN12_GLOBAL__N_125RefcountMapValuePurgeableENS_12DenseMapInfoIS5_EENS_6detail12DenseMapPairIS5_mEEEES5_mS7_S9_SC_EixEOS5_ : 100 -> 96
~ __ZNK11objc_object27sidetable_getExtraRC_nolockEv : 116 -> 120
~ __ZN4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrIK11objc_objectEmN12_GLOBAL__N_125RefcountMapValuePurgeableENS_12DenseMapInfoIS5_EENS_6detail12DenseMapPairIS5_mEEEES5_mS7_S9_SC_E11try_emplaceIJmEEENSt3__14pairINS_16DenseMapIteratorIS5_mS7_S9_SC_Lb0EEEbEEOS5_DpOT_ : 164 -> 160
~ __ZNK11objc_object24sidetable_isDeallocatingEv : 116 -> 120
~ -[__NSUnrecognizedTaggedPointer autorelease] : 12 -> 8
~ +[NSObject forwardInvocation:] : 72 -> 76
~ -[NSObject forwardInvocation:] : 80 -> 76
~ +[NSObject description] : 8 -> 12
~ -[NSObject description] : 12 -> 8
~ __ZN19AutoreleasePoolPageC2EPS_ : 280 -> 284
~ __ZL23callSetWeaklyReferencedP11objc_object : 256 -> 252
~ __ZN4objc12DenseMapBaseINS_8DenseMapI12DisguisedPtrIK11objc_objectEmN12_GLOBAL__N_125RefcountMapValuePurgeableENS_12DenseMapInfoIS5_EENS_6detail12DenseMapPairIS5_mEEEES5_mS7_S9_SC_E15LookupBucketForIS5_EEbRKT_RPSC_ : 252 -> 256
~ __ZNK4objc12DenseMapBaseINS_13SmallDenseMapIPKvNS_15ObjcAssociationELj1ENS_17DenseMapValueInfoIS4_EENS_12DenseMapInfoIS3_EENS_6detail12DenseMapPairIS3_S4_EEEES3_S4_S6_S8_SB_E22FatalCorruptHashTablesEPKSB_j : 96 -> 92
~ __ZL22defaultBadAllocHandlerP10objc_class : 48 -> 36
~ __ZL18startWeakTableScanv : 120 -> 132
~ +[NSObject doesNotRecognizeSelector:] : 80 -> 68
~ -[NSObject doesNotRecognizeSelector:] : 68 -> 80
~ +[NSObject methodSignatureForSelector:] : 24 -> 28
~ -[NSObject methodSignatureForSelector:] : 28 -> 24
~ __ZNK19AutoreleasePoolPage10busted_dieEv : 40 -> 44
```
