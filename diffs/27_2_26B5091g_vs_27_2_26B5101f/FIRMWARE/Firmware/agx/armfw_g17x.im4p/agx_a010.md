## agx_a010

> `Firmware/agx/armfw_g17x.im4p/agx_a010`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3cc90
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3cd24
+  __TEXT.__gxf_code: 0x4f50
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x11d5
Functions:
~ sub_fffffc00000388f0 : 432 -> 468
~ sub_fffffc0000038aa0 -> sub_fffffc0000038ac4 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:18:59"
- "Sep 13 2026 19:02:20"
```
