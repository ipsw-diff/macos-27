## SpotlightDaemon

> `/System/Library/PrivateFrameworks/SpotlightDaemon.framework/Versions/A/SpotlightDaemon`

```diff

-2465.1.3.0.0
-  __TEXT.__text: 0xc6b0c
-  __TEXT.__objc_methlist: 0x4c04
+2465.1.7.0.0
+  __TEXT.__text: 0xc99bc
+  __TEXT.__objc_methlist: 0x4d54
   __TEXT.__const: 0x410
-  __TEXT.__cstring: 0x9b3a
-  __TEXT.__gcc_except_tab: 0x45bc
-  __TEXT.__oslogstring: 0xc21f
-  __TEXT.__unwind_info: 0x3448
+  __TEXT.__cstring: 0x9c9b
+  __TEXT.__gcc_except_tab: 0x46a8
+  __TEXT.__oslogstring: 0xc324
+  __TEXT.__unwind_info: 0x34f0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x650
-  __DATA_CONST.__objc_classlist: 0x1d0
+  __DATA_CONST.__objc_classlist: 0x1d8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3c60
+  __DATA_CONST.__objc_selrefs: 0x3d98
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__objc_superrefs: 0x148
+  __DATA_CONST.__objc_superrefs: 0x150
   __DATA_CONST.__objc_arraydata: 0x2f0
-  __DATA_CONST.__got: 0xbc0
-  __AUTH_CONST.__const: 0x5868
+  __DATA_CONST.__got: 0xbf0
+  __AUTH_CONST.__const: 0x5948
   __AUTH_CONST.__cfstring: 0x7fc0
-  __AUTH_CONST.__objc_const: 0x6358
+  __AUTH_CONST.__objc_const: 0x64e8
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_arrayobj: 0x360
   __AUTH_CONST.__objc_intobj: 0x210
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x1060
-  __AUTH.__objc_data: 0x280
-  __DATA.__objc_ivar: 0x538
+  __AUTH.__objc_data: 0x2d0
+  __DATA.__objc_ivar: 0x54c
   __DATA.__data: 0x3f0
-  __DATA.__bss: 0x1c0
+  __DATA.__bss: 0x1d0
   __DATA.__common: 0x4
   __DATA_DIRTY.__objc_data: 0xfa0
   __DATA_DIRTY.__data: 0x160

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libutil.dylib
-  Functions: 3427
-  Symbols:   6960
-  CStrings:  2613
+  Functions: 3468
+  Symbols:   7059
+  CStrings:  2629
 
Symbols:
+ -[CSBundleFilterEscalatedIdentifiers .cxx_destruct]
+ -[CSBundleFilterEscalatedIdentifiers excludedAppBundleIdentifiers]
+ -[CSBundleFilterEscalatedIdentifiers fileProviderExcludedBundleIDs]
+ -[CSBundleFilterEscalatedIdentifiers hiddenAppBundleIdentifiers]
+ -[CSBundleFilterEscalatedIdentifiers initWithLockedAppBundleIdentifiers:hiddenAppBundleIdentifiers:mdmRestrictedBundleIdentifiers:excludedAppBundleIdentifiers:fileProviderExcludedBundleIDs:]
+ -[CSBundleFilterEscalatedIdentifiers lockedAppBundleIdentifiers]
+ -[CSBundleFilterEscalatedIdentifiers mdmRestrictedBundleIdentifiers]
+ -[MDSearchableIndexService _decodeAttributeBackfillResultForGroup:plistBytes:]
+ -[MDSearchableIndexService _decodeBundleFilterEvaluationRequest:error:]
+ -[MDSearchableIndexService _evaluateFileProviderContainerGroups:excludedBundleIDs:completionHandler:]
+ -[MDSearchableIndexService _mergeFileProviderExcludedBundleIDsForRequest:lockedAppBundleIdentifiers:hiddenAppBundleIdentifiers:excludedAppBundleIdentifiers:]
+ -[MDSearchableIndexService _rejectIfDisallowedBundleID:]
+ -[MDSearchableIndexService _rejectIfNotInternal:reason:]
+ -[MDSearchableIndexService _resolveAttributeBackfillResultsForGroups:completionHandler:]
+ -[MDSearchableIndexService _resolveEscalatedIdentifiersForRequest:]
+ -[MDSearchableIndexService _resolveExcludedAppBundleIdentifiers]
+ -[MDSearchableIndexService _resolveFileProviderAndAttributeBackfillForRequest:escalated:completionHandler:]
+ -[MDSearchableIndexService _resolveHiddenAppBundleIdentifiers]
+ -[MDSearchableIndexService _resolveLockedAppBundleIdentifiers]
+ -[MDSearchableIndexService _resolveMDMRestrictedBundleIdentifiers]
+ -[MDSearchableIndexService _sendBundleFilterEvaluationReply:overConnection:indexID:evaluationReply:attributeBackfillResults:evaluationError:escalated:]
+ -[MDSearchableIndexService _validateAttributeBackfillGroup:]
+ -[MDSearchableIndexService _validateAttributeBackfillGroupsInRequest:]
+ -[MDSearchableIndexService _validateBundleFilterEvaluationRequest:]
+ -[MDSearchableIndexService _validateFileProviderContainerGroup:]
+ -[MDSearchableIndexService _validateFileProviderContainerGroupsInRequest:]
+ -[MDSearchableIndexService evaluateFilters:]
+ GCC_except_table100
+ GCC_except_table119
+ GCC_except_table144
+ GCC_except_table145
+ GCC_except_table146
+ GCC_except_table148
+ GCC_except_table167
+ GCC_except_table168
+ GCC_except_table202
+ GCC_except_table203
+ GCC_except_table204
+ GCC_except_table205
+ GCC_except_table206
+ GCC_except_table207
+ GCC_except_table208
+ GCC_except_table21
+ GCC_except_table211
+ GCC_except_table213
+ GCC_except_table214
+ GCC_except_table215
+ GCC_except_table216
+ GCC_except_table217
+ GCC_except_table218
+ GCC_except_table219
+ GCC_except_table220
+ GCC_except_table221
+ GCC_except_table222
+ GCC_except_table223
+ GCC_except_table224
+ GCC_except_table225
+ GCC_except_table226
+ GCC_except_table227
+ GCC_except_table228
+ GCC_except_table229
+ GCC_except_table230
+ GCC_except_table234
+ OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._excludedAppBundleIdentifiers
+ OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._fileProviderExcludedBundleIDs
+ OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._hiddenAppBundleIdentifiers
+ OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._lockedAppBundleIdentifiers
+ OBJC_IVAR_$_CSBundleFilterEscalatedIdentifiers._mdmRestrictedBundleIdentifiers
+ SPBundleFilterAllowedAttributeBackfillAttributeNames.onceToken
+ SPBundleFilterAllowedAttributeBackfillAttributeNames.sAllowed
+ _MDItemEventSourceBundleIdentifier
+ _MDItemRelatedAppBundleIdentifier
+ _OBJC_CLASS_$_CSBundleFilterAttributeBackfillResult
+ _OBJC_CLASS_$_CSBundleFilterEscalatedIdentifiers
+ _OBJC_CLASS_$_CSBundleFilterEvaluationReply
+ _OBJC_CLASS_$_CSBundleFilterEvaluationRequest
+ _OBJC_METACLASS_$_CSBundleFilterEscalatedIdentifiers
+ __107-[MDSearchableIndexService _resolveFileProviderAndAttributeBackfillForRequest:escalated:completionHandler:]_block_invoke
+ __88-[MDSearchableIndexService _resolveAttributeBackfillResultsForGroups:completionHandler:]_block_invoke
+ __OBJC_$_INSTANCE_METHODS_CSBundleFilterEscalatedIdentifiers
+ __OBJC_$_INSTANCE_VARIABLES_CSBundleFilterEscalatedIdentifiers
+ __OBJC_$_PROP_LIST_CSBundleFilterEscalatedIdentifiers
+ __OBJC_CLASS_RO_$_CSBundleFilterEscalatedIdentifiers
+ __OBJC_METACLASS_RO_$_CSBundleFilterEscalatedIdentifiers
+ ___101-[MDSearchableIndexService _evaluateFileProviderContainerGroups:excludedBundleIDs:completionHandler:]_block_invoke
+ ___107-[MDSearchableIndexService _resolveFileProviderAndAttributeBackfillForRequest:escalated:completionHandler:]_block_invoke
+ ___44-[MDSearchableIndexService evaluateFilters:]_block_invoke
+ ___88-[MDSearchableIndexService _resolveAttributeBackfillResultsForGroups:completionHandler:]_block_invoke
+ ___SPBundleFilterAllowedAttributeBackfillAttributeNames_block_invoke
+ ___block_descriptor_112_e8_32s40s48s56s_e63_v32?0"CSBundleFilterEvaluationReply"8"NSArray"16"NSError"24l
+ ___block_descriptor_48_e8_32s40r_e17_v16?0"NSArray"8l
+ ___block_descriptor_56_e8_32s40r48r_e51_v24?0"CSBundleFilterEvaluationReply"8"NSError"16l
+ ___block_descriptor_80_e8_32s40s48s56s64r72r_e20_v24?08"NSError"16l
+ _objc_msgSend$_decodeAttributeBackfillResultForGroup:plistBytes:
+ _objc_msgSend$_decodeBundleFilterEvaluationRequest:error:
+ _objc_msgSend$_evaluateFileProviderContainerGroups:excludedBundleIDs:completionHandler:
+ _objc_msgSend$_mergeFileProviderExcludedBundleIDsForRequest:lockedAppBundleIdentifiers:hiddenAppBundleIdentifiers:excludedAppBundleIdentifiers:
+ _objc_msgSend$_rejectIfDisallowedBundleID:
+ _objc_msgSend$_rejectIfNotInternal:reason:
+ _objc_msgSend$_resolveAttributeBackfillResultsForGroups:completionHandler:
+ _objc_msgSend$_resolveEscalatedIdentifiersForRequest:
+ _objc_msgSend$_resolveExcludedAppBundleIdentifiers
+ _objc_msgSend$_resolveFileProviderAndAttributeBackfillForRequest:escalated:completionHandler:
+ _objc_msgSend$_resolveHiddenAppBundleIdentifiers
+ _objc_msgSend$_resolveLockedAppBundleIdentifiers
+ _objc_msgSend$_resolveMDMRestrictedBundleIdentifiers
+ _objc_msgSend$_sendBundleFilterEvaluationReply:overConnection:indexID:evaluationReply:attributeBackfillResults:evaluationError:escalated:
+ _objc_msgSend$_validateAttributeBackfillGroup:
+ _objc_msgSend$_validateAttributeBackfillGroupsInRequest:
+ _objc_msgSend$_validateBundleFilterEvaluationRequest:
+ _objc_msgSend$_validateFileProviderContainerGroup:
+ _objc_msgSend$_validateFileProviderContainerGroupsInRequest:
+ _objc_msgSend$abandoned
+ _objc_msgSend$attributeBackfillGroups
+ _objc_msgSend$attributeName
+ _objc_msgSend$evaluateFilters:
+ _objc_msgSend$excludedAppBundleIdentifiers
+ _objc_msgSend$fileProviderContainerGroups
+ _objc_msgSend$fileProviderExcludedBundleIDs
+ _objc_msgSend$fileProviderMatchedIdentifiers
+ _objc_msgSend$fileProviderUnresolvedIdentifiers
+ _objc_msgSend$hiddenAppBundleIdentifiers
+ _objc_msgSend$identifiers
+ _objc_msgSend$initWithBundleID:resolvedValues:confirmedAbsentIdentifiers:
+ _objc_msgSend$initWithFileProviderMatchedIdentifiers:fileProviderUnresolvedIdentifiers:lockedAppBundleIdentifiers:hiddenAppBundleIdentifiers:mdmRestrictedBundleIdentifiers:excludedAppBundleIdentifiers:attributeBackfillResults:
+ _objc_msgSend$initWithLockedAppBundleIdentifiers:hiddenAppBundleIdentifiers:mdmRestrictedBundleIdentifiers:excludedAppBundleIdentifiers:fileProviderExcludedBundleIDs:
+ _objc_msgSend$knownOIDPaths
+ _objc_msgSend$lockedAppBundleIdentifiers
+ _objc_msgSend$mdmRestrictedBundleIdentifiers
+ _objc_msgSend$needsAppProtectionBundleIDs
+ _objc_msgSend$needsExcludedAppBundleIDs
+ _objc_msgSend$needsMDMRestrictedBundleIDs
- GCC_except_table110
- GCC_except_table112
- GCC_except_table120
- GCC_except_table123
- GCC_except_table129
- GCC_except_table131
- GCC_except_table132
- GCC_except_table140
- GCC_except_table141
- GCC_except_table142
- GCC_except_table153
- GCC_except_table155
- GCC_except_table158
- GCC_except_table159
- GCC_except_table169
- GCC_except_table170
- GCC_except_table171
- GCC_except_table172
- GCC_except_table173
- GCC_except_table174
- GCC_except_table175
- GCC_except_table176
- GCC_except_table177
- GCC_except_table178
- GCC_except_table179
- GCC_except_table180
- GCC_except_table181
- GCC_except_table182
- GCC_except_table183
- GCC_except_table184
- GCC_except_table187
- GCC_except_table188
- GCC_except_table193
CStrings:
+ "#apphistory dropping action for %@: attribute set encoding was abandoned"
+ "-[MDSearchableIndexService evaluateFilters:]"
+ "AppProtection bundle IDs"
+ "Attempt to access Mail by client %@"
+ "Excluded Apps bundle IDs"
+ "MDM-restricted bundle IDs"
+ "Non-internal client %@ requested %s"
+ "attribute backfill"
+ "cross-bundle exclusion match"
+ "evaluate-filters-data"
+ "evaluate-filters-data-size"
+ "evaluate_filters"
+ "failed to encode bundle filter evaluation reply %@"
+ "fetchAttributes has no index for protectionClass:%@, bundleID:%@"
+ "v24@?0@\"CSBundleFilterEvaluationReply\"8@\"NSError\"16"
+ "v32@?0@\"CSBundleFilterEvaluationReply\"8@\"NSArray\"16@\"NSError\"24"
```
