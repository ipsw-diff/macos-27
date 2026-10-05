## libspindump.dylib

> `/usr/lib/libspindump.dylib`

```diff

-453.0.0.0.0
-  __TEXT.__text: 0x4500
+453.1.0.0.0
+  __TEXT.__text: 0x461c
   __TEXT.__const: 0xc0
-  __TEXT.__cstring: 0x500
-  __TEXT.__oslogstring: 0xd72
+  __TEXT.__cstring: 0x54a
+  __TEXT.__oslogstring: 0xe16
   __TEXT.__unwind_info: 0x1c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH_CONST.__cfstring: 0x40
   __AUTH_CONST.__auth_got: 0x210
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x38
+  __DATA.__bss: 0x48
   __DATA_DIRTY.__bss: 0x328
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 99
-  Symbols:   213
-  CStrings:  124
+  Symbols:   215
+  CStrings:  126
 
Symbols:
+ _gActionCountSinceLastSignpost
+ _gHIDEventCountSinceLastSignpost
Functions:
~ _SPCheckHIDResponseTime2 : 3808 -> 4092
CStrings:
+ "%{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu hidEventCountSinceLastSignpost=%{public,name=hidEventCountSinceLastSignpost}llu userActionCountSinceLastSignpost=%{public,name=userActionCountSinceLastSignpost}llu"
+ "hid_event_count_since_last_signpost"
+ "user_action_count_since_last_signpost"
- "%{public, signpost.description:begin_time}llu %{public, signpost.description:end_time}llu"
```
