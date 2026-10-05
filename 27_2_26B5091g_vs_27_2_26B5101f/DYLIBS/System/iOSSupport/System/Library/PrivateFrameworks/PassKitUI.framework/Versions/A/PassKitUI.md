## PassKitUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/PassKitUI.framework/Versions/A/PassKitUI`

```diff

-1696.2.6.1.0
-  __TEXT.__text: 0x174204
-  __TEXT.__objc_methlist: 0xbb98
-  __TEXT.__const: 0x108d8
-  __TEXT.__swift5_typeref: 0xa17c
-  __TEXT.__constg_swiftt: 0x4d40
-  __TEXT.__swift5_fieldmd: 0x3aa4
+1696.2.8.1.0
+  __TEXT.__text: 0x174504
+  __TEXT.__objc_methlist: 0xbbd8
+  __TEXT.__const: 0x10940
+  __TEXT.__swift5_typeref: 0xa182
+  __TEXT.__constg_swiftt: 0x4d4c
+  __TEXT.__swift5_fieldmd: 0x3ab0
   __TEXT.__swift5_builtin: 0x230
-  __TEXT.__swift5_reflstr: 0x4202
+  __TEXT.__swift5_reflstr: 0x4212
   __TEXT.__swift5_assocty: 0x1528
-  __TEXT.__oslogstring: 0x3dc9
+  __TEXT.__oslogstring: 0x3e27
   __TEXT.__swift5_proto: 0x988
   __TEXT.__swift5_types: 0x420
-  __TEXT.__swift_as_entry: 0x220
-  __TEXT.__swift_as_cont: 0x21c
-  __TEXT.__cstring: 0x98e0
+  __TEXT.__swift_as_entry: 0x224
+  __TEXT.__swift_as_cont: 0x220
+  __TEXT.__cstring: 0x98e3
   __TEXT.__swift5_protos: 0x4c
-  __TEXT.__swift_as_ret: 0x220
+  __TEXT.__swift_as_ret: 0x228
   __TEXT.__swift5_capture: 0x66c
   __TEXT.__swift5_mpenum: 0x18
   __TEXT.__gcc_except_tab: 0xebc
   __TEXT.__ustring: 0x4c
-  __TEXT.__unwind_info: 0x78c0
-  __TEXT.__eh_frame: 0x3418
+  __TEXT.__unwind_info: 0x78e8
+  __TEXT.__eh_frame: 0x33c4
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xd8
   __DATA_CONST.__objc_protolist: 0x2b0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7b98
+  __DATA_CONST.__objc_selrefs: 0x7bc8
   __DATA_CONST.__objc_protorefs: 0xf0
   __DATA_CONST.__objc_superrefs: 0x468
   __DATA_CONST.__objc_arraydata: 0xc0
-  __DATA_CONST.__got: 0x2060
+  __DATA_CONST.__got: 0x2058
   __AUTH_CONST.__const: 0x8160
   __AUTH_CONST.__cfstring: 0x4a20
-  __AUTH_CONST.__objc_const: 0x19ff0
+  __AUTH_CONST.__objc_const: 0x1a048
   __AUTH_CONST.__objc_intobj: 0x468
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_doubleobj: 0x60
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_floatobj: 0x30
-  __AUTH_CONST.__auth_got: 0x26e8
-  __AUTH.__objc_data: 0x66c0
+  __AUTH_CONST.__auth_got: 0x26f8
+  __AUTH.__objc_data: 0x6710
   __AUTH.__data: 0x3b58
-  __DATA.__objc_ivar: 0x5b8
+  __DATA.__objc_ivar: 0x5c4
   __DATA.__data: 0x5639
   __DATA.__common: 0x548
   __DATA.__bss: 0x122b8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 9108
-  Symbols:   12687
-  CStrings:  1522
+  Functions: 9117
+  Symbols:   12702
+  CStrings:  1523
 
Symbols:
+ -[PKLinkedApplication _beginLoadingApplicationState]
+ -[PKLinkedApplication _resolveApplicationStateCompletionsAndContinueIfNeeded:]
+ -[PKLinkedApplication hasObservedInstall]
+ -[PKLinkedApplication installedBundleIdentifier]
+ -[PKLinkedApplication openPotentialUniversalLinkWithCompletion:]
+ -[PKPaymentAuthorizationController _setRetainSelf:]
+ GCC_except_table29
+ OBJC_IVAR_$_PKLinkedApplication._installedApplicationsChangeRequiresReload
+ OBJC_IVAR_$_PKLinkedApplication._observedInstall
+ OBJC_IVAR_$_PKPaymentAuthorizationController._retainSelfLock
+ _PKPeerPaymentReceiptMockingEnabled
+ __Z17PKOpenApplicationP8NSStringP25FBSOpenApplicationOptionsU13block_pointerFvbP7NSErrorE
+ ___52-[PKLinkedApplication _beginLoadingApplicationState]_block_invoke
+ __swift_closure_destructor.6Tm
+ _objc_msgSend$_beginLoadingApplicationState
+ _objc_msgSend$_resolveApplicationStateCompletionsAndContinueIfNeeded:
+ _objc_msgSend$_setRetainSelf:
+ _symbolic _____ 11PassKitCore37ProvisioningDeviceTransferContentTypeO
- GCC_except_table26
- ___61-[PKLinkedApplication _reloadApplicationStateWithCompletion:]_block_invoke
- __swift_closure_destructor.5Tm
CStrings:
+ "PKLinkedApplication: openPotentialUniversalLinkWithCompletion: called on unavailable platform"
```
