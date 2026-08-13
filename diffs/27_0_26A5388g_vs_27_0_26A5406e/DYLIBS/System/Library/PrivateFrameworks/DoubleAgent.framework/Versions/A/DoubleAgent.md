## DoubleAgent

> `/System/Library/PrivateFrameworks/DoubleAgent.framework/Versions/A/DoubleAgent`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__DATA.__data`

```diff

-46.0.0.0.0
-  __TEXT.__text: 0x3ec0
+46.0.1.0.0
+  __TEXT.__text: 0x3f94
   __TEXT.__objc_methlist: 0x3f4
   __TEXT.__const: 0x98
   __TEXT.__cstring: 0x30e
-  __TEXT.__oslogstring: 0x47e
+  __TEXT.__oslogstring: 0x4fc
   __TEXT.__unwind_info: 0x120
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 104
-  Symbols:   200
-  CStrings:  46
+  Functions: 106
+  Symbols:   201
+  CStrings:  47
 
Symbols:
+ _OUTLINED_FUNCTION_9
Functions:
~ -[AppleDoubleParser createAttrHeaderIfNeeded:] : 684 -> 804
+ _OUTLINED_FUNCTION_9
~ -[AppleDoubleParser createAttrHeaderIfNeeded:].cold.1 : 96 -> 84
+ -[AppleDoubleParser createAttrHeaderIfNeeded:].cold.4
CStrings:
+ "%s: resource fork offset (0x%x) is invalid when there are no other extended attributes; rejecting malformed AppleDouble file."
```
