## SiriVOX

> `/System/Library/PrivateFrameworks/SiriVOX.framework/Versions/A/SiriVOX`

```diff

-3605.17.1.0.0
-  __TEXT.__text: 0x8a3b8
-  __TEXT.__objc_methlist: 0x8bc0
+3605.18.1.0.0
+  __TEXT.__text: 0x8abf4
+  __TEXT.__objc_methlist: 0x8bf8
   __TEXT.__const: 0x12c
   __TEXT.__constg_swiftt: 0x8c
   __TEXT.__swift5_typeref: 0x97
   __TEXT.__swift5_fieldmd: 0x38
   __TEXT.__swift5_types: 0x8
-  __TEXT.__cstring: 0x116cc
+  __TEXT.__cstring: 0x1175f
   __TEXT.__swift5_capture: 0x78
   __TEXT.__swift5_reflstr: 0x16
-  __TEXT.__gcc_except_tab: 0x5cc
-  __TEXT.__oslogstring: 0x8956
+  __TEXT.__gcc_except_tab: 0x5e8
+  __TEXT.__oslogstring: 0x8be9
   __TEXT.__dlopen_cstrs: 0xda
-  __TEXT.__unwind_info: 0x2cb0
+  __TEXT.__unwind_info: 0x2cc0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x48
   __DATA_CONST.__objc_protolist: 0x2d8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3d98
+  __DATA_CONST.__objc_selrefs: 0x3db8
   __DATA_CONST.__objc_protorefs: 0x48
   __DATA_CONST.__objc_superrefs: 0x4a8
   __DATA_CONST.__objc_arraydata: 0x980
   __DATA_CONST.__got: 0x778
   __AUTH_CONST.__const: 0x2cc8
   __AUTH_CONST.__cfstring: 0x5f60
-  __AUTH_CONST.__objc_const: 0x13878
+  __AUTH_CONST.__objc_const: 0x13900
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0xe58
   __AUTH_CONST.__objc_dictobj: 0x348
   __AUTH_CONST.__auth_got: 0x570
   __AUTH.__objc_data: 0x4150
   __AUTH.__data: 0x30
-  __DATA.__objc_ivar: 0xcc0
+  __DATA.__objc_ivar: 0xccc
   __DATA.__data: 0x2260
   __DATA.__bss: 0x248
   - /System/Library/Frameworks/AudioToolbox.framework/Versions/A/AudioToolbox

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3208
-  Symbols:   8395
-  CStrings:  2249
+  Functions: 3215
+  Symbols:   8408
+  CStrings:  2259
 
Symbols:
+ -[SVXHomePodUIBridgeClientDelegate didPauseTTSForCurrentUserTurn]
+ -[SVXHomePodUIBridgeClientDelegate setDidPauseTTSForCurrentUserTurn:]
+ -[SVXSession currentActivationContext]
+ -[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]
+ GCC_except_table2102
+ GCC_except_table2127
+ GCC_except_table2264
+ GCC_except_table2387
+ GCC_except_table2389
+ GCC_except_table2391
+ GCC_except_table2409
+ GCC_except_table2410
+ GCC_except_table2540
+ GCC_except_table2546
+ GCC_except_table2549
+ GCC_except_table2856
+ GCC_except_table3012
+ GCC_except_table3087
+ OBJC_IVAR_$_SVXHomePodUIBridgeClientDelegate._didPauseTTSForCurrentUserTurn
+ OBJC_IVAR_$_SVXSpeechSynthesizer._streamTaskTrackers
+ OBJC_IVAR_$_SVXSpeechSynthesizer._streamsWithFinishedPlayback
+ ___66-[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]_block_invoke
+ ___71-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceDetectedSpeechStart:]_block_invoke
+ ___82-[SVXHomePodUIBridgeClientDelegate uiBridgeServiceReceivedSpeechMitigationResult:]_block_invoke
+ _objc_msgSend$didPauseTTSForCurrentUserTurn
+ _objc_msgSend$setDidPauseTTSForCurrentUserTurn:
+ _objc_msgSend$speechSynthesizerDidFailStreamWithError:taskTracker:
- GCC_except_table2100
- GCC_except_table2123
- GCC_except_table2260
- GCC_except_table2382
- GCC_except_table2384
- GCC_except_table2386
- GCC_except_table2404
- GCC_except_table2405
- GCC_except_table2535
- GCC_except_table2539
- GCC_except_table2541
- GCC_except_table2849
- GCC_except_table3005
- GCC_except_table3080
CStrings:
+ "#Choreography - TTS was never paused for this turn, skipping resume"
+ "#Choreography - TTS was never paused, skipping legacy resume"
+ "%s Ignored because the stream does not belong to the current request. (_currentRequestUUID = %@, streamRequestUUID = %@)"
+ "%s Ignored failure of an unregistered stream. (streamId = %@, error = %@)"
+ "%s Response stream failed; ending the abandoned request. (_currentRequestUUID = %@, error = %@)"
+ "%s Stopping TTS for the active request with no current speaking context... (ttsSession = %@, activeTTSRequest = %@)"
+ "%s Stream errored after its audio finished; reporting success. (streamId = %@, error = %@)"
+ "%s error = %@, taskTracker = %@"
+ "-[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]"
+ "-[SVXSession speechSynthesizerDidFailStreamWithError:taskTracker:]_block_invoke"
```
