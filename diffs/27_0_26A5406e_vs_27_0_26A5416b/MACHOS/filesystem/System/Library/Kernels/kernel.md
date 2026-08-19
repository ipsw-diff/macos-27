## kernel

> `/System/Library/Kernels/kernel`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__data`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__assert`
- `__DATA_CONST.__kern_brk_desc`
- `__DATA_CONST.__sdt`
- `__DATA_CONST.__mod_init_func`
- `__KLDDATA.__init`
- `__KLDDATA.__init_entry_set`
- `__KLDDATA.__static_ifinit`

```diff

-13432.1.6.501.1
-  __TEXT.__text: 0x9057b0
-  __TEXT.__const: 0x457a0
+13432.1.9.0.0
+  __TEXT.__text: 0x905730
+  __TEXT.__const: 0x45780
   __TEXT.__os_log: 0x4c2eb
   __TEXT.__cstring: 0xa336d
   __TEXT.__eh_frame: 0x118

   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0
   __LINKINFO.__symbolsets: 0x4e2fa
-  __CTF.__ctf: 0xd3db6
+  __CTF.__ctf: 0xd3d96
   Functions: 27124
   Symbols:   24380
   CStrings:  26045
Functions:
~ _kdp_init : 1552 -> 1488
~ sub_ffffff80007a8500 -> sub_ffffff80007a84c0 : 1152 -> 1184
~ sub_ffffff80007aa230 -> sub_ffffff80007aa210 : 1232 -> 1216
~ sub_ffffff80008de1d0 -> sub_ffffff80008de1a0 : 2928 -> 2848
~ sub_ffffff8000b0778e -> sub_ffffff8000b0770e : 7239794 -> 7239922
```
