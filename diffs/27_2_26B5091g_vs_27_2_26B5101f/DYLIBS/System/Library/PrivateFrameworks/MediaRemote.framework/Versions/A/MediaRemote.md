## MediaRemote

> `/System/Library/PrivateFrameworks/MediaRemote.framework/Versions/A/MediaRemote`

```diff

-4026.200.15.0.0
-  __TEXT.__text: 0x30eeb0
-  __TEXT.__objc_methlist: 0x2b934
+4026.200.23.0.0
+  __TEXT.__text: 0x30f40c
+  __TEXT.__objc_methlist: 0x2b96c
   __TEXT.__const: 0x5d8
-  __TEXT.__cstring: 0x2c525
+  __TEXT.__cstring: 0x2c5a8
   __TEXT.__oslogstring: 0xd42d
-  __TEXT.__gcc_except_tab: 0x58c0
+  __TEXT.__gcc_except_tab: 0x5910
   __TEXT.__dlopen_cstrs: 0x40b
   __TEXT.__ustring: 0x7b8
-  __TEXT.__unwind_info: 0xe300
+  __TEXT.__unwind_info: 0xe2f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4b98
+  __DATA_CONST.__const: 0x4bd8
   __DATA_CONST.__objc_classlist: 0x11c0
   __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0x228
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf160
+  __DATA_CONST.__objc_selrefs: 0xf180
   __DATA_CONST.__objc_protorefs: 0x80
   __DATA_CONST.__objc_superrefs: 0xff0
   __DATA_CONST.__objc_arraydata: 0x260
   __DATA_CONST.__got: 0x1428
-  __AUTH_CONST.__const: 0xa440
-  __AUTH_CONST.__cfstring: 0x23e00
-  __AUTH_CONST.__objc_const: 0x466c0
-  __AUTH_CONST.__objc_intobj: 0x4f8
+  __AUTH_CONST.__const: 0xa460
+  __AUTH_CONST.__cfstring: 0x23f00
+  __AUTH_CONST.__objc_const: 0x46768
+  __AUTH_CONST.__objc_intobj: 0x510
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0xa90
   __AUTH.__objc_data: 0x5d20
-  __DATA.__objc_ivar: 0x32f4
+  __DATA.__objc_ivar: 0x3300
   __DATA.__data: 0x1a08
   __DATA.__bss: 0x8a8
   __DATA.__common: 0x8

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 20610
-  Symbols:   35178
-  CStrings:  6512
+  Functions: 20615
+  Symbols:   35188
+  CStrings:  6520
 
Symbols:
+ -[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]
+ -[MRGroupComposition setSpeakerGroupCount:]
+ -[MRGroupComposition setTvAndSpeakerCount:]
+ -[MRGroupComposition speakerGroupCount]
+ -[MRGroupComposition tvAndSpeakerCount]
+ -[_MRCommandOptionsProtobuf hasRequestDetails]
+ -[_MRCommandOptionsProtobuf requestDetails]
+ -[_MRCommandOptionsProtobuf setRequestDetails:]
+ OBJC_IVAR_$_MRGroupComposition._speakerGroupCount
+ OBJC_IVAR_$_MRGroupComposition._tvAndSpeakerCount
+ OBJC_IVAR_$__MRCommandOptionsProtobuf._requestDetails
+ __72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_2
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_3
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_4
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_5
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_6
+ ___72-[MRAVRoutingDiscoverySessionWrapper _onNotifyQueue_reevaluateAndNotify]_block_invoke_7
+ ___75-[MRActiveRoutesObserver _handleActiveSystemEndpointDidRemoveOutputDevice:]_block_invoke_3
+ ___block_descriptor_176_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r160r168r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24l
+ ___copy_helper_block_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r160r168r
+ ___destroy_helper_block_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r160r168r
+ _objc_msgSend$_onNotifyQueue_reevaluateAndNotify
+ _objc_msgSend$setRequestDetails:
+ _objc_msgSend$setSpeakerGroupCount:
+ _objc_msgSend$setTvAndSpeakerCount:
+ _objc_msgSend$speakerGroupCount
+ _objc_msgSend$tvAndSpeakerCount
- -[MRAVRoutingDiscoverySessionWrapper _currentVisibleEndpointsForSession:]
- -[MRAVRoutingDiscoverySessionWrapper _currentVisibleOutputDevicesForSession:]
- -[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]
- -[MRAVRoutingDiscoverySessionWrapper _shouldNotify]
- __58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_2
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_3
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_4
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_5
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_6
- ___58-[MRAVRoutingDiscoverySessionWrapper _reevaluateAndNotify]_block_invoke_7
- ___block_descriptor_160_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r_e45_v32?0"MRAVOutputDevice"8I16I20"NSString"24l
- ___copy_helper_block_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r
- ___destroy_helper_block_e8_32r40r48r56r64r72r80r88r96r104r112r120r128r136r144r152r
- _objc_msgSend$_currentVisibleEndpointsForSession:
- _objc_msgSend$_currentVisibleOutputDevicesForSession:
- _objc_msgSend$_reevaluateAndNotify
- _objc_msgSend$_shouldNotify
CStrings:
+ "GracePeriod"
+ "OA"
+ "SpeakerGroup"
+ "TVAndSpeaker"
+ "hifispeaker.2"
+ "requestDetails"
+ "speakerGroup: %lu;"
+ "tv.and.hifispeaker.fill"
+ "tvAndSpeaker: %lu;"
- "O"
```
