## agx_b000

> `Firmware/agx/armfw_g18g.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3c80c
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3c8a0
+  __TEXT.__gxf_code: 0x4f50
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x20e1
Functions:
~ sub_fffffc00000389a8 : 436 -> 472
~ sub_fffffc0000038b5c -> sub_fffffc0000038b80 : 428 -> 540
~ sub_fffffc000003c6c8 -> sub_fffffc000003c75c : 332 -> 324
CStrings:
+ "Sep 29 2026 21:29:56"
- "Sep 13 2026 19:11:37"
```
