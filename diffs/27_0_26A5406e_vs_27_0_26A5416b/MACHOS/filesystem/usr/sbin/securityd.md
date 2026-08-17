## securityd

> `/usr/sbin/securityd`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__dof_security_`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`
- `__DATA.__thread_vars`

```diff

-62460.1.1.0.0
-  __TEXT.__text: 0x6e5ec
-  __TEXT.__auth_stubs: 0x19d0
+62460.1.2.0.0
+  __TEXT.__text: 0x6e370
+  __TEXT.__auth_stubs: 0x19b0
   __TEXT.__objc_stubs: 0x1c0
   __TEXT.__init_offsets: 0x18
   __TEXT.__objc_methlist: 0x20
   __TEXT.__const: 0x25dd
-  __TEXT.__gcc_except_tab: 0x8478
-  __TEXT.__cstring: 0x1c31
-  __TEXT.__oslogstring: 0x4af4
+  __TEXT.__gcc_except_tab: 0x8458
+  __TEXT.__cstring: 0x1be5
+  __TEXT.__oslogstring: 0x4a86
   __TEXT.__objc_classname: 0x18
   __TEXT.__objc_methtype: 0x65
   __TEXT.__objc_methname: 0x126
   __TEXT.__dof_security_: 0x466
-  __TEXT.__unwind_info: 0x24c0
+  __TEXT.__unwind_info: 0x24b8
   __DATA_CONST.__const: 0x75d0
-  __DATA_CONST.__cfstring: 0x6e0
+  __DATA_CONST.__cfstring: 0x6c0
   __DATA_CONST.__objc_protolist: 0x8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x8
-  __DATA_CONST.__auth_got: 0xd00
+  __DATA_CONST.__auth_got: 0xcf0
   __DATA_CONST.__got: 0x218
   __DATA_CONST.__auth_ptr: 0x20
   __DATA.__objc_const: 0x10

   - /usr/lib/libxar.1.dylib
   - /usr/lib/libz.1.dylib
   Functions: 1776
-  Symbols:   489
-  CStrings:  843
+  Symbols:   487
+  CStrings:  838
 
Symbols:
- _SecCoreAnalyticsSendLegacyKeychainEntitlementRejectedEvent
- __ZNSt3__112basic_stringIcNS_11char_traitsIcEENS_9allocatorIcEEED1Ev
Functions:
~ sub_10003e574 : 1936 -> 1760
~ sub_10003fc64 -> sub_10003fbb4 : 668 -> 208
CStrings:
- "Extraction requested for %s"
- "Rejecting client(%s) due to lack of entitlement: '%@'"
- "checking entitlements of %s"
- "com.apple.private.securityd.keychain-master-key-extraction"
- "extractMasterKey"
```
