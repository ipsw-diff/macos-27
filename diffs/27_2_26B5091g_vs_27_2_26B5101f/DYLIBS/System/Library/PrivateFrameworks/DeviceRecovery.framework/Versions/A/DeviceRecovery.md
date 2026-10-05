## DeviceRecovery

> `/System/Library/PrivateFrameworks/DeviceRecovery.framework/Versions/A/DeviceRecovery`

```diff

-150.40.7.0.0
-  __TEXT.__text: 0x10afc
-  __TEXT.__objc_methlist: 0x720
+150.40.9.0.0
+  __TEXT.__text: 0x11284
+  __TEXT.__objc_methlist: 0x778
   __TEXT.__const: 0xe2
   __TEXT.__gcc_except_tab: 0x1c0
-  __TEXT.__cstring: 0x27e9
-  __TEXT.__oslogstring: 0x1145
+  __TEXT.__cstring: 0x28f9
+  __TEXT.__oslogstring: 0x11e7
   __TEXT.__constg_swiftt: 0x78
   __TEXT.__swift5_typeref: 0x38
   __TEXT.__swift5_reflstr: 0x20
   __TEXT.__swift5_fieldmd: 0x34
   __TEXT.__swift5_types: 0x4
-  __TEXT.__unwind_info: 0x6d0
+  __TEXT.__unwind_info: 0x6f8
   __TEXT.__eh_frame: 0xd8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x330
+  __DATA_CONST.__const: 0x338
   __DATA_CONST.__objc_classlist: 0x20
   __DATA_CONST.__objc_protolist: 0x20
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x508
+  __DATA_CONST.__objc_selrefs: 0x530
   __DATA_CONST.__objc_protorefs: 0x18
   __DATA_CONST.__objc_superrefs: 0x18
   __DATA_CONST.__got: 0xd8
   __AUTH_CONST.__const: 0x400
-  __AUTH_CONST.__cfstring: 0xea0
-  __AUTH_CONST.__objc_const: 0x858
+  __AUTH_CONST.__cfstring: 0xee0
+  __AUTH_CONST.__objc_const: 0x898
   __AUTH_CONST.__objc_intobj: 0x48
   __AUTH_CONST.__auth_got: 0x308
-  __DATA.__objc_ivar: 0x54
+  __DATA.__objc_ivar: 0x58
   __DATA.__data: 0x28
   __DATA.__bss: 0x30
   __DATA_DIRTY.__objc_data: 0x1f0

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 538
-  Symbols:   655
-  CStrings:  308
+  Functions: 551
+  Symbols:   668
+  CStrings:  317
 
Symbols:
+ -[DeviceRecoveryController addEraseAndUpdateRestrictionForClient:completion:]
+ -[DeviceRecoveryController eraseAndUpdateRestricted]
+ -[DeviceRecoveryController removeEraseAndUpdateRestrictionForClient:completion:]
+ -[DeviceRecoveryController setEraseAndUpdateRestricted:]
+ -[DeviceRecoveryController setEraseAndUpdateRestriction:forClient:completion:]
+ OBJC_IVAR_$_DeviceRecoveryController._eraseAndUpdateRestricted
+ _DRServiceAttributeEraseAndUpdateRestricted
+ __78-[DeviceRecoveryController setEraseAndUpdateRestriction:forClient:completion:]_block_invoke
+ ___78-[DeviceRecoveryController setEraseAndUpdateRestriction:forClient:completion:]_block_invoke
+ _objc_msgSend$addEraseAndUpdateRestrictionForClient:completion:
+ _objc_msgSend$removeEraseAndUpdateRestrictionForClient:completion:
+ _objc_msgSend$setEraseAndUpdateRestricted:
+ _objc_msgSend$setEraseAndUpdateRestriction:forClient:completion:
CStrings:
+ "%{public}s: Could not update EACS / Software Update restriction: %{public}@"
+ "%{public}s: Framework: %{public}s EACS / Software Update restriction for '%{public}@'"
+ "-[DeviceRecoveryController setEraseAndUpdateRestriction:forClient:completion:]"
+ "-[DeviceRecoveryController setEraseAndUpdateRestriction:forClient:completion:]_block_invoke"
+ "EraseAndUpdateRestricted"
+ "adding"
+ "clientIdentifier.length > 0"
+ "no client identifier provided"
+ "removing"
```
