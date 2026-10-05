## agx_a000

> `Firmware/agx/armfw_g13g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x40fb0
-  __TEXT.__gxf_code: 0x1150
+  __TEXT.__text: 0x41030
+  __TEXT.__gxf_code: 0x10dc
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x1d54
Functions:
~ __rtk_arm_start_bootstrap_area : 1888 -> 1868
~ sub_ffffff800003beb8 -> sub_ffffff800003bea4 : 436 -> 472
~ sub_ffffff800003c06c -> sub_ffffff800003c07c : 428 -> 540
CStrings:
+ "Sep 29 2026 21:25:46"
- "Sep 13 2026 19:07:56"
```
