## agx_a000

> `Firmware/agx/armfw_g16g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__gxf_data`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x52c38
-  __TEXT.__gxf_code: 0x5080
+  __TEXT.__text: 0x52ccc
+  __TEXT.__gxf_code: 0x5090
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1d8d
Functions:
~ sub_fffffc000004e4e8 : 436 -> 472
~ sub_fffffc000004e69c -> sub_fffffc000004e6c0 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:17:01"
- "Sep 13 2026 19:00:34"
```
