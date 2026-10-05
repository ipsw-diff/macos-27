## com.apple.iokit.IO80211Family

> `com.apple.iokit.IO80211Family`

```diff

-1587.6.0.0.0
+1587.9.0.0.0
   __TEXT.__os_log: 0x9e58
   __TEXT.__const: 0x2bec0
-  __TEXT.__cstring: 0x99849
-  __TEXT_EXEC.__text: 0x2714e0
+  __TEXT.__cstring: 0x9959f
+  __TEXT_EXEC.__text: 0x27138c
   __TEXT_EXEC.__auth_stubs: 0x1420
   __DATA.__data: 0x5ec8
   __DATA.__common: 0x50c8
   __DATA.__bss: 0x14d8
   __DATA_CONST.__mod_init_func: 0x558
   __DATA_CONST.__mod_term_func: 0x558
-  __DATA_CONST.__const: 0x3a448
+  __DATA_CONST.__const: 0x3a488
   __DATA_CONST.__kalloc_type: 0x9ec0
   __DATA_CONST.__kalloc_var: 0xa00
   __DATA_CONST.__auth_got: 0xa10
   __DATA_CONST.__got: 0x150
   __DATA_CONST.__auth_ptr: 0x20
-  Functions: 13144
-  Symbols:   17168
-  CStrings:  14936
+  Functions: 13152
+  Symbols:   17177
+  CStrings:  14929
 
Symbols:
+ __FUNCTION__._ZN22IO80211AWDLPeerManager15setAirDropStateEb
+ __Z25getChanSwitchFromRawStatsP31apple80211_channel_switch_statsP30apple80211_channel_switch_data
+ __Z28apple80211getAGGRESSIVE_EDCAP23IO80211SkywalkInterfaceP26apple80211_aggressive_edca
+ __Z28apple80211setAGGRESSIVE_EDCAP23IO80211SkywalkInterfaceP26apple80211_aggressive_edca
+ __Z34getNanChanBoundaryStatFromRawStatsP31apple80211_channel_switch_statsP42apple80211_nan_channel_boundary_event_data
+ __ZN21IO80211ScanCacheStore14setAuthContextER18IO80211AuthContext
+ __ZN22IO80211AWDLPeerManager15setAirDropStateEb
+ __ZN22IO80211AWDLPeerManager17sendAggresiveEdcaEb
+ __ZN22IO80211AWDLPeerManager19aggressiveEdcaTimerEP18IO80211TimerSource
+ __ZZN14WCL11axManager15freeActionFrameEPvE20kalloc_type_view_866
+ __ZZN14WCL11axManager22send11axAsrActionFrameEhhPhjE21kalloc_type_view_1166
+ __ZZN14WCL11axManager24sendHsLpEmlsrActionFrameEbbjE21kalloc_type_view_1216
+ __ZZN21IO80211ScanCacheStore25initIO80211ScanCacheStoreER27IO80211ScanCacheStoreParamsE20kalloc_type_view_590
+ __ZZN21IO80211ScanCacheStore4freeEvE20kalloc_type_view_127
+ __ZZN22IO80211AWDLPeerManager10growAFRingEvE22kalloc_type_view_19449
+ __ZZN22IO80211AWDLPeerManager10growAFRingEvE22kalloc_type_view_19461
+ __ZZN22IO80211AWDLPeerManager12shrinkAFRingEvE22kalloc_type_view_19485
+ __ZZN22IO80211AWDLPeerManager12shrinkAFRingEvE22kalloc_type_view_19497
+ __ZZN22IO80211AWDLPeerManager13freeResourcesEvE21kalloc_type_view_2665
+ __ZZN22IO80211AWDLPeerManager17initWithInterfaceEP23IO80211VirtualInterfaceP10ether_addrE21kalloc_type_view_2132
+ __ZZN22IO80211AWDLPeerManager17initWithInterfaceEP23IO80211VirtualInterfaceP10ether_addrE21kalloc_type_view_2619
+ __ZZN22IO80211AWDLPeerManager22initAWDLStateTrackInfoEvE22kalloc_type_view_24999
+ __ZZN22IO80211AWDLPeerManager28freeAwdlPacketDescriptorPoolEvE22kalloc_type_view_40752
+ __ZZN22IO80211AWDLPeerManager28initAwdlPacketDescriptorPoolEjE22kalloc_type_view_40736
+ __ZZN22IO80211AWDLPeerManager33realTimeStatsGetSkywalkStatisticsEvE22kalloc_type_view_30630
+ __ZZN22IO80211AWDLPeerManager33realTimeStatsGetSkywalkStatisticsEvE22kalloc_type_view_30660
+ __ZZN22IO80211AWDLPeerManager4freeEvE21kalloc_type_view_2712
+ __ZZN22IO80211AWDLPeerManager4freeEvE21kalloc_type_view_2723
+ __ZZN27IO80211NANDataPathInitiator4freeEvE19kalloc_type_view_96
+ __ZZN27IO80211NANDataPathResponder4freeEvE20kalloc_type_view_103
- __ZZN14WCL11axManager15freeActionFrameEPvE20kalloc_type_view_858
- __ZZN14WCL11axManager22send11axAsrActionFrameEhhPhjE21kalloc_type_view_1158
- __ZZN14WCL11axManager24sendHsLpEmlsrActionFrameEbbjE21kalloc_type_view_1208
- __ZZN21IO80211ScanCacheStore25initIO80211ScanCacheStoreER27IO80211ScanCacheStoreParamsE20kalloc_type_view_581
- __ZZN21IO80211ScanCacheStore4freeEvE20kalloc_type_view_126
- __ZZN22IO80211AWDLPeerManager10growAFRingEvE22kalloc_type_view_19428
- __ZZN22IO80211AWDLPeerManager10growAFRingEvE22kalloc_type_view_19440
- __ZZN22IO80211AWDLPeerManager12shrinkAFRingEvE22kalloc_type_view_19464
- __ZZN22IO80211AWDLPeerManager12shrinkAFRingEvE22kalloc_type_view_19476
- __ZZN22IO80211AWDLPeerManager13freeResourcesEvE21kalloc_type_view_2653
- __ZZN22IO80211AWDLPeerManager17initWithInterfaceEP23IO80211VirtualInterfaceP10ether_addrE21kalloc_type_view_2129
- __ZZN22IO80211AWDLPeerManager17initWithInterfaceEP23IO80211VirtualInterfaceP10ether_addrE21kalloc_type_view_2607
- __ZZN22IO80211AWDLPeerManager22initAWDLStateTrackInfoEvE22kalloc_type_view_24978
- __ZZN22IO80211AWDLPeerManager28freeAwdlPacketDescriptorPoolEvE22kalloc_type_view_40736
- __ZZN22IO80211AWDLPeerManager28initAwdlPacketDescriptorPoolEjE22kalloc_type_view_40720
- __ZZN22IO80211AWDLPeerManager33realTimeStatsGetSkywalkStatisticsEvE22kalloc_type_view_30609
- __ZZN22IO80211AWDLPeerManager33realTimeStatsGetSkywalkStatisticsEvE22kalloc_type_view_30639
- __ZZN22IO80211AWDLPeerManager4freeEvE21kalloc_type_view_2699
- __ZZN22IO80211AWDLPeerManager4freeEvE21kalloc_type_view_2710
- __ZZN27IO80211NANDataPathInitiator4freeEvE19kalloc_type_view_94
- __ZZN27IO80211NANDataPathResponder4freeEvE19kalloc_type_view_97
CStrings:
+ "\"IO80211_kexts-1587.9\""
+ "%s::%s  Unable to instantiate _awdlAggressiveEdcaTimer \n"
+ "121122222222222"
+ "1222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222221111111111111111111111111111111111112"
+ "APPLE80211_IOC_AGGRESSIVE_EDCA"
+ "AirDrop aggressiveEdcaTimer timeout \n"
+ "IO80211_kexts-1587.9"
+ "Sep 29 2026 21:17:06"
+ "[ik] %s@%d:AirDrop state changed to <%d> \n"
+ "setAirDropState"
- "\"IO80211_kexts-1587.6\""
- "%s: ERROR: DP attribute length %u too short for publish id\n"
- "%s: ERROR: DP attribute length %u too short for responder NDI\n"
- "%s: ERROR: DP attribute length %u too short, minimum %u\n"
- "1211222222222"
- "122222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222221111111111111111111111111111111111112"
- "ERROR: %s::%s NAN attribute ID %d at offset %u with length %u exceeds dataLen %u\n"
- "ERROR: %s::%s Parsing SD attribute, SRF length %u exceeds remaining %u\n"
- "ERROR: %s::%s Parsing SD attribute, length %u too short for SRF header\n"
- "ERROR: %s::%s Parsing SD attribute, length %u too short for match filter length\n"
- "ERROR: %s::%s Parsing SD attribute, length %u too short for service info length\n"
- "ERROR: %s::%s Parsing SD attribute, length %u too short, minimum %u\n"
- "ERROR: %s::%s Parsing SD attribute, match filter length %u exceeds remaining %u\n"
- "ERROR: %s::%s Parsing SD attribute, service info length %u exceeds remaining %u\n"
- "ERROR: %s::%s Truncated NAN attribute header at offset %u, dataLen %u\n"
- "IO80211_kexts-1587.6"
- "Sep 13 2026 18:59:37"
```
