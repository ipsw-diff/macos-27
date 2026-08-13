## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/Support/assistantd`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3600.68.44.0.0
-  __TEXT.__text: 0x5316c4
-  __TEXT.__auth_stubs: 0x31d0
-  __TEXT.__objc_stubs: 0x42360
-  __TEXT.__objc_methlist: 0x2175c
-  __TEXT.__cstring: 0x49b42
+3600.68.61.0.0
+  __TEXT.__text: 0x533548
+  __TEXT.__auth_stubs: 0x3210
+  __TEXT.__objc_stubs: 0x424c0
+  __TEXT.__objc_methlist: 0x21884
+  __TEXT.__cstring: 0x4a1c2
   __TEXT.__const: 0xa2ec0
   __TEXT.__dlopen_cstrs: 0x56f
-  __TEXT.__gcc_except_tab: 0x30a0
-  __TEXT.__oslogstring: 0x3e3e0
+  __TEXT.__gcc_except_tab: 0x30dc
+  __TEXT.__oslogstring: 0x3e8f6
   __TEXT.__objc_classname: 0x4dc9
-  __TEXT.__objc_methname: 0x5b084
-  __TEXT.__objc_methtype: 0xeb97
+  __TEXT.__objc_methname: 0x5b370
+  __TEXT.__objc_methtype: 0xebcd
   __TEXT.__ustring: 0x32
-  __TEXT.__unwind_info: 0x96b8
+  __TEXT.__unwind_info: 0x9710
   __TEXT.__eh_frame: 0x140
-  __DATA_CONST.__const: 0x231d0
-  __DATA_CONST.__cfstring: 0x11360
+  __DATA_CONST.__const: 0x231c0
+  __DATA_CONST.__cfstring: 0x113e0
   __DATA_CONST.__objc_classlist: 0xcb0
   __DATA_CONST.__objc_catlist: 0x630
   __DATA_CONST.__objc_protolist: 0x6a0

   __DATA_CONST.__objc_dictobj: 0x2f8
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_floatobj: 0x30
-  __DATA_CONST.__auth_got: 0x18f8
+  __DATA_CONST.__auth_got: 0x1918
   __DATA_CONST.__got: 0x39b0
   __DATA_CONST.__auth_ptr: 0x20
-  __DATA.__objc_const: 0x32000
-  __DATA.__objc_selrefs: 0x13d00
-  __DATA.__objc_ivar: 0x2470
+  __DATA.__objc_const: 0x320c8
+  __DATA.__objc_selrefs: 0x13da0
+  __DATA.__objc_ivar: 0x247c
   __DATA.__objc_data: 0x7ee0
   __DATA.__data: 0x5af8
-  __DATA.__bss: 0x9b8
+  __DATA.__bss: 0x9c8
   __DATA.__common: 0x1428
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/AVRouting.framework/Versions/A/AVRouting

   - /System/Library/PrivateFrameworks/CoreEmbeddedSpeechRecognition.framework/Versions/A/CoreEmbeddedSpeechRecognition
   - /System/Library/PrivateFrameworks/CoreKnowledge.framework/Versions/A/CoreKnowledge
   - /System/Library/PrivateFrameworks/CoreSpeech.framework/Versions/A/CoreSpeech
+  - /System/Library/PrivateFrameworks/CoreSpeechFoundation.framework/Versions/A/CoreSpeechFoundation
   - /System/Library/PrivateFrameworks/DialogEngine.framework/Versions/A/DialogEngine
   - /System/Library/PrivateFrameworks/FeatureStore.framework/Versions/A/FeatureStore
   - /System/Library/PrivateFrameworks/FeedbackLogger.framework/Versions/A/FeedbackLogger

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 13804
-  Symbols:   2753
-  CStrings:  25567
+  Functions: 13838
+  Symbols:   2757
+  CStrings:  25633
 
Symbols:
+ _ADShouldEmitUEIRequestLinkForRequestId
+ _AFCanSyncIFPVoices
+ _NSStringFromAFSiriRestrictionReasons
+ __os_crash
+ _objc_sync_enter
+ _objc_sync_exit
+ _snprintf
- _abort
- _dispatch_block_create
- _sandbox_free_error
CStrings:
+ "%s #IFToolbox Reinitializing Intelligence Toolbox Readiness delegate for locale: %{public}@"
+ "%s #SiriAvailability Synchronously updating capabilities for language code %@"
+ "%s #SiriAvailability recomputing: current locale changed"
+ "%s #hal Skipping context donation for type %{public}@: serialized context is nil"
+ "%s #hal Skipping context donation: nil type from metadata %@"
+ "%s #unredactedMeCard -cachedUnredactedMeCard invoked (meCard present: %d)"
+ "%s Asset manager is nil."
+ "%s Cannot re-initialize Intelligence Flow assets delegate, languageCode: '%{public}@' is invalid for locale creation."
+ "%s Cannot re-initialize Intelligence Flow assets delegate, languageCode: '%{public}@' is nil."
+ "%s Could not get AFHearablesExperienceManager shared instance to wire internal delegate"
+ "%s Dictation Sampling: Stopping adding audio samples after adding %ld bytes since the permit monitor requested an abort (e.g. background task expiration)."
+ "%s Dictation originates from the Siri app; forcing context clear to start a fresh dictation session."
+ "%s Logging ORCH→UEI RequestLink for triggerless/server-command reply turn with requestId=%@ turnId=%@"
+ "%s Reinitializing Intelligence Flow assets delegate for locale: %{public}@"
+ "%s Reply after the announce finished reading; completing %lu already-read announce(s) (current %@) instead of re-reading"
+ "%s Siri restriction imposed (%@) — disabling assistant"
+ "%s Skipping peer location request based on orchestration mode"
+ "%s Synching Voice Trigger data in %f seconds (vtFireTime %llu requestedFireTime %llu)"
+ "%s Voice Trigger sync timer already scheduled to fire no later than %f seconds from now; not rescheduling (vtFireTime %llu requestedFireTime %llu)"
+ "%s siriAvailability is nil in _clearContextAndStartAssistantSessionWithInvocationContext:; triggering synchronous capabilities update"
+ "%s siriAvailability is nil in resumeSessionWithOptions:completion:; triggering synchronous capabilities update"
+ "%s ‼️ Forcing shake to dismiss for confirmation reject during announce! Active confirmation contexts: %@"
+ "%s 🫨🔍 ADDaemon: Internal delegate already wired, skipping"
+ "(no error string)"
+ "(unset)"
+ "-[ADAssetManager registerAssetProvidersForLanguage:]"
+ "-[ADAssistantDataManager cachedUnredactedMeCard]"
+ "-[ADCommandCenter _clearContextAndStartAssistantSessionWithInvocationContext:]"
+ "-[ADCommandCenter handleSiriAvailabilityDidChange:]_block_invoke"
+ "-[ADCommandCenter resumeSessionWithOptions:completion:]_block_invoke"
+ "-[ADCommandCenter(Instrumentation) _logReplyTurnRequestLinkWithSpeechOptions:sessionUUID:]"
+ "-[ADHearablesExperienceManager _wireInternalDelegateToClientManager]"
+ "-[ADSiriCapabilitiesStore handleCurrentLocaleDidChange:]"
+ "-[ADSiriCapabilitiesStore performFullUpdate]"
+ "-[ADSiriCapabilitiesStore updateCapabilitiesSynchronouslyForLanguageCode:]"
+ "-[AFMutableDeviceContext setSerializedContextSnapshot:withMetadata:]"
+ "177"
+ "@\"SAPerson\"16@0:8"
+ "ADSiriCapabilitiesStoreAvailabilityDidChangeNotification"
+ "ADSiriCapabilitiesStoreNewAvailabilityKey"
+ "ADSiriCapabilitiesStoreOldAvailabilityKey"
+ "MobileAssistantDaemons-3600.68.61"
+ "T@\"<AFHearablesExperienceManagerInternalDelegate>\",&,N,V_internalDelegateAdapter"
+ "TQ,N,V_voiceTriggerSyncFireTime"
+ "Ti,N,V_expressivityPreset"
+ "Ti,N,V_pacePreset"
+ "_ADInitializeSandbox"
+ "_expressivityPreset"
+ "_getIsLLMSiriAvailable"
+ "_internalDelegateAdapter"
+ "_logReplyTurnRequestLinkWithSpeechOptions:sessionUUID:"
+ "_pacePreset"
+ "_shouldLogReplyTurnRequestLinkForSpeechEvent:"
+ "_voiceTriggerSyncFireTime"
+ "_wireInternalDelegateToClientManager"
+ "assistantd sandbox init: confstr(_CS_DARWIN_USER_CACHE_DIR) failed: %s"
+ "assistantd sandbox init: confstr(_CS_DARWIN_USER_CACHE_DIR) truncated (needed=%zu, cap=%zu)"
+ "assistantd sandbox init: confstr(_CS_DARWIN_USER_DIR) failed: %s"
+ "assistantd sandbox init: confstr(_CS_DARWIN_USER_DIR) truncated (needed=%zu, cap=%zu)"
+ "assistantd sandbox init: confstr(_CS_DARWIN_USER_TEMP_DIR) failed: %s"
+ "assistantd sandbox init: confstr(_CS_DARWIN_USER_TEMP_DIR) truncated (needed=%zu, cap=%zu)"
+ "assistantd sandbox init: realpath for HOME ('%s') failed: %s"
+ "assistantd sandbox init: realpath('%s') for cache dir failed: %s"
+ "assistantd sandbox init: realpath('%s') for temp dir failed: %s"
+ "assistantd sandbox init: realpath('%s') for unsuffixed user dir failed: %s"
+ "assistantd sandbox init: sandbox_init_with_parameters(com.apple.assistantd) failed: %s"
+ "assistantd sandbox init: setenv(%s, \"assistantd\") failed: %s"
+ "cachedUnredactedMeCard"
+ "expressivity_preset"
+ "handleCurrentLocaleDidChange:"
+ "handleSiriAvailabilityDidChange:"
+ "hasExpressivityPreset"
+ "hasPacePreset"
+ "internalDelegateAdapter"
+ "masteredVersion"
+ "pace_preset"
+ "restrictionReasons"
+ "setExpressivityPreset:"
+ "setHasExpressivityPreset:"
+ "setHasPacePreset:"
+ "setInternalDelegateAdapter:"
+ "setIsLLMSiriAvailable:"
+ "setPacePreset:"
+ "setVoiceTriggerSyncFireTime:"
+ "unredactedMeCard"
+ "updateCapabilitiesSynchronouslyForLanguageCode:"
+ "voiceTriggerSyncFireTime"
+ "{?=\"expressivityPreset\"b1\"gender\"b1\"pacePreset\"b1}"
- "%s #IFToolbox Reinitializing Intelligence Toolbox Readiness delegate for new locale: %{public}@"
- "%s Asset manager is deallocated."
- "%s Cannot re-initialize Intelligence Flow assets delegate, new languageCode: '%{public}@' is invalid for locale creation."
- "%s Cannot re-initialize Intelligence Flow assets delegate, new languageCode: '%{public}@' is nil."
- "%s Error Initializing sandbox: %{public}s\n"
- "%s Failed to get realpath for cache directory.  errno: %{public}s\n"
- "%s Failed to get realpath for home directory.  errno: %{public}s\n"
- "%s Failed to get realpath for temp directory.  errno: %{public}s\n"
- "%s Failed to get realpath for unsuffixed user directory.  errno: %{public}s\n"
- "%s Reinitializing Intelligence Flow assets delegate for new locale: %{public}@"
- "%s Synching Voice Trigger data in %f seconds"
- "-[ADAssetManager languageCodeWasChangedTo:]_block_invoke"
- "-[ADSiriCapabilitiesStore updateCapabilitiesStore]"
- "22"
- "MobileAssistantDaemons-3600.68.44"
- "SiriExpressiveVoicesEnabled"
- "SiriSetup"
- "_pendingAssetFetchBackstops"
- "isSharedBackedUpMigrationEnabled"
- "linwood_voices_seed"
- "removeObjectIdenticalTo:"
- "{?=\"gender\"b1}"
```
