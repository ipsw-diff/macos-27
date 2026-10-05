## agx_b010

> `Firmware/agx/armfw_g17p.im4p/agx_b010`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3bda8
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3be3c
+  __TEXT.__gxf_code: 0x4f50
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1d0d
Functions:
~ sub_fffffc0000037bb0 : 432 -> 468
~ sub_fffffc0000037d60 -> sub_fffffc0000037d84 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:36:55"
- "Sep 13 2026 19:18:28"
```
