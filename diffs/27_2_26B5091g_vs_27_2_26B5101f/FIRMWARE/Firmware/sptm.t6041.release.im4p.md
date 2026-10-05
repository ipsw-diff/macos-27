## sptm.t6041.release.im4p

> `Firmware/sptm.t6041.release.im4p`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__LATE_CONST.__late_const`

```diff

-820.40.20.0.1
-  __TEXT.__cstring: 0x158f6
+820.40.23.0.0
+  __TEXT.__cstring: 0x15bac
   __TEXT.__const: 0xa74
   __TEXT.__binname: 0x40
   __TEXT.__chain_starts: 0x14
   __DATA_CONST.__const: 0x7c00
   __LATE_CONST.__late_const: 0x8c9b0
-  __TEXT_EXEC.__text: 0x5f078
+  __TEXT_EXEC.__text: 0x5fdc0
   __TEXT_EXEC.__exc: 0x2000
   __LAST.__pinst: 0xc
   __DATA.__data: 0xf

   __DATA.__bss: 0x60a8
   __DATA.__common: 0x17088
   __BOOTDATA.__data: 0x18000
-  Functions: 399
+  Functions: 401
   Symbols:   1
-  CStrings:  2537
+  CStrings:  2550
 
CStrings:
+ "%s: Failed to verify TLBI"
+ "%s: The GMMU TLBI verification register should be 8B-aligned"
+ "%s: UAT Dekker gate acquisition timed out after %llu ns (spun for %llu cycles)"
+ "%s: UAT Dekker lock acquisition timed out after %llu ns (spun for %llu cycles)"
+ "%s: dart %p (%s:%u): relaxed_rw_protections and allow_pte_remap are not supported together"
+ "%s: gmmu-tlbi-verification-bit (%llu) is unset or out of range [0, 63]"
+ "%s: verify-gmmu-tlbis-at-sync is enabled but gmmu-tlbi-verification-reg is not set"
+ "0x4B1D000000000003ULL"
+ "SPTM-820.40.23|2026-09-27:20:05:06.102161|"
+ "gmmu-tlbi-verification-bit"
+ "gmmu-tlbi-verification-reg"
+ "hib_header_copy->handoffPageCount < HIB_HANDOFF_PAGECOUNT_LIMIT"
+ "uat_dekker_gate_lock"
+ "uat_dekkerlock_lock"
+ "uat_sync_outer_tlb_sapt_flush"
+ "verify-gmmu-tlbis-at-sync"
- "0x4B1D000000000002ULL"
- "SPTM-820.40.20.0.1|2026-09-13:18:57:31.262056|"
- "wrprot"
```
