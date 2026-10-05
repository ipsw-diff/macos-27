## AppleAccountUI

> `/System/Library/PrivateFrameworks/AppleAccountUI.framework/Versions/A/AppleAccountUI`

```diff

-589.125.5.0.0
-  __TEXT.__text: 0x75718
+589.125.7.0.0
+  __TEXT.__text: 0x757dc
   __TEXT.__objc_methlist: 0xb24
   __TEXT.__const: 0x6344
   __TEXT.__gcc_except_tab: 0x88

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xd78
+  __DATA_CONST.__objc_selrefs: 0xd80
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__objc_arraydata: 0xb0
-  __DATA_CONST.__got: 0x7f0
+  __DATA_CONST.__got: 0x7f8
   __AUTH_CONST.__const: 0x3b30
   __AUTH_CONST.__cfstring: 0x10e0
   __AUTH_CONST.__objc_const: 0x2f90

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 3391
-  Symbols:   2028
+  Symbols:   2030
   CStrings:  429
 
Symbols:
+ -[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:telemetryFlowID:completion:]
+ -[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:telemetryFlowID:context:completion:]
+ _OBJC_CLASS_$_AKSignoutInfo
+ __122-[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:telemetryFlowID:context:completion:]_block_invoke
+ __81-[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:telemetryFlowID:completion:]_block_invoke
+ ___122-[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:telemetryFlowID:context:completion:]_block_invoke
+ ___81-[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:telemetryFlowID:completion:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s64b
+ ___destroy_helper_block_e8_32s40s48s56s64s
+ _objc_msgSend$_signoutFromAuthKitForAltDSID:telemetryFlowID:completion:
+ _objc_msgSend$initWithReason:
+ _objc_msgSend$signoutForAltDSID:withSignoutInfo:completion:
- -[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:completion:]
- -[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:context:completion:]
- __106-[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:context:completion:]_block_invoke
- __65-[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:completion:]_block_invoke
- ___106-[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:context:completion:]_block_invoke
- ___65-[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:completion:]_block_invoke
- ___block_descriptor_64_e8_32s40s48s56bs_e5_v8?0l
- ___copy_helper_block_e8_32s40s48s56b
- ___destroy_helper_block_e8_32s40s48s56s
- _objc_msgSend$_signoutFromAuthKitForAltDSID:completion:
- _objc_msgSend$spyglassSignoutForAltDSID:completion:
Functions:
~ -[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:context:completion:] -> -[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:telemetryFlowID:context:completion:] : 1628 -> 1728
~ __106-[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:context:completion:]_block_invoke.32 -> __122-[AAUISignOutUtilities signOutServiceAccountsWithServiceOwnersManager:forAltDSID:DSID:telemetryFlowID:context:completion:]_block_invoke.32 : 636 -> 640
~ ___copy_helper_block_e8_32s40s48s56b -> ___copy_helper_block_e8_32s40s48s56s64b : 76 -> 84
~ ___destroy_helper_block_e8_32s40s48s56s -> ___destroy_helper_block_e8_32s40s48s56s64s : 64 -> 72
~ -[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:completion:] -> -[AAUISignOutUtilities _signoutFromAuthKitForAltDSID:telemetryFlowID:completion:] : 328 -> 404
```
