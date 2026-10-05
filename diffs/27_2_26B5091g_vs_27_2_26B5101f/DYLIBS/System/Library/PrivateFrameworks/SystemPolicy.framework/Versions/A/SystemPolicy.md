## SystemPolicy

> `/System/Library/PrivateFrameworks/SystemPolicy.framework/Versions/A/SystemPolicy`

```diff

-823.40.10.0.0
-  __TEXT.__text: 0x18e5c
+823.40.13.0.0
+  __TEXT.__text: 0x19370
   __TEXT.__objc_methlist: 0x19f0
   __TEXT.__const: 0xd8
   __TEXT.__cstring: 0x1826
-  __TEXT.__gcc_except_tab: 0x1bc
-  __TEXT.__oslogstring: 0x1544
+  __TEXT.__gcc_except_tab: 0x218
+  __TEXT.__oslogstring: 0x166c
   __TEXT.__dlopen_cstrs: 0x62
-  __TEXT.__unwind_info: 0xa88
+  __TEXT.__unwind_info: 0xab0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x30
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xfa0
+  __DATA_CONST.__objc_selrefs: 0xfb8
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0xd8
   __DATA_CONST.__objc_arraydata: 0x4a0
-  __DATA_CONST.__got: 0x2e0
+  __DATA_CONST.__got: 0x2e8
   __AUTH_CONST.__const: 0x930
   __AUTH_CONST.__cfstring: 0x2220
   __AUTH_CONST.__objc_const: 0x3818
   __AUTH_CONST.__objc_arrayobj: 0x1b0
   __AUTH_CONST.__objc_dictobj: 0xa0
   __AUTH_CONST.__objc_intobj: 0x30
-  __AUTH_CONST.__auth_got: 0x4a0
+  __AUTH_CONST.__auth_got: 0x4c0
   __DATA.__objc_ivar: 0x2b0
   __DATA.__data: 0x248
   __DATA.__bss: 0xd0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libmis.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 818
-  Symbols:   1805
-  CStrings:  460
+  Functions: 825
+  Symbols:   1815
+  CStrings:  467
 
Symbols:
+ -[SPScriptScanner getScriptScanEvaluationForFileHandle:scriptData:scanResult:]
+ _OBJC_EHTYPE_$_NSException
+ ___78-[SPScriptScanner getScriptScanEvaluationForFileHandle:scriptData:scanResult:]_block_invoke
+ _copyURLForFileHandle
+ _fcntl
+ _fstat
+ _objc_begin_catch
+ _objc_end_catch
+ _objc_msgSend$fileDescriptor
+ _objc_msgSend$fileURLWithFileSystemRepresentation:isDirectory:relativeToURL:
+ _objc_msgSend$getScriptScanEvaluationForFileHandle:scriptHash:scanResult:withReply:
+ _objc_msgSend$reason
+ copyURLForFileHandle
- -[SPScriptScanner getScriptScanEvaluationFor:scriptData:scanResult:]
- ___68-[SPScriptScanner getScriptScanEvaluationFor:scriptData:scanResult:]_block_invoke
- _objc_msgSend$getScriptScanEvaluationFor:scriptHash:scanResult:withReply:
CStrings:
+ "Failed to get the path of a file handle: %s"
+ "Failed to stat file handle: %s"
+ "Failed to stat the path of a file handle (%s): %s"
+ "File handle has no usable descriptor"
+ "File handle is not a regular file: mode %o"
+ "File handle is not usable: %@"
+ "Path of a file handle (%s) no longer refers to the open file"
```
