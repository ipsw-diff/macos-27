## parsecd

> `/System/Library/PrivateFrameworks/CoreParsec.framework/parsecd`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`

```diff

-3600.56.26.0.0
-  __TEXT.__text: 0x174f24
+3600.56.26.14.1
+  __TEXT.__text: 0x173c00
   __TEXT.__auth_stubs: 0x4d50
-  __TEXT.__objc_stubs: 0x4000
-  __TEXT.__objc_methlist: 0x1274
-  __TEXT.__const: 0xed40
-  __TEXT.__cstring: 0x6984
-  __TEXT.__objc_classname: 0x1487
-  __TEXT.__objc_methname: 0x67d5
+  __TEXT.__objc_stubs: 0x3fa0
+  __TEXT.__objc_methlist: 0x122c
+  __TEXT.__const: 0xece0
+  __TEXT.__cstring: 0x6964
+  __TEXT.__objc_classname: 0x13a7
+  __TEXT.__objc_methname: 0x6715
   __TEXT.__objc_methtype: 0x1bc3
   __TEXT.__gcc_except_tab: 0xf4
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__constg_swiftt: 0x598c
-  __TEXT.__swift5_typeref: 0x4e74
-  __TEXT.__swift5_reflstr: 0x5523
-  __TEXT.__swift5_fieldmd: 0x50fc
+  __TEXT.__constg_swiftt: 0x58c8
+  __TEXT.__swift5_typeref: 0x4e02
+  __TEXT.__swift5_reflstr: 0x54b3
+  __TEXT.__swift5_fieldmd: 0x506c
   __TEXT.__swift5_builtin: 0x35c
   __TEXT.__swift5_assocty: 0x650
   __TEXT.__swift5_capture: 0x380c
-  __TEXT.__oslogstring: 0x60f6
+  __TEXT.__oslogstring: 0x5fc6
   __TEXT.__swift5_proto: 0x8d4
-  __TEXT.__swift5_types: 0x48c
+  __TEXT.__swift5_types: 0x480
   __TEXT.__swift_as_entry: 0x94
   __TEXT.__swift_as_cont: 0xd0
   __TEXT.__swift5_protos: 0x12c
   __TEXT.__swift_as_ret: 0x78
   __TEXT.__swift5_mpenum: 0x6c
-  __TEXT.__unwind_info: 0x50d8
+  __TEXT.__unwind_info: 0x50a0
   __TEXT.__eh_frame: 0x71b8
   __DATA_CONST.__const: 0xfff0
   __DATA_CONST.__cfstring: 0x8a0
-  __DATA_CONST.__objc_classlist: 0x2f0
+  __DATA_CONST.__objc_classlist: 0x2d8
   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x1e8
   __DATA_CONST.__objc_imageinfo: 0x8

   __DATA_CONST.__objc_superrefs: 0x8
   __DATA_CONST.__auth_got: 0x26b8
   __DATA_CONST.__got: 0x13c0
-  __DATA_CONST.__auth_ptr: 0x1e98
-  __DATA.__objc_const: 0x78c8
-  __DATA.__objc_selrefs: 0x1618
+  __DATA_CONST.__auth_ptr: 0x1e88
+  __DATA.__objc_const: 0x7628
+  __DATA.__objc_selrefs: 0x1600
   __DATA.__objc_ivar: 0x8
-  __DATA.__objc_data: 0x1570
-  __DATA.__data: 0x9c20
+  __DATA.__objc_data: 0x14a8
+  __DATA.__data: 0x9a70
   __DATA.__bss: 0xd780
   __DATA.__common: 0x5c0
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 8924
+  Functions: 8900
   Symbols:   2266
-  CStrings:  2581
+  CStrings:  2565
 
CStrings:
- "Caller location authorization changed: %{bool,public}d (status: %{public}d, accuracy: %{public}ld)"
- "Caller location authorized: %{bool,public}d for %{public}s"
- "Caller location request failed: %@"
- "Caller location updated: (%{public}f, %{public}f) accuracy: %{public}fm"
- "_TtC7parsecd21CallerLocationMonitor"
- "_TtCC7parsecd21CallerLocationMonitorP33_623A24F31DADE66D4B56BCDC3BA1128F5State"
- "_TtCC7parsecd21CallerLocationMonitorP33_623A24F31DADE66D4B56BCDC3BA1128F8Delegate"
- "accuracyAuthorization"
- "authHandler"
- "authorizationStatus"
- "authorized"
- "initWithEffectiveBundleIdentifier:delegate:onQueue:"
- "locationHandler"
- "manager"
- "parsecd.Delegate"
- "safariCallerLocationMonitor"
```
