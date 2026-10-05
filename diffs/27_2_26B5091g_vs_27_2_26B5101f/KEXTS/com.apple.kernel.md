## com.apple.kernel

> `com.apple.kernel`

```diff

-13432.40.162.0.0
-  __TEXT.__const: 0x38b20
+13432.40.177.0.3
+  __TEXT.__const: 0x38b30
   __TEXT.__copyio_vectors: 0x340
-  __TEXT.__cstring: 0xb6fa2
-  __TEXT.__os_log: 0x42b0a
+  __TEXT.__cstring: 0xb6feb
+  __TEXT.__os_log: 0x42c0b
   __TEXT.__eh_frame: 0x7e0
   __DATA_CONST.__hib_const: 0x310
-  __DATA_CONST.__sdt_cstring: 0x73b0
-  __DATA_CONST.__sdt: 0xee20
+  __DATA_CONST.__sdt_cstring: 0x73e4
+  __DATA_CONST.__sdt: 0xee38
   __DATA_CONST.__kalloc_type: 0x183c0
-  __DATA_CONST.__const: 0x139bb8
-  __DATA_CONST.__assert: 0x15b8
+  __DATA_CONST.__const: 0x139b90
+  __DATA_CONST.__assert: 0x15cc
   __DATA_CONST.__kalloc_var: 0x87f0
   __DATA_CONST.__exclaves_bt: 0xc0
   __DATA_CONST.__kern_brk_desc: 0x78

   __DATA_CONST.__auth_ptr: 0x10
   __DATA_SPTM.__const: 0x74000
   __TEXT_EXEC.__exc: 0x1000
-  __TEXT_EXEC.__text: 0x9f6850
+  __TEXT_EXEC.__text: 0x9f78d0
   __TEXT_EXEC.__hib_text: 0x19c8
   __TEXT_EXEC.__commpage_text: 0x334
   __TEXT_BOOT_EXEC.__bootcode: 0x6a2c

   __DATA.__lock_grp: 0x17b40
   __DATA.__percpu: 0x8730
   __DATA.__common: 0xa3c60
-  __DATA.__bss: 0xabf10
+  __DATA.__bss: 0xabf20
   __HIBDATA.__data: 0x31
   __HIBDATA.__bss: 0x670
   __HIBDATA.__common: 0x108
   __BOOTDATA.__data: 0x18000
   __BOOTDATA.__static_if: 0xed0
   __BOOTDATA.__init: 0x22378
-  __BOOTDATA.__init_entry_set: 0x157c8
+  __BOOTDATA.__init_entry_set: 0x157b0
   __BOOTDATA.__static_ifinit: 0x18
   __PRELINK_TEXT.__text: 0x0
   __PRELINK_INFO.__info: 0x0

   __PLK_DATA_CONST.__data: 0x0
   __PLK_LLVM_COV.__llvm_covmap: 0x0
   __PLK_LINKEDIT.__data: 0x0
-  __LINKINFO.__symbolsets: 0x50830
+  __LINKINFO.__symbolsets: 0x5089d
   __CTF.__ctf: 0x0
-  Functions: 23915
-  Symbols:   6949
-  CStrings:  26960
+  Functions: 23923
+  Symbols:   6951
+  CStrings:  26970
 
Symbols:
+ _exclaves_indicator_system_state_change
+ _vfs_context_allows_unmunged_atime
CStrings:
+ "11111122"
+ "22111220222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222220222121222221111111222211111112222211111122222111111222221111112222211222211122211112111111111111"
+ "FilterDropBadDirection"
+ "SK[%u]: %-30s dropped packet injected on ring %u whose wrap flag does not match the ring direction: pkt_pflags 0x%llx\n"
+ "SK[%u]: %-30s filter packet is not mbuf-wrapped: pkt_pflags 0x%llx\n"
+ "SK[%u]: %-30s filter packet is not packet-wrapped: pkt_pflags 0x%llx\n"
+ "bad__direction"
+ "com.apple.security.cs.debugger"
+ "not__mbuf__wrapped"
+ "not__pkt__wrapped"
+ "nx_netif_filter_pkt_to_mbuf"
+ "nx_netif_filter_pkt_to_pkt"
+ "ret == TB_ERROR_SUCCESS"
- "221112202222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222222121222221111111222211111112222211111122222111111222221111112222211222211122211112111111111111"
- "protect_privileged_from_untrusted"
- "vm_protect_privileged_from_untrusted"
```
