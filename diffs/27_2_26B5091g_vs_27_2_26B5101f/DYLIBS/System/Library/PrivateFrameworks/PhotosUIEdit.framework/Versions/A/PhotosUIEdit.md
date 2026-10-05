## PhotosUIEdit

> `/System/Library/PrivateFrameworks/PhotosUIEdit.framework/Versions/A/PhotosUIEdit`

```diff

-916.45.110.0.0
-  __TEXT.__text: 0xcce6c
-  __TEXT.__objc_methlist: 0x437c
-  __TEXT.__const: 0x6378
-  __TEXT.__swift5_typeref: 0x12714
+916.53.100.0.0
+  __TEXT.__text: 0xcd7c0
+  __TEXT.__objc_methlist: 0x43bc
+  __TEXT.__const: 0x6398
+  __TEXT.__swift5_typeref: 0x1271c
   __TEXT.__constg_swiftt: 0x2afc
   __TEXT.__swift5_reflstr: 0x250b
   __TEXT.__swift5_assocty: 0x588
   __TEXT.__swift5_fieldmd: 0x1e1c
   __TEXT.__swift5_builtin: 0x118
-  __TEXT.__swift5_proto: 0x1fc
+  __TEXT.__swift5_proto: 0x200
   __TEXT.__swift5_types: 0x198
-  __TEXT.__cstring: 0x5d32
+  __TEXT.__cstring: 0x5da7
   __TEXT.__swift5_capture: 0xd24
   __TEXT.__swift_as_entry: 0x6c
   __TEXT.__swift_as_ret: 0x90
   __TEXT.__swift_as_cont: 0x154
   __TEXT.__swift5_mpenum: 0x28
-  __TEXT.__oslogstring: 0x4233
+  __TEXT.__oslogstring: 0x428d
   __TEXT.__swift5_protos: 0x14
-  __TEXT.__gcc_except_tab: 0x674
-  __TEXT.__unwind_info: 0x4348
-  __TEXT.__eh_frame: 0x2694
+  __TEXT.__gcc_except_tab: 0x68c
+  __TEXT.__unwind_info: 0x4370
+  __TEXT.__eh_frame: 0x269c
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x58
   __DATA_CONST.__objc_protolist: 0x98
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x39f8
+  __DATA_CONST.__objc_selrefs: 0x3a28
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x188
   __DATA_CONST.__objc_arraydata: 0x70
-  __DATA_CONST.__got: 0x15d0
-  __AUTH_CONST.__const: 0x5c58
-  __AUTH_CONST.__cfstring: 0x3b00
-  __AUTH_CONST.__objc_const: 0x9fb0
+  __DATA_CONST.__got: 0x15d8
+  __AUTH_CONST.__const: 0x5c88
+  __AUTH_CONST.__cfstring: 0x3ba0
+  __AUTH_CONST.__objc_const: 0xa040
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__auth_got: 0x20d0
   __AUTH.__objc_data: 0x790
   __AUTH.__data: 0x988
-  __DATA.__objc_ivar: 0x4c8
-  __DATA.__data: 0x2560
-  __DATA.__bss: 0x3628
+  __DATA.__objc_ivar: 0x4d8
+  __DATA.__data: 0x2568
+  __DATA.__bss: 0x36a8
   __DATA.__common: 0x58
   __DATA_DIRTY.__objc_data: 0x2238
   __DATA_DIRTY.__data: 0x2cd8

   - /System/Library/PrivateFrameworks/PhotosEditing.framework/Versions/A/PhotosEditing
   - /System/Library/PrivateFrameworks/PhotosFormats.framework/Versions/A/PhotosFormats
   - /System/Library/PrivateFrameworks/PhotosGenerativeServices.framework/Versions/A/PhotosGenerativeServices
+  - /System/Library/PrivateFrameworks/PhotosRendering.framework/Versions/A/PhotosRendering
   - /System/Library/PrivateFrameworks/PhotosSpatialMediaCore.framework/Versions/A/PhotosSpatialMediaCore
   - /System/Library/PrivateFrameworks/PhotosSpatialMediaEditing.framework/Versions/A/PhotosSpatialMediaEditing
   - /System/Library/PrivateFrameworks/PhotosSwiftUICore.framework/Versions/A/PhotosSwiftUICore

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5965
-  Symbols:   6301
-  CStrings:  1089
+  Functions: 5976
+  Symbols:   6322
+  CStrings:  1096
 
Symbols:
+ +[PEAdjustmentPreset _sanitizedCompositionForCompositionController:autoType:]
+ +[PEEditAIToolCompletedEventBuilder sendEventForCleanupTool:requestDuration:result:guardrailReasons:generativeModel:interactionMode:userSelectedInteractionMode:modelResolution:]
+ +[PEEditAIToolCompletedEventBuilder sendEventForTool:requestDuration:result:guardrailReasons:sourceTab:interactionCount:generativeModel:interactionMode:userSelectedInteractionMode:modelResolution:]
+ -[PEAdjustmentPreset _deserializedComposition]
+ -[PEAdjustmentPreset _serializeComposition:autoType:includeSidecar:]
+ -[PEAdjustmentPreset _serializeDeferredComposition]
+ -[PEAdjustmentPreset initWithCompositionControllerDeferringSerialization:asset:]
+ -[PECleanupSegmentAnalyzer ciContext]
+ -[PECleanupSegmentAnalyzer setCiContext:]
+ GCC_except_table1011
+ GCC_except_table1021
+ GCC_except_table1025
+ GCC_except_table1027
+ GCC_except_table1040
+ GCC_except_table1052
+ GCC_except_table1167
+ GCC_except_table1280
+ GCC_except_table1281
+ GCC_except_table1282
+ GCC_except_table1320
+ GCC_except_table1333
+ GCC_except_table409
+ GCC_except_table437
+ GCC_except_table450
+ GCC_except_table474
+ GCC_except_table489
+ GCC_except_table754
+ GCC_except_table778
+ GCC_except_table936
+ GCC_except_table948
+ GCC_except_table959
+ OBJC_IVAR_$_PEAdjustmentPreset._deferredAutoType
+ OBJC_IVAR_$_PEAdjustmentPreset._deferredSerialization
+ OBJC_IVAR_$_PEAdjustmentPreset._deferredSourceAssetUUID
+ OBJC_IVAR_$_PECleanupSegmentAnalyzer._ciContext
+ _OUTLINED_FUNCTION_345
+ _OUTLINED_FUNCTION_346
+ ___80-[PEAdjustmentPreset initWithCompositionControllerDeferringSerialization:asset:]_block_invoke
+ ___block_descriptor_40_e8_32w_e5_v8?0l
+ _associated conformance 12PhotosUIEdit24CompositionMediaProvider33_6B0A8C9A6CD579A51EF3C64FC30C5F82LLC0A7Editing0aD9ProvidingAA11Observation10Observable
+ _kCIContextName
+ _objc_msgSend$_deserializedComposition
+ _objc_msgSend$_sanitizedCompositionForCompositionController:autoType:
+ _objc_msgSend$_serializeComposition:autoType:includeSidecar:
+ _objc_msgSend$_serializeDeferredComposition
+ _objc_msgSend$ciContext
+ _objc_msgSend$contextWithOptions:
+ _objc_msgSend$initWithBrushMask:mask:strokeScale:ciContext:
+ _objc_msgSend$sendEventForTool:requestDuration:result:guardrailReasons:sourceTab:interactionCount:generativeModel:interactionMode:userSelectedInteractionMode:modelResolution:
- +[PEEditAIToolCompletedEventBuilder sendEventForCleanupTool:requestDuration:result:guardrailReasons:generativeModel:interactionMode:userSelectedInteractionMode:]
- +[PEEditAIToolCompletedEventBuilder sendEventForTool:requestDuration:result:guardrailReasons:sourceTab:interactionCount:generativeModel:interactionMode:userSelectedInteractionMode:]
- -[PEAdjustmentPreset _serializeCompositionController:includeSidecar:]
- GCC_except_table1002
- GCC_except_table1009
- GCC_except_table1012
- GCC_except_table1016
- GCC_except_table1031
- GCC_except_table1043
- GCC_except_table1158
- GCC_except_table1273
- GCC_except_table1274
- GCC_except_table1275
- GCC_except_table1313
- GCC_except_table1326
- GCC_except_table430
- GCC_except_table443
- GCC_except_table467
- GCC_except_table482
- GCC_except_table745
- GCC_except_table769
- GCC_except_table927
- GCC_except_table939
- GCC_except_table950
- _objc_msgSend$_serializeCompositionController:includeSidecar:
- _objc_msgSend$context
- _objc_msgSend$initWithBrushMask:mask:strokeScale:
- _objc_msgSend$sendEventForTool:requestDuration:result:guardrailReasons:sourceTab:interactionCount:generativeModel:interactionMode:userSelectedInteractionMode:
CStrings:
+ "PEAdjustmentPreset failed to serialize deferred composition, keeping it in memory"
+ "PECleanupSegmentAnalyzer"
+ "PENoUpsellRateLimitErrorMessage"
+ "PESerializationUtility sidecar data could not be loaded: %{public}@"
+ "composition"
+ "isEditAIEligible"
+ "modelResolution"
+ "outAutoType"
- "PESerializationUtility sidecar data could not be loaded: %@"
```
