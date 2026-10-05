## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices`

```diff

-10.1.13.1.1
-  __TEXT.__text: 0x8e1828
+10.1.17.0.0
+  __TEXT.__text: 0x8e6be8
   __TEXT.__lazy_helpers: 0x2e98
-  __TEXT.__objc_methlist: 0x245ac
-  __TEXT.__const: 0xbad50
+  __TEXT.__objc_methlist: 0x24704
+  __TEXT.__const: 0xbb080
   __TEXT.__dlopen_cstrs: 0x834
-  __TEXT.__cstring: 0x2cac8
-  __TEXT.__swift5_typeref: 0x7a13
-  __TEXT.__swift5_reflstr: 0x41ce
-  __TEXT.__swift5_assocty: 0xfd8
-  __TEXT.__constg_swiftt: 0x5ccc
+  __TEXT.__cstring: 0x2cd60
+  __TEXT.__swift5_typeref: 0x7aa7
+  __TEXT.__swift5_reflstr: 0x42be
+  __TEXT.__swift5_assocty: 0xfc0
+  __TEXT.__constg_swiftt: 0x5d88
   __TEXT.__swift5_builtin: 0x3e8
-  __TEXT.__swift5_fieldmd: 0x5940
-  __TEXT.__swift5_proto: 0x1258
-  __TEXT.__swift5_types: 0x708
+  __TEXT.__swift5_fieldmd: 0x5a4c
+  __TEXT.__swift5_proto: 0x126c
+  __TEXT.__swift5_types: 0x720
   __TEXT.__swift_as_entry: 0x8d8
-  __TEXT.__swift_as_ret: 0xa60
-  __TEXT.__swift_as_cont: 0x13cc
-  __TEXT.__swift5_capture: 0x4188
+  __TEXT.__swift_as_ret: 0xa64
+  __TEXT.__swift_as_cont: 0x1400
+  __TEXT.__swift5_capture: 0x41ec
   __TEXT.__swift5_mpenum: 0x9c
   __TEXT.__swift5_protos: 0x120
-  __TEXT.__oslogstring: 0x314d5
-  __TEXT.__gcc_except_tab: 0x5358
+  __TEXT.__oslogstring: 0x317bf
+  __TEXT.__gcc_except_tab: 0x53a0
   __TEXT.__ustring: 0x262
-  __TEXT.__unwind_info: 0x16858
-  __TEXT.__eh_frame: 0x184c4
+  __TEXT.__unwind_info: 0x173d8
+  __TEXT.__eh_frame: 0x18634
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x5d68
-  __DATA_CONST.__objc_classlist: 0x15f0
+  __DATA_CONST.__const: 0x5d78
+  __DATA_CONST.__objc_classlist: 0x15f8
   __DATA_CONST.__objc_catlist: 0xe8
-  __DATA_CONST.__objc_protolist: 0x4a8
+  __DATA_CONST.__objc_protolist: 0x4b0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xfe58
-  __DATA_CONST.__objc_protorefs: 0x270
+  __DATA_CONST.__objc_selrefs: 0xff30
+  __DATA_CONST.__objc_protorefs: 0x278
   __DATA_CONST.__objc_superrefs: 0xcf8
   __DATA_CONST.__objc_arraydata: 0x498
-  __DATA_CONST.__got: 0x1a38
-  __AUTH_CONST.__const: 0x45210
-  __AUTH_CONST.__cfstring: 0x23640
-  __AUTH_CONST.__objc_const: 0x3fee8
+  __DATA_CONST.__got: 0x1a48
+  __AUTH_CONST.__const: 0x45830
+  __AUTH_CONST.__cfstring: 0x237a0
+  __AUTH_CONST.__objc_const: 0x3ff48
   __AUTH_CONST.__lazy_load_got: 0x460
   __AUTH_CONST.__objc_intobj: 0xc60
   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0x2440
-  __AUTH.__objc_data: 0x9988
-  __AUTH.__data: 0x2c50
-  __DATA.__objc_ivar: 0x1a68
-  __DATA.__data: 0x7e30
-  __DATA.__bss: 0x1c6d8
+  __AUTH_CONST.__auth_got: 0x2460
+  __AUTH.__objc_data: 0x99f8
+  __AUTH.__data: 0x2c80
+  __DATA.__objc_ivar: 0x1a60
+  __DATA.__data: 0x7e40
+  __DATA.__bss: 0x1c958
   __DATA.__common: 0x1520
   __DATA_DIRTY.__objc_ivar: 0x6e4
-  __DATA_DIRTY.__objc_data: 0x6058
-  __DATA_DIRTY.__data: 0x320c
+  __DATA_DIRTY.__objc_data: 0x6048
+  __DATA_DIRTY.__data: 0x31fc
   __DATA_DIRTY.__bss: 0x63b0
   __DATA_DIRTY.__common: 0x90
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 29831
-  Symbols:   32486
-  CStrings:  8954
+  Functions: 30014
+  Symbols:   32559
+  CStrings:  8978
 
Symbols:
+ +[AMSData contentTypeForEncoding:]
+ +[AMSDevice frontCameraOffsetFromCenterOfDisplayAtIndex:]
+ +[AMSFinancePaymentSheetResponse _preloadPromiseForSalableIconURL:activePurchaseTask:logKey:]
+ +[AMSProcessInfo attributionBundleIdentifierForProxyAppBundleID:hasAttributionEntitlement:]
+ +[AMSProcessInfo hasNetworkAttributionEntitlement]
+ +[AMSPurchaseRequestEncoder shouldCompressRequestPropertiesUsingBag:]
+ +[AMSTreatmentStore isExcludedTreatmentStoreError:]
+ +[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespace:bag:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]
+ +[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]
+ +[AMSURLSession _configurationForClientInfo:]
+ +[NSURLSessionConfiguration(AppleMediaServices_Project) ams_defaultConfiguration]
+ -[AMSFollowUp _activeMediaAccountDSID]
+ -[AMSFollowUp _clearGroupedHardwareFollowUpsForOtherAccounts:groupingDSID:]
+ -[AMSFollowUp _isEligibleForGroupedHardwareOffer:]
+ -[AMSMediaSharedProperties _initWithClientIdentifier:sessionCacheKey:account:bag:clientInfo:URLKnownToBeTrusted:URLSessionConfiguration:]
+ -[AMSMediaSharedProperties sessionCacheKey]
+ -[AMSTreatmentStore _encodeExperimentData:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore _reportFailureToMetrics:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore _reportPropagatedFailureToMetrics:failureReason:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore activeTreatmentsForAreas:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore areasForNamespaces:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore areasForTopics:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore areasWithIDs:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore encodeExperimentDataForTopic:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore experimentDataForAreas:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]
+ -[AMSTreatmentStore treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]
+ -[AMSURLRequestEncoder reportsTreatmentErrorsToMetrics]
+ -[AMSURLRequestEncoder setReportsTreatmentErrorsToMetrics:]
+ -[AMSURLRequestProperties initWithLogUUID:]
+ -[NSMutableURLRequest(AppleMediaServices) ams_addProductTypeHeader]
+ -[NSMutableURLRequest(AppleMediaServices) ams_compressBodyWithLogUUID:loggingFor:]
+ OBJC_IVAR_$_AMSMediaSharedProperties._sessionCacheKey
+ OBJC_IVAR_$_AMSURLRequestEncoder._reportsTreatmentErrorsToMetrics
+ _AMSBagKeyPurchaseRequestCompressionEnabled
+ _MGCopyAnswerForDisplayAtIndex
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_deviceSupportsSecureDoubleClick
+ _MobileGestalt_get_touchIDCapability
+ _OBJC_CLASS_$_AMSRequestBody
+ _OBJC_METACLASS_$_AMSRequestBody
+ __111-[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]_block_invoke
+ __115-[AMSTreatmentStore treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]_block_invoke
+ __137+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]_block_invoke
+ __137+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]_block_invoke_2
+ __57-[AMSTreatmentStore areasWithIDs:reportsErrorsToMetrics:]_block_invoke
+ __59-[AMSTreatmentStore areasForTopics:reportsErrorsToMetrics:]_block_invoke
+ __63-[AMSTreatmentStore areasForNamespaces:reportsErrorsToMetrics:]_block_invoke
+ __75-[AMSFollowUp _clearGroupedHardwareFollowUpsForOtherAccounts:groupingDSID:]_block_invoke
+ __CLASS_METHODS_AMSRequestBody
+ __DATA_AMSRequestBody
+ __INSTANCE_METHODS_AMSRequestBody
+ __IVARS_AMSRequestBody
+ __METACLASS_DATA_AMSRequestBody
+ __PROPERTIES_AMSRequestBody
+ __PROTOCOL_INSTANCE_METHODS__TtP18AppleMediaServices36SelfieAuthenticationServiceInterface_
+ __PROTOCOL_METHOD_TYPES__TtP18AppleMediaServices36SelfieAuthenticationServiceInterface_
+ __PROTOCOL__TtP18AppleMediaServices36SelfieAuthenticationServiceInterface_
+ ___101-[AMSTreatmentStore experimentDataForAreas:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]_block_invoke
+ ___103-[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]_block_invoke
+ ___103-[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]_block_invoke_2
+ ___107-[AMSTreatmentStore encodeExperimentDataForTopic:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]_block_invoke
+ ___107-[AMSTreatmentStore encodeExperimentDataForTopic:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]_block_invoke_2
+ ___111-[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]_block_invoke
+ ___115-[AMSTreatmentStore treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]_block_invoke
+ ___115-[AMSTreatmentStore treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]_block_invoke_2
+ ___115-[AMSTreatmentStore treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:]_block_invoke_3
+ ___137+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]_block_invoke
+ ___137+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]_block_invoke_2
+ ___140+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespace:bag:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:]_block_invoke
+ ___54-[AMSPurchaseRequestEncoder initWithPurchaseInfo:bag:]_block_invoke
+ ___57-[AMSTreatmentStore areasWithIDs:reportsErrorsToMetrics:]_block_invoke
+ ___57-[AMSTreatmentStore areasWithIDs:reportsErrorsToMetrics:]_block_invoke_2
+ ___57-[AMSTreatmentStore areasWithIDs:reportsErrorsToMetrics:]_block_invoke_3
+ ___57-[AMSTreatmentStore areasWithIDs:reportsErrorsToMetrics:]_block_invoke_4
+ ___59-[AMSTreatmentStore areasForTopics:reportsErrorsToMetrics:]_block_invoke
+ ___59-[AMSTreatmentStore areasForTopics:reportsErrorsToMetrics:]_block_invoke_2
+ ___59-[AMSTreatmentStore areasForTopics:reportsErrorsToMetrics:]_block_invoke_3
+ ___59-[AMSTreatmentStore areasForTopics:reportsErrorsToMetrics:]_block_invoke_4
+ ___63-[AMSTreatmentStore areasForNamespaces:reportsErrorsToMetrics:]_block_invoke
+ ___63-[AMSTreatmentStore areasForNamespaces:reportsErrorsToMetrics:]_block_invoke_2
+ ___69+[AMSPurchaseRequestEncoder shouldCompressRequestPropertiesUsingBag:]_block_invoke
+ ___75-[AMSFollowUp _clearGroupedHardwareFollowUpsForOtherAccounts:groupingDSID:]_block_invoke
+ ___92-[AMSPurchaseProtocolHandler reconfigureNewRequest:originalTask:redirect:completionHandler:]_block_invoke_2
+ ___93+[AMSFinancePaymentSheetResponse _preloadPromiseForSalableIconURL:activePurchaseTask:logKey:]_block_invoke
+ ___block_descriptor_105_e8_32s40s48s56s64s72s80s88r_e5_v8?0l
+ ___block_descriptor_40_e46_"AMSPromise"24?0"AMSURLResult"8"NSError"16l
+ ___block_descriptor_40_e8_32s_e20_v16?0"AMSBoolean"8l
+ ___block_descriptor_40_e8_32s_e24_B16?0"FLFollowUpItem"8l
+ ___block_descriptor_41_e8_32s_e17_v16?0"NSError"8l
+ ___block_descriptor_48_e8_32s40bs_e34_v24?0"AMSURLAction"8"NSError"16l
+ ___block_descriptor_49_e8_32s40s_e17_v16?0"NSError"8l
+ ___block_descriptor_57_e8_32s40s48s_e33_"AMSPromise"16?0"AMSOptional"8l
+ ___block_descriptor_65_e8_32s40s48bs_e46_"AMSPromise"24?0"NSDictionary"8"NSError"16l
+ ___block_descriptor_65_e8_32s40s48s56bs_e32_v24?0"AMSBoolean"8"NSError"16l
+ ___block_descriptor_65_e8_32s40s48s56s_e34_"AMSPromise"16?0"NSDictionary"8l
+ ___block_descriptor_65_e8_32s40s48s_e34_"AMSPromise"16?0"NSDictionary"8l
+ ___block_descriptor_73_e8_32s40s48s56bs_e46_"AMSPromise"24?0"NSDictionary"8"NSError"16l
+ ___block_descriptor_73_e8_32s40s48s56s64bs_e20_v20?0B8"NSError"12l
+ __swift_closure_destructor.24Tm
+ __swift_closure_destructor.49Tm
+ _associated conformance 10Foundation4DateV18AppleMediaServicesE24ISO8601UTCTimeZoneFormatOSHADSQ
+ _associated conformance 10Foundation4DateV18AppleMediaServicesE26ISO8601LocalTimeZoneFormatOSHADSQ
+ _get_enum_tag_for_layout_string 18AppleMediaServices15RequestBodyCoreO8EncodingO
+ _kMGDisplayIndexedQueryFrontCameraOffsetFromDisplayCenter
+ _objc_msgSend$_activeMediaAccountDSID
+ _objc_msgSend$_clearGroupedHardwareFollowUpsForOtherAccounts:groupingDSID:
+ _objc_msgSend$_configurationForClientInfo:
+ _objc_msgSend$_encodeExperimentData:reportsErrorsToMetrics:
+ _objc_msgSend$_initWithClientIdentifier:sessionCacheKey:account:bag:clientInfo:URLKnownToBeTrusted:URLSessionConfiguration:
+ _objc_msgSend$_isEligibleForGroupedHardwareOffer:
+ _objc_msgSend$_preloadPromiseForSalableIconURL:activePurchaseTask:logKey:
+ _objc_msgSend$_reportFailureToMetrics:reportsErrorsToMetrics:
+ _objc_msgSend$_reportPropagatedFailureToMetrics:failureReason:reportsErrorsToMetrics:
+ _objc_msgSend$activeTreatmentsForAreas:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:
+ _objc_msgSend$activeTreatmentsForAreas:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:
+ _objc_msgSend$activeTreatmentsForAreas:userId:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:
+ _objc_msgSend$addTreatmentHeadersToRequest:forTreatmentNamespace:bag:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:
+ _objc_msgSend$addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:reportsErrorsToMetrics:
+ _objc_msgSend$ams_addProductTypeHeader
+ _objc_msgSend$ams_compressBodyWithLogUUID:loggingFor:
+ _objc_msgSend$ams_defaultConfiguration
+ _objc_msgSend$apply:to:
+ _objc_msgSend$areasForNamespaces:reportsErrorsToMetrics:
+ _objc_msgSend$areasForTopics:reportsErrorsToMetrics:
+ _objc_msgSend$areasWithIDs:reportsErrorsToMetrics:
+ _objc_msgSend$attributionBundleIdentifierForProxyAppBundleID:hasAttributionEntitlement:
+ _objc_msgSend$contentTypeForEncoding:
+ _objc_msgSend$encodeExperimentDataForTopic:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:
+ _objc_msgSend$experimentDataForAreas:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:
+ _objc_msgSend$extractFrom:
+ _objc_msgSend$gzippedWith:
+ _objc_msgSend$hasNetworkAttributionEntitlement
+ _objc_msgSend$initWithData:contentType:
+ _objc_msgSend$initWithLogUUID:
+ _objc_msgSend$isExcludedTreatmentStoreError:
+ _objc_msgSend$methodCarriesBody:
+ _objc_msgSend$performBiometricAuthenticationWithReply:
+ _objc_msgSend$reportsTreatmentErrorsToMetrics
+ _objc_msgSend$sessionCacheKey
+ _objc_msgSend$setReportsTreatmentErrorsToMetrics:
+ _objc_msgSend$shouldCompressRequest:
+ _objc_msgSend$shouldCompressRequestPropertiesUsingBag:
+ _objc_msgSend$treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:reportsErrorsToMetrics:
+ _symbolic $s18AppleMediaServices36SelfieAuthenticationServiceInterfaceP
+ _symbolic ScCySb______pG s5ErrorP
+ _symbolic ScCy_____Sg_____G 18AppleMediaServices20AutoBugCaptureReportC8Reporter33_53E9BFD2965C81AFBEDE880E2C1BF3BALLV s5NeverO
+ _symbolic _____ 10Foundation4DateV18AppleMediaServicesE24ISO8601UTCTimeZoneFormatO
+ _symbolic _____ 10Foundation4DateV18AppleMediaServicesE26ISO8601LocalTimeZoneFormatO
+ _symbolic _____ 18AppleMediaServices15RequestBodyCoreO
+ _symbolic _____ 18AppleMediaServices15RequestBodyCoreO0E0V
+ _symbolic _____ 18AppleMediaServices15RequestBodyCoreO8EncodingO
+ _symbolic _____ 18AppleMediaServices20AutoBugCaptureReportC8Reporter33_53E9BFD2965C81AFBEDE880E2C1BF3BALLV
+ _symbolic _____Sg 18AppleMediaServices20AutoBugCaptureReportC8Reporter33_53E9BFD2965C81AFBEDE880E2C1BF3BALLV
+ _type_layout_string 18AppleMediaServices15RequestBodyCoreO0E0V
+ _type_layout_string 18AppleMediaServices15RequestBodyCoreO8EncodingO
+ _type_layout_string 18AppleMediaServices20AutoBugCaptureReportC8Reporter33_53E9BFD2965C81AFBEDE880E2C1BF3BALLV
- +[AMSProcessInfo attributionBundleIdentifierForProxyAppBundleID:hasImpersonateEntitlement:]
- +[AMSProcessInfo hasNetworkImpersonationEntitlement]
- +[AMSURLSession _defaultConfiguration]
- -[AMSFinanceActionResponse _runAction:completionHandler:]
- -[AMSFinanceActionResponse asyncQueue]
- -[AMSFinanceActionResponse detached]
- -[AMSFinanceActionResponse setAsyncQueue:]
- -[AMSFinanceActionResponse setDetached:]
- -[AMSFinanceDialogResponse asyncQueue]
- -[AMSFinanceDialogResponse detached]
- -[AMSFinanceDialogResponse setAsyncQueue:]
- -[AMSFinanceDialogResponse setDetached:]
- -[AMSMediaSharedProperties _initWithClientIdentifier:account:bag:clientInfo:URLKnownToBeTrusted:URLSessionConfiguration:]
- -[AMSTreatmentStore _encodeExperimentData:]
- -[NSMutableURLRequest(AppleMediaServices) ams_addContentLengthHeaderForData:]
- -[NSMutableURLRequest(AppleMediaServices) ams_addContentTypeHeaderForEncoding:]
- OBJC_IVAR_$_AMSFinanceActionResponse._asyncQueue
- OBJC_IVAR_$_AMSFinanceActionResponse._detached
- OBJC_IVAR_$_AMSFinanceDialogResponse._asyncQueue
- OBJC_IVAR_$_AMSFinanceDialogResponse._detached
- __114+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:]_block_invoke
- __114+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:]_block_invoke_2
- __34-[AMSTreatmentStore areasWithIDs:]_block_invoke
- __36-[AMSTreatmentStore areasForTopics:]_block_invoke
- __40-[AMSTreatmentStore areasForNamespaces:]_block_invoke
- __66-[AMSFinanceDialogResponse performWithTaskInfo:completionHandler:]_block_invoke
- __88-[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifierProvider:]_block_invoke
- __92-[AMSTreatmentStore treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:]_block_invoke
- ___114+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:]_block_invoke
- ___114+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:]_block_invoke_2
- ___117+[AMSURLRequestDecoration addTreatmentHeadersToRequest:forTreatmentNamespace:bag:canonicalAccountIdentifierProvider:]_block_invoke
- ___34-[AMSTreatmentStore areasWithIDs:]_block_invoke
- ___34-[AMSTreatmentStore areasWithIDs:]_block_invoke_2
- ___34-[AMSTreatmentStore areasWithIDs:]_block_invoke_3
- ___34-[AMSTreatmentStore areasWithIDs:]_block_invoke_4
- ___36-[AMSTreatmentStore areasForTopics:]_block_invoke
- ___36-[AMSTreatmentStore areasForTopics:]_block_invoke_2
- ___36-[AMSTreatmentStore areasForTopics:]_block_invoke_3
- ___36-[AMSTreatmentStore areasForTopics:]_block_invoke_4
- ___40-[AMSTreatmentStore areasForNamespaces:]_block_invoke
- ___40-[AMSTreatmentStore areasForNamespaces:]_block_invoke_2
- ___57-[AMSFinanceActionResponse _runAction:completionHandler:]_block_invoke
- ___66-[AMSFinanceActionResponse performWithTaskInfo:completionHandler:]_block_invoke_2
- ___78-[AMSTreatmentStore experimentDataForAreas:userId:canonicalAccountIdentifier:]_block_invoke
- ___80-[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifier:]_block_invoke
- ___80-[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifier:]_block_invoke_2
- ___84-[AMSTreatmentStore encodeExperimentDataForTopic:userId:canonicalAccountIdentifier:]_block_invoke
- ___84-[AMSTreatmentStore encodeExperimentDataForTopic:userId:canonicalAccountIdentifier:]_block_invoke_2
- ___88-[AMSTreatmentStore activeTreatmentsForAreas:userId:canonicalAccountIdentifierProvider:]_block_invoke
- ___92-[AMSTreatmentStore treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:]_block_invoke
- ___92-[AMSTreatmentStore treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:]_block_invoke_2
- ___92-[AMSTreatmentStore treatmentsForAreas:startDate:endDate:userId:canonicalAccountIdentifier:]_block_invoke_3
- ___block_descriptor_32_e22_v16?0"AMSURLAction"8l
- ___block_descriptor_40_e8_32bs_e34_v24?0"AMSURLAction"8"NSError"16l
- ___block_descriptor_56_e8_32s40s48s_e33_"AMSPromise"16?0"AMSOptional"8l
- ___block_descriptor_64_e8_32s40s48bs_e46_"AMSPromise"24?0"NSDictionary"8"NSError"16l
- ___block_descriptor_64_e8_32s40s48s56s_e34_"AMSPromise"16?0"NSDictionary"8l
- ___block_descriptor_64_e8_32s40s48s_e34_"AMSPromise"16?0"NSDictionary"8l
- ___block_descriptor_65_e8_32s40s48s56bs_e20_v20?0B8"NSError"12l
- ___block_descriptor_72_e8_32s40s48s56bs_e46_"AMSPromise"24?0"NSDictionary"8"NSError"16l
- ___block_descriptor_97_e8_32s40s48s56s64s72s80r_e5_v8?0l
- ___copy_helper_block_e8_32s40s48s56s64s72s80r
- ___destroy_helper_block_e8_32s40s48s56s64s72s80r
- __swift_closure_destructor.20Tm
- __swift_closure_destructor.41Tm
- _objc_msgSend$_defaultConfiguration
- _objc_msgSend$_encodeExperimentData:
- _objc_msgSend$_initWithClientIdentifier:account:bag:clientInfo:URLKnownToBeTrusted:URLSessionConfiguration:
- _objc_msgSend$_runAction:completionHandler:
- _objc_msgSend$activeTreatmentsForAreas:canonicalAccountIdentifierProvider:
- _objc_msgSend$activeTreatmentsForAreas:userId:canonicalAccountIdentifierProvider:
- _objc_msgSend$addTreatmentHeadersToRequest:forTreatmentNamespace:bag:canonicalAccountIdentifierProvider:
- _objc_msgSend$addTreatmentHeadersToRequest:forTreatmentNamespaces:canonicalAccountIdentifierProvider:
- _objc_msgSend$ams_addContentLengthHeaderForData:
- _objc_msgSend$ams_addContentTypeHeaderForEncoding:
- _objc_msgSend$areasForNamespaces:
- _objc_msgSend$areasForTopics:
- _objc_msgSend$areasWithIDs:
- _objc_msgSend$asyncQueue
- _objc_msgSend$attributionBundleIdentifierForProxyAppBundleID:hasImpersonateEntitlement:
- _objc_msgSend$detached
- _objc_msgSend$hasNetworkImpersonationEntitlement
- _objc_msgSend$setDetached:
- _objc_msgSend$set_infersDiscretionaryFromOriginatingClient:
- _symbolic _____Sg 18AppleMediaServices30AutoBugCaptureCallbackDelegate33_53E9BFD2965C81AFBEDE880E2C1BF3BALLC
CStrings:
+ "%{public}@: Dropping hardware offer follow up %{public}@: its account is not the active Media account."
+ "%{public}@: Migration: Failed to clear grouped hardware follow ups belonging to other accounts. Error: %@"
+ "%{public}@: Migration: No active iTunes account. Leaving hardware follow ups as they are."
+ "%{public}@: Migration: clearing grouped hardware follow ups belonging to other accounts: %@"
+ "%{public}@: No grouped hardware offer follow up with identifier %{public}@"
+ "%{public}@: [%{public}@] Failed to obtain front camera offset for display %{public}ld: %{public}d"
+ "%{public}@: [%{public}@] Failed to resolve the canonical account identifier (error: %{public}@)"
+ "%{public}@: [%{public}@] Nil clientIdentifier; every such caller shares one session cache entry"
+ "%{public}@Unable to compress request body. Using uncompressed body. error = %{public}@"
+ "AppleMediaServices_BridgedInterface.RequestBody"
+ "Failed to fetch area identifiers for namespaces"
+ "Failed to fetch area identifiers for topics"
+ "Failed to fetch areas"
+ "Failed to fetch treatments"
+ "Failed to resolve the canonical account identifier"
+ "Failed to synchronize treatments"
+ "Grouped hardware offers are only shown for the active Media account"
+ "Inactive Account"
+ "PassLibraryCacheWarming"
+ "Pre-evaluation failed: neither FaceID nor TouchID-with-intent constraints were satisfied"
+ "Pre-evaluation failed: passcode is not the sole alternative to the conjunction"
+ "Pre-evaluation failed: signing is not a TouchID and button press conjunction"
+ "PreloadSalableIconAtKnownURL"
+ "TreatmentStoreErrorMetrics"
+ "Treatments"
+ "X-Apple-Product-Type"
+ "com.apple.private.network.socket-delegate"
+ "performBiometricAuthentication()"
+ "purchase-request-compression-enabled"
+ "touchIDWithUserIntent"
+ "treatments"
+ "v16@?0@\"AMSBoolean\"8"
- "%{public}@Failed to gzip request body. error = %{public}@"
- "%{public}@Unable to compress request body. Using uncompressed body."
- "CompressPurchaseRequestBodies"
- "Pre-evaluation failed: FaceID constraints not satisfied"
- "com.apple.AMSFinanceActionResponse"
- "com.apple.AMSFinanceDialogResponse"
- "com.apple.private.nsurlsession.impersonate"
- "detached"
```
