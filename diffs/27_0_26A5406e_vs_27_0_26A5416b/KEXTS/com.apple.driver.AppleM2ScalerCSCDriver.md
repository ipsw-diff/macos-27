## com.apple.driver.AppleM2ScalerCSCDriver

> `com.apple.driver.AppleM2ScalerCSCDriver`

```diff

-200.62.2.0.0
-  __TEXT.__const: 0xc30b0
-  __TEXT.__cstring: 0x25868
-  __TEXT_EXEC.__text: 0x145efc
+200.62.3.0.0
+  __TEXT.__const: 0xc30c0
+  __TEXT.__cstring: 0x25869
+  __TEXT_EXEC.__text: 0x146004
   __TEXT_EXEC.__auth_stubs: 0xba0
   __DATA.__data: 0x22388
   __DATA.__common: 0x2710

   __DATA_CONST.__kalloc_type: 0x4e40
   __DATA_CONST.__kalloc_var: 0x13b0
   __DATA_CONST.__auth_got: 0x5d0
-  __DATA_CONST.__got: 0xa0
+  __DATA_CONST.__got: 0xa8
   __DATA_CONST.__auth_ptr: 0x88
   Functions: 10194
-  Symbols:   10251
+  Symbols:   10252
   CStrings:  3664
 
Symbols:
+ __ZZN26IOSurfaceAcceleratorClient29transformSurface_asynchronousEP20TransformSurfaceDataE20kalloc_type_view_627
+ __ZZN26IOSurfaceAcceleratorClient29transformSurface_asynchronousEP20TransformSurfaceDataE20kalloc_type_view_688
+ __ZZN26IOSurfaceAcceleratorClient40asynchronousUserClientCompletionCallbackEPvS0_E20kalloc_type_view_595
+ _kernel_task
- __ZZN26IOSurfaceAcceleratorClient29transformSurface_asynchronousEP20TransformSurfaceDataE20kalloc_type_view_623
- __ZZN26IOSurfaceAcceleratorClient29transformSurface_asynchronousEP20TransformSurfaceDataE20kalloc_type_view_684
- __ZZN26IOSurfaceAcceleratorClient40asynchronousUserClientCompletionCallbackEPvS0_E20kalloc_type_view_591
Functions:
~ __ZN16ApiodmaRegStream17addPacketSequenceERNS_11CommandRing7CommandEPK18M2ScalerCSCRequest : 192 -> 216
~ __ZN24BlockDescriptorRegStream25prepareBlockDescriptorSetEP18M2ScalerCSCRequest : 1104 -> 1152
~ __ZN26IOSurfaceAcceleratorClient11clientCloseEv : 256 -> 264
~ __ZN26IOSurfaceAcceleratorClient24user_set_client_propertyEP34IOSurfaceAcceleratorClientPropertyy : 160 -> 156
~ __ZN24AppleM2ScalerCSCHalMSR2325prepareClientForTransformEP26IOSurfaceAcceleratorClientb : 212 -> 236
~ __ZN29BlockDescriptorRegStreamMSR2323allocateTileArrayBufferEPK18M2ScalerCSCRequestm : 1056 -> 1104
~ __ZN29BlockDescriptorRegStreamMSR2321resizeNeighborChannelEP18M2ScalerCSCRequestmm : 1056 -> 1104
~ __ZN29BlockDescriptorRegStreamMSR2324configureNeighborChannelEP18M2ScalerCSCRequest : 1020 -> 1044
~ __ZN22AppleM2ScalerCSCDriver28addToRequestAge_gatedContextEP18M2ScalerCSCRequestb : 228 -> 264
~ __ZN22AppleM2ScalerCSCHalMSR38sendBlockEnablementDataToCoreAnalyticsEP18M2ScalerCSCRequest : 7180 -> 7188
CStrings:
+ "121111121222121211111111111221221121121212212222"
- "12111112122212121111111111122122112112112212222"
```
