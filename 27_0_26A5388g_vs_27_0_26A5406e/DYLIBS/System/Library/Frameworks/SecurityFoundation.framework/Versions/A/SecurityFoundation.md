## SecurityFoundation

> `/System/Library/Frameworks/SecurityFoundation.framework/Versions/A/SecurityFoundation`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__weak_got`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-55294.0.1.0.0
-  __TEXT.__text: 0x45cfc
+55294.0.2.0.0
+  __TEXT.__text: 0x45c9c
   __TEXT.__objc_methlist: 0x4ed0
   __TEXT.__const: 0x28030
   __TEXT.__cstring: 0x7c37
   __TEXT.__gcc_except_tab: 0x1850
   __TEXT.__oslogstring: 0xd8
   __TEXT.__dof_security_: 0x3c6
-  __TEXT.__unwind_info: 0x1b30
+  __TEXT.__unwind_info: 0x1b38
   __TEXT.__eh_frame: 0x48
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
Functions:
~ -[_SFKeychainManager publicKeyLookupWithIdentifier:certificate:result:] : 776 -> 680
```
