## libCoreFSCache.dylib

> `/System/Library/Frameworks/OpenGL.framework/Versions/A/Libraries/libCoreFSCache.dylib`

```diff

-404.0.0.0.0
-  __TEXT.__text: 0x55a4
+405.0.0.0.0
+  __TEXT.__text: 0x5804
   __TEXT.__const: 0x90
-  __TEXT.__cstring: 0x27a
-  __TEXT.__oslogstring: 0xaf9
-  __TEXT.__unwind_info: 0x230
+  __TEXT.__cstring: 0x27c
+  __TEXT.__oslogstring: 0xc1c
+  __TEXT.__unwind_info: 0x240
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x58
   __DATA_CONST.__got: 0x0

   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 117
+  Functions: 121
   Symbols:   129
-  CStrings:  78
+  CStrings:  83
 
CStrings:
+ "Unexpected: in-memory page-aligned size: %zu is larger than read-only on-disk file size: %zu by more than a page. Page size is %zu."
+ "fopen for resetting cache not permitted on read-only cache file."
+ "r"
+ "read-only cache is invalid or missing; not reinitializing"
+ "refusing to reset a read-only cache"
```
