## com.apple.security.sandbox

> `com.apple.security.sandbox`

```diff

-3051.40.70.0.0
-  __TEXT.__os_log: 0x278d
-  __TEXT.__const: 0x20a17
+3051.40.80.0.0
+  __TEXT.__os_log: 0x278f
+  __TEXT.__const: 0x20917
   __TEXT.__cstring: 0x7dc7
-  __TEXT_EXEC.__text: 0x5281c
+  __TEXT_EXEC.__text: 0x52858
   __TEXT_EXEC.__auth_stubs: 0x15d0
   __DATA.__data: 0x3b0
   __DATA.__bss: 0x7f19c
Symbols:
+ mount_info_alloc.kalloc_type_view_1685
+ mount_info_release.kalloc_type_view_1720
+ pending_approval_entry_create.kalloc_type_view_1685
+ pending_approval_entry_create.kalloc_type_view_1692
+ pending_approval_entry_release.kalloc_type_view_1664
+ pending_swap_begin.kalloc_type_view_2146
+ pending_swap_release.kalloc_type_view_2101
+ re_cache_init.kalloc_type_view_37
+ sandcastle_init.kalloc_type_view_3436
+ sandcastle_pattern_buffer_free_callback.kalloc_type_view_326
+ sandcastle_pattern_buffer_new.kalloc_type_view_309
+ storage_class_for_vnode.kalloc_type_view_3602
+ storage_class_for_vnode.kalloc_type_view_3613
+ variables_populate.kalloc_type_view_219
- mount_info_alloc.kalloc_type_view_1684
- mount_info_release.kalloc_type_view_1719
- pending_approval_entry_create.kalloc_type_view_1677
- pending_approval_entry_create.kalloc_type_view_1684
- pending_approval_entry_release.kalloc_type_view_1656
- pending_swap_begin.kalloc_type_view_2145
- pending_swap_release.kalloc_type_view_2100
- re_cache_init.kalloc_type_view_92
- sandcastle_init.kalloc_type_view_3427
- sandcastle_pattern_buffer_free_callback.kalloc_type_view_318
- sandcastle_pattern_buffer_new.kalloc_type_view_301
- storage_class_for_vnode.kalloc_type_view_3597
- storage_class_for_vnode.kalloc_type_view_3608
- variables_populate.kalloc_type_view_248
Functions:
~ _hook_mount_check_umount : 452 -> 468
~ _hook_mount_notify_mount : 1916 -> 1948
~ _eval : 13932 -> 13936
~ _sb_event : 2864 -> 2860
~ _authorize_extension_issue : 696 -> 680
~ _re_cache_init : 496 -> 504
~ _collection_init : 1004 -> 1024
CStrings:
+ "%s set rootless flags on %s with flags=0x%lx"
- "%s set rootless flags on %s with flags=%lu"
```
