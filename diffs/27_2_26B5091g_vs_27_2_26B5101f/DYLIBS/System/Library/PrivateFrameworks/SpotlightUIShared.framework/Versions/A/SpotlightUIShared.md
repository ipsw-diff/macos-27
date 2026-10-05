## SpotlightUIShared

> `/System/Library/PrivateFrameworks/SpotlightUIShared.framework/Versions/A/SpotlightUIShared`

```diff

-250.1.4.1.0
-  __TEXT.__text: 0xf6714
-  __TEXT.__objc_methlist: 0x13c0
+250.1.10.100.0
+  __TEXT.__text: 0xf7a94
+  __TEXT.__objc_methlist: 0x1480
   __TEXT.__const: 0xb1fc
-  __TEXT.__cstring: 0x3e18
-  __TEXT.__gcc_except_tab: 0xac
-  __TEXT.__oslogstring: 0x1a62
+  __TEXT.__cstring: 0x3ea8
+  __TEXT.__gcc_except_tab: 0x2c
+  __TEXT.__oslogstring: 0x1c22
   __TEXT.__ustring: 0x7de
   __TEXT.__swift5_typeref: 0x39f2
   __TEXT.__swift5_reflstr: 0x1fa8

   __TEXT.__swift5_capture: 0x8bc
   __TEXT.__swift5_builtin: 0x140
   __TEXT.__swift5_mpenum: 0x34
-  __TEXT.__unwind_info: 0x5688
-  __TEXT.__eh_frame: 0x9f54
+  __TEXT.__unwind_info: 0x5708
+  __TEXT.__eh_frame: 0x9f84
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0xb0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1cc8
+  __DATA_CONST.__objc_selrefs: 0x1d88
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0x30
   __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__got: 0x1250
-  __AUTH_CONST.__const: 0x7b49
-  __AUTH_CONST.__cfstring: 0xae0
-  __AUTH_CONST.__objc_const: 0x40e8
+  __DATA_CONST.__got: 0x12c0
+  __AUTH_CONST.__const: 0x7b79
+  __AUTH_CONST.__cfstring: 0xb60
+  __AUTH_CONST.__objc_const: 0x4118
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1dd8
+  __AUTH_CONST.__auth_got: 0x1e00
   __AUTH.__objc_data: 0x12f8
   __AUTH.__data: 0x2738
-  __DATA.__objc_ivar: 0x84
+  __DATA.__objc_ivar: 0x88
   __DATA.__data: 0x1b48
   __DATA.__objc_stublist: 0x8
   __DATA.__bss: 0xc3b0

   - /System/Library/Frameworks/LinkPresentation.framework/Versions/A/LinkPresentation
   - /System/Library/Frameworks/MapKit.framework/Versions/A/MapKit
   - /System/Library/Frameworks/QuartzCore.framework/Versions/A/QuartzCore
+  - /System/Library/Frameworks/Security.framework/Versions/A/Security
   - /System/Library/Frameworks/SwiftUI.framework/Versions/A/SwiftUI
   - /System/Library/Frameworks/UniformTypeIdentifiers.framework/Versions/A/UniformTypeIdentifiers
   - /System/Library/Frameworks/UserNotifications.framework/Versions/A/UserNotifications

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5745
-  Symbols:   3319
-  CStrings:  553
+  Functions: 5777
+  Symbols:   3386
+  CStrings:  561
 
Symbols:
+ +[SUISPasteboardExtractor attributeSetWithPasteboard:newlyCachedFiles:]
+ +[SUISPasteboardExtractor createIdentifierKey]
+ +[SUISPasteboardExtractor finalizeUniqueIdentifierForAttributeSet:]
+ +[SUISPasteboardExtractor hashStringFromData:]
+ +[SUISPasteboardExtractor hashStringFromRawHash:]
+ +[SUISPasteboardExtractor hashStringFromString:key:]
+ +[SUISPasteboardExtractor identifierKeyQuery]
+ +[SUISPasteboardExtractor identifierKey]
+ +[SUISPasteboardExtractor loadIdentifierKey]
+ +[SUISPasteboardExtractor readIdentifierKeyWithStatus:]
+ +[SUISPasteboardManager carryOverHistoryAttributesTo:from:]
+ +[SUISPasteboardManager indexActionForAttributeSet:generationCount:lastIndexedAttributeSet:lastIndexedGeneration:hasNewlyCachedFiles:]
+ +[SUISPasteboardManager pasteboardIndexingQueue]
+ +[SUIUtilities isEventShapeHighlightEnabled]
+ -[SUISPasteboardManager clearPasteboardHistoryIfWipeRequested]
+ -[SUISPasteboardManager deleteCachedFiles:]
+ -[SUISPasteboardManager deleteStalePasteboardItem:]
+ -[SUISPasteboardManager forgetLastIndexedAttributeSet:]
+ -[SUISPasteboardManager historyItemCopiedGeneration]
+ -[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:replacing:newlyCachedFiles:]
+ -[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:generationCount:newlyCachedFiles:]
+ -[SUISPasteboardManager lastIndexedAttributeSet]
+ -[SUISPasteboardManager lastIndexedGeneration]
+ -[SUISPasteboardManager setHistoryItemCopiedGeneration:]
+ -[SUISPasteboardManager setLastIndexedAttributeSet:]
+ -[SUISPasteboardManager setLastIndexedGeneration:]
+ GCC_except_table11
+ OBJC_IVAR_$_SUISPasteboardManager._historyItemCopiedGeneration
+ OBJC_IVAR_$_SUISPasteboardManager._lastIndexedAttributeSet
+ OBJC_IVAR_$_SUISPasteboardManager._lastIndexedGeneration
+ _CCHmac
+ _CC_SHA256
+ _OBJC_CLASS_$_NSMutableData
+ _OUTLINED_FUNCTION_2
+ _SecItemAdd
+ _SecItemCopyMatching
+ _SecRandomCopyBytes
+ __71+[SUISImageOrPDFPasteboardExtractor modifyAttributeSet:withPasteboard:]_block_invoke
+ __91-[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:replacing:newlyCachedFiles:]_block_invoke
+ ___109-[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:generationCount:newlyCachedFiles:]_block_invoke
+ ___45-[SUISPasteboardManager pasteboardDidChange:]_block_invoke
+ ___48+[SUISPasteboardManager pasteboardIndexingQueue]_block_invoke
+ ___55-[SUISPasteboardManager forgetLastIndexedAttributeSet:]_block_invoke
+ ___91-[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:replacing:newlyCachedFiles:]_block_invoke
+ ___block_descriptor_64_e8_32s40s48s56s_e17_v16?0"NSError"8l
+ ___block_descriptor_64_e8_32s40s48s_e5_v8?0l
+ ___block_descriptor_72_e8_32s40s48s56s64s_e17_v16?0"NSArray"8l
+ ___block_descriptor_88_e8_32s40s48s56s64s72s80s_e5_v8?0l
+ ___copy_helper_block_e8_32s40s48s56s
+ ___copy_helper_block_e8_32s40s48s56s64s
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s
+ ___destroy_helper_block_e8_32s40s48s56s
+ ___destroy_helper_block_e8_32s40s48s56s64s
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s
+ ___kCFBooleanFalse
+ _kSecAttrAccessGroup
+ _kSecAttrAccessible
+ _kSecAttrAccessibleAfterFirstUnlockThisDeviceOnly
+ _kSecAttrAccount
+ _kSecAttrService
+ _kSecAttrSynchronizable
+ _kSecClass
+ _kSecClassGenericPassword
+ _kSecRandomDefault
+ _kSecReturnData
+ _kSecUseDataProtectionKeychain
+ _kSecValueData
+ _objc_msgSend$attributeSetWithPasteboard:newlyCachedFiles:
+ _objc_msgSend$bytes
+ _objc_msgSend$carryOverHistoryAttributesTo:from:
+ _objc_msgSend$clearPasteboardHistoryIfWipeRequested
+ _objc_msgSend$contentCreationDate
+ _objc_msgSend$createIdentifierKey
+ _objc_msgSend$dataUsingEncoding:
+ _objc_msgSend$dataWithLength:
+ _objc_msgSend$deleteCachedFiles:
+ _objc_msgSend$deleteStalePasteboardItem:
+ _objc_msgSend$finalizeUniqueIdentifierForAttributeSet:
+ _objc_msgSend$forgetLastIndexedAttributeSet:
+ _objc_msgSend$hashStringFromData:
+ _objc_msgSend$hashStringFromRawHash:
+ _objc_msgSend$hashStringFromString:key:
+ _objc_msgSend$historyItemCopiedGeneration
+ _objc_msgSend$identifierKey
+ _objc_msgSend$identifierKeyQuery
+ _objc_msgSend$indexActionForAttributeSet:generationCount:lastIndexedAttributeSet:lastIndexedGeneration:hasNewlyCachedFiles:
+ _objc_msgSend$indexCoreSpotlightItemWithAttributeSet:replacing:newlyCachedFiles:
+ _objc_msgSend$indexOrUpdateIfExistsCorespotlightItemAttributeSet:generationCount:newlyCachedFiles:
+ _objc_msgSend$isCachedPasteboardFileURL:
+ _objc_msgSend$lastIndexedAttributeSet
+ _objc_msgSend$lastIndexedGeneration
+ _objc_msgSend$loadIdentifierKey
+ _objc_msgSend$mutableBytes
+ _objc_msgSend$needsPasteboardHistoryWipe
+ _objc_msgSend$pasteboardIndexingQueue
+ _objc_msgSend$readIdentifierKeyWithStatus:
+ _objc_msgSend$setHistoryItemCopiedGeneration:
+ _objc_msgSend$setLastIndexedAttributeSet:
+ _objc_msgSend$setLastIndexedGeneration:
+ _objc_msgSend$setNeedsPasteboardHistoryWipe:
+ _objc_msgSend$setObject:forKeyedSubscript:
+ _objc_msgSend$sortUsingSelector:
+ _objc_msgSend$stringWithCapacity:
+ _objc_msgSend$thumbnailBundleID
+ _sIdentifierKey
+ pasteboardIndexingQueue.onceToken
+ pasteboardIndexingQueue.queue
- +[SUISImageOrPDFPasteboardExtractor copyFile:toDestination:]
- +[SUISImageOrPDFPasteboardExtractor uniqueFilePathForDirectory:withFileName:]
- +[SUISPasteboardExtractor attributeSetWithPasteboard:]
- +[SUISPasteboardManager pasteboardExpirationManagerQueue]
- -[SUISPasteboardManager changeCount]
- -[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:]
- -[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:]
- -[SUISPasteboardManager pasteboardHistoryItemWasCopied]
- -[SUISPasteboardManager setChangeCount:]
- -[SUISPasteboardManager setPasteboardHistoryItemWasCopied:]
- GCC_except_table3
- OBJC_IVAR_$_SUISPasteboardManager._changeCount
- OBJC_IVAR_$_SUISPasteboardManager._pasteboardHistoryItemWasCopied
- __64-[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:]_block_invoke
- ___57+[SUISPasteboardManager pasteboardExpirationManagerQueue]_block_invoke
- ___64-[SUISPasteboardManager indexCoreSpotlightItemWithAttributeSet:]_block_invoke
- ___76-[SUISPasteboardManager indexOrUpdateIfExistsCorespotlightItemAttributeSet:]_block_invoke
- ___Block_byref_object_copy_
- ___Block_byref_object_dispose_
- ___block_descriptor_48_e8_32s40s_e17_v16?0"NSError"8l
- ___block_descriptor_56_e8_32s40s48s_e17_v16?0"NSArray"8l
- ___block_descriptor_80_e8_32s40s48s56s64r_e5_v8?0l
- ___copy_helper_block_e8_32s40s48s56s64r
- ___destroy_helper_block_e8_32s40s48s56s64r
- _objc_msgSend$attributeSetWithPasteboard:
- _objc_msgSend$containsString:
- _objc_msgSend$copyItemAtURL:toURL:error:
- _objc_msgSend$hash
- _objc_msgSend$indexCoreSpotlightItemWithAttributeSet:
- _objc_msgSend$indexOrUpdateIfExistsCorespotlightItemAttributeSet:
- _objc_msgSend$localizedDescription
- _objc_msgSend$pasteboardExpirationManagerQueue
- _objc_msgSend$pasteboardHistoryItemWasCopied
- _objc_msgSend$pathExtension
- _objc_msgSend$setChangeCount:
- _objc_msgSend$setPasteboardHistoryItemWasCopied:
- _objc_msgSend$stringByDeletingPathExtension
- _objc_msgSend$uniqueFilePathForDirectory:withFileName:
- pasteboardExpirationManagerQueue.onceToken
- pasteboardExpirationManagerQueue.queue
CStrings:
+ "%02x"
+ "%@ extracted nothing from the pasteboard, skipping"
+ "SUIEventShapeHighlights"
+ "already indexed this content for generation count %ld, skipping hash:%@"
+ "better extraction for generation count %ld, replacing hash:%@ with hash:%@"
+ "cached attachment for generation count %ld was gone, re-indexing hash:%@"
+ "com.apple.Spotlight.pasteboardHistory"
+ "com.apple.spotlight.delete.pasteboard.unindexed"
+ "com.apple.spotlight.pasteboardIndexingQueue"
+ "com.apple.spotlight.replace.pasteboard.superseded"
+ "deleting stale pasteboard item hash:%@ files:%lu"
+ "failed to generate pasteboard identifier key"
+ "failed to read pasteboard identifier key: %d"
+ "failed to store pasteboard identifier key: %d"
+ "failed to write %{private}@ data"
+ "generated a new pasteboard identifier key"
+ "identifierKey"
+ "no identifier key available, not indexing this pasteboard item"
+ "not indexing pasteboard item, identifier length:%lu lastUsedDate:%@"
+ "pasteboard did update, generation count: %ld"
+ "pasteboard identifier key already exists, re-reading"
+ "wiping pasteboard history for the new identifier scheme"
- "%@ (%ld)"
- "%@ (%ld).%@"
- "%lu"
- "Failed to copy file: %@"
- "Failed to remove existing file: %@"
- "File copied successfully to: %@"
- "Source file does not exist: %@"
- "com.apple.spotlight.pasteboardExpirationManagerQueue"
- "copying fileURL %{private}@ to destinationURL %{private}@"
- "identifier for CSSItem has no length"
- "pasteboard change count is: %ld"
- "pasteboard did update"
- "updating changeCount from:%ld to %ld"
- "we're missing the lastuseddate when indexing. Skip indexing."
```
