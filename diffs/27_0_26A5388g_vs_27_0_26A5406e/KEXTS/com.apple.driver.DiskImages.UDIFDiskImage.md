## com.apple.driver.DiskImages.UDIFDiskImage

> `com.apple.driver.DiskImages.UDIFDiskImage`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`

```diff

-701.0.0.0.0
+704.0.0.0.0
   __TEXT.__const: 0x3058
   __TEXT.__cstring: 0x2b0
-  __TEXT_EXEC.__text: 0xb0a4
+  __TEXT_EXEC.__text: 0xb1a4
   __TEXT_EXEC.__auth_stubs: 0x240
   __DATA.__data: 0xc4
   __DATA.__common: 0xd8
Functions:
~ __ZN16KDIUDIFDiskImage19_generateGlobalBLKXEP14UDIFFileHeaderPP6OSDatas : 1000 -> 1264
~ __ZN15KDIUDIFEncoding12loadMetaDataEv : 680 -> 668
~ _lzvnDecode : 1216 -> 1220
```
