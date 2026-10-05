## PowerlogHelperdOperators

> `/System/Library/PrivateFrameworks/PowerlogHelperdOperators.framework/Versions/A/PowerlogHelperdOperators`

```diff

-3486.40.99.0.0
-  __TEXT.__text: 0x110c2c
-  __TEXT.__objc_methlist: 0xa7d8
-  __TEXT.__const: 0x4b0
-  __TEXT.__cstring: 0x16a24
-  __TEXT.__oslogstring: 0xb378
+3486.40.113.0.0
+  __TEXT.__text: 0x1110e4
+  __TEXT.__objc_methlist: 0xa808
+  __TEXT.__const: 0x4c0
+  __TEXT.__cstring: 0x16a94
+  __TEXT.__oslogstring: 0xb40e
   __TEXT.__gcc_except_tab: 0x1cf0
   __TEXT.__unwind_info: 0x3968
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x7360
+  __DATA_CONST.__objc_selrefs: 0x7390
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x1d8
-  __DATA_CONST.__objc_arraydata: 0x2bc8
+  __DATA_CONST.__objc_arraydata: 0x2ba8
   __DATA_CONST.__got: 0xac0
   __AUTH_CONST.__const: 0x2c38
-  __AUTH_CONST.__cfstring: 0x20ca0
-  __AUTH_CONST.__objc_const: 0xd6f8
+  __AUTH_CONST.__cfstring: 0x20d00
+  __AUTH_CONST.__objc_const: 0xd758
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__objc_doubleobj: 0x640
+  __AUTH_CONST.__objc_doubleobj: 0x650
   __AUTH_CONST.__objc_intobj: 0x1440
   __AUTH_CONST.__objc_dictobj: 0x1ef0
-  __AUTH_CONST.__objc_arrayobj: 0xd38
+  __AUTH_CONST.__objc_arrayobj: 0xd50
   __AUTH_CONST.__auth_got: 0xb80
   __AUTH.__objc_data: 0x9d8
-  __DATA.__objc_ivar: 0xda8
+  __DATA.__objc_ivar: 0xdb0
   __DATA.__data: 0x3a0
   __DATA.__bss: 0xe60
   __DATA.__common: 0x74

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5326
-  Symbols:   10703
-  CStrings:  5514
+  Functions: 5330
+  Symbols:   10715
+  CStrings:  5518
 
Symbols:
+ +[PLUrsaUtilities diagnosticExtensionIDsForProcess:]
+ -[PLSleepWakeAgent kaIDMax]
+ -[PLSleepWakeAgent kaIDMin]
+ -[PLSleepWakeAgent setKaIDMax:]
+ -[PLSleepWakeAgent setKaIDMin:]
+ OBJC_IVAR_$_PLSleepWakeAgent._kaIDMax
+ OBJC_IVAR_$_PLSleepWakeAgent._kaIDMin
+ ___52+[PLUrsaUtilities diagnosticExtensionIDsForProcess:]_block_invoke
+ _objc_msgSend$diagnosticExtensionIDsForProcess:
+ _objc_msgSend$kaIDMax
+ _objc_msgSend$kaIDMin
+ _objc_msgSend$lowercaseString
+ _objc_msgSend$setKaIDMax:
+ _objc_msgSend$setKaIDMin:
+ _objc_msgSend$whitespaceCharacterSet
+ diagnosticExtensionIDsForProcess:.mapping
+ diagnosticExtensionIDsForProcess:.onceToken
- +[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]
- ___65+[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]_block_invoke
- _objc_msgSend$shouldCollectCPLDiagnosticExtensionForProcess:
- shouldCollectCPLDiagnosticExtensionForProcess:.cplDiagnosticExtensionProcesses
- shouldCollectCPLDiagnosticExtensionForProcess:.onceToken
CStrings:
+ "Kernel assertions entry: kaID=%llu, duration=%f, count=%zu"
+ "PLUrsaUtilities: requesting diagnostic extensions %{public}@ for %{public}@"
+ "com.apple.DiagnosticExtensions.IMDiagnosticExtension"
+ "getSignpostMetricsWithStartDate returned launchDurations=%lu extendedLaunchDurations=%lu launchesTimeSeries=%lu bundleIDs(launchDurations)=%@"
+ "imagent"
+ "imdpersistence.imdpersistenceagent"
+ "imdpersistenceagent"
- ",%@"
- "Kernel assertions entry: paID=%llu, duration=%f, count=%zu"
- "PLUrsaUtilities: requesting CPL diagnostic extension for %{public}@"
```
