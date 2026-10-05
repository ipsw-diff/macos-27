## WebKitLegacy

> `/System/Library/Frameworks/WebKit.framework/Versions/A/Frameworks/WebKitLegacy.framework/Versions/A/WebKitLegacy`

```diff

-625.2.5.11.1
-  __TEXT.__text: 0x19c058
-  __TEXT.__objc_methlist: 0x10258
+625.2.7.1.0
+  __TEXT.__text: 0x19c0f8
+  __TEXT.__objc_methlist: 0x10250
   __TEXT.__const: 0x67a
   __TEXT.__getClass_cstr: 0x30
-  __TEXT.__gcc_except_tab: 0x1495c
-  __TEXT.__cstring: 0x1ea70
+  __TEXT.__gcc_except_tab: 0x14958
+  __TEXT.__cstring: 0x1eb25
   __TEXT.__oslogstring: 0x14a
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0xa4f8
+  __TEXT.__unwind_info: 0xa4f0
   __TEXT.__eh_frame: 0x88
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_catlist: 0x98
   __DATA_CONST.__objc_protolist: 0x1a8
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x94a0
+  __DATA_CONST.__objc_selrefs: 0x9498
   __DATA_CONST.__objc_protorefs: 0x58
   __DATA_CONST.__objc_superrefs: 0x368
   __DATA_CONST.__objc_arraydata: 0x38
   __DATA_CONST.__got: 0x1420
   __AUTH_CONST.__const: 0x5390
-  __AUTH_CONST.__cfstring: 0xff60
+  __AUTH_CONST.__cfstring: 0xffe0
   __AUTH_CONST.__objc_const: 0x11490
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x3d8
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x28
-  __AUTH_CONST.__auth_got: 0x4760
+  __AUTH_CONST.__auth_got: 0x4758
   __AUTH.__objc_data: 0x2a30
   __AUTH.__data: 0x40
   __DATA.__objc_ivar: 0x508

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 7530
-  Symbols:   15917
-  CStrings:  2529
+  Functions: 7529
+  Symbols:   15915
+  CStrings:  2533
 
Symbols:
- +[WebCoreStatistics garbageCollectJavaScriptObjectsOnAlternateThreadForDebugging:]
- __ZN7WebCore27GarbageCollectionController43garbageCollectOnAlternateThreadForDebuggingEb
Functions:
~ +[WebPreferences initialize] : 13068 -> 13124
~ -[DOMElement focus] : 264 -> 268
- +[WebCoreStatistics setJavaScriptGarbageCollectorTimerEnabled:]
~ +[WebPreferences(WebPrivateInternalFeatures) _internalFeatures] : 14132 -> 14256
~ -[WebView(WebViewInternalPreferencesChangedGenerated) _preferencesChangedGenerated:] : 23932 -> 23952
CStrings:
+ "AppKit gestures for manipulation surfaces"
+ "Use AppKit gestures to drive manipulation surfaces"
+ "UseAppKitGesturesForManipulationSurfaces"
+ "WebKitUseAppKitGesturesForManipulationSurfaces"
```
