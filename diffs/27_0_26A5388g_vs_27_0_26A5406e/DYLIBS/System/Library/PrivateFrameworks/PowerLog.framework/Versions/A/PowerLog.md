## PowerLog

> `/System/Library/PrivateFrameworks/PowerLog.framework/Versions/A/PowerLog`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_doubleobj`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH.__objc_data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-3486.0.81.501.3
-  __TEXT.__text: 0x1c76c
+3486.1.2.0.0
+  __TEXT.__text: 0x1c770
   __TEXT.__objc_methlist: 0x12dc
-  __TEXT.__const: 0x1e0
+  __TEXT.__const: 0x1d8
   __TEXT.__gcc_except_tab: 0x694
-  __TEXT.__cstring: 0x20bc
-  __TEXT.__oslogstring: 0x3885
+  __TEXT.__cstring: 0x20f4
+  __TEXT.__oslogstring: 0x38a2
   __TEXT.__unwind_info: 0x720
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x178
   __DATA_CONST.__got: 0x188
   __AUTH_CONST.__const: 0x8d0
-  __AUTH_CONST.__cfstring: 0x25a0
+  __AUTH_CONST.__cfstring: 0x25c0
   __AUTH_CONST.__objc_const: 0x2000
   __AUTH_CONST.__objc_intobj: 0x3d8
   __AUTH_CONST.__objc_arrayobj: 0x120

   - /usr/lib/libsqlite3.dylib
   Functions: 796
   Symbols:   1522
-  CStrings:  638
+  CStrings:  639
 
Functions:
~ sub_19ca5e948 -> sub_197f63948 : 72 -> 76
~ _batteryUIIsEligibleForOptimizeBatteryPrompt : 448 -> 424
~ _PLBatteryUsageUIStringForResponseType : 548 -> 572
CStrings:
+ "OptimizeBatteryPromptEligibility"
+ "is Eligible for Optimize Battery Prompt: %d"
+ "optimizeBatteryPromptEligibility"
- "drainRate"
- "drainRate: %lf"
```
