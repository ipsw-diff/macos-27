## AirPlaySupport

> `/System/Library/PrivateFrameworks/AirPlaySupport.framework/Versions/A/AirPlaySupport`

```diff

-1005.8.1.0.0
-  __TEXT.__text: 0xc2ca8
+1005.12.1.0.0
+  __TEXT.__text: 0xc2b68
   __TEXT.__objc_methlist: 0x374
   __TEXT.__const: 0xf08
   __TEXT.__dlopen_cstrs: 0x158
   __TEXT.__gcc_except_tab: 0x368
-  __TEXT.__cstring: 0x322bb
+  __TEXT.__cstring: 0x320c4
   __TEXT.__oslogstring: 0x1cc
   __TEXT.__unwind_info: 0x2980
   __TEXT.__objc_stubs: 0x0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2616
-  Symbols:   5027
-  CStrings:  4315
+  Functions: 2617
+  Symbols:   5028
+  CStrings:  4294
 
Symbols:
+ GCC_except_table2538
+ _APSAudioHoseMetricCollectorSetSenderRTMetrics
+ _FigSignalErrorAtGM
- GCC_except_table2537
- _FigSignalErrorAt3
Functions:
~ _APSSharedRingBuffer_CreateWithBufferAndState : 820 -> 652
~ _APSSharedRingBuffer_Create : 1032 -> 980
~ _protocolDriverSenderTCP_Flush : 268 -> 244
~ _protocolDriverSenderTCP_FlushFromTime : 380 -> 356
~ _APSAPAPExtensionConvertLoudnessInfoDictLoudnessParametersToBBuf : 692 -> 536
~ _APSAudioFormatDescriptionCreateWithAudioFormatIndex : 816 -> 776
~ _APSAudioFormatDescriptionListCreate : 456 -> 420
~ _APSAudioHoseMetricCollectorCreate : 624 -> 628
~ _APSAudioHoseMetricCollectorDeregisterHose : 1420 -> 1436
+ _APSAudioHoseMetricCollectorSetSenderRTMetrics
~ __APSAudioHoseMetricCollectorFinalize : 200 -> 212
CStrings:
+ "%s signalled err=%d at <>:%d"
+ "APSAudioHoseMetricCollectorSetSenderRTMetrics"
- "%s%s%s signalled err=%d (%s) (%s) at %s:%d"
- "-108"
- "-6705"
- "-877"
- "-878"
- "-879"
- "-880"
- "APSAPAPExtensionLoudnessInfoUtils.c"
- "APSAudioFormatDescription.c"
- "APSAudioFormatDescriptionList.c"
- "APSSharedRingBuffer.c"
- "Could not allocate APSAudioFormatDescription"
- "Could not allocate APSAudioFormatDescriptionList"
- "Failed to create bufferMemObject"
- "Failed to create stateMemObject"
- "bufferMemory region maps to NULL"
- "bufferMemorySize is zero"
- "kCMBaseObjectError_AllocationFailed"
- "loudness key missing"
- "sample peak key missing"
- "stateMemObject maps to NULL"
- "stateMemoryLength < sizeof(RingState)"
- "true peak key missing"
```
