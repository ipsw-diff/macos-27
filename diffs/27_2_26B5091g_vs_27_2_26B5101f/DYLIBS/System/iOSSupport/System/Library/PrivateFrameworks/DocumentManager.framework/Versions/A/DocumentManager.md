## DocumentManager

> `/System/iOSSupport/System/Library/PrivateFrameworks/DocumentManager.framework/Versions/A/DocumentManager`

```diff

-401.1.5.0.0
-  __TEXT.__text: 0x3207c
-  __TEXT.__objc_methlist: 0x2f8c
+403.1.8.0.0
+  __TEXT.__text: 0x32628
+  __TEXT.__objc_methlist: 0x2fac
   __TEXT.__const: 0x1b0
-  __TEXT.__cstring: 0x4ff5
+  __TEXT.__cstring: 0x5008
   __TEXT.__ustring: 0x68c
-  __TEXT.__oslogstring: 0x312a
+  __TEXT.__oslogstring: 0x3206
   __TEXT.__gcc_except_tab: 0x784
-  __TEXT.__unwind_info: 0x10c0
+  __TEXT.__unwind_info: 0x10e0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1598
   __DATA_CONST.__objc_classlist: 0x130
-  __DATA_CONST.__objc_catlist: 0x60
+  __DATA_CONST.__objc_catlist: 0x68
   __DATA_CONST.__objc_protolist: 0xc8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2b70
+  __DATA_CONST.__objc_selrefs: 0x2bc8
   __DATA_CONST.__objc_protorefs: 0x60
   __DATA_CONST.__objc_superrefs: 0xc8
   __DATA_CONST.__objc_arraydata: 0x10
-  __DATA_CONST.__got: 0x628
+  __DATA_CONST.__got: 0x630
   __AUTH_CONST.__const: 0x400
-  __AUTH_CONST.__cfstring: 0x4300
-  __AUTH_CONST.__objc_const: 0x4720
+  __AUTH_CONST.__cfstring: 0x4320
+  __AUTH_CONST.__objc_const: 0x4760
   __AUTH_CONST.__objc_intobj: 0x78
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x0

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libprequelite.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 1256
-  Symbols:   3322
-  CStrings:  840
+  Functions: 1264
+  Symbols:   3339
+  CStrings:  846
 
Symbols:
+ -[FPSandboxingURLWrapper(DOCCallerAuthorization) doc_noFollowSafeWrapper]
+ -[FPSandboxingURLWrapper(DOCCallerAuthorization) doc_wrapperAuthorizedForConnection:readonly:]
+ _FPOriginalDocumentURL
+ __OBJC_$_CATEGORY_FPSandboxingURLWrapper_$_DOCCallerAuthorization
+ __OBJC_$_CATEGORY_INSTANCE_METHODS_FPSandboxingURLWrapper_$_DOCCallerAuthorization
+ ___73-[FPSandboxingURLWrapper(DOCCallerAuthorization) doc_noFollowSafeWrapper]_block_invoke
+ _objc_msgSend$_resolveFlags
+ _objc_msgSend$assembleURL:sandbox:physicalURL:physicalSandbox:
+ _objc_msgSend$doc_hasSandboxAccessToFile:readonly:
+ _objc_msgSend$doc_noFollowSafeWrapper
+ _objc_msgSend$doc_noFollowURL
+ _objc_msgSend$getResourceValue:forKey:error:
+ _objc_msgSend$scope
+ _objc_msgSend$setTemporaryResourceValue:forKey:
+ _objc_msgSend$setVisibilityPriority:
+ _objc_msgSend$visibilityPriority
+ _objc_msgSend$wrapperWithSecurityScopedURL:
CStrings:
+ "Caller has no sandbox access to %@ readonly: %d"
+ "Could not resolve wrapped URL: %@"
+ "No connection to authorize wrapper against: %@"
+ "Resolvable URL not allowed access %@ readonly: %d"
+ "Wrapper carries no sandbox extension: %@"
+ "visibilityPriority"
```
