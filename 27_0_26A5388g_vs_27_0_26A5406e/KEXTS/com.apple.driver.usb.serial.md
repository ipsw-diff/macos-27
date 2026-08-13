## com.apple.driver.usb.serial

> `com.apple.driver.usb.serial`

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

-156.0.0.0.0
+157.0.0.0.0
   __TEXT.__const: 0x60
   __TEXT.__cstring: 0x235
-  __TEXT_EXEC.__text: 0x577c
+  __TEXT_EXEC.__text: 0x5858
   __TEXT_EXEC.__auth_stubs: 0x260
   __DATA.__data: 0xc8
   __DATA.__common: 0x60
Symbols:
+ __ZZN14AppleUSBSerial13freeResourcesEvE20kalloc_type_view_608
+ __ZZN14AppleUSBSerial13freeResourcesEvE20kalloc_type_view_617
+ __ZZN14AppleUSBSerial14allocResourcesEhhP24IOBufferMemoryDescriptorS1_jjE20kalloc_type_view_569
+ __ZZN14AppleUSBSerial14allocResourcesEhhP24IOBufferMemoryDescriptorS1_jjE20kalloc_type_view_572
- __ZZN14AppleUSBSerial13freeResourcesEvE20kalloc_type_view_586
- __ZZN14AppleUSBSerial13freeResourcesEvE20kalloc_type_view_595
- __ZZN14AppleUSBSerial14allocResourcesEhhP24IOBufferMemoryDescriptorS1_jjE20kalloc_type_view_547
- __ZZN14AppleUSBSerial14allocResourcesEhhP24IOBufferMemoryDescriptorS1_jjE20kalloc_type_view_550
Functions:
~ _OUTLINED_FUNCTION_2 : 20 -> 12
~ _OUTLINED_FUNCTION_3 : 12 -> 20
~ __ZN24AppleUSBSerialUserClient14externalMethodEjP25IOExternalMethodArgumentsP24IOExternalMethodDispatchP8OSObjectPv : 1716 -> 1760
~ __ZN14AppleUSBSerial14allocResourcesEhhP24IOBufferMemoryDescriptorS1_jj : 668 -> 844
```
