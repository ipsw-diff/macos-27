## com.apple.security.AppleImage4

> `com.apple.security.AppleImage4`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA.__data`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__const`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__image4_exp`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`

```diff

 374.0.0.0.0
   __TEXT.__const: 0xe830
   __TEXT.__cstring: 0x686b
-  __TEXT_EXEC.__text: 0x24e8c
+  __TEXT_EXEC.__text: 0x24ecc
   __TEXT_EXEC.__auth_stubs: 0x7c0
   __DATA.__data: 0x758
   __DATA.__bss: 0x385
Functions:
~ _verify_ecdsa_sig : 372 -> 436
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JGa8Hj/Binaries/AppleImage4/install/Symbols/Image4"
+ "@(#)VERSION:Darwin Image4 Extension Version 7.0.0: Wed Aug  5 21:48:48 PDT 2026; root:AppleImage4-374~13656/AppleImage4/RELEASE_ARM64E"
+ "Darwin Image4 Extension Version 7.0.0: Wed Aug  5 21:48:48 PDT 2026; root:AppleImage4-374~13656/AppleImage4/RELEASE_ARM64E"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.TMtGK3/Binaries/AppleImage4/install/Symbols/Image4"
- "@(#)VERSION:Darwin Image4 Extension Version 7.0.0: Tue Jul 14 21:22:04 PDT 2026; root:AppleImage4-374~10022/AppleImage4/RELEASE_ARM64E"
- "Darwin Image4 Extension Version 7.0.0: Tue Jul 14 21:22:04 PDT 2026; root:AppleImage4-374~10022/AppleImage4/RELEASE_ARM64E"
```
