## SafariShared

> `/System/iOSSupport/System/Library/PrivateFrameworks/SafariShared.framework/Versions/A/SafariShared`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-625.2.5.11.1
-  __TEXT.__text: 0x1be1e4
+625.2.7.1.0
+  __TEXT.__text: 0x1be254
   __TEXT.__objc_methlist: 0x12fd4
-  __TEXT.__const: 0x9fa70
-  __TEXT.__gcc_except_tab: 0x1cdb4
+  __TEXT.__const: 0x9fc60
+  __TEXT.__gcc_except_tab: 0x1cdf8
   __TEXT.__cstring: 0x1abb7
   __TEXT.__ustring: 0xcb78
   __TEXT.__oslogstring: 0x10f92

   __DATA_CONST.__objc_protolist: 0x2a8
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x8
-  __DATA_CONST.__objc_selrefs: 0xa4c8
+  __DATA_CONST.__objc_selrefs: 0xa4c0
   __DATA_CONST.__objc_protorefs: 0xb0
   __DATA_CONST.__objc_superrefs: 0x858
   __DATA_CONST.__objc_arraydata: 0x9f0
-  __DATA_CONST.__got: 0x1958
+  __DATA_CONST.__got: 0x1950
   __AUTH_CONST.__const: 0x3f90
   __AUTH_CONST.__cfstring: 0x16f80
   __AUTH_CONST.__objc_const: 0x225d0

   __AUTH.__objc_data: 0x2f10
   __AUTH.__data: 0x350
   __DATA.__objc_ivar: 0x15d0
-  __DATA.__data: 0x3db0
+  __DATA.__data: 0x3da0
   __DATA.__bss: 0x3300
   __DATA.__common: 0x30
   __DATA_DIRTY.__objc_data: 0x3e08

   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 10559
-  Symbols:   20597
+  Symbols:   20596
   CStrings:  4849
 
Symbols:
+ -[WBSTabOrderManager _nextNonClosedTabAdjacentToIndex:inAscendingOrder:foundIndex:]
+ _objc_msgSend$_nextNonClosedTabAdjacentToIndex:inAscendingOrder:foundIndex:
- -[WBSTabOrderManager _nextNonClosedTabAdjacentToIndex:inAscendingOrder:]
- _objc_msgSend$_nextNonClosedTabAdjacentToIndex:inAscendingOrder:
- _objc_msgSend$tabAtIndex:inAllTabs:
Functions:
~ ___105-[WBSContentBlockerStatisticsSQLiteStore blockedThirdPartiesAfter:before:onFirstParty:completionHandler:]_block_invoke : 888 -> 924
~ -[WBSContentBlockerStatisticsSQLiteStore _idForThirdPartyWithHighLevelDomain:] : 424 -> 476
~ -[WBSContentBlockerStatisticsSQLiteStore _idForFirstPartyWithHighLevelDomain:] : 424 -> 476
~ -[WBSTrialSearchParameters updateUsingPreferenceKeys:] : 408 -> 468
~ -[WBSTabOrderManager tabToSelectBeforeClosingTabs:] : 684 -> 700
~ -[WBSTabOrderManager _nextNonClosedTabAdjacentToIndex:inAscendingOrder:] -> -[WBSTabOrderManager _nextNonClosedTabAdjacentToIndex:inAscendingOrder:foundIndex:] : 244 -> 236
~ sub_2c396949c -> sub_2c3b1e56c : 2292 -> 2228
~ sub_2c3969d90 -> sub_2c3b1ee20 : 620 -> 572
~ sub_2c396a480 -> sub_2c3b1f4e0 : 72 -> 88
CStrings:
+ "22625.2.7.1"
- "22625.2.5.11.1"
```
