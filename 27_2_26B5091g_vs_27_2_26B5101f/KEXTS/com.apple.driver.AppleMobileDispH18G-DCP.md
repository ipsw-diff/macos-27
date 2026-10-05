## com.apple.driver.AppleMobileDispH18G-DCP

> `com.apple.driver.AppleMobileDispH18G-DCP`

```diff

-700.50.104.0.0
+700.50.108.1.0
   __TEXT.__const: 0x1920
-  __TEXT.__cstring: 0x7377
-  __TEXT_EXEC.__text: 0x271a4
+  __TEXT.__cstring: 0x78dd
+  __TEXT_EXEC.__text: 0x278ac
   __TEXT_EXEC.__auth_stubs: 0xe40
   __DATA.__data: 0x393b8
   __DATA.__common: 0x120

   __DATA_CONST.__got: 0xd0
   Functions: 1495
   Symbols:   1920
-  CStrings:  599
+  CStrings:  613
 
Functions:
~ __ZN23IOMobileFramebufferShim10swap_startEPjP12IOUserClient : 360 -> 448
~ __ZN23IOMobileFramebufferShim29set_config_requires_dual_pipeEv : 224 -> 284
~ __ZN23IOMobileFramebufferShim20set_digital_out_modeEjj : 7324 -> 8976
CStrings:
+ "%s: Aborting set_digital_out_mode after dual pipe teardown on %d. HPD dropped during teardown, dual pipe timing cannot run on one pipe."
+ "%s: Dual pipe: fb %u issuing secondary modeset on fb %u (timing %u color %u)\n"
+ "%s: Dual pipe: fb %u primary VFTG link check done in %u ms, localStatus %u\n"
+ "%s: Dual pipe: fb %u primary modeset thread finished in %u ms, status 0x%x\n"
+ "%s: Dual pipe: fb %u waiting for primary VFTG link check, timeout %u ms\n"
+ "%s: Dual pipe: fb %u waiting for primary modeset thread, timeout %u ms\n"
+ "%s: modeset: fb %u is_dual=%d adm_forced=%d vftg_cfg=%d paired=%d hpd_dual_ok=%d timing=%u color=%u (%ux%u@%uHz)\n"
+ "%s: modeset: fb %u set_digital_out_mode returning 0x%x (timing %u color %u dual %d)\n"
+ "AED: fb %u could not read ADM pipe-count intent (0x%x); modesetting as single pipe\n"
+ "Aborting set_digital_out_mode after dual pipe teardown on %d. HPD dropped during teardown, dual pipe timing cannot run on one pipe."
+ "Dual pipe: fb %u issuing secondary modeset on fb %u (timing %u color %u)\n"
+ "Dual pipe: fb %u primary VFTG link check done in %u ms, localStatus %u\n"
+ "Dual pipe: fb %u primary modeset thread finished in %u ms, status 0x%x\n"
+ "Dual pipe: fb %u waiting for primary VFTG link check, timeout %u ms\n"
+ "Dual pipe: fb %u waiting for primary modeset thread, timeout %u ms\n"
+ "dual pipe: rejected swap_start on secondary fb %u (client %p)"
+ "modeset: fb %u is_dual=%d adm_forced=%d vftg_cfg=%d paired=%d hpd_dual_ok=%d timing=%u color=%u (%ux%u@%uHz)\n"
+ "modeset: fb %u set_digital_out_mode returning 0x%x (timing %u color %u dual %d)\n"
- "%s: Merge Config: Primary VFTG enable time %dms\n"
- "%s: Primary modeset time %dms\n"
- "Merge Config: Primary VFTG enable time %dms\n"
- "Primary modeset time %dms\n"
```
