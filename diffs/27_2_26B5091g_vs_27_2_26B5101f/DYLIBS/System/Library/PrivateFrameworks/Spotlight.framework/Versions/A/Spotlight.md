## Spotlight

> `/System/Library/PrivateFrameworks/Spotlight.framework/Versions/A/Spotlight`

```diff

-2465.1.3.0.0
-  __TEXT.__text: 0xe3f3c
-  __TEXT.__objc_methlist: 0x545c
-  __TEXT.__const: 0x2630
-  __TEXT.__gcc_except_tab: 0x417c
-  __TEXT.__cstring: 0x6e01
+2465.1.7.0.0
+  __TEXT.__text: 0xe71d8
+  __TEXT.__objc_methlist: 0x5724
+  __TEXT.__const: 0x2640
+  __TEXT.__gcc_except_tab: 0x43a0
+  __TEXT.__cstring: 0x6ee1
   __TEXT.__oslogstring: 0x5d5f
   __TEXT.__ustring: 0x32
+  __TEXT.__constg_swiftt: 0xa3c
   __TEXT.__swift5_typeref: 0xe89
+  __TEXT.__swift5_reflstr: 0x7e7
   __TEXT.__swift5_fieldmd: 0x84c
-  __TEXT.__constg_swiftt: 0xa3c
-  __TEXT.__swift5_reflstr: 0x7f7
+  __TEXT.__swift5_types: 0x9c
   __TEXT.__swift5_protos: 0x18
   __TEXT.__swift5_proto: 0x14c
-  __TEXT.__swift5_types: 0x9c
   __TEXT.__swift_as_entry: 0xd4
   __TEXT.__swift_as_ret: 0xc0
   __TEXT.__swift_as_cont: 0x168
   __TEXT.__swift5_capture: 0x6ac
   __TEXT.__swift5_assocty: 0x168
   __TEXT.__swift5_builtin: 0x3c
-  __TEXT.__unwind_info: 0x3050
+  __TEXT.__unwind_info: 0x30e0
   __TEXT.__eh_frame: 0x1ce8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xce0
-  __DATA_CONST.__objc_classlist: 0x2a0
+  __DATA_CONST.__const: 0xd08
+  __DATA_CONST.__objc_classlist: 0x2b8
   __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0x78
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4648
-  __DATA_CONST.__objc_superrefs: 0x190
+  __DATA_CONST.__objc_selrefs: 0x4858
+  __DATA_CONST.__objc_superrefs: 0x198
   __DATA_CONST.__objc_arraydata: 0xa18
-  __DATA_CONST.__got: 0x15b0
-  __AUTH_CONST.__const: 0x4928
-  __AUTH_CONST.__cfstring: 0x6f60
-  __AUTH_CONST.__objc_const: 0x7db0
+  __DATA_CONST.__got: 0x15f8
+  __AUTH_CONST.__const: 0x49e8
+  __AUTH_CONST.__cfstring: 0x6fe0
+  __AUTH_CONST.__objc_const: 0x8550
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x8d0
   __AUTH_CONST.__objc_arrayobj: 0x2a0
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x18b0
-  __AUTH.__objc_data: 0x810
+  __AUTH_CONST.__auth_got: 0x18b8
+  __AUTH.__objc_data: 0x900
   __AUTH.__data: 0x88
-  __DATA.__objc_ivar: 0x58c
+  __DATA.__objc_ivar: 0x608
   __DATA.__data: 0xc80
-  __DATA.__bss: 0x25f0
+  __DATA.__bss: 0x2600
   __DATA.__common: 0x8
   __DATA_DIRTY.__objc_data: 0x17f0
   __DATA_DIRTY.__data: 0x918

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3431
-  Symbols:   6770
-  CStrings:  1526
+  Functions: 3508
+  Symbols:   6956
+  CStrings:  1533
 
Symbols:
+ +[SPApplicationQuery _test_runOnApplicationsQueryQueue:]
+ +[SPBundleFilter applyFiltering:context:]
+ -[SFGenerativeSearchResultContainer classForCoder]
+ -[SFGenerativeSearchResultContainer classForKeyedArchiver]
+ -[SPApplicationQuery _test_readAppRankEvaluatorOnApplicationsQueryQueue]
+ -[SPApplicationQuery _test_setTrivialAppRankEvaluator]
+ -[SPBundleFilterResolvedDimensions .cxx_destruct]
+ -[SPBundleFilterResolvedDimensions allowedSet]
+ -[SPBundleFilterResolvedDimensions disableSearchInSpotlightActive]
+ -[SPBundleFilterResolvedDimensions disableSearchInSpotlightBypassSet]
+ -[SPBundleFilterResolvedDimensions eventSourceActive]
+ -[SPBundleFilterResolvedDimensions eventSourceExemptSet]
+ -[SPBundleFilterResolvedDimensions excludedSet]
+ -[SPBundleFilterResolvedDimensions fileProviderBundleIDs]
+ -[SPBundleFilterResolvedDimensions fileProviderRequested]
+ -[SPBundleFilterResolvedDimensions hiddenSet]
+ -[SPBundleFilterResolvedDimensions indexLookupReachable]
+ -[SPBundleFilterResolvedDimensions initWithContext:]
+ -[SPBundleFilterResolvedDimensions installedAppSet]
+ -[SPBundleFilterResolvedDimensions lockedSet]
+ -[SPBundleFilterResolvedDimensions mdmActive]
+ -[SPBundleFilterResolvedDimensions mdmRestrictedSet]
+ -[SPBundleFilterResolvedDimensions needsAppProtectionServerXPC]
+ -[SPBundleFilterResolvedDimensions needsExcludedAppServerXPC]
+ -[SPBundleFilterResolvedDimensions needsMDMServerXPC]
+ -[SPBundleFilterResolvedDimensions notificationSourceActive]
+ -[SPBundleFilterResolvedDimensions relatedAppActive]
+ -[SPBundleFilterResolvedDimensions relatedAppAttributeComplete]
+ -[SPBundleFilterResolvedDimensions relatedAppInstalledActive]
+ -[SPBundleFilterResolvedDimensions resolveBundleListDimensionsWithContext:]
+ -[SPBundleFilterResolvedDimensions resolveIOSOnlyDimensionsWithContext:]
+ -[SPBundleFilterResolvedDimensions resolveSourceAttributeDimensionsWithContext:]
+ -[SPBundleFilterResolvedDimensions setExcludedSet:]
+ -[SPBundleFilterResolvedDimensions setHiddenSet:]
+ -[SPBundleFilterResolvedDimensions setLockedSet:]
+ -[SPBundleFilterResolvedDimensions setMdmRestrictedSet:]
+ -[SPBundleFilteringContext .cxx_destruct]
+ -[SPBundleFilteringContext allowedAppBundleIDs]
+ -[SPBundleFilteringContext disableSearchInSpotlightBypassBundleIDs]
+ -[SPBundleFilteringContext disabledOptions]
+ -[SPBundleFilteringContext enabledOptions]
+ -[SPBundleFilteringContext eventSourceExemptBundleIDs]
+ -[SPBundleFilteringContext excludedAppBundleIDs]
+ -[SPBundleFilteringContext hiddenAppBundleIDs]
+ -[SPBundleFilteringContext lockedAppBundleIDs]
+ -[SPBundleFilteringContext maximumEffortLevel]
+ -[SPBundleFilteringContext relatedAppBundleIdentifierAttributeComplete]
+ -[SPBundleFilteringContext setAllowedAppBundleIDs:]
+ -[SPBundleFilteringContext setDisableSearchInSpotlightBypassBundleIDs:]
+ -[SPBundleFilteringContext setDisabledOptions:]
+ -[SPBundleFilteringContext setEnabledOptions:]
+ -[SPBundleFilteringContext setEventSourceExemptBundleIDs:]
+ -[SPBundleFilteringContext setExcludedAppBundleIDs:]
+ -[SPBundleFilteringContext setHiddenAppBundleIDs:]
+ -[SPBundleFilteringContext setLockedAppBundleIDs:]
+ -[SPBundleFilteringContext setMaximumEffortLevel:]
+ -[SPBundleFilteringContext setRelatedAppBundleIdentifierAttributeComplete:]
+ GCC_except_table124
+ GCC_except_table132
+ GCC_except_table163
+ GCC_except_table94
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._allowedSet
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._disableSearchInSpotlightActive
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._disableSearchInSpotlightBypassSet
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._eventSourceActive
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._eventSourceExemptSet
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._excludedSet
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._fileProviderBundleIDs
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._fileProviderRequested
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._hiddenSet
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._indexLookupReachable
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._installedAppSet
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._lockedSet
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._mdmActive
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._mdmRestrictedSet
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._needsAppProtectionServerXPC
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._needsExcludedAppServerXPC
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._needsMDMServerXPC
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._notificationSourceActive
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._relatedAppActive
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._relatedAppAttributeComplete
+ OBJC_IVAR_$_SPBundleFilterResolvedDimensions._relatedAppInstalledActive
+ OBJC_IVAR_$_SPBundleFilteringContext._allowedAppBundleIDs
+ OBJC_IVAR_$_SPBundleFilteringContext._disableSearchInSpotlightBypassBundleIDs
+ OBJC_IVAR_$_SPBundleFilteringContext._disabledOptions
+ OBJC_IVAR_$_SPBundleFilteringContext._enabledOptions
+ OBJC_IVAR_$_SPBundleFilteringContext._eventSourceExemptBundleIDs
+ OBJC_IVAR_$_SPBundleFilteringContext._excludedAppBundleIDs
+ OBJC_IVAR_$_SPBundleFilteringContext._hiddenAppBundleIDs
+ OBJC_IVAR_$_SPBundleFilteringContext._lockedAppBundleIDs
+ OBJC_IVAR_$_SPBundleFilteringContext._maximumEffortLevel
+ OBJC_IVAR_$_SPBundleFilteringContext._relatedAppBundleIdentifierAttributeComplete
+ SPBundleFilterAliasClasses.classes
+ SPBundleFilterAliasClasses.onceToken
+ SPBundleFilterExpandAliasClasses
+ _MDItemCreator
+ _MDItemEventSourceBundleIdentifier
+ _MDItemRelatedAppBundleIdentifier
+ _OBJC_CLASS_$_CSBundleFilterAttributeBackfillGroup
+ _OBJC_CLASS_$_CSBundleFilterEvaluationRequest
+ _OBJC_CLASS_$_SPBundleFilter
+ _OBJC_CLASS_$_SPBundleFilterResolvedDimensions
+ _OBJC_CLASS_$_SPBundleFilteringContext
+ _OBJC_METACLASS_$_SPBundleFilter
+ _OBJC_METACLASS_$_SPBundleFilterResolvedDimensions
+ _OBJC_METACLASS_$_SPBundleFilteringContext
+ _PRSRankingFindMyBundleString
+ _PRSRankingPeopleFindMyBundleString
+ _PRSRankingPersonBundleString
+ _SPBundleFilterCheckDisabledSets
+ _SPBundleFilterComputeSourceAttributeResults
+ _SPBundleFilterErrorDomain
+ _SPBundleFilterEvaluateBundleIDLists
+ _SPBundleFilterEvaluateRelatedAppBundleIdentifier
+ _SPBundleFilterExpandAliasClasses
+ _SPBundleFilterIndexLookupAttributeNeeded
+ _SPBundleFilterItemsInState
+ _SPBundleFilterOptionIsActive
+ _SPBundleFilterStringEquals
+ __OBJC_$_CLASS_METHODS_SPBundleFilter
+ __OBJC_$_INSTANCE_METHODS_SPBundleFilterResolvedDimensions
+ __OBJC_$_INSTANCE_METHODS_SPBundleFilteringContext
+ __OBJC_$_INSTANCE_VARIABLES_SPBundleFilterResolvedDimensions
+ __OBJC_$_INSTANCE_VARIABLES_SPBundleFilteringContext
+ __OBJC_$_PROP_LIST_SPBundleFilterResolvedDimensions
+ __OBJC_$_PROP_LIST_SPBundleFilteringContext
+ __OBJC_CLASS_RO_$_SPBundleFilter
+ __OBJC_CLASS_RO_$_SPBundleFilterResolvedDimensions
+ __OBJC_CLASS_RO_$_SPBundleFilteringContext
+ __OBJC_METACLASS_RO_$_SPBundleFilter
+ __OBJC_METACLASS_RO_$_SPBundleFilterResolvedDimensions
+ __OBJC_METACLASS_RO_$_SPBundleFilteringContext
+ __ZNSt3__16vectorI17SPResultValueItemNS_9allocatorIS1_EEE5clearB9nqn220106Ev
+ ___29-[SPApplicationQuery dealloc]_block_invoke
+ ___54-[SPApplicationQuery _test_setTrivialAppRankEvaluator]_block_invoke
+ ___54-[SPApplicationQuery _test_setTrivialAppRankEvaluator]_block_invoke_2
+ ___72-[SPApplicationQuery _test_readAppRankEvaluatorOnApplicationsQueryQueue]_block_invoke
+ ___SPBundleFilterAliasClasses_block_invoke
+ ___SPBundleFilterAwaitServerXPCReply_block_invoke
+ ___SPBundleFilterMergeAttributeBackfillResults_block_invoke
+ ___block_descriptor_32_e5_C8?0l
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24l
+ ___block_descriptor_64_e8_32s40r48r56r_e51_v24?0"CSBundleFilterEvaluationReply"8"NSError"16l
+ ___copy_helper_block_e8_32s40r48r56r
+ ___destroy_helper_block_e8_32s40r48r56r
+ _objc_msgSend$_evaluateFilters:completionHandler:
+ _objc_msgSend$allowedAppBundleIDs
+ _objc_msgSend$allowedSet
+ _objc_msgSend$attributeBackfillResults
+ _objc_msgSend$confirmedAbsentIdentifiers
+ _objc_msgSend$creator
+ _objc_msgSend$disableSearchInSpotlight
+ _objc_msgSend$disableSearchInSpotlightActive
+ _objc_msgSend$disableSearchInSpotlightBypassBundleIDs
+ _objc_msgSend$disableSearchInSpotlightBypassSet
+ _objc_msgSend$disabledOptions
+ _objc_msgSend$enabledOptions
+ _objc_msgSend$eventSourceActive
+ _objc_msgSend$eventSourceBundleIdentifier
+ _objc_msgSend$eventSourceExemptBundleIDs
+ _objc_msgSend$eventSourceExemptSet
+ _objc_msgSend$excludedAppBundleIDs
+ _objc_msgSend$excludedSet
+ _objc_msgSend$fileProviderRequested
+ _objc_msgSend$filteringResult
+ _objc_msgSend$hiddenAppBundleIDs
+ _objc_msgSend$hiddenSet
+ _objc_msgSend$indexLookupReachable
+ _objc_msgSend$initWithBundleID:attributeName:protectionClass:identifiers:
+ _objc_msgSend$initWithContext:
+ _objc_msgSend$initWithFileProviderContainerGroups:fileProviderExcludedBundleIDs:needsAppProtectionBundleIDs:needsMDMRestrictedBundleIDs:needsExcludedAppBundleIDs:attributeBackfillGroups:
+ _objc_msgSend$lockedAppBundleIDs
+ _objc_msgSend$lockedSet
+ _objc_msgSend$maximumEffortLevel
+ _objc_msgSend$mdmActive
+ _objc_msgSend$mdmRestrictedSet
+ _objc_msgSend$needsAppProtectionServerXPC
+ _objc_msgSend$needsExcludedAppServerXPC
+ _objc_msgSend$needsMDMServerXPC
+ _objc_msgSend$notificationSourceActive
+ _objc_msgSend$relatedAppActive
+ _objc_msgSend$relatedAppAttributeComplete
+ _objc_msgSend$relatedAppBundleIdentifierAttributeComplete
+ _objc_msgSend$relatedAppInstalledActive
+ _objc_msgSend$resolveBundleListDimensionsWithContext:
+ _objc_msgSend$resolveIOSOnlyDimensionsWithContext:
+ _objc_msgSend$resolveSourceAttributeDimensionsWithContext:
+ _objc_msgSend$resolvedValues
+ _objc_msgSend$setFilteringResult:
+ _objc_setProperty_nonatomic_copy
- GCC_except_table118
- GCC_except_table126
- GCC_except_table156
- GCC_except_table88
CStrings:
+ "$\""
+ "Option(s) 0x%lx present in both enabledOptions and disabledOptions."
+ "SPBundleFilterErrorDomain"
+ "com.apple.usernotifications.groups"
+ "test"
+ "v24@?0@\"CSBundleFilterEvaluationReply\"8@\"NSError\"16"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
```
