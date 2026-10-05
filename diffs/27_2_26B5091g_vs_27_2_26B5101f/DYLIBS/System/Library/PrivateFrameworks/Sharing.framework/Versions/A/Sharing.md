## Sharing

> `/System/Library/PrivateFrameworks/Sharing.framework/Versions/A/Sharing`

```diff

-2131.20.71.0.0
-  __TEXT.__text: 0x33491c
-  __TEXT.__objc_methlist: 0x12d0c
-  __TEXT.__cstring: 0x2cd68
-  __TEXT.__const: 0x21ddc
-  __TEXT.__gcc_except_tab: 0x3544
-  __TEXT.__oslogstring: 0xcd83
+2131.21.21.0.0
+  __TEXT.__text: 0x3361bc
+  __TEXT.__objc_methlist: 0x12ebc
+  __TEXT.__cstring: 0x2ce68
+  __TEXT.__const: 0x21f7c
+  __TEXT.__gcc_except_tab: 0x35a4
+  __TEXT.__oslogstring: 0xcf13
   __TEXT.__dlopen_cstrs: 0x5f2
   __TEXT.__ustring: 0x18
-  __TEXT.__swift5_typeref: 0x8939
-  __TEXT.__constg_swiftt: 0x7250
-  __TEXT.__swift5_reflstr: 0x40fa
-  __TEXT.__swift5_fieldmd: 0x7028
+  __TEXT.__swift5_typeref: 0x89e9
+  __TEXT.__constg_swiftt: 0x726c
+  __TEXT.__swift5_reflstr: 0x417a
+  __TEXT.__swift5_fieldmd: 0x7044
   __TEXT.__swift5_builtin: 0x1e0
-  __TEXT.__swift5_assocty: 0x10d0
+  __TEXT.__swift5_assocty: 0x1130
   __TEXT.__swift5_capture: 0x29e4
   __TEXT.__swift5_protos: 0x28
-  __TEXT.__swift5_proto: 0x1cb0
-  __TEXT.__swift5_types: 0x950
+  __TEXT.__swift5_proto: 0x1cc8
+  __TEXT.__swift5_types: 0x954
   __TEXT.__swift_as_entry: 0x40c
   __TEXT.__swift_as_ret: 0x40c
   __TEXT.__swift_as_cont: 0xa88
   __TEXT.__swift5_mpenum: 0xb8
-  __TEXT.__unwind_info: 0x11850
-  __TEXT.__eh_frame: 0xeb0c
+  __TEXT.__unwind_info: 0x118d8
+  __TEXT.__eh_frame: 0xeb54
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2e70
-  __DATA_CONST.__objc_classlist: 0x870
+  __DATA_CONST.__const: 0x2e88
+  __DATA_CONST.__objc_classlist: 0x878
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x360
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8710
+  __DATA_CONST.__objc_selrefs: 0x87b0
   __DATA_CONST.__objc_protorefs: 0x1d8
   __DATA_CONST.__objc_classrefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x508
   __DATA_CONST.__objc_arraydata: 0x2f0
-  __DATA_CONST.__got: 0x1290
-  __AUTH_CONST.__const: 0x1c3d0
-  __AUTH_CONST.__cfstring: 0x11840
-  __AUTH_CONST.__objc_const: 0x356a8
+  __DATA_CONST.__got: 0x12b8
+  __AUTH_CONST.__const: 0x1c450
+  __AUTH_CONST.__cfstring: 0x11900
+  __AUTH_CONST.__objc_const: 0x359d8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x498
   __AUTH_CONST.__objc_dictobj: 0x398
   __AUTH_CONST.__objc_arrayobj: 0xa8
-  __AUTH_CONST.__auth_got: 0x2960
-  __AUTH.__objc_data: 0x2b58
-  __AUTH.__data: 0x3090
-  __DATA.__objc_ivar: 0x1fc8
-  __DATA.__data: 0xb980
-  __DATA.__bss: 0x397c0
+  __AUTH_CONST.__auth_got: 0x2968
+  __AUTH.__objc_data: 0x2ba8
+  __AUTH.__data: 0x3098
+  __DATA.__objc_ivar: 0x1ff4
+  __DATA.__data: 0xb9f0
+  __DATA.__bss: 0x39ac0
   __DATA.__common: 0x160
   __DATA_DIRTY.__objc_data: 0x4588
-  __DATA_DIRTY.__data: 0x1398
+  __DATA_DIRTY.__data: 0x1388
   __DATA_DIRTY.__bss: 0x428
   __DATA_DIRTY.__common: 0x60
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 21820
-  Symbols:   21239
-  CStrings:  7466
+  Functions: 21897
+  Symbols:   21317
+  CStrings:  7481
 
Symbols:
+ +[SFCollaborationRouteEvent eventName]
+ +[SFCollaborationRouteEvent routeCodeForActivityType:]
+ -[NSURL(Sharing) sf_hasSchemeIn:]
+ -[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]
+ -[SFAutoUnlockManager _releasePairingContextForDevice:]
+ -[SFAutoUnlockManager enableAutoUnlockWithDevice:passcodeRef:]
+ -[SFAutoUnlockManager pairingLAContexts]
+ -[SFCollaborationPerformer _submitRouteEventIfNeededWithOutcome:error:]
+ -[SFCollaborationPerformer _suppressRouteEvent]
+ -[SFCollaborationPerformer dealloc]
+ -[SFCollaborationPerformer didReportRouteEvent]
+ -[SFCollaborationPerformer performStartTicks]
+ -[SFCollaborationPerformer reportCreationFailureWithError:]
+ -[SFCollaborationPerformer routeItemType]
+ -[SFCollaborationPerformer setDidReportRouteEvent:]
+ -[SFCollaborationPerformer setPerformStartTicks:]
+ -[SFCollaborationPerformer setRouteItemType:]
+ -[SFCollaborationRouteEvent .cxx_destruct]
+ -[SFCollaborationRouteEvent activityType]
+ -[SFCollaborationRouteEvent errorCode]
+ -[SFCollaborationRouteEvent errorDomain]
+ -[SFCollaborationRouteEvent eventPayload]
+ -[SFCollaborationRouteEvent hostAppBundleID]
+ -[SFCollaborationRouteEvent itemType]
+ -[SFCollaborationRouteEvent outcome]
+ -[SFCollaborationRouteEvent setActivityType:]
+ -[SFCollaborationRouteEvent setErrorCode:]
+ -[SFCollaborationRouteEvent setErrorDomain:]
+ -[SFCollaborationRouteEvent setHostAppBundleID:]
+ -[SFCollaborationRouteEvent setItemType:]
+ -[SFCollaborationRouteEvent setOutcome:]
+ -[SFCollaborationRouteEvent setWaitMs:]
+ -[SFCollaborationRouteEvent submitEvent]
+ -[SFCollaborationRouteEvent waitMs]
+ GCC_except_table62
+ GCC_except_table90
+ OBJC_IVAR_$_SFAutoUnlockManager._pairingLAContexts
+ OBJC_IVAR_$_SFCollaborationPerformer._didReportRouteEvent
+ OBJC_IVAR_$_SFCollaborationPerformer._performStartTicks
+ OBJC_IVAR_$_SFCollaborationPerformer._routeItemType
+ OBJC_IVAR_$_SFCollaborationRouteEvent._activityType
+ OBJC_IVAR_$_SFCollaborationRouteEvent._errorCode
+ OBJC_IVAR_$_SFCollaborationRouteEvent._errorDomain
+ OBJC_IVAR_$_SFCollaborationRouteEvent._hostAppBundleID
+ OBJC_IVAR_$_SFCollaborationRouteEvent._itemType
+ OBJC_IVAR_$_SFCollaborationRouteEvent._outcome
+ OBJC_IVAR_$_SFCollaborationRouteEvent._waitMs
+ _OBJC_CLASS_$_SFCollaborationRouteEvent
+ _OBJC_METACLASS_$_SFCollaborationRouteEvent
+ __72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke
+ __OBJC_$_CLASS_METHODS_SFCollaborationRouteEvent
+ __OBJC_$_CLASS_PROP_LIST_SFCollaborationRouteEvent
+ __OBJC_$_INSTANCE_METHODS_SFCollaborationRouteEvent
+ __OBJC_$_INSTANCE_VARIABLES_SFCollaborationRouteEvent
+ __OBJC_$_PROP_LIST_SFCollaborationRouteEvent
+ __OBJC_CLASS_PROTOCOLS_$_SFCollaborationRouteEvent
+ __OBJC_CLASS_RO_$_SFCollaborationRouteEvent
+ __OBJC_METACLASS_RO_$_SFCollaborationRouteEvent
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_2
+ ___72-[SFAutoUnlockManager _enableAutoUnlockWithDevice:passcode:passcodeRef:]_block_invoke_3
+ __xpc_type_array
+ _associated conformance 7Sharing9URLSchemeVSHAASQ
+ _associated conformance 7Sharing9URLSchemeVs26ExpressibleByStringLiteralAA0eF4TypesADP_s01_cd7BuiltineF0
+ _associated conformance 7Sharing9URLSchemeVs26ExpressibleByStringLiteralAAs0cd23ExtendedGraphemeClusterF0
+ _associated conformance 7Sharing9URLSchemeVs33ExpressibleByUnicodeScalarLiteralAA0efG4TypesADP_s01_cd7BuiltinefG0
+ _associated conformance 7Sharing9URLSchemeVs43ExpressibleByExtendedGraphemeClusterLiteralAA0efgH4TypesADP_s01_cd7BuiltinefgH0
+ _associated conformance 7Sharing9URLSchemeVs43ExpressibleByExtendedGraphemeClusterLiteralAAs0cd13UnicodeScalarH0
+ _objc_msgSend$_enableAutoUnlockWithDevice:passcode:passcodeRef:
+ _objc_msgSend$_releasePairingContextForDevice:
+ _objc_msgSend$_submitRouteEventIfNeededWithOutcome:error:
+ _objc_msgSend$_suppressRouteEvent
+ _objc_msgSend$enableAutoUnlockWithDevice:passcodeRef:clientProxy:
+ _objc_msgSend$itemType
+ _objc_msgSend$outcome
+ _objc_msgSend$routeCodeForActivityType:
+ _objc_msgSend$setItemType:
+ _objc_msgSend$setOutcome:
+ _objc_msgSend$setWaitMs:
+ _objc_msgSend$waitMs
+ _symbolic $ss26ExpressibleByStringLiteralP
+ _symbolic $ss33ExpressibleByUnicodeScalarLiteralP
+ _symbolic $ss43ExpressibleByExtendedGraphemeClusterLiteralP
+ _symbolic _____ 7Sharing9URLSchemeV
+ _type_layout_string 7Sharing9URLSchemeV
+ _xpc_type_get_name
- GCC_except_table48
- GCC_except_table70
- GCC_except_table75
- __59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_2
- ___59-[SFAutoUnlockManager enableAutoUnlockWithDevice:passcode:]_block_invoke_3
- _objc_msgSend$enableAutoUnlockWithDevice:passcode:clientProxy:
CStrings:
+ "### Ignoring CLI mode / forced PIN from unauthenticated PreAuth on non-internal build\n"
+ "Handing off to Manage Share, not reporting a collaboration route"
+ "MusicHandoffScan"
+ "QUICHTTPPerf server is internal-only; refusing to start listener on a customer build"
+ "QUICHTTPPerf server is not available on this build"
+ "Report collaboration route: %{public}@"
+ "com.apple.sharing.collaborationRoute"
+ "createSFNodeKindsFromXPCArray: expected an XPC array, got %{public}s"
+ "createSFNodeKindsFromXPCArray: skipping unknown kind %ld at array index %ld"
+ "getSFNodeKindForIndex: index %ld out of range (count %ld)"
+ "iPhoneDuo"
+ "itemType"
+ "outcome"
+ "route"
+ "waitMs"
```
