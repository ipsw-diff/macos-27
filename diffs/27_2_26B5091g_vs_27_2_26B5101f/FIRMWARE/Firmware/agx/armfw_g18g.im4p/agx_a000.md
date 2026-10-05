## agx_a000

> `Firmware/agx/armfw_g18g.im4p/agx_a000`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA.__const`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x3c858
-  __TEXT.__gxf_code: 0x4f40
+  __TEXT.__text: 0x3c8ec
+  __TEXT.__gxf_code: 0x4f50
   __TEXT.__gxf_code_pad: 0x0
   __TEXT.__gxf_shr_code: 0x560
   __TEXT.__const: 0x20e1
Functions:
~ sub_fffffc00000389f4 : 436 -> 472
~ sub_fffffc0000038ba8 -> sub_fffffc0000038bcc : 428 -> 540
CStrings:
+ "Sep 29 2026 21:19:29"
- "Sep 13 2026 19:02:48"
```
