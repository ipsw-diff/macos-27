## agx_a000

> `Firmware/agx/armfw_g17p.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3c058
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3c0ec
+  __TEXT.__gxf_code: 0x4f50
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1d0d
Functions:
~ sub_fffffc0000037e60 : 432 -> 468
~ sub_fffffc0000038010 -> sub_fffffc0000038034 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:17:04"
- "Sep 13 2026 19:00:38"
```
