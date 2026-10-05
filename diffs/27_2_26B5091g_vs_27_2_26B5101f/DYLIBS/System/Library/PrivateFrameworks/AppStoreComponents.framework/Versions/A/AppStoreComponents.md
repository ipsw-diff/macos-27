## AppStoreComponents

> `/System/Library/PrivateFrameworks/AppStoreComponents.framework/Versions/A/AppStoreComponents`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-27.1.9.0.0
-  __TEXT.__text: 0x6f108
-  __TEXT.__objc_methlist: 0x6f14
+27.1.11.0.0
+  __TEXT.__text: 0x6f180
+  __TEXT.__objc_methlist: 0x6f2c
   __TEXT.__const: 0x19f4
   __TEXT.__cstring: 0x34e6
-  __TEXT.__oslogstring: 0x2e0b
+  __TEXT.__oslogstring: 0x2e1d
   __TEXT.__gcc_except_tab: 0x6c4
   __TEXT.__swift5_typeref: 0x486
   __TEXT.__swift5_capture: 0x1c8

   __TEXT.__swift5_proto: 0x100
   __TEXT.__swift5_types: 0xa8
   __TEXT.__swift5_protos: 0xc
-  __TEXT.__unwind_info: 0x28a0
+  __TEXT.__unwind_info: 0x28a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x50
   __DATA_CONST.__objc_protolist: 0xd8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3220
+  __DATA_CONST.__objc_selrefs: 0x3230
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x368
   __DATA_CONST.__objc_arraydata: 0x60
   __DATA_CONST.__got: 0x790
   __AUTH_CONST.__const: 0x2bc0
   __AUTH_CONST.__cfstring: 0x4940
-  __AUTH_CONST.__objc_const: 0xcfc0
+  __AUTH_CONST.__objc_const: 0xcff0
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_doubleobj: 0x30
   __AUTH_CONST.__auth_got: 0xb90
   __AUTH.__objc_data: 0xb18
   __AUTH.__data: 0x450
-  __DATA.__objc_ivar: 0x6fc
+  __DATA.__objc_ivar: 0x700
   __DATA.__data: 0x1408
   __DATA.__objc_stublist: 0x8
   __DATA.__bss: 0x1f30

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3171
-  Symbols:   6323
+  Functions: 3173
+  Symbols:   6328
   CStrings:  898
 
Symbols:
+ -[ASCLockupView hiddenReason]
+ -[ASCLockupView setHiddenReason:]
+ OBJC_IVAR_$_ASCLockupView._hiddenReason
+ _objc_msgSend$hiddenReason
+ _objc_msgSend$setHiddenReason:
Functions:
~ -[ASCLockupView setLockupSize:] : 164 -> 216
~ -[ASCLockupView setHidden:] : 96 -> 8
+ -[ASCLockupView setHiddenReason:]
+ -[ASCLockupView setWebBrowserFlowType:]
CStrings:
+ ";"
+ "Current process is not eligible to use %{public}@ lockup view size, keeping %{public}@ and hiding lockup"
- "+"
- "Current process is not eligible to use %{public}@ lockup view size, keeping %{public}@"
```
