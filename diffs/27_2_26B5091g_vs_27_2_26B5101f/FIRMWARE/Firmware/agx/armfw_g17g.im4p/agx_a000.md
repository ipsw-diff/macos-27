## agx_a000

> `Firmware/agx/armfw_g17g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3d868
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3d8fc
+  __TEXT.__gxf_code: 0x4f50
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1085
Functions:
~ sub_fffffc0000039638 : 432 -> 468
~ sub_fffffc00000397e8 -> sub_fffffc000003980c : 428 -> 540
CStrings:
+ "Sep 29 2026 21:18:51"
- "Sep 13 2026 19:02:14"
```
