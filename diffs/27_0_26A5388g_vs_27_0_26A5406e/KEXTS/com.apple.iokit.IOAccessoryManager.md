## com.apple.iokit.IOAccessoryManager

> `com.apple.iokit.IOAccessoryManager`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`

```diff

-1068.0.0.0.0
+1068.0.2.0.0
   __TEXT.__const: 0x2b8
   __TEXT.__cstring: 0x110ec
-  __TEXT.__os_log: 0x12126
-  __TEXT_EXEC.__text: 0xebf28
+  __TEXT.__os_log: 0x12155
+  __TEXT_EXEC.__text: 0xebffc
   __TEXT_EXEC.__auth_stubs: 0xbc0
   __DATA.__data: 0x7e8
   __DATA.__common: 0x16b8

   __DATA_CONST.__got: 0x1e8
   __DATA_CONST.__auth_ptr: 0x20
   Functions: 5013
-  Symbols:   7456
-  CStrings:  2962
+  Symbols:   7457
+  CStrings:  2963
 
Symbols:
+ __ZZN17IOPortFeatureLDCM32_handleMitigationsForLiquidStateEbE11_os_log_fmt_5
Functions:
~ __ZN17IOPortFeatureLDCM32_handleMitigationsForLiquidStateEb : 1616 -> 1828
CStrings:
+ "%s::%s(): [%s%s%s] Mitigations not supported\n\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.eLXOQo/Sources/IOAccessoryManager_Arrow/IOAccessoryIDBusTransport.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ATRBkp/Sources/IOAccessoryManager_Arrow/IOAccessoryIDBusTransport.cpp"
```
