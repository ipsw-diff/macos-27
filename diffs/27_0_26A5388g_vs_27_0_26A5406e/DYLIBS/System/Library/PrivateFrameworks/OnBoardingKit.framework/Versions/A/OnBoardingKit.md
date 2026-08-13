## OnBoardingKit

> `/System/Library/PrivateFrameworks/OnBoardingKit.framework/Versions/A/OnBoardingKit`

### Sections with Same Size but Changed Content

- `__TEXT.__constg_swiftt`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_doubleobj`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-3977.0.20.0.0
-  __TEXT.__text: 0x26be8
-  __TEXT.__objc_methlist: 0x2d0c
+3977.0.22.0.0
+  __TEXT.__text: 0x26f8c
+  __TEXT.__objc_methlist: 0x2d6c
   __TEXT.__gcc_except_tab: 0x164
   __TEXT.__const: 0x186
-  __TEXT.__cstring: 0x14f9
+  __TEXT.__cstring: 0x1529
   __TEXT.__oslogstring: 0x923
   __TEXT.__constg_swiftt: 0x50
   __TEXT.__swift5_typeref: 0x6
   __TEXT.__swift5_fieldmd: 0x10
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x7f0
+  __TEXT.__unwind_info: 0x7f8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0x28
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x2300
+  __DATA_CONST.__objc_selrefs: 0x2348
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_superrefs: 0xd8
   __DATA_CONST.__objc_arraydata: 0x60
   __DATA_CONST.__got: 0x430
   __AUTH_CONST.__const: 0x3a0
-  __AUTH_CONST.__cfstring: 0x1ce0
-  __AUTH_CONST.__objc_const: 0x5bd8
+  __AUTH_CONST.__cfstring: 0x1d60
+  __AUTH_CONST.__objc_const: 0x5c68
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_doubleobj: 0x10
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__objc_data: 0x7d0
   __AUTH.__data: 0x98
-  __DATA.__objc_ivar: 0x3f4
+  __DATA.__objc_ivar: 0x400
   __DATA.__data: 0x1e0
   __DATA.__bss: 0x48
   __DATA.__common: 0x60

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 960
-  Symbols:   2716
-  CStrings:  302
+  Functions: 968
+  Symbols:   2735
+  CStrings:  306
 
Symbols:
+ -[OBPrivacyFlow _bestStringConsideringNetworkForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:countryPolicySuffix:]
+ -[OBPrivacyFlow _stringForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:countryPolicySuffix:withNetworkSuffix:]
+ -[OBPrivacyFlow _stringKeyWithCapabilitiesFromPrefix:withNetwork:withGenerative:countryPolicySuffix:]
+ -[OBPrivacyFlow localizedButtonSecondaryCaptionForLanguage:preferredDeviceType:]
+ -[OBPrivacyLinkButton initWithTitle:caption:captionAttachmentImage:secondaryCaption:symbolName:useLargeIcon:textAlignment:]
+ -[OBPrivacyLinkButton secondaryCaptionText]
+ -[OBPrivacyLinkButton setSecondaryCaptionText:]
+ -[OBTemplateView bodyTextReservedRegionHeight]
+ -[OBTemplateView hasCapturedBodyTextReservedRegion]
+ -[OBTemplateView setBodyTextReservedRegionHeight:]
+ -[OBTemplateView setHasCapturedBodyTextReservedRegion:]
+ OBJC_IVAR_$_OBPrivacyLinkButton._secondaryCaptionText
+ OBJC_IVAR_$_OBTemplateView._bodyTextReservedRegionHeight
+ OBJC_IVAR_$_OBTemplateView._hasCapturedBodyTextReservedRegion
+ _objc_msgSend$_bestStringConsideringNetworkForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:countryPolicySuffix:
+ _objc_msgSend$_stringForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:countryPolicySuffix:withNetworkSuffix:
+ _objc_msgSend$_stringKeyWithCapabilitiesFromPrefix:withNetwork:withGenerative:countryPolicySuffix:
+ _objc_msgSend$bodyTextReservedRegionHeight
+ _objc_msgSend$hasCapturedBodyTextReservedRegion
+ _objc_msgSend$initWithTitle:caption:captionAttachmentImage:secondaryCaption:symbolName:useLargeIcon:textAlignment:
+ _objc_msgSend$localizedButtonSecondaryCaptionForLanguage:preferredDeviceType:
+ _objc_msgSend$secondaryCaptionText
+ _objc_msgSend$setBodyTextReservedRegionHeight:
+ _objc_msgSend$setHasCapturedBodyTextReservedRegion:
+ _objc_msgSend$setSecondaryCaptionText:
+ _objc_msgSend$stringByAppendingFormat:
- -[OBPrivacyFlow _bestStringConsideringNetworkForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:withGMEChinaSuffix:]
- -[OBPrivacyFlow _stringForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:withGMEChinaSuffix:withNetworkSuffix:]
- -[OBPrivacyFlow _stringKeyWithCapabilitiesFromPrefix:withNetwork:withGenerative:withGMEChinaSuffix:]
- _objc_msgSend$_bestStringConsideringNetworkForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:withGMEChinaSuffix:
- _objc_msgSend$_stringForKeyWithPrefix:language:preferredDeviceType:withGenerativeSuffix:withGMEChinaSuffix:withNetworkSuffix:
- _objc_msgSend$_stringKeyWithCapabilitiesFromPrefix:withNetwork:withGenerative:withGMEChinaSuffix:
- _objc_msgSend$initWithTitle:caption:captionAttachmentImage:symbolName:useLargeIcon:textAlignment:
CStrings:
+ "\n\n"
+ " %@"
+ "BUTTON_CAPTION_SECONDARY"
+ "_NOTGMECHINA"
```
