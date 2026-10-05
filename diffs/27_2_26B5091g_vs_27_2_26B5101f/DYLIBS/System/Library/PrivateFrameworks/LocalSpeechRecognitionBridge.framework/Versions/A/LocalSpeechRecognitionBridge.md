## LocalSpeechRecognitionBridge

> `/System/Library/PrivateFrameworks/LocalSpeechRecognitionBridge.framework/Versions/A/LocalSpeechRecognitionBridge`

```diff

-3605.25.2.0.0
-  __TEXT.__text: 0x1f31c
-  __TEXT.__objc_methlist: 0x2514
+3605.31.3.0.0
+  __TEXT.__text: 0x1f3e4
+  __TEXT.__objc_methlist: 0x2524
   __TEXT.__dlopen_cstrs: 0xb0
   __TEXT.__const: 0xb0
   __TEXT.__gcc_except_tab: 0x230
-  __TEXT.__cstring: 0x4b2d
+  __TEXT.__cstring: 0x4bc0
   __TEXT.__oslogstring: 0x2d3e
   __TEXT.__unwind_info: 0x960
   __TEXT.__objc_stubs: 0x0

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x248
+  __DATA_CONST.__const: 0x258
   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_protolist: 0xb8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1360
+  __DATA_CONST.__objc_selrefs: 0x1368
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0xc8
   __DATA_CONST.__objc_arraydata: 0x20
   __DATA_CONST.__got: 0x1e8
   __AUTH_CONST.__const: 0x810
-  __AUTH_CONST.__cfstring: 0x1ae0
-  __AUTH_CONST.__objc_const: 0x3d58
+  __AUTH_CONST.__cfstring: 0x1b80
+  __AUTH_CONST.__objc_const: 0x3d88
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x4b0
-  __DATA.__objc_ivar: 0x2cc
+  __DATA.__objc_ivar: 0x2d0
   __DATA.__data: 0x8b0
   __DATA_DIRTY.__objc_data: 0x410
   __DATA_DIRTY.__bss: 0x58

   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 776
-  Symbols:   1888
-  CStrings:  614
+  Functions: 777
+  Symbols:   1890
+  CStrings:  619
 
Symbols:
+ -[LBLocalSpeechRecognitionSettings initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:isLinwoodEnabled:applicationProcessIdentifier:isAudioSourceRemote:]
+ -[LBLocalSpeechRecognitionSettings isAudioSourceRemote]
+ GCC_except_table700
+ GCC_except_table735
+ GCC_except_table740
+ GCC_except_table745
+ OBJC_IVAR_$_LBLocalSpeechRecognitionSettings._isAudioSourceRemote
+ _objc_msgSend$initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:isLinwoodEnabled:applicationProcessIdentifier:isAudioSourceRemote:
- +[LBLocalSpeechRecognitionSettings companionSettingsWithRequestId:inputOrigin:]
- GCC_except_table699
- GCC_except_table734
- GCC_except_table739
- GCC_except_table744
- _objc_msgSend$initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:isLinwoodEnabled:
Functions:
- +[LBLocalSpeechRecognitionSettings companionSettingsWithRequestId:inputOrigin:]
~ -[LBLocalSpeechRecognitionSettings initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:isLinwoodEnabled:applicationProcessIdentifier:] : 1200 -> 260
+ -[LBLocalSpeechRecognitionSettings initWithRequestId:inputOrigin:speechRecognitionTaskName:speechRecognitionMode:location:jitGrammar:overrideModelPath:applicationName:detectUtterances:continuousListening:shouldHandleCapitalization:secureOfflineOnly:maximumRecognitionDuration:recognitionOverrides:shouldStoreAudioOnDevice:deliverEagerPackage:enableEmojiRecognition:enableAutoPunctuation:UILanguage:enableVoiceCommands:dictationUIInteractionId:sharedUserInfos:prefixText:postfixText:selectedText:powerContext:shouldStartAudioCapture:audioCaptureStartHostTime:audioRecordType:audioRecordDeviceId:shouldGenerateVoiceCommandCandidates:asrLocale:activeUserInfo:messagesContext:sessionId:isLinwoodEnabled:applicationProcessIdentifier:isAudioSourceRemote:]
~ -[LBLocalSpeechRecognitionSettings description] : 1092 -> 1124
~ -[LBLocalSpeechRecognitionSettings initWithCoder:] : 2336 -> 2396
~ -[LBLocalSpeechRecognitionSettings encodeWithCoder:] : 1308 -> 1356
+ -[LBLocalSpeechRecognitionSettings applicationProcessIdentifier]
CStrings:
+ "ContinuityEndReceived"
+ "LBLocalSpeechRecognitionSettings:::isAudioSourceRemote"
+ "NoTRPArrived"
+ "SpeechRecognitionDelayedStart"
+ "[isAudioSourceRemote = %@]"
```
