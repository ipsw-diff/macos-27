## LoginUIKit

> `/System/Library/PrivateFrameworks/LoginUIKit.framework/Versions/A/LoginUIKit`

```diff

-415.2.3.0.0
-  __TEXT.__text: 0xaad4c
-  __TEXT.__objc_methlist: 0xb034
-  __TEXT.__const: 0x1360
-  __TEXT.__cstring: 0xa6b5
-  __TEXT.__gcc_except_tab: 0x11e8
+415.2.4.0.0
+  __TEXT.__text: 0xa9a88
+  __TEXT.__objc_methlist: 0xb08c
+  __TEXT.__const: 0x1344
+  __TEXT.__cstring: 0xa703
+  __TEXT.__gcc_except_tab: 0x11f4
   __TEXT.__dlopen_cstrs: 0x404
   __TEXT.__ustring: 0x3a
-  __TEXT.__oslogstring: 0x72c
-  __TEXT.__swift5_typeref: 0x524
-  __TEXT.__constg_swiftt: 0x480
+  __TEXT.__oslogstring: 0x701
+  __TEXT.__swift5_typeref: 0x51d
+  __TEXT.__constg_swiftt: 0x464
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_capture: 0x78c
-  __TEXT.__swift5_types: 0x3c
+  __TEXT.__swift5_types: 0x38
   __TEXT.__swift_as_entry: 0x50
   __TEXT.__swift_as_ret: 0x5c
   __TEXT.__swift_as_cont: 0x8c
-  __TEXT.__swift5_fieldmd: 0x16c
+  __TEXT.__swift5_fieldmd: 0x15c
   __TEXT.__swift5_reflstr: 0xfe
   __TEXT.__swift5_assocty: 0x48
   __TEXT.__swift5_proto: 0x3c
-  __TEXT.__unwind_info: 0x39a8
+  __TEXT.__unwind_info: 0x3978
   __TEXT.__eh_frame: 0xf10
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__const: 0x9a0
   __DATA_CONST.__objc_classlist: 0x5b8
   __DATA_CONST.__objc_catlist: 0x60
-  __DATA_CONST.__objc_protolist: 0xf0
+  __DATA_CONST.__objc_protolist: 0xf8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6298
+  __DATA_CONST.__objc_selrefs: 0x62b8
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x4e8
   __DATA_CONST.__objc_arraydata: 0x210
-  __DATA_CONST.__got: 0x11c0
-  __AUTH_CONST.__const: 0x35c8
-  __AUTH_CONST.__cfstring: 0x9120
-  __AUTH_CONST.__objc_const: 0x11248
+  __DATA_CONST.__got: 0x11b0
+  __AUTH_CONST.__const: 0x34f1
+  __AUTH_CONST.__cfstring: 0x91a0
+  __AUTH_CONST.__objc_const: 0x112c8
   __AUTH_CONST.__objc_intobj: 0x1c8
   __AUTH_CONST.__objc_arrayobj: 0x318
   __AUTH_CONST.__objc_doubleobj: 0x80
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x1190
+  __AUTH_CONST.__auth_got: 0x1138
   __AUTH.__objc_data: 0x35c0
   __AUTH.__data: 0x340
   __DATA.__objc_ivar: 0xb88
-  __DATA.__data: 0xf38
+  __DATA.__data: 0xf90
   __DATA.__bss: 0xe40
-  __DATA.__common: 0xd8
+  __DATA.__common: 0xc0
   __DATA_DIRTY.__objc_data: 0x4a8
   __DATA_DIRTY.__data: 0x58
   __DATA_DIRTY.__bss: 0x58

   - /System/Library/Frameworks/SecurityFoundation.framework/Versions/A/SecurityFoundation
   - /System/Library/Frameworks/SwiftUI.framework/Versions/A/SwiftUI
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
-  - /System/Library/PrivateFrameworks/CoreUtils.framework/Versions/A/CoreUtils
   - /System/Library/PrivateFrameworks/CoreWLANKit.framework/Versions/A/CoreWLANKit
   - /System/Library/PrivateFrameworks/DiskManagement.framework/Versions/A/DiskManagement
   - /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/Versions/A/IOMobileFramebuffer

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4814
-  Symbols:   9795
-  CStrings:  1441
+  Functions: 4797
+  Symbols:   9804
+  CStrings:  1442
 
Symbols:
+ -[LUIAuthenticationManager ahpManager:didEvictModule:]
+ -[LUIAuthenticationManager ahpManager:didLoseConnectionToModule:]
+ -[LUIAuthenticationManager providerForModule:]
+ -[LUIAuthenticationServiceProvider resetActivationState]
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_LAAHPManagerDelegate
+ __OBJC_$_PROTOCOL_METHOD_TYPES_LAAHPManagerDelegate
+ __OBJC_$_PROTOCOL_REFS_LAAHPManagerDelegate
+ __OBJC_CLASS_PROTOCOLS_$_LUIAuthenticationManager
+ __OBJC_LABEL_PROTOCOL_$_LAAHPManagerDelegate
+ __OBJC_PROTOCOL_$_LAAHPManagerDelegate
+ ___56-[LUIAuthenticationServiceProvider resetActivationState]_block_invoke
+ _objc_msgSend$providerForModule:
+ _objc_msgSend$resetActivationState
+ _objc_msgSend$setManagerDelegate:
- _IsAppleInternalBuild
- _MGCopyMultipleAnswers
- ___swift_memcpy0_1
- _objc_msgSend$valueForKey:
- _symbolic _____ 15WallpaperAccess9ModelInfoO
CStrings:
+ "AHP manager evicted module %@"
+ "AHP manager lost the connection to module %@"
+ "Module of service %@ is gone: dropping activation state for %@"
+ "No service provider for module: %@"
- "/System/Library/Desktop Pictures/Mac "
- "DeviceEnclosureColor"
- "Unknown enclosure color %ld"
```
