## UnifiedAssetFramework

> `/System/Library/PrivateFrameworks/UnifiedAssetFramework.framework/Versions/A/UnifiedAssetFramework`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__constg_swiftt`
- `__TEXT.__swift5_typeref`
- `__TEXT.__swift5_types`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-3600.74.1.0.0
-  __TEXT.__text: 0x801c8
+3600.77.1.0.0
+  __TEXT.__text: 0x801cc
   __TEXT.__objc_methlist: 0x3670
   __TEXT.__const: 0x198
   __TEXT.__constg_swiftt: 0x48
   __TEXT.__swift5_typeref: 0x67
   __TEXT.__swift5_reflstr: 0x9
   __TEXT.__swift5_fieldmd: 0x1c
-  __TEXT.__cstring: 0xb7e7
+  __TEXT.__cstring: 0xb7de
   __TEXT.__oslogstring: 0xf115
   __TEXT.__swift5_types: 0x4
   __TEXT.__gcc_except_tab: 0xe30
Symbols:
+ -[UAFAssetOriginReport _populateFromMAReport:error:]
+ _objc_msgSend$_populateFromMAReport:error:
- -[UAFAssetOriginReport _populateFromMAReport:error:errorOut:]
- _objc_msgSend$_populateFromMAReport:error:errorOut:
Functions:
~ -[UAFSubscriptionStoreManager _openDatabase:] : 2792 -> 2784
~ -[UAFAssetOriginReport initWithAutoAssetSet:atomicInstance:atomicEntries:error:] : 464 -> 484
~ -[UAFAssetOriginReport _populateFromMAReport:error:errorOut:] -> -[UAFAssetOriginReport _populateFromMAReport:error:] : 1196 -> 1188
CStrings:
+ "-[UAFAssetOriginReport _populateFromMAReport:error:]"
- "-[UAFAssetOriginReport _populateFromMAReport:error:errorOut:]"
```
