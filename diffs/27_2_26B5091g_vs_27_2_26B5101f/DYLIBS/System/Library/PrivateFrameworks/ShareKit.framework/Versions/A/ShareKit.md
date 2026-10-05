## ShareKit

> `/System/Library/PrivateFrameworks/ShareKit.framework/Versions/A/ShareKit`

```diff

-2131.20.71.0.0
-  __TEXT.__text: 0x772ec
+2131.21.21.0.0
+  __TEXT.__text: 0x773c4
   __TEXT.__objc_methlist: 0x5b34
   __TEXT.__const: 0x20c
   __TEXT.__cstring: 0x470a
-  __TEXT.__gcc_except_tab: 0x1418
-  __TEXT.__oslogstring: 0x63f4
+  __TEXT.__gcc_except_tab: 0x1430
+  __TEXT.__oslogstring: 0x6429
   __TEXT.__ustring: 0x128
   __TEXT.__dlopen_cstrs: 0x52
-  __TEXT.__unwind_info: 0x2258
+  __TEXT.__unwind_info: 0x2260
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x70
   __DATA_CONST.__objc_protolist: 0x108
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4850
+  __DATA_CONST.__objc_selrefs: 0x4860
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x1a8
   __DATA_CONST.__objc_arraydata: 0x68

   - /System/Library/PrivateFrameworks/ViewBridge.framework/Versions/A/ViewBridge
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2576
-  Symbols:   6299
-  CStrings:  1257
+  Functions: 2577
+  Symbols:   6301
+  CStrings:  1258
 
Symbols:
+ _objc_msgSend$postNotificationName:object:userInfo:audience:entitlement:options:error:
+ _objc_msgSend$reportCreationFailureWithError:
Functions:
~ +[SHKSharingService saveDefaultDisplayOrder:domain:] : 312 -> 436
~ -[SHKSharingServicePicker _showErrorViewAndCancelCollaborationPerformerForError:] : 320 -> 352
+ +[SHKSharingService saveDefaultDisplayOrder:domain:].cold.2
CStrings:
+ "Failed to post display order notification for %@: %@"
```
