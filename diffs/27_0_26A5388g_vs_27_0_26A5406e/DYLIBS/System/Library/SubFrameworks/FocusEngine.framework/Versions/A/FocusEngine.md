## FocusEngine

> `/System/Library/SubFrameworks/FocusEngine.framework/Versions/A/FocusEngine`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH.__objc_data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-9127.0.79.0.0
-  __TEXT.__text: 0x34260
-  __TEXT.__objc_methlist: 0x3958
+9127.0.84.1.402
+  __TEXT.__text: 0x34268
+  __TEXT.__objc_methlist: 0x3960
   __TEXT.__const: 0x118
   __TEXT.__cstring: 0x3caa
   __TEXT.__gcc_except_tab: 0x4d0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xb0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1c98
+  __DATA_CONST.__objc_selrefs: 0x1ca8
   __DATA_CONST.__objc_protorefs: 0x20
   __DATA_CONST.__objc_superrefs: 0x1a8
   __DATA_CONST.__objc_arraydata: 0x18

   - /usr/lib/swift/libswiftObjectiveC.dylib
   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
-  Functions: 1259
-  Symbols:   3150
+  Functions: 1260
+  Symbols:   3152
   CStrings:  449
 
Symbols:
+ -[UIFocusMovementAction abortForUsageViolation:]
+ _objc_msgSend$abort
Functions:
+ -[UIFocusMovementAction abortForUsageViolation:]
```
