## agx_b000

> `Firmware/agx/armfw_g16g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__gxf_data`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x52744
-  __TEXT.__gxf_code: 0x5080
+  __TEXT.__text: 0x527d8
+  __TEXT.__gxf_code: 0x5090
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1dcd
Functions:
~ sub_fffffc000004dff4 : 436 -> 472
~ sub_fffffc000004e1a8 -> sub_fffffc000004e1cc : 428 -> 540
~ sub_fffffc0000052604 -> sub_fffffc0000052698 : 320 -> 328
CStrings:
+ "Sep 29 2026 21:22:18"
- "Sep 13 2026 19:05:14"
```
