## QueryParser

> `/System/Library/PrivateFrameworks/QueryParser.framework/Versions/A/QueryParser`

```diff

-3605.7.1.0.0
-  __TEXT.__text: 0x11c67c
-  __TEXT.__objc_methlist: 0x29ec
+3605.8.1.0.0
+  __TEXT.__text: 0x11d78c
+  __TEXT.__objc_methlist: 0x2a94
   __TEXT.__const: 0x2d48
-  __TEXT.__gcc_except_tab: 0x13918
-  __TEXT.__oslogstring: 0x7a5e
-  __TEXT.__cstring: 0xd4b5
+  __TEXT.__gcc_except_tab: 0x13af8
+  __TEXT.__oslogstring: 0x7bee
+  __TEXT.__cstring: 0xd525
   __TEXT.__ustring: 0x112
   __TEXT.__swift5_typeref: 0x5c2
   __TEXT.__constg_swiftt: 0x5f0

   __TEXT.__swift5_assocty: 0x90
   __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift5_protos: 0x8
-  __TEXT.__unwind_info: 0x5c80
+  __TEXT.__unwind_info: 0x5cd0
   __TEXT.__eh_frame: 0xc90
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x2118
+  __DATA_CONST.__objc_selrefs: 0x21a8
   __DATA_CONST.__objc_superrefs: 0xf0
   __DATA_CONST.__objc_arraydata: 0x1ff8
-  __DATA_CONST.__got: 0x780
-  __AUTH_CONST.__const: 0x4be0
-  __AUTH_CONST.__cfstring: 0x128c0
-  __AUTH_CONST.__objc_const: 0x4650
+  __DATA_CONST.__got: 0x788
+  __AUTH_CONST.__const: 0x4c10
+  __AUTH_CONST.__cfstring: 0x129e0
+  __AUTH_CONST.__objc_const: 0x46f8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x1b18
   __AUTH_CONST.__objc_arrayobj: 0x390

   __AUTH_CONST.__auth_got: 0x1480
   __AUTH.__objc_data: 0x8e8
   __AUTH.__data: 0x448
-  __DATA.__objc_ivar: 0x30c
+  __DATA.__objc_ivar: 0x310
   __DATA.__data: 0x11b0
   __DATA.__bss: 0x1510
   __DATA.__common: 0x18

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 4400
-  Symbols:   7142
-  CStrings:  3405
+  Functions: 4418
+  Symbols:   7170
+  CStrings:  3419
 
Symbols:
+ +[QPAssetManager _contentTypesForAssetSet:]
+ +[QPAssetManager _isKnownContentType:forAssetSet:]
+ +[QPAssetManager(Testing) _test_assetNameEmbedding]
+ +[QPAssetManager(Testing) _test_assetNameGeo]
+ +[QPAssetManager(Testing) _test_assetNameQueryParser]
+ +[QPAssetManager(Testing) _test_assetNameQueryUnderstanding]
+ +[QPAssetManager(Testing) _test_assetNameSFC]
+ +[QPAssetManager(Testing) _test_assetNameSafety]
+ +[QPAssetManager(Testing) _test_assetSetQueryParserOverrides]
+ +[QPAssetManager(Testing) _test_assetSetQueryParser]
+ -[QPAssetManager _bulkPopulateForAssetSet:locale:]
+ -[QPAssetManager _cacheKeyForAssetSet:locale:contentType:]
+ -[QPAssetManager(Testing) _test_bulkPopulateForAssetSet:locale:]
+ -[QPAssetManager(Testing) _test_bulkPopulateShortCircuitCount]
+ OBJC_IVAR_$_QPAssetManager._locked_bulkPopulateShortCircuitCount
+ _OBJC_CLASS_$_RBSAcquisitionCompletionAttribute
+ __50-[QPAssetManager _bulkPopulateForAssetSet:locale:]_block_invoke
+ __OBJC_$_CLASS_METHODS_QPAssetManager(Testing)
+ ___50-[QPAssetManager _bulkPopulateForAssetSet:locale:]_block_invoke
+ ___57-[QPAssetManager _systemAssetPathsForContentType:locale:]_block_invoke_2
+ ___62-[QPAssetManager(Testing) _test_bulkPopulateShortCircuitCount]_block_invoke
+ ___block_descriptor_56_ea8_32s40s48s_e17_v16?0"NSError"8l
+ ___block_descriptor_64_ea8_32s40s48r56r_e5_v8?0l
+ ___copy_helper_block_ea8_32s40s48r56r
+ ___destroy_helper_block_ea8_32s40s48r56r
+ _objc_msgSend$_bulkPopulateForAssetSet:locale:
+ _objc_msgSend$_cacheKeyForAssetSet:locale:contentType:
+ _objc_msgSend$_contentTypesForAssetSet:
+ _objc_msgSend$_isKnownContentType:forAssetSet:
+ _objc_msgSend$addEntriesFromDictionary:
+ _objc_msgSend$attributeWithCompletionPolicy:
+ _objc_msgSend$consistencyToken
+ _objc_msgSend$isLatestConsistencyToken:
- _ZL18assetManagerLoggerv
- __57-[QPAssetManager _systemAssetPathsForContentType:locale:]_block_invoke
- __OBJC_$_CLASS_METHODS_QPAssetManager
- __ZL18assetManagerLoggerv
- ___block_descriptor_48_ea8_32s40s_e17_v16?0"NSError"8l
CStrings:
+ "UAFAssetAccess"
+ "[UAF] Asset set changed during enumeration for %s locale %s — discarding"
+ "[UAF] Failed to acquire scoped RBS assertion: %s"
+ "[UAF] Timed out waiting for UAF flock release; skipping enumeration (%s locale %s)"
+ "[UAF] UAFAssetAccess unavailable, using FinishTaskUninterruptable: %s"
+ "[UAF] Unknown enumeratorTag %s for content type %s — skipping"
+ "[UAF] _bulkPopulateForAssetSet: no content descriptors registered for %s — BUG"
+ "[UAF] retrieveAssetSet: returned nil for %s locale %s — skipping bulk populate"
+ "assetName"
+ "com.apple.UnifiedAssetFramework"
+ "contentType"
+ "directory"
+ "entryKey"
+ "enumeratorTag"
+ "flat"
+ "perLocale"
- "[UAF] Failed to acquire scoped RBS assertion; skipping OTA retrieval this call: %s"
- "[UAF] Unknown content type: %s"
```
