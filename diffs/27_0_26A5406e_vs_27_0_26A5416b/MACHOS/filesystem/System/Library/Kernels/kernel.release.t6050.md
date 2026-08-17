## kernel.release.t6050

> `/System/Library/Kernels/kernel.release.t6050`

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
-  __TEXT.__const: 0x38a00
+13432.1.9.0.0
+  __TEXT.__const: 0x389f0
   __TEXT.__copyio_vectors: 0x340
   __TEXT.__cstring: 0xb6ba4
   __TEXT.__os_log: 0x4275c

   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9fce58
+  __TEXT_EXEC.__text: 0x9fce8c
   __TEXT_EXEC.__hib_text: 0x19cc
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x69bc

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x507dd
-  __CTF.__ctf: 0x10d59a
+  __CTF.__ctf: 0x10d547
   Functions: 23868
   Symbols:   6947
   CStrings:  27004
Functions:
~ sub_fffffe0007945560 : 1136 -> 1188
~ sub_fffffe0007d25e40 -> sub_fffffe0007d25e74 : 32 -> 44
~ sub_fffffe0007d27b28 -> sub_fffffe0007d27b68 : 1240 -> 1176
```
