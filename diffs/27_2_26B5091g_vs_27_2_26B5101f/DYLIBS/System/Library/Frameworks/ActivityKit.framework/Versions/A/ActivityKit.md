## ActivityKit

> `/System/Library/Frameworks/ActivityKit.framework/Versions/A/ActivityKit`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-313.2.4.0.0
-  __TEXT.__text: 0xbd2a8
-  __TEXT.__objc_methlist: 0xf2c
-  __TEXT.__const: 0xef9a
+313.2.7.0.0
+  __TEXT.__text: 0xbe87c
+  __TEXT.__objc_methlist: 0xf4c
+  __TEXT.__const: 0xefaa
   __TEXT.__cstring: 0x1e61
   __TEXT.__gcc_except_tab: 0x18
-  __TEXT.__swift5_typeref: 0x3e0e
-  __TEXT.__swift5_fieldmd: 0x3058
-  __TEXT.__constg_swiftt: 0x3878
+  __TEXT.__swift5_typeref: 0x3e18
+  __TEXT.__swift5_fieldmd: 0x3064
+  __TEXT.__constg_swiftt: 0x3890
   __TEXT.__swift5_builtin: 0xdc
-  __TEXT.__swift5_reflstr: 0x2413
+  __TEXT.__swift5_reflstr: 0x2433
   __TEXT.__swift5_protos: 0x28
   __TEXT.__swift5_types: 0x3fc
   __TEXT.__swift5_assocty: 0x730
   __TEXT.__swift5_proto: 0xd74
-  __TEXT.__oslogstring: 0x1d3f
-  __TEXT.__swift5_capture: 0x9f0
+  __TEXT.__oslogstring: 0x1d5f
+  __TEXT.__swift5_capture: 0xa10
   __TEXT.__swift_as_entry: 0x98
   __TEXT.__swift_as_ret: 0x94
   __TEXT.__swift_as_cont: 0x68
   __TEXT.__swift5_mpenum: 0x38
-  __TEXT.__unwind_info: 0x4470
-  __TEXT.__eh_frame: 0x4608
+  __TEXT.__unwind_info: 0x44a0
+  __TEXT.__eh_frame: 0x4648
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x158
   __DATA_CONST.__objc_protolist: 0x1c8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x698
+  __DATA_CONST.__objc_selrefs: 0x6b8
   __DATA_CONST.__objc_protorefs: 0xe0
   __DATA_CONST.__objc_superrefs: 0x50
   __DATA_CONST.__got: 0x480
-  __AUTH_CONST.__const: 0x8b60
+  __AUTH_CONST.__const: 0x8bb0
   __AUTH_CONST.__cfstring: 0xe0
-  __AUTH_CONST.__objc_const: 0x5600
-  __AUTH_CONST.__auth_got: 0xc58
+  __AUTH_CONST.__objc_const: 0x5660
+  __AUTH_CONST.__auth_got: 0xc70
   __AUTH.__objc_data: 0xc10
   __AUTH.__data: 0x720
-  __DATA.__objc_ivar: 0xa0
-  __DATA.__data: 0x2e18
+  __DATA.__objc_ivar: 0xa4
+  __DATA.__data: 0x2e38
   __DATA.__bss: 0x12130
   __DATA.__common: 0x18
-  __DATA_DIRTY.__objc_data: 0xe38
-  __DATA_DIRTY.__data: 0x3060
+  __DATA_DIRTY.__objc_data: 0xe58
+  __DATA_DIRTY.__data: 0x3070
   __DATA_DIRTY.__bss: 0x8980
   __DATA_DIRTY.__common: 0x28
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5191
-  Symbols:   2222
-  CStrings:  358
+  Functions: 5206
+  Symbols:   2228
+  CStrings:  359
 
Symbols:
+ -[ACActivityDescriptor initWithIdentifier:sceneTargets:alertSceneTargets:presentationOptions:isEphemeral:isMomentary:isImportant:createdDate:descriptorData:contentTypesByDestination:alertContentTypesByDestination:remoteDeviceIdentifier:localizedAppName:localizedActivityName:protectionClass:]
+ -[ACActivityDescriptor localizedActivityName]
+ -[ACActivityDescriptor localizedName]
+ -[ACActivityDescriptor setLocalizedActivityName:]
+ OBJC_IVAR_$_ACActivityDescriptor._localizedActivityName
+ _objc_msgSend$initWithIdentifier:sceneTargets:alertSceneTargets:presentationOptions:isEphemeral:isMomentary:isImportant:createdDate:descriptorData:contentTypesByDestination:alertContentTypesByDestination:remoteDeviceIdentifier:localizedAppName:localizedActivityName:protectionClass:
+ _objc_msgSend$invalidate
+ _objc_msgSend$localizedActivityName
+ _symbolic _____ySOG 8Dispatch0A11SpecificKeyC
- -[ACActivityDescriptor initWithIdentifier:sceneTargets:alertSceneTargets:presentationOptions:isEphemeral:isMomentary:isImportant:createdDate:descriptorData:contentTypesByDestination:alertContentTypesByDestination:remoteDeviceIdentifier:localizedAppName:protectionClass:]
- _objc_msgSend$initWithIdentifier:sceneTargets:alertSceneTargets:presentationOptions:isEphemeral:isMomentary:isImportant:createdDate:descriptorData:contentTypesByDestination:alertContentTypesByDestination:remoteDeviceIdentifier:localizedAppName:protectionClass:
- _objc_msgSend$localizedAppName
CStrings:
+ "AlertClient invalidated"
```
