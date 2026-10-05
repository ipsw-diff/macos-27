## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8142.RELEASE.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__mod_init_func`
- `__PDATA.__data`
- `__PDATA.__shared_cache`

```diff

-1777.40.28.0.2
-  __TEXT.__text: 0xd5f904
+1777.40.34.0.0
+  __TEXT.__text: 0xd69478
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0xa4a61
-  __TEXT.__const: 0x19cc54
-  __TEXT.__swift5_typeref: 0x2a366
-  __TEXT.__swift5_reflstr: 0x3d268
-  __TEXT.__swift5_assocty: 0xea50
-  __TEXT.__swift5_fieldmd: 0x5d674
-  __TEXT.__constg_swiftt: 0x626f0
-  __TEXT.__swift5_protos: 0x121c
-  __TEXT.__swift5_proto: 0x9c10
-  __TEXT.__swift5_types: 0x5fac
+  __TEXT.__cstring: 0xa5381
+  __TEXT.__const: 0x19d054
+  __TEXT.__swift5_typeref: 0x2a456
+  __TEXT.__swift5_reflstr: 0x3d478
+  __TEXT.__swift5_assocty: 0xea68
+  __TEXT.__swift5_fieldmd: 0x5d84c
+  __TEXT.__constg_swiftt: 0x62968
+  __TEXT.__swift5_protos: 0x1220
+  __TEXT.__swift5_proto: 0x9c2c
+  __TEXT.__swift5_types: 0x5fc4
   __TEXT.__swift5_types2: 0xc0
   __TEXT.__swift5_builtin: 0x2760
-  __TEXT.__swift5_capture: 0x3538
-  __TEXT.__objc_methtype: 0x2d6
+  __TEXT.__swift5_capture: 0x3558
+  __TEXT.__objc_methtype: 0x2f6
   __TEXT.__swift5_mpenum: 0xc34
-  __TEXT.__swift_as_entry: 0x1658
-  __TEXT.__swift_as_ret: 0x1870
-  __TEXT.__swift_as_cont: 0x2f3c
-  __TEXT.__oslogstring: 0x6cc7
+  __TEXT.__swift_as_entry: 0x168c
+  __TEXT.__swift_as_ret: 0x18ac
+  __TEXT.__swift_as_cont: 0x2f94
+  __TEXT.__oslogstring: 0x6ee7
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x128
-  __TEXT.__eh_frame: 0x76cf4
+  __TEXT.__eh_frame: 0x77258
   __DATA.__TIGHTBEAM_VT: 0x1200
   __DATA.__TIGHTBEAM: 0x4a8
-  __DATA.__const: 0xe3630
-  __DATA.__data: 0x4f6e0
+  __DATA.__const: 0xe3998
+  __DATA.__data: 0x4f988
   __DATA.__mod_init_func: 0x40
-  __DATA.__ENDPOINTS: 0x1bbd0
-  __DATA.__auth_ptr: 0x7570
+  __DATA.__ENDPOINTS: 0x1bcd7
+  __DATA.__auth_ptr: 0x7598
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x3b8
   __DATA.__DARTS: 0x93f

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0x24aa0
-  __DATA.__common: 0x2961
+  __DATA.__bss: 0x24ab0
+  __DATA.__common: 0x2951
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6810
   __PDATA.__objc_imageinfo: 0x8

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 47652
+  Functions: 47754
   Symbols:   1
-  CStrings:  15137
+  CStrings:  15200
 
CStrings:
+ " DisplayManager is not configured!"
+ " but a session is already active!"
+ " but startTimestampUS is nil!"
+ " deferrals(hwBusy)="
+ " deferrals(pipelineBusy)="
+ " for Storage exclave"
+ " gateEarlyRejects="
+ " gateExemptedBuffers="
+ " is not a valid integer: "
+ " lastVerdictAge="
+ " opted into prefers-waiting-through-sleep, blocking: "
+ " parked request(s) with mappers disabled; they will submit against unmapped DART state"
+ " parking until sleep cycle completes, parked: "
+ " rejected before IO prep. SleepCycle: "
+ "), deferring DART unmap"
+ "430.40.6"
+ ": initiating upcall (notification ID: "
+ ": notification done"
+ ": panicking to prevent MTE tag brute-forcing"
+ "; using no-op control"
+ "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Mon Sep 28 22:23:30 PDT 2026; root:AppleImage4_exclavecore-374~19122/ExclaveImage4/RELEASE_ARM64E"
+ "ANEExclave version: ANEExclave_exclavecore-13.102.1"
+ "Applying MTE backoff of "
+ "Build Date: Mon Sep 28 22:08:03 PDT 2026"
+ "Builtin.Borrow is not supported in runtime type lookup"
+ "Bundle metadata for "
+ "CompanionHandler: "
+ "CompanionHandler: %s: failed: %s"
+ "CompanionHandler: %s: initiating upcall (notification ID: %u)"
+ "CompanionHandler: %s: notification done"
+ "CompanionHandler: setupPowerDownAsyncSignal: setup done for ID: "
+ "CompanionHandler: setupPowerDownAsyncSignal: setup done for ID: %u"
+ "CompanionHandler: setupPowerUpAsyncSignal: setup done for ID: "
+ "CompanionHandler: setupPowerUpAsyncSignal: setup done for ID: %u"
+ "Conclave MTE tag check fault: esr="
+ "ENABLED via driver opt-in"
+ "Empty value of bundle metadata "
+ "ExclaveOS Image4 Framework Version 7.0.0: Mon Sep 28 22:23:30 PDT 2026; root:AppleImage4_exclavecore-374~19122/ExclaveImage4/RELEASE_ARM64E"
+ "In-flight HW or pipeline requests present (pipeline: "
+ "Initialized count must be in 0 ... unsafeUninitializedCapacity."
+ "Invalid log level "
+ "MTE tag check fault #"
+ "Mon Sep 28 22:53:10 PDT 2026"
+ "Park-through-sleep "
+ "ParkThroughSleep enabled: "
+ "SEP power control wired but SoC type is unknown; disabling SEP reset lockout"
+ "SEP reset lockout not supported on "
+ "SEP reset protection "
+ "SEP reset protection enabled: "
+ "SEP reset protection requested but no SEP control is wired on this part"
+ "SetLogLevelFromBundle()"
+ "SleepCycle parked requests: "
+ "SleepCycle pipeline count: "
+ "SleepCycle totals: parks="
+ "StorageExclaveComponent/XRTBundleResources.swift"
+ "[BrightnessCheck] NOT EVALUATED ("
+ "[SecureM3Handler] ERROR firmware load failed"
+ "[SecureM3Handler] MCPU power "
+ "[SecureM3Handler] MCPU power %ld -> %ld"
+ "disabled (default)"
+ "doPowerDownAsyncSignal"
+ "doPowerUpAsyncSignal"
+ "getBundleMetadata(_:)"
+ "notifyPowerStateToCompanion: no notification handler registered"
+ "notifyPowerStateToCompanion: powerUp:"
+ "notifyPowerStateToCompanion: powerUp:%{bool}d upcall took %fus"
+ "ns before launch"
+ "ns before next launch"
+ "releasePipelineReservation not called with workLoop Gate held!"
+ "sharedmem_framemap_getPhysicalAddress"
+ "sharedmem_framemap_setMapped_delta"
+ "takePipelineReservation called twice for request "
+ "takePipelineReservation not called with workLoop Gate held!"
+ "v24@?0{sharedmem_pagerange=QQ}8"
+ "waitForSleepCycleCompletion not called with workLoop Gate held!"
+ "writeFileInternal(client:catInfo:name:offset:length:encrypted:inputBuffer:)"
- " opted into prefers-waiting-through-sleep; option accepted but not yet implemented"
- "430.40.5"
- "@(#)VERSION:ExclaveOS Image4 Framework Version 7.0.0: Fri Sep 11 23:21:59 PDT 2026; root:AppleImage4_exclavecore-374~18483/ExclaveImage4/RELEASE_ARM64E"
- "ANEExclave version: ANEExclave_exclavecore-13.101.1"
- "Build Date: Fri Sep 11 22:16:20 PDT 2026"
- "ExclaveOS Image4 Framework Version 7.0.0: Fri Sep 11 23:21:59 PDT 2026; root:AppleImage4_exclavecore-374~18483/ExclaveImage4/RELEASE_ARM64E"
- "In-flight HW requests present, deferring DART unmap"
- "Initialized count set to greater than specified capacity."
- "Tue Sep 15 13:13:25 PDT 2026"
- "localmap_map(%zx): localmap() remap with changed PA (%llx != %llx)\n"
- "sharedmem_framemap_getPhysicalAddresses"
- "sharedmem_framemap_setMapped"
- "writeFileInternal(client:catInfo:name:offset:length:encrypted:)"
```
