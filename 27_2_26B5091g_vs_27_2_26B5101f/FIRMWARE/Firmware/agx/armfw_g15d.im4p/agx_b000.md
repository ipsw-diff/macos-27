## agx_b000

> `Firmware/agx/armfw_g15d.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x53f18
-  __TEXT.__gxf_code: 0x10c8
+  __TEXT.__text: 0x53f98
+  __TEXT.__gxf_code: 0x1054
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x12c0
Functions:
~ __rtk_arm_start_bootstrap_area : 1892 -> 1872
~ sub_fffffc000004e110 -> sub_fffffc000004e0fc : 436 -> 472
~ sub_fffffc000004e2c4 -> sub_fffffc000004e2d4 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:23:39"
- "Sep 13 2026 19:06:14"
```
