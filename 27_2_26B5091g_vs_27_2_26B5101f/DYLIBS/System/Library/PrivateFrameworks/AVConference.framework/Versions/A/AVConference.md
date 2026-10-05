## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/Versions/A/AVConference`

```diff

-2260.11.1.0.0
-  __TEXT.__text: 0x7bff34
+2260.14.1.0.0
+  __TEXT.__text: 0x7c0aac
   __TEXT.__realtime: 0xea4
-  __TEXT.__objc_methlist: 0x39f30
+  __TEXT.__objc_methlist: 0x39f48
   __TEXT.__const: 0x184a8
-  __TEXT.__cstring: 0x9b6ec
-  __TEXT.__oslogstring: 0x142815
-  __TEXT.__gcc_except_tab: 0x3258
+  __TEXT.__cstring: 0x9b706
+  __TEXT.__oslogstring: 0x142c64
+  __TEXT.__gcc_except_tab: 0x326c
   __TEXT.__ustring: 0x2d4
   __TEXT.__dlopen_cstrs: 0x56
-  __TEXT.__unwind_info: 0x1b4e8
+  __TEXT.__unwind_info: 0x1b508
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_arraydata: 0x2790
   __DATA_CONST.__got: 0x1b00
   __AUTH_CONST.__const: 0x8a08
-  __AUTH_CONST.__cfstring: 0x29220
-  __AUTH_CONST.__objc_const: 0x6c768
+  __AUTH_CONST.__cfstring: 0x29260
+  __AUTH_CONST.__objc_const: 0x6c7d8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x4e00
   __AUTH_CONST.__objc_arrayobj: 0x1d58

   __AUTH_CONST.__auth_got: 0x2ba8
   __AUTH.__objc_data: 0x140
   __AUTH.__data: 0x8
-  __DATA.__objc_ivar: 0x76b4
+  __DATA.__objc_ivar: 0x76c0
   __DATA.__data: 0x1e20
   __DATA.__bss: 0xad8
   __DATA.__common: 0x9

   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 35338
-  Symbols:   54543
-  CStrings:  33380
+  Functions: 35346
+  Symbols:   54550
+  CStrings:  33391
 
Symbols:
+ -[VCVideoStreamSendGroupConfig enableSyncGroupReferenceTimestamp]
+ -[VCVideoStreamSendGroupConfig setEnableSyncGroupReferenceTimestamp:]
+ OBJC_IVAR_$_VCCoreAudio_AudioUnitMock._isImplicitPreferenceSession
+ OBJC_IVAR_$_VCVideoStreamSendGroup._enableSyncGroupReferenceTimestamp
+ OBJC_IVAR_$_VCVideoStreamSendGroupConfig._enableSyncGroupReferenceTimestamp
+ __44-[VCControlChannelMultiWay lastUsedMKIBytes]_block_invoke
+ ___44-[VCControlChannelMultiWay lastUsedMKIBytes]_block_invoke
+ ___block_descriptor_40_e8_32o_e232_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12l
- ___block_descriptor_40_e8_32o_e229_v20?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12l
CStrings:
+ " [%s] %s:%d %@(%p) Video frame is too old and modulated timestamp rolled backward – dropping frame. modulatedTimestamp=%u, frameTimeInSec=%f, rtpTimestampRate=%u"
+ " [%s] %s:%d Bad buffer length(%zu) for FaceTime audio media control info with header bitmap 0x%x, expecting %zu"
+ " [%s] %s:%d Bad buffer length(%zu) for FaceTime audio media control info, expecting %zu"
+ " [%s] %s:%d Not enough buffer for ECN CE count"
+ " [%s] %s:%d Not enough buffer for ECN ECT1 count"
+ " [%s] %s:%d Not enough buffer for bandwidth estimation"
+ " [%s] %s:%d Not enough buffer for video burst loss"
+ " [%s] %s:%d Video frame is too old and modulated timestamp rolled backward – dropping frame. modulatedTimestamp=%u, frameTimeInSec=%f, rtpTimestampRate=%u"
+ " [%s] %s:%d [FTDC] _dualCaptureSupported=%d, useVirtualCapture=%d"
+ " [%s] %s:%d configureWithBuffer failed with error %08X for control info=%p, dropping it"
+ "-[VCControlChannelMultiWay lastUsedMKIBytes]_block_invoke"
+ "2260.14.1"
+ "VideoPacketBuffer [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/AVConference/AVConference.subproj/Sources/Others/VideoPacketBuffer.c:%d: VideoPacketBuffer[%p] Reusing cached plaintext for re-assembled frame timestamp=%u frameSequenceNumber=%d isLate=%d"
+ "lcid"
+ "rcid"
+ "v20@?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}^IQ})}12"
- " [%s] %s:%d Bad buffer length(%zu) for FaceTime audio media control info, expecting %u"
- " [%s] %s:%d [FTDC] _dualCaptureSupported=%d"
- "-[VCControlChannelMultiWay lastUsedMKIBytes]"
- "2260.11.1"
- "v20@?0i8^{FigRemoteOperation=iiQ^{__CFString}(?={?=^{__CFDictionary}^{__CFDictionary}}{?=^v^{__IOSurface}^{__IOSurface}}{?=^{opaqueCMSampleBuffer}Q^{__CFArray}}{?=^{opaqueCMFormatDescription}}{?=q^{opaqueCMFormatDescription}})}12"
```
