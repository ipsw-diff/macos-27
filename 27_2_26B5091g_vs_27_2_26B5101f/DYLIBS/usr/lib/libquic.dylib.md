## libquic.dylib

> `/usr/lib/libquic.dylib`

```diff

-6681.40.82.0.0
-  __TEXT.__text: 0xcfa90
+6681.40.95.0.6
+  __TEXT.__text: 0xd0174
   __TEXT.__objc_methlist: 0x244
   __TEXT.__const: 0x3a5
-  __TEXT.__cstring: 0x88b5
-  __TEXT.__oslogstring: 0x1260d
-  __TEXT.__unwind_info: 0x12d8
+  __TEXT.__cstring: 0x8907
+  __TEXT.__oslogstring: 0x12684
+  __TEXT.__unwind_info: 0x12e0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __AUTH_CONST.__const: 0x1870
   __AUTH_CONST.__cfstring: 0x1320
   __AUTH_CONST.__objc_const: 0xf8
-  __AUTH_CONST.__auth_got: 0xd40
+  __AUTH_CONST.__auth_got: 0xd48
   __AUTH.__objc_data: 0x28
   __AUTH.__data: 0x118
   __DATA.__objc_ivar: 0xc

   - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1169
-  Symbols:   1718
-  CStrings:  2618
+  Functions: 1172
+  Symbols:   1722
+  CStrings:  2623
 
Symbols:
+ _nw_quic_connection_get_path_recovery_timeout
+ _quic_migration_pulse_applies
+ _quic_migration_pulse_fire_now
+ _quic_migration_pulse_stop
CStrings:
+ "%{public}s %{public}s [%{public}s-%{public}s] arming pulse timer (%llu ms)"
+ "%{public}s %{public}s [%{public}s-%{public}s] cancelling pulse timer"
+ "%{public}s %{public}s [%{public}s-%{public}s] nothing left to try, reporting failure now rather than waiting"
+ "%{public}s not arming pulse timer on companion path; expecting connectivity to resume"
+ "quic_migration_pulse_applies"
+ "quic_migration_pulse_start"
+ "quic_migration_pulse_stop"
- "%{public}s %{public}s [%{public}s-%{public}s] cancelling pulse timer; current path is still usable"
- "%{public}s %{public}s [%{public}s-%{public}s] not arming pulse timer on companion path; expecting connectivity to resume"
```
