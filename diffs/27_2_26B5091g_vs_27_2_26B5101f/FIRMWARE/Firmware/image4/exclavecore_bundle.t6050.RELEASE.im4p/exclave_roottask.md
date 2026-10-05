## exclave_roottask

> `Firmware/image4/exclavecore_bundle.t6050.RELEASE.im4p/exclave_roottask`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_entry`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__DATA.__data`
- `__DATA.__shared_cache`
- `__DATA.__mod_init_func`
- `__DATA.__auth_ptr`
- `__DATA.__const`
- `__DATA.__got`
- `__DATA.__thread_vars`

```diff

-1490.40.25.0.0
-  __TEXT.__text: 0x4f2350
+1490.40.28.0.0
+  __TEXT.__text: 0x4f2530
   __TEXT.__lcxx_override: 0xe4
   __TEXT.__const: 0xf28a0
-  __TEXT.__cstring: 0x3e602
+  __TEXT.__cstring: 0x3e642
   __TEXT.__swift5_typeref: 0xd07c
   __TEXT.__swift5_capture: 0x155c
   __TEXT.__swift5_entry: 0x8

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x80
-  __TEXT.__eh_frame: 0x2215c
+  __TEXT.__eh_frame: 0x221cc
   __DATA.__data: 0xcf70
   __DATA.__shared_cache: 0x70
   __DATA.__mod_init_func: 0x58

   __DATA_CONST.__mod_term_func: 0x0
   __PDATA.__mod_init_func: 0x0
   __PDATA.__shared_cache: 0x0
-  Functions: 19314
+  Functions: 19321
   Symbols:   29
-  CStrings:  6110
+  CStrings:  6111
 
CStrings:
+ "Builtin.Borrow is not supported in runtime type lookup"
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
- "Initialized count set to greater than specified capacity."
```
