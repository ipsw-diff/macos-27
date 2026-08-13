## RealityCoreTextureImport

> `/System/Library/PrivateFrameworks/RealityCoreTextureImport.framework/Versions/A/RealityCoreTextureImport`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__weak_auth_got`
- `__AUTH.__objc_data`
- `__DATA.__data`

```diff

-24.0.4.0.0
-  __TEXT.__text: 0x4ba54
+24.0.5.0.1
+  __TEXT.__text: 0x4ba80
   __TEXT.__objc_methlist: 0x3f4
   __TEXT.__const: 0xe108
-  __TEXT.__cstring: 0x3627
+  __TEXT.__cstring: 0x3654
   __TEXT.__oslogstring: 0x2425
   __TEXT.__unwind_info: 0x15e8
   __TEXT.__eh_frame: 0x7c

   - /usr/lib/libobjc.A.dylib
   Functions: 1369
   Symbols:   1947
-  CStrings:  541
+  CStrings:  542
 
Functions:
~ __ZNK2re16DataImportSource18tryReadHeaderBytesEPvm : 100 -> 104
~ __ZN2re16DataImportSource20tryCreateImageSourceEPK14__CFDictionaryb : 236 -> 284
~ __Z27loadTextureDataWithProviderRN2re15ImportOperationEb : 2756 -> 2748
CStrings:
+ "Failed to create CGImageSource for nil data."
```
