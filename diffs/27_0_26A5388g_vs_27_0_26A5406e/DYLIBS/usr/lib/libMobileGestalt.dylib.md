## libMobileGestalt.dylib

> `/usr/lib/libMobileGestalt.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_fieldmd`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-1622.0.4.0.0
-  __TEXT.__text: 0x63308
+1622.0.5.0.0
+  __TEXT.__text: 0x63440
   __TEXT.__objc_methlist: 0x128
   __TEXT.__const: 0x91d8
-  __TEXT.__cstring: 0x15ec0
-  __TEXT.__oslogstring: 0x341e
+  __TEXT.__cstring: 0x15f40
+  __TEXT.__oslogstring: 0x34a7
   __TEXT.__gcc_except_tab: 0x30
   __TEXT.__dlopen_cstrs: 0x50
   __TEXT.__swift5_typeref: 0x37d

   __DATA_CONST.__objc_superrefs: 0x10
   __DATA_CONST.__got: 0x1b0
   __AUTH_CONST.__const: 0x2f6a0
-  __AUTH_CONST.__cfstring: 0x10720
+  __AUTH_CONST.__cfstring: 0x10760
   __AUTH_CONST.__objc_const: 0x1b8
   __AUTH_CONST.__auth_got: 0x928
   __AUTH.__data: 0x1a8

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftCore.dylib
   - /usr/lib/swift/libswiftCoreFoundation.dylib
-  Functions: 3569
+  Functions: 3572
   Symbols:   1469
-  CStrings:  3458
+  CStrings:  3460
 
CStrings:
+ "Screen canvas size is in incorrect format; bailing from orientation check"
+ "Screen canvas size was NULL; bailing from orientation check"
+ "copyAvailableDisplayZoomSizes: Changed landscape to portrait for (%d, %d)"
- "copyAvailableDisplayZoomSizes: Changed landscape to portrait for %dx%d"
```
