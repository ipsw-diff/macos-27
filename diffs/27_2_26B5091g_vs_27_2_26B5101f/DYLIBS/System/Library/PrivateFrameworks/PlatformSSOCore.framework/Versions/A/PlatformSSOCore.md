## PlatformSSOCore

> `/System/Library/PrivateFrameworks/PlatformSSOCore.framework/Versions/A/PlatformSSOCore`

```diff

-643.40.27.0.0
-  __TEXT.__text: 0xfe7f0
-  __TEXT.__objc_methlist: 0x7400
+643.40.34.0.0
+  __TEXT.__text: 0x1006fc
+  __TEXT.__objc_methlist: 0x7468
   __TEXT.__const: 0x3540
-  __TEXT.__cstring: 0xf937
-  __TEXT.__oslogstring: 0x6dbc
+  __TEXT.__cstring: 0xfd67
+  __TEXT.__oslogstring: 0x719c
+  __TEXT.__ustring: 0x2c
   __TEXT.__gcc_except_tab: 0x1144
   __TEXT.__dlopen_cstrs: 0x363
   __TEXT.__swift5_typeref: 0x694
-  __TEXT.__constg_swiftt: 0xbfc
+  __TEXT.__constg_swiftt: 0xc04
   __TEXT.__swift5_reflstr: 0x98a
   __TEXT.__swift5_fieldmd: 0x9f0
   __TEXT.__swift5_builtin: 0xb4

   __TEXT.__swift_as_cont: 0x118
   __TEXT.__swift5_protos: 0x18
   __TEXT.__swift5_mpenum: 0x48
-  __TEXT.__unwind_info: 0x4860
-  __TEXT.__eh_frame: 0x20d8
+  __TEXT.__unwind_info: 0x48e0
+  __TEXT.__eh_frame: 0x2100
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1fa8
+  __DATA_CONST.__const: 0x1fb0
   __DATA_CONST.__objc_classlist: 0x580
   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xa8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x38b0
+  __DATA_CONST.__objc_selrefs: 0x3930
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0x238
-  __DATA_CONST.__objc_arraydata: 0x68
-  __DATA_CONST.__got: 0xb90
-  __AUTH_CONST.__const: 0x2ec8
-  __AUTH_CONST.__cfstring: 0x8cc0
-  __AUTH_CONST.__objc_const: 0x17c50
-  __AUTH_CONST.__objc_intobj: 0x288
+  __DATA_CONST.__objc_arraydata: 0x130
+  __DATA_CONST.__got: 0xba0
+  __AUTH_CONST.__const: 0x2f78
+  __AUTH_CONST.__cfstring: 0x9160
+  __AUTH_CONST.__objc_const: 0x17c70
+  __AUTH_CONST.__objc_intobj: 0x2a0
   __AUTH_CONST.__objc_doubleobj: 0x60
-  __AUTH_CONST.__objc_arrayobj: 0x90
+  __AUTH_CONST.__objc_arrayobj: 0xa8
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x10c0
   __AUTH.__objc_data: 0x34d8
-  __AUTH.__data: 0x948
+  __AUTH.__data: 0x958
   __DATA.__objc_ivar: 0x728
-  __DATA.__data: 0x1538
-  __DATA.__bss: 0x1790
+  __DATA.__data: 0x1528
+  __DATA.__bss: 0x17d0
   __DATA.__common: 0x89
   __DATA_DIRTY.__objc_data: 0x6e0
   __DATA_DIRTY.__bss: 0x140

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 5782
-  Symbols:   8925
-  CStrings:  2701
+  Functions: 5814
+  Symbols:   8973
+  CStrings:  2753
 
Symbols:
+ +[POConstantCoreUtil validatedAdditionalHTTPHeaders:]
+ -[POAuthenticationProcess addAdditionalHTTPHeadersToRequest:context:]
+ -[PODeviceConfiguration additionalHTTPHeaders]
+ -[PODeviceConfiguration setAdditionalHTTPHeaders:]
+ -[POLoginProcessBase biometricPolicyIsUnsatisfied:]
+ -[POLoginProcessBase hasVerifiedBiometricContext]
+ -[POLoginProcessBase isNewAccountPendingRegistration]
+ -[POLoginProcessBase isUserCreatedDuringSetupAssistant]
+ -[POLoginProcessBase isWithinAuthenticationGracePeriod:]
+ GCC_except_table140
+ GCC_except_table165
+ GCC_except_table62
+ OBJC_IVAR_$_PODeviceConfiguration._additionalHTTPHeaders
+ POIsReservedHTTPHeaderField.onceToken
+ POIsReservedHTTPHeaderField.reservedFields
+ POIsValidHTTPHeaderFieldName.illegalFieldCharacters
+ POIsValidHTTPHeaderFieldName.onceToken
+ POIsValidHTTPHeaderFieldValue.illegalValueCharacters
+ POIsValidHTTPHeaderFieldValue.onceToken
+ PO_LOG_POConstantCoreUtil
+ PO_LOG_POConstantCoreUtil.log
+ PO_LOG_POConstantCoreUtil.once
+ _OBJC_CLASS_$_NSCountedSet
+ _OBJC_CLASS_$_TKCTKDConnection
+ _PO_LOG_POConstantCoreUtil
+ __48-[PODeviceConfiguration setDeviceEncryptionKey:]_block_invoke
+ __53+[POConstantCoreUtil validatedAdditionalHTTPHeaders:]_block_invoke
+ __69-[POAuthenticationProcess addAdditionalHTTPHeadersToRequest:context:]_block_invoke
+ ___53+[POConstantCoreUtil validatedAdditionalHTTPHeaders:]_block_invoke
+ ___69-[POAuthenticationProcess addAdditionalHTTPHeadersToRequest:context:]_block_invoke
+ ___POAdditionalHTTPHeadersForDisplay_block_invoke
+ ___POIsReservedHTTPHeaderField_block_invoke
+ ___POIsValidHTTPHeaderFieldName_block_invoke
+ ___POIsValidHTTPHeaderFieldValue_block_invoke
+ ___PO_LOG_POConstantCoreUtil_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24l
+ _kPOErrorDomain
+ _objc_msgSend$addAdditionalHTTPHeadersToRequest:context:
+ _objc_msgSend$additionalHTTPHeaders
+ _objc_msgSend$characterSetWithRange:
+ _objc_msgSend$countForObject:
+ _objc_msgSend$driverConfigurationsWithCTKDConnection:
+ _objc_msgSend$formUnionWithCharacterSet:
+ _objc_msgSend$hasVerifiedBiometricContext
+ _objc_msgSend$invertedSet
+ _objc_msgSend$isLAAuth
+ _objc_msgSend$isNewAccountPendingRegistration
+ _objc_msgSend$isUserCreatedDuringSetupAssistant
+ _objc_msgSend$isWithinAuthenticationGracePeriod:
+ _objc_msgSend$rangeOfCharacterFromSet:
+ _objc_msgSend$rangeOfComposedCharacterSequencesForRange:
+ _objc_msgSend$setValue:forHTTPHeaderField:
+ _objc_msgSend$substringWithRange:
+ _objc_msgSend$validatedAdditionalHTTPHeaders:
+ _objc_msgSend$valueForHTTPHeaderField:
+ _objc_msgSend$whitespaceCharacterSet
- -[POUserConfiguration newUser]
- GCC_except_table138
- GCC_except_table163
- GCC_except_table60
- OBJC_IVAR_$_POUserConfiguration._newUser
- _objc_msgSend$driverConfigurations
- _objc_msgSend$driverConfigurationsWithClient:
- _objc_msgSend$initWithTokenID:serverEndpoint:targetUID:
CStrings:
+ "!#$%&'*+-.^_`|~"
+ "%@…%@ (%@ characters)"
+ "Added %{public}@ of %{public}@ additional HTTP headers to request: %{public}@"
+ "Additional HTTP header is already set on the request; not overwriting it."
+ "AdditionalHTTPHeaders entry is not a string pair; discarding it."
+ "AdditionalHTTPHeaders field collides with another entry that differs only in case; discarding all of them."
+ "AdditionalHTTPHeaders field is not a valid header name; discarding it."
+ "AdditionalHTTPHeaders field is reserved; discarding it."
+ "AdditionalHTTPHeaders is not a dictionary; ignoring it."
+ "AdditionalHTTPHeaders value is not a valid header value; discarding it."
+ "Headers: %@, Limit: %@"
+ "Login Policy: %{public}@ requires a biometric factor that was not provided"
+ "Login Policy: biometric policy does not apply to AccessKey authentication"
+ "Login Policy: biometric policy does not apply to SmartCard authentication"
+ "Login Policy: biometric policy does not apply to an account pending registration"
+ "Login Policy: biometric policy does not apply to temporary session accounts"
+ "Login Policy: biometric requirement satisfied by LA authentication"
+ "Login Policy: does not have auth grace period"
+ "Login Policy: grace period expired"
+ "Login Policy: la authentication with an unusable externalized LAContext"
+ "Login Policy: la authentication with no externalized LAContext"
+ "Login Policy: registration incomplete and outside the authentication grace period"
+ "Login Policy: registration incomplete, within the authentication grace period"
+ "Login Policy: the account is pending registration, deferring to the local credential"
+ "Missing device encryption key."
+ "Missing temporary account credential."
+ "POConstantCoreUtil"
+ "Too many entries in AdditionalHTTPHeaders; ignoring all of them."
+ "Unable to decrypt temporary account credential with the outgoing key; dropping entry."
+ "accept"
+ "accept-encoding"
+ "authentication-info"
+ "authorization"
+ "connection"
+ "content-encoding"
+ "content-length"
+ "content-type"
+ "cookie"
+ "cookie2"
+ "expect"
+ "host"
+ "keep-alive"
+ "proxy-authenticate"
+ "proxy-authentication-info"
+ "proxy-authorization"
+ "set-cookie"
+ "set-cookie2"
+ "soapaction"
+ "te"
+ "trailer"
+ "transfer-encoding"
+ "upgrade"
+ "www-authenticate"
- "XCTestCase"
```
