## CarPlay

> `/System/iOSSupport/System/Library/Frameworks/CarPlay.framework/Versions/A/CarPlay`

```diff

-552.4.1.0.0
-  __TEXT.__text: 0x5ba28
-  __TEXT.__objc_methlist: 0x8ff8
-  __TEXT.__const: 0x35a
-  __TEXT.__cstring: 0x53f6
-  __TEXT.__oslogstring: 0x246e
+552.7.2.0.0
+  __TEXT.__text: 0x5c3f8
+  __TEXT.__objc_methlist: 0x90e0
+  __TEXT.__const: 0x36a
+  __TEXT.__cstring: 0x5486
+  __TEXT.__oslogstring: 0x24ce
   __TEXT.__gcc_except_tab: 0x794
   __TEXT.__constg_swiftt: 0x134
   __TEXT.__swift5_typeref: 0x7f

   __TEXT.__swift5_fieldmd: 0x64
   __TEXT.__swift5_proto: 0x4
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x23b0
+  __TEXT.__unwind_info: 0x23d8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x1d20
-  __DATA_CONST.__objc_classlist: 0x3e0
+  __DATA_CONST.__objc_classlist: 0x3e8
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x220
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3cd0
-  __DATA_CONST.__objc_protorefs: 0x100
-  __DATA_CONST.__objc_superrefs: 0x340
+  __DATA_CONST.__objc_selrefs: 0x3d18
+  __DATA_CONST.__objc_protorefs: 0x108
+  __DATA_CONST.__objc_superrefs: 0x348
   __DATA_CONST.__got: 0x680
   __AUTH_CONST.__const: 0x9a8
-  __AUTH_CONST.__cfstring: 0x53c0
-  __AUTH_CONST.__objc_const: 0x1f640
+  __AUTH_CONST.__cfstring: 0x5420
+  __AUTH_CONST.__objc_const: 0x1f880
   __AUTH_CONST.__objc_intobj: 0xd8
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__auth_got: 0x630
-  __AUTH.__objc_data: 0x48
-  __DATA.__objc_ivar: 0xa08
+  __AUTH.__objc_data: 0x98
+  __DATA.__objc_ivar: 0xa18
   __DATA.__data: 0x1940
   __DATA.__bss: 0x360
   __DATA.__common: 0x18

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 3094
-  Symbols:   7143
-  CStrings:  963
+  Functions: 3111
+  Symbols:   7184
+  CStrings:  968
 
Symbols:
+ +[CPPlaybackItemIdentifier supportsSecureCoding]
+ -[CPListTemplate _playableItemForMatchingIdentifier:]
+ -[CPListTemplate listTemplateWithIdentifier:requestPlaybackConfirmationForMatchingIdentifier:completionHandler:]
+ -[CPPlaybackConfiguration .cxx_destruct]
+ -[CPPlaybackConfiguration initWithPreferredPresentation:playbackAction:elapsedTime:duration:requiresPlaybackConfirmation:]
+ -[CPPlaybackConfiguration playbackConfirmationBlock]
+ -[CPPlaybackConfiguration requiresPlaybackConfirmation]
+ -[CPPlaybackConfiguration setPlaybackConfirmationBlock:]
+ -[CPPlaybackItemIdentifier .cxx_destruct]
+ -[CPPlaybackItemIdentifier elementIndex]
+ -[CPPlaybackItemIdentifier encodeWithCoder:]
+ -[CPPlaybackItemIdentifier identifier]
+ -[CPPlaybackItemIdentifier initWithCoder:]
+ -[CPPlaybackItemIdentifier initWithIdentifier:]
+ -[CPPlaybackItemIdentifier initWithIdentifier:elementIndex:]
+ CPBarButtonSanitizedImage
+ OBJC_IVAR_$_CPPlaybackConfiguration._playbackConfirmationBlock
+ OBJC_IVAR_$_CPPlaybackConfiguration._requiresPlaybackConfirmation
+ OBJC_IVAR_$_CPPlaybackItemIdentifier._elementIndex
+ OBJC_IVAR_$_CPPlaybackItemIdentifier._identifier
+ _CPBarButtonMaximumImageSize
+ _CPBarButtonSanitizedImage
+ _OBJC_CLASS_$_CPPlaybackItemIdentifier
+ _OBJC_METACLASS_$_CPPlaybackItemIdentifier
+ __OBJC_$_CLASS_METHODS_CPPlaybackItemIdentifier
+ __OBJC_$_CLASS_PROP_LIST_CPPlaybackItemIdentifier
+ __OBJC_$_INSTANCE_METHODS_CPPlaybackItemIdentifier
+ __OBJC_$_INSTANCE_VARIABLES_CPPlaybackItemIdentifier
+ __OBJC_$_PROP_LIST_CPPlaybackItemIdentifier
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_CPListClientTemplateDelegate
+ __OBJC_CLASS_PROTOCOLS_$_CPPlaybackItemIdentifier
+ __OBJC_CLASS_RO_$_CPPlaybackItemIdentifier
+ __OBJC_METACLASS_RO_$_CPPlaybackItemIdentifier
+ __OBJC_PROTOCOL_REFERENCE_$_CPPlayableItem
+ ___112-[CPListTemplate listTemplateWithIdentifier:requestPlaybackConfirmationForMatchingIdentifier:completionHandler:]_block_invoke
+ _objc_msgSend$_playableItemForMatchingIdentifier:
+ _objc_msgSend$elementIndex
+ _objc_msgSend$initWithIdentifier:elementIndex:
+ _objc_msgSend$initWithPreferredPresentation:playbackAction:elapsedTime:duration:requiresPlaybackConfirmation:
+ _objc_msgSend$playbackConfirmationBlock
+ _objc_msgSend$requiresPlaybackConfirmation
+ _objc_msgSend$setPlaybackConfirmationBlock:
- GCC_except_table74
CStrings:
+ "%@ requesting playback confirmation for %{public}@"
+ "Failed to identify a local playable item for %@ %lu"
+ "kCPPlaybackConfigurationRequiresPlaybackConfirmationKey"
+ "kCPPlaybackItemIdentifierElementIndexKey"
+ "kCPPlaybackItemIdentifierIdentifierKey"
```
