## exclave_sharedcache

> `Firmware/image4/exclavecore_bundle.t6050.RELEASE.restore.im4p/exclave_sharedcache`

### Sections with Same Size but Changed Content

- `__TEXT.__swift5_types2`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_entry`
- `__TEXT.__chain_fixups`
- `__DATA.__TIGHTBEAM_VT`
- `__DATA.__TIGHTBEAM`
- `__DATA.__mod_init_func`
- `__DATA.__shared_cache`
- `__DATA.__got`
- `__PDATA.__auth_ptr`
- `__PDATA.__const`
- `__PDATA.__data`
- `__PDATA.__shared_cache`
- `__PDATA.__common`

```diff

-1777.0.20.0.0
-  __TEXT.__text: 0x5c7fb8
+1777.0.27.0.0
+  __TEXT.__text: 0x5ca8d4
   __TEXT.__lcxx_override: 0xe4
-  __TEXT.__cstring: 0x4e081
-  __TEXT.__const: 0x11f244
-  __TEXT.__swift5_typeref: 0x12eb8
-  __TEXT.__swift5_reflstr: 0x11228
-  __TEXT.__swift5_assocty: 0x78e8
-  __TEXT.__swift5_fieldmd: 0x1a614
-  __TEXT.__constg_swiftt: 0x25984
-  __TEXT.__swift5_protos: 0x8a4
-  __TEXT.__swift5_proto: 0x394c
-  __TEXT.__swift5_types: 0x2204
+  __TEXT.__cstring: 0x4e371
+  __TEXT.__const: 0x11f974
+  __TEXT.__swift5_typeref: 0x1302e
+  __TEXT.__swift5_reflstr: 0x11358
+  __TEXT.__swift5_assocty: 0x7a10
+  __TEXT.__swift5_fieldmd: 0x1a790
+  __TEXT.__constg_swiftt: 0x25a10
+  __TEXT.__swift5_protos: 0x8ac
+  __TEXT.__swift5_proto: 0x3a14
+  __TEXT.__swift5_types: 0x2220
   __TEXT.__swift5_types2: 0x60
-  __TEXT.__swift5_builtin: 0x1568
+  __TEXT.__swift5_builtin: 0x1590
   __TEXT.__swift5_capture: 0xf9c
   __TEXT.__objc_methtype: 0xe1
-  __TEXT.__swift5_mpenum: 0x39c
+  __TEXT.__swift5_mpenum: 0x3b4
   __TEXT.__swift_as_entry: 0x994
   __TEXT.__swift_as_ret: 0xb08
   __TEXT.__swift_as_cont: 0x11f8
-  __TEXT.__oslogstring: 0xb2
+  __TEXT.__oslogstring: 0xf0
   __TEXT.__swift5_entry: 0x8
   __TEXT.__constructor: 0x0
   __TEXT.__init_offsets: 0x0

   __TEXT.__term_offsets: 0x0
   __TEXT.__thread_starts: 0x0
   __TEXT.__chain_fixups: 0xb0
-  __TEXT.__eh_frame: 0x32dc4
+  __TEXT.__eh_frame: 0x32f9c
   __DATA.__TIGHTBEAM_VT: 0x720
   __DATA.__TIGHTBEAM: 0x1d8
-  __DATA.__const: 0x3abb8
-  __DATA.__data: 0x16650
+  __DATA.__const: 0x3ac98
+  __DATA.__data: 0x166e0
   __DATA.__mod_init_func: 0x40
-  __DATA.__ENDPOINTS: 0x1a221
-  __DATA.__auth_ptr: 0x1fd8
+  __DATA.__ENDPOINTS: 0x1a328
+  __DATA.__auth_ptr: 0x2008
   __DATA.__DEVICETREE: 0x18
   __DATA.__shared_cache: 0x380
   __DATA.__DARTS: 0x93f

   __DATA.__mod_term_func: 0x0
   __DATA.__thread_data: 0x0
   __DATA.__thread_bss: 0x30
-  __DATA.__bss: 0xe260
-  __DATA.__common: 0x6ba
+  __DATA.__bss: 0xe540
+  __DATA.__common: 0x6ca
   __PDATA.__auth_ptr: 0x280
   __PDATA.__const: 0x67b0
   __PDATA.__objc_imageinfo: 0x8

   __PDATA.__data: 0x2af0
   __PDATA.__ENDPOINTS: 0x838
   __PDATA.__shared_cache: 0x70
-  __PDATA.__bss: 0xc4b8
+  __PDATA.__bss: 0xba48
   __PDATA.__common: 0x2578
   __DATA_CONST.__mod_init_func: 0x0
   __DATA_CONST.__mod_term_func: 0x0
-  Functions: 22442
+  Functions: 22491
   Symbols:   1
-  CStrings:  7123
+  CStrings:  7141
 
CStrings:
+ "\n    Background factors: last="
+ " -> calculated XYZ:"
+ " [nits]\n    Indicator factors: last="
+ " sample is invalid, using max sample (lux="
+ ", BackgroundColor="
+ ", IndicatorColor="
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7YaW5m/Binaries/Tightbeam_exclavecore/install/TempContent/Objects/Tightbeam.build/Tightbeam_exclavecore.build/DerivedSources/tb_codec.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7YaW5m/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/Components/ComponentRuntime.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7YaW5m/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/Transports/cL4/cL4_transport.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7YaW5m/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/Transports/cL4_large/cL4_large_transport.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7YaW5m/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/message_accumulator.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7YaW5m/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/message_splitter.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7YaW5m/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/tb_connection.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7YaW5m/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/tb_first_contact.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7YaW5m/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/tb_message.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8oCRHE/Binaries/libtrace_exclavecore/install/TempContent/Objects/libtrace.build/libtrace_exclavecore.build/DerivedSources/OSLogExclaves_C.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8oCRHE/Sources/libtrace_exclavecore/LogServerExclaves/Sources/Overlay/libtrace.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8oCRHE/Sources/libtrace_exclavecore/libtrace-exclaves/backtrace.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8oCRHE/Sources/libtrace_exclavecore/libtrace-exclaves/console.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8oCRHE/Sources/libtrace_exclavecore/libtrace-exclaves/format.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8oCRHE/Sources/libtrace_exclavecore/libtrace-exclaves/log.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8oCRHE/Sources/libtrace_exclavecore/libtrace-exclaves/log_server.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8oCRHE/Sources/libtrace_exclavecore/libtrace-exclaves/tracepoint_internal.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8oCRHE/Sources/libtrace_exclavecore/libtrace-exclaves/utils.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.9pNKEe/Sources/DriverKit_services_exclavecore/ExclaveDriverKit/DeviceServer/DeviceServerCapabilities/DeviceServerCapabilities.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EHr2Vr/Sources/RTBuddy_exclavecore/RTBuddyExclaves/SecureRTBuddy/SecureRTBuddy.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EHr2Vr/Sources/RTBuddy_exclavecore/RTBuddyExclaves/SecureRTBuddy/SecureRTBuddyDeviceTreeHelper.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EHr2Vr/Sources/RTBuddy_exclavecore/RTBuddyExclaves/SecureRTBuddyCore/RTBuddyCL4ProxyConnection.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Binaries/ExclavePlatform_services_exclavecore/install/TempContent/Objects/xnu-proxy.build/xnu-proxy.build/DerivedSources/XnuProxy_C.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/native-scheduler/XrtHosted/hosted.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/allocator.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/constant.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/cpus.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/scheduler.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/scheduler_early_init.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/thread.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/thread.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/turnstile.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/downcall.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/exclaves.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/main.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/panic.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/upcall.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.YbGrRv/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/xnu.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZzXeRD/Sources/ExclaveSharedMemory_services_exclavecore/SharedMemoryComponent/SharedMemoryServer-utils.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZzXeRD/Sources/ExclaveSharedMemory_services_exclavecore/SharedMemoryComponent/SharedMemoryServer.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZzXeRD/Sources/ExclaveSharedMemory_services_exclavecore/SharedMemoryComponent/shmem_component_helper.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.cFRrAK/Binaries/ExclaveStackshot_services_exclavecore/install/TempContent/Objects/ExclaveStackshot.build/StackshotLayoutManagerComponent.build/DerivedSources/StackshotLayoutManagerComponent_c.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.jxQZzO/Sources/swiftlang_stdlib_exclavecore/swift/lib/Demangling/Demangler.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.lpz1u2/Sources/DebugExclave_exclavecore/debug/dbgexclave_message.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mbVHK1/Sources/AppleSEPManager_exclavecore/ExclaveSEPManager/Sources/ExclaveSEPManager/ExclaveSEPControl.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mbVHK1/Sources/AppleSEPManager_exclavecore/ExclaveSEPManager/Sources/ExclaveSEPManager/ExclaveSEPEndpoint.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mbVHK1/Sources/AppleSEPManager_exclavecore/ExclaveSEPManager/Sources/ExclaveSEPManager/ExclaveSEPManager.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mxCCp0/Sources/DriverKit_exclavecore/ExclaveDriverKit/DeviceTreeKit/DeviceTreeKit.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mxCCp0/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_AnyIOMemoryDescriptor/_AnyIOMemoryDescriptorDMADeviceReadMap.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mxCCp0/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_AnyIOMemoryDescriptor/_AnyIOMemoryDescriptorDMADeviceReadWriteMap.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mxCCp0/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_AnyIOMemoryDescriptor/_AnyIOMemoryDescriptorReadMap.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mxCCp0/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_AnyIOMemoryDescriptor/_AnyIOMemoryDescriptorReadWriteMap.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mxCCp0/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_IOMemoryDescriptorGeneric/_IOMemoryDescriptorGenericDMAMap.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.mxCCp0/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_IOMemoryDescriptorGeneric/_IOMemoryDescriptorGenericPreparation.swift"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Binaries/ExclavePlatform_exclavecore/install/TempContent/Objects/ExclavePlatform.build/EntropyBroker.build/DerivedSources/EntropyBroker_C.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Binaries/ExclavePlatform_exclavecore/install/TempContent/Objects/ExclavePlatform.build/libvas.build/DerivedSources/EASM_C.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Binaries/ExclavePlatform_exclavecore/install/TempContent/Objects/xnu-proxy.build/panichandler.build/DerivedSources/StackshotPanicInfo_C.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Binaries/ExclavePlatform_exclavecore/install/TempContent/Objects/xnu-proxy.build/panichandler.build/DerivedSources/StackshotSupport_C.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/DeviceMemoryContext/device_memory_context.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/common/platform_vas.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/common/serial/serial_common.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/liblibc_plat_cl4_standalone/liblibc_plat_cl4_vmem.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/libvas/Source/shadow.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/libvas/Source/shadow.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/libvas/Source/sharedmem-util.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/libvas/Source/sharedmemory.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/libvas/Source/span.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/libvas/Source/vas.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xnu-proxy/panic-handler/panic.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/arch/arm64/exception.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/exception.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/irq.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/notify.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/process.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/sync.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/sync_trace.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/thread.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/thread_id.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/debug/trace.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.q1hGVM/Sources/ExclavePlatform_exclavecore/xrt/xrt/ipc/endpoint.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sgn58Z/Binaries/ExclaveStackshot_exclavecore/install/TempContent/Objects/ExclaveStackshot.build/StackshotDelegateComponent_ec.build/DerivedSources/StackshotDelegateComponent_C.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sgn58Z/Binaries/ExclaveStackshot_exclavecore/install/TempContent/Objects/ExclaveStackshot.build/StackshotDelegateSupport_ec.build/DerivedSources/StackshotDelegate_C.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sgn58Z/Sources/ExclaveStackshot_exclavecore/StackshotDelegateComponent/stackshot_delegate.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.u4SxwZ/Binaries/ExclaveSharedMemory_exclavecore/install/TempContent/Objects/ExclaveSharedMemory.build/SharedMemory_ec.build/DerivedSources/SharedMemory_C.c"
+ "Calculated XYZ and supplied XYZ for background color are too far from each other, original RGB:"
+ "Calculated XYZ and supplied XYZ for indicator color are too far from each other, original RGB:"
+ "Can't skip by a negative offset"
+ "Chill pill usage is "
+ "EXBrightComponent/EXBrightComponent_swift.swift"
+ "EXBrightComponent/Extensions.swift"
+ "EXBrightDefines/EXBrightDefines_swift.swift"
+ "EXBrightDisplayPipeClient/EXBrightDisplayPipeClient_swift.swift"
+ "EXBrightPILEICClient/EXBrightPILEICClient_swift.swift"
+ "Escaping Closure Propagated"
+ "Failed to calibrate sensor(s), setting dispatchUpcallOnSILEnabled=true"
+ "MMIO read: addr=%p value=0x%llx"
+ "MMIO read: addr=%p value=0x%x"
+ "MMIO write: addr=%p value=0x%x"
+ "Queue size must > 0"
+ "Swift/BorrowingSequence.swift"
+ "[EIC] MMIO read: addr=%p value=0x%llx\n"
+ "[EIC] MMIO read: addr=%p value=0x%x\n"
+ "[EIC] MMIO write: addr=%p value=0x%x\n"
+ "] Brightness health nil when expecting a value - setting to false"
+ "] Cannot estimate ramp duration, invalid target brightness value: "
+ "] Contrast Health "
+ "] Contrast failure session began"
+ "] Contrast failure session continuing, passing since "
+ "] Contrast failure session ending"
+ "] Contrast failure session longer than grace period for applying soft boundary, reporting failure"
+ "] Contrast failure session still in grace period ("
+ "] Contrast health for frame #"
+ "] ContrastCheckResult="
+ "] Failed to create BrightnessUtil, health checks will not be available!"
+ "] Hibernation count has changed, reporting bad health"
+ "] Indicator Brightness Health "
+ "] Indicator brightness health for frame #"
+ "] No MIB before first sample, ignoring .failureNoMIB"
+ "] Overflow when substracting timestamps, frame ts: "
+ "] Received MIB with SIL off"
+ "] SCA factor is 0, requesting soft boundary"
+ "] SIL not enabled when requesting soft boundary"
+ "] Setting UI Brightness "
+ "] Soft boundary minimum ontime not met"
+ "] Switched to MIB ramp up mode during brightness ramp down, ignoring this frame."
+ "] Underflow in contrast failure session recovery check, "
+ "] Underflow in soft boundary SIL session start grace period evaluation - "
+ "] Underflow when checking minimum ontime for soft boundary"
+ "] Waking up from hibernation with soft boundary state as enabled!"
+ "] We have received empty array of frames for health check!"
+ "][EXDisplayPipe Utilization] Health Check took "
+ "][evaluateContrastHealth] Contrast is progressing, returning success"
+ "][healthCheckMode] .rampUp -> .steady. Ctx: adjustedIBNitsFiltered="
+ "malloc assertion \"!(zone->xzz_memtag_config.enabled && zone->xzz_memtag_config.max_block_size > XZM_SMALL_BLOCK_SIZE_MAX)\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:981)"
+ "malloc assertion \"!memtag_config.tag_data\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8865)"
+ "malloc assertion \"((uintptr_t)segment >> XZM_METAPOOL_SEGMENT_BLOCK_SHIFT) < XZM_SEGMENT_TABLE_LIMIT_ENTRY\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/../xzone_malloc/xzone_inline_internal.h:195)"
+ "malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8293)"
+ "malloc assertion \"(quarantine && chunk->xzc_empty_count) || (!quarantine && chunk->xzc_guard_count > gc->xxgc_density)\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:719)"
+ "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2730)"
+ "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2905)"
+ "malloc assertion \"allocation_front_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7834)"
+ "malloc assertion \"allocation_front_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:969)"
+ "malloc assertion \"chunk->xzc_empty_count\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:458)"
+ "malloc assertion \"middle_pte % XZM_PAGE_TABLE_GRANULE == 0\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:995)"
+ "malloc assertion \"middle_pte_middle < ranges[0].max_address\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:1035)"
+ "malloc assertion \"old_size\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6830)"
+ "malloc assertion \"range_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:990)"
+ "malloc assertion \"ranges[0].min_address < middle_pte_middle\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:1034)"
+ "malloc assertion \"ranges[0].min_address < ranges[0].max_address\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:971)"
+ "malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:2197)"
+ "malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.igIbiM/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5336)"
+ "minItems must be >= 1"
+ "octopus_chill_pill_stability"
- "\n    Background RGB: last="
- " [nits]\n    Indicator RGB: last="
- ", BackgroundRGB="
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Binaries/ExclavePlatform_exclavecore/install/TempContent/Objects/ExclavePlatform.build/EntropyBroker.build/DerivedSources/EntropyBroker_C.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Binaries/ExclavePlatform_exclavecore/install/TempContent/Objects/ExclavePlatform.build/libvas.build/DerivedSources/EASM_C.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Binaries/ExclavePlatform_exclavecore/install/TempContent/Objects/xnu-proxy.build/panichandler.build/DerivedSources/StackshotPanicInfo_C.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Binaries/ExclavePlatform_exclavecore/install/TempContent/Objects/xnu-proxy.build/panichandler.build/DerivedSources/StackshotSupport_C.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/DeviceMemoryContext/device_memory_context.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/common/platform_vas.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/common/serial/serial_common.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/liblibc_plat_cl4_standalone/liblibc_plat_cl4_vmem.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/libvas/Source/shadow.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/libvas/Source/shadow.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/libvas/Source/sharedmem-util.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/libvas/Source/sharedmemory.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/libvas/Source/span.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/libvas/Source/vas.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xnu-proxy/panic-handler/panic.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/arch/arm64/exception.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/exception.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/irq.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/notify.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/process.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/sync.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/sync_trace.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/thread.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/concurrency/thread_id.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/debug/trace.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.2RnX0V/Sources/ExclavePlatform_exclavecore/xrt/xrt/ipc/endpoint.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.5fVTMW/Sources/DriverKit_exclavecore/ExclaveDriverKit/DeviceTreeKit/DeviceTreeKit.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.5fVTMW/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_AnyIOMemoryDescriptor/_AnyIOMemoryDescriptorDMADeviceReadMap.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.5fVTMW/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_AnyIOMemoryDescriptor/_AnyIOMemoryDescriptorDMADeviceReadWriteMap.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.5fVTMW/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_AnyIOMemoryDescriptor/_AnyIOMemoryDescriptorReadMap.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.5fVTMW/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_AnyIOMemoryDescriptor/_AnyIOMemoryDescriptorReadWriteMap.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.5fVTMW/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_IOMemoryDescriptorGeneric/_IOMemoryDescriptorGenericDMAMap.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.5fVTMW/Sources/DriverKit_exclavecore/ExclaveDriverKit/ExclaveDriverKit/Memory/_IOMemoryDescriptorGeneric/_IOMemoryDescriptorGenericPreparation.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BOKs5n/Binaries/ExclaveSharedMemory_exclavecore/install/TempContent/Objects/ExclaveSharedMemory.build/SharedMemory_ec.build/DerivedSources/SharedMemory_C.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BUzbve/Binaries/libtrace_exclavecore/install/TempContent/Objects/libtrace.build/libtrace_exclavecore.build/DerivedSources/OSLogExclaves_C.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BUzbve/Sources/libtrace_exclavecore/LogServerExclaves/Sources/Overlay/libtrace.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BUzbve/Sources/libtrace_exclavecore/libtrace-exclaves/backtrace.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BUzbve/Sources/libtrace_exclavecore/libtrace-exclaves/console.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BUzbve/Sources/libtrace_exclavecore/libtrace-exclaves/format.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BUzbve/Sources/libtrace_exclavecore/libtrace-exclaves/log.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BUzbve/Sources/libtrace_exclavecore/libtrace-exclaves/log_server.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BUzbve/Sources/libtrace_exclavecore/libtrace-exclaves/tracepoint_internal.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.BUzbve/Sources/libtrace_exclavecore/libtrace-exclaves/utils.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.C0LF1X/Binaries/Tightbeam_exclavecore/install/TempContent/Objects/Tightbeam.build/Tightbeam_exclavecore.build/DerivedSources/tb_codec.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.C0LF1X/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/Components/ComponentRuntime.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.C0LF1X/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/Transports/cL4/cL4_transport.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.C0LF1X/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/Transports/cL4_large/cL4_large_transport.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.C0LF1X/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/message_accumulator.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.C0LF1X/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/message_splitter.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.C0LF1X/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/tb_connection.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.C0LF1X/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/tb_first_contact.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.C0LF1X/Sources/Tightbeam_exclavecore/Runtime/Tightbeam/tb_message.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.Ff9iYt/Binaries/ExclaveStackshot_exclavecore/install/TempContent/Objects/ExclaveStackshot.build/StackshotDelegateComponent_ec.build/DerivedSources/StackshotDelegateComponent_C.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.Ff9iYt/Binaries/ExclaveStackshot_exclavecore/install/TempContent/Objects/ExclaveStackshot.build/StackshotDelegateSupport_ec.build/DerivedSources/StackshotDelegate_C.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.Ff9iYt/Sources/ExclaveStackshot_exclavecore/StackshotDelegateComponent/stackshot_delegate.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PBwZw7/Sources/ExclaveSharedMemory_services_exclavecore/SharedMemoryComponent/SharedMemoryServer-utils.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PBwZw7/Sources/ExclaveSharedMemory_services_exclavecore/SharedMemoryComponent/SharedMemoryServer.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PBwZw7/Sources/ExclaveSharedMemory_services_exclavecore/SharedMemoryComponent/shmem_component_helper.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PHD2Xt/Binaries/ExclaveStackshot_services_exclavecore/install/TempContent/Objects/ExclaveStackshot.build/StackshotLayoutManagerComponent.build/DerivedSources/StackshotLayoutManagerComponent_c.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.SrFklq/Sources/AppleSEPManager_exclavecore/ExclaveSEPManager/Sources/ExclaveSEPManager/ExclaveSEPControl.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.SrFklq/Sources/AppleSEPManager_exclavecore/ExclaveSEPManager/Sources/ExclaveSEPManager/ExclaveSEPEndpoint.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.SrFklq/Sources/AppleSEPManager_exclavecore/ExclaveSEPManager/Sources/ExclaveSEPManager/ExclaveSEPManager.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.XKUcCZ/Sources/DebugExclave_exclavecore/debug/dbgexclave_message.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.bLPqjD/Sources/swiftlang_stdlib_exclavecore/swift/lib/Demangling/Demangler.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Binaries/ExclavePlatform_services_exclavecore/install/TempContent/Objects/xnu-proxy.build/xnu-proxy.build/DerivedSources/XnuProxy_C.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/native-scheduler/XrtHosted/hosted.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/allocator.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/constant.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/cpus.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/scheduler.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/scheduler_early_init.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/thread.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/thread.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/native-scheduler/native-scheduler/turnstile.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/downcall.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/exclaves.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/main.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/panic.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/upcall.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rSgAJi/Sources/ExclavePlatform_services_exclavecore/xnu-proxy/src/xnu.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rkWezK/Sources/RTBuddy_exclavecore/RTBuddyExclaves/SecureRTBuddy/SecureRTBuddy.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rkWezK/Sources/RTBuddy_exclavecore/RTBuddyExclaves/SecureRTBuddy/SecureRTBuddyDeviceTreeHelper.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.rkWezK/Sources/RTBuddy_exclavecore/RTBuddyExclaves/SecureRTBuddyCore/RTBuddyCL4ProxyConnection.swift"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.zIIR3q/Sources/DriverKit_services_exclavecore/ExclaveDriverKit/DeviceServer/DeviceServerCapabilities/DeviceServerCapabilities.c"
- "Brightness health nil when expecting a value - setting to false"
- "Cannot estimate ramp duration, invalid target brightness value: "
- "Contrast Health "
- "Contrast failure session began"
- "Contrast failure session continuing, passing since "
- "Contrast failure session ending"
- "Contrast failure session longer than grace period for applying soft boundary, reporting failure"
- "Contrast failure session still in grace period ("
- "Contrast health for frame #"
- "ContrastCheckResult="
- "EXBrightComponent/EXBrightComponent_Swift.swift"
- "EXBrightDisplayPipeClient/EXBrightDisplayPipeClient_Swift.swift"
- "EXBrightPILEICClient/EXBrightPILEICClient_Swift.swift"
- "Failed to create BrightnessUtil, health checks will not be available!"
- "Hibernation count has changed, reporting bad health"
- "Indicator Brightness Health "
- "Indicator brightness health for frame #"
- "MMIO Write: addr=%p value=0x%x"
- "No MIB before first sample, ignoring .failureNoMIB"
- "Overflow when substracting timestamps, frame ts: "
- "Received MIB with SIL off"
- "SCA factor is 0, requesting soft boundary"
- "SIL not enabled when requesting soft boundary"
- "Setting UI Brightness "
- "Soft boundary minimum ontime not met"
- "Switched to MIB ramp up mode during brightness ramp down, ignoring this frame."
- "Underflow in contrast failure session recovery check, "
- "Underflow in soft boundary SIL session start grace period evaluation - "
- "Underflow when checking minimum ontime for soft boundary"
- "Unexpected size!"
- "Waking up from hibernation with soft boundary state as enabled!"
- "We have received empty array of frames for health check!"
- "[EIC] MMIO Write: addr=%p value=0x%x\n"
- "[EXDisplayPipe Utilization] Health Check took "
- "[evaluateContrastHealth] Contrast is progressing, returning success"
- "[healthCheckMode] .rampUp -> .steady. Ctx: adjustedIBNitsFiltered="
- "malloc assertion \"!(zone->xzz_memtag_config.enabled && zone->xzz_memtag_config.max_block_size > XZM_SMALL_BLOCK_SIZE_MAX)\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:981)"
- "malloc assertion \"!memtag_config.tag_data\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8865)"
- "malloc assertion \"((uintptr_t)segment >> XZM_METAPOOL_SEGMENT_BLOCK_SHIFT) < XZM_SEGMENT_TABLE_LIMIT_ENTRY\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/../xzone_malloc/xzone_inline_internal.h:195)"
- "malloc assertion \"(chunk_capacity & 1) == 0 || chunk_padding != 0\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:8293)"
- "malloc assertion \"(quarantine && chunk->xzc_empty_count) || (!quarantine && chunk->xzc_guard_count > gc->xxgc_density)\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:719)"
- "malloc assertion \"(uintptr_t)segment < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2730)"
- "malloc assertion \"(uintptr_t)segment_body < XZM_LIMIT_ADDRESS\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:2905)"
- "malloc assertion \"allocation_front_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:7834)"
- "malloc assertion \"allocation_front_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:969)"
- "malloc assertion \"chunk->xzc_empty_count\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:458)"
- "malloc assertion \"middle_pte % XZM_PAGE_TABLE_GRANULE == 0\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:995)"
- "malloc assertion \"middle_pte_middle < ranges[0].max_address\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:1035)"
- "malloc assertion \"old_size\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:6830)"
- "malloc assertion \"range_count == 2\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:990)"
- "malloc assertion \"ranges[0].min_address < middle_pte_middle\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:1034)"
- "malloc assertion \"ranges[0].min_address < ranges[0].max_address\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_segment.c:971)"
- "malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:2197)"
- "malloc assertion \"success\" failed (/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.sN9Alc/Sources/libmalloc_exclavecore/src/xzone_malloc/xzone_malloc.c:5336)"
```
