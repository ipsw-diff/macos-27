## ToneKit

> `/System/Library/PrivateFrameworks/ToneKit.framework/Versions/A/ToneKit`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__DATA.__objc_ivar`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-672.0.0.0.0
-  __TEXT.__text: 0x11e1c
+675.0.0.0.0
+  __TEXT.__text: 0x12074
   __TEXT.__objc_methlist: 0x1b8c
-  __TEXT.__cstring: 0x964
+  __TEXT.__cstring: 0xa40
   __TEXT.__const: 0x5c
+  __TEXT.__oslogstring: 0x22f
   __TEXT.__gcc_except_tab: 0x10c
-  __TEXT.__oslogstring: 0x1ec
   __TEXT.__ustring: 0x9c
   __TEXT.__unwind_info: 0x540
   __TEXT.__objc_stubs: 0x0

   - /System/Library/PrivateFrameworks/ToneLibrary.framework/Versions/A/ToneLibrary
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 484
+  Functions: 486
   Symbols:   1396
-  CStrings:  119
+  CStrings:  122
 
Symbols:
+ -[TKTonePickerItem _setWantsIndentedLayout:]
+ -[TKTonePickerItem wantsIndentedLayout]
+ OBJC_IVAR_$_TKTonePickerItem._wantsIndentedLayout
- -[TKPickerRowItem _setWantsIndentedLayout:]
- -[TKPickerRowItem wantsIndentedLayout]
- OBJC_IVAR_$_TKPickerRowItem._wantsIndentedLayout
CStrings:
+ "-[TKTonePickerItem wantsIndentedLayout]"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.Fcscqj/Sources/ToneLibrary/Kit/Tones/TKTonePickerController.m"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.Fcscqj/Sources/ToneLibrary/Kit/Tones/TKTonePickerItem.m"
+ "A nested row must be able to show a leading checkmark: %{public}@."
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.v0Pp3k/Sources/ToneLibrary/Kit/Tones/TKTonePickerController.m"
```
