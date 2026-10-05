## dyld

> `/System/ExclaveKit/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__all_image_info`

```diff

-27102.0.0.0.0
-  __TEXT.__text: 0x5c8d8
+27104.0.0.0.0
+  __TEXT.__text: 0x5caa4
   __TEXT.__const: 0x1c0ac
-  __TEXT.__cstring: 0xeca4
-  __TEXT.__unwind_info: 0x2380
+  __TEXT.__cstring: 0xed2e
+  __TEXT.__unwind_info: 0x2390
   __TEXT.__eh_frame: 0x50
   __DATA_CONST.__const: 0xb50
   __AUTH_CONST.__const: 0x3f50

   __DATA.__common: 0x550
   __DATA.__bss: 0xba408
   __DATA_DIRTY.__all_image_info: 0x170
-  Functions: 2763
-  Symbols:   2441
-  CStrings:  1477
+  Functions: 2767
+  Symbols:   2444
+  CStrings:  1480
 
Symbols:
+ __ZNK6mach_o6Header22parse_dylinker_commandERKNS0_15LoadCommandInfoEPNS_5ErrorE
+ __process_panicv
+ _process_panicv.panic
+ _xrt__process_panic_exception
- xrt_process_panicv.panic
CStrings:
+ "27104"
+ "load command #%d %.*s name offset too small"
+ "load command #%d %.*s not a dylib load command"
+ "load command #%d string start offset too small"
- "27102"
```
