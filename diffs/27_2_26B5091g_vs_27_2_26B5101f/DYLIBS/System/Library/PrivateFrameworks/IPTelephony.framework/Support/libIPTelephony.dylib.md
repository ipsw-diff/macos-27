## libIPTelephony.dylib

> `/System/Library/PrivateFrameworks/IPTelephony.framework/Support/libIPTelephony.dylib`

```diff

-2772.1.0.0.0
-  __TEXT.__text: 0x4356a4
+2774.0.0.0.0
+  __TEXT.__text: 0x43584c
   __TEXT.__init_offsets: 0x18c
   __TEXT.__objc_methlist: 0xf9c
   __TEXT.__const: 0x1c160
-  __TEXT.__gcc_except_tab: 0x3bfbc
+  __TEXT.__gcc_except_tab: 0x3bfc0
   __TEXT.__cstring: 0x129ea
-  __TEXT.__oslogstring: 0x45932
+  __TEXT.__oslogstring: 0x45a24
   __TEXT.__unwind_info: 0x173e0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libxml2.2.dylib
   Functions: 14718
   Symbols:   22669
-  CStrings:  7778
+  CStrings:  7781
 
Functions:
~ __ZN12SipUserAgent20initializeAuthClientEb : 1436 -> 1432
~ __ZN9SDPParser24parseTTYFormatParametersER18SDPMediaFormatInfotNSt3__112basic_stringIcNS2_11char_traitsIcEENS2_9allocatorIcEEEE : 772 -> 888
~ __ZN21SipRegistrationClient14handleResponseENSt3__110shared_ptrIK11SipResponseEENS1_I20SipClientTransactionEE : 5440 -> 5584
~ __ZN18IPTelephonyManager18_initializeFromSIMERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEERKN3ims11StackConfigE : 3808 -> 4000
~ __ZN18IPTelephonyManager17initializeFromSIMERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEES8_RKN3ims11StackConfigENS0_10shared_ptrI8ImsPrefsEES8_ : 2232 -> 2208
CStrings:
+ "[ERROR]  %{private, mask.hash}sSip stack not found %{public}s"
+ "[WARN]   %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport, and I am roaming: accepted."
+ "[WARN]   %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport: ignored! Will retry Registration."
+ "[WARN]   TTY with unexpected format parameters parsed: '%s'"
- "[WARN]   %{private, mask.hash}sI need IPSec, but Reg 200 OK arrived over default transport: ignored. Will retry Registration."
```
