## MediaConversionService

> `/System/Library/PrivateFrameworks/MediaConversionService.framework/Versions/A/MediaConversionService`

```diff

-916.45.110.0.0
-  __TEXT.__text: 0x203d0
-  __TEXT.__objc_methlist: 0x1ff4
+916.53.100.0.0
+  __TEXT.__text: 0x209a4
+  __TEXT.__objc_methlist: 0x2004
   __TEXT.__const: 0xc8
   __TEXT.__gcc_except_tab: 0x57c
-  __TEXT.__cstring: 0x5aa5
-  __TEXT.__oslogstring: 0x28e7
-  __TEXT.__unwind_info: 0x998
+  __TEXT.__cstring: 0x5bfe
+  __TEXT.__oslogstring: 0x2940
+  __TEXT.__unwind_info: 0x9b8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x668
+  __DATA_CONST.__const: 0x690
   __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x16e8
+  __DATA_CONST.__objc_selrefs: 0x16f0
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x60
-  __DATA_CONST.__objc_arraydata: 0x5a8
+  __DATA_CONST.__objc_arraydata: 0x5b8
   __DATA_CONST.__got: 0x3c8
   __AUTH_CONST.__const: 0x920
-  __AUTH_CONST.__cfstring: 0x34c0
+  __AUTH_CONST.__cfstring: 0x3560
   __AUTH_CONST.__objc_const: 0x30d8
-  __AUTH_CONST.__objc_intobj: 0x198
-  __AUTH_CONST.__objc_arrayobj: 0xc0
+  __AUTH_CONST.__objc_intobj: 0x1c8
+  __AUTH_CONST.__objc_arrayobj: 0xf0
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_dictobj: 0x50
   __AUTH_CONST.__auth_got: 0x0

   - /System/Library/PrivateFrameworks/PhotosFormats.framework/Versions/A/PhotosFormats
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 765
-  Symbols:   2143
-  CStrings:  627
+  Functions: 769
+  Symbols:   2151
+  CStrings:  633
 
Symbols:
+ -[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]
+ -[PHMediaFormatConversionRequest _provenanceRenderOutputType]
+ -[PHMediaFormatConversionRequest provenanceRenderSourceURL]
+ -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withUnprocessedSourceRenderURL:processedOriginalDestinationURL:sidecarURL:]
+ GCC_except_table112
+ GCC_except_table118
+ GCC_except_table161
+ GCC_except_table178
+ GCC_except_table182
+ GCC_except_table189
+ GCC_except_table199
+ GCC_except_table207
+ GCC_except_table471
+ GCC_except_table473
+ GCC_except_table588
+ GCC_except_table598
+ GCC_except_table634
+ GCC_except_table722
+ GCC_except_table724
+ GCC_except_table727
+ GCC_except_table729
+ GCC_except_table742
+ OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceRenderSourceURL
+ _PAMediaConversionErrorIsProvenanceProcessingError
+ _PAMediaConversionIsProvenanceClientUpgradeRequiredError
+ _PAMediaConversionServiceProvenanceRetryableKey
+ _PAProvenanceCloudAppErrorIsTransient
+ _PFErrorOrUnderlyingErrorMatchesCodesByDomain
+ ___157-[PHMediaFormatConversionImplementation_MediaConversionService _submitProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]_block_invoke
+ _objc_msgSend$_provenanceRenderOutputType
+ _objc_msgSend$_submitProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:
+ _objc_msgSend$outputFileType
+ _objc_msgSend$provenanceRenderSourceURL
+ _objc_msgSend$setProvenanceMetadataBehavior:withUnprocessedSourceRenderURL:processedOriginalDestinationURL:sidecarURL:
- -[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]
- -[PHMediaFormatConversionRequest provenanceAdjustedRenderSourceURL]
- -[PHMediaFormatConversionRequest setProvenanceMetadataBehavior:withUnprocessedSourceAdjustedRenderURL:processedOriginalDestinationURL:sidecarURL:]
- GCC_except_table109
- GCC_except_table115
- GCC_except_table158
- GCC_except_table175
- GCC_except_table179
- GCC_except_table183
- GCC_except_table196
- GCC_except_table204
- GCC_except_table451
- GCC_except_table453
- GCC_except_table584
- GCC_except_table594
- GCC_except_table626
- GCC_except_table718
- GCC_except_table720
- GCC_except_table723
- GCC_except_table725
- GCC_except_table738
- OBJC_IVAR_$_PHMediaFormatConversionRequest._provenanceAdjustedRenderSourceURL
- ___165-[PHMediaFormatConversionImplementation_MediaConversionService _submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:]_block_invoke
- _objc_msgSend$_submitAdjustedProvenanceProcessingRequest:destination:sourceURLCollection:options:completionHandler:
- _objc_msgSend$provenanceAdjustedRenderSourceURL
- _objc_msgSend$setProvenanceMetadataBehavior:withUnprocessedSourceAdjustedRenderURL:processedOriginalDestinationURL:sidecarURL:
CStrings:
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppCaptureUnsupported"
+ "PAMediaConversionServiceErrorCodeProvenanceCloudAppClientVersionUnsupported"
+ "PAMediaConversionServiceErrorCodeProvenanceDestinationFormatUnsupported"
+ "PAMediaConversionServiceErrorCodeProvenanceRevocationCheckClientUpgradeRequired"
+ "PAMediaConversionServiceProvenanceRetryableKey"
+ "Render path extension (%@) is not a known UTType. Falling back to the conversion source's format."
+ "Requesting single-pass Provenance processing with render. Source: %@, destination: %@."
- "Requesting single-pass Provenance processing with adjusted render. Source: %@, destination: %@."
```
