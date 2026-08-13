## CallKit

> `/System/Library/Frameworks/CallKit.framework/Versions/A/CallKit`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
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
- `__AUTH.__objc_data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-1397.100.1.0.0
-  __TEXT.__text: 0x6bbe4
-  __TEXT.__objc_methlist: 0x9154
+1403.100.1.0.0
+  __TEXT.__text: 0x6bdf4
+  __TEXT.__objc_methlist: 0x917c
   __TEXT.__const: 0x130
-  __TEXT.__cstring: 0x62cc
-  __TEXT.__oslogstring: 0x3955
+  __TEXT.__cstring: 0x62ed
+  __TEXT.__oslogstring: 0x39c9
   __TEXT.__gcc_except_tab: 0x690
-  __TEXT.__unwind_info: 0x1ce0
+  __TEXT.__unwind_info: 0x1cf8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__got: 0x4b8
   __AUTH_CONST.__const: 0x1200
-  __AUTH_CONST.__cfstring: 0x41c0
+  __AUTH_CONST.__cfstring: 0x41e0
   __AUTH_CONST.__objc_const: 0xee88
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_arrayobj: 0x48

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 3234
-  Symbols:   6847
-  CStrings:  980
+  Functions: 3238
+  Symbols:   6851
+  CStrings:  982
 
Symbols:
+ -[CXProvider _registerCurrentConfigurationIfAudioSessionIDStaleOnQueue]
+ -[CXProvider _registerCurrentConfigurationOnQueue]
+ -[CXProvider currentOpaqueAudioSessionID]
+ ___28-[CXProvider performAction:]_block_invoke
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.qWmnZ8/Sources/CallKit/CallKit/CXCallDirectoryLabeledPhoneNumberEntryData.m"
+ "Cached audioSessionID %u no longer matches current opaqueSessionID %u; re-registering configuration for CXProvider."
+ "com.apple.application-identifier"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.vtQtZb/Sources/CallKit/CallKit/CXCallDirectoryLabeledPhoneNumberEntryData.m"
```
