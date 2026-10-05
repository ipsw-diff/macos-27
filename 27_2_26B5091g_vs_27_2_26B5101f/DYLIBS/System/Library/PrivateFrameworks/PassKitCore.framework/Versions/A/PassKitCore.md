## PassKitCore

> `/System/Library/PrivateFrameworks/PassKitCore.framework/Versions/A/PassKitCore`

```diff

-1696.2.6.1.0
-  __TEXT.__text: 0x868d50
-  __TEXT.__objc_methlist: 0x701d8
-  __TEXT.__const: 0x18f30
-  __TEXT.__swift5_typeref: 0x7b9a
-  __TEXT.__cstring: 0x6f739
-  __TEXT.__constg_swiftt: 0x6dcc
-  __TEXT.__swift5_reflstr: 0x5cfd
-  __TEXT.__swift5_fieldmd: 0x7370
+1696.2.8.1.0
+  __TEXT.__text: 0x86b394
+  __TEXT.__objc_methlist: 0x70278
+  __TEXT.__const: 0x18fe0
+  __TEXT.__swift5_typeref: 0x7ba2
+  __TEXT.__cstring: 0x6fabc
+  __TEXT.__constg_swiftt: 0x6de8
+  __TEXT.__swift5_reflstr: 0x5d2d
+  __TEXT.__swift5_fieldmd: 0x73b0
   __TEXT.__swift5_builtin: 0x4b0
   __TEXT.__swift5_assocty: 0xba0
-  __TEXT.__swift5_proto: 0x1164
-  __TEXT.__swift5_types: 0x750
-  __TEXT.__swift5_capture: 0x4904
-  __TEXT.__oslogstring: 0x371ad
+  __TEXT.__swift5_proto: 0x116c
+  __TEXT.__swift5_types: 0x754
+  __TEXT.__swift5_capture: 0x4a24
+  __TEXT.__oslogstring: 0x3720c
   __TEXT.__swift_as_entry: 0x158
   __TEXT.__swift_as_ret: 0x16c
   __TEXT.__swift_as_cont: 0x2e8

   __TEXT.__swift5_types2: 0x4
   __TEXT.__gcc_except_tab: 0x6638
   __TEXT.__ustring: 0x1e6c
-  __TEXT.__unwind_info: 0x24988
+  __TEXT.__unwind_info: 0x24a08
   __TEXT.__eh_frame: 0x73d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x12358
+  __DATA_CONST.__const: 0x12428
   __DATA_CONST.__objc_classlist: 0x3d28
   __DATA_CONST.__objc_catlist: 0x110
   __DATA_CONST.__objc_protolist: 0x518
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x23bf8
+  __DATA_CONST.__objc_selrefs: 0x23c48
   __DATA_CONST.__objc_protorefs: 0x210
   __DATA_CONST.__objc_superrefs: 0x3030
   __DATA_CONST.__objc_arraydata: 0x2850
   __DATA_CONST.__got: 0x4920
-  __AUTH_CONST.__const: 0x2f2b8
-  __AUTH_CONST.__cfstring: 0x780a0
-  __AUTH_CONST.__objc_const: 0xcc1b0
+  __AUTH_CONST.__const: 0x2f560
+  __AUTH_CONST.__cfstring: 0x783c0
+  __AUTH_CONST.__objc_const: 0xcc360
   __AUTH_CONST.__objc_arrayobj: 0xd50
   __AUTH_CONST.__objc_intobj: 0x10e0
   __AUTH_CONST.__objc_dictobj: 0x1590
   __AUTH_CONST.__objc_doubleobj: 0x2b0
   __AUTH_CONST.__auth_got: 0x28d0
   __AUTH.__objc_data: 0x1ee48
-  __AUTH.__data: 0x53e0
+  __AUTH.__data: 0x53f0
   __AUTH.__thread_vars: 0x18
   __AUTH.__thread_bss: 0x8
-  __DATA.__objc_ivar: 0x7060
+  __DATA.__objc_ivar: 0x707c
   __DATA.__data: 0x8720
-  __DATA.__bss: 0x21498
+  __DATA.__bss: 0x21598
   __DATA.__common: 0x1d9
-  __DATA_DIRTY.__objc_ivar: 0x1f1c
+  __DATA_DIRTY.__objc_ivar: 0x1f20
   __DATA_DIRTY.__objc_data: 0x8a20
   __DATA_DIRTY.__data: 0x88
   __DATA_DIRTY.__bss: 0x10d0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 53166
-  Symbols:   88685
-  CStrings:  20895
+  Functions: 53209
+  Symbols:   88740
+  CStrings:  20923
 
Symbols:
+ -[PKExistingCardAuthorizationRequestMessage contentType]
+ -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:contentType:analyticsArchivedParentToken:]
+ -[PKPaymentButtonAnalytics _lock_payloadForEvent:error:]
+ -[PKPaymentButtonAnalytics _reportPayload:]
+ -[PKPaymentButtonAnalytics didRenderContent]
+ -[PKPaymentButtonAnalytics reportContentRendered]
+ -[PKPaymentPassAction isTopUpAction]
+ -[PKPaymentRemoteCredential supportsExistingCardAuthorization]
+ -[PKPaymentSetupFieldPickerItem localizedDescriptionStyle]
+ -[PKPaymentSetupFieldPickerItem localizedDescription]
+ -[PKPaymentSetupFieldPickerItem submissionConfirmationActionStyle]
+ -[PKPaymentSetupFieldPickerItem submissionConfirmationActionTitle]
+ -[PKPeerPaymentRequiredFieldsPage headerImageStyle]
+ -[PKPeerPaymentRequiredFieldsPage setHeaderImageStyle:]
+ -[PKSharedPassSharesController _activeUserShare]
+ -[PKSharedPassSharesController sharesCreatedByCurrentUser]
+ OBJC_IVAR_$_PKPaymentButtonAnalytics._didRenderContent
+ OBJC_IVAR_$_PKPaymentButtonAnalytics._lock
+ OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._localizedDescription
+ OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._localizedDescriptionStyle
+ OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._submissionConfirmationActionStyle
+ OBJC_IVAR_$_PKPaymentSetupFieldPickerItem._submissionConfirmationActionTitle
+ OBJC_IVAR_$_PKPeerPaymentRequiredFieldsPage._headerImageStyle
+ _PKAggDKeyApplePayButtonErrorTypeCardArtNotDisplayed
+ _PKAggDKeyApplePayButtonErrorTypeNoEligibleCard
+ _PKAggDKeyApplePayButtonErrorTypePassImageConversionFailed
+ _PKAggDKeyApplePayButtonErrorTypePassLibraryUnavailable
+ _PKAggDKeyApplePayButtonErrorTypePaymentPassLookupFailed
+ _PKAggDKeyApplePayButtonEventTypeContentRendered
+ _PKAnalyticsReportErrorTypeHandoffPaymentFailure
+ _PKAnalyticsReportErrorTypeHandoffUserDismissed
+ _PKAnalyticsReportPeerPaymentKeyboardTapBillSplitButtonTag
+ _PKAnalyticsReportPeerPaymentKeyboardTapButtonTag
+ _PKAnalyticsReportPeerPaymentKeyboardTapOpenButtonTag
+ _PKExistingCardAuthorizationContentTypeKey
+ _PKISO23220_1_PhotoID_ResidentAddressLatinCharacter
+ _PKISO23220_1_PhotoID_ResidentState
+ _PKISO23220_1_PhotoID_ResidentStateLatinCharacter
+ _PKISO23220_1_PhotoID_ResidentStateUnicode
+ _PKISO23220_1_PhotoID_ResidentStreet
+ _PKISO23220_1_PhotoID_ResidentStreetLatinCharacter
+ _PKISO23220_1_PhotoID_ResidentStreetUnicode
+ _PKPaymentFieldPickerItemLocalizedDescriptionStyleKey
+ _PKPaymentFieldPickerItemSubmissionConfirmationActionStyleKey
+ _PKPaymentFieldPickerItemSubmissionConfirmationActionTitleKey
+ _PKPaymentSetupHeaderImageStyleFromString
+ _PKPeerPaymentReceiptMockingEnabled
+ _PKUserGeneratedPassSupported
+ __DoNotUse_PassDesignerOnly_PKPassSecurePreviewContextCreateMessagesPreviewForUnsignedPass
+ ___188-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:contentType:analyticsArchivedParentToken:]_block_invoke
+ ___48-[PKSharedPassSharesController _activeUserShare]_block_invoke
+ ___58-[PKSharedPassSharesController sharesCreatedByCurrentUser]_block_invoke
+ ___58-[PKSharedPassSharesController sharesCreatedByCurrentUser]_block_invoke_2
+ ___block_descriptor_32_e21_B16?0"PKPassShare"8l
+ __swift_closure_destructor.34Tm
+ __swift_closure_destructor.41Tm
+ _associated conformance 11PassKitCore37ProvisioningDeviceTransferContentTypeOSHAASQ
+ _objc_msgSend$_activeUserShare
+ _objc_msgSend$_lock_payloadForEvent:error:
+ _objc_msgSend$_reportPayload:
+ _objc_msgSend$childSharesOfShare:
+ _objc_msgSend$initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:contentType:analyticsArchivedParentToken:
+ _objc_msgSend$isTopUpAction
+ _objc_msgSend$setIsTopUpRequest:
+ _objc_msgSend$setTransferType:
+ _symbolic _____ 11PassKitCore37ProvisioningDeviceTransferContentTypeO
- -[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:analyticsArchivedParentToken:]
- -[PKPaymentButtonAnalytics _recordEvent:]
- -[PKPaymentButtonAnalytics _recordEvent:withError:]
- GCC_except_table86
- _PKAnalyticsReportViewedLineItemKey
- _PKPassSecurePreviewContextCreateMessagesPreviewForUnsignedPass
- ___176-[PKExistingCardAuthorizationRequestMessage initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:analyticsArchivedParentToken:]_block_invoke
- _objc_msgSend$_recordEvent:
- _objc_msgSend$_recordEvent:withError:
- _objc_msgSend$initWithGroupsBySessionIdentifier:destinationDeviceType:destinationDeviceName:selectedCredentialCount:analyticsArchivedParentToken:
- _objc_msgSend$setButtonType:
CStrings:
+ "COULD_NOT_ADD_KEY_TITLE"
+ "PROVISIONING_DEVICE_TRANSFER_GENERIC_ERROR_MESSAGE"
+ "Sharing Capabilities: %{public}@ cannot share, activation state %ld and application state %ld."
+ "com.apple.wallet.ecom.smartButtons.errorType.CardArtNotDisplayed"
+ "com.apple.wallet.ecom.smartButtons.errorType.NoEligibleCard"
+ "com.apple.wallet.ecom.smartButtons.errorType.PassImageConversionFailed"
+ "com.apple.wallet.ecom.smartButtons.errorType.PassLibraryUnavailable"
+ "com.apple.wallet.ecom.smartButtons.errorType.PaymentPassLookupFailed"
+ "com.apple.wallet.ecom.smartButtons.eventType.applePayButtonContentRendered"
+ "contentType"
+ "contentType: '%ld'; "
+ "destructive"
+ "didRenderContent"
+ "didRenderContent: '%@'; "
+ "headerImageStyle"
+ "highlighted"
+ "keyboardTap"
+ "keyboardTapBillSplit"
+ "keyboardTapOpen"
+ "localizedDescriptionStyle"
+ "paymentFailure"
+ "resident_address_latin1"
+ "resident_state_latin1"
+ "resident_state_unicode"
+ "resident_street_latin1"
+ "resident_street_unicode"
+ "submissionConfirmationActionStyle"
+ "submissionConfirmationActionTitle"
+ "userDismissed"
- "viewedLineItem"
```
