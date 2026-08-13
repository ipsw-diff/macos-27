## com.apple.driver.AppleSPIMC

> `com.apple.driver.AppleSPIMC`

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

-39.0.0.0.0
+40.0.0.0.0
   __TEXT.__const: 0x10
-  __TEXT.__cstring: 0x177d
-  __TEXT_EXEC.__text: 0x70e8
+  __TEXT.__cstring: 0x179d
+  __TEXT_EXEC.__text: 0x712c
   __TEXT_EXEC.__auth_stubs: 0x250
   __DATA.__data: 0xc4
   __DATA.__common: 0x68

   __DATA_CONST.__got: 0x50
   Functions: 131
   Symbols:   458
-  CStrings:  165
+  CStrings:  166
 
Functions:
~ __ZN20AppleSPIMCController21_executeSPICommandPIOEP18AppleARMSPICommand : 3920 -> 3988
CStrings:
+ "%s %s:%d: transaction timeout!\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.r9vB84/Sources/AppleSPIMC/Kernel/AppleSPIMC.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.jcZ6YR/Sources/AppleSPIMC/Kernel/AppleSPIMC.cpp"
```
