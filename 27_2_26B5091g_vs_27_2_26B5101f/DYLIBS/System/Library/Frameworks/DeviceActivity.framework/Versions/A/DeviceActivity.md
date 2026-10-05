## DeviceActivity

> `/System/Library/Frameworks/DeviceActivity.framework/Versions/A/DeviceActivity`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-407.1.4.0.0
-  __TEXT.__text: 0x91bdc
+407.1.5.0.0
+  __TEXT.__text: 0x91688
   __TEXT.__objc_methlist: 0x490
   __TEXT.__const: 0x3a58
   __TEXT.__constg_swiftt: 0xd80

   __TEXT.__swift5_capture: 0x5f0
   __TEXT.__oslogstring: 0x14fb
   __TEXT.__swift_as_ret: 0x38
-  __TEXT.__unwind_info: 0x2170
-  __TEXT.__eh_frame: 0x2b98
+  __TEXT.__unwind_info: 0x2180
+  __TEXT.__eh_frame: 0x2bc8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __AUTH_CONST.__const: 0x31c8
   __AUTH_CONST.__cfstring: 0x40
   __AUTH_CONST.__objc_const: 0xbd8
-  __AUTH_CONST.__auth_got: 0xbb8
+  __AUTH_CONST.__auth_got: 0xbc0
   __AUTH.__objc_data: 0x120
   __AUTH.__data: 0x600
   __DATA.__data: 0x8c0

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2462
+  Functions: 2464
   Symbols:   940
   CStrings:  183
 
CStrings:
+ "Refreshing all activity due to queryStart (%{public}s) being after now (%{public}s)"
- "Skipping refresh because query start: %{public}s, is out of bounds: %{public}s - %{public}s"
```
