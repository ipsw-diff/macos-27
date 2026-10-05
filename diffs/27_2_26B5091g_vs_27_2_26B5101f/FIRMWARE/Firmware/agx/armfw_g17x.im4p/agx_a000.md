## agx_a000

> `Firmware/agx/armfw_g17x.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d00c
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3d0a0
+  __TEXT.__gxf_code: 0x4f50
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x11d5
Functions:
~ sub_fffffc0000038c6c : 432 -> 468
~ sub_fffffc0000038e1c -> sub_fffffc0000038e40 : 428 -> 540
~ sub_fffffc000003cec8 -> sub_fffffc000003cf5c : 332 -> 324
CStrings:
+ "Sep 29 2026 21:30:00"
- "Sep 13 2026 19:11:41"
```
