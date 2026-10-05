## Rapport

> `/System/Library/PrivateFrameworks/Rapport.framework/Versions/A/Rapport`

```diff

-751.200.41.0.0
-  __TEXT.__text: 0xe2270
-  __TEXT.__objc_methlist: 0xa130
-  __TEXT.__cstring: 0x1453c
-  __TEXT.__const: 0x41b8
+751.200.73.0.0
+  __TEXT.__text: 0xe25e4
+  __TEXT.__objc_methlist: 0xa148
+  __TEXT.__cstring: 0x145ec
+  __TEXT.__const: 0x41a8
   __TEXT.__gcc_except_tab: 0x14f0
-  __TEXT.__oslogstring: 0x26fd
+  __TEXT.__oslogstring: 0x26bd
   __TEXT.__swift5_typeref: 0xc4f
   __TEXT.__swift5_capture: 0x950
   __TEXT.__swift5_fieldmd: 0xb34

   __TEXT.__swift5_builtin: 0x50
   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x3c08
+  __TEXT.__unwind_info: 0x3c18
   __TEXT.__eh_frame: 0x960
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x170
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4580
+  __DATA_CONST.__objc_selrefs: 0x4590
   __DATA_CONST.__objc_protorefs: 0x100
   __DATA_CONST.__objc_superrefs: 0x1f8
   __DATA_CONST.__objc_arraydata: 0xb0
   __DATA_CONST.__got: 0x4e8
-  __AUTH_CONST.__const: 0x3f00
-  __AUTH_CONST.__cfstring: 0x6140
-  __AUTH_CONST.__objc_const: 0x115f0
-  __AUTH_CONST.__objc_intobj: 0x258
+  __AUTH_CONST.__const: 0x3f30
+  __AUTH_CONST.__cfstring: 0x5f20
+  __AUTH_CONST.__objc_const: 0x115f8
+  __AUTH_CONST.__objc_intobj: 0x270
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x78
-  __AUTH_CONST.__auth_got: 0xfc0
+  __AUTH_CONST.__auth_got: 0xfc8
   __AUTH.__objc_data: 0x50
   __DATA.__objc_ivar: 0x1114
   __DATA.__data: 0x738

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5868
-  Symbols:   8429
-  CStrings:  3047
+  Functions: 5871
+  Symbols:   8435
+  CStrings:  3039
 
Symbols:
+ -[RPClient endpointContextForService:trustCircles:parameters:completion:]
+ ___73-[RPClient endpointContextForService:trustCircles:parameters:completion:]_block_invoke
+ ___73-[RPClient endpointContextForService:trustCircles:parameters:completion:]_block_invoke_2
+ ___block_descriptor_72_e8_32s40s48s56bs_e5_v8?0l
+ _nw_parameters_copy_dictionary
+ _objc_msgSend$endpointContextForService:trustCircles:encodedParameters:completion:
CStrings:
+ "### Specifying the trust flags using RPOptionStatusFlags for registering message '%@' is required."
+ "-[RPClient endpointContextForService:trustCircles:parameters:completion:]"
+ "-[RPClient endpointContextForService:trustCircles:parameters:completion:]_block_invoke"
+ "Access permitted for %~@ for %@"
+ "Access revoked for %~@ for %@"
+ "Failed to encode parameters"
+ "Failed to encode parameters %@ for %@: %{error}"
+ "MusicHandoffScan"
+ "No change in devices: "
+ "No context provided"
+ "Requesting endpoint context for %@ with %@ and %#ll{flags}\n"
- "### Specifying the trust flags using RPOptionStatusFlags for registering message '%@' is required. Please file a radar in 'Rapport | All' to get more information."
- "FaceTimeAgent"
- "GeneralKnowledgeAgent"
- "HomeKitAgent"
- "HomepodSystemAgent"
- "IMSHPApp"
- "IMSTVApp"
- "MediaAgent"
- "No change in devices: %@"
- "PhotosAgent"
- "ScreenSaverAgent"
- "SearchAgent"
- "SystemAgent"
- "acousticcalibrationd"
- "idac-client"
- "idacd"
- "idactool"
- "imsutil"
- "sgsutil"
```
