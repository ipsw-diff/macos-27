## launchd

> `/sbin/launchd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_capture`
- `__TEXT.__dof_launchd`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`
- `__DATA.__os_assumes_log`

```diff

-3298.0.26.0.2
-  __TEXT.__text: 0x5bff0
+3298.1.1.0.0
+  __TEXT.__text: 0x5be58
   __TEXT.__auth_stubs: 0x23b0
   __TEXT.__init_offsets: 0x4
   __TEXT.__objc_methlist: 0x20c

   __TEXT.__swift5_fieldmd: 0x60
   __TEXT.__swift5_proto: 0x8
   __TEXT.__swift5_types: 0xc
-  __TEXT.__cstring: 0x16fe4
+  __TEXT.__cstring: 0x16f51
   __TEXT.__swift5_capture: 0x14
   __TEXT.__objc_methtype: 0xf
   __TEXT.__objc_classname: 0x212

   __TEXT.__dof_launchd: 0x81d
   __TEXT.__unwind_info: 0x1128
   __TEXT.__eh_frame: 0x210
-  __DATA_CONST.__const: 0x59e0
+  __DATA_CONST.__const: 0x59d8
   __DATA_CONST.__objc_classlist: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_superrefs: 0xb0

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
-  Functions: 1480
+  Functions: 1479
   Symbols:   658
-  CStrings:  2875
+  CStrings:  2871
 
CStrings:
+ "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Mon Aug 10 01:06:09 PDT 2026; root:libxpc_executables-3298.1.1~29/launchd/RELEASE_ARM64E"
+ "Darwin Bootstrapper Version 7.0.0: Mon Aug 10 01:06:09 PDT 2026; root:libxpc_executables-3298.1.1~29/launchd/RELEASE_ARM64E"
- "@(#)VERSION:Darwin Bootstrapper Version 7.0.0: Mon Aug  3 23:16:35 PDT 2026; root:libxpc_executables-3298.0.26.0.2~272/launchd/RELEASE_ARM64E"
- "Darwin Bootstrapper Version 7.0.0: Mon Aug  3 23:16:35 PDT 2026; root:libxpc_executables-3298.0.26.0.2~272/launchd/RELEASE_ARM64E"
- "Failed to resolve BundlePath: error=%s: %d, caller=%s"
- "_BundlePath"
- "bundle path = %s"
- "com.apple.private.xpc.launchd.allow-set-bundle-path"
```
