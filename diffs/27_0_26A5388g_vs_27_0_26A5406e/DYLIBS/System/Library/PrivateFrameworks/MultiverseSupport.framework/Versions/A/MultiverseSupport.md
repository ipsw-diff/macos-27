## MultiverseSupport

> `/System/Library/PrivateFrameworks/MultiverseSupport.framework/Versions/A/MultiverseSupport`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH.__objc_data`
- `__DATA.__data`

```diff

-117.0.0.0.0
-  __TEXT.__text: 0x76fc
+117.1.2.0.0
+  __TEXT.__text: 0x7714
   __TEXT.__objc_methlist: 0x4ac
   __TEXT.__const: 0x108
   __TEXT.__gcc_except_tab: 0x10
-  __TEXT.__cstring: 0xbdd
+  __TEXT.__cstring: 0xc1a
   __TEXT.__oslogstring: 0xc02
   __TEXT.__unwind_info: 0x1b0
   __TEXT.__objc_stubs: 0x0

   - /usr/lib/libobjc.A.dylib
   Functions: 226
   Symbols:   456
-  CStrings:  203
+  CStrings:  204
 
Functions:
~ _usb_change_callback : 2816 -> 2840
CStrings:
+ "anri"
+ "strncmp(device->ifname, \"en\", strlen(\"en\")) == 0 || strncmp(device->ifname, \"anpi\", strlen(\"anpi\")) == 0 || strncmp(device->ifname, \"anri\", strlen(\"anri\")) == 0"
- "strncmp(device->ifname, \"en\", strlen(\"en\")) == 0 || strncmp(device->ifname, \"anpi\", strlen(\"anpi\")) == 0"
```
