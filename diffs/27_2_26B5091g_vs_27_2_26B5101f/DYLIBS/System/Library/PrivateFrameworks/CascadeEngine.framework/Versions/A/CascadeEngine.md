## CascadeEngine

> `/System/Library/PrivateFrameworks/CascadeEngine.framework/Versions/A/CascadeEngine`

```diff

-256.0.1.0.0
-  __TEXT.__text: 0x67fd0
-  __TEXT.__objc_methlist: 0x1f2c
+258.0.0.0.0
+  __TEXT.__text: 0x682c0
+  __TEXT.__objc_methlist: 0x1f44
   __TEXT.__const: 0x1280
-  __TEXT.__gcc_except_tab: 0x6f4
-  __TEXT.__cstring: 0x2acf
+  __TEXT.__gcc_except_tab: 0x6d0
+  __TEXT.__cstring: 0x2aff
   __TEXT.__ustring: 0x84
-  __TEXT.__oslogstring: 0x6cff
+  __TEXT.__oslogstring: 0x6d4f
   __TEXT.__dlopen_cstrs: 0x47
   __TEXT.__swift5_typeref: 0xe32
   __TEXT.__swift5_reflstr: 0x31e

   __TEXT.__swift_as_entry: 0x98
   __TEXT.__swift_as_ret: 0x98
   __TEXT.__swift_as_cont: 0xdc
-  __TEXT.__unwind_info: 0x1b20
-  __TEXT.__eh_frame: 0x1840
+  __TEXT.__unwind_info: 0x1b30
+  __TEXT.__eh_frame: 0x1868
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x120
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1a78
+  __DATA_CONST.__objc_selrefs: 0x1a88
   __DATA_CONST.__objc_protorefs: 0x60
   __DATA_CONST.__objc_superrefs: 0xe0
   __DATA_CONST.__objc_arraydata: 0x50

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 2387
-  Symbols:   2887
-  CStrings:  834
+  Functions: 2389
+  Symbols:   2890
+  CStrings:  837
 
Symbols:
+ -[CCRapportManager _isFileTransferSessionPossibleWithPeer:error:]
+ -[CCRapportManager _peerHasIPLink:]
+ -[CCRapportManager _statusFlagsUnionForPeer:matchedDeviceCount:]
+ _objc_msgSend$_isFileTransferSessionPossibleWithPeer:error:
+ _objc_msgSend$_statusFlagsUnionForPeer:matchedDeviceCount:
- -[CCRapportManager _isFileTransferSessionPossible:]
- _objc_msgSend$_isFileTransferSessionPossible:
CStrings:
+ " no"
+ "%@ active device statusFlags: 0x%llx"
+ "%@ has%s IP link (%lu active device(s))"
+ "No transport available for a Rapport FileTransferSession"
- "WiFi is off"
```
