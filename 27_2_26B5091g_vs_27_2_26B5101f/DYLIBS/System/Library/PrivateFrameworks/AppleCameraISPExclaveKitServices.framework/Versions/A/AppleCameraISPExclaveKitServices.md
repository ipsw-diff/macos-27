## AppleCameraISPExclaveKitServices

> `/System/Library/PrivateFrameworks/AppleCameraISPExclaveKitServices.framework/Versions/A/AppleCameraISPExclaveKitServices`

```diff

-20.105.2.0.0
-  __TEXT.__text: 0x316b4
-  __TEXT.__const: 0x2f2
-  __TEXT.__gcc_except_tab: 0x934
-  __TEXT.__oslogstring: 0x43c2
-  __TEXT.__cstring: 0x8c81
+20.107.1.0.0
+  __TEXT.__text: 0x31928
+  __TEXT.__const: 0x2e2
+  __TEXT.__gcc_except_tab: 0x91c
+  __TEXT.__oslogstring: 0x44b3
+  __TEXT.__cstring: 0x8c93
   __TEXT.__constg_swiftt: 0x48
   __TEXT.__swift5_typeref: 0x6
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x1290
+  __TEXT.__unwind_info: 0x1288
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __DATA_CONST.__const: 0x660

   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__auth_got: 0x440
   __AUTH.__data: 0x98
-  __DATA.__data: 0x118bb4
+  __DATA.__data: 0x118bbc
   __DATA.__common: 0x98
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 1183
+  Functions: 1185
   Symbols:   966
-  CStrings:  819
+  CStrings:  822
 
Symbols:
+ __Z40isNewSharedMemoryReplayBufferDumpSkipRawP21ISPExclaveKitDefaults
+ __Z40isNewSharedMemoryReplayBufferDumpSkipYuvP21ISPExclaveKitDefaults
+ __ZN28ISPExclaveKitFileServiceBase24_allocateLocalTempBufferEm
- GCC_except_table19
- GCC_except_table28
- _ZN28ISPExclaveKitFileLoadServiceC2Ebb
CStrings:
+ "%s:%d - [EK] CH: %d frameId: 0x%x bufferTypeIndex = %d dropped: copy out failed (err %d)\n"
+ "%s:%d - _isMemoryPortCreated is false for region: %s\n"
+ "%s:%d - creating shared memory region: %s failed with err: %d, region unavailable on this platform\n"
+ "%s:%d - exclaves_outbound_buffer_copyout failed with err: %d - region %s offset 0x%lx + size %ld %s mapped view of %zu bytes; destination buffer left unwritten\n"
+ "exceeds"
+ "is within"
- "%s:%d - _isMemoryPortCreated is false\n"
- "%s:%d - creating shared memory region: %s failed with err: %d\n"
- "%s:%d - exclaves_outbound_buffer_copyout failed with err: %d\n"
```
