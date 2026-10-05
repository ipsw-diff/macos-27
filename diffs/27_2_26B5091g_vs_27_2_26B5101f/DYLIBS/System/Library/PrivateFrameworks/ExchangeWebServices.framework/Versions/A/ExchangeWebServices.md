## ExchangeWebServices

> `/System/Library/PrivateFrameworks/ExchangeWebServices.framework/Versions/A/ExchangeWebServices`

```diff

-846.200.51.0.0
-  __TEXT.__text: 0x41efc
-  __TEXT.__objc_methlist: 0xb258
+846.200.71.0.0
+  __TEXT.__text: 0x425e0
+  __TEXT.__objc_methlist: 0xb308
   __TEXT.__const: 0x1a8
-  __TEXT.__cstring: 0xaa9a
-  __TEXT.__oslogstring: 0x122f
+  __TEXT.__cstring: 0xab43
+  __TEXT.__oslogstring: 0x12c9
   __TEXT.__gcc_except_tab: 0x5f0
-  __TEXT.__unwind_info: 0x17f8
+  __TEXT.__unwind_info: 0x1820
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x2620
+  __DATA_CONST.__const: 0x2628
   __DATA_CONST.__objc_classlist: 0xfa0
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x70
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4018
+  __DATA_CONST.__objc_selrefs: 0x4080
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x458
-  __DATA_CONST.__objc_arraydata: 0x110
+  __DATA_CONST.__objc_arraydata: 0x118
   __DATA_CONST.__got: 0x10f8
-  __AUTH_CONST.__const: 0x740
-  __AUTH_CONST.__cfstring: 0x10a20
-  __AUTH_CONST.__objc_const: 0x49e88
-  __AUTH_CONST.__objc_arrayobj: 0x90
+  __AUTH_CONST.__const: 0x760
+  __AUTH_CONST.__cfstring: 0x10aa0
+  __AUTH_CONST.__objc_const: 0x49f48
+  __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_intobj: 0x90
-  __AUTH_CONST.__auth_got: 0x338
+  __AUTH_CONST.__auth_got: 0x340
   __AUTH.__objc_data: 0x9c40
-  __DATA.__objc_ivar: 0x1018
+  __DATA.__objc_ivar: 0x1028
   __DATA.__data: 0x550
-  __DATA.__bss: 0x270
+  __DATA.__bss: 0x280
   __DATA.__common: 0x8
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/CFNetwork.framework/Versions/A/CFNetwork

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 3295
-  Symbols:   9168
-  CStrings:  2262
+  Functions: 3313
+  Symbols:   9197
+  CStrings:  2269
 
Symbols:
+ +[EWSRetirementAlertPresenter dismissButtonTitle]
+ +[EWSRetirementAlertPresenter learnMoreButtonTitle]
+ +[ExchangeOAuthClient _defaultOIDCScopesForGraphDomain]
+ +[ExchangeOAuthClient defaultResourceForHostURL:]
+ +[ExchangeOAuthTokenRequest log]
+ +[ExchangeOAuthTokenRequest oauthTokenRefreshRequestForTokenRequestURI:clientID:hostURL:isOnPrem:usingGraph:refreshToken:]
+ -[EWSExchangeServiceBindingTask mailboxDenialReason]
+ -[EWSExchangeServiceBindingTask mailboxRequestSucceeded]
+ -[EWSExchangeServiceBindingTask setMailboxDenialReason:]
+ -[EWSExchangeServiceBindingTask setMailboxRequestSucceeded:]
+ -[EWSRetirementAlertAccountSnapshot initWithIdentifier:emailAddress:displayName:inAccountStore:managed:graphCapable:]
+ -[EWSRetirementAlertAccountSnapshot isGraphCapable]
+ -[EWSRetirementAlertConfiguration initWithEnabled:classificationRetryInterval:confirmedLocationRetryInterval:endpointGoneEnabled:explicitRefusalEnabled:denialCountThreshold:denialSpacingInterval:proactiveConfiguration:reactiveConfiguration:]
+ -[EWSRetirementAlertConfiguration isExplicitRefusalEnabled]
+ -[EWSRetirementAlertCoordinator _denialReasonForAccountIdentifier:configuration:simulatedReason:countThreshold:]
+ -[EWSRetirementAlertCoordinator mailboxAccessLostForAccountIdentifier:]
+ -[EWSRetirementAlertCoordinator mailboxDenialReasonIsActionableForAddAccount:]
+ -[EWSRetirementAlertCoordinator mailboxReportingFlags]
+ -[EWSRetirementAlertCoordinator reactiveLearnMoreURLIfActionable]
+ -[EWSRetirementAlertCoordinator recordDenialWithReason:forAccountIdentifier:]
+ GCC_except_table41
+ OBJC_IVAR_$_EWSExchangeServiceBindingTask._mailboxDenialReason
+ OBJC_IVAR_$_EWSExchangeServiceBindingTask._mailboxRequestSucceeded
+ OBJC_IVAR_$_EWSRetirementAlertAccountSnapshot._graphCapable
+ OBJC_IVAR_$_EWSRetirementAlertConfiguration._explicitRefusalEnabled
+ _EWSMailboxRefusalLearnMoreURLKey
+ ___32+[ExchangeOAuthTokenRequest log]_block_invoke
+ __os_log_fault_impl
+ _objc_msgSend$_defaultOIDCScopesForGraphDomain
+ _objc_msgSend$_denialReasonForAccountIdentifier:configuration:simulatedReason:countThreshold:
+ _objc_msgSend$defaultResourceForHostURL:
+ _objc_msgSend$defaultScopeForHostURL:isOnPrem:usingGraph:
+ _objc_msgSend$initWithEnabled:classificationRetryInterval:confirmedLocationRetryInterval:endpointGoneEnabled:explicitRefusalEnabled:denialCountThreshold:denialSpacingInterval:proactiveConfiguration:reactiveConfiguration:
+ _objc_msgSend$isExplicitRefusalEnabled
+ _objc_msgSend$isGraphCapable
+ _objc_msgSend$oauthTokenRefreshRequestForTokenRequestURI:clientID:resource:refreshToken:
+ _objc_msgSend$oauthTokenRefreshRequestForTokenRequestURI:clientID:scope:refreshToken:
+ _objc_msgSend$setMailboxDenialReason:
+ _objc_msgSend$setMailboxRequestSucceeded:
- -[EWSRetirementAlertAccountSnapshot initWithIdentifier:emailAddress:displayName:inAccountStore:managed:]
- -[EWSRetirementAlertConfiguration initWithEnabled:classificationRetryInterval:confirmedLocationRetryInterval:endpointGoneEnabled:denialCountThreshold:denialSpacingInterval:proactiveConfiguration:reactiveConfiguration:]
- -[EWSRetirementAlertCoordinator _denialReasonForAccountIdentifier:configuration:simulatedReason:]
- -[EWSRetirementAlertCoordinator alertsSuppressedForAccountIdentifier:managed:]
- -[EWSRetirementAlertCoordinator mailboxReportingFlagsForAccountIdentifier:managed:]
- -[EWSRetirementAlertCoordinator recordDenialWithReason:forAccountIdentifier:managed:]
- GCC_except_table38
- _objc_msgSend$_denialReasonForAccountIdentifier:configuration:simulatedReason:
- _objc_msgSend$alertsSuppressedForAccountIdentifier:managed:
- _objc_msgSend$initWithEnabled:classificationRetryInterval:confirmedLocationRetryInterval:endpointGoneEnabled:denialCountThreshold:denialSpacingInterval:proactiveConfiguration:reactiveConfiguration:
CStrings:
+ "%@://%@/"
+ "Cannot build on-prem OAuth refresh request: hostURL is nil."
+ "EWSMailboxRefusalLearnMoreURL"
+ "ExchangeOAuthTokenRequest"
+ "ExplicitRefusalEnabled"
+ "On-prem account also flagged usingGraph; hostURL may be a Graph endpoint, not an on-prem host"
+ "https://support.apple.com/149092?cid=mc-ols-tbd-article_149092-ui_link-62027190"
```
