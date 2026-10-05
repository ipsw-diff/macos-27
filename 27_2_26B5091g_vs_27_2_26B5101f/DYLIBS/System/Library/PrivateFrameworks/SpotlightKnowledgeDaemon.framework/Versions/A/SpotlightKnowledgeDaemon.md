## SpotlightKnowledgeDaemon

> `/System/Library/PrivateFrameworks/SpotlightKnowledgeDaemon.framework/Versions/A/SpotlightKnowledgeDaemon`

```diff

-2465.1.3.0.0
-  __TEXT.__text: 0x4b5af0
-  __TEXT.__objc_methlist: 0x9628
-  __TEXT.__const: 0x17aa8
+2465.1.7.0.0
+  __TEXT.__text: 0x4b592c
+  __TEXT.__objc_methlist: 0x9638
+  __TEXT.__const: 0x17ab8
   __TEXT.__oslogstring: 0x12b8e
-  __TEXT.__cstring: 0x16443
-  __TEXT.__gcc_except_tab: 0x5d88
+  __TEXT.__cstring: 0x16413
+  __TEXT.__gcc_except_tab: 0x5d80
   __TEXT.__dlopen_cstrs: 0x5e
   __TEXT.__swift5_typeref: 0xee46
   __TEXT.__constg_swiftt: 0x9188

   __TEXT.__swift5_assocty: 0x13e0
   __TEXT.__swift5_proto: 0x10c4
   __TEXT.__swift5_types: 0x8f4
-  __TEXT.__swift5_capture: 0x3900
+  __TEXT.__swift5_capture: 0x38f0
   __TEXT.__swift_as_entry: 0x498
   __TEXT.__swift_as_ret: 0x4e0
   __TEXT.__swift_as_cont: 0x584
   __TEXT.__swift5_protos: 0x284
   __TEXT.__swift5_mpenum: 0x94
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xfff0
-  __TEXT.__eh_frame: 0x155f0
+  __TEXT.__unwind_info: 0x10020
+  __TEXT.__eh_frame: 0x156b0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_protolist: 0x1f0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x5e68
+  __DATA_CONST.__objc_selrefs: 0x5e70
   __DATA_CONST.__objc_protorefs: 0xc0
   __DATA_CONST.__objc_superrefs: 0x4d0
-  __DATA_CONST.__objc_arraydata: 0xa50
+  __DATA_CONST.__objc_arraydata: 0xa40
   __DATA_CONST.__got: 0x2340
-  __AUTH_CONST.__const: 0x1c8a0
-  __AUTH_CONST.__cfstring: 0x9500
-  __AUTH_CONST.__objc_const: 0x184d0
+  __AUTH_CONST.__const: 0x1c878
+  __AUTH_CONST.__cfstring: 0x94c0
+  __AUTH_CONST.__objc_const: 0x184f0
   __AUTH_CONST.__weak_auth_got: 0x18
   __AUTH_CONST.__objc_intobj: 0xb28
   __AUTH_CONST.__objc_arrayobj: 0x630
   __AUTH_CONST.__objc_dictobj: 0x320
   __AUTH_CONST.__objc_doubleobj: 0x20
-  __AUTH_CONST.__auth_got: 0x35f0
+  __AUTH_CONST.__auth_got: 0x35f8
   __AUTH.__objc_data: 0x15f8
   __AUTH.__data: 0x2478
-  __DATA.__objc_ivar: 0xb8c
+  __DATA.__objc_ivar: 0xb90
   __DATA.__data: 0x3560
   __DATA.__bss: 0xeb00
   __DATA.__common: 0x58
   __DATA_DIRTY.__objc_data: 0x3fa0
-  __DATA_DIRTY.__data: 0xd118
+  __DATA_DIRTY.__data: 0xd108
   __DATA_DIRTY.__bss: 0x9a00
   __DATA_DIRTY.__common: 0x408
   - /System/Library/Frameworks/Contacts.framework/Versions/A/Contacts

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 17007
-  Symbols:   14428
-  CStrings:  3782
+  Functions: 17000
+  Symbols:   14432
+  CStrings:  3780
 
Symbols:
+ -[SKDLocationProcessor isRecentRecord:]
+ -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:enablePIR:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:enablePIR:entityCategories:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector enumerateDetectedLocationsInString:locale:enablePIR:entityBlock:rangeBlock:errorBlock:]
+ -[SKGDataDetector locationFromAddress:locale:enablePIR:errorBlock:]
+ GCC_except_table59
+ OBJC_IVAR_$_SKGDataDetector._defaults
+ __swift_closure_destructor.26Tm
+ _objc_msgSend$enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:enablePIR:entityBlock:rangeBlock:errorBlock:
+ _objc_msgSend$enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:enablePIR:entityCategories:entityBlock:rangeBlock:errorBlock:
+ _objc_msgSend$enumerateDetectedLocationsInString:locale:enablePIR:entityBlock:rangeBlock:errorBlock:
+ _objc_msgSend$isOfflineLocationsEnabled
+ _objc_msgSend$isOnlineLocationsEnabled
+ _objc_msgSend$isRecentRecord:
+ _objc_msgSend$locationFromAddress:locale:enablePIR:errorBlock:
- -[SKDLocationProcessor shouldLookupOnlineLocationsForRecord:]
- -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityBlock:rangeBlock:errorBlock:]
- -[SKGDataDetector enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityCategories:entityBlock:rangeBlock:errorBlock:]
- -[SKGDataDetector enumerateDetectedLocationsInString:locale:entityBlock:rangeBlock:errorBlock:]
- GCC_except_table58
- GCC_except_table62
- __swift_closure_destructor.30Tm
- _objc_msgSend$enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityBlock:rangeBlock:errorBlock:
- _objc_msgSend$enumerateDetectedDataInString:locale:referenceDate:referenceTimezone:entityCategories:entityBlock:rangeBlock:errorBlock:
- _objc_msgSend$enumerateDetectedLocationsInString:locale:entityBlock:rangeBlock:errorBlock:
- _objc_msgSend$shouldLookupOnlineLocationsForRecord:
CStrings:
- "enableOfflineLocations"
- "enableOnlineLocations"
```
