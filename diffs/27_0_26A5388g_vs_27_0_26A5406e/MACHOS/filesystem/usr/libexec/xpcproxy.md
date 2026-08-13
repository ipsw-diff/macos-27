## xpcproxy

> `/usr/libexec/xpcproxy`

### Sections with Same Size but Changed Content

- `__TEXT.__dof_launchd`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA.__os_assumes_log`

```diff

-3298.0.21.0.0
-  __TEXT.__text: 0xb038
-  __TEXT.__auth_stubs: 0xc60
-  __TEXT.__lazy_helpers: 0x1a4
-  __TEXT.__const: 0x1b0
+3298.0.26.0.2
+  __TEXT.__text: 0xb31c
+  __TEXT.__auth_stubs: 0xc80
+  __TEXT.__lazy_helpers: 0x24c
+  __TEXT.__const: 0x1c0
   __TEXT.__xpcproxy: 0x1
-  __TEXT.__oslogstring: 0x1a1b
-  __TEXT.__cstring: 0x1be9
+  __TEXT.__oslogstring: 0x1977
+  __TEXT.__cstring: 0x1c9b
   __TEXT.__dof_launchd: 0x2e5
-  __TEXT.__unwind_info: 0x188
+  __TEXT.__unwind_info: 0x190
   __DATA_CONST.__const: 0x260
-  __DATA_CONST.__auth_got: 0x630
+  __DATA_CONST.__auth_got: 0x640
   __DATA_CONST.__got: 0xa0
-  __DATA.__lazy_load_got: 0x28
+  __DATA.__lazy_load_got: 0x38
   __DATA.__os_assumes_log: 0x8
-  __DATA.__data: 0x28
+  __DATA.__data: 0x2c
   __DATA.__crash_info: 0x148
   __DATA.__bss: 0x490
   __DATA.__common: 0x1
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 101
-  Symbols:   225
-  CStrings:  332
+  Functions: 103
+  Symbols:   229
+  CStrings:  339
 
Symbols:
+ _asp_spawnattrs_init
+ _asp_spawnattrs_set_bundle_path
+ _fcntl
+ _posix_spawn_file_actions_adddup2
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.5ixXmV/Binaries/libxpc_executables/install/Symbols/xpcproxy"
+ "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Mon Aug  3 23:19:19 PDT 2026; root:libxpc_executables-3298.0.26.0.2~272/xpcproxy/RELEASE_ARM64E"
+ "ASP"
+ "Darwin Bootstrapper Trampoline Version 7.0.0: Mon Aug  3 23:19:19 PDT 2026; root:libxpc_executables-3298.0.26.0.2~272/xpcproxy/RELEASE_ARM64E"
+ "Unable to open stderr path (%s)"
+ "Unable to open stdin path (%s)"
+ "Unable to open stdout path (%s)"
+ "Unable to set system policy bundle path"
+ "Unable to unpack bundle path"
+ "assertion failure: \"posix_spawn_file_actions_adddup2(&ctx->filact, fd, 0)\" -> %llu"
+ "assertion failure: \"posix_spawn_file_actions_adddup2(&ctx->filact, fd, 1)\" -> %llu"
+ "assertion failure: \"posix_spawn_file_actions_adddup2(&ctx->filact, fd, 2)\" -> %llu"
+ "assertion failure: \"posix_spawnattr_setmacpolicyinfo_np(&ctx->psattr, \"ASP\", &ctx->asp_attrs, sizeof(ctx->asp_attrs))\" -> %llu"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.5v8qSb/Binaries/libxpc_executables/install/Symbols/xpcproxy"
- "@(#)VERSION:Darwin Bootstrapper Trampoline Version 7.0.0: Mon Jul 13 21:49:43 PDT 2026; root:libxpc_executables-3298.0.21~90/xpcproxy/RELEASE_ARM64E"
- "Darwin Bootstrapper Trampoline Version 7.0.0: Mon Jul 13 21:49:43 PDT 2026; root:libxpc_executables-3298.0.21~90/xpcproxy/RELEASE_ARM64E"
- "assertion failure: \"posix_spawn_file_actions_addopen(&ctx->filact, 0, stdin_path, 0x00000200|0x0000|0x00020000, (0000400|0000200|0000040|0000020|0000004|0000002))\" -> %llu"
- "assertion failure: \"posix_spawn_file_actions_addopen(&ctx->filact, 1, stdout_path, 0x00000200|0x0002|0x00000008|0x00020000, (0000400|0000200|0000040|0000020|0000004|0000002))\" -> %llu"
- "assertion failure: \"posix_spawn_file_actions_addopen(&ctx->filact, 2, stderr_path, 0x00000200|0x0002|0x00000008|0x00020000, (0000400|0000200|0000040|0000020|0000004|0000002))\" -> %llu"
```
