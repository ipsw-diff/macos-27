## ScreenTimeUI

> `/System/Library/PrivateFrameworks/ScreenTimeUI.framework/Versions/A/ScreenTimeUI`

```diff

-655.1.9.1.0
-  __TEXT.__text: 0x69910
-  __TEXT.__objc_methlist: 0x1fe0
+655.1.12.0.0
+  __TEXT.__text: 0x699bc
+  __TEXT.__objc_methlist: 0x1fe8
   __TEXT.__const: 0x3404
   __TEXT.__cstring: 0x2f55
   __TEXT.__gcc_except_tab: 0x4ac

   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x58
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1e70
+  __DATA_CONST.__objc_selrefs: 0x1e80
   __DATA_CONST.__objc_protorefs: 0x10
   __DATA_CONST.__objc_superrefs: 0x40
   __DATA_CONST.__got: 0xbf0

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2086
-  Symbols:   2775
+  Functions: 2087
+  Symbols:   2778
   CStrings:  504
 
Symbols:
+ -[NSImage(STImageAdditions) iconFromPrecomposedImage:platform:migratedToNewScreenTime:]
+ _objc_msgSend$iconFromPrecomposedImage:platform:migratedToNewScreenTime:
+ _objc_msgSend$isMigratedToNewScreenTime
Functions:
~ -[STIconCache imageForBundleIdentifier:completionHandler:] : 1460 -> 1504
~ -[STIconCache _handleiTunesResponseForAppInfo:response:data:error:completionHandler:] : 928 -> 972
~ -[STIconCache imageForBundleIdentifier:] : 1232 -> 1268
~ -[STIconCache _handleiTunesResponseForAppInfo:response:data:error:] : 752 -> 792
~ -[NSImage(STImageAdditions) iconFromPrecomposedImage:platform:] : 468 -> 8
+ -[NSImage(STImageAdditions) iconFromPrecomposedImage:platform:migratedToNewScreenTime:]
```
