## com.apple.driver.AppleDisplayManager

> `com.apple.driver.AppleDisplayManager`

```diff

-700.50.104.0.0
+700.50.108.1.0
   __TEXT.__const: 0x8
-  __TEXT.__cstring: 0x2b9e
-  __TEXT_EXEC.__text: 0x944c
+  __TEXT.__cstring: 0x2db4
+  __TEXT_EXEC.__text: 0x9d74
   __TEXT_EXEC.__auth_stubs: 0x1c0
   __DATA.__data: 0xc8
   __DATA.__common: 0x60

   __DATA_CONST.__kalloc_type: 0x80
   __DATA_CONST.__auth_got: 0xe0
   __DATA_CONST.__got: 0x48
-  Functions: 132
-  Symbols:   503
-  CStrings:  248
+  Functions: 134
+  Symbols:   505
+  CStrings:  254
 
Symbols:
+ __ZL19is_display_dp_splitPK21IOAVDisplayConnectionPK7OSArray
+ __ZL29does_disp_have_multiple_tilesPK21IOAVDisplayConnectionPK7OSArrayS4_
+ __ZL35has_tiled_sibling_on_different_pipePK21IOAVDisplayConnectionPK20IOAVTiledDisplayInfoPK7OSArray
- __ZL29does_disp_have_multiple_tilesPK21IOAVDisplayConnection
CStrings:
+ "*****Dump tiled displays******\n"
+ "*****End of tiled displays******\n"
+ "AED %s: fb %u is DP-Split; skipping rearrange for it\n"
+ "AED %s: fb %u is tiled; skipping rearrange for it\n"
+ "AED: %s: committing %u display connection(s) to crossbar, testOnly %d\n"
+ "AED: %s: fb %u rejecting request, exceeds full dual-pipe allocation (w %u vs %u, bw %llu vs %llu)\n"
+ "AED: %s: fb %u rejecting request, exceeds single-pipe availability (w %u vs %u, bw %llu vs %llu)\n"
+ "AED: %s: fb %u shrink 2->1: w req %u vs single %u, bw req %llu vs single %llu\n"
+ "AED: fb %u fits one pipe, capping its width offer at %u instead of %u so the full pair stays for a native dual pipe display"
- "AED: FB %d: reallocation (2->1)\n"
- "AED: request is beyond resource limits\n"
- "request is beyond resource limits\n"
```
