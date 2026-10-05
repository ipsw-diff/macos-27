## MediaAnalysisServices

> `/System/Library/PrivateFrameworks/MediaAnalysisServices.framework/Versions/A/MediaAnalysisServices`

```diff

-460.8.2.0.0
-  __TEXT.__text: 0x406e0
-  __TEXT.__objc_methlist: 0x4fc4
+460.12.1.0.0
+  __TEXT.__text: 0x40b38
+  __TEXT.__objc_methlist: 0x4fd4
   __TEXT.__const: 0x108
-  __TEXT.__cstring: 0x3e38
-  __TEXT.__gcc_except_tab: 0x44d8
+  __TEXT.__cstring: 0x3e60
+  __TEXT.__gcc_except_tab: 0x456c
   __TEXT.__oslogstring: 0x2326
   __TEXT.__dlopen_cstrs: 0x417
-  __TEXT.__unwind_info: 0x2120
+  __TEXT.__unwind_info: 0x2130
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0x430
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1990
+  __DATA_CONST.__objc_selrefs: 0x19b0
   __DATA_CONST.__objc_protorefs: 0x40
   __DATA_CONST.__objc_superrefs: 0x3f0
-  __DATA_CONST.__got: 0x518
+  __DATA_CONST.__got: 0x520
   __AUTH_CONST.__const: 0xc68
-  __AUTH_CONST.__cfstring: 0x4de0
+  __AUTH_CONST.__cfstring: 0x4e00
   __AUTH_CONST.__objc_const: 0xa2e8
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__auth_got: 0x0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1771
-  Symbols:   3904
-  CStrings:  877
+  Functions: 1772
+  Symbols:   3909
+  CStrings:  878
 
Symbols:
+ -[MADService fileTypeForURL:]
+ GCC_except_table100
+ GCC_except_table110
+ GCC_except_table131
+ GCC_except_table133
+ GCC_except_table142
+ GCC_except_table148
+ GCC_except_table156
+ GCC_except_table159
+ GCC_except_table171
+ GCC_except_table174
+ GCC_except_table177
+ GCC_except_table179
+ GCC_except_table181
+ GCC_except_table183
+ GCC_except_table185
+ GCC_except_table188
+ GCC_except_table195
+ GCC_except_table206
+ GCC_except_table211
+ GCC_except_table214
+ GCC_except_table88
+ _OBJC_CLASS_$_NSFileHandle
+ _objc_msgSend$fileHandleForReadingFromURL:error:
+ _objc_msgSend$fileTypeForURL:
+ _objc_msgSend$pathExtension
+ _objc_msgSend$requestImageProcessing:forFileHandle:fileType:identifier:requestID:andReply:
+ _objc_msgSend$requestVideoProcessing:fileHandle:fileType:fileURL:sandboxToken:identifier:requestID:reply:
+ _objc_msgSend$requiresBlastdoor
+ _objc_msgSend$typeWithFilenameExtension:
- GCC_except_table112
- GCC_except_table132
- GCC_except_table134
- GCC_except_table143
- GCC_except_table149
- GCC_except_table158
- GCC_except_table168
- GCC_except_table173
- GCC_except_table176
- GCC_except_table178
- GCC_except_table180
- GCC_except_table182
- GCC_except_table184
- GCC_except_table186
- GCC_except_table189
- GCC_except_table196
- GCC_except_table209
- GCC_except_table212
- GCC_except_table85
- GCC_except_table87
- GCC_except_table89
- GCC_except_table91
- GCC_except_table97
- _objc_msgSend$requestImageProcessing:forAssetURL:withSandboxToken:identifier:requestID:andReply:
- _objc_msgSend$requestVideoProcessing:assetURL:sandboxToken:identifier:requestID:reply:
Functions:
+ -[MADService fileTypeForURL:]
~ -[MADService performRequests:onImageURL:withIdentifier:completionHandler:] : 920 -> 952
~ -[MADService performRequests:onImageURL:withIdentifier:error:] : 1076 -> 1128
~ -[MADService performRequests:videoURL:identifier:progressHandler:completionHandler:] : 960 -> 1748
CStrings:
+ "Could not determine a media type for %@"
```
