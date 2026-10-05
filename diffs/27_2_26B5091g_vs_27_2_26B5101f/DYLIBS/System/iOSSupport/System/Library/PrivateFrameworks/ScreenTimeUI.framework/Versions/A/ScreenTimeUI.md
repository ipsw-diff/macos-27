## ScreenTimeUI

> `/System/iOSSupport/System/Library/PrivateFrameworks/ScreenTimeUI.framework/Versions/A/ScreenTimeUI`

```diff

-655.1.9.1.0
-  __TEXT.__text: 0x32e90
-  __TEXT.__objc_methlist: 0x1cc0
+655.1.12.0.0
+  __TEXT.__text: 0x32f2c
+  __TEXT.__objc_methlist: 0x1cc8
   __TEXT.__const: 0xc34
   __TEXT.__cstring: 0x1966
   __TEXT.__gcc_except_tab: 0x4a4

   __DATA_CONST.__objc_catlist: 0x28
   __DATA_CONST.__objc_protolist: 0x48
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1a50
+  __DATA_CONST.__objc_selrefs: 0x1a60
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__got: 0x730

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 1117
-  Symbols:   2291
+  Functions: 1118
+  Symbols:   2294
   CStrings:  405
 
Symbols:
+ -[UIImage(STImageAdditions) iconFromPrecomposedImage:platform:migratedToNewScreenTime:]
+ _objc_msgSend$iconFromPrecomposedImage:platform:migratedToNewScreenTime:
+ _objc_msgSend$isMigratedToNewScreenTime
Functions:
~ -[STIconCache imageForBundleIdentifier:completionHandler:] : 1372 -> 1412
~ -[STIconCache _handleiTunesResponseForAppInfo:response:data:error:completionHandler:] : 844 -> 884
~ -[STIconCache imageForBundleIdentifier:] : 1172 -> 1204
~ -[STIconCache _handleiTunesResponseForAppInfo:response:data:error:] : 688 -> 724
~ -[UIImage(STImageAdditions) iconFromPrecomposedImage:platform:] : 412 -> 8
+ -[UIImage(STImageAdditions) iconFromPrecomposedImage:platform:migratedToNewScreenTime:]
```
