## CalendarFoundation

> `/System/Library/PrivateFrameworks/CalendarFoundation.framework/Versions/A/CalendarFoundation`

```diff

-1636.1.2.0.0
-  __TEXT.__text: 0x67754
-  __TEXT.__objc_methlist: 0x5fe4
-  __TEXT.__cstring: 0x70a2
-  __TEXT.__const: 0x564
-  __TEXT.__gcc_except_tab: 0xa7c
-  __TEXT.__oslogstring: 0x3705
+1636.2.2.0.0
+  __TEXT.__text: 0x69c04
+  __TEXT.__objc_methlist: 0x600c
+  __TEXT.__cstring: 0x70d2
+  __TEXT.__const: 0x8c4
+  __TEXT.__gcc_except_tab: 0xa78
+  __TEXT.__oslogstring: 0x37d5
   __TEXT.__ustring: 0x2e8
   __TEXT.__dlopen_cstrs: 0xe0
-  __TEXT.__swift5_typeref: 0x1f8
-  __TEXT.__constg_swiftt: 0x104
-  __TEXT.__swift5_reflstr: 0xf7
-  __TEXT.__swift5_fieldmd: 0xf8
-  __TEXT.__swift5_proto: 0xc
-  __TEXT.__swift5_types: 0x14
+  __TEXT.__swift5_typeref: 0x2cc
+  __TEXT.__constg_swiftt: 0x1b8
+  __TEXT.__swift5_reflstr: 0x140
+  __TEXT.__swift5_fieldmd: 0x170
+  __TEXT.__swift5_proto: 0x34
+  __TEXT.__swift5_types: 0x2c
+  __TEXT.__swift5_builtin: 0x50
+  __TEXT.__swift5_mpenum: 0x8
+  __TEXT.__swift5_assocty: 0x30
   __TEXT.__swift5_capture: 0xfc
-  __TEXT.__swift5_builtin: 0x14
   __TEXT.__swift_as_entry: 0x8
   __TEXT.__swift_as_ret: 0x8
   __TEXT.__swift_as_cont: 0x8
-  __TEXT.__unwind_info: 0x2870
+  __TEXT.__unwind_info: 0x2940
   __TEXT.__eh_frame: 0x130
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0xce0
+  __DATA_CONST.__const: 0xce8
   __DATA_CONST.__objc_classlist: 0x370
   __DATA_CONST.__objc_catlist: 0xb0
   __DATA_CONST.__objc_protolist: 0xc0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x4390
+  __DATA_CONST.__objc_selrefs: 0x43b8
   __DATA_CONST.__objc_protorefs: 0x18
-  __DATA_CONST.__objc_superrefs: 0x190
+  __DATA_CONST.__objc_superrefs: 0x188
   __DATA_CONST.__objc_arraydata: 0xf8
-  __DATA_CONST.__got: 0x918
-  __AUTH_CONST.__const: 0x1c18
-  __AUTH_CONST.__cfstring: 0x9780
+  __DATA_CONST.__got: 0x938
+  __AUTH_CONST.__const: 0x1d68
+  __AUTH_CONST.__cfstring: 0x97c0
   __AUTH_CONST.__objc_const: 0x7c10
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0x18
-  __AUTH_CONST.__auth_got: 0xaf0
+  __AUTH_CONST.__auth_got: 0xb80
   __AUTH.__objc_data: 0xee0
-  __AUTH.__data: 0xe8
+  __AUTH.__data: 0x178
   __DATA.__objc_ivar: 0x364
-  __DATA.__data: 0xb28
-  __DATA.__bss: 0x650
+  __DATA.__data: 0xb68
+  __DATA.__bss: 0xb80
   __DATA_DIRTY.__objc_data: 0x13d8
   __DATA_DIRTY.__data: 0xe8
   __DATA_DIRTY.__bss: 0x380

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 2814
-  Symbols:   6051
-  CStrings:  1648
+  Functions: 2887
+  Symbols:   6092
+  CStrings:  1654
 
Symbols:
+ +[CalPersonaUtils _isPersonalPersonaAvailable]
+ +[CalPersonaUtils _personaUtilErrorForUserManagementError:]
+ +[CalPersonaUtils _personaUtilErrorWithCode:underlyingError:]
+ +[CalPersonaUtils performBlockAsPersonaWithIdentifier:block:error:]
+ +[CalUMCalendarDataContainerInfo containerInfoWithAccount:error:]
+ +[CalUMCalendarDataContainerInfo containerInfoWithPersonaID:error:]
+ -[CalMockCalendarDataContainerProvider containerForAccountIdentifier:error:]
+ -[CalMockCalendarDataContainerProvider containerInfoForAccount:error:]
+ -[CalMockCalendarDataContainerProvider containerInfoForAccountIdentifier:error:]
+ -[CalMockCalendarDataContainerProvider containerInfoForPersonaIdentifier:error:]
+ -[CalMockCalendarDataContainerProvider personaForAccountIdentifier:error:]
+ -[CalUMCalendarDataContainerProvider containerForAccountIdentifier:error:]
+ -[CalUMCalendarDataContainerProvider containerInfoForAccount:error:]
+ -[CalUMCalendarDataContainerProvider containerInfoForAccountIdentifier:error:]
+ -[CalUMCalendarDataContainerProvider containerInfoForPersonaIdentifier:error:]
+ _CalPersonaUtilsErrorDomain
+ _NSPOSIXErrorDomain
+ _NSUnderlyingErrorKey
+ ___67+[CalUMCalendarDataContainerInfo containerInfoWithPersonaID:error:]_block_invoke
+ ___swift_memcpy17_8
+ ___swift_memcpy8_8
+ _associated conformance 18CalendarFoundation19CachedDateFormatterV11FormatStyleOSHAASQ
+ _associated conformance 18CalendarFoundation19CachedDateFormatterV3Key33_9D03EE37A6E1641E4F2D3701453009D0LLVSHAASQ
+ _associated conformance So19NSFormattingContextVSHSCSQ
+ _associated conformance So20NSDateFormatterStyleVSHSCSQ
+ _get_enum_tag_for_layout_string 18CalendarFoundation19CachedDateFormatterV11FormatStyleO
+ _objc_msgSend$_isPersonalPersonaAvailable
+ _objc_msgSend$_personaUtilErrorForUserManagementError:
+ _objc_msgSend$_personaUtilErrorWithCode:underlyingError:
+ _objc_msgSend$containerForAccountIdentifier:error:
+ _objc_msgSend$containerInfoForAccountIdentifier:error:
+ _objc_msgSend$containerInfoWithAccount:error:
+ _objc_msgSend$containerInfoWithPersonaID:error:
+ _objc_msgSend$isPersonalPersona
+ _objc_msgSend$listAllPersonaAttributesWithError:
+ _objc_msgSend$performBlockAsPersonaWithIdentifier:block:error:
+ _objc_msgSend$personaForAccountIdentifier:error:
+ _swift_cvw_enumFn_getEnumTag
+ _swift_cvw_initStructMetadataWithLayoutString
+ _swift_cvw_initWithTake
+ _swift_getEnumTagSinglePayloadGeneric
+ _swift_getSingletonMetadata
+ _swift_storeEnumTagSinglePayloadGeneric
+ _symbolic $sSY
+ _symbolic SS
+ _symbolic Si
+ _symbolic So15NSDateFormatterC
+ _symbolic Su
+ _symbolic _____ 10Foundation8CalendarV
+ _symbolic _____ 18CalendarFoundation19CachedDateFormatterV
+ _symbolic _____ 18CalendarFoundation19CachedDateFormatterV11FormatStyleO
+ _symbolic _____ 18CalendarFoundation19CachedDateFormatterV3Key33_9D03EE37A6E1641E4F2D3701453009D0LLV
+ _symbolic _____ So19NSFormattingContextV
+ _symbolic _____ So20NSDateFormatterStyleV
+ _symbolic _____4date_AA4timet So20NSDateFormatterStyleV
+ _symbolic _____Sg 10Foundation6LocaleV
+ _symbolic _____ySDy_____So15NSDateFormatterCG_____G s13ManagedBufferCsRi__rlE 18CalendarFoundation19CachedDateFormatterV3Key33_9D03EE37A6E1641E4F2D3701453009D0LLV So16os_unfair_lock_sV
+ _symbolic _____y_____So15NSDateFormatterCG s18_DictionaryStorageC 18CalendarFoundation19CachedDateFormatterV3Key33_9D03EE37A6E1641E4F2D3701453009D0LLV
+ _type_layout_string 18CalendarFoundation19CachedDateFormatterV
+ _type_layout_string 18CalendarFoundation19CachedDateFormatterV11FormatStyleO
- +[CalPersonaUtils performBlockAsPersonaWithIdentifier:block:]
- -[CalMockCalendarDataContainerProvider containerForAccountIdentifier:]
- -[CalMockCalendarDataContainerProvider containerInfoForAccount:]
- -[CalMockCalendarDataContainerProvider containerInfoForAccountIdentifier:]
- -[CalMockCalendarDataContainerProvider containerInfoForPersonaIdentifier:]
- -[CalMockCalendarDataContainerProvider personaForAccountIdentifier:]
- -[CalUMCalendarDataContainerInfo initWithAccount:]
- -[CalUMCalendarDataContainerInfo initWithPersonaID:]
- -[CalUMCalendarDataContainerProvider containerForAccountIdentifier:]
- -[CalUMCalendarDataContainerProvider containerInfoForAccount:]
- -[CalUMCalendarDataContainerProvider containerInfoForAccountIdentifier:]
- -[CalUMCalendarDataContainerProvider containerInfoForPersonaIdentifier:]
- ___52-[CalUMCalendarDataContainerInfo initWithPersonaID:]_block_invoke
- _objc_msgSend$containerForAccountIdentifier:
- _objc_msgSend$containerInfoForAccountIdentifier:
- _objc_msgSend$initWithAccount:
- _objc_msgSend$initWithPersonaID:
- _objc_msgSend$performBlockAsPersonaWithIdentifier:block:
- _objc_msgSend$personaForAccountIdentifier:
CStrings:
+ "CalPersonaUtilsErrorDomain"
+ "Error listing all persona attributes: %@"
+ "Personal persona is available. Assuming the requested persona was actually deleted."
+ "Personal persona is not available."
+ "Unexpected error from UserManagement: %@"
+ "value.stringValue"
```
