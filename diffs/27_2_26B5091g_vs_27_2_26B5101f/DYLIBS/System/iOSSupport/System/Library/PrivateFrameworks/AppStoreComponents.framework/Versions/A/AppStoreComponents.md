## AppStoreComponents

> `/System/iOSSupport/System/Library/PrivateFrameworks/AppStoreComponents.framework/Versions/A/AppStoreComponents`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-27.1.9.0.0
-  __TEXT.__text: 0x6935c
-  __TEXT.__objc_methlist: 0x6a8c
+27.1.11.0.0
+  __TEXT.__text: 0x693d4
+  __TEXT.__objc_methlist: 0x6aa4
   __TEXT.__const: 0x1a94
   __TEXT.__cstring: 0x3236
-  __TEXT.__oslogstring: 0x300b
+  __TEXT.__oslogstring: 0x301d
   __TEXT.__gcc_except_tab: 0x714
   __TEXT.__dlopen_cstrs: 0x108
   __TEXT.__constg_swiftt: 0x724

   __TEXT.__swift5_types: 0xa8
   __TEXT.__swift5_protos: 0xc
   __TEXT.__swift5_capture: 0x1b0
-  __TEXT.__unwind_info: 0x2798
+  __TEXT.__unwind_info: 0x27a0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0xe0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3000
+  __DATA_CONST.__objc_selrefs: 0x3010
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x358
   __DATA_CONST.__objc_arraydata: 0x60
   __DATA_CONST.__got: 0x778
   __AUTH_CONST.__const: 0x1b50
   __AUTH_CONST.__cfstring: 0x47e0
-  __AUTH_CONST.__objc_const: 0xc9d0
+  __AUTH_CONST.__objc_const: 0xca00
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x30
   __AUTH_CONST.__auth_got: 0xbb0
   __AUTH.__objc_data: 0x910
   __AUTH.__data: 0x410
-  __DATA.__objc_ivar: 0x6d0
+  __DATA.__objc_ivar: 0x6d4
   __DATA.__data: 0x13e8
   __DATA.__bss: 0x1fd0
   __DATA.__common: 0x28

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3044
-  Symbols:   6142
+  Functions: 3046
+  Symbols:   6147
   CStrings:  896
 
Symbols:
+ -[ASCLockupView hiddenReason]
+ -[ASCLockupView setHiddenReason:]
+ OBJC_IVAR_$_ASCLockupView._hiddenReason
+ _objc_msgSend$hiddenReason
+ _objc_msgSend$setHiddenReason:
Functions:
~ -[ASCLockupView setLockupSize:] : 148 -> 200
~ -[ASCLockupView setHidden:] : 92 -> 8
+ -[ASCLockupView setHiddenReason:]
+ -[ASCLockupView setWebBrowserFlowType:]
CStrings:
+ ":"
+ "Current process is not eligible to use %{public}@ lockup view size, keeping %{public}@ and hiding lockup"
- "*"
- "Current process is not eligible to use %{public}@ lockup view size, keeping %{public}@"
```
