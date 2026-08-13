## OSEligibility

> `/System/Library/PrivateFrameworks/OSEligibility.framework/Versions/A/OSEligibility`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`

```diff

-446.0.2.0.0
-  __TEXT.__text: 0x1e79c
+446.1.1.0.0
+  __TEXT.__text: 0x1e7fc
   __TEXT.__objc_methlist: 0x17c
   __TEXT.__const: 0x5054
   __TEXT.__swift5_typeref: 0xe7e
-  __TEXT.__oslogstring: 0x1c0
+  __TEXT.__oslogstring: 0x1d0
   __TEXT.__cstring: 0x8f8
   __TEXT.__constg_swiftt: 0xb84
   __TEXT.__swift5_reflstr: 0x10f4

   __DATA_CONST.__objc_classlist: 0x28
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x138
+  __DATA_CONST.__objc_selrefs: 0x150
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__got: 0xb8
   __AUTH_CONST.__const: 0x1728

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   Functions: 931
-  Symbols:   526
+  Symbols:   529
   CStrings:  61
 
Symbols:
+ _objc_msgSend$betaTesterType
+ _objc_msgSend$distributorInfo
+ _objc_msgSend$iTunesMetadata
Functions:
~ sub_26e924e90 -> sub_26e564e90 : 2932 -> 2940
~ sub_26e93f5a8 -> sub_26e57f5b0 : 32 -> 120
CStrings:
+ "Not bypassing eligibility for %s:%s (isProfileValidated: %{bool}d isUPPValidated:%{bool}d isExternalBeta:%{bool}d)"
- "Not bypassing eligibility for %s:%s (isProfileValidated: %{bool}d isUPPValidated:%{bool}d isBeta:%{bool}d"
```
