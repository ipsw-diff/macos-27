## PlatformSSO

> `/System/Library/PrivateFrameworks/PlatformSSO.framework/Versions/A/PlatformSSO`

```diff

-643.40.27.0.0
-  __TEXT.__text: 0x11e1f0
-  __TEXT.__objc_methlist: 0x4994
-  __TEXT.__const: 0x2250
-  __TEXT.__gcc_except_tab: 0x20e8
-  __TEXT.__cstring: 0xf234
-  __TEXT.__oslogstring: 0xb838
+643.40.34.0.0
+  __TEXT.__text: 0x1205f8
+  __TEXT.__objc_methlist: 0x4ae4
+  __TEXT.__const: 0x2260
+  __TEXT.__gcc_except_tab: 0x2210
+  __TEXT.__cstring: 0xf564
+  __TEXT.__oslogstring: 0xbf76
   __TEXT.__dlopen_cstrs: 0x47b
-  __TEXT.__swift5_typeref: 0x75c
+  __TEXT.__swift5_typeref: 0x76e
   __TEXT.__swift5_fieldmd: 0x934
-  __TEXT.__constg_swiftt: 0xc64
+  __TEXT.__constg_swiftt: 0xc6c
   __TEXT.__swift5_reflstr: 0x94a
   __TEXT.__swift5_builtin: 0x50
   __TEXT.__swift5_protos: 0x24

   __TEXT.__swift5_mpenum: 0x10
   __TEXT.__swift5_capture: 0x27c
   __TEXT.__swift5_assocty: 0x18
-  __TEXT.__unwind_info: 0x4568
-  __TEXT.__eh_frame: 0x42b0
+  __TEXT.__unwind_info: 0x4610
+  __TEXT.__eh_frame: 0x42b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x34a0
+  __DATA_CONST.__objc_selrefs: 0x35a8
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0xf0
   __DATA_CONST.__objc_arraydata: 0xa0
-  __DATA_CONST.__got: 0x9d0
+  __DATA_CONST.__got: 0x9f0
   __AUTH_CONST.__const: 0x2ea8
-  __AUTH_CONST.__cfstring: 0x6740
-  __AUTH_CONST.__objc_const: 0xac38
+  __AUTH_CONST.__cfstring: 0x6820
+  __AUTH_CONST.__objc_const: 0xad80
   __AUTH_CONST.__objc_intobj: 0x198
   __AUTH_CONST.__objc_dictobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0xd8
   __AUTH_CONST.__objc_doubleobj: 0x30
-  __AUTH_CONST.__auth_got: 0xce0
+  __AUTH_CONST.__auth_got: 0xce8
   __AUTH.__objc_data: 0x9b0
-  __AUTH.__data: 0xf80
-  __DATA.__objc_ivar: 0x428
+  __AUTH.__data: 0xf88
+  __DATA.__objc_ivar: 0x440
   __DATA.__data: 0x7e0
   __DATA.__bss: 0xef8
   __DATA.__common: 0xb0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4364
-  Symbols:   5759
-  CStrings:  2294
+  Functions: 4405
+  Symbols:   5837
+  CStrings:  2322
 
Symbols:
+ -[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]
+ -[POAgentAuthenticationProcess requestUserRegistrationRepairIfNeeded]
+ -[POAgentAuthenticationProcess setUserRegistrationRepairLock:]
+ -[POAgentAuthenticationProcess setUserRegistrationRepairRequested:]
+ -[POAgentAuthenticationProcess shouldRunConfigurationChangeOnUnlock]
+ -[POAgentAuthenticationProcess userRegistrationRepairLock]
+ -[POAgentAuthenticationProcess userRegistrationRepairRequested]
+ -[POConfigurationManager verifyOwnSecureTokenPasswordForUser:passwordContext:error:]
+ -[PODaemonConnection verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]
+ -[PODaemonProcess verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]
+ -[PODirectoryServices verifyOwnSecureTokenPassword:forUser:error:]
+ -[POLoginProcess isCreatingNewUserForCurrentCredential]
+ -[POLoginProcess resolvedLocalUserName]
+ -[POProfile additionalHTTPHeaders]
+ -[PORegistrationManager claimDeviceRegistrationStart]
+ -[PORegistrationManager claimRegistrationStartResumingUnfinishedDeviceRegistration:]
+ -[PORegistrationManager claimUserRegistrationStart]
+ -[PORegistrationManager publishRegistrationContext:claim:]
+ -[PORegistrationManager publishRegistrationContextWithState:claim:]
+ -[PORegistrationManager registrationContextLock]
+ -[PORegistrationManager registrationGeneration]
+ -[PORegistrationManager registrationIsInProgress]
+ -[PORegistrationManager registrationStarting]
+ -[PORegistrationManager releaseRegistrationStart:]
+ -[PORegistrationManager setRegistrationContextLock:]
+ -[PORegistrationManager setRegistrationGeneration:]
+ -[PORegistrationManager setRegistrationStarting:]
+ -[POUnlockProcess denyUnlockForUnsatisfiedBiometricPolicy]
+ GCC_except_table100
+ GCC_except_table103
+ GCC_except_table109
+ GCC_except_table110
+ GCC_except_table118
+ GCC_except_table119
+ GCC_except_table120
+ GCC_except_table125
+ GCC_except_table144
+ GCC_except_table152
+ GCC_except_table156
+ GCC_except_table157
+ GCC_except_table165
+ GCC_except_table166
+ GCC_except_table168
+ GCC_except_table171
+ GCC_except_table174
+ GCC_except_table18
+ GCC_except_table185
+ GCC_except_table191
+ GCC_except_table194
+ GCC_except_table201
+ GCC_except_table206
+ GCC_except_table207
+ GCC_except_table216
+ GCC_except_table222
+ GCC_except_table237
+ GCC_except_table249
+ GCC_except_table283
+ GCC_except_table291
+ GCC_except_table292
+ GCC_except_table91
+ GCC_except_table92
+ GCC_except_table97
+ OBJC_IVAR_$_POAgentAuthenticationProcess._userRegistrationRepairLock
+ OBJC_IVAR_$_POAgentAuthenticationProcess._userRegistrationRepairRequested
+ OBJC_IVAR_$_POProfile._additionalHTTPHeaders
+ OBJC_IVAR_$_PORegistrationManager._registrationContextLock
+ OBJC_IVAR_$_PORegistrationManager._registrationGeneration
+ OBJC_IVAR_$_PORegistrationManager._registrationStarting
+ _NSLocalizedDescriptionKey
+ _ODFrameworkErrorDomain
+ __66-[PODirectoryServices verifyOwnSecureTokenPassword:forUser:error:]_block_invoke
+ __80-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]_block_invoke
+ __80-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]_block_invoke_2
+ __82-[PODaemonProcess verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]_block_invoke
+ __85-[PODaemonConnection verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]_block_invoke
+ ___66-[PODirectoryServices verifyOwnSecureTokenPassword:forUser:error:]_block_invoke
+ ___69-[POAgentAuthenticationProcess requestUserRegistrationRepairIfNeeded]_block_invoke
+ ___80-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]_block_invoke
+ ___80-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]_block_invoke_2
+ ___82-[PODaemonProcess verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]_block_invoke
+ ___84-[POConfigurationManager verifyOwnSecureTokenPasswordForUser:passwordContext:error:]_block_invoke
+ ___85-[PODaemonConnection verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]_block_invoke
+ ___block_descriptor_57_e8_32s40s48bs_e20_v24?0Q8"NSError"16l
+ _kPOErrorDomain
+ _objc_msgSend$additionalHTTPHeaders
+ _objc_msgSend$biometricPolicyIsUnsatisfied:
+ _objc_msgSend$claimDeviceRegistrationStart
+ _objc_msgSend$claimRegistrationStartResumingUnfinishedDeviceRegistration:
+ _objc_msgSend$claimUserRegistrationStart
+ _objc_msgSend$denyUnlockForUnsatisfiedBiometricPolicy
+ _objc_msgSend$dictionary
+ _objc_msgSend$handleUserNeedsReauthenticationAfterDelay:error:
+ _objc_msgSend$isCreatingNewUserForCurrentCredential
+ _objc_msgSend$isNewAccountPendingRegistration
+ _objc_msgSend$publishRegistrationContext:claim:
+ _objc_msgSend$registrationContextLock
+ _objc_msgSend$registrationGeneration
+ _objc_msgSend$registrationIsInProgress
+ _objc_msgSend$registrationStarting
+ _objc_msgSend$releaseRegistrationStart:
+ _objc_msgSend$requestUserRegistrationRepairIfNeeded
+ _objc_msgSend$resolvedLocalUserName
+ _objc_msgSend$setAdditionalHTTPHeaders:
+ _objc_msgSend$setRegistrationGeneration:
+ _objc_msgSend$setRegistrationStarting:
+ _objc_msgSend$setUserRegistrationRepairRequested:
+ _objc_msgSend$shouldRunConfigurationChangeOnUnlock
+ _objc_msgSend$stringForUserState:
+ _objc_msgSend$userRegistrationRepairLock
+ _objc_msgSend$userRegistrationRepairRequested
+ _objc_msgSend$validatedAdditionalHTTPHeaders:
+ _objc_msgSend$verifyOwnSecureTokenPassword:forUser:error:
+ _objc_msgSend$verifyOwnSecureTokenPasswordForUser:passwordContext:completion:
+ _objc_msgSend$verifyOwnSecureTokenPasswordForUser:passwordContext:error:
+ _symbolic _____y______pSgG s23_ContiguousArrayStorageC 15PlatformSSOCore15POAuthenticatorP
- GCC_except_table101
- GCC_except_table104
- GCC_except_table113
- GCC_except_table115
- GCC_except_table116
- GCC_except_table121
- GCC_except_table126
- GCC_except_table148
- GCC_except_table162
- GCC_except_table163
- GCC_except_table164
- GCC_except_table170
- GCC_except_table177
- GCC_except_table178
- GCC_except_table183
- GCC_except_table197
- GCC_except_table202
- GCC_except_table203
- GCC_except_table212
- GCC_except_table214
- GCC_except_table233
- GCC_except_table243
- GCC_except_table277
- GCC_except_table285
- GCC_except_table286
- GCC_except_table56
- GCC_except_table90
- _OUTLINED_FUNCTION_16
- _OUTLINED_FUNCTION_17
- __60-[PODirectoryServices verifyOwnSecureTokenPassword:forUser:]_block_invoke
- __74-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]_block_invoke
- __74-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]_block_invoke_2
- ___60-[PODirectoryServices verifyOwnSecureTokenPassword:forUser:]_block_invoke
- ___74-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]_block_invoke
- ___74-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]_block_invoke_2
- ___block_descriptor_56_e8_32s40s48bs_e20_v24?0Q8"NSError"16l
- _objc_msgSend$verifyOwnSecureTokenPassword:forUser:
CStrings:
+ ")#Z"
+ "-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:error:]"
+ "-[POConfigurationManager verifyOwnSecureTokenPasswordForUser:passwordContext:error:]"
+ "-[PODaemonProcess verifyOwnSecureTokenPasswordForUser:passwordContext:completion:]"
+ "-[PODirectoryServices verifyOwnSecureTokenPassword:forUser:error:]"
+ "A registration check was already requested for this user"
+ "A registration is already in progress (state = %{public}@), not asking for a registration check"
+ "A registration is already running for this new user; not running the registration checks on unlock"
+ "AdditionalHTTPHeaders"
+ "Bootstrap token is not supported; not verifying the secure token because the divergence could not be repaired."
+ "Cannot continue the FileVault token unlock; returning to the login prompt."
+ "Could not verify the new password against the account's own secure token; not repairing with the bootstrap token: %{public}@"
+ "Could not verify the password against the account's own secure token; not escalating to the forced password change: %{public}@"
+ "Could not verify the password against the own secure token."
+ "Failed to save user configuration after key update."
+ "Key rotation and binding both succeeded; clearing the binding repair flag"
+ "Keybag rekey failed at login; falling back to the password-authorized local account password change"
+ "Local user found"
+ "Login Policy: denied, TouchID is required and cannot be satisfied on the built-in credential path"
+ "Login Policy: the account is pending registration, deferring to the local credential"
+ "OpenID Authorization Request: Performing auth in the system session for an elevation prompt"
+ "Own secure token rejected the password."
+ "Password missing"
+ "Registration has failed, not asking for a registration check"
+ "The account's own secure token rejected this password; retrying with the forced password change"
+ "The configuration changed while this registration was starting; not publishing it"
+ "Token binding is owed; token unlock is unavailable and the IdP password cannot be synced during login. Sign in with the local account password to repair it."
+ "User registration is not usable (state = %{public}@), running the registration checks"
+ "User registration needs to be repaired before the user can authenticate."
+ "User registration no longer needs repair (state = %{public}@)"
+ "another registration is already starting"
+ "handleTokenAuthAfterSuccessfulIdPAuthentication: IdP authentication SUCCEEDED but login cannot complete: the token binding is owed (POUserStateNeedsBinding), so the token cannot unlock the keychain, and the IdP password cannot be synced to the local account here — no user session yet, and no old password or bound token to authorize the change. The user must sign in with the LOCAL account password, which repairs the binding and clears this state; the IdP password works again afterwards."
+ "keybag pairing failed before the keybag password change"
+ "shouldRun(%{public}s, %{public}s): false - account is exempt from Platform SSO policy"
+ "\xf0\xf0Q"
- ")#Y"
- "-[POAgentAuthenticationProcess handleUserNeedsReauthenticationAfterDelay:]"
- "-[PODirectoryServices verifyOwnSecureTokenPassword:forUser:]"
- "Own secure token did not accept the password."
- "The account's own secure token does not accept this password; retrying with the forced password change"
- "User registration already in progress: %{public}@"
- "\xf0\xf0A"
```
