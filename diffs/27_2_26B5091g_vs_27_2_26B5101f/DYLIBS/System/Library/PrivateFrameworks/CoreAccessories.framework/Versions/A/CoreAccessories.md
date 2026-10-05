## CoreAccessories

> `/System/Library/PrivateFrameworks/CoreAccessories.framework/Versions/A/CoreAccessories`

```diff

-1219.40.7.0.0
-  __TEXT.__text: 0x28a90
-  __TEXT.__objc_methlist: 0x19bc
+1219.40.10.0.0
+  __TEXT.__text: 0x28b28
+  __TEXT.__objc_methlist: 0x19d4
   __TEXT.__const: 0x168
-  __TEXT.__cstring: 0x3d30
+  __TEXT.__cstring: 0x3d79
   __TEXT.__oslogstring: 0x4021
   __TEXT.__gcc_except_tab: 0x82c
   __TEXT.__ustring: 0xa

   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x17a0
+  __DATA_CONST.__const: 0x17c0
   __DATA_CONST.__objc_classlist: 0x50
   __DATA_CONST.__objc_protolist: 0x68
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xf58
+  __DATA_CONST.__objc_selrefs: 0xf68
   __DATA_CONST.__objc_protorefs: 0x50
   __DATA_CONST.__objc_superrefs: 0x48
   __DATA_CONST.__objc_arraydata: 0xd8
   __DATA_CONST.__got: 0x138
   __AUTH_CONST.__const: 0x1510
-  __AUTH_CONST.__cfstring: 0x3b20
-  __AUTH_CONST.__objc_const: 0x2368
+  __AUTH_CONST.__cfstring: 0x3b60
+  __AUTH_CONST.__objc_const: 0x2398
   __AUTH_CONST.__objc_arrayobj: 0x30
   __AUTH_CONST.__objc_intobj: 0x30
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0xdc
+  __DATA.__objc_ivar: 0xe0
   __DATA.__data: 0x760
   __DATA.__bss: 0x128
   __DATA_DIRTY.__objc_data: 0x320

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 848
-  Symbols:   2383
-  CStrings:  865
+  Functions: 850
+  Symbols:   2389
+  CStrings:  867
 
Symbols:
+ -[_ACCExternalAccessoryInfo ppidVersionUID]
+ -[_ACCExternalAccessoryInfo setPpidVersionUID:]
+ GCC_except_table40
+ GCC_except_table46
+ OBJC_IVAR_$__ACCExternalAccessoryInfo._ppidVersionUID
+ _kACCExternalAccessoryPPIDVersionUIDKey
+ _kACCInfo_PPIDVersionUID
+ _kCFACCExternalAccessoryPPIDVersionUIDKey
+ _kCFACCInfo_PPIDVersionUID
+ _objc_msgSend$ppidVersionUID
+ _objc_msgSend$setPpidVersionUID:
- GCC_except_table108
- GCC_except_table38
- GCC_except_table44
- GCC_except_table57
- GCC_except_table64
Functions:
~ -[_ACCExternalAccessoryInfo initWithAccessoryInfoDictionary:] : 660 -> 700
~ -[_ACCExternalAccessoryInfo description] : 344 -> 376
~ -[_ACCExternalAccessoryInfo updateAccessoryInfo:] : 752 -> 800
+ -[_ACCExternalAccessoryInfo productID]
+ -[_ACCExternalAccessoryInfo setDestinationSharingOptions:]
~ -[_ACCExternalAccessoryInfo .cxx_destruct] : 200 -> 212
CStrings:
+ "<_ACCExternalAccessoryInfo>[%@ name='%@' manu='%@' model='%@' serial='%@' fw(active)='%@', fw(pending)='%@', hw='%@' ppid='%@' ppidVersionUID='%@']"
+ "ACCExternalAccessoryPPIDVersionUIDKey"
+ "PPIDVersionUID"
- "<_ACCExternalAccessoryInfo>[%@ name='%@' manu='%@' model='%@' serial='%@' fw(active)='%@', fw(pending)='%@', hw='%@' ppid='%@']"
```
