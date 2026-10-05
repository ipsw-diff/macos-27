## TranslationDaemon

> `/System/Library/PrivateFrameworks/TranslationDaemon.framework/Versions/A/TranslationDaemon`

```diff

-393.1.0.0.0
-  __TEXT.__text: 0x1b08a0
-  __TEXT.__objc_methlist: 0x1a568
+396.0.0.0.0
+  __TEXT.__text: 0x1b11dc
+  __TEXT.__objc_methlist: 0x1a628
   __TEXT.__const: 0x9d0
-  __TEXT.__gcc_except_tab: 0x1b558
-  __TEXT.__cstring: 0x63fb
-  __TEXT.__oslogstring: 0xdda0
+  __TEXT.__gcc_except_tab: 0x1b4c8
+  __TEXT.__cstring: 0x643b
+  __TEXT.__oslogstring: 0xdfb0
   __TEXT.__dlopen_cstrs: 0xb2
   __TEXT.__swift5_typeref: 0x36d
   __TEXT.__swift5_capture: 0xe0

   __TEXT.__swift_as_ret: 0xc
   __TEXT.__swift_as_cont: 0x10
   __TEXT.__swift5_protos: 0x4
-  __TEXT.__unwind_info: 0x11078
+  __TEXT.__unwind_info: 0x11090
   __TEXT.__eh_frame: 0x388
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x1810
-  __DATA_CONST.__objc_classlist: 0x11d8
+  __DATA_CONST.__const: 0x1808
+  __DATA_CONST.__objc_classlist: 0x11e0
   __DATA_CONST.__objc_catlist: 0x140
   __DATA_CONST.__objc_protolist: 0x100
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6c90
+  __DATA_CONST.__objc_selrefs: 0x6cd8
   __DATA_CONST.__objc_protorefs: 0x10
-  __DATA_CONST.__objc_superrefs: 0x1128
+  __DATA_CONST.__objc_superrefs: 0x1130
   __DATA_CONST.__objc_arraydata: 0x3e8
   __DATA_CONST.__got: 0xf50
   __AUTH_CONST.__const: 0x4350
-  __AUTH_CONST.__cfstring: 0x7f00
-  __AUTH_CONST.__objc_const: 0x2d2c8
+  __AUTH_CONST.__cfstring: 0x7f20
+  __AUTH_CONST.__objc_const: 0x2d410
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x348
   __AUTH_CONST.__objc_arrayobj: 0x138
   __AUTH_CONST.__objc_dictobj: 0xc8
   __AUTH_CONST.__objc_doubleobj: 0x30
   __AUTH_CONST.__auth_got: 0xbc8
-  __AUTH.__objc_data: 0xa1c0
-  __DATA.__objc_ivar: 0x11fc
-  __DATA.__data: 0xd70
+  __AUTH.__objc_data: 0xa210
+  __DATA.__objc_ivar: 0x1204
+  __DATA.__data: 0xd90
   __DATA.__bss: 0x6b0
   __DATA_DIRTY.__objc_data: 0x1130
-  __DATA_DIRTY.__data: 0x2c0
+  __DATA_DIRTY.__data: 0x2a8
   __DATA_DIRTY.__bss: 0x320
   __DATA_DIRTY.__common: 0x30
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswiftDispatch.dylib
   - /usr/lib/swift/libswiftIOKit.dylib
   - /usr/lib/swift/libswiftMetal.dylib
-  - /usr/lib/swift/libswiftNaturalLanguage.dylib
   - /usr/lib/swift/libswiftOSLog.dylib
   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftQuartzCore.dylib

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 10615
-  Symbols:   21548
-  CStrings:  2292
+  Functions: 10631
+  Symbols:   21580
+  CStrings:  2301
 
Symbols:
+ +[_LTHotfixManager _selectHotfixAssetFromEntries:minimumFormatVersion:maximumFormatVersion:]
+ +[_LTSpeechTranslationAssetInfo _phrasebookHasContentAtLocalFileURL:]
+ +[_LTTranslationServer _canReuseAIAdapterEngine:forContext:]
+ -[_LTAIAdapterTranslationEngine matchesInferenceLocationForLocalePair:aiInferenceLocation:]
+ -[_LTHotfixAssetMetadata .cxx_destruct]
+ -[_LTHotfixAssetMetadata description]
+ -[_LTHotfixAssetMetadata formatVersion]
+ -[_LTHotfixAssetMetadata initWithName:version:formatVersion:]
+ -[_LTHotfixAssetMetadata name]
+ -[_LTHotfixAssetMetadata version]
+ -[_LTHotfixManager _attemptHotfixRefresh:]
+ -[_LTHotfixManager _downloadHotfixAsset:completion:]
+ -[_LTHotfixManager _extractArchive:forAsset:]
+ -[_LTHotfixManager _installHotfixAsset:archive:completion:]
+ -[_LTHotfixManager _installedHotfixDirectoryForAsset:]
+ -[_LTHotfixManager _replaceHotfixOnInternalQueue:completion:]
+ -[_LTHotfixManager _resolveAvailableHotfix:]
+ OBJC_IVAR_$__LTHotfixAssetMetadata._formatVersion
+ OBJC_IVAR_$__LTHotfixAssetMetadata._name
+ OBJC_IVAR_$__LTHotfixAssetMetadata._version
+ _OBJC_CLASS_$__LTHotfixAssetMetadata
+ _OBJC_METACLASS_$__LTHotfixAssetMetadata
+ __42-[_LTHotfixManager _attemptHotfixRefresh:]_block_invoke
+ __44-[_LTHotfixManager _resolveAvailableHotfix:]_block_invoke
+ __52-[_LTHotfixManager _downloadHotfixAsset:completion:]_block_invoke
+ __59-[_LTHotfixManager _installHotfixAsset:archive:completion:]_block_invoke
+ __59-[_LTHotfixManager _installHotfixAsset:archive:completion:]_block_invoke_2
+ __CLASS_METHODS__LTAIAdapterImplementation
+ __OBJC_$_CLASS_METHODS__LTTranslationServer
+ __OBJC_$_INSTANCE_METHODS__LTHotfixAssetMetadata
+ __OBJC_$_INSTANCE_VARIABLES__LTHotfixAssetMetadata
+ __OBJC_$_PROP_LIST__LTHotfixAssetMetadata
+ __OBJC_CLASS_RO_$__LTHotfixAssetMetadata
+ __OBJC_METACLASS_RO_$__LTHotfixAssetMetadata
+ ___42-[_LTHotfixManager _attemptHotfixRefresh:]_block_invoke
+ ___44-[_LTHotfixManager _resolveAvailableHotfix:]_block_invoke
+ ___46-[_LTHotfixManager _replaceHotfix:completion:]_block_invoke
+ ___52-[_LTHotfixManager _downloadHotfixAsset:completion:]_block_invoke
+ ___52-[_LTHotfixManager _downloadWithRequest:completion:]_block_invoke_2
+ ___59-[_LTHotfixManager _installHotfixAsset:archive:completion:]_block_invoke
+ ___59-[_LTHotfixManager _installHotfixAsset:archive:completion:]_block_invoke_2
+ ___block_descriptor_48_e8_32s40bs_e34_v24?0"NSDictionary"8"NSError"16l
+ ___block_descriptor_48_e8_32s40bs_e44_v24?0"_LTHotfixAssetMetadata"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48bs_e28_v24?0"NSData"8"NSError"16l
+ ___block_descriptor_56_e8_32s40s48bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24l
+ _hotfixDirectory
+ _isCompleteHotfixDirectory
+ _objc_msgSend$_attemptHotfixRefresh:
+ _objc_msgSend$_canReuseAIAdapterEngine:forContext:
+ _objc_msgSend$_downloadHotfixAsset:completion:
+ _objc_msgSend$_extractArchive:forAsset:
+ _objc_msgSend$_installHotfixAsset:archive:completion:
+ _objc_msgSend$_installedHotfixDirectoryForAsset:
+ _objc_msgSend$_phrasebookHasContentAtLocalFileURL:
+ _objc_msgSend$_replaceHotfixOnInternalQueue:completion:
+ _objc_msgSend$_resolveAvailableHotfix:
+ _objc_msgSend$_selectHotfixAssetFromEntries:minimumFormatVersion:maximumFormatVersion:
+ _objc_msgSend$initWithName:version:formatVersion:
+ _objc_msgSend$matchesInferenceLocationForLocalePair:aiInferenceLocation:
+ _objc_msgSend$resolvedAIInferenceLocation
+ _objc_msgSend$resolvedInferenceLocationForLocation:localePair:taskHint:
- +[_LTHotfixManager _hotfixDirectoryNameForEntry:]
- +[_LTHotfixManager _selectHotfixEntryFromMapping:minimumFormatVersion:maximumFormatVersion:]
- -[_LTAIAdapterTranslationEngine aiInferenceLocation]
- -[_LTHotfixManager _downloadHotfix:completion:]
- -[_LTHotfixManager _installNewestSupportedHotfix:]
- -[_LTHotfixManager updateHotfix:]
- OBJC_IVAR_$__LTAIAdapterTranslationEngine._aiInferenceLocation
- __34-[_LTHotfixManager refreshHotfix:]_block_invoke
- __34-[_LTHotfixManager refreshHotfix:]_block_invoke_2
- __47-[_LTHotfixManager _downloadHotfix:completion:]_block_invoke
- __50-[_LTHotfixManager _installNewestSupportedHotfix:]_block_invoke
- ___33-[_LTHotfixManager updateHotfix:]_block_invoke
- ___34-[_LTHotfixManager refreshHotfix:]_block_invoke_2
- ___47-[_LTHotfixManager _downloadHotfix:completion:]_block_invoke
- ___47-[_LTHotfixManager _downloadHotfix:completion:]_block_invoke_2
- ___50-[_LTHotfixManager _installNewestSupportedHotfix:]_block_invoke
- ___block_descriptor_48_e8_32bs40w_e17_v16?0"NSError"8l
- ___block_descriptor_48_e8_32bs40w_e34_v24?0"NSDictionary"8"NSError"16l
- ___block_descriptor_48_e8_32s40bs_e46_v32?0"NSData"8"NSURLResponse"16"NSError"24l
- ___block_descriptor_64_e8_32s40s48bs56w_e28_v24?0"NSData"8"NSError"16l
- __swift_FORCE_LOAD_$_swiftNaturalLanguage
- __swift_FORCE_LOAD_$_swiftNaturalLanguage_$_TranslationDaemon
- _objc_msgSend$_downloadHotfix:completion:
- _objc_msgSend$_hotfixDirectoryNameForEntry:
- _objc_msgSend$_installNewestSupportedHotfix:
- _objc_msgSend$_replaceHotfix:completion:
- _objc_msgSend$_selectHotfixEntryFromMapping:minimumFormatVersion:maximumFormatVersion:
- _objc_msgSend$updateHotfix:
- _parseHotfixEntryVersions
CStrings:
+ "%@ (%d-%d)"
+ "Abandoning refresh of %{public}@ after download failure, installed hotfix left in place"
+ "Can't reuse AI adapter engine: its session runs %{public}@ inference, but %{public}@ under %{public}@ resolves to %{public}@"
+ "Download hotfix: %{public}@"
+ "Extracted hotfix %@ holds no %@"
+ "Extracted hotfix completeness check failed: %@"
+ "Failed to download hotfix archive %{public}@, error code %{public}ld: %@"
+ "Failed to find compatible hotfix between versions %d-%d, out of %lu mapping entries"
+ "Found existing hotfix, no need to install"
+ "Hotfix install prepare failure: %@"
+ "Installed hotfix %{public}@"
+ "Resolved available hotfix %{public}@"
+ "Reusing existing AI adapter engine since it supports this locale pair and its inference session config hasn't changed"
+ "Skipping phrasebook symlink for %{public}@: no files in %{public}@/PB"
+ "Successfully downloaded hotfix archive %{public}@"
+ "Treating hotfix %{public}@ as not installed, its directory couldn't be read: %@"
+ "ai_ifp_speech_to_speech"
+ "v24@?0@\"_LTHotfixAssetMetadata\"8@\"NSError\"16"
- "Found existing hotfix"
- "Hotfix asset refresh prepare failure: %@"
- "Hotfix asset refresh update failure: %@"
- "Hotfix entry does not name a version to install"
- "Refusing to install a hotfix entry that names no version: %@"
- "Remove folder failed: %@"
- "Reusing existing AI adapter engine since it supports this locale pair and the task hint and process identifier haven't changed"
- "Select hotfix: %@"
- "Update of hotfix assets failed: %@"
```
