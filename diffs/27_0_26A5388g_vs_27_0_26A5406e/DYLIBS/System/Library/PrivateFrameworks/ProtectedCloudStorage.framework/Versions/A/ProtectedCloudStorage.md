## ProtectedCloudStorage

> `/System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/Versions/A/ProtectedCloudStorage`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-1303.0.3.0.0
-  __TEXT.__text: 0x705a8
+1303.0.6.0.0
+  __TEXT.__text: 0x705cc
   __TEXT.__objc_methlist: 0x1f10
   __TEXT.__const: 0x3d0
   __TEXT.__cstring: 0xdf6b
-  __TEXT.__oslogstring: 0x3fc4
+  __TEXT.__oslogstring: 0x4029
   __TEXT.__gcc_except_tab: 0x3580
   __TEXT.__dlopen_cstrs: 0x214
   __TEXT.__unwind_info: 0x1868

   - /usr/lib/libsqlite3.dylib
   Functions: 2152
   Symbols:   4290
-  CStrings:  3776
+  CStrings:  3777
 
Functions:
~ ___42-[PCSCKKSSyncViewOperation checkTLKStatus]_block_invoke : 532 -> 568
CStrings:
+ "CKKS response for active views: not in circle"
+ "CKKS response for active views: wait for Octagon. This should resolve, proceeding with CKKS sync anyway"
- "CKKS response for active views: wait for Octagon"
```
