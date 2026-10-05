## exclave_pmm_exclave

> `Firmware/image4/exclavecore_bundle.t8152.RELEASE.im4p/exclave_pmm_exclave`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA.__const`
- `__DATA.__data`
- `__DATA.__auth_ptr`
- `__DATA.__shared_cache`
- `__DATA.__mod_init_func`

```diff

-1490.40.25.0.0
-  __TEXT.__text: 0x4d108
+1490.40.28.0.0
+  __TEXT.__text: 0x4d148
   __TEXT.__const: 0x1d140
-  __TEXT.__cstring: 0x125ec
+  __TEXT.__cstring: 0x12568
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0
   __TEXT.__term_offsets: 0x0

   __PDATA.__shared_cache: 0x0
   Functions: 14
   Symbols:   4
-  CStrings:  1531
+  CStrings:  1529
 
Functions:
~ sub_80156f8 -> sub_80156d8 : 7728 -> 7804
~ sub_8017528 -> sub_8017554 : 127632 -> 127636
~ sub_8036828 -> sub_8036858 : 256 -> 272
CStrings:
- "[PMM DEBUG] stats_describe_handler: returning success for statId=%u\n"
- "[PMM DEBUG] stats_describe_handler: statId=%u, total_count=%u\n"
```
