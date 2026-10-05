## ConfigurationProfiles

> `/System/Library/PrivateFrameworks/ConfigurationProfiles.framework/Versions/A/ConfigurationProfiles`

```diff

-1847.40.4.0.0
-  __TEXT.__text: 0x65478
+1847.40.6.0.0
+  __TEXT.__text: 0x657dc
   __TEXT.__objc_methlist: 0x14fc
   __TEXT.__const: 0x3f1
   __TEXT.__gcc_except_tab: 0x868
-  __TEXT.__oslogstring: 0x102a3
-  __TEXT.__cstring: 0x17752
+  __TEXT.__oslogstring: 0x103c8
+  __TEXT.__cstring: 0x1787b
   __TEXT.__unwind_info: 0x1db0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __AUTH_CONST.__objc_arrayobj: 0x180
   __AUTH_CONST.__objc_dictobj: 0x140
   __AUTH_CONST.__objc_intobj: 0x60
-  __AUTH_CONST.__auth_got: 0xbd8
+  __AUTH_CONST.__auth_got: 0xbe8
   __AUTH.__objc_data: 0x410
   __DATA.__objc_ivar: 0xd0
   __DATA.__data: 0x63a

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 2059
-  Symbols:   2937
-  CStrings:  2400
+  Symbols:   2939
+  CStrings:  2404
 
Symbols:
+ _class_getName
+ _object_getClassName
Functions:
~ _MergeAllPasscodePolicies : 2016 -> 2188
~ _MergeAndSetPasscodePolicy : 1748 -> 1980
~ ___MergePolicyDictionary_block_invoke : 1176 -> 1640
CStrings:
+ "22:30:36"
+ "MergeAllPasscodePolicies kPasscodeMinutesUntilFailedLoginReset ignored - unexpected class '%s'"
+ "MergeAndSetPasscodePolicy kPasscodeMinutesUntilFailedLoginReset skipped: newPolicyValue class '%s', failedAttempts class '%s'"
+ "MergePolicyDictionary ignoring policy key '%s' - expected %s but got %s"
+ "Sep 27 2026"
+ "nil"
- "20:45:30"
- "Sep 13 2026"
```
