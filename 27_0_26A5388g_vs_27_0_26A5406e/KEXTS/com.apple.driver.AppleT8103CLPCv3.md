## com.apple.driver.AppleT8103CLPCv3

> `com.apple.driver.AppleT8103CLPCv3`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__DATA_CONST.__mod_init_func`
- `__DATA_CONST.__mod_term_func`
- `__DATA_CONST.__kalloc_type`
- `__DATA_CONST.__kalloc_var`
- `__DATA_CONST.__auth_got`
- `__DATA_CONST.__got`

```diff

-1794.0.24.0.0
-  __TEXT.__cstring: 0x388d
+1794.0.32.0.4
+  __TEXT.__cstring: 0x39ca
   __TEXT.__const: 0x9d8
-  __TEXT_EXEC.__text: 0x5bd8c
+  __TEXT_EXEC.__text: 0x5c270
   __TEXT_EXEC.__auth_stubs: 0x8a0
-  __DATA.__data: 0xb258
+  __DATA.__data: 0xb740
   __DATA.__common: 0xb900
   __DATA.__bss: 0x268
   __DATA_CONST.__mod_init_func: 0x110
   __DATA_CONST.__mod_term_func: 0x18
-  __DATA_CONST.__const: 0x5ec0
+  __DATA_CONST.__const: 0x60b8
   __DATA_CONST.__kalloc_type: 0x380
   __DATA_CONST.__kalloc_var: 0x370
   __DATA_CONST.__auth_got: 0x450
   __DATA_CONST.__got: 0xe0
-  Functions: 1326
-  Symbols:   1828
-  CStrings:  504
+  Functions: 1338
+  Symbols:   1835
+  CStrings:  508
 
Symbols:
+ _OUTLINED_FUNCTION_19
+ __ZN4clpc15PropertyFactory19setDataRateToEffortIfNS_13SimplePerfMapILb1ELm3ENS_19PerfMapPolicyDirectILm1ELm3ENS_5arrayIhLm1EEEhhLm0EEEEENS4_IjLm3EEEEEbRKT0_RKT1_jRjPvRNS_13PropertyFlagsE
+ __ZN4clpc15PropertyFactory25setFabricDataRateToEffortIfEEbRjPvRNS_13PropertyFlagsE
+ __ZN4clpc15PropertyFactory25setMemoryDataRateToEffortIfEEbRjPvRNS_13PropertyFlagsE
+ __ZN4clpc4CLPC26handleGetDeviceThermalModeERb
+ __ZN4clpc4CLPC26handleSetDeviceThermalModeEy
+ __ZN4clpc4pmgr17PMCVoterInterface22writePerfStateFloorRegEb
+ __ZN4clpc5power14PackageLimiterINS0_11T8103ConfigEE41setExternal100msContextualPowerModeBudgetEf
+ __ZNK4clpc5power14PackageLimiterINS0_11T8103ConfigEE41getExternal100msContextualPowerModeBudgetEv
- __ZN4clpc5power14PackageLimiterINS0_11T8103ConfigEE38setExternal1sContextualPowerModeBudgetEf
- __ZNK4clpc5power14PackageLimiterINS0_11T8103ConfigEE38getExternal1sContextualPowerModeBudgetEv
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/ane_perf_sampler_impl.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/ane_topology.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/apple_clpc.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/clpc.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/clpc.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_cluster_perf_sampler.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_cluster_perf_sampler_impl.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_core_memstall_sampler.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_core_perf_sampler_impl.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_dvfm_table_impl.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_sched_interface.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_temperature_sampler.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_timer.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_topology.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/cpu_uncore_perf_sampler.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/fabric_dvfm_table.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/gpu_dvfm_table.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/perf_map_impl.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/pmc_voter_interface.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/power_map.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZJS99J/Sources/AppleCLPC/CLPC/source/power_telemetry_pusher_impl.hpp"
+ "2026-08-05T21:55:45-07:00"
+ "AppleCLPC-1794.0.32.0.4"
+ "scratch_config.layout.stride == sizeof(uint32_t)"
+ "state.base_address"
+ "telemetry_pusher.init(powerTelemetryPusherConfig())"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/ane_perf_sampler_impl.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/ane_topology.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/apple_clpc.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/clpc.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/clpc.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_cluster_perf_sampler.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_cluster_perf_sampler_impl.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_core_memstall_sampler.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_core_perf_sampler_impl.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_dvfm_table_impl.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_sched_interface.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_temperature_sampler.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_timer.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_topology.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/cpu_uncore_perf_sampler.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/fabric_dvfm_table.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/gpu_dvfm_table.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/perf_map_impl.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/pmc_voter_interface.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.JxxHhF/Sources/AppleCLPC/CLPC/source/power_map.cpp"
- "2026-07-14T21:26:48-07:00"
- "AppleCLPC-1794.0.24"
```
