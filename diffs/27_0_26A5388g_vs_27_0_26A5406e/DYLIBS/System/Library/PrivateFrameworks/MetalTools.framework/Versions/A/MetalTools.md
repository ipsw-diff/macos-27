## MetalTools

> `/System/Library/PrivateFrameworks/MetalTools.framework/Versions/A/MetalTools`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__weak_got`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-382.5.0.0.0
-  __TEXT.__text: 0x14f154
+382.5.3.0.0
+  __TEXT.__text: 0x14f184
   __TEXT.__objc_methlist: 0x1b29c
   __TEXT.__gcc_except_tab: 0x32e8
-  __TEXT.__cstring: 0x36409
+  __TEXT.__cstring: 0x3643f
   __TEXT.__const: 0x5b0
   __TEXT.__oslogstring: 0x28d1
   __TEXT.__unwind_info: 0x5938

   __DATA_CONST.__objc_superrefs: 0x6c0
   __DATA_CONST.__got: 0xbe0
   __AUTH_CONST.__const: 0x1150
-  __AUTH_CONST.__cfstring: 0xfc40
+  __AUTH_CONST.__cfstring: 0xfc60
   __AUTH_CONST.__objc_const: 0x4b350
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__auth_got: 0x650

   - /usr/lib/libobjc.A.dylib
   Functions: 8406
   Symbols:   15515
-  CStrings:  3747
+  CStrings:  3748
 
Functions:
~ -[MTLDebugDevice tensorSizeAndAlignWithDescriptor:] : 288 -> 336
CStrings:
+ "descriptor should not configure any auxiliary planes."
```
