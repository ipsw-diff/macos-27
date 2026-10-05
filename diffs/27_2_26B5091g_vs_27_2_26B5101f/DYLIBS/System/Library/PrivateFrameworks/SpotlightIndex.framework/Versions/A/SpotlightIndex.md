## SpotlightIndex

> `/System/Library/PrivateFrameworks/SpotlightIndex.framework/Versions/A/SpotlightIndex`

```diff

-2465.1.3.0.0
-  __TEXT.__text: 0x4de5fc
+2465.1.7.0.0
+  __TEXT.__text: 0x4df044
   __TEXT.__objc_methlist: 0x404
   __TEXT.__const: 0xacf2
-  __TEXT.__cstring: 0x3ec81
+  __TEXT.__cstring: 0x3ef80
   __TEXT.__gcc_except_tab: 0x27c
-  __TEXT.__oslogstring: 0x1f141
+  __TEXT.__oslogstring: 0x1f454
   __TEXT.__ustring: 0x400
   __TEXT.__dof_mds: 0x29b
-  __TEXT.__unwind_info: 0x7698
+  __TEXT.__unwind_info: 0x76a0
   __TEXT.__eh_frame: 0x220
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_arraydata: 0x78
   __DATA_CONST.__got: 0x608
   __AUTH_CONST.__const: 0xd3d8
-  __AUTH_CONST.__cfstring: 0x12d00
+  __AUTH_CONST.__cfstring: 0x12e00
   __AUTH_CONST.__objc_const: 0x5e8
   __AUTH_CONST.__weak_auth_got: 0x28
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x2018
+  __AUTH_CONST.__auth_got: 0x2020
   __AUTH.__objc_data: 0xa0
   __AUTH.__data: 0x18d8
   __DATA.__objc_ivar: 0x60
   __DATA.__data: 0xe08
-  __DATA.__bss: 0x5758
+  __DATA.__bss: 0x5778
   __DATA_DIRTY.__objc_data: 0xa0
   __DATA_DIRTY.__data: 0x5a4
   __DATA_DIRTY.__bss: 0x1a0e8

   - /usr/lib/libicucore.A.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 8108
-  Symbols:   10925
-  CStrings:  9600
+  Functions: 8110
+  Symbols:   10930
+  CStrings:  9621
 
Symbols:
+ CIIndexSetCreateWithRange.sLoggedCount
+ GCC_except_table7084
+ _CIIndexSetSetIndexRangeWithCache.sLoggedCount
+ __CIIndexSetAddRange_Bitmap_Src_SparseDst
+ __MDPlistContainerAllocFailure
+ _repair_journal_flush
- GCC_except_table7082
CStrings:
+ "%s:%d: Parsed v2 journal entry with faulty isFromMail size %ld"
+ "%s:%d: Repair journal: could not write the %u item batch for bundle %@; those items will not be repaired"
+ "%s:%d: Repair journal: the plist builder refused a value, most likely nesting past its depth bound; dropping the whole %u item batch for bundle %@"
+ "%s:%d: Rogue accumulated position %d at docID %d off %llu. Canceling"
+ "%s:%d: Rogue nil position at docID %d off %llu size %llu(%llu), Rogue nil count %d. Canceling _CIPositionIterate_Compressed"
+ "%s:%d: Rogue position %d at docID %d off %llu size %llu(%llu), Rogue count %d. Canceling"
+ "%s:%d: Rogue position %d at docID %d off %llu. Canceling _CIPositionIterate_Compressed"
+ "%s:%d: [CIIndexSet] CIIndexSetCreateWithRange: unrepresentable range [%u, %u], clamping"
+ "%s:%d: [CIIndexSet] _CIIndexSetSetIndexRangeWithCache: refusing unrepresentable range [%u, %u]"
+ "%s:%d: unrepresentable payloadCount (%u), marking index invalid\n"
+ "2465.1.7"
+ "<si:%s> - Playback skipping sn: %lld mrsn: %lld csn: %lld mailMigration: %d"
+ "CIIndexSetCreateWithRange"
+ "Parsed v2 journal entry with faulty isFromMail size %ld"
+ "Repair journal: could not write the %u item batch for bundle %@; those items will not be repaired"
+ "Repair journal: the plist builder refused a value, most likely nesting past its depth bound; dropping the whole %u item batch for bundle %@"
+ "Rogue accumulated position %d at docID %d off %llu. Canceling"
+ "Rogue nil position at docID %d off %llu size %llu(%llu), Rogue nil count %d. Canceling _CIPositionIterate_Compressed"
+ "Rogue position %d at docID %d off %llu size %llu(%llu), Rogue count %d. Canceling"
+ "Rogue position %d at docID %d off %llu. Canceling _CIPositionIterate_Compressed"
+ "[CIIndexSet] CIIndexSetCreateWithRange: unrepresentable range [%u, %u], clamping"
+ "[CIIndexSet] _CIIndexSetSetIndexRangeWithCache: refusing unrepresentable range [%u, %u]"
+ "_CIIndexSetSetIndexRangeWithCache"
+ "repair_journal_batch_abandoned"
+ "repair_journal_flush"
+ "unrepresentable payloadCount (%u), marking index invalid\n"
- "%s:%d: Rogue nil position at docID %d off %llu size %llu(%llu), Rogue nil count %d. Canceling"
- "%s:%d: Rogue nil position at docID %d off %llu size %llu(%llu), Rogue nil count %d. Canceling _CIPositionIterate_NewCompressed"
- "2465.1.3"
- "Rogue nil position at docID %d off %llu size %llu(%llu), Rogue nil count %d. Canceling"
- "Rogue nil position at docID %d off %llu size %llu(%llu), Rogue nil count %d. Canceling _CIPositionIterate_NewCompressed"
```
