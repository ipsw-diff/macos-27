## CascadeSets

> `/System/Library/PrivateFrameworks/CascadeSets.framework/Versions/A/CascadeSets`

```diff

-250.0.0.1.0
-  __TEXT.__text: 0xb22bc
-  __TEXT.__objc_methlist: 0x669c
+250.0.0.3.0
+  __TEXT.__text: 0xb234c
+  __TEXT.__objc_methlist: 0x66a4
   __TEXT.__const: 0x3cc8
   __TEXT.__gcc_except_tab: 0x18d4
   __TEXT.__cstring: 0x8e57
-  __TEXT.__oslogstring: 0x5400
+  __TEXT.__oslogstring: 0x5410
   __TEXT.__dlopen_cstrs: 0x3d8
   __TEXT.__swift5_typeref: 0xe33
   __TEXT.__constg_swiftt: 0x16bc

   __DATA_CONST.__objc_protolist: 0x1c8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3270
+  __DATA_CONST.__objc_selrefs: 0x3278
   __DATA_CONST.__objc_protorefs: 0x98
   __DATA_CONST.__objc_superrefs: 0x360
   __DATA_CONST.__objc_arraydata: 0x168

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 4696
-  Symbols:   6419
+  Functions: 4697
+  Symbols:   6420
   CStrings:  1327
 
Symbols:
+ -[CCItemFieldPredicate copyWithFieldType:value:]
+ _objc_msgSend$copyWithFieldType:value:
- _objc_msgSend$predicateWithFieldType:equalsStringValue:error:
Functions:
+ -[CCItemFieldPredicate copyWithFieldType:value:]
~ ___44-[CCSetChangeXPCNotifier notifyChangeToSet:]_block_invoke : 612 -> 644
~ +[CCCachedDocumentUtilities documentCachePredicateFromAssociatedSetPredicate:documentCacheSet:error:] : 852 -> 840
~ +[CCCachedDocumentUtilities _documentCachePredicateFromAssociatedSetKeyPrefixedIdentifier:documentCacheSet:error:] : 544 -> 560
CStrings:
+ "%@ firing xpc_event for set: %@ to %lu listener(s)"
- "%@ firing xpc_event for set: %@"
```
