## accessoryaccessd

> `/System/Library/Frameworks/AccessoryAccess.framework/Versions/Current/Resources/accessoryaccessd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_selrefs`

```diff

-308.1.5.0.0
-  __TEXT.__text: 0x391bc
+308.1.7.0.0
+  __TEXT.__text: 0x393f0
   __TEXT.__auth_stubs: 0xdf0
   __TEXT.__objc_stubs: 0x2a0
   __TEXT.__const: 0x4158
-  __TEXT.__gcc_except_tab: 0x4438
+  __TEXT.__gcc_except_tab: 0x4458
   __TEXT.__cstring: 0xf3d
-  __TEXT.__oslogstring: 0xa8b
+  __TEXT.__oslogstring: 0xb4b
   __TEXT.__objc_methname: 0x1ae
-  __TEXT.__unwind_info: 0x1598
+  __TEXT.__unwind_info: 0x15a0
   __DATA_CONST.__const: 0x1030
   __DATA_CONST.__cfstring: 0x120
   __DATA_CONST.__objc_imageinfo: 0x8

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 651
+  Functions: 652
   Symbols:   301
-  CStrings:  208
+  CStrings:  210
 
CStrings:
+ "Client (pid: %{private, mask.hash}d, session: %{private, mask.hash}d) is not on console (session: %{private, mask.hash}d)"
+ "Could not get responsible audit token for pid %{private, mask.hash}d."
```
