## ISP.mediacapture

> `/System/Library/MediaCapture/ISP.mediacapture`

```diff

-20.105.2.0.0
-  __TEXT.__text: 0x1af01c
+20.107.1.0.0
+  __TEXT.__text: 0x1af810
   __TEXT.__init_offsets: 0xc
-  __TEXT.__gcc_except_tab: 0x4aac
-  __TEXT.__const: 0x27ae5
-  __TEXT.__oslogstring: 0x1c94b
-  __TEXT.__cstring: 0x16a52
-  __TEXT.__unwind_info: 0x5708
+  __TEXT.__gcc_except_tab: 0x4aa8
+  __TEXT.__const: 0x27cdd
+  __TEXT.__oslogstring: 0x1ca06
+  __TEXT.__cstring: 0x16b28
+  __TEXT.__unwind_info: 0x5730
   __TEXT.__eh_frame: 0x50
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x8
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x1f68
-  __AUTH_CONST.__cfstring: 0x8300
+  __AUTH_CONST.__cfstring: 0x8360
   __AUTH_CONST.__weak_auth_got: 0xb0
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1350
-  __DATA.__data: 0x574e98
+  __AUTH_CONST.__auth_got: 0x1360
+  __DATA.__data: 0x5afe98
   __DATA.__bss: 0xab0
   __DATA.__common: 0x5728
   - /System/Library/Frameworks/Accelerate.framework/Versions/A/Accelerate

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 5136
-  Symbols:   7264
-  CStrings:  5933
+  Functions: 5147
+  Symbols:   7277
+  CStrings:  5946
 
Symbols:
+ GCC_except_table454
+ GCC_except_table526
+ GCC_except_table529
+ GCC_except_table547
+ GCC_except_table677
+ _ZN3ISP29ISPGraphExclaveSecureDataNode22EnsureBufferPoolsReadyEv
+ _ZN3ISP9ISPDevice19CacheChannelConfigsEj
+ __ZN3ISP29ISPGraphExclaveSecureDataNode22EnsureBufferPoolsReadyEv
+ __ZN3ISP9ISPDevice19CacheChannelConfigsEj
+ __ZN3ISP9ISPDevice26ISP_CopyChannelConfigCacheEjP21ISPChannelConfigCache
+ __ZN3ISP9ISPDevice29ISP_RefreshChannelConfigCacheEj
+ __ZN3ISP9ISPDevice35InvokeDeviceMessageNotificationProcEjPv
+ __ZN3ISPL24IMX714_setfile_2027_01XXE
+ __ZN3ISPL24IMX914_setfile_2327_01XXE
+ __ZN3ISPL24IMX914_setfile_2327_02XXE
+ _os_unfair_lock_lock
+ _os_unfair_lock_unlock
- GCC_except_table527
- GCC_except_table545
- GCC_except_table674
- _ZN3ISP29ISPGraphExclaveSecureDataNode10onActivateEv
CStrings:
+ "%s - Error reading kernel config cache - chan: %d, res: 0x%08X\n"
+ "%s - [Exclaves]: [ERROR]: ch%u: buffer pools unavailable, dropping frame %u\n"
+ "%s - channel configs not valid - exiting\n"
+ "%s - kernel config count %d != firmware %d - chan: %d\n"
+ "/usr/local/share/firmware/isp/2027_01XX.dat"
+ "/usr/local/share/firmware/isp/2327_01XX.dat"
+ "/usr/local/share/firmware/isp/2327_02XX.dat"
+ "AECounter_Private"
+ "CacheChannelConfigs"
+ "Could not find %s as %s (errno: %d)"
+ "EnsureBufferPoolsReady"
+ "Found %s at %s."
+ "ISPCaptureStreamStart - EnableDolbyVisionMetadata error: 0x%08X\n\n"
+ "Will use ISP references"
+ "Will use SEP references"
+ "sparse reference plist"
+ "sparseLP reference plist"
- "%s - Error getting LSC polynomial - chan: %d, res: 0x%08X\n"
- "%s - Error getting camera config - chan: %d, res: 0x%08X\n"
- "Could not find reference plist at %s (errno: %d). Will use ISP references"
- "Found reference plist at %s. Will use SEP references"
```
