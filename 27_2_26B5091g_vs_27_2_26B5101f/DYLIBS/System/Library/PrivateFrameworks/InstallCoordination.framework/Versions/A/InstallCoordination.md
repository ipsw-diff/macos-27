## InstallCoordination

> `/System/Library/PrivateFrameworks/InstallCoordination.framework/Versions/A/InstallCoordination`

```diff

-849.40.4.0.1
-  __TEXT.__text: 0x65600
-  __TEXT.__objc_methlist: 0x4988
+849.40.7.0.2
+  __TEXT.__text: 0x65d78
+  __TEXT.__objc_methlist: 0x4a38
   __TEXT.__const: 0xc8
-  __TEXT.__cstring: 0x189ec
+  __TEXT.__cstring: 0x18b86
   __TEXT.__gcc_except_tab: 0x1c10
   __TEXT.__oslogstring: 0x195
   __TEXT.__ustring: 0x4
-  __TEXT.__unwind_info: 0x1da8
+  __TEXT.__unwind_info: 0x1dd0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x9c8
-  __DATA_CONST.__objc_classlist: 0x210
+  __DATA_CONST.__const: 0x9d0
+  __DATA_CONST.__objc_classlist: 0x220
   __DATA_CONST.__objc_catlist: 0x18
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x22b0
+  __DATA_CONST.__objc_selrefs: 0x22e8
   __DATA_CONST.__got: 0x0
-  __AUTH_CONST.__const: 0x19a0
-  __AUTH_CONST.__cfstring: 0x5fe0
-  __AUTH_CONST.__objc_const: 0xd5c0
+  __AUTH_CONST.__const: 0x19d0
+  __AUTH_CONST.__cfstring: 0x6060
+  __AUTH_CONST.__objc_const: 0xd7c0
   __AUTH_CONST.__auth_got: 0x4b0
+  __AUTH.__objc_data: 0xa0
   __DATA.__objc_protorefs: 0x20
-  __DATA.__objc_classrefs: 0x348
-  __DATA.__objc_superrefs: 0x180
-  __DATA.__objc_ivar: 0x254
+  __DATA.__objc_classrefs: 0x350
+  __DATA.__objc_superrefs: 0x190
+  __DATA.__objc_ivar: 0x260
   __DATA.__data: 0x1e0
   __DATA.__bss: 0x90
   __DATA_DIRTY.__objc_data: 0x14a0

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 1823
-  Symbols:   4034
-  CStrings:  1908
+  Functions: 1837
+  Symbols:   4067
+  CStrings:  1916
 
Symbols:
+ +[IXAppInstallCoordinator(IXAppReplacement) managedAppBundleIdentifiersWithError:]
+ +[IXAppInstallCoordinator(IXAppReplacement) prepareForAppReplacementSourceLookupWithOptions:error:]
+ -[IXAppReplacementSourceCacheOptions copyWithZone:]
+ -[IXAppReplacementSourceCacheOptions hash]
+ -[IXAppReplacementSourceCacheOptions initForTesting]
+ -[IXAppReplacementSourceCacheOptions isEqual:]
+ -[IXAppReplacementSourceResolver .cxx_destruct]
+ -[IXAppReplacementSourceResolver identity]
+ -[IXAppReplacementSourceResolver initWithIdentity:managedAppBundleIdentifiers:]
+ -[IXAppReplacementSourceResolver managedAppBundleIdentifiers]
+ -[IXAppReplacementSourceResolver resolveAppReplacementSource:replacementRuledOut:replacementCandidate:error:]
+ -[IXPlaceholderAttributes alternateDisplayNames]
+ -[IXPlaceholderAttributes setAlternateDisplayNames:]
+ OBJC_IVAR_$_IXAppReplacementSourceResolver._identity
+ OBJC_IVAR_$_IXAppReplacementSourceResolver._managedAppBundleIdentifiers
+ OBJC_IVAR_$_IXPlaceholderAttributes._alternateDisplayNames
+ _OBJC_CLASS_$_IXAppReplacementSourceCacheOptions
+ _OBJC_CLASS_$_IXAppReplacementSourceResolver
+ _OBJC_METACLASS_$_IXAppReplacementSourceCacheOptions
+ _OBJC_METACLASS_$_IXAppReplacementSourceResolver
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementSourceCacheOptions
+ __OBJC_$_INSTANCE_METHODS_IXAppReplacementSourceResolver
+ __OBJC_$_INSTANCE_VARIABLES_IXAppReplacementSourceResolver
+ __OBJC_$_PROP_LIST_IXAppReplacementSourceResolver
+ __OBJC_CLASS_PROTOCOLS_$_IXAppReplacementSourceCacheOptions
+ __OBJC_CLASS_RO_$_IXAppReplacementSourceCacheOptions
+ __OBJC_CLASS_RO_$_IXAppReplacementSourceResolver
+ __OBJC_METACLASS_RO_$_IXAppReplacementSourceCacheOptions
+ __OBJC_METACLASS_RO_$_IXAppReplacementSourceResolver
+ ___43-[IXPlaceholderAttributes infoPlistContent]_block_invoke
+ ___block_descriptor_40_e8_32s_e35_v32?0"NSString"8"NSString"16^B24l
+ _objc_msgSend$alternateDisplayNames
+ _objc_msgSend$setAlternateDisplayNames:
CStrings:
+ "+[IXAppInstallCoordinator(IXAppReplacement) managedAppBundleIdentifiersWithError:]"
+ "+[IXAppInstallCoordinator(IXAppReplacement) prepareForAppReplacementSourceLookupWithOptions:error:]"
+ "-[IXAppReplacementSourceResolver resolveAppReplacementSource:replacementRuledOut:replacementCandidate:error:]"
+ "CFBundleDisplayName#"
+ "Car"
+ "Failed to replace data container."
+ "alternateDisplayNames"
+ "v32@?0@\"NSString\"8@\"NSString\"16^B24"
```
