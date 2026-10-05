## agx_a000

> `Firmware/agx/armfw_g14c.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4ede8
-  __TEXT.__gxf_code: 0x10c8
+  __TEXT.__text: 0x4ee68
+  __TEXT.__gxf_code: 0x1054
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1f20
Functions:
~ __rtk_arm_start_bootstrap_area : 1888 -> 1868
~ sub_ffffff8000049068 -> sub_ffffff8000049054 : 436 -> 472
~ sub_ffffff800004921c -> sub_ffffff800004922c : 428 -> 540
CStrings:
+ "Sep 29 2026 21:16:39"
- "Sep 13 2026 19:00:17"
```
