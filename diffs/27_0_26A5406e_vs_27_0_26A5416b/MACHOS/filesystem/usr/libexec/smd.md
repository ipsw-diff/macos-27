## smd

> `/usr/libexec/smd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-3298.0.26.0.2
+3298.1.1.0.0
   __TEXT.__text: 0x107b8
   __TEXT.__auth_stubs: 0xc80
   __TEXT.__objc_stubs: 0x1500

   __TEXT.__objc_classname: 0x1b1
   __TEXT.__objc_methtype: 0xa85
   __TEXT.__objc_methname: 0x14d1
-  __TEXT.__cstring: 0x1359
+  __TEXT.__cstring: 0x134d
   __TEXT.__gcc_except_tab: 0x2dc
   __TEXT.__unwind_info: 0x3d0
   __DATA_CONST.__const: 0x518
CStrings:
+ "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Mon Aug 10 01:08:31 PDT 2026; root:libxpc_executables-3298.1.1~29/smd/RELEASE_ARM64E"
+ "Darwin Privileged Tool Bootstrapper Version 2.0.0: Mon Aug 10 01:08:31 PDT 2026; root:libxpc_executables-3298.1.1~29/smd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Privileged Tool Bootstrapper Version 2.0.0: Mon Aug  3 23:18:57 PDT 2026; root:libxpc_executables-3298.0.26.0.2~272/smd/RELEASE_ARM64E"
- "Darwin Privileged Tool Bootstrapper Version 2.0.0: Mon Aug  3 23:18:57 PDT 2026; root:libxpc_executables-3298.0.26.0.2~272/smd/RELEASE_ARM64E"
```
