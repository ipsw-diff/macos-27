## agx_b000

> `Firmware/agx/armfw_g15s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x503ac
-  __TEXT.__gxf_code: 0x10c8
+  __TEXT.__text: 0x5042c
+  __TEXT.__gxf_code: 0x1054
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1138
Functions:
~ __rtk_arm_start_bootstrap_area : 1892 -> 1872
~ sub_fffffc000004a63c -> sub_fffffc000004a628 : 436 -> 472
~ sub_fffffc000004a7f0 -> sub_fffffc000004a800 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:23:20"
- "Sep 13 2026 19:05:56"
```
