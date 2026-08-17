## SystemStatus

> `/System/Library/PrivateFrameworks/SystemStatus.framework/Versions/A/SystemStatus`

```diff

-286.100.0.0.0
-  __TEXT.__text: 0x40134
+286.200.1.0.0
+  __TEXT.__text: 0x401d0
   __TEXT.__objc_methlist: 0x5358
   __TEXT.__const: 0x108
-  __TEXT.__cstring: 0x2fcc
+  __TEXT.__cstring: 0x2fff
   __TEXT.__gcc_except_tab: 0x3d4
   __TEXT.__oslogstring: 0x1444
   __TEXT.__unwind_info: 0x1760

   __DATA_CONST.__objc_catlist: 0x8
   __DATA_CONST.__objc_protolist: 0x110
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x15a0
+  __DATA_CONST.__objc_selrefs: 0x15a8
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x260
   __DATA_CONST.__objc_arraydata: 0x18
   __DATA_CONST.__got: 0x3e8
   __AUTH_CONST.__const: 0x1780
-  __AUTH_CONST.__cfstring: 0x2dc0
+  __AUTH_CONST.__cfstring: 0x2de0
   __AUTH_CONST.__objc_const: 0x9c20
   __AUTH_CONST.__objc_arrayobj: 0x18
   __AUTH_CONST.__auth_got: 0x0

   - /System/Library/PrivateFrameworks/BaseBoard.framework/Versions/A/BaseBoard
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 2062
-  Symbols:   4249
-  CStrings:  542
+  Functions: 2063
+  Symbols:   4251
+  CStrings:  543
 
Symbols:
+ _BSDispatchBlockCreateWithQualityOfService
+ _objc_msgSend$_setQueue:
+ _st_dispatch_sync_user_initiated
- _BSDispatchQueueCreateSerial
Functions:
~ -[STLocalDynamicActivityAttributionManager init] : 196 -> 200
~ -[STStatusDomainXPCServerHandle initWithXPCConnectionProvider:serverLaunchObservable:] : 420 -> 424
~ -[STStatusDomainXPCServerHandle _internalQueue_setupXPCConnectionIfNecessary] : 536 -> 576
~ -[STDynamicActivityAttributionPublisher init] : 148 -> 152
+ _st_dispatch_sync_user_initiated
~ -[STStatusDomainPublisherXPCServerHandle initWithXPCConnectionProvider:serverLaunchObservable:] : 616 -> 620
CStrings:
+ "com.apple.systemstatus.observer.xpcconnectionqueue"
```
