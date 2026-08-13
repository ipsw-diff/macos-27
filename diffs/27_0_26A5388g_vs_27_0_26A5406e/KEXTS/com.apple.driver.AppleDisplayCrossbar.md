## com.apple.driver.AppleDisplayCrossbar

> `com.apple.driver.AppleDisplayCrossbar`

### Sections with Same Size but Changed Content

- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`

```diff

-417.0.3.0.0
+417.0.4.0.0
   __TEXT.__const: 0x1a4
-  __TEXT.__cstring: 0x4cc7
+  __TEXT.__cstring: 0x4de0
   __TEXT.__os_log: 0x689b
-  __TEXT_EXEC.__text: 0x3dd80
+  __TEXT_EXEC.__text: 0x3e130
   __TEXT_EXEC.__auth_stubs: 0x630
   __DATA.__data: 0xc4
   __DATA.__common: 0x4e8
   __DATA_CONST.__mod_init_func: 0xf0
   __DATA_CONST.__mod_term_func: 0xf0
-  __DATA_CONST.__const: 0x17d78
+  __DATA_CONST.__const: 0x17d88
   __DATA_CONST.__kalloc_type: 0x7c0
   __DATA_CONST.__kalloc_var: 0xa0
   __DATA_CONST.__auth_got: 0x318
   __DATA_CONST.__got: 0xf8
-  Functions: 2158
+  Functions: 2161
   Symbols:   2442
-  CStrings:  814
+  CStrings:  821
 
Symbols:
+ __ZN29AppleDisplayConnectionManager13updatePeerUFPEP25IODPSwitchAllocationStateP22AppleDisplayConnectionP10IODPTXPortS5_
- ___ZN29AppleDisplayConnectionManager27setDisplayConnectionMappingEP7OSArrayb_block_invoke_3
CStrings:
+ "auto connect must be disabled for seamless update\n"
+ "disconnect ufp(%d,%d) from dfp(%d,%d)\n"
+ "disconnect ufp(%d,%d) from ufp(%d,%d) seamlessly\n"
+ "no available peer pipe for rearrangement\n"
+ "no available ufp peer found seamlessly\n"
+ "rearrange only support single pipe\n"
+ "testOnly with success\n"
```
