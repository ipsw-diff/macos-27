## AppPredictionClient

> `/System/Library/PrivateFrameworks/AppPredictionClient.framework/Versions/A/AppPredictionClient`

```diff

-675.0.2.0.0
-  __TEXT.__text: 0x198c14
-  __TEXT.__objc_methlist: 0x18a64
+677.0.2.0.0
+  __TEXT.__text: 0x19c530
+  __TEXT.__objc_methlist: 0x18b9c
   __TEXT.__const: 0x708
-  __TEXT.__cstring: 0x1bf0d
-  __TEXT.__oslogstring: 0x17410
-  __TEXT.__gcc_except_tab: 0x1c38
+  __TEXT.__cstring: 0x1c2a2
+  __TEXT.__oslogstring: 0x178ab
+  __TEXT.__gcc_except_tab: 0x1cac
   __TEXT.__dlopen_cstrs: 0x2cc
   __TEXT.__ustring: 0x18a
-  __TEXT.__unwind_info: 0x83e8
+  __TEXT.__unwind_info: 0x8490
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x90
   __DATA_CONST.__objc_protolist: 0x238
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x9f88
+  __DATA_CONST.__objc_selrefs: 0xa060
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0xbf0
-  __DATA_CONST.__objc_arraydata: 0xb10
-  __DATA_CONST.__got: 0x16c8
-  __AUTH_CONST.__const: 0x6440
-  __AUTH_CONST.__cfstring: 0x154a0
-  __AUTH_CONST.__objc_const: 0x447d0
+  __DATA_CONST.__objc_arraydata: 0xb30
+  __DATA_CONST.__got: 0x16d8
+  __AUTH_CONST.__const: 0x6550
+  __AUTH_CONST.__cfstring: 0x15560
+  __AUTH_CONST.__objc_const: 0x448a8
   __AUTH_CONST.__objc_intobj: 0xa98
   __AUTH_CONST.__objc_arrayobj: 0x6d8
   __AUTH_CONST.__objc_doubleobj: 0x20
-  __AUTH_CONST.__objc_dictobj: 0x168
+  __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__auth_got: 0x690
   __AUTH.__objc_data: 0x33e0
-  __DATA.__objc_ivar: 0x1c3c
+  __DATA.__objc_ivar: 0x1c50
   __DATA.__data: 0x1aa0
-  __DATA.__bss: 0x300
+  __DATA.__bss: 0x320
   __DATA_DIRTY.__objc_data: 0x55f0
   __DATA_DIRTY.__data: 0x88
   __DATA_DIRTY.__bss: 0x330

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 10880
-  Symbols:   20595
-  CStrings:  4794
+  Functions: 10927
+  Symbols:   20678
+  CStrings:  4825
 
Symbols:
+ +[ATXDefaultHomeScreenItemManager _widgetIdentifiersNotAllowedForClient:]
+ +[ATXDefaultHomeScreenItemManager _widgetIdentifiersNotAllowedOnTvOS]
+ +[ATXDefaultHomeScreenItemProducerUtilities remoteWidgetsFromPairedDeviceRanking:size:personalityToDescriptorDictionary:]
+ +[ATXDefaultHomeScreenItemProducerUtilities widgetsByInterleavingWidgets:withWidgets:limit:usedPersonalities:usedAppBundleIds:]
+ -[ATXDefaultHomeScreenItemManager _pairedDeviceRankedWidgetsForClientIdentity:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _deviceIdentifierForRelationshipIdentifier:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _hasPairedDeviceImportForVariant:]
+ -[ATXDefaultHomeScreenItemManagerTransfer _pairedDevicePathForVariant:sourceDeviceIdentifier:]
+ -[ATXDefaultHomeScreenItemManagerTransfer importedWidgetSmartStacksByPathForVariant:]
+ -[ATXDefaultHomeScreenItemManagerTransfer pairedDeviceWidgetSmartStackForVariant:relationshipIdentifier:maximumAge:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _generatedStacksWithRequest:includeRequiredWidgets:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _pairedDeviceRemoteWidgetsForSize:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _stacksByFillingWithPairedDeviceThirdPartyWidgets:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer _tvOSRequiredWidgetsKeyForOnboarding:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer pairedDeviceRankedWidgets]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer setPairedDeviceRankedWidgets:]
+ -[ATXDefaultHomeScreenItemOnboardingStacksProducer usageRankedStacksWithRequest:]
+ -[ATXDefaultHomeScreenItemProducer _onboardingStacksProducerForSmartStackRequest:]
+ -[ATXDefaultHomeScreenItemProducer pairedDeviceRankedWidgets]
+ -[ATXDefaultHomeScreenItemProducer setPairedDeviceRankedWidgets:]
+ -[ATXDefaultHomeScreenItemProducer usageRankedStacksWithRequest:]
+ -[ATXDefaultWidgetSuggesterClient fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]
+ -[ATXWidgetSmartStackResponse setSourceDeviceIdentifier:]
+ -[ATXWidgetSmartStackResponse sourceDeviceIdentifier]
+ ATXCanonicalContainerBundleIdForWidgetDedup
+ ATXCanonicalContainerBundleIdForWidgetDedup.aliases
+ ATXCanonicalContainerBundleIdForWidgetDedup.onceToken
+ OBJC_IVAR_$_ATXDefaultHomeScreenItemManagerTransfer._pairedDevicePathPrefix
+ OBJC_IVAR_$_ATXDefaultHomeScreenItemManagerTransfer._widgetSuggesterClient
+ OBJC_IVAR_$_ATXDefaultHomeScreenItemOnboardingStacksProducer._pairedDeviceRankedWidgets
+ OBJC_IVAR_$_ATXDefaultHomeScreenItemProducer._pairedDeviceRankedWidgets
+ OBJC_IVAR_$_ATXWidgetSmartStackResponse._sourceDeviceIdentifier
+ _ATXCanonicalContainerBundleIdForWidgetDedup
+ _OBJC_CLASS_$_CHSRemoteDeviceService
+ _OBJC_CLASS_$_NSOrderedSet
+ __103-[ATXDefaultHomeScreenItemOnboardingStacksProducer _generatedStacksWithRequest:includeRequiredWidgets:]_block_invoke
+ __105-[ATXDefaultWidgetSuggesterClient fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke
+ __153-[ATXDefaultHomeScreenItemOnboardingStacksProducer _dayZeroStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke
+ __196-[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke
+ __86-[ATXDefaultHomeScreenItemManagerTransfer _deviceIdentifierForRelationshipIdentifier:]_block_invoke
+ ___103-[ATXDefaultHomeScreenItemOnboardingStacksProducer _generatedStacksWithRequest:includeRequiredWidgets:]_block_invoke
+ ___105-[ATXDefaultWidgetSuggesterClient fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:]_block_invoke
+ ___107-[ATXDefaultHomeScreenItemOnboardingStacksProducer _pairedDeviceRemoteWidgetsForSize:denyListOfExtensions:]_block_invoke
+ ___153-[ATXDefaultHomeScreenItemOnboardingStacksProducer _dayZeroStacksFromRequiredPersonalitiesPerStack:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke
+ ___196-[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]_block_invoke
+ ___55-[ATXDefaultHomeScreenItemProducer _personalizedUpdate]_block_invoke
+ ___86-[ATXDefaultHomeScreenItemManagerTransfer _deviceIdentifierForRelationshipIdentifier:]_block_invoke
+ ___ATXCanonicalContainerBundleIdForWidgetDedup_block_invoke
+ ___block_descriptor_48_e8_32s40r_e29_v16?0"NSMutableDictionary"8l
+ ___block_descriptor_48_e8_32s40s_e29_v16?0"NSMutableDictionary"8l
+ ___block_descriptor_48_e8_32s_e30_B16?0"ATXWidgetPersonality"8l
+ ___pairedDeviceIdentifiersByRelationship_block_invoke
+ _cachePath
+ _canonicalDeviceIdentifier
+ _isNilOrArrayOfWidgets
+ _isWellFormedSmartStackResponse
+ _kATXPairedDeviceWidgetRankingMaximumAge
+ _objc_msgSend$_blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:
+ _objc_msgSend$_deviceIdentifierForRelationshipIdentifier:
+ _objc_msgSend$_generatedStacksWithRequest:includeRequiredWidgets:
+ _objc_msgSend$_hasPairedDeviceImportForVariant:
+ _objc_msgSend$_onboardingStacksProducerForSmartStackRequest:
+ _objc_msgSend$_pairedDevicePathForVariant:sourceDeviceIdentifier:
+ _objc_msgSend$_pairedDeviceRankedWidgetsForClientIdentity:
+ _objc_msgSend$_pairedDeviceRemoteWidgetsForSize:denyListOfExtensions:
+ _objc_msgSend$_stacksByFillingWithPairedDeviceThirdPartyWidgets:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:
+ _objc_msgSend$_tvOSRequiredWidgetsKeyForOnboarding:
+ _objc_msgSend$_widgetIdentifiersNotAllowedForClient:
+ _objc_msgSend$allPairedDevices
+ _objc_msgSend$contentsOfDirectoryAtPath:error:
+ _objc_msgSend$fetchWidgetSmartStackForPairedTvOSDeviceWithRequest:completionHandler:
+ _objc_msgSend$lastPathComponent
+ _objc_msgSend$orderedSetWithObjects:
+ _objc_msgSend$pairedDeviceRankedWidgets
+ _objc_msgSend$relationshipID
+ _objc_msgSend$remoteWidgetsFromPairedDeviceRanking:size:personalityToDescriptorDictionary:
+ _objc_msgSend$setPairedDeviceRankedWidgets:
+ _objc_msgSend$sourceDeviceIdentifier
+ _objc_msgSend$usageRankedStacksWithRequest:
+ _objc_msgSend$widgetsByInterleavingWidgets:withWidgets:limit:usedPersonalities:usedAppBundleIds:
+ _pairedDeviceIdentifiersByRelationship
+ pairedDeviceIdentifiersByRelationship
+ pairedDeviceIdentifiersByRelationship.lock
+ pairedDeviceIdentifiersByRelationship.onceToken
- __79-[ATXDefaultHomeScreenItemOnboardingStacksProducer generatedStacksWithRequest:]_block_invoke
- ___79-[ATXDefaultHomeScreenItemOnboardingStacksProducer generatedStacksWithRequest:]_block_invoke
CStrings:
+ "%s: %lu third-party widgets available from the paired device's ranking"
+ "%s: Couldn't read import at %@: %@"
+ "%s: Importing %lu smart stacks from source device %@"
+ "%s: No descriptor available for required personalities %{public}@"
+ "%s: No paired device for relationship %@"
+ "%s: No usable stacks from paired device %@ (error: %@)"
+ "%s: Not importing malformed smart stacks"
+ "%s: Number of Stacks being requested %lu, including required widgets: %{BOOL}d"
+ "%s: Skipping remote widget %{public}@:%{public}@ because a local version exists for %{public}@:%{public}@"
+ "%s: blending %lu of the paired device's %lu ranked widgets"
+ "%s: blending %lu of the paired device's %lu ranked widgets into gallery widgets"
+ "%s: descriptor metadata unavailable (%{public}@), continuing with %lu descriptors because this is a day zero request"
+ "%s: generating usage ranked stacks for Client. numDescriptors:%lu, descriptorCacheSize:%lu, appsWithLaunches:%lu"
+ "%s: stack has %lu of %lu widgets; the paired device has no more third-party widgets to fill it"
+ "(unstamped)"
+ "-[ATXDefaultHomeScreenItemManagerTransfer importWidgetSmartStackWithRequest:response:completionHandler:]"
+ "-[ATXDefaultHomeScreenItemManagerTransfer importedWidgetSmartStacksByPathForVariant:]"
+ "-[ATXDefaultHomeScreenItemManagerTransfer pairedDeviceWidgetSmartStackForVariant:relationshipIdentifier:maximumAge:]"
+ "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _blendedStacksForSize:requiredWidgetPersonalitiesPerStack:rankedWidgets:usedWidgetPersonalities:maxNumberOfWidgetsPerStack:denyListOfExtensions:]"
+ "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _generatedStacksWithRequest:includeRequiredWidgets:]"
+ "-[ATXDefaultHomeScreenItemOnboardingStacksProducer _stacksByFillingWithPairedDeviceThirdPartyWidgets:size:maxNumberOfWidgetsPerStack:denyListOfExtensions:]"
+ "-[ATXDefaultHomeScreenItemProducer usageRankedStacksWithRequest:]"
+ "ATXDefaultWidgetSuggesterClient: XPC error; could not generate smart stacks for paired tvOS device via duetexpertd: %@"
+ "Smart stacks to import are malformed"
+ "com.apple.mobilecal"
+ "dayZero:%{BOOL}d pairedDevice:%{BOOL}d"
+ "denyListWidgetsTvOS"
+ "onboardingDefaultStackTvOS"
+ "smartStackDenyListAssetLookup"
+ "smartStackDescriptorCacheAccess"
+ "smartStackPairedDeviceRanking"
+ "smartStackProtectedAppsLookup"
+ "sourceDeviceIdentifier"
+ "v16@?0@\"NSMutableDictionary\"8"
+ "widgets:%lu"
- "%s: Number of Stacks being requested %lu"
- "%s: Skipping remote widget because local version exists for %@:%@"
- "-[ATXDefaultHomeScreenItemOnboardingStacksProducer generatedStacksWithRequest:]"
- "dayZero:%{BOOL}d"
```
