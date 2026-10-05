## agx_a000

> `Firmware/agx/armfw_g14d.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4f528
-  __TEXT.__gxf_code: 0x10c8
+  __TEXT.__text: 0x4f5a8
+  __TEXT.__gxf_code: 0x1054
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1f60
Functions:
~ __rtk_arm_start_bootstrap_area : 1888 -> 1868
~ sub_ffffff80000497a8 -> sub_ffffff8000049794 : 436 -> 472
~ sub_ffffff800004995c -> sub_ffffff800004996c : 428 -> 540
CStrings:
+ "Sep 29 2026 21:16:42"
- "Sep 13 2026 19:00:17"
```
