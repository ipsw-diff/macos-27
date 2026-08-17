## pccvre

> `/System/Library/SecurityResearch/usr/bin/pccvre`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_proto`
- `__TEXT.__swift5_types`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__TEXT.__swift5_capture`
- `__TEXT.__swift5_entry`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-274.0.8.0.0
-  __TEXT.__text: 0x1a7a40
-  __TEXT.__auth_stubs: 0x3520
+274.1.3.0.0
+  __TEXT.__text: 0x1a84a8
+  __TEXT.__auth_stubs: 0x3530
   __TEXT.__objc_stubs: 0xa40
   __TEXT.__objc_methlist: 0x184
   __TEXT.__const: 0x15c68

   __TEXT.__swift5_mpenum: 0xd0
   __TEXT.__swift5_reflstr: 0x32dd
   __TEXT.__swift5_fieldmd: 0x54c0
-  __TEXT.__cstring: 0xa2a6
+  __TEXT.__cstring: 0xa3c6
   __TEXT.__swift5_assocty: 0x5c8
   __TEXT.__swift5_proto: 0x1278
   __TEXT.__swift5_types: 0x5a8
   __TEXT.__objc_classname: 0x691
   __TEXT.__objc_methname: 0xd47
   __TEXT.__swift5_protos: 0x2c
-  __TEXT.__oslogstring: 0x2137
+  __TEXT.__oslogstring: 0x2187
   __TEXT.__swift_as_entry: 0x21c
   __TEXT.__swift_as_ret: 0x248
   __TEXT.__swift_as_cont: 0x4a0
   __TEXT.__objc_methtype: 0x2c4
   __TEXT.__swift5_capture: 0x300
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__unwind_info: 0x5980
-  __TEXT.__eh_frame: 0xc604
+  __TEXT.__unwind_info: 0x5990
+  __TEXT.__eh_frame: 0xc644
   __DATA_CONST.__const: 0x9050
   __DATA_CONST.__cfstring: 0x34c0
   __DATA_CONST.__objc_classlist: 0xd8
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x28
-  __DATA_CONST.__auth_got: 0x1a98
+  __DATA_CONST.__auth_got: 0x1aa0
   __DATA_CONST.__got: 0x9a8
   __DATA_CONST.__auth_ptr: 0xe10
   __DATA.__objc_const: 0x1628

   - /usr/lib/swift/libswift_DarwinFoundation3.dylib
   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 6741
-  Symbols:   1408
-  CStrings:  1578
+  Functions: 6743
+  Symbols:   1409
+  CStrings:  1582
 
Symbols:
+ _$s10Foundation3URLV4hostSSSgvg
+ _$sSo12NSURLSessionC10FoundationE8download3for8delegateAC3URLV_So13NSURLResponseCtAC10URLRequestV_So0A12TaskDelegate_pSgtYaKF
+ _$sSo12NSURLSessionC10FoundationE8download3for8delegateAC3URLV_So13NSURLResponseCtAC10URLRequestV_So0A12TaskDelegate_pSgtYaKFTu
- _$sSo12NSURLSessionC10FoundationE8download4from8delegateAC3URLV_So13NSURLResponseCtAH_So0A12TaskDelegate_pSgtYaKF
- _$sSo12NSURLSessionC10FoundationE8download4from8delegateAC3URLV_So13NSURLResponseCtAH_So0A12TaskDelegate_pSgtYaKFTu
CStrings:
+ " for an availability check; set a token to authenticate: export CLOUDSDK_AUTH_ACCESS_TOKEN=$(gcloud auth print-access-token)\n"
+ ". Provide a valid access token by running: export CLOUDSDK_AUTH_ACCESS_TOKEN=$(gcloud auth print-access-token)"
+ "CLOUDSDK_AUTH_ACCESS_TOKEN"
+ "Note: Google Cloud Storage returned "
+ "e970bf252f65b7afc2163bc38fa742c92e443bfb47bc19fae694eb1c09535eae"
+ "no CLOUDSDK_AUTH_ACCESS_TOKEN set; requesting %{public}s unauthenticated"
- "asset doesn't contain digest"
- "dd1b2a89cf5b230a02dc7534a457454495d562183203ddc0742274e5a1a2fbd3"
```
