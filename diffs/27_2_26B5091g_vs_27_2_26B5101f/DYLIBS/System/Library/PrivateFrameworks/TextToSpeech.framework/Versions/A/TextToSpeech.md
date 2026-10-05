## TextToSpeech

> `/System/Library/PrivateFrameworks/TextToSpeech.framework/Versions/A/TextToSpeech`

```diff

-727.3.0.0.0
-  __TEXT.__text: 0x329488
+727.3.2.0.0
+  __TEXT.__text: 0x32b018
   __TEXT.__objc_methlist: 0x4550
-  __TEXT.__const: 0x3f331
+  __TEXT.__const: 0x3f391
   __TEXT.__dlopen_cstrs: 0x2af
-  __TEXT.__constg_swiftt: 0x806c
-  __TEXT.__swift5_typeref: 0x789a
-  __TEXT.__swift5_fieldmd: 0x61bc
-  __TEXT.__cstring: 0x8c81
-  __TEXT.__swift5_types: 0x7a0
-  __TEXT.__swift5_capture: 0x3194
-  __TEXT.__swift5_reflstr: 0x4be0
+  __TEXT.__constg_swiftt: 0x8208
+  __TEXT.__swift5_typeref: 0x7912
+  __TEXT.__swift5_fieldmd: 0x6250
+  __TEXT.__cstring: 0x8cd1
+  __TEXT.__swift5_types: 0x7a4
+  __TEXT.__swift5_capture: 0x31d0
+  __TEXT.__swift5_reflstr: 0x4cf0
   __TEXT.__swift5_assocty: 0x1600
   __TEXT.__swift5_proto: 0x1320
   __TEXT.__swift_as_entry: 0xc88
-  __TEXT.__swift_as_ret: 0xdac
-  __TEXT.__swift_as_cont: 0x1230
+  __TEXT.__swift_as_ret: 0xdb0
+  __TEXT.__swift_as_cont: 0x1234
   __TEXT.__swift5_builtin: 0x474
-  __TEXT.__oslogstring: 0x2e60
+  __TEXT.__oslogstring: 0x2fa0
   __TEXT.__swift5_protos: 0x5c
   __TEXT.__swift5_mpenum: 0x144
   __TEXT.__gcc_except_tab: 0x2ba8
   __TEXT.__ustring: 0x2c6
-  __TEXT.__unwind_info: 0xf0b8
-  __TEXT.__eh_frame: 0x170f0
+  __TEXT.__unwind_info: 0xf150
+  __TEXT.__eh_frame: 0x17148
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1330
+  __DATA_CONST.__const: 0x1340
   __DATA_CONST.__objc_classlist: 0x3d0
   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0xc8

   __DATA_CONST.__objc_superrefs: 0x108
   __DATA_CONST.__objc_arraydata: 0x1398
   __DATA_CONST.__got: 0xdb8
-  __AUTH_CONST.__const: 0x17e88
+  __AUTH_CONST.__const: 0x17f38
   __AUTH_CONST.__cfstring: 0x6340
-  __AUTH_CONST.__objc_const: 0xbba0
+  __AUTH_CONST.__objc_const: 0xbca0
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_arrayobj: 0xee8
   __AUTH_CONST.__objc_intobj: 0x48

   __AUTH_CONST.__objc_floatobj: 0x40
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__auth_got: 0x2968
-  __AUTH.__objc_data: 0x22b8
+  __AUTH.__objc_data: 0x2410
   __AUTH.__data: 0x2810
   __DATA.__objc_ivar: 0x428
-  __DATA.__data: 0x2fe8
-  __DATA.__bss: 0x1e7d0
+  __DATA.__data: 0x2ff8
+  __DATA.__bss: 0x1e800
   __DATA.__common: 0x228
   __DATA_DIRTY.__objc_data: 0x12b8
-  __DATA_DIRTY.__data: 0x39c0
+  __DATA_DIRTY.__data: 0x3a20
   __DATA_DIRTY.__bss: 0x89c0
   __DATA_DIRTY.__common: 0x2f0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 16066
+  Functions: 16109
   Symbols:   1356
-  CStrings:  1730
+  CStrings:  1733
 
CStrings:
+ "$ioCycleHeadroomMultiplier"
+ "$maxIOCycleHeadroom"
+ "(?:[0-9A-Fa-f]{1,4}:){7}[0-9A-Fa-f]{1,4}|(?:[0-9A-Fa-f]{1,4}:)+:(?:[0-9A-Fa-f]{1,4}:?)*[0-9A-Fa-f]{0,4}|::(?:[0-9A-Fa-f]{1,4}:?)+[0-9A-Fa-f]{0,4}"
+ "AudioQueue diag [%ld refills, %.*fHz]: dispatchLatency avg=%.*fms max=%.*fms, maxWork=%.*fms, minInFlight=%ld, underflows=%ld, deadlineMisses=%ld, genSkips=%ld, poolReuse=%ld alloc=%ld sizeMiss=%ld freeDepth=%ld, ioCycle=%.*fms bufDur=%.*fms buffersPerIOCycle=%.*f"
+ "AudioQueue missed refill deadline #%ld: emitted silence with %ld buffer(s) pending — refill did not stage within a buffer duration. maxDispatchLatency=%.*fms, maxWork=%.*fms, staged=%ld, ioCycle=%.*fms, buffersPerIOCycle=%.*f stagedTarget=%ld adaptiveFloor=%ld"
+ "AudioQueue underflow #%ld: nothing pending, emitted silence. maxDispatchLatency=%.*fms, maxWork=%.*fms, refills=%ld"
+ "Callback-thread enqueue failed: %d"
+ "TTSSettingsIoCycleHeadroomMultiplier"
+ "TTSSettingsMaxIOCycleHeadroom"
- "$seamFadeDuration"
- "(?:[0-9A-Fa-f]{1,4}:){2,7}[0-9A-Fa-f]{1,4}|(?:[0-9A-Fa-f]{1,4}:)+:(?:[0-9A-Fa-f]{1,4}:?)*[0-9A-Fa-f]{0,4}|::(?:[0-9A-Fa-f]{1,4}:?)+[0-9A-Fa-f]{0,4}"
- "AudioQueue diag [%ld refills, %.*fHz]: dispatchLatency avg=%.*fms max=%.*fms, maxWork=%.*fms, minInFlight=%ld, underflows=%ld, genSkips=%ld, poolReuse=%ld alloc=%ld sizeMiss=%ld freeDepth=%ld"
- "AudioQueue underflow #%ld: injecting silence. maxDispatchLatency=%.*fms, maxWork=%.*fms, minInFlight=%ld, sizeMisses=%ld, refills=%ld"
- "Interleaved mono to %u channels using Accelerate"
- "TTSSettingsSeamFadeDuration"
```
