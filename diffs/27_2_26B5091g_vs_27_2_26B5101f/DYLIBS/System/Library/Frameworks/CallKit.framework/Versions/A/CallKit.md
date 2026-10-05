## CallKit

> `/System/Library/Frameworks/CallKit.framework/Versions/A/CallKit`

```diff

-1406.200.62.0.0
-  __TEXT.__text: 0x69f14
+1406.200.84.0.0
+  __TEXT.__text: 0x6ac44
   __TEXT.__objc_methlist: 0x91fc
   __TEXT.__const: 0x130
-  __TEXT.__cstring: 0x635c
-  __TEXT.__oslogstring: 0x3aba
-  __TEXT.__gcc_except_tab: 0x690
-  __TEXT.__unwind_info: 0x2890
+  __TEXT.__cstring: 0x6499
+  __TEXT.__oslogstring: 0x3c35
+  __TEXT.__gcc_except_tab: 0x71c
+  __TEXT.__unwind_info: 0x28c8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_superrefs: 0x388
   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__got: 0x4b8
-  __AUTH_CONST.__const: 0x1200
-  __AUTH_CONST.__cfstring: 0x4220
+  __AUTH_CONST.__const: 0x1230
+  __AUTH_CONST.__cfstring: 0x42c0
   __AUTH_CONST.__objc_const: 0xeed8
   __AUTH_CONST.__objc_intobj: 0x60
   __AUTH_CONST.__objc_arrayobj: 0x48

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 3253
-  Symbols:   6873
-  CStrings:  990
+  Functions: 3265
+  Symbols:   6880
+  CStrings:  1007
 
Symbols:
+ GCC_except_table106
+ _OUTLINED_FUNCTION_5
+ __94-[CXCallDirectoryStore migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:error:]_block_invoke
+ ___94-[CXCallDirectoryStore migrateAllDataFromExtensionWithBundleID:toExtensionWithBundleID:error:]_block_invoke
+ ___block_descriptor_72_e8_32s40s48s56r64r_e20_B24?0?<B?^>8^16l
+ ___copy_helper_block_e8_32s40s48s56r64r
+ ___destroy_helper_block_e8_32s40s48s56r64r
CStrings:
+ "DELETE FROM Extension WHERE bundle_id = ?"
+ "Deleting old extension"
+ "Executing migration"
+ "Failed to delete old extension: %@"
+ "Failed to update blocking entries: %@"
+ "Failed to update identification entries: %@"
+ "Failed to update new extension state: %@"
+ "Getting new extension's unique id"
+ "Getting old extension's data"
+ "New extension's unique id not found"
+ "Old extension not found"
+ "SELECT id FROM Extension WHERE bundle_id = ?"
+ "SELECT id, priority, state FROM Extension WHERE bundle_id = ?"
+ "UPDATE Extension SET priority = ?, state = ? WHERE bundle_id = ?"
+ "UPDATE PhoneNumberBlockingEntry SET extension_id = ? WHERE extension_id = ?"
+ "UPDATE PhoneNumberIdentificationEntry SET extension_id = ? WHERE extension_id = ?"
+ "Updating blocking entries"
+ "Updating identification entries"
+ "Updating new extension state"
- "Executing application migration"
- "UPDATE Extension SET bundle_id = ? WHERE bundle_id = ?"
```
