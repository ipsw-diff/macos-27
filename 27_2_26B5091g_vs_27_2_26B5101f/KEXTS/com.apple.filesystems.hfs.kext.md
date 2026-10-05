## com.apple.filesystems.hfs.kext

> `com.apple.filesystems.hfs.kext`

```diff

-753.40.3.0.0
+753.40.4.0.0
   __TEXT.__const: 0x1ab0
-  __TEXT.__cstring: 0xabdc
-  __TEXT_EXEC.__text: 0x4e9dc
+  __TEXT.__cstring: 0xac58
+  __TEXT_EXEC.__text: 0x4eb28
   __TEXT_EXEC.__auth_stubs: 0x1850
   __DATA.__data: 0x4d0
   __DATA.__common: 0x10

   __DATA_CONST.__auth_ptr: 0x8
   Functions: 510
   Symbols:   1569
-  CStrings:  870
+  CStrings:  872
 
Symbols:
+ hfs_mountfs.kalloc_type_view_1283
+ hfs_mountfs.kalloc_type_view_1894
+ hfs_unmount.kalloc_type_view_2111
- hfs_mountfs.kalloc_type_view_1272
- hfs_mountfs.kalloc_type_view_1883
- hfs_unmount.kalloc_type_view_2100
Functions:
~ _DeleteRecord : 276 -> 296
~ _hfs_swap_BTNode : 5348 -> 5600
~ _hfs_vnop_ioctl : 9776 -> 9800
~ _hfs_mount : 3600 -> 3616
~ _RotateLeft : 792 -> 800
~ _VerifyHeader : 216 -> 228
CStrings:
+ "\"hfs_UNswap_BTNode: initial record at bad offset (0x%04X)\\n\" @%s:%d"
+ "hfs_swap_BTNode: initial record at bad offset (0x%04X)\n"
```
