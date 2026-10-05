## libsystem_eligibility.dylib

> `/usr/lib/system/libsystem_eligibility.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-446.40.35.0.1
-  __TEXT.__text: 0x4260
-  __TEXT.__const: 0x768
+446.40.44.0.0
+  __TEXT.__text: 0x42c8
+  __TEXT.__const: 0x760
   __TEXT.__cstring: 0x5815
   __TEXT.__oslogstring: 0x39b
-  __TEXT.__unwind_info: 0xf8
+  __TEXT.__unwind_info: 0x100
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0xee0
   __DATA_CONST.__got: 0x0

   - /usr/lib/system/libsystem_malloc.dylib
   - /usr/lib/system/libsystem_trace.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 34
-  Symbols:   86
+  Functions: 35
+  Symbols:   87
   CStrings:  551
 
Symbols:
+ _os_eligibility_bring_up_daemon_4_network_prompt
Functions:
+ _os_eligibility_bring_up_daemon_4_network_prompt
CStrings:
+ "CA-BC"
+ "CA-PE"
- "CA-NB"
- "CA-NS"
```
