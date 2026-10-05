## agx_b000

> `Firmware/agx/armfw_g14s.im4p/agx_b000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA.__const`
- `__DATA._rtk_mtab`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4e5a4
-  __TEXT.__gxf_code: 0x10c8
+  __TEXT.__text: 0x4e624
+  __TEXT.__gxf_code: 0x1054
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1f08
Functions:
~ __rtk_arm_start_bootstrap_area : 1888 -> 1868
~ sub_ffffff8000048824 -> sub_ffffff8000048810 : 436 -> 472
~ sub_ffffff80000489d8 -> sub_ffffff80000489e8 : 428 -> 540
CStrings:
+ "Sep 29 2026 21:21:43"
- "Sep 13 2026 19:04:35"
```
