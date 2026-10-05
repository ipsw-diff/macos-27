## TelephonyUtilities

> `/System/Library/PrivateFrameworks/TelephonyUtilities.framework/Versions/A/TelephonyUtilities`

```diff

-1626.200.65.0.0
-  __TEXT.__text: 0x1b33ac
-  __TEXT.__objc_methlist: 0x1ba18
-  __TEXT.__cstring: 0x12916
-  __TEXT.__const: 0x4adc
-  __TEXT.__oslogstring: 0x136a7
+1626.200.84.0.0
+  __TEXT.__text: 0x1b8c34
+  __TEXT.__objc_methlist: 0x1bac0
+  __TEXT.__cstring: 0x12a16
+  __TEXT.__const: 0x4b6c
+  __TEXT.__oslogstring: 0x13a1a
   __TEXT.__gcc_except_tab: 0x141c
   __TEXT.__ustring: 0xde
   __TEXT.__dlopen_cstrs: 0x4fb
-  __TEXT.__constg_swiftt: 0xeb0
-  __TEXT.__swift5_typeref: 0x13a1
+  __TEXT.__constg_swiftt: 0xec4
+  __TEXT.__swift5_typeref: 0x1443
   __TEXT.__swift5_builtin: 0xc8
   __TEXT.__swift5_reflstr: 0xc89
-  __TEXT.__swift5_fieldmd: 0x1354
+  __TEXT.__swift5_fieldmd: 0x1320
   __TEXT.__swift5_assocty: 0xf0
-  __TEXT.__swift5_proto: 0x3e0
-  __TEXT.__swift5_types: 0x150
-  __TEXT.__swift5_capture: 0x2b8
-  __TEXT.__swift_as_entry: 0xb4
-  __TEXT.__swift_as_ret: 0xcc
-  __TEXT.__swift_as_cont: 0x194
+  __TEXT.__swift5_proto: 0x3d8
+  __TEXT.__swift5_types: 0x14c
+  __TEXT.__swift5_capture: 0x38c
+  __TEXT.__swift_as_entry: 0xec
+  __TEXT.__swift_as_ret: 0x104
+  __TEXT.__swift_as_cont: 0x1e4
   __TEXT.__swift5_protos: 0x14
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x8f28
-  __TEXT.__eh_frame: 0x2a70
+  __TEXT.__unwind_info: 0x9140
+  __TEXT.__eh_frame: 0x31d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1948
+  __DATA_CONST.__const: 0x1950
   __DATA_CONST.__objc_classlist: 0x8b8
   __DATA_CONST.__objc_catlist: 0xc0
   __DATA_CONST.__objc_protolist: 0x420
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xb690
+  __DATA_CONST.__objc_selrefs: 0xb6d0
   __DATA_CONST.__objc_protorefs: 0x110
   __DATA_CONST.__objc_superrefs: 0x700
   __DATA_CONST.__objc_arraydata: 0xac0
-  __DATA_CONST.__got: 0x1048
-  __AUTH_CONST.__const: 0x6780
-  __AUTH_CONST.__cfstring: 0x12580
-  __AUTH_CONST.__objc_const: 0x2b578
+  __DATA_CONST.__got: 0x1040
+  __AUTH_CONST.__const: 0x6888
+  __AUTH_CONST.__cfstring: 0x12660
+  __AUTH_CONST.__objc_const: 0x2b600
   __AUTH_CONST.__objc_intobj: 0x318
   __AUTH_CONST.__objc_doubleobj: 0x40
   __AUTH_CONST.__objc_arrayobj: 0x2e8
-  __AUTH_CONST.__auth_got: 0x1378
+  __AUTH_CONST.__auth_got: 0x1360
   __AUTH.__objc_data: 0x2510
-  __AUTH.__data: 0xcf0
-  __DATA.__objc_ivar: 0x1940
-  __DATA.__data: 0x3f10
-  __DATA.__bss: 0x7ae0
+  __AUTH.__data: 0xd18
+  __DATA.__objc_ivar: 0x1948
+  __DATA.__data: 0x3f30
+  __DATA.__bss: 0x79e0
   __DATA.__common: 0xb0
   __DATA_DIRTY.__objc_data: 0x3488
   __DATA_DIRTY.__data: 0x198

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11743
-  Symbols:   20557
-  CStrings:  4438
+  Functions: 11840
+  Symbols:   20587
+  CStrings:  4452
 
Symbols:
+ +[NSPredicate(TUManagedConversationLinkDescriptor) tu_predicateForConversationLinkDescriptorsIsAccessibilityLink:]
+ +[NSPredicate(TUManagedConversationLinkDescriptor) tu_predicateForConversationLinkDescriptorsWithPseudonyms:]
+ -[TUContinuityConversationLink groupUUID]
+ -[TUContinuityConversationLink initWithTUConversationLink:displayName:date:uniqueId:groupUUID:]
+ -[TUConversationLink isAccessibilityLink]
+ -[TUConversationManager accessibilityLinkPseudonymsAmongPseudonyms:completionHandler:]
+ -[TUConversationManager interpreterRequestWithID:debugSendLink:toHandle:]
+ -[TUConversationManagerXPCClient accessibilityLinkPseudonymsAmongPseudonyms:completionHandler:]
+ -[TUConversationManagerXPCClient interpreterRequestWithID:debugSendLink:toHandle:]
+ -[TUJoinConversationRequest handlesToAddAfterHandoff]
+ -[TUJoinConversationRequest setHandlesToAddAfterHandoff:]
+ GCC_except_table103
+ GCC_except_table108
+ GCC_except_table167
+ GCC_except_table175
+ GCC_except_table182
+ GCC_except_table216
+ OBJC_IVAR_$_TUContinuityConversationLink._groupUUID
+ OBJC_IVAR_$_TUJoinConversationRequest._handlesToAddAfterHandoff
+ _TUSimulatedModeEnabledKey
+ ___73-[TUConversationManager interpreterRequestWithID:debugSendLink:toHandle:]_block_invoke
+ ___73-[TUConversationManager interpreterRequestWithID:debugSendLink:toHandle:]_block_invoke_2
+ ___82-[TUConversationManagerXPCClient interpreterRequestWithID:debugSendLink:toHandle:]_block_invoke
+ ___95-[TUConversationManagerXPCClient accessibilityLinkPseudonymsAmongPseudonyms:completionHandler:]_block_invoke
+ _objc_msgSend$accessibilityLinkPseudonymsAmongPseudonyms:completionHandler:
+ _objc_msgSend$conversationManager:debugSendInterpreterLink:toHandle:
+ _objc_msgSend$handlesToAddAfterHandoff
+ _objc_msgSend$initWithTUConversationLink:displayName:date:uniqueId:groupUUID:
+ _objc_msgSend$interpreterRequestWithID:debugSendLink:toHandle:
+ _objc_msgSend$setHandlesToAddAfterHandoff:
+ _swift_deletedAsyncMethodErrorTu
+ _symbolic Scgyyt______pG s5ErrorP
+ _symbolic ShySSG
+ _symbolic ShySSGIeAgHr_
+ _symbolic _____ySSSaySo8TUHandleCGG s18_DictionaryStorageC
+ _symbolic _____yShySSGG 2os21OSAllocatedUnfairLockV
+ _symbolic _____yShySSG_G ScG8IteratorV
+ _symbolic _____yShySSG_____G s13ManagedBufferCsRi__rlE So16os_unfair_lock_sV
+ _symbolic _____ySo8TUHandleCSbG s18_DictionaryStorageC
+ _symbolic _____y_____y_____GG 2os21OSAllocatedUnfairLockV 18TelephonyUtilities23CancellableContinuationO AD15ResponseWrapperV
+ _symbolic yt______pIeghHrzo_ s5ErrorP
- -[TUContinuityConversationLink initWithTUConversationLink:displayName:date:uniqueId:]
- GCC_except_table102
- GCC_except_table106
- GCC_except_table165
- GCC_except_table173
- GCC_except_table180
- GCC_except_table214
- _associated conformance 18TelephonyUtilities17TUCallContextCardV4ItemO8BirthdayV15TUBirthdayStateOSHAASQ
- _objc_msgSend$initWithTUConversationLink:displayName:date:uniqueId:
- _objc_msgSend$simulatedModeEnabled
- _symbolic _____ 18TelephonyUtilities17TUCallContextCardV4ItemO8BirthdayV15TUBirthdayStateO
CStrings:
+ " handlesToAddAfterHandoff=%@"
+ "Asked which of %lu pseudonym(s) are accessibility links"
+ "Companion Lockdown Mode Enabled"
+ "Error in retrieving accessibility link pseudonyms: %@"
+ "FaceTimeServiceAvailabilityHelper: Cannot generate IDS destination for handle, reporting false for handle: %@"
+ "FaceTimeServiceAvailabilityHelper: Every destination is FaceTime available, no need to wait for the remaining services"
+ "FaceTimeServiceAvailabilityHelper: Got %{public}s back for availability of service %s: %@"
+ "FaceTimeServiceAvailabilityHelper: Querying availability of FaceTime services for %ld handles across %ld destinations with timeout: %s"
+ "FaceTimeServiceAvailabilityHelper: The ID status cache reported every destination valid for service %s, skipping the network lookup"
+ "FaceTimeServiceAvailabilityHelper: Timeout reached querying batch availability of FaceTime, returning the results gathered so far"
+ "SimulatedModeEnabled"
+ "The companion device could not complete the operation because it has Lockdown Mode enabled."
+ "accessibilityReqUUID != NULL"
+ "accessibilityReqUUID == NULL"
+ "idStatus(for:service:fromNetwork:)"
+ "pseudonym IN %@"
- "requiredIDStatus(for:service:)"
- "simulatedMode"
```
