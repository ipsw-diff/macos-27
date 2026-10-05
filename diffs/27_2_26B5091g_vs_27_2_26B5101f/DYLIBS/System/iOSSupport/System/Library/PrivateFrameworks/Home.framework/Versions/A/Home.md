## Home

> `/System/iOSSupport/System/Library/PrivateFrameworks/Home.framework/Versions/A/Home`

```diff

-1265.0.0.4.2
-  __TEXT.__text: 0x387210
-  __TEXT.__objc_methlist: 0x2bcac
-  __TEXT.__const: 0x5320
+1269.2.3.0.1
+  __TEXT.__text: 0x3876b4
+  __TEXT.__objc_methlist: 0x2bce4
+  __TEXT.__const: 0x5318
   __TEXT.__swift5_typeref: 0x28a8
-  __TEXT.__oslogstring: 0x1bce3
+  __TEXT.__oslogstring: 0x1bdd3
   __TEXT.__swift5_reflstr: 0xd63
   __TEXT.__swift5_assocty: 0x2e8
   __TEXT.__swift5_fieldmd: 0x10a8

   __TEXT.__swift5_protos: 0x40
   __TEXT.__swift5_proto: 0x23c
   __TEXT.__swift5_types: 0x17c
-  __TEXT.__cstring: 0x3440a
+  __TEXT.__cstring: 0x3443e
   __TEXT.__swift5_capture: 0xf18
   __TEXT.__swift_as_entry: 0x21c
   __TEXT.__swift_as_ret: 0x1e4

   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__gcc_except_tab: 0x4a8c
   __TEXT.__ustring: 0x72
-  __TEXT.__unwind_info: 0x11390
-  __TEXT.__eh_frame: 0x67a0
+  __TEXT.__unwind_info: 0x113a8
+  __TEXT.__eh_frame: 0x67d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x10d88
+  __DATA_CONST.__const: 0x10d98
   __DATA_CONST.__objc_classlist: 0x1828
   __DATA_CONST.__objc_catlist: 0x418
   __DATA_CONST.__objc_protolist: 0x8d0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x12880
+  __DATA_CONST.__objc_selrefs: 0x128a0
   __DATA_CONST.__objc_protorefs: 0x3d0
   __DATA_CONST.__objc_superrefs: 0x12e8
   __DATA_CONST.__objc_arraydata: 0x3c8
   __DATA_CONST.__got: 0x30d0
   __AUTH_CONST.__const: 0xeb18
-  __AUTH_CONST.__cfstring: 0x26ee0
+  __AUTH_CONST.__cfstring: 0x26f20
   __AUTH_CONST.__objc_const: 0x4b018
   __AUTH_CONST.__objc_intobj: 0x22e0
   __AUTH_CONST.__objc_arrayobj: 0x270

   __AUTH.__objc_data: 0x9fe8
   __AUTH.__data: 0x1230
   __DATA.__objc_ivar: 0x1554
-  __DATA.__data: 0x72a0
+  __DATA.__data: 0x72b0
   __DATA.__objc_stublist: 0x10
   __DATA.__bss: 0x37d0
   __DATA.__common: 0x120
   __DATA_DIRTY.__objc_ivar: 0xcb4
   __DATA_DIRTY.__objc_data: 0x6700
   __DATA_DIRTY.__data: 0xee8
-  __DATA_DIRTY.__bss: 0x1d80
+  __DATA_DIRTY.__bss: 0x1d70
   __DATA_DIRTY.__common: 0x60
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 20608
-  Symbols:   37426
-  CStrings:  8339
+  Functions: 20613
+  Symbols:   37437
+  CStrings:  8345
 
Symbols:
+ +[HFHomeKitDispatcher isProxPairingLaunch]
+ +[HFHomeKitDispatcher setIsProxPairingLaunch:]
+ -[HFHomeKitDispatcher _allowsLocationSensing]
+ -[HFSoftwareUpdateManager isSoftwareUpdateOnAssetServer:]
+ -[HMAccessory(HFSoftwareUpdateAdditions) hf_isSoftwareUpdateOnAssetServer]
+ GCC_except_table193
+ GCC_except_table194
+ GCC_except_table197
+ GCC_except_table39
+ GCC_except_table45
+ GCC_except_table54
+ GCC_except_table59
+ GCC_except_table77
+ GCC_except_table79
+ _HFPreferencesCameraClipsDebugMenuKey
+ ___isProxPairingLaunch
+ _objc_msgSend$_allowsLocationSensing
+ _objc_msgSend$failureError
+ _objc_msgSend$isProxPairingLaunch
+ _objc_msgSend$isSoftwareUpdateOnAssetServer:
- -[NSError(HFAdditions) hf_isNFCReaderTooHotError]
- GCC_except_table160
- GCC_except_table191
- GCC_except_table192
- GCC_except_table195
- GCC_except_table57
- GCC_except_table70
- GCC_except_table78
- __55-[HFHomeKitDispatcher _setupLocationSensingCoordinator]_block_invoke
CStrings:
+ "No software update to check: %@"
+ "OnAssetServer"
+ "Update State: %@; On Asset Server: %{BOOL}d; %@"
+ "_allowsLocationSensing -> %{bool}d (hostProcess: %ld, isAllowedProcess: %{bool}d, isProxPairingLaunchInHomeUIService: %{bool}d, isRunningOnAccessory: %{bool}d)"
+ "cameraClipsShowDebugMenu"
+ "prox_pairing"
```
