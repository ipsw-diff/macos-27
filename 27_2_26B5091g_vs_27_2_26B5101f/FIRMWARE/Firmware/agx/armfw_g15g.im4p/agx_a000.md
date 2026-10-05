## agx_a000

> `Firmware/agx/armfw_g15g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f30c
-  __TEXT.__gxf_code: 0x10c8
+  __TEXT.__text: 0x4f38c
+  __TEXT.__gxf_code: 0x1054
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x23fc
Functions:
~ __rtk_arm_start_bootstrap_area : 1892 -> 1872
~ sub_fffffc0000049b60 -> sub_fffffc0000049b4c : 436 -> 472
~ sub_fffffc0000049d14 -> sub_fffffc0000049d24 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:16:38"
- "Sep 13 2026 19:00:15"
```
