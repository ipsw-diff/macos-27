## AppleMediaServices

> `/System/Library/PrivateFrameworks/AppleMediaServices.framework/Versions/A/AppleMediaServices`

```diff

-10.0.60.1.2
-  __TEXT.__text: 0x8ee128
+10.0.60.1.3
+  __TEXT.__text: 0x8ee3e4
   __TEXT.__lazy_helpers: 0x2e98
-  __TEXT.__objc_methlist: 0x23e7c
+  __TEXT.__objc_methlist: 0x23ea4
   __TEXT.__const: 0xba548
   __TEXT.__dlopen_cstrs: 0x834
-  __TEXT.__cstring: 0x2bbae
+  __TEXT.__cstring: 0x2bbe9
   __TEXT.__swift5_typeref: 0x75f7
   __TEXT.__constg_swiftt: 0x5a54
   __TEXT.__swift5_builtin: 0x3d4

   __DATA_CONST.__objc_catlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x490
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xfae8
+  __DATA_CONST.__objc_selrefs: 0xfb08
   __DATA_CONST.__objc_protorefs: 0x258
   __DATA_CONST.__objc_superrefs: 0xcf8
   __DATA_CONST.__objc_arraydata: 0x498
   __DATA_CONST.__got: 0x19d8
   __AUTH_CONST.__const: 0x44510
-  __AUTH_CONST.__cfstring: 0x23080
-  __AUTH_CONST.__objc_const: 0x3f1f0
+  __AUTH_CONST.__cfstring: 0x230a0
+  __AUTH_CONST.__objc_const: 0x3f220
   __AUTH_CONST.__lazy_load_got: 0x460
   __AUTH_CONST.__objc_intobj: 0xc30
   __AUTH_CONST.__objc_arrayobj: 0x180

   __AUTH_CONST.__auth_got: 0x2398
   __AUTH.__objc_data: 0x9b68
   __AUTH.__data: 0x2bd8
-  __DATA.__objc_ivar: 0x1a2c
+  __DATA.__objc_ivar: 0x1a30
   __DATA.__data: 0x7c74
   __DATA.__bss: 0x1bdd8
   __DATA.__common: 0x1520

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 29129
-  Symbols:   32114
-  CStrings:  8797
+  Functions: 29132
+  Symbols:   32122
+  CStrings:  8798
 
Symbols:
+ -[AMSAuthenticateOptions setSuppressOtherMediaTypeStorefrontSync:]
+ -[AMSAuthenticateOptions suppressOtherMediaTypeStorefrontSync]
+ -[AMSAuthenticateTask _signIntoMediaTypes:withVerifiedAccount:authenticationResults:]
+ -[AMSAuthenticateTask _signIntoOtherMediaTypesWithVerifiedAccount:authenticationResults:]
+ OBJC_IVAR_$_AMSAuthenticateOptions._suppressOtherMediaTypeStorefrontSync
+ ___85-[AMSAuthenticateTask _signIntoMediaTypes:withVerifiedAccount:authenticationResults:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56s64s_e55_"AMSPromise"24?0"AMSAuthenticateResult"8"NSError"16l
+ _objc_msgSend$_signIntoMediaTypes:withVerifiedAccount:authenticationResults:
+ _objc_msgSend$_signIntoOtherMediaTypesWithVerifiedAccount:authenticationResults:
+ _objc_msgSend$setSuppressOtherMediaTypeStorefrontSync:
+ _objc_msgSend$subarrayWithRange:
+ _objc_msgSend$suppressOtherMediaTypeStorefrontSync
- -[AMSAuthenticateTask _signIntoOtherMediaTypeWithVerifiedAccount:authenticationResults:]
- ___88-[AMSAuthenticateTask _signIntoOtherMediaTypeWithVerifiedAccount:authenticationResults:]_block_invoke
- ___block_descriptor_56_e8_32s40s48s_e55_"AMSPromise"24?0"AMSAuthenticateResult"8"NSError"16l
- _objc_msgSend$_signIntoOtherMediaTypeWithVerifiedAccount:authenticationResults:
CStrings:
+ "-[AMSAuthenticateTask _signIntoMediaTypes:withVerifiedAccount:authenticationResults:]"
+ "AMSAuthenticateOptionsSuppressOtherMediaTypeStorefrontSyncKey"
- "-[AMSAuthenticateTask _signIntoOtherMediaTypeWithVerifiedAccount:authenticationResults:]"
```
