## com.apple.iokit.IOMobileGraphicsFamily-DCP

> `com.apple.iokit.IOMobileGraphicsFamily-DCP`

```diff

-700.50.104.0.0
-  __TEXT.__cstring: 0x609d
+700.50.108.1.0
+  __TEXT.__cstring: 0x632b
   __TEXT.__const: 0x32e8
-  __TEXT_EXEC.__text: 0x2ad0c
+  __TEXT_EXEC.__text: 0x2adf4
   __TEXT_EXEC.__auth_stubs: 0xf00
   __DATA.__data: 0xe8
   __DATA.__common: 0x2720

   __DATA_CONST.__auth_ptr: 0x8
   Functions: 801
   Symbols:   1442
-  CStrings:  500
+  CStrings:  510
 
Symbols:
+ __ZZ21notify_event_callbackP8OSObjectP20IOSurfaceSharedEventyyE21kalloc_type_view_7786
+ __ZZN21IOMobileFramebufferAP13spinner_setupEvE21kalloc_type_view_6465
+ __ZZN21IOMobileFramebufferAP13spinner_setupEvE21kalloc_type_view_6513
+ __ZZN21IOMobileFramebufferAP16spinner_teardownEvE21kalloc_type_view_6519
+ __ZZN21IOMobileFramebufferAP16spinner_teardownEvE21kalloc_type_view_6548
+ __ZZN21IOMobileFramebufferAP17shared_event_waitEPN5IOMFB2AP11SharedEventEP9IOSurfaceP18IOMFBSwapIORequestjjb27IOMFBSharedEventTraceSourceE21kalloc_type_view_7916
+ __ZZN21IOMobileFramebufferAP18flush_cached_stateEvE21kalloc_type_view_2519
+ __ZZN21IOMobileFramebufferAP18flush_cached_stateEvE21kalloc_type_view_2539
+ __ZZN21IOMobileFramebufferAP25shared_event_signal_abortEPN5IOMFB2AP11SharedEventEP9IOSurfacejjb27IOMFBSharedEventTraceSourceE21kalloc_type_view_8046
- __ZZ21notify_event_callbackP8OSObjectP20IOSurfaceSharedEventyyE21kalloc_type_view_7767
- __ZZN21IOMobileFramebufferAP13spinner_setupEvE21kalloc_type_view_6446
- __ZZN21IOMobileFramebufferAP13spinner_setupEvE21kalloc_type_view_6494
- __ZZN21IOMobileFramebufferAP16spinner_teardownEvE21kalloc_type_view_6500
- __ZZN21IOMobileFramebufferAP16spinner_teardownEvE21kalloc_type_view_6529
- __ZZN21IOMobileFramebufferAP17shared_event_waitEPN5IOMFB2AP11SharedEventEP9IOSurfaceP18IOMFBSwapIORequestjjb27IOMFBSharedEventTraceSourceE21kalloc_type_view_7897
- __ZZN21IOMobileFramebufferAP18flush_cached_stateEvE21kalloc_type_view_2500
- __ZZN21IOMobileFramebufferAP18flush_cached_stateEvE21kalloc_type_view_2520
- __ZZN21IOMobileFramebufferAP25shared_event_signal_abortEPN5IOMFB2AP11SharedEventEP9IOSurfacejjb27IOMFBSharedEventTraceSourceE21kalloc_type_view_8027
Functions:
~ __ZN21IOMobileFramebufferAP13map_block_bufEPNS_18map_block_buf_argsE26IOMFB_Parameter_Block_TypePKhmP4taskb : 700 -> 892
~ __ZN21IOMobileFramebufferAP9set_blockEP4taskjjPKyjPKhm : 532 -> 572
CStrings:
+ "map_block_buf: pbt=%u allocateBufferWithOptions failed user_size=%u\n"
+ "map_block_buf: pbt=%u block_size=%zu too small for addr_offs=%u size_offs=%u"
+ "map_block_buf: pbt=%u buf->map failed, buf_flags=0x%x\n"
+ "map_block_buf: pbt=%u buf->prepare failed ret=0x%x, buf_flags=0x%x\n"
+ "map_block_buf: pbt=%u set_kernel_power_assert failed ret=0x%x\n"
+ "map_block_buf: pbt=%u temp_buf->map failed\n"
+ "map_block_buf: pbt=%u temp_buf->prepare failed ret=0x%x"
+ "map_block_buf: pbt=%u withAddressRange failed user_addr=0x%llx, user_size=%u, buf_flags=0x%x\n"
+ "set_block: map_block_buf failed, pbt=%u, block=%p, block_size=%zu, ret=0x%x\n"
+ "set_block: pbt=%u rejected, DCP reset in progress\n"
```
