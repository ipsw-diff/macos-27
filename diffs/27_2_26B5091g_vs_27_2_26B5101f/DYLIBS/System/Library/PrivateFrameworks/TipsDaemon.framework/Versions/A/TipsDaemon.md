## TipsDaemon

> `/System/Library/PrivateFrameworks/TipsDaemon.framework/Versions/A/TipsDaemon`

```diff

-866.2.2.0.0
-  __TEXT.__text: 0x84b54
-  __TEXT.__objc_methlist: 0x36c0
-  __TEXT.__const: 0x2be8
+866.2.3.0.0
+  __TEXT.__text: 0x85a78
+  __TEXT.__objc_methlist: 0x3770
+  __TEXT.__const: 0x2c18
   __TEXT.__oslogstring: 0x1f76
-  __TEXT.__cstring: 0x3509
+  __TEXT.__cstring: 0x35a9
   __TEXT.__gcc_except_tab: 0x10dc
-  __TEXT.__swift5_typeref: 0xe8e
-  __TEXT.__swift5_fieldmd: 0x904
-  __TEXT.__constg_swiftt: 0xe50
+  __TEXT.__swift5_typeref: 0xe94
+  __TEXT.__swift5_fieldmd: 0x944
+  __TEXT.__constg_swiftt: 0xe8c
   __TEXT.__swift5_builtin: 0xf0
-  __TEXT.__swift5_reflstr: 0x5ee
+  __TEXT.__swift5_reflstr: 0x64e
   __TEXT.__swift5_assocty: 0x180
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_proto: 0x1a4
-  __TEXT.__swift5_types: 0x10c
-  __TEXT.__swift5_capture: 0x64c
+  __TEXT.__swift5_types: 0x110
+  __TEXT.__swift5_capture: 0x65c
   __TEXT.__swift_as_entry: 0xf0
   __TEXT.__swift_as_ret: 0x170
   __TEXT.__swift_as_cont: 0x318
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x2ef8
-  __TEXT.__eh_frame: 0x3b10
+  __TEXT.__unwind_info: 0x2f60
+  __TEXT.__eh_frame: 0x3b30
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4b8
-  __DATA_CONST.__objc_classlist: 0x510
+  __DATA_CONST.__const: 0x4c0
+  __DATA_CONST.__objc_classlist: 0x520
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2398
+  __DATA_CONST.__objc_selrefs: 0x23b8
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x1b0
+  __DATA_CONST.__objc_superrefs: 0x1b8
   __DATA_CONST.__objc_arraydata: 0x78
-  __DATA_CONST.__got: 0xb38
-  __AUTH_CONST.__const: 0x3ce9
-  __AUTH_CONST.__cfstring: 0x2700
-  __AUTH_CONST.__objc_const: 0x7db8
+  __DATA_CONST.__got: 0xb40
+  __AUTH_CONST.__const: 0x3d41
+  __AUTH_CONST.__cfstring: 0x2720
+  __AUTH_CONST.__objc_const: 0x7f68
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__auth_got: 0xd88
-  __AUTH.__objc_data: 0xeb0
-  __AUTH.__data: 0x50
-  __DATA.__objc_ivar: 0x210
-  __DATA.__data: 0x830
+  __AUTH.__objc_data: 0xfd0
+  __AUTH.__data: 0x78
+  __DATA.__objc_ivar: 0x214
+  __DATA.__data: 0x848
   __DATA.__bss: 0x1c00
   __DATA.__common: 0x8
-  __DATA_DIRTY.__objc_data: 0x3330
+  __DATA_DIRTY.__objc_data: 0x3338
   __DATA_DIRTY.__data: 0xf98
   __DATA_DIRTY.__bss: 0x16e0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3007
-  Symbols:   4291
-  CStrings:  694
+  Functions: 3035
+  Symbols:   4317
+  CStrings:  698
 
Symbols:
+ -[TPSBundleIdsCondition .cxx_destruct]
+ -[TPSBundleIdsCondition init]
+ -[TPSBundleIdsCondition requestingBundleId]
+ -[TPSBundleIdsCondition setRequestingBundleId:]
+ -[TPSBundleIdsCondition targetingValidations]
+ -[TPSDeliveryPrecondition applyRequestingBundleId:]
+ -[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]
+ -[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]
+ GCC_except_table165
+ GCC_except_table170
+ GCC_except_table179
+ GCC_except_table185
+ GCC_except_table196
+ OBJC_IVAR_$_TPSBundleIdsCondition._requestingBundleId
+ _OBJC_CLASS_$_TPSBundleIdsCondition
+ _OBJC_CLASS_$_TPSBundleIdsValidation
+ _OBJC_METACLASS_$_TPSBundleIdsCondition
+ _OBJC_METACLASS_$_TPSBundleIdsValidation
+ __252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke
+ __252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_2
+ __94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke
+ __94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke_2
+ __DATA_TPSBundleIdsValidation
+ __INSTANCE_METHODS_TPSBundleIdsValidation
+ __IVARS_TPSBundleIdsValidation
+ __METACLASS_DATA_TPSBundleIdsValidation
+ __OBJC_$_INSTANCE_METHODS_TPSBundleIdsCondition
+ __OBJC_$_INSTANCE_VARIABLES_TPSBundleIdsCondition
+ __OBJC_$_PROP_LIST_TPSBundleIdsCondition
+ __OBJC_CLASS_RO_$_TPSBundleIdsCondition
+ __OBJC_METACLASS_RO_$_TPSBundleIdsCondition
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke
+ ___252-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:]_block_invoke_2
+ ___45-[TPSBundleIdsCondition targetingValidations]_block_invoke
+ ___94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke
+ ___94-[TPSTipsManager processClientConditions:requestingBundleId:targetingCache:completionHandler:]_block_invoke_2
+ ___block_descriptor_112_e8_32s40s48s56s64r72r80r88r96r104w_e24_v16?0?<v?"NSError">8l
+ ___block_descriptor_48_e8_32s40s_e35_v32?0"TPSInclusivityInfo"8Q16^B24l
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80w_e39_v32?0"NSString"8"NSDictionary"16^B24l
+ ___copy_helper_block_e8_32s40s48s56s64r72r80r88r96r104w
+ ___destroy_helper_block_e8_32s40s48s56s64r72r80r88r96r104w
+ _objc_msgSend$applyRequestingBundleId:
+ _objc_msgSend$contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:requestingBundleId:bgTaskEvent:completionHandler:
+ _objc_msgSend$initWithTargetBundleIds:excludeBundleIds:requestingBundleId:
+ _objc_msgSend$processClientConditions:requestingBundleId:targetingCache:completionHandler:
+ _objc_msgSend$requestingBundleId
+ _objc_msgSend$setIgnoreCache:
+ _objc_msgSend$setRequestingBundleId:
+ _symbolic _____ 10TipsDaemon19BundleIdsValidationC
- -[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]
- -[TPSTipsManager processClientConditions:targetingCache:completionHandler:]
- GCC_except_table167
- GCC_except_table174
- GCC_except_table181
- GCC_except_table187
- GCC_except_table198
- __233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke
- __233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_2
- __75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke
- __75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke_2
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke
- ___233-[TPSTipsManager contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:]_block_invoke_2
- ___75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke
- ___75-[TPSTipsManager processClientConditions:targetingCache:completionHandler:]_block_invoke_2
- ___block_descriptor_104_e8_32s40s48s56r64r72r80r88r96w_e24_v16?0?<v?"NSError">8l
- ___block_descriptor_80_e8_32s40s48s56s64s72w_e39_v32?0"NSString"8"NSDictionary"16^B24l
- ___copy_helper_block_e8_32s40s48s56r64r72r80r88r96w
- ___copy_helper_block_e8_32s40s48s56s64s72w
- ___destroy_helper_block_e8_32s40s48s56r64r72r80r88r96w
- ___destroy_helper_block_e8_32s40s48s56s64s72w
- _objc_msgSend$contentWithMetaDictionary:documentsDictionary:processTipKitContent:contextualEligibility:widgetEligibility:notificationEligibility:userGuideEligibility:preferredNotificationIdentifiers:bgTaskEvent:completionHandler:
- _objc_msgSend$processClientConditions:targetingCache:completionHandler:
CStrings:
+ " - checking requesting bundle id: "
+ " - no requesting bundle id; condition does not match."
+ "TipsDaemon.BundleIdsValidation"
+ "bundleIds"
```
