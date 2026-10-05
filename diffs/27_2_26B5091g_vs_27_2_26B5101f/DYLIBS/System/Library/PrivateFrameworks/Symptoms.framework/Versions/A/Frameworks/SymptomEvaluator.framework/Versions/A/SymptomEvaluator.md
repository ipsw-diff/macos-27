## SymptomEvaluator

> `/System/Library/PrivateFrameworks/Symptoms.framework/Versions/A/Frameworks/SymptomEvaluator.framework/Versions/A/SymptomEvaluator`

```diff

-2394.40.15.0.0
-  __TEXT.__text: 0x1f23bc
+2394.40.16.0.0
+  __TEXT.__text: 0x1f2640
   __TEXT.__objc_methlist: 0x12554
-  __TEXT.__cstring: 0x1ba2f
+  __TEXT.__cstring: 0x1ba6f
   __TEXT.__const: 0xf10
-  __TEXT.__oslogstring: 0x2ab95
+  __TEXT.__oslogstring: 0x2ac75
   __TEXT.__gcc_except_tab: 0x315c
   __TEXT.__dlopen_cstrs: 0x56
   __TEXT.__swift5_typeref: 0x38d

   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x20
   __AUTH_CONST.__objc_arrayobj: 0x60
-  __AUTH_CONST.__auth_got: 0x1410
+  __AUTH_CONST.__auth_got: 0x1420
   __AUTH.__objc_data: 0xbd8
   __AUTH.__data: 0xc8
   __DATA.__objc_ivar: 0x1f40

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   Functions: 9503
-  Symbols:   18684
-  CStrings:  8478
+  Symbols:   18686
+  CStrings:  8482
 
Symbols:
+ _audit_token_to_pid
+ _csops_audittoken
Functions:
~ -[ManagedEventTransport _createReply:forConnection:] : 1368 -> 2012
CStrings:
+ "Managed event caller (pid %d) authorized: %{public}s entitlement"
+ "Managed event caller (pid %d) authorized: platform binary"
+ "Managed event request from caller (pid %d) denied: not a platform binary and missing entitlement %{public}s"
+ "com.apple.symptoms.symptomsd.managed_events.read"
```
