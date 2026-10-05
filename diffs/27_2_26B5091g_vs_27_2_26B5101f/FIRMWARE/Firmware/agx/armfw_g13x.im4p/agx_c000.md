## agx_c000

> `Firmware/agx/armfw_g13x.im4p/agx_c000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4497c
-  __TEXT.__gxf_code: 0x1150
+  __TEXT.__text: 0x449fc
+  __TEXT.__gxf_code: 0x10dc
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1f88
Functions:
~ __rtk_arm_start_bootstrap_area : 1888 -> 1868
~ sub_ffffff800003ec44 -> sub_ffffff800003ec30 : 436 -> 472
~ sub_ffffff800003edf8 -> sub_ffffff800003ee08 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:27:53"
- "Sep 13 2026 19:10:06"
```
