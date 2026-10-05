## LaunchServices

> `/System/Library/Frameworks/CoreServices.framework/Versions/A/Frameworks/LaunchServices.framework/Versions/A/LaunchServices`

```diff

-1517.1.9.0.0
-  __TEXT.__text: 0x2508b8
+1517.1.11.400.0
+  __TEXT.__text: 0x24faec
   __TEXT.__lazy_helpers: 0xa8
-  __TEXT.__objc_methlist: 0xee9c
+  __TEXT.__objc_methlist: 0xee6c
   __TEXT.__const: 0xad8
-  __TEXT.__cstring: 0x33e9d
-  __TEXT.__oslogstring: 0x229f9
-  __TEXT.__gcc_except_tab: 0x34e34
+  __TEXT.__cstring: 0x33ce0
+  __TEXT.__oslogstring: 0x229f4
+  __TEXT.__gcc_except_tab: 0x34cbc
   __TEXT.__ustring: 0x1be
   __TEXT.__dof_LSFSNode: 0x2b6
-  __TEXT.__unwind_info: 0x10328
+  __TEXT.__unwind_info: 0x102d0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x190
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x6ee8
+  __DATA_CONST.__objc_selrefs: 0x6ed8
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x638
   __DATA_CONST.__objc_arraydata: 0xa10
   __DATA_CONST.__got: 0xe40
-  __AUTH_CONST.__const: 0xabe8
-  __AUTH_CONST.__cfstring: 0x1e1e0
-  __AUTH_CONST.__objc_const: 0x166b8
+  __AUTH_CONST.__const: 0xab88
+  __AUTH_CONST.__cfstring: 0x1e1a0
+  __AUTH_CONST.__objc_const: 0x166a8
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__lazy_load_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x738

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/system/libxpc.dylib
-  Functions: 11226
-  Symbols:   19615
-  CStrings:  7986
+  Functions: 11221
+  Symbols:   19606
+  CStrings:  7985
 
Symbols:
+ _LSRegisterExtensionPoint
+ _LSRegisterExtensionPointInfo
+ _LSRegisterPlatformExtensionPointInfo
+ _LSRegisterPlatformFrameworkExtensionPointInfo
+ _LSRegisterPluginURL
+ __LSGetPIDVersionFromToken
- -[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]
- -[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]
- __LSRegisterExtensionPointClient
- __LSUnregisterExtensionPoint
- __LSUnregisterExtensionPointClient
- ___101-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]_block_invoke
- ___92-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]_block_invoke
- ____LSRegisterExtensionPointClient_block_invoke
- ____LSRegisterExtensionPointClient_block_invoke_2
- ____LSUnregisterExtensionPointClient_block_invoke
- ____LSUnregisterExtensionPointClient_block_invoke_2
- ___block_descriptor_64_ea8_32s40s48bs_e42_v24?0"LSDBExecutionContext"8"NSError"16l
- ___block_descriptor_68_ea8_32s40s48s56bs_e42_v24?0"LSDBExecutionContext"8"NSError"16l
- _objc_msgSend$registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:
- _objc_msgSend$unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:
CStrings:
+ " pidversion="
+ "_LSRegisterExtensionPointInfo"
+ "_LSRegisterPlatformExtensionPointInfo"
+ "_LSRegisterPlatformFrameworkExtensionPointInfo"
+ "_LSRegisterPluginURL"
+ "cannot register extension points from a LS client"
+ "deprecated function %{public}s called"
- "%s Registering extension point with identifier '%@' platform: %d url '%@' SDK Dictionary: %@"
- "-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]"
- "-[_LSDModifyClient registerExtensionPoint:platform:declaringURL:withInfo:completionHandler:]_block_invoke"
- "-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]"
- "-[_LSDModifyClient unregisterExtensionPoint:platform:withVersion:parentBundleUnit:completionHandler:]_block_invoke"
- "OSStatus _LSRegisterPlatformFrameworkExtensionPointInfo(CFStringRef, uint32_t, CFURLRef, CFDictionaryRef)"
- "invalid extensionPoint SDK dictionary"
- "invalid extensionPoint identifier"
```
