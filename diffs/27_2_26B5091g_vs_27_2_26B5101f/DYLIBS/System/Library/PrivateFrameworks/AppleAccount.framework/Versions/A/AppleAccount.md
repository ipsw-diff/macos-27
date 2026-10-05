## AppleAccount

> `/System/Library/PrivateFrameworks/AppleAccount.framework/Versions/A/AppleAccount`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-1069.125.5.0.0
-  __TEXT.__text: 0x277e64
-  __TEXT.__objc_methlist: 0xb31c
+1069.125.7.0.0
+  __TEXT.__text: 0x278384
+  __TEXT.__objc_methlist: 0xb304
   __TEXT.__cstring: 0x105a1
   __TEXT.__const: 0x484a0
-  __TEXT.__oslogstring: 0x127dd
+  __TEXT.__oslogstring: 0x128fd
   __TEXT.__gcc_except_tab: 0x1aa8
   __TEXT.__dlopen_cstrs: 0x2d3
   __TEXT.__swift5_typeref: 0x334a

   __TEXT.__swift_as_cont: 0x450
   __TEXT.__swift5_capture: 0x7b8
   __TEXT.__unwind_info: 0x7b28
-  __TEXT.__eh_frame: 0x6938
+  __TEXT.__eh_frame: 0x6970
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0xa0
   __DATA_CONST.__objc_protolist: 0x248
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x50d8
+  __DATA_CONST.__objc_selrefs: 0x50d0
   __DATA_CONST.__objc_protorefs: 0xe0
   __DATA_CONST.__objc_superrefs: 0x588
   __DATA_CONST.__objc_arraydata: 0xe0
-  __DATA_CONST.__got: 0x1040
+  __DATA_CONST.__got: 0x1030
   __AUTH_CONST.__const: 0x10a50
   __AUTH_CONST.__cfstring: 0xcfe0
-  __AUTH_CONST.__objc_const: 0x26360
+  __AUTH_CONST.__objc_const: 0x26320
   __AUTH_CONST.__objc_intobj: 0x120
   __AUTH_CONST.__objc_arrayobj: 0x108
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x12c8
+  __AUTH_CONST.__auth_got: 0x12c0
   __AUTH.__objc_data: 0xa0
-  __DATA.__objc_ivar: 0xbc4
+  __DATA.__objc_ivar: 0xbc0
   __DATA.__data: 0x2858
   __DATA.__bss: 0x14c80
   __DATA.__common: 0xa48

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   Functions: 8777
-  Symbols:   11451
-  CStrings:  3524
+  Symbols:   11448
+  CStrings:  3529
 
Symbols:
+ +[AALoginAccountRequest urlBagKey]
+ +[AARegisterRequest urlBagKey]
+ +[AAUpdateProvisioningRequest urlBagKey]
+ -[AARequest initWithURLConfig:]
+ -[AARequest urlConfig]
+ GCC_except_table127
+ GCC_except_table19
+ OBJC_IVAR_$_AARequest._urlConfig
+ _objc_msgSend$urlConfig
- -[AALoginAccountRequest urlString]
- -[AARegisterRequest urlString]
- -[AAURLConfiguration(Deprecated) fetchAccountSettingsURL]
- -[AAURLConfiguration(Deprecated) loginAccountURL]
- -[AAURLConfiguration(Deprecated) signInURL]
- -[AAUpdateProvisioningRequest urlString]
- GCC_except_table125
- OBJC_IVAR_$_AALoginAccountRequest._urlConfig
- OBJC_IVAR_$_AAUpdateProvisioningRequest._urlConfig
- _objc_msgSend$fetchAccountSettingsURL
- _objc_msgSend$loginAccountURL
- _objc_msgSend$signInURL
CStrings:
+ "AASignInFlowController: Sign in - server backoff suppressed the login request"
+ "Avatar optimized for upload"
+ "Fetched identity from remote service"
+ "Received identity change notification for unregistered account: %{private,mask.hash}@"
+ "Starting observation with initial update if different from known identity"
+ "Starting observation with no initial update"
- "Received identity change notification for unregistered account: %@"
```
