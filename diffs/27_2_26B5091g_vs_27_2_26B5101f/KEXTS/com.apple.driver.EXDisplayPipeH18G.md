## com.apple.driver.EXDisplayPipeH18G

> `com.apple.driver.EXDisplayPipeH18G`

```diff

-9.2.7.0.0
+9.2.12.0.0
   __TEXT.__const: 0x50
-  __TEXT.__cstring: 0x29ea
-  __TEXT_EXEC.__text: 0x9c54
-  __TEXT_EXEC.__auth_stubs: 0x4b0
+  __TEXT.__cstring: 0x2cf7
+  __TEXT_EXEC.__text: 0xa280
+  __TEXT_EXEC.__auth_stubs: 0x4c0
   __DATA.__data: 0xc4
   __DATA.__common: 0x60
   __DATA.__bss: 0x10
   __DATA_CONST.__mod_init_func: 0x18
   __DATA_CONST.__mod_term_func: 0x10
-  __DATA_CONST.__const: 0x17b0
+  __DATA_CONST.__const: 0x1830
   __DATA_CONST.__kalloc_type: 0x80
-  __DATA_CONST.__auth_got: 0x258
+  __DATA_CONST.__auth_got: 0x260
   __DATA_CONST.__got: 0x38
-  Functions: 187
-  Symbols:   596
-  CStrings:  250
+  Functions: 193
+  Symbols:   606
+  CStrings:  265
 
Symbols:
+ __NSConcreteGlobalBlock
+ __ZN13EXDisplayPipe24setup_async_notificationEPKcPP22IOInterruptEventSourceP10IOWorkLoopU13block_pointerFvS3_iEPF10tb_error_tPK65exdisplaypipecompanioninterface_exdisplaypipecompanioninterface_sjE
+ __ZN13EXDisplayPipe37setup_power_state_async_notificationsEv
+ ____ZN13EXDisplayPipe37setup_power_state_async_notificationsEv_block_invoke
+ ____ZN13EXDisplayPipe37setup_power_state_async_notificationsEv_block_invoke_2
+ ___block_literal_global
+ __block_literal_global
+ _exclaves_indicator_system_state_change
+ _exdisplaypipecompanioninterface_exdisplaypipecompanioninterface_setuppowerdownasyncsignal
+ _exdisplaypipecompanioninterface_exdisplaypipecompanioninterface_setuppowerupasyncsignal
CStrings:
+ "12111112122212121222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222111221111111111111111111112111112"
+ "EXDisplayPipe: secure display power DOWN notification received (count %d)\n"
+ "EXDisplayPipe: secure display power DOWN, EIC pause returned 0x%x\n"
+ "EXDisplayPipe: secure display power UP notification received (count %d)\n"
+ "EXDisplayPipe: secure display power UP, EIC resume returned 0x%x\n"
+ "EXDisplayPipe::%s %s addEventSource failed with 0x%x\n"
+ "EXDisplayPipe::%s %s complete for ID %d \n"
+ "EXDisplayPipe::%s %s exclaveAsyncNotificationRegister failed with 0x%x\n"
+ "EXDisplayPipe::%s %s failed to allocate IOInterruptEventSource\n"
+ "EXDisplayPipe::%s %s tightbeam call failed with 0x%x\n"
+ "EXDisplayPipe::%s %s workloop is NULL\n"
+ "EXDisplayPipe::%s XNU notification IOWorkLoop creation failed\n"
+ "EXDisplayPipe::%s setup_power_state_async_notifications failed\n"
+ "power-down"
+ "power-up"
+ "setup_async_notification"
- "12111112122212121222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222111221111111111111111112111112"
```
