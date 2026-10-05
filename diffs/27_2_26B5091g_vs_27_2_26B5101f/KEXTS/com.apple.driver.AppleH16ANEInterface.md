## com.apple.driver.AppleH16ANEInterface

> `com.apple.driver.AppleH16ANEInterface`

```diff

-10.101.100.0.0
-  __TEXT.__cstring: 0x11e05
-  __TEXT.__os_log: 0x3df78
-  __TEXT.__const: 0x1240
-  __TEXT_EXEC.__text: 0x15574c
-  __TEXT_EXEC.__auth_stubs: 0x1270
+10.102.3.0.0
+  __TEXT.__cstring: 0x11eeb
+  __TEXT.__os_log: 0x3e1cb
+  __TEXT.__const: 0x1250
+  __TEXT_EXEC.__text: 0x156204
+  __TEXT_EXEC.__auth_stubs: 0x1280
   __DATA.__data: 0x54f4
   __DATA.__common: 0x7e0
   __DATA.__bss: 0x868
   __DATA_CONST.__mod_init_func: 0x300
   __DATA_CONST.__mod_term_func: 0x138
-  __DATA_CONST.__const: 0x18b18
+  __DATA_CONST.__const: 0x18b80
   __DATA_CONST.__kalloc_var: 0x8c00
   __DATA_CONST.__kalloc_type: 0x7040
-  __DATA_CONST.__auth_got: 0x938
+  __DATA_CONST.__auth_got: 0x940
   __DATA_CONST.__got: 0x148
   __DATA_CONST.__auth_ptr: 0x8
-  Functions: 5092
-  Symbols:   10854
-  CStrings:  5441
+  Functions: 5101
+  Symbols:   10871
+  CStrings:  5452
 
Symbols:
+ __ZN11ANEHWDevice22enableDPEPushTelemetryEv
+ __ZN11ANEHWDevice23disableDPEPushTelemetryEv
+ __ZN11ANEHWDevice31isFWSharedEventSignalingEnabledEv
+ __ZN18ANEDeviceInterface31isFWSharedEventSignalingEnabledEv
+ __ZN19ANEInferenceRequest23recomputeFencesAcquiredEv
+ __ZN19ANEInferenceRequest29establishExternalDependenciesEv
+ __ZN27ANEAGXSignalingSetupManager29agxArrivalNotificationHandlerEP9IOService
+ __ZN27ANEAGXSignalingSetupManagerD1Ev
+ __ZN27ANEAGXSignalingSetupManagerD2Ev
+ __ZN9IOService23addMatchingNotificationEPK8OSSymbolP12OSDictionaryiU13block_pointerFbPS_P10IONotifierE
+ __ZZN11ANEHWDevice24power_off_hardware_gatedEvE11_os_log_fmt_6
+ __ZZN11ANEHWDevice25takePowerAssertionPrivateEP24ANEHWDeviceClientContext21ANEHWDevicePowerLevelE11_os_log_fmt_1
+ __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_4983
+ __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_5060
+ __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_5063
+ __ZZN12ANEScheduler30completeRequestsWithStaleEpochE17aneHWBoardSubTypeE11_os_log_fmt_1
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2226
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2314
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2396
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2535
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_3887
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_4030
+ __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_4287
+ __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_599
+ __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_603
+ __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_609
+ __ZZN19ANEInferenceRequest25updateLowLatencySignalingEvE11_os_log_fmt_1
+ __ZZN27ANEAGXSignalingSetupManager29agxArrivalNotificationHandlerEP9IOServiceE11_os_log_fmt
+ __ZZN27ANEAGXSignalingSetupManager29agxArrivalNotificationHandlerEP9IOServiceE11_os_log_fmt_0
+ __ZZN27ANEAGXSignalingSetupManager29agxArrivalNotificationHandlerEP9IOServiceE11_os_log_fmt_1
+ __ZZN27ANEAGXSignalingSetupManager29agxArrivalNotificationHandlerEP9IOServiceE11_os_log_fmt_2
+ __ZZN27ANEAGXSignalingSetupManager29agxArrivalNotificationHandlerEP9IOServiceE11_os_log_fmt_3
+ __ZZN27ANEAGXSignalingSetupManagerdlEPvmE19kalloc_type_view_48
+ __ZZN27ANEAGXSignalingSetupManagernwEmE19kalloc_type_view_48
+ ____ZN11ANEHWDevice31isFWSharedEventSignalingEnabledEv_block_invoke
+ ____ZN27ANEAGXSignalingSetupManagerC2EP9IOServiceP31ANEFWToggleSharedEventInterfacej_block_invoke
- _OUTLINED_FUNCTION_8
- _OUTLINED_FUNCTION_9
- __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_4960
- __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_5037
- __ZZN11ANEHWDevice4stopEP9IOServiceE21kalloc_type_view_5040
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2198
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2286
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2368
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_2507
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_3859
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_4002
- __ZZN17ANEHWDeviceConfig22initializeANESoCConfigEPK16AppleARMIODeviceP11ANEHWDeviceE21kalloc_type_view_4259
- __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_598
- __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_602
- __ZZN19ANEInferenceRequest15removeRTCommandEvE20kalloc_type_view_608
- __ZZN27ANEAGXSignalingSetupManager13notifyClientsEbE11_os_log_fmt_0
- __ZZN27ANEAGXSignalingSetupManagerC1EP9IOServiceP31ANEFWToggleSharedEventInterfacejE11_os_log_fmt_2
- __ZZN27ANEAGXSignalingSetupManagerdlEPvmE19kalloc_type_view_47
- __ZZN27ANEAGXSignalingSetupManagernwEmE19kalloc_type_view_47
CStrings:
+ "%s: %s: ANE%u: AGX peer already latched, ignoring additional %s service\n"
+ "%s: %s: ANE%u: FW shared event signaling disabled, cleared FW-FW signaling for programHandle: 0x%llx transactionId: 0x%llx\n"
+ "%s: %s: ANE%u: Watching for peer AGX service %s\n"
+ "%s: %s: Leaving recoverable request uuid: 0x%llx on ANE%d - re-dispatched after power on\n"
+ "%s: %s: Powered MPM off via PS register before powering down\n"
+ "%s: %s: Timed out after waiting %u seconds for requests to complete on the ANE.\n"
+ "%s: %s: takeAneSysClockAssertion_gated result = 0x%x fAneSysClockAssertions=%d\n"
+ "2111112"
+ "B24@?0^{IOService=^^?i^{ExpansionData}^{OSDictionary}^{OSDictionary}^{ExpansionData}^{IOService}i^{IOService}[2I]QQ^{IOServicePM}B^vi^{IOInterruptSource}}8^{IONotifier=^^?i}16"
+ "[ERROR] %s: %s: ANE%u: Couldn't create matching dictionary for %s\n"
+ "[ERROR] %s: %s: ANE%u: Failed to install %s arrival notification\n"
+ "[ERROR] %s: %s: ANE%u: Failed to push AGX signaling state %d to firmware: 0x%x\n"
+ "[ERROR] %s: %s: Failed to power MPM off before powering down: 0x%x\n"
+ "agxArrivalNotificationHandler"
+ "power-off-exclave-mpm"
- "%s: %s: AGX peer EP service NOT FOUND\n"
- "%s: %s: ANE powered off, clearing MPM powered state so the Exclave re-arm re-enables it\n"
- "%s: %s: Timed out after waiting %u ms for requests to complete on the ANE.\n"
- "21112"
```
