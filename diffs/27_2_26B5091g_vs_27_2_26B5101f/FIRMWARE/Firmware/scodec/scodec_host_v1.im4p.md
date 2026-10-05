## scodec_host_v1.im4p

> `Firmware/scodec/scodec_host_v1.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA._afk_sys_objt`
- `__DATA.__mod_init_func`

```diff

-  __TEXT.__text: 0x4ccfc
+  __TEXT.__text: 0x4cd90
   __TEXT.__const: 0x3938
   __TEXT.__cstring: 0x2a21
   __TEXT.__init_offsets: 0x0
Functions:
~ __create_reporters_gated : 432 -> 468
~ __update_reporter : 428 -> 540
~ __rtk_lock_lock : 376 -> 368
```
