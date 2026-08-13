## com.apple.driver.usb.AppleUSBXHCI

> `com.apple.driver.usb.AppleUSBXHCI`

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

-1617.0.9.0.0
+1617.0.12.0.0
   __TEXT.__cstring: 0x5722
   __TEXT.__os_log: 0x50f0
   __TEXT.__const: 0xb4
-  __TEXT_EXEC.__text: 0x4b02c
+  __TEXT_EXEC.__text: 0x4b180
   __TEXT_EXEC.__auth_stubs: 0x720
   __DATA.__data: 0xc8
   __DATA.__common: 0x3f8
Functions:
~ __ZN19AppleUSBXHCIRequest7prepareEv : 11172 -> 11340
~ __ZN30AppleUSBXHCIIsochronousRequest7prepareEv : 13264 -> 13436
```
