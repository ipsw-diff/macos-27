## DeviceConfiguration

> `/System/Library/PrivateFrameworks/DeviceConfiguration.framework/Versions/A/DeviceConfiguration`

```diff

-39.40.2.0.0
-  __TEXT.__text: 0xd71fc
+39.40.3.0.0
+  __TEXT.__text: 0xdcf24
   __TEXT.__objc_methlist: 0x77c
-  __TEXT.__const: 0xc6f8
-  __TEXT.__cstring: 0x1bd8
-  __TEXT.__swift5_typeref: 0x2b2e
-  __TEXT.__swift5_capture: 0xba4
-  __TEXT.__constg_swiftt: 0x2070
-  __TEXT.__swift5_reflstr: 0x1288
-  __TEXT.__swift5_fieldmd: 0x1e18
-  __TEXT.__oslogstring: 0x4124
+  __TEXT.__const: 0xc838
+  __TEXT.__cstring: 0x1be8
+  __TEXT.__swift5_typeref: 0x2b82
+  __TEXT.__swift5_capture: 0xd04
+  __TEXT.__constg_swiftt: 0x20b8
+  __TEXT.__swift5_reflstr: 0x12c8
+  __TEXT.__swift5_fieldmd: 0x1e3c
+  __TEXT.__oslogstring: 0x41d4
   __TEXT.__swift5_builtin: 0xdc
   __TEXT.__swift5_assocty: 0x538
   __TEXT.__swift5_protos: 0x38
   __TEXT.__swift5_proto: 0x7c8
   __TEXT.__swift5_types: 0x26c
-  __TEXT.__swift_as_entry: 0x334
-  __TEXT.__swift_as_ret: 0x328
-  __TEXT.__swift_as_cont: 0x5d4
+  __TEXT.__swift_as_entry: 0x33c
+  __TEXT.__swift_as_ret: 0x330
+  __TEXT.__swift_as_cont: 0x5e8
   __TEXT.__swift5_acfuncs: 0x384
   __TEXT.__swift5_mpenum: 0x60
-  __TEXT.__unwind_info: 0x3ea0
-  __TEXT.__eh_frame: 0x91e8
+  __TEXT.__unwind_info: 0x3fb0
+  __TEXT.__eh_frame: 0x9588
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x88
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3d8
+  __DATA_CONST.__objc_selrefs: 0x3c8
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x6488
+  __AUTH_CONST.__const: 0x66f8
   __AUTH_CONST.__cfstring: 0xa0
-  __AUTH_CONST.__objc_const: 0x2fb0
-  __AUTH_CONST.__auth_got: 0xdd8
+  __AUTH_CONST.__objc_const: 0x2fd0
+  __AUTH_CONST.__auth_got: 0xe68
   __AUTH.__objc_data: 0xd0
   __AUTH.__data: 0x30
-  __DATA.__data: 0x10a8
+  __DATA.__data: 0x10d0
   __DATA.__bss: 0xa080
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0xc90
-  __DATA_DIRTY.__data: 0x2880
+  __DATA_DIRTY.__data: 0x28d0
   __DATA_DIRTY.__bss: 0x5080
   __DATA_DIRTY.__common: 0x200
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswiftDistributed.dylib
   - /usr/lib/swift/libswiftIOKit.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib
+  - /usr/lib/swift/libswiftSynchronization.dylib
   - /usr/lib/swift/libswiftSystem.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 3988
-  Symbols:   1390
-  CStrings:  444
+  Functions: 4048
+  Symbols:   1395
+  CStrings:  448
 
Symbols:
+ __swift_closure_destructor.23Tm
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
+ _swift_task_isCancelled
+ _swift_task_isCancelledWithFlags
+ _symbolic SaySSG6stores_t
+ _symbolic ______pIego_ s5ErrorP
+ _symbolic _____ySDySSSDySS_____GGG 15Synchronization5MutexVAARi_zrlE 19DeviceConfiguration15StoreDescriptorC
+ _symbolic _____y_____G s11_SetStorageC 19DeviceConfiguration15StoreIdentifierC
+ _symbolic _____y_____SayABGG s18_DictionaryStorageC 19DeviceConfiguration15StoreIdentifierC
- _OBJC_CLASS_$_NSLock
- __swift_closure_destructor.14Tm
- _objc_msgSend$lock
- _objc_msgSend$unlock
- _symbolic So6NSLockC
CStrings:
+ "Failed to restore state for store with ID %{public}@. Error: %{public}@"
+ "Found duplicate store IDs: %{public}s"
+ "Restoring state for stores %{public}s..."
+ "stores"
```
