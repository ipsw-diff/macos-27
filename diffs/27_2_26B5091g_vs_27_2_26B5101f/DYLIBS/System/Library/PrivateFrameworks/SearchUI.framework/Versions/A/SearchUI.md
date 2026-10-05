## SearchUI

> `/System/Library/PrivateFrameworks/SearchUI.framework/Versions/A/SearchUI`

```diff

-685.1.3.0.0
-  __TEXT.__text: 0xcdec8
-  __TEXT.__objc_methlist: 0xf774
+685.1.8.0.0
+  __TEXT.__text: 0xce0bc
+  __TEXT.__objc_methlist: 0xf7bc
   __TEXT.__const: 0x2f74
   __TEXT.__cstring: 0x3514
-  __TEXT.__oslogstring: 0x2635
+  __TEXT.__oslogstring: 0x2685
   __TEXT.__gcc_except_tab: 0x7d0
   __TEXT.__ustring: 0xa8
   __TEXT.__dlopen_cstrs: 0xb2

   __TEXT.__swift_as_ret: 0xdc
   __TEXT.__swift_as_cont: 0x164
   __TEXT.__swift5_mpenum: 0x8
-  __TEXT.__unwind_info: 0x4748
+  __TEXT.__unwind_info: 0x4758
   __TEXT.__eh_frame: 0x1a20
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x408
   __DATA_CONST.__objc_protolist: 0x2e0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x86a0
+  __DATA_CONST.__objc_selrefs: 0x86d8
   __DATA_CONST.__objc_protorefs: 0x78
   __DATA_CONST.__objc_superrefs: 0x5c8
   __DATA_CONST.__objc_arraydata: 0xac0
   __DATA_CONST.__got: 0x1e20
   __AUTH_CONST.__const: 0x3ca0
   __AUTH_CONST.__cfstring: 0x3660
-  __AUTH_CONST.__objc_const: 0x1ae30
+  __AUTH_CONST.__objc_const: 0x1ae60
   __AUTH_CONST.__objc_intobj: 0x150
   __AUTH_CONST.__objc_arrayobj: 0x9c0
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_doubleobj: 0x10
-  __AUTH_CONST.__auth_got: 0x1410
+  __AUTH_CONST.__auth_got: 0x1418
   __AUTH.__objc_data: 0x2d88
   __AUTH.__data: 0x3c8
-  __DATA.__objc_ivar: 0xbac
+  __DATA.__objc_ivar: 0xbb0
   __DATA.__data: 0x25b0
   __DATA.__bss: 0xa78
   __DATA.__common: 0xe8

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 5945
-  Symbols:   13505
-  CStrings:  801
+  Functions: 5951
+  Symbols:   13518
+  CStrings:  802
 
Symbols:
+ +[SearchUICollectionViewItem reportedSizeForItem:inFrame:]
+ +[SearchUIUtilities standardGridContentInset]
+ -[SearchUIGridSectionModel separatorStyleForIndex:shouldDrawTopAndBottomSeparators:]
+ -[SearchUIImage boundsTargetSizeExactly]
+ -[SearchUIImage setBoundsTargetSizeExactly:]
+ OBJC_IVAR_$_SearchUIImage._boundsTargetSizeExactly
+ _TLKImageHasAlphaChannel
+ __OBJC_$_CLASS_METHODS_SearchUICollectionViewItem
+ ___block_descriptor_90_e8_32s40bs_e17_v16?0"PHAsset"8l
+ ___block_descriptor_98_e8_32s40s48bs_e5_v8?0l
+ _objc_msgSend$boundsTargetSizeExactly
+ _objc_msgSend$layoutAttributesForItemWithIndexPath:
+ _objc_msgSend$preferredLayoutAttributesFittingAttributes:
+ _objc_msgSend$searchui_cardLoader
+ _objc_msgSend$setBoundsTargetSizeExactly:
+ _objc_msgSend$setResizeMode:
+ _objc_msgSend$setTouchScrollingEnabled:
+ _objc_msgSend$standardGridContentInset
- __75-[SearchUIOpenUserActivityHandler performCommand:triggerEvent:environment:]_block_invoke_2
- ___75-[SearchUIOpenUserActivityHandler performCommand:triggerEvent:environment:]_block_invoke_2
- ___block_descriptor_89_e8_32s40bs_e17_v16?0"PHAsset"8l
- ___block_descriptor_97_e8_32s40s48bs_e5_v8?0l
- _objc_msgSend$cardLoader
CStrings:
+ "No application record for %@, refusing to open user activity with an unresolved destination"
```
