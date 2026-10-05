## agx_b000

> `Firmware/agx/armfw_g16s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x5176c
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x51800
+  __TEXT.__gxf_code: 0x4f50
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x12fd
Functions:
~ sub_fffffc000004cf80 : 436 -> 472
~ sub_fffffc000004d134 -> sub_fffffc000004d158 : 428 -> 540
~ sub_fffffc000005162c -> sub_fffffc00000516c0 : 328 -> 320
CStrings:
+ "Sep 29 2026 21:23:17"
- "Sep 13 2026 19:05:57"
```
