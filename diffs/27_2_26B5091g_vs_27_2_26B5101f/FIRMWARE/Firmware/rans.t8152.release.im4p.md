## rans.t8152.release.im4p

> `Firmware/rans.t8152.release.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__chain_starts`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_mtab`
- `__DATA.__const`

```diff

   __TEXT.text_first: 0x45a0
-  __TEXT.__text: 0x210e94
+  __TEXT.__text: 0x210f30
   __TEXT.shared: 0xee40
   __TEXT.read: 0x7214
   __TEXT.__const: 0x63e0
-  __TEXT.__cstring: 0x277da
+  __TEXT.__cstring: 0x277dc
   __TEXT.__init_offsets: 0x0
   __TEXT.__chain_starts: 0x1c
   __DATA._rtk_boot: 0x4000

   __DATA._rtk_patchbay: 0x4b9
   __DATA._rtk_tunables: 0xa10
   __DATA._rtk_mtab: 0x330
-  __DATA.__data: 0x8528
+  __DATA.__data: 0x8530
   __DATA.__const: 0x1cc8
   __DATA.__gxf_data: 0x10
   __DATA.core_globals: 0x17b
Functions:
~ sub_1dcb8 : 460 -> 496
~ sub_1de84 -> sub_1dea8 : 448 -> 640
~ sub_baf2c -> sub_bb010 : 80220 -> 80128
~ sub_2131e0 -> sub_213268 : 22848 -> 22868
~ sub_218d30 -> sub_218dcc : 368 -> 356
CStrings:
+ "3975.40.15"
+ "3975.40.15~176"
+ "AppleStorageFirmware-3975.40.15~176"
- "3975.40.14"
- "3975.40.14~73"
- "AppleStorageFirmware-3975.40.14~73"
```
