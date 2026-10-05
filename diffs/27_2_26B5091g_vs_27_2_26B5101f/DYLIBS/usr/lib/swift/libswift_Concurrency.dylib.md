## libswift_Concurrency.dylib

> `/usr/lib/swift/libswift_Concurrency.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-6.4.0.34.1
-  __TEXT.__text: 0x6d1ac
+6.4.2.1.7
+  __TEXT.__text: 0x6d17c
   __TEXT.__init_offsets: 0xc
   __TEXT.__const: 0x30aa
   __TEXT.__cstring: 0x23b6

   __DATA.__data: 0xf0
   __DATA.__bss: 0x4140
   __DATA.__common: 0x88
-  __DATA_DIRTY.__data: 0x470
+  __DATA_DIRTY.__data: 0x468
   __DATA_DIRTY.__bss: 0x1c00
   __DATA_DIRTY.__common: 0x69
   - /usr/lib/libSystem.B.dylib

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/system/libdispatch.dylib
-  Functions: 3079
-  Symbols:   5858
+  Functions: 3078
+  Symbols:   5856
   CStrings:  224
 
Symbols:
- _ZL19dispatchEnqueueFunc
- __ZL29initializeDispatchEnqueueFuncP16dispatch_queue_sPv11qos_class_t
Functions:
~ _swift_dispatchEnqueueGlobal : 168 -> 160
~ _swift_dispatchEnqueueMain : 32 -> 24
~ _swift_task_enqueueOnDispatchQueue : 32 -> 24
- _$ss23AsyncCompactMapSequenceVMa
CStrings:
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
- "Initialized count set to greater than specified capacity."
```
