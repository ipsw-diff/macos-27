## MediaPlaybackCore

> `/System/Library/PrivateFrameworks/MediaPlaybackCore.framework/Versions/A/MediaPlaybackCore`

```diff

-26145.26.31.201.0
-  __TEXT.__text: 0x3ccb74
+26140.26.31.301.0
+  __TEXT.__text: 0x3cd590
   __TEXT.__objc_methlist: 0x164e0
   __TEXT.__dlopen_cstrs: 0xbe
   __TEXT.__const: 0xd880
-  __TEXT.__cstring: 0x22fd0
-  __TEXT.__constg_swiftt: 0x65b8
+  __TEXT.__cstring: 0x230cc
+  __TEXT.__constg_swiftt: 0x65f8
   __TEXT.__swift5_typeref: 0x462a
   __TEXT.__swift5_builtin: 0x578
-  __TEXT.__swift5_reflstr: 0x4932
-  __TEXT.__swift5_fieldmd: 0x4818
+  __TEXT.__swift5_reflstr: 0x4972
+  __TEXT.__swift5_fieldmd: 0x4824
   __TEXT.__swift5_assocty: 0xa20
-  __TEXT.__oslogstring: 0x41c52
+  __TEXT.__oslogstring: 0x41d88
   __TEXT.__swift5_proto: 0x7a8
   __TEXT.__swift5_types: 0x44c
-  __TEXT.__swift5_capture: 0x6564
+  __TEXT.__swift5_capture: 0x6514
   __TEXT.__swift_as_entry: 0x2c0
   __TEXT.__swift_as_ret: 0x320
   __TEXT.__swift_as_cont: 0x8ac
   __TEXT.__swift5_mpenum: 0xb8
   __TEXT.__swift5_protos: 0xc4
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__gcc_except_tab: 0x555c
+  __TEXT.__gcc_except_tab: 0x560c
   __TEXT.__ustring: 0x4d4
   __TEXT.__unwind_info: 0xac30
-  __TEXT.__eh_frame: 0x9dc8
+  __TEXT.__eh_frame: 0x9da0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_superrefs: 0x6b0
   __DATA_CONST.__objc_arraydata: 0x298
   __DATA_CONST.__got: 0x2a68
-  __AUTH_CONST.__const: 0x1e518
-  __AUTH_CONST.__cfstring: 0x1de80
-  __AUTH_CONST.__objc_const: 0x30b20
+  __AUTH_CONST.__const: 0x1e4a0
+  __AUTH_CONST.__cfstring: 0x1dec0
+  __AUTH_CONST.__objc_const: 0x30b40
   __AUTH_CONST.__objc_intobj: 0x888
   __AUTH_CONST.__objc_arrayobj: 0x288
   __AUTH_CONST.__objc_dictobj: 0xc8

   __DATA.__objc_ivar: 0x1a34
   __DATA.__data: 0x56d0
   __DATA.__bss: 0xc018
-  __DATA.__common: 0xe0
+  __DATA.__common: 0xe8
   __DATA_DIRTY.__objc_data: 0x3100
-  __DATA_DIRTY.__data: 0x5b78
+  __DATA_DIRTY.__data: 0x5ba8
   __DATA_DIRTY.__bss: 0x1b30
   __DATA_DIRTY.__common: 0xb0
   - /System/Library/Frameworks/AVFAudio.framework/Versions/A/AVFAudio

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 19118
-  Symbols:   22780
-  CStrings:  7554
+  Functions: 19119
+  Symbols:   22781
+  CStrings:  7559
 
Symbols:
+ __88-[_MPCQueueControllerBehaviorMusic performInsertCommand:targetContentItemID:completion:]_block_invoke
+ ___block_descriptor_117_e8_32s40s48s56s64s72s80s88bs96r_e5_v8?0l
+ ___block_descriptor_117_e8_32s40s48s56s64s72s80s88bs96r_e61_v32?0"MPRemoteCommandStatus"8"NSString"16"NSDictionary"24l
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s88b96r
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96r
+ __swift_closure_destructor.137Tm
+ __swift_closure_destructor.64Tm
- ___88-[_MPCQueueControllerBehaviorMusic performInsertCommand:targetContentItemID:completion:]_block_invoke_2
- ___block_descriptor_117_e8_32s40s48s56s64s72s80s88s96bs_e5_v8?0l
- ___block_descriptor_117_e8_32s40s48s56s64s72s80s88s96bs_e61_v32?0"MPRemoteCommandStatus"8"NSString"16"NSDictionary"24l
- ___copy_helper_block_e8_32s40s48s56s64s72s80s88s96b
- ___destroy_helper_block_e8_32s40s48s56s64s72s80s88s96s
- __swift_closure_destructor.130Tm
CStrings:
+ "Insertion position requires a non-empty afterContentItemID."
+ "NSString *_MPCPlaybackAccountIDForAccountIDs(NSString *__strong, NSString *__strong)"
+ "Playback stopped"
+ "[ALC:%{public}s] - Effective start %{public}f within cold-start margin %{public}f of overlap start %{public}f, cancelling transition"
+ "[AccountManager] Unexpected combo account, recovering with first/last tokens: %{public}@"
+ "[AccountManager] combining an already-combo borrowing account ID: %@"
+ "[AccountManager] combining an already-combo primary account ID: %@"
+ "[BMUS:%{public}@:%{public}@] performInsertCommand: | failed [insertion position %ld requires a non-empty afterContentItemID]"
+ "[PL:%{public}s] TRANSITION: Effective start %{public}f within cold-start margin %{public}f of overlap start %{public}f, cancelling crossfade [%{public}s]"
+ "[PL:%{public}s] TRANSITION: Jump during an ongoing crossfade, cancelling [%{public}s]"
+ "com.apple.WorkflowKit.BackgroundShortcutRunner"
- "Audio session is in invalid activation state "
- "Audio session is not activated"
- "Unexpected combo account: %@"
- "[ALC:%{public}s] - Jump position passes overlap start, cancelling transition"
- "[PL:%{public}s] PLAYER CONTROLLER: Failing user event due to an audio session activation error: %@"
- "[PL:%{public}s] TRANSITION: Jump position passes overlap start, cancelling crossfade [%{public}s]"
```
