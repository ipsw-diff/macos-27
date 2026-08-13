## PhotosFormats

> `/System/Library/PrivateFrameworks/PhotosFormats.framework/Versions/A/PhotosFormats`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__weak_got`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_doubleobj`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH.__objc_data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-910.34.101.0.0
-  __TEXT.__text: 0xdd5dc
+911.0.111.0.0
+  __TEXT.__text: 0xdd5cc
   __TEXT.__objc_methlist: 0xc740
   __TEXT.__const: 0x2da0
   __TEXT.__dlopen_cstrs: 0x43

   - /System/Library/PrivateFrameworks/CMPhoto.framework/Versions/A/CMPhoto
   - /System/Library/PrivateFrameworks/MMCS.framework/Versions/A/MMCS
   - /System/Library/PrivateFrameworks/PhotoFoundation.framework/Versions/A/PhotoFoundation
+  - /System/Library/PrivateFrameworks/Portrait.framework/Versions/A/Portrait
   - /System/Library/PrivateFrameworks/SoftLinking.framework/Versions/A/SoftLinking
   - /usr/lib/libAppleArchive.dylib
   - /usr/lib/libMobileGestalt.dylib

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 4844
-  Symbols:   11552
+  Symbols:   11553
   CStrings:  2532
 
Symbols:
+ _objc_msgSend$setSupportsLandscapeConfiguration:
Functions:
~ -[PFPosterDynamicDeviceConfiguration initWithCoder:] : 668 -> 708
~ +[PFParallaxLayoutConfiguration configurationForScreenSize:screenScale:determinedConfiguration:orientation:] : 640 -> 600
~ -[PFPosterOrientedLayout layoutByUpdatingImageSize:] : 1736 -> 1720
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFAppleArchive.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxAsset.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayer.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayerStack.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayerStackArchiver.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayoutConfiguration.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayoutUtilities.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFPosterConfiguration.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFPosterLayout.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryAutoEditConfiguration.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryAutoEditFrequencyTable.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeAsset.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeDisplayAsset.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeDisplayAssetNormalization.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeLibrary.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeSongAsset.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.6QE7cA/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeStyle.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFAppleArchive.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxAsset.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayer.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayerStack.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayerStackArchiver.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayoutConfiguration.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFParallaxLayoutUtilities.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFPosterConfiguration.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/PFPosterLayout.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryAutoEditConfiguration.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryAutoEditFrequencyTable.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeAsset.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeDisplayAsset.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeDisplayAssetNormalization.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeLibrary.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeSongAsset.m"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.EbTYr4/Sources/Photos_Foundation/Projects/PhotosFormats/PhotosFormats/story/PFStoryRecipeStyle.m"
```
