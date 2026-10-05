## PowerlogLiteOperators

> `/System/Library/PrivateFrameworks/PowerlogLiteOperators.framework/Versions/A/PowerlogLiteOperators`

```diff

-3486.40.99.0.0
-  __TEXT.__text: 0x1f5c5c
-  __TEXT.__objc_methlist: 0xd9c4
+3486.40.113.0.0
+  __TEXT.__text: 0x1f60f8
+  __TEXT.__objc_methlist: 0xd9f4
   __TEXT.__const: 0x21b0
   __TEXT.__swift5_typeref: 0x4f9
   __TEXT.__constg_swiftt: 0x36c

   __TEXT.__swift5_types: 0x48
   __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_builtin: 0x28
-  __TEXT.__cstring: 0x38723
+  __TEXT.__cstring: 0x387b5
   __TEXT.__swift5_capture: 0xb8
   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift_as_entry: 0x24
   __TEXT.__swift_as_ret: 0x24
   __TEXT.__swift_as_cont: 0x44
-  __TEXT.__oslogstring: 0xcd78
+  __TEXT.__oslogstring: 0xcd55
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__gcc_except_tab: 0x1d9c
   __TEXT.__ustring: 0x12
-  __TEXT.__unwind_info: 0x45e8
+  __TEXT.__unwind_info: 0x45f0
   __TEXT.__eh_frame: 0xdb0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x8c70
+  __DATA_CONST.__objc_selrefs: 0x8ca0
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x398
-  __DATA_CONST.__objc_arraydata: 0x60b0
+  __DATA_CONST.__objc_arraydata: 0x6090
   __DATA_CONST.__got: 0xbe8
   __AUTH_CONST.__const: 0x33f8
-  __AUTH_CONST.__cfstring: 0x4d880
-  __AUTH_CONST.__objc_const: 0xfda8
+  __AUTH_CONST.__cfstring: 0x4d900
+  __AUTH_CONST.__objc_const: 0xfe08
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0x4f38
   __AUTH_CONST.__objc_dictobj: 0x2620
-  __AUTH_CONST.__objc_arrayobj: 0xfc0
-  __AUTH_CONST.__objc_doubleobj: 0xbf0
+  __AUTH_CONST.__objc_arrayobj: 0xfd8
+  __AUTH_CONST.__objc_doubleobj: 0xc00
   __AUTH_CONST.__auth_got: 0x1350
   __AUTH.__objc_data: 0x378
   __AUTH.__data: 0xcf8
-  __DATA.__objc_ivar: 0x48c
+  __DATA.__objc_ivar: 0x494
   __DATA.__data: 0x618
   __DATA.__common: 0x1e8
   __DATA.__bss: 0x24e0

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 6494
-  Symbols:   12623
-  CStrings:  13059
+  Functions: 6499
+  Symbols:   12636
+  CStrings:  13063
 
Symbols:
+ +[PLUrsaUtilities diagnosticExtensionIDsForProcess:]
+ -[PLSleepWakeAgent kaIDMax]
+ -[PLSleepWakeAgent kaIDMin]
+ -[PLSleepWakeAgent setKaIDMax:]
+ -[PLSleepWakeAgent setKaIDMin:]
+ GCC_except_table39
+ OBJC_IVAR_$_PLSleepWakeAgent._kaIDMax
+ OBJC_IVAR_$_PLSleepWakeAgent._kaIDMin
+ __41-[PLSMCMetricsAgent logPowerDeliveryKeys]_block_invoke
+ ___52+[PLUrsaUtilities diagnosticExtensionIDsForProcess:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48s_e25_v32?0"NSString"8Q16^B24l
+ _objc_msgSend$diagnosticExtensionIDsForProcess:
+ _objc_msgSend$kaIDMax
+ _objc_msgSend$kaIDMin
+ _objc_msgSend$lowercaseString
+ _objc_msgSend$setKaIDMax:
+ _objc_msgSend$setKaIDMin:
+ _objc_msgSend$whitespaceCharacterSet
- +[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]
- GCC_except_table38
- ___65+[PLUrsaUtilities shouldCollectCPLDiagnosticExtensionForProcess:]_block_invoke
- ___block_descriptor_49_e8_32s40s_e25_v32?0"NSString"8Q16^B24l
- _objc_msgSend$shouldCollectCPLDiagnosticExtensionForProcess:
CStrings:
+ "%@: rail is OFF, timestamp=%u, entry=%d"
+ "%@: reached end of buffer, timestamp=%u, entry=%d"
+ "Kernel assertions entry: kaID=%llu, duration=%f, count=%zu"
+ "Log Power Delivery Keys to CA, payload=%@"
+ "PLUrsaUtilities: requesting diagnostic extensions %{public}@ for %{public}@"
+ "com.apple.DiagnosticExtensions.IMDiagnosticExtension"
+ "com.apple.power.powerDeliveryKeys"
+ "imagent"
+ "imdpersistence.imdpersistenceagent"
+ "imdpersistenceagent"
+ "rail = %@, payload = %@"
- "%@: manually increment timestamp %u at entry %d"
- "%@: reached the end of buffer at entry %d"
- "%@: reached the end of buffer at entry %d due to timestamp jump %u"
- ",%@"
- "Kernel assertions entry: paID=%llu, duration=%f, count=%zu"
- "PLUrsaUtilities: requesting CPL diagnostic extension for %{public}@"
- "PMUMetricsStatic: rail = %@, payload = %@"
```
