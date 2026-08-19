## uarpd

> `/usr/libexec/uarpd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-1587.1.2.0.0
-  __TEXT.__text: 0xad4e4
-  __TEXT.__auth_stubs: 0x920
+1587.1.3.0.0
+  __TEXT.__text: 0xad1d0
+  __TEXT.__auth_stubs: 0x940
   __TEXT.__objc_stubs: 0xa7e0
   __TEXT.__objc_methlist: 0x8820
-  __TEXT.__objc_methname: 0xf573
+  __TEXT.__objc_methname: 0xf586
   __TEXT.__objc_classname: 0x1d20
-  __TEXT.__cstring: 0xb1d1
-  __TEXT.__objc_methtype: 0x2acd
+  __TEXT.__cstring: 0xb1df
+  __TEXT.__objc_methtype: 0x2ad1
   __TEXT.__const: 0x148
-  __TEXT.__gcc_except_tab: 0x1c4
+  __TEXT.__gcc_except_tab: 0x1ec
   __TEXT.__oslogstring: 0x96a9
-  __TEXT.__unwind_info: 0x2418
+  __TEXT.__unwind_info: 0x2438
   __DATA_CONST.__const: 0x1180
   __DATA_CONST.__cfstring: 0x55e0
   __DATA_CONST.__objc_classlist: 0x610

   __DATA_CONST.__objc_arraydata: 0x70
   __DATA_CONST.__objc_arrayobj: 0x30
   __DATA_CONST.__objc_dictobj: 0x28
-  __DATA_CONST.__auth_got: 0x4a0
+  __DATA_CONST.__auth_got: 0x4b0
   __DATA_CONST.__got: 0x660
-  __DATA.__objc_const: 0x108f0
+  __DATA.__objc_const: 0x10910
   __DATA.__objc_selrefs: 0x3228
-  __DATA.__objc_ivar: 0xb70
+  __DATA.__objc_ivar: 0xb74
   __DATA.__objc_data: 0x3ca0
   __DATA.__data: 0x548
   __DATA.__bss: 0x1178

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libpcap.A.dylib
-  Functions: 4007
-  Symbols:   217
-  CStrings:  5020
+  Functions: 4009
+  Symbols:   219
+  CStrings:  5022
 
Symbols:
+ _dispatch_get_specific
+ _dispatch_queue_set_specific
CStrings:
+ "-[UARPEndpointLayer3 directConfiguration]_block_invoke"
+ "_kInternalQueueKey"
+ "r^v"
+ "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xb31"
- "-[UARPEndpointLayer3 directConfiguration]"
- "\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xf0\xa31"
```
