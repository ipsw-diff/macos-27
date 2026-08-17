## AVConference

> `/System/Library/PrivateFrameworks/AVConference.framework/Versions/A/AVConference`

```diff

-2235.62.1.0.0
-  __TEXT.__text: 0x7c8b9c
+2235.63.5.2.0
+  __TEXT.__text: 0x7c8cc0
   __TEXT.__realtime: 0xea4
-  __TEXT.__objc_methlist: 0x39ee0
+  __TEXT.__objc_methlist: 0x39ec8
   __TEXT.__const: 0x184e8
-  __TEXT.__cstring: 0x9b8d0
-  __TEXT.__oslogstring: 0x140dc4
+  __TEXT.__cstring: 0x9b912
+  __TEXT.__oslogstring: 0x140e62
   __TEXT.__gcc_except_tab: 0x3188
   __TEXT.__ustring: 0x2d4
   __TEXT.__dlopen_cstrs: 0x56
-  __TEXT.__unwind_info: 0x12588
+  __TEXT.__unwind_info: 0x12578
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x38
   __DATA_CONST.__objc_protolist: 0x510
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x184e0
+  __DATA_CONST.__objc_selrefs: 0x184d0
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x1248
   __DATA_CONST.__objc_arraydata: 0x2790
   __DATA_CONST.__got: 0x1b68
   __AUTH_CONST.__const: 0x8a58
   __AUTH_CONST.__cfstring: 0x290e0
-  __AUTH_CONST.__objc_const: 0x6c698
+  __AUTH_CONST.__objc_const: 0x6c678
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x4e00
   __AUTH_CONST.__objc_arrayobj: 0x1d58

   __AUTH_CONST.__auth_got: 0x2b78
   __AUTH.__objc_data: 0x140
   __AUTH.__data: 0xc8
-  __DATA.__objc_ivar: 0x767c
+  __DATA.__objc_ivar: 0x7678
   __DATA.__data: 0x7e50
   __DATA.__bss: 0x9b8
   __DATA.__common: 0x9

   - /usr/lib/libspindump.dylib
   - /usr/lib/libtailspin.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 35330
-  Symbols:   54520
-  CStrings:  33321
+  Functions: 35328
+  Symbols:   54515
+  CStrings:  33326
 
Symbols:
- -[VCAudioManager anyClientNeedsMicInputWithPreferredClient:]
- -[VCAudioManager updateMicAttributionForClient:shouldAdd:]
- OBJC_IVAR_$_VCAudioManager._hasActiveMicClients
- _objc_msgSend$anyClientNeedsMicInputWithPreferredClient:
- _objc_msgSend$updateMicAttributionForClient:shouldAdd:
Functions:
~ ___37-[VCAudioManager setMicrophoneMuted:]_block_invoke : 916 -> 984
~ -[VCAudioManager applyAudioSessionMute] : 1260 -> 1052
- -[VCAudioManager anyClientNeedsMicInputWithPreferredClient:]
~ -[VCAudioManager updateStateWithAudioIOClient:] : 3216 -> 3164
- -[VCAudioManager updateMicAttributionForClient:shouldAdd:]
~ ___50-[VCAudioStreamReceiveGroup setAudioChannelIndex:]_block_invoke : 28 -> 596
~ -[VCSession setupSpatialAudio] : 752 -> 1256
~ -[VCAudioManager updateDirectionWithClient:settings:isClientRegistered:] : 400 -> 280
~ -[VCSession setupSpatialAudio].cold.1 : 140 -> 168
CStrings:
+ " [%s] %s:%d %@(%p) Applying mute property for audioSessionId=%d, isMuted=%d"
+ " [%s] %s:%d %@(%p) audioChannelIndex changed %u -> %u for streamGroup=%s"
+ " [%s] %s:%d %@(%p) setMicrophoneMuted:%d"
+ " [%s] %s:%d Applying mute property for audioSessionId=%d, isMuted=%d"
+ " [%s] %s:%d audioChannelIndex changed %u -> %u for streamGroup=%s"
+ " [%s] %s:%d setMicrophoneMuted:%d"
+ "-[VCAudioStreamReceiveGroup setAudioChannelIndex:]_block_invoke"
+ "2235.63.5.2"
+ "VCSession [%s] %s:%d %@(%p) sessionMode=%ld hasExistingSpatialAudioPool=%d"
+ "VCSession [%s] %s:%d sessionMode=%ld hasExistingSpatialAudioPool=%d"
- " [%s] %s:%d %@(%p) Applying mute property for audioSessionId=%d, isMuted=%d (sessionMute=%@ _isMicrophoneMuted=%d hasActiveMicClients=%d)"
- " [%s] %s:%d %@(%p) setMicrophoneMuted=%d"
- " [%s] %s:%d Applying mute property for audioSessionId=%d, isMuted=%d (sessionMute=%@ _isMicrophoneMuted=%d hasActiveMicClients=%d)"
- " [%s] %s:%d setMicrophoneMuted=%d"
- "2235.62.1"
```
