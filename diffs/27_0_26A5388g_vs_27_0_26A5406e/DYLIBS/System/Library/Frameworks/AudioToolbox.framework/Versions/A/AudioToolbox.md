## AudioToolbox

> `/System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-1638.0.0.0.0
-  __TEXT.__text: 0x1737ec
-  __TEXT.__realtime: 0x1c0d8
+1638.104.1.0.0
+  __TEXT.__text: 0x173c54
+  __TEXT.__realtime: 0x1c0dc
   __TEXT.__objc_methlist: 0x161c
   __TEXT.__const: 0x4460
   __TEXT.__dlopen_cstrs: 0x3fc
-  __TEXT.__gcc_except_tab: 0x15a04
-  __TEXT.__cstring: 0xb39e
-  __TEXT.__oslogstring: 0x18ebd
+  __TEXT.__gcc_except_tab: 0x15a10
+  __TEXT.__cstring: 0xb3d2
+  __TEXT.__oslogstring: 0x18fae
   __TEXT.__unwind_info: 0x8218
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x3a8
   __DATA_CONST.__got: 0x570
   __AUTH_CONST.__const: 0xac28
-  __AUTH_CONST.__cfstring: 0x2ec0
+  __AUTH_CONST.__cfstring: 0x2ee0
   __AUTH_CONST.__objc_const: 0x2180
   __AUTH_CONST.__weak_auth_got: 0x38
   __AUTH_CONST.__objc_intobj: 0x5d0

   - /usr/lib/swift/libswiftos.dylib
   Functions: 6055
   Symbols:   10482
-  CStrings:  3687
+  CStrings:  3691
 
Functions:
~ __ZN16AudioQueueObject4StopEbbPNS_10StopStatusE : 996 -> 1380
~ __ZN20AudioQueueXPC_Server13EnqueueBufferEjNSt3__14spanIK26AQBufferCreateDestroyEventLm18446744073709551615EEEjjjNS1_IK28AudioStreamPacketDescriptionLm18446744073709551615EEEjjNS1_IK24AudioQueueParameterEventLm18446744073709551615EEE19XAudioTimeStampBaseb : 6116 -> 6248
~ __ZN20AudioQueueXPC_Server11SetPropertyEjjRKN4swix4dataE : 632 -> 1008
~ __ZN10AQMEDevice22RemoveAndReAddIOClientER14AQIONodeClient : 1308 -> 1320
~ __ZN10AQMEDevice16AddRunningClientER14AQIONodeClientbb : 612 -> 836
~ __ZN14MEMixerChannel12MixInputProcEPvPjPK14AudioTimeStampjjP15AudioBufferList : 1228 -> 1232
CStrings:
+ "%25s:%-5d %s: aq@%p: cinematic audio latency %.3f s, tail time %.3f s"
+ "%25s:%-5d AQMEDevice(%p)::AddRunningClient connected client has no IO connector: %s"
+ "%25s:%-5d Rejecting kAudioQueueProperty_ClientAuditToken from unentitled caller pid %d"
+ "com.apple.private.audio.client-audit-token-override"
```
