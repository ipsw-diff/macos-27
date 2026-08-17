## kernel.release.vmapple

> `/System/Library/Kernels/kernel.release.vmapple`

### Sections with Same Size but Changed Content

- `__TEXT.__copyio_vectors`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__kalloc_type`
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
-  __TEXT.__const: 0x375b0
+13432.1.9.0.0
+  __TEXT.__const: 0x375a0
   __TEXT.__copyio_vectors: 0x150
   __TEXT.__cstring: 0x9d7e0
   __TEXT.__os_log: 0x41d91

   __DATA_CONST.__mod_init_func: 0x2d0
   __DATA_CONST.__auth_ptr: 0x10
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9845ec
+  __TEXT_EXEC.__text: 0x984634
   __TEXT_EXEC.__hib_text: 0x10b8
   __TEXT_EXEC.__commpage_text: 0x334
   __KLD.__text: 0xb118

   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
   __LINKINFO.__symbolsets: 0x50330
-  __CTF.__ctf: 0xf90ac
+  __CTF.__ctf: 0xf90e3
   Functions: 22172
   Symbols:   6925
   CStrings:  25170
Functions:
~ sub_fffffe00078af5f0 : 1196 -> 1268
~ sub_fffffe0007c845d4 -> sub_fffffe0007c8461c : 44 -> 36
~ sub_fffffe0007c859b4 -> sub_fffffe0007c859f4 : 9804 -> 9740
```
