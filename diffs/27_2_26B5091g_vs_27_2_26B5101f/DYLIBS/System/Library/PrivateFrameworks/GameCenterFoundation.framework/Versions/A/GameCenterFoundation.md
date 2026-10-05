## GameCenterFoundation

> `/System/Library/PrivateFrameworks/GameCenterFoundation.framework/Versions/A/GameCenterFoundation`

```diff

-821.1.11.0.0
-  __TEXT.__text: 0x1795bc
-  __TEXT.__objc_methlist: 0x125b4
-  __TEXT.__cstring: 0x196f0
+821.1.16.0.0
+  __TEXT.__text: 0x179a54
+  __TEXT.__objc_methlist: 0x125dc
+  __TEXT.__cstring: 0x19790
   __TEXT.__const: 0x65f8
-  __TEXT.__gcc_except_tab: 0x131c
-  __TEXT.__oslogstring: 0xdc7b
+  __TEXT.__gcc_except_tab: 0x1334
+  __TEXT.__oslogstring: 0xdd8b
   __TEXT.__ustring: 0x18
   __TEXT.__dlopen_cstrs: 0x58
   __TEXT.__swift5_typeref: 0x2056

   __TEXT.__swift_as_ret: 0x1dc
   __TEXT.__swift_as_cont: 0x3f4
   __TEXT.__swift5_mpenum: 0x48
-  __TEXT.__unwind_info: 0x81e8
-  __TEXT.__eh_frame: 0x59c0
+  __TEXT.__unwind_info: 0x8228
+  __TEXT.__eh_frame: 0x5a38
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x100
   __DATA_CONST.__objc_protolist: 0x230
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x84c8
+  __DATA_CONST.__objc_selrefs: 0x84e0
   __DATA_CONST.__objc_protorefs: 0x128
   __DATA_CONST.__objc_superrefs: 0x510
   __DATA_CONST.__objc_arraydata: 0x2a8
-  __DATA_CONST.__got: 0x1070
+  __DATA_CONST.__got: 0x1068
   __AUTH_CONST.__const: 0xaa78
-  __AUTH_CONST.__cfstring: 0x11840
-  __AUTH_CONST.__objc_const: 0x24bd8
+  __AUTH_CONST.__cfstring: 0x11880
+  __AUTH_CONST.__objc_const: 0x24c08
   __AUTH_CONST.__objc_arrayobj: 0x150
   __AUTH_CONST.__objc_intobj: 0x2a0
   __AUTH_CONST.__objc_dictobj: 0x190
   __AUTH_CONST.__auth_got: 0x1340
   __AUTH.__objc_data: 0x2be0
   __AUTH.__data: 0x1088
-  __DATA.__objc_ivar: 0xfdc
+  __DATA.__objc_ivar: 0xfe0
   __DATA.__data: 0x3a28
   __DATA.__bss: 0x81e0
   __DATA.__common: 0x20

   - /usr/lib/swift/libswift_StringProcessing.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 11431
-  Symbols:   15322
-  CStrings:  4215
+  Functions: 11441
+  Symbols:   15329
+  CStrings:  4220
 
Symbols:
+ -[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]
+ -[GKMatch pendingPlayerIdentityResolutionGroup]
+ -[GKMatch setPendingPlayerIdentityResolutionGroup:]
+ GCC_except_table177
+ GCC_except_table189
+ GCC_except_table191
+ GCC_except_table192
+ GCC_except_table201
+ GCC_except_table203
+ GCC_except_table216
+ OBJC_IVAR_$_GKMatch._pendingPlayerIdentityResolutionGroup
+ __58-[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]_block_invoke
+ ___58-[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]_block_invoke
- GCC_except_table181
- GCC_except_table187
- GCC_except_table188
- GCC_except_table193
- GCC_except_table199
- GCC_except_table212
CStrings:
+ "%@ (completion != ((void*)0))\n[%s (%s:%d)]"
+ "-[GKMatch handleUnresolvedConnectedPlayersWithCompletion:]"
+ "com.apple.gamecenter.match.pendingplayeridentityresolution"
+ "handleUnresolvedConnectedPlayersWithCompletion: timed out after %.1fs waiting for player identity resolution, proceeding with a possibly-incomplete roster"
+ "handleUnresolvedConnectedPlayersWithCompletion: waiting up to %.1fs for any in-flight player identity resolution"
```
