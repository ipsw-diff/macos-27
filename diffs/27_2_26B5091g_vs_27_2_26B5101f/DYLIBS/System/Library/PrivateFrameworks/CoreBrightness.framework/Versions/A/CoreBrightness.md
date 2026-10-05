## CoreBrightness

> `/System/Library/PrivateFrameworks/CoreBrightness.framework/Versions/A/CoreBrightness`

```diff

-2300.40.37.0.0
-  __TEXT.__text: 0x161ce0
-  __TEXT.__objc_methlist: 0xd5d0
-  __TEXT.__cstring: 0xcf55
-  __TEXT.__const: 0x12790
-  __TEXT.__gcc_except_tab: 0x1fd8
-  __TEXT.__oslogstring: 0x186ad
+2300.40.47.0.4
+  __TEXT.__text: 0x1667c4
+  __TEXT.__objc_methlist: 0xd7c8
+  __TEXT.__cstring: 0xd0d5
+  __TEXT.__const: 0x12950
+  __TEXT.__gcc_except_tab: 0x210c
+  __TEXT.__oslogstring: 0x18f5d
   __TEXT.__dlopen_cstrs: 0x10d
-  __TEXT.__swift5_typeref: 0xeaf
-  __TEXT.__constg_swiftt: 0xc34
-  __TEXT.__swift5_reflstr: 0xa4e
+  __TEXT.__swift5_typeref: 0xf35
+  __TEXT.__constg_swiftt: 0xd80
+  __TEXT.__swift5_reflstr: 0xbfe
   __TEXT.__swift5_assocty: 0x288
-  __TEXT.__swift5_fieldmd: 0x100c
-  __TEXT.__swift5_builtin: 0xdc
-  __TEXT.__swift5_capture: 0x3d0
+  __TEXT.__swift5_fieldmd: 0x1240
+  __TEXT.__swift5_builtin: 0x168
+  __TEXT.__swift5_capture: 0x41c
   __TEXT.__swift5_protos: 0x8
   __TEXT.__swift5_proto: 0x308
-  __TEXT.__swift5_types: 0x120
+  __TEXT.__swift5_types: 0x144
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__unwind_info: 0x7558
-  __TEXT.__eh_frame: 0xb90
+  __TEXT.__unwind_info: 0x76c0
+  __TEXT.__eh_frame: 0xbd0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1210
-  __DATA_CONST.__objc_classlist: 0x708
-  __DATA_CONST.__objc_catlist: 0x18
-  __DATA_CONST.__objc_protolist: 0x340
+  __DATA_CONST.__objc_classlist: 0x718
+  __DATA_CONST.__objc_catlist: 0x20
+  __DATA_CONST.__objc_protolist: 0x350
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x5800
-  __DATA_CONST.__objc_protorefs: 0x130
+  __DATA_CONST.__objc_selrefs: 0x58c0
+  __DATA_CONST.__objc_protorefs: 0x138
   __DATA_CONST.__objc_superrefs: 0x5c8
   __DATA_CONST.__objc_arraydata: 0xb90
-  __DATA_CONST.__got: 0x760
-  __AUTH_CONST.__const: 0x5990
-  __AUTH_CONST.__cfstring: 0xe780
-  __AUTH_CONST.__objc_const: 0x359c0
+  __DATA_CONST.__got: 0x7b0
+  __AUTH_CONST.__const: 0x5f58
+  __AUTH_CONST.__cfstring: 0xe880
+  __AUTH_CONST.__objc_const: 0x360b0
   __AUTH_CONST.__weak_auth_got: 0x20
   __AUTH_CONST.__objc_intobj: 0xcd8
   __AUTH_CONST.__objc_floatobj: 0x180
   __AUTH_CONST.__objc_arrayobj: 0x2a0
   __AUTH_CONST.__objc_dictobj: 0x5f0
   __AUTH_CONST.__objc_doubleobj: 0x40
-  __AUTH_CONST.__auth_got: 0x1290
-  __AUTH.__objc_data: 0x2770
-  __AUTH.__data: 0x630
-  __DATA.__objc_ivar: 0x17ac
-  __DATA.__data: 0x66fb0
-  __DATA.__bss: 0x63f0
+  __AUTH_CONST.__auth_got: 0x12f8
+  __AUTH.__objc_data: 0x28d0
+  __AUTH.__data: 0x690
+  __DATA.__objc_ivar: 0x17d8
+  __DATA.__data: 0x670c0
+  __DATA.__bss: 0x6430
   __DATA.__common: 0x10
   __DATA_DIRTY.__objc_data: 0x21e8
   __DATA_DIRTY.__data: 0x510
-  __DATA_DIRTY.__bss: 0x168
+  __DATA_DIRTY.__bss: 0x160
   __DATA_DIRTY.__common: 0x10
   - /System/Library/Frameworks/CoreDisplay.framework/Versions/A/CoreDisplay
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8269
-  Symbols:   13008
-  CStrings:  4673
+  Functions: 8381
+  Symbols:   13131
+  CStrings:  4730
 
Symbols:
+ -[BLControl setFrameInfoProviderForProxy:]
+ -[BacklightDriverPWM _noteLevelWriteForFrequencySettle:]
+ -[BacklightDriverPWM _scheduleFrequencySettleAfter:]
+ -[BacklightDriverPWM dutyKey]
+ -[BacklightDriverPWM setDutyKey:]
+ -[BacklightDriverPWM setUseDynamicFrequency:]
+ -[BacklightDriverPWM useDynamicFrequency]
+ -[BrightnessSystemClient observerSlug:]
+ -[BrightnessSystemClient refreshKeys]
+ -[CBDisplayBrightnessClient description]
+ -[CBDisplayClient description]
+ -[CBIndicatorBrightnessModule registerForThermalPressureNotifications]
+ -[CBIndicatorBrightnessModule thermalPressureNotificationHandler:]
+ -[CBPreset alwaysRequestMaxHeadroom]
+ -[CBPreset maxPotentialEDRHeadroom]
+ -[CBPresetsParser alwaysRequestMaxHeadroom:]
+ -[CBPresetsParser maxPotentialEDRHeadroomForDisplay:]
+ -[CBSystemContext frameInfoProvider]
+ -[CBSystemContext setFrameInfoProvider:]
+ -[NSArray(PrimitiveDataProvider) copyFloatVector]
+ -[NSSet(PrettyDescription) prettyDescription]
+ -[PWMDeviceController _reportDuty:]
+ -[PWMDeviceController dutyKey]
+ -[PWMDeviceController setDutyCycle:dynamicFrequency:]
+ -[PWMDeviceController setDutyKey:]
+ GCC_except_table100
+ GCC_except_table125
+ GCC_except_table150
+ GCC_except_table153
+ GCC_except_table154
+ GCC_except_table158
+ GCC_except_table159
+ GCC_except_table162
+ GCC_except_table163
+ GCC_except_table167
+ GCC_except_table168
+ GCC_except_table177
+ GCC_except_table182
+ GCC_except_table183
+ GCC_except_table69
+ GCC_except_table72
+ GCC_except_table77
+ OBJC_IVAR_$_BacklightDriverPWM._frequencySettlePending
+ OBJC_IVAR_$_BacklightDriverPWM._lastLevelWriteTime
+ OBJC_IVAR_$_BacklightDriverPWM._lastLevelWritten
+ OBJC_IVAR_$_BacklightDriverPWM._useDynamicFrequency
+ OBJC_IVAR_$_BrightnessSystemClient._observedKeys
+ OBJC_IVAR_$_BrightnessSystemClient._observersCount
+ OBJC_IVAR_$_CBCPMSModule._currentHDRNits
+ OBJC_IVAR_$_CBIndicatorBrightnessModule._thermalPressure
+ OBJC_IVAR_$_CBIndicatorBrightnessModule._thermalPressureNotificationToken
+ OBJC_IVAR_$_CBSystemContext._frameInfoProvider
+ OBJC_IVAR_$_PWMDeviceController._clock
+ OBJC_IVAR_$_PWMDeviceController._dutyKey
+ _OBJC_CLASS_$_CBSMCLib
+ _OBJC_CLASS_$_NSHashTable
+ _OBJC_CLASS_$_OS_dispatch_queue
+ _OBJC_METACLASS_$_CBSMCLib
+ _OBJC_METACLASS_$__TtC14CoreBrightnessP33_6B340E709F1569E35356F761E538365910SMCKeyImpl
+ _OUTLINED_FUNCTION_25
+ _OUTLINED_FUNCTION_26
+ _PROTOCOLS__TtC14CoreBrightnessP33_6B340E709F1569E35356F761E538365910SMCKeyImpl
+ _SMCGetKeyInfo
+ _SMCOpenConnectionWithDefaultService
+ _SMCWriteKeyWithKnownSize
+ __45-[CBIndicatorBrightnessModule setSilEnabled:]_block_invoke
+ __DATA_CBSMCLib
+ __DATA__TtC14CoreBrightnessP33_6B340E709F1569E35356F761E538365910SMCKeyImpl
+ __INSTANCE_METHODS_CBSMCLib
+ __INSTANCE_METHODS__TtC14CoreBrightnessP33_6B340E709F1569E35356F761E538365910SMCKeyImpl
+ __IVARS_CBSMCLib
+ __IVARS__TtC14CoreBrightnessP33_6B340E709F1569E35356F761E538365910SMCKeyImpl
+ __METACLASS_DATA_CBSMCLib
+ __METACLASS_DATA__TtC14CoreBrightnessP33_6B340E709F1569E35356F761E538365910SMCKeyImpl
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_NSSet_$_PrettyDescription
+ __OBJC_$_CATEGORY_NSSet_$_PrettyDescription
+ __OBJC_$_PROP_LIST_NSSet_$_PrettyDescription
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_CBSMCKey
+ __OBJC_$_PROTOCOL_METHOD_TYPES_CBSMCKey
+ __OBJC_$_PROTOCOL_REFS_CBSMCKey
+ __OBJC_LABEL_PROTOCOL_$_CBSMCKey
+ __OBJC_PROTOCOL_$_CBSMCKey
+ __PROTOCOLS__TtC14CoreBrightnessP33_6B340E709F1569E35356F761E538365910SMCKeyImpl
+ __ZN14CoreBrightness19lookupValueWithAxisIfEET_NSt3__16vectorIS1_NS2_9allocatorIS1_EEEES6_S1_
+ __ZN4AABC22BrightnessRestrictionsD2Ev
+ __ZN4AABC39BrightnessRestrictionMultiPointValues_saSERKS0_
+ ___52-[BacklightDriverPWM _scheduleFrequencySettleAfter:]_block_invoke
+ ___70-[CBIndicatorBrightnessModule registerForThermalPressureNotifications]_block_invoke
+ ___block_descriptor_40_e8_32b_e33_v16?0r^{?=IIQQQQIBBBfffQIBQQfB}8l
+ ___block_descriptor_40_e8_32r_e8_v12?0i8l
+ ___block_descriptor_40_e8_32w_e5_v8?0l
+ ___block_descriptor_49_e8_32o40o_e15_v32?08Q16^B24l
+ ___copy_helper_block_e8_32w
+ ___destroy_helper_block_e8_32w
+ ___swift_memcpy512_8
+ ___swift_memcpy56_8
+ ___swift_memcpy5_4
+ ___swift_memcpy8_8
+ _kOSThermalNotificationPressureLevelName
+ _objc_copyWeak
+ _objc_initWeak
+ _objc_msgSend$_noteLevelWriteForFrequencySettle:
+ _objc_msgSend$_reportDuty:
+ _objc_msgSend$_scheduleFrequencySettleAfter:
+ _objc_msgSend$alwaysRequestMaxHeadroom
+ _objc_msgSend$alwaysRequestMaxHeadroom:
+ _objc_msgSend$copyFloatVector
+ _objc_msgSend$dutyKey
+ _objc_msgSend$initWithFrameInfoProvider:
+ _objc_msgSend$initWithOptions:capacity:
+ _objc_msgSend$maxPotentialEDRHeadroom
+ _objc_msgSend$maxPotentialEDRHeadroomForDisplay:
+ _objc_msgSend$observerSlug:
+ _objc_msgSend$prettyDescription
+ _objc_msgSend$refreshKeys
+ _objc_msgSend$registerForThermalPressureNotifications
+ _objc_msgSend$setDutyCycle:dynamicFrequency:
+ _objc_msgSend$setDutyKey:
+ _objc_msgSend$setFrameInfoProvider:
+ _objc_msgSend$setFrameInfoProviderForProxy:
+ _objc_msgSend$thermalPressureNotificationHandler:
+ _objc_msgSend$writeFloat:
+ _objc_msgSend$writeFloat:throttled:
+ _swift_isaMask
+ _symbolic Say_____G So17OS_dispatch_queueC8DispatchE10AttributesV
+ _symbolic So8CBSMCLibC
+ _symbolic Spy_____G So13smc_connect_ta
+ _symbolic _____ 14CoreBrightness10SMCKeyImpl33_6B340E709F1569E35356F761E5383659LLC
+ _symbolic _____ 14CoreBrightness10SMCKeyImpl33_6B340E709F1569E35356F761E5383659LLC7PendingO
+ _symbolic _____ So10SMCKeyAttra
+ _symbolic _____ So10SMCKeyInfoa
+ _symbolic _____ So10SMCKeyInfoa20__Unnamed_union_infoV
+ _symbolic _____ So13smc_connect_ta
+ _symbolic _____ So16SMCNumericOutputa
+ _symbolic _____ So24SMCProgrammableAccumDataa
+ _symbolic _____ So25SMCProgrammableAccumParama
+ _symbolic _____ s5UInt8V
+ _symbolic _____Sg 8Dispatch0A4TimeV
+ _symbolic _____Sg s13OpaquePointerV
+ _symbolic ______A3At So24SMCProgrammableAccumDataa
+ _symbolic ______A3At s6UInt32V
+ _type_layout_string So10SMCKeyAttra
+ _type_layout_string So10SMCKeyInfoa
+ _type_layout_string So13smc_connect_ta
+ _type_layout_string So24SMCProgrammableAccumDataa
+ _type_layout_string So25SMCProgrammableAccumParama
- GCC_except_table138
- GCC_except_table140
- GCC_except_table149
- GCC_except_table152
- GCC_except_table156
- GCC_except_table157
- GCC_except_table160
- GCC_except_table161
- GCC_except_table165
- GCC_except_table166
- GCC_except_table174
- GCC_except_table175
- GCC_except_table180
- GCC_except_table181
- GCC_except_table40
- GCC_except_table61
- GCC_except_table65
- GCC_except_table70
- GCC_except_table71
- GCC_except_table98
- OBJC_IVAR_$_CBCPMSModule._currentSDRNits
- ___block_descriptor_40_e8_32b_e32_v16?0r^{?=IIQQQQIBBBfffQIBQQf}8l
- _objc_msgSend$setWithSet:
CStrings:
+ "%@<%@>"
+ "%@@%@ with %@"
+ "-[BrightnessSystemClient unregisterObserver:]"
+ "BrightnessRestrictionsFromPreferences"
+ "CPMSCurrentHDRNits"
+ "CoreBrightness.SMCKeyImpl"
+ "CoreBrightness_Internal.CBSMCLib"
+ "Display on seeded by handoff — skipping snap to own curve"
+ "EXBrightSILStateTrusted"
+ "Failed to write %f to SMC key %s (%hhd)"
+ "Ignoring %{public}@: expected %zu levels, got %lu"
+ "Ignoring %{public}@: not ascending: %{public}@"
+ "Initial thermal pressure level: %llu"
+ "Loaded Restriction Dictionary (Dynamic Slider Configuration) from defaults (StoreDemoMode = %d): %@"
+ "PresetHostAlwaysRequestMaxHeadroom"
+ "PresetHostMaxPotentialEDRHeadroom"
+ "Presets(%lu): always request max headroom = %d"
+ "Presets(%lu): maxPotentialEDRHeadroom: %@"
+ "SMC key %s unavailable on this platform (%hhd)"
+ "SMC key name %s is not four characters"
+ "Semantic ambient lux levels: %{public}@"
+ "Setting PWM duty cycle to: %llu at %llu Hz"
+ "Thermal Pressure Critical! Snapping to target indicator brightness %f"
+ "Thermal pressure level changed: %llu -> %llu"
+ "Unable to open an SMC connection; missing the entitlement?"
+ "Wrote %f to SMC key %s"
+ "[%@]"
+ "[BRT update: %s]: begin ramp L: %0.2f -> %0.2f P: %0.2f -> %0.2f (hwMax-perceptual) t: %f rate: %0.2f nits/s %0.2fhz"
+ "[CPMS] Current HDR brightness updated: %f -> %f"
+ "[CPMS] Sending nits cap ramp to display: target=%f duration=%fs start=%f"
+ "[CPMS] Using current HDR nits (%f) instead of cap (%f) for ramp duration calculation"
+ "[Display] CPMS cap ramp: seeding origin %f -> %f (target %f, headroom %f)"
+ "[Display] CPMS ramp request: target=%f duration=%f start=%f"
+ "[Dynamic Slider] MAX - failed to convert thresholds or factors to a float vector"
+ "[Dynamic Slider] MAX - missing thresholds or factors"
+ "[Dynamic Slider] MAX - thresholds and factors differ in size (%zu vs %zu)"
+ "[Dynamic Slider] MAX - thresholds and factors need at least 1 entry"
+ "[Dynamic Slider] MAX - thresholds or factors are not arrays"
+ "[Dynamic Slider] MAX - thresholds or factors not sorted in ascending order"
+ "[Dynamic Slider] MIN - failed to convert thresholds or factors to a float vector"
+ "[Dynamic Slider] MIN - missing thresholds or factors"
+ "[Dynamic Slider] MIN - thresholds and factors differ in size (%zu vs %zu)"
+ "[Dynamic Slider] MIN - thresholds and factors need at least 1 entry"
+ "[Dynamic Slider] MIN - thresholds or factors are not arrays"
+ "[Dynamic Slider] MIN - thresholds or factors not sorted in ascending order"
+ "[Observer] Adding %@"
+ "[Observer] Not adding %@ - no observable properties"
+ "[Observer] Observed keys 🔑: %@ - %@ + %@ = %@"
+ "[Observer] Refreshing %@"
+ "[Observer] Removing %@ since the set of properties become empty."
+ "[Observer] Unregistering %@"
+ "[dcpRoleID=%d] [ReadBack] Couldn't fetch SIL state!"
+ "[dcpRoleID=%d] [ReadBack] SIL=%d"
+ "[dcpRoleID=%d] [ReadBack] SIL=%d, sessionID=%u"
+ "[dcpRoleID=%d] [WillSend] SIL=%d"
+ "[dcpRoleID=%d] [WillSend] SIL=%d failed!"
+ "cleared"
+ "com.apple.CoreBrightness.CBSMCLib"
+ "crgb lookup: found=%d parsed=%d value=%d"
+ "frame info provider %s"
+ "notify_get_state failed with %d for token %d"
+ "notify_register_dispatch failed with %d for %s"
+ "published"
+ "semantic-lux-levels"
+ "startNits"
+ "v16@?0r^{?=IIQQQQIBBBfffQIBQQfB}8"
- "CPMSCurrentSDRNits"
- "Registered observer %@ with handle %@, properties %@. Subscribing to the following new keys: %@"
- "Removing observer %@ with handle %@. Unregistering the following keys: %@"
- "Setting PWM duty cycle to: %llu"
- "[CPMS] Sending nits cap ramp to display: target=%f duration=%fs"
- "[CPMS] Using current SDR nits (%f) instead of cap (%f) for ramp duration calculation"
- "[Display] CPMS ramp request: target=%f duration=%f"
- "[dcpRoleID=%d] SIL=%d, monotonicTimeUS=%llu. Sending to EXBright: %@."
- "v16@?0r^{?=IIQQQQIBBBfffQIBQQf}8"
```
