## agx_b000

> `Firmware/agx/armfw_g15c.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x52dc4
-  __TEXT.__gxf_code: 0x10c8
+  __TEXT.__text: 0x52e44
+  __TEXT.__gxf_code: 0x1054
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x11d0
Functions:
~ __rtk_arm_start_bootstrap_area : 1892 -> 1872
~ sub_fffffc000004cfbc -> sub_fffffc000004cfa8 : 436 -> 472
~ sub_fffffc000004d170 -> sub_fffffc000004d180 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:23:27"
- "Sep 13 2026 19:06:07"
```
