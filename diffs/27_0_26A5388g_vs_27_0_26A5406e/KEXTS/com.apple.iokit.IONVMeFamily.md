## com.apple.iokit.IONVMeFamily

> `com.apple.iokit.IONVMeFamily`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__got`

```diff

-877.0.6.0.0
+877.0.7.0.0
   __TEXT.__cstring: 0x109cd
   __TEXT.__const: 0x740
-  __TEXT_EXEC.__text: 0x5e6ac
-  __TEXT_EXEC.__auth_stubs: 0xe00
+  __TEXT_EXEC.__text: 0x5e6ec
+  __TEXT_EXEC.__auth_stubs: 0xe10
   __DATA.__data: 0x46c
   __DATA.__common: 0x578
   __DATA.__bss: 0x10

   __DATA_CONST.__const: 0x156e0
   __DATA_CONST.__kalloc_type: 0x840
   __DATA_CONST.__kalloc_var: 0x690
-  __DATA_CONST.__auth_got: 0x700
+  __DATA_CONST.__auth_got: 0x708
   __DATA_CONST.__got: 0x188
-  Functions: 3597
-  Symbols:   3277
+  Functions: 3598
+  Symbols:   3279
   CStrings:  1763
 
Symbols:
+ __ZN16IONVMeController27__DISK_IS_ASLEEP_DEADLINE__Ey
+ __ZZN16IONVMeController16ReleaseResourcesEvE21kalloc_type_view_1810
+ __ZZN16IONVMeController17AllocateResourcesEvE21kalloc_type_view_1712
+ __ZZN16IONVMeController17AllocateResourcesEvE21kalloc_type_view_1777
+ __ZZN16IONVMeController22CreateCompletionQueuesEvE21kalloc_type_view_3729
+ __ZZN16IONVMeController22CreateCompletionQueuesEvE21kalloc_type_view_3755
+ __ZZN16IONVMeController22CreateSubmissionQueuesEvE21kalloc_type_view_3439
+ __ZZN16IONVMeController22CreateSubmissionQueuesEvE21kalloc_type_view_3464
+ __ZZN16IONVMeController22DeleteCompletionQueuesEvE21kalloc_type_view_3784
+ __ZZN16IONVMeController22DeleteSubmissionQueuesEvE21kalloc_type_view_3493
+ _lck_mtx_sleep_deadline
- __ZZN16IONVMeController16ReleaseResourcesEvE21kalloc_type_view_1789
- __ZZN16IONVMeController17AllocateResourcesEvE21kalloc_type_view_1691
- __ZZN16IONVMeController17AllocateResourcesEvE21kalloc_type_view_1756
- __ZZN16IONVMeController22CreateCompletionQueuesEvE21kalloc_type_view_3708
- __ZZN16IONVMeController22CreateCompletionQueuesEvE21kalloc_type_view_3734
- __ZZN16IONVMeController22CreateSubmissionQueuesEvE21kalloc_type_view_3418
- __ZZN16IONVMeController22CreateSubmissionQueuesEvE21kalloc_type_view_3443
- __ZZN16IONVMeController22DeleteCompletionQueuesEvE21kalloc_type_view_3763
- __ZZN16IONVMeController22DeleteSubmissionQueuesEvE21kalloc_type_view_3472
Functions:
+ __ZN16IONVMeController27__DISK_IS_ASLEEP_DEADLINE__Ey
~ __ZN16IONVMeController8PolledIOEhP18IOMemoryDescriptorjyy18IOPolledCompletionjPKhm : 2028 -> 2024
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/AppleNVMeBuffer.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/AppleNVMeController.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/AppleNVMeRequest.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/AppleNVMeRequestPool.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/AppleNVMeRequestPoolTagReserve.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/AppleNVMeRequestTimer.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/AppleNVMeSMARTUserClient.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/AppleNVMeUserClient.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/AppleNVMeWorkLoop.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/IONVMeBlockStorageDevice.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/IONVMeController.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Common/IONVMeControllerPolledAdapter.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleANS2CGNVMeController.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleANS2CGv2Controller.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleANS2DARTNVMeController.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleANS2NVMeController.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleANS3CGv2Controller.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleANS3NVMeController.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleEmbeddedNVMeController.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleEmbeddedNVMeDiagnostics.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleEmbeddedNVMeNVRAM.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleEmbeddedNVMeTemperatureSensor.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleNVMeEAN.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleNVMeEANUC.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleNVMeFWNamespaceDevice.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleNVMeFWNamespaceUC.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleNVMeNamespaceDevice.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleNVMeNamespaceUC.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/AppleNVMeUpdateUC.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/IOEmbeddedNVMeBlockDevice.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/IONVMeEffaceableDevice.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/IONVMeLifeboatBlockDevice.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.24s99i/Sources/IONVMeFamily/Embedded/NVMeSEPNotifier.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/AppleNVMeBuffer.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/AppleNVMeController.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/AppleNVMeRequest.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/AppleNVMeRequestPool.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/AppleNVMeRequestPoolTagReserve.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/AppleNVMeRequestTimer.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/AppleNVMeSMARTUserClient.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/AppleNVMeUserClient.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/AppleNVMeWorkLoop.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/IONVMeBlockStorageDevice.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/IONVMeController.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Common/IONVMeControllerPolledAdapter.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleANS2CGNVMeController.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleANS2CGv2Controller.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleANS2DARTNVMeController.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleANS2NVMeController.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleANS3CGv2Controller.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleANS3NVMeController.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleEmbeddedNVMeController.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleEmbeddedNVMeDiagnostics.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleEmbeddedNVMeNVRAM.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleEmbeddedNVMeTemperatureSensor.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleNVMeEAN.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleNVMeEANUC.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleNVMeFWNamespaceDevice.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleNVMeFWNamespaceUC.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleNVMeNamespaceDevice.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleNVMeNamespaceUC.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/AppleNVMeUpdateUC.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/IOEmbeddedNVMeBlockDevice.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/IONVMeEffaceableDevice.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/IONVMeLifeboatBlockDevice.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mGoG5J/Sources/IONVMeFamily/Embedded/NVMeSEPNotifier.cpp"
```
