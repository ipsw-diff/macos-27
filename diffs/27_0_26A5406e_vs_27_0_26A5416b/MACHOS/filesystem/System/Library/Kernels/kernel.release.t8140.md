## kernel.release.t8140

> `/System/Library/Kernels/kernel.release.t8140`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__const`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__exclaves_bt`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`
- `__BOOTDATA.__static_if`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`

```diff

-13432.1.6.501.1
-  __TEXT.__const: 0x38750
+13432.1.9.0.0
+  __TEXT.__const: 0x38740
   __TEXT.__copyio_vectors: 0x150
   __TEXT.__cstring: 0xb3d61
   __TEXT.__os_log: 0x422be

   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9e42f8
+  __TEXT_EXEC.__text: 0x9e432c
   __TEXT_EXEC.__hib_text: 0x19cc
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x69d4

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x507dd
-  __CTF.__ctf: 0x1064b3
+  __CTF.__ctf: 0x10652e
   Functions: 23726
   Symbols:   6947
   CStrings:  26676
Functions:
~ sub_fffffe0007927abc : 1136 -> 1188
~ sub_fffffe0007d052e0 -> sub_fffffe0007d05314 : 32 -> 44
~ sub_fffffe0007d06fc8 -> sub_fffffe0007d07008 : 4152 -> 4088
```
