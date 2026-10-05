## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t8140.RELEASE.im4p/exclave_sharedcache`

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
-  __TEXT.__text: 0xd74b48
+1777.40.34.0.0
+  __TEXT.__text: 0xd7e6b8
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0xa3cb1
-  __TEXT.__const: 0x1cf324
-  __TEXT.__swift5_typeref: 0x2a27e
-  __TEXT.__swift5_reflstr: 0x44168
-  __TEXT.__swift5_assocty: 0xe650
-  __TEXT.__swift5_fieldmd: 0x6d7a8
-  __TEXT.__constg_swiftt: 0x64cb8
-  __TEXT.__swift5_protos: 0x1194
-  __TEXT.__swift5_proto: 0xa56c
-  __TEXT.__swift5_types: 0x6778
+  __TEXT.__cstring: 0xa45d1
+  __TEXT.__const: 0x1cf724
+  __TEXT.__swift5_typeref: 0x2a35e
+  __TEXT.__swift5_reflstr: 0x44378
+  __TEXT.__swift5_assocty: 0xe668
+  __TEXT.__swift5_fieldmd: 0x6d980
+  __TEXT.__constg_swiftt: 0x64f30
+  __TEXT.__swift5_protos: 0x1198
+  __TEXT.__swift5_proto: 0xa588
+  __TEXT.__swift5_types: 0x6790
   __TEXT.__swift5_types2: 0xbc
   __TEXT.__swift5_builtin: 0x2738
-  __TEXT.__swift5_capture: 0x3638
-  __TEXT.__objc_methtype: 0x2d6
+  __TEXT.__swift5_capture: 0x3658
+  __TEXT.__objc_methtype: 0x2f6
   __TEXT.__swift5_mpenum: 0xbdc
-  __TEXT.__swift_as_entry: 0x15f0
-  __TEXT.__swift_as_ret: 0x1844
-  __TEXT.__swift_as_cont: 0x2eac
-  __TEXT.__oslogstring: 0x6bb7
+  __TEXT.__swift_as_entry: 0x1624
+  __TEXT.__swift_as_ret: 0x1880
+  __TEXT.__swift_as_cont: 0x2f04
+  __TEXT.__oslogstring: 0x6dd7
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0x140
-  __TEXT.__eh_frame: 0x750c8
+  __TEXT.__eh_frame: 0x7562c
   __DATA.__TIGHTBEAM_VT: 0x1080
   __DATA.__TIGHTBEAM: 0x448
-  __DATA.__const: 0x11c088
-  __DATA.__data: 0x50638
+  __DATA.__const: 0x11c3f0
+  __DATA.__data: 0x508e0
   __DATA.__mod_init_func: 0x48
-  __DATA.__ENDPOINTS: 0x1bbd0
-  __DATA.__auth_ptr: 0x6280
+  __DATA.__ENDPOINTS: 0x1bcd7
+  __DATA.__auth_ptr: 0x62a8
   __DATA.__DEVICETREE: 0x30
   __DATA.__shared_cache: 0x3b8
   __DATA.__DARTS: 0x93f

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0x24770
-  __DATA.__common: 0x3d79
+  __DATA.__bss: 0x24780
+  __DATA.__common: 0x3d69
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x6810
   __PDATA.__objc_imageinfo: 0x8

   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 49377
+  Functions: 49479
   Symbols:   1
-  CStrings:  15103
+  CStrings:  15166
 
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
+ "Mon Sep 28 22:53:15 PDT 2026"
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
- "Tue Sep 15 13:13:33 PDT 2026"
- "localmap_map(%zx): localmap() remap with changed PA (%llx != %llx)\n"
- "sharedmem_framemap_getPhysicalAddresses"
- "sharedmem_framemap_setMapped"
- "writeFileInternal(client:catInfo:name:offset:length:encrypted:)"
```
