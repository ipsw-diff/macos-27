## libSystemDetermination.dylib

> `/System/Library/Frameworks/CoreTelephony.framework/Support/libSystemDetermination.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`

```diff

 13487.1.0.0.0
-  __TEXT.__text: 0x7004c
+  __TEXT.__text: 0x6f77c
   __TEXT.__const: 0x3e09
-  __TEXT.__gcc_except_tab: 0x59d8
+  __TEXT.__gcc_except_tab: 0x59cc
   __TEXT.__cstring: 0x2de8
-  __TEXT.__oslogstring: 0xa16d
+  __TEXT.__oslogstring: 0x9cf9
   __TEXT.__unwind_info: 0x2430
-  __TEXT.__auth_stubs: 0x1430
+  __TEXT.__auth_stubs: 0x1410
   __DATA_CONST.__const: 0xdf8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10

   __AUTH_CONST.__const: 0x4a10
   __AUTH_CONST.__cfstring: 0x940
   __AUTH_CONST.__weak_auth_got: 0x18
-  __AUTH_CONST.__auth_got: 0xa08
+  __AUTH_CONST.__auth_got: 0x9f8
   __DATA_DIRTY.__data: 0x8
   __DATA_DIRTY.__bss: 0x60
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1794
-  Symbols:   2941
-  CStrings:  1459
+  Symbols:   2939
+  CStrings:  1437
 
Symbols:
- __Z8asString18RegistrationStatus
- __os_log_debug_impl
Functions:
~ __ZN2sd10DCNManager11scheduleDCNERKNSt3__112basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEE : 384 -> 320
~ __ZN26SystemDeterminationManager23submitRcsDurationMetricERK13PersonalityID : 2992 -> 2932
~ __ZN26SystemDeterminationManager50checkBasebandAssertionIfInWiFiCallingOnlyMode_syncERKNSt3__110shared_ptrIN2sd27IMSSubscriberModelInterfaceEEE : 792 -> 636
~ __ZZN26SystemDeterminationManager32handleRegisteredNetworkInfo_syncEN10subscriber7SimSlotERKNSt3__16vectorI27RegisteredNetworkInfoChangeNS2_9allocatorIS4_EEEERK21RegisteredNetworkInfoENK3$_0clINS2_10shared_ptrIN2sd32IMSSubscriberControllerInterfaceEEEEEDaT_ : 1344 -> 1200
~ __ZN26SystemDeterminationManager26handleCountryOfOriginationERKNSt3__110shared_ptrIN2sd32IMSSubscriberControllerInterfaceEEENS0_12basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE : 1608 -> 1516
~ __ZN26SystemDeterminationManager26handleIsRoamingUpdate_syncEN10subscriber7SimSlotE13RoamingResult : 672 -> 588
~ __ZN26SystemDeterminationManager32handleDomesticRoamingUpdate_syncEN10subscriber7SimSlotEb : 320 -> 264
~ __ZNSt3__110__function6__funcIZZN26SystemDeterminationManager15subscribeToPushERK13PersonalityIDRKNS_6vectorIhNS_9allocatorIhEEEERKNS_12basic_stringIcNS_11char_traitsIcEENS7_IcEEEENS_8functionIFvSI_xEEEENK3$_0clEvEUlSI_xE_SK_EclESI_Ox : 668 -> 400
~ __ZNSt3__110__function6__funcIZZN26SystemDeterminationManager26initPushUrlCheckTimer_syncEvENK3$_0clEvEUlRKNS_12basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEEExE_FvSB_xEEclESB_Ox : 556 -> 288
~ __ZN2sd27IMSSubscriberControllerBase23handleImsPdpActive_syncEb15DataContextType : 1456 -> 1328
~ __ZNK2sd23IMSSubscriberController41sendEmergencyAccessNetworkInfoUpdate_syncEv : 828 -> 764
~ __ZNK2sd23IMSSubscriberController36isRequirementMetForCellularFootprintEv : 596 -> 424
~ __ZN2sd18IMSSubscriberModel10setImsPrefE15DataContextTypePKN5caulk10option_setINS_14ImsServiceTypeEjEE : 1072 -> 1016
~ __ZN2sd18IMSSubscriberModel15enableTelephonyEb : 428 -> 332
~ __ZN2sd18IMSSubscriberModel23setRCSPcscfPropertyListENSt3__16vectorINS1_4pairINS1_12basic_stringIcNS1_11char_traitsIcEENS1_9allocatorIcEEEENS_6UEInfo16RCSPcscfPropertyEEENS7_ISC_EEEE : 736 -> 512
~ __ZN2sd18IMSSubscriberModel18updateRoamingStateE13RoamingResult : 332 -> 252
~ __ZNK2sd18IMSSubscriberModel26getIsCellularFootprintSeenEv : 188 -> 100
~ __ZN2sd18IMSSubscriberModel26setIsCellularFootprintSeenEb : 196 -> 104
~ __ZN2sd18IMSSubscriberModel14updateIsimInfoEv : 1640 -> 1576
CStrings:
- "Cellular footprint is not required for VoWiFi, ok to bring up IMS PDN"
- "Current DataContext is: %s. Checking CB key is not needed"
- "DCN already scheduled"
- "DomesticRoamingUpdate: roaming state %{bool}d"
- "EmergencyAccessNetworkInfoUpdate: Not in emergency call. Don't send emergency access network info update"
- "ISIM info didn't change"
- "ImsPdpActive: Lazuli mode. Country Of Origination not required"
- "ImsPdpActive: Not in iWLAN mode. Country Of Origination not required"
- "Not submitting RCSServiceDuration metric for zero duration"
- "Received PushURL: %{public}s"
- "Returning isCellularFootprintSeen as %{bool}d"
- "Roaming result remains as %s"
- "RoamingUpdate: Ignore undetermined roaming state %s"
- "Setting isCellularFootprintSeen to %{bool}d"
- "Skipping fLastRegisteredNetworkInfo update: no valid cell info (RAT=%s DataMode=%s regStatus=%s)"
- "Stored PushURL: %{public}s"
- "Telephony was NOT %s successfully"
- "Updating RCSPcscfPropertyList: \n"
- "WiFiCalling-only mode: true. Baseband booted assertion required. iSimInfoReady: %{bool}d, deviceInfoReady: %{bool}d. BB booted assertion held: %{bool}d"
- "addr = %s"
- "fInCallImsPref is inactive!"
- "handleCountryOfOrigination: mcc INT is: %u"
```
