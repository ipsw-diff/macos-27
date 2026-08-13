## libIPTelephony.dylib

> `/System/Library/PrivateFrameworks/IPTelephony.framework/Support/libIPTelephony.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__weak_got`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`
- `__DATA_DIRTY.__data`

```diff

-2764.0.0.0.0
-  __TEXT.__text: 0x439738
-  __TEXT.__init_offsets: 0x188
+2765.0.0.0.0
+  __TEXT.__text: 0x439a18
+  __TEXT.__init_offsets: 0x18c
   __TEXT.__objc_methlist: 0xf9c
   __TEXT.__const: 0x1c070
-  __TEXT.__gcc_except_tab: 0x3b7b4
-  __TEXT.__cstring: 0x12969
-  __TEXT.__oslogstring: 0x455e3
+  __TEXT.__gcc_except_tab: 0x3b7ec
+  __TEXT.__cstring: 0x129ce
+  __TEXT.__oslogstring: 0x45676
   __TEXT.__unwind_info: 0x15b58
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH.__objc_data: 0x3c0
   __DATA.__objc_ivar: 0x164
   __DATA.__data: 0x3a8
-  __DATA.__common: 0x130
+  __DATA.__common: 0x148
   __DATA.__bss: 0x1b8
   __DATA_DIRTY.__objc_data: 0xa0
   __DATA_DIRTY.__data: 0x249

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 14669
-  Symbols:   22607
-  CStrings:  7697
+  Functions: 14670
+  Symbols:   22610
+  CStrings:  7699
 
Symbols:
+ _GLOBAL__sub_I_SipRegistrationMetrics.cpp
+ __ZN22SipRegistrationMetrics39kReasonIPSecCompletionEnforcementFailedE
+ __ZN9ImsResultlsIA68_cEERS_RKT_
Functions:
~ __ZN21SipRegistrationClient14handleResponseENSt3__110shared_ptrIK11SipResponseEENS1_I20SipClientTransactionEE : 4916 -> 5440
+ _GLOBAL__sub_I_SipRegistrationMetrics.cpp
~ __ZN9SipDialog19cancelInviteRequestENSt3__110shared_ptrI20SipClientTransactionEEPK24ImsCallTerminationReason : 1236 -> 1208
~ __ZN13LazuliSession19handleInviteFailureEjRKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEERK6SipUrijN3xpc5arrayE : 7912 -> 8024
CStrings:
+ "%{private, mask.hash}sreceived Reg 200 OK. EnableIPSec: %{bool}d, Enforce IPSec: %{bool}d, DefaultTransportGroup: %p, RecvTransportGroup: %p, isEmergency: %{bool}d"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.3EJBFt/Sources/ipTelephony/Source/Daemon/Core/AWD/cpp/CATM.pb.cc"
+ "IPSec completion enforcement: 200 OK on insecure transport rejected"
+ "IPSecCompletionEnforcementFailed"
+ "[WARN]   %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport: ignored. Will retry Registration."
- "%{private, mask.hash}sreceived Reg 200 OK"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.jffAhC/Sources/ipTelephony/Source/Daemon/Core/AWD/cpp/CATM.pb.cc"
- "[WARN]   %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport: ignored."
```
