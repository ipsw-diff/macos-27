## kernel.release.t8112

> `/System/Library/Kernels/kernel.release.t8112`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__hib_const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__const`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__data`
- `__BOOTDATA.__static_if`
- `__BOOTDATA.__init`
- `__BOOTDATA.__init_entry_set`

```diff

-13432.1.6.501.1
-  __TEXT.__const: 0x37af0
+13432.1.9.0.0
+  __TEXT.__const: 0x37ae0
   __TEXT.__copyio_vectors: 0x150
   __TEXT.__cstring: 0xa4eb1
   __TEXT.__os_log: 0x420fe

   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9a06d4
+  __TEXT_EXEC.__text: 0x9a0708
   __TEXT_EXEC.__hib_text: 0x19c8
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x69b0

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x507dd
-  __CTF.__ctf: 0x107283
+  __CTF.__ctf: 0x10729a
   Functions: 22921
   Symbols:   6947
   CStrings:  25870
Functions:
~ sub_fffffe00078d1bac : 1136 -> 1188
~ sub_fffffe0007ca96bc -> sub_fffffe0007ca96f0 : 36 -> 48
~ sub_fffffe0007cab3a4 -> sub_fffffe0007cab3e4 : 3164 -> 3100
```
