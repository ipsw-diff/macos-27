## t603xdcp_restore.im4p

> `Firmware/dcp/t603xdcp_restore.im4p`

### Sections with Same Size but Changed Content

- `__TEXT.__chain_starts`
- `__DATA._rtk_patchbay`
- `__DATA._rtk_power`
- `__DATA.__mod_init_func`
- `__DATA._rtk_data_uuid`
- `__DATA._rtk_mtab`

```diff

-  __TEXT.__text: 0x2e8f40
-  __TEXT.__const: 0x3ac52c
+  __TEXT.__text: 0x2e98e0
+  __TEXT.__const: 0x3ac56c
   __TEXT.__chain_starts: 0x30
-  __TEXT.__cstring: 0x38a25
+  __TEXT.__cstring: 0x38b6b
   __TEXT.__lcxx_override: 0x24
   __TEXT.__init_offsets: 0x0
-  __DATA.__const: 0x38040
-  __DATA.__data: 0x11f560
+  __DATA.__const: 0x381d0
+  __DATA.__data: 0x11f558
   __DATA._rtk_patchbay: 0x75a
   __DATA._rtk_tunables: 0x5b0
   __DATA._rtk_boot: 0x9000

   __DATA._rtk_init_stack: 0xa000
   __DATA._rtk_irq_stack: 0x1000
   __DATA._rtk_exc_stack: 0x1000
-  __DATA._afk_sys_drv: 0xea0
+  __DATA._afk_sys_drv: 0xec0
   __DATA.__mod_init_func: 0x88
-  __DATA._afk_sys_objt: 0xbe0
+  __DATA._afk_sys_objt: 0xbf0
   __DATA._rtk_heap: 0x30000
   __DATA._rtk_threads: 0x0
-  __DATA.__zerofill: 0x30970
+  __DATA.__zerofill: 0x309c0
   __DATA.__afk_obj_num: 0x210
   __DATA._rtk_data_uuid: 0x40
   __DATA._rtk_mtab: 0x580
   __DATA.__constructor: 0x8
   __DATA.__gxf_data: 0x10
-  __OS_LOG.__string: 0x23fec
-  Functions: 7234
+  __OS_LOG.__string: 0x240fa
+  Functions: 7242
   Symbols:   0
-  CStrings:  8881
+  CStrings:  8895
 
CStrings:
+ " [AppleDCPDPTXController.cpp::%d] DCPAV[%d] %s::%s X3442 VGHL boost WA %s"
+ " [DCPDPDevice.cpp::%d] DCPAV[%d] %s::%s failed to create serializer for Link Training"
+ " [DCPDPVirtualDevice.cpp::%d] DCPAV[%d] %s::%s Writing intial DPCD %d bytes\n"
+ "%s: remote pipe never reached link check (status %u after %u ms); disabling sync pipe mode\n"
+ "%s: waiting for remote pipe link check, timeout %u ms\n"
+ "ASSERT!%s:%d Invalid Unit number"
+ "DCPDPVirtualService"
+ "Parser e: failed to set PTUC TLS RR LUT dbv_nits=%d, attempt %u/%u\n"
+ "Writing intial DPCD %d bytes\n"
+ "X3442 VGHL boost WA %s"
+ "[AFK]%s: service=0x%llx retrieving DPTX FIFO stats"
+ "[AFK]%s: service=0x%llx retrieving health stats"
+ "[AFK]setHeadless = %u, force = %u"
+ "display wall"
+ "dual pipe"
+ "failed to create serializer for Link Training"
+ "handleDPTXFIFOCmd"
+ "handleHealthMonitorCmd"
- "Disabling sync pipe mode. Other pipe failed link\n"
- "Parser e: failed to set PTUC TLS RR LUT brightness %d\n"
- "[AFK]DCPExpertEPClient::handleCommand: service=0x%llx retrieving health stats"
- "[AFK]setHeadless = %u"
```
