## TranslationUI

> `/System/Library/PrivateFrameworks/TranslationUI.framework/Versions/A/TranslationUI`

```diff

-388.0.0.0.0
-  __TEXT.__text: 0xc5794
+389.0.0.0.0
+  __TEXT.__text: 0xc5804
   __TEXT.__objc_methlist: 0xd54
   __TEXT.__const: 0x7884
   __TEXT.__cstring: 0x1746

   __AUTH_CONST.__const: 0x5368
   __AUTH_CONST.__cfstring: 0x140
   __AUTH_CONST.__objc_const: 0x21f0
-  __AUTH_CONST.__auth_got: 0x1750
+  __AUTH_CONST.__auth_got: 0x1760
   __AUTH.__objc_data: 0x6f8
   __AUTH.__data: 0x950
   __DATA.__objc_ivar: 0x30

   - /System/Library/PrivateFrameworks/TextRecognition.framework/Versions/A/TextRecognition
   - /System/Library/PrivateFrameworks/TranslationUIServices.framework/Versions/A/TranslationUIServices
   - /System/Library/PrivateFrameworks/VisionKitCore.framework/Versions/A/VisionKitCore
+  - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/swift/libswiftAVFoundation.dylib

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 3706
-  Symbols:   1985
+  Symbols:   1987
   CStrings:  381
 
Symbols:
+ _MobileGestalt_get_current_device
+ _MobileGestalt_get_deviceSupportsInstructionFollowingPruningModels
Functions:
~ sub_2a3aad0f0 -> sub_2a3afc130 : 88 -> 200
```
