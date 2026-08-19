## SystemStatusServer

> `/System/Library/PrivateFrameworks/SystemStatusServer.framework/Versions/A/SystemStatusServer`

```diff

-286.100.0.0.0
-  __TEXT.__text: 0x144f8
-  __TEXT.__objc_methlist: 0xf60
-  __TEXT.__const: 0x98
-  __TEXT.__cstring: 0x88a
-  __TEXT.__gcc_except_tab: 0x1c4
-  __TEXT.__oslogstring: 0x9b2
-  __TEXT.__unwind_info: 0x540
+286.200.1.0.0
+  __TEXT.__text: 0x13074
+  __TEXT.__objc_methlist: 0xdf8
+  __TEXT.__const: 0x88
+  __TEXT.__cstring: 0x793
+  __TEXT.__gcc_except_tab: 0x190
+  __TEXT.__oslogstring: 0x49f
+  __TEXT.__unwind_info: 0x4e8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x160
-  __DATA_CONST.__objc_classlist: 0xd0
+  __DATA_CONST.__objc_classlist: 0xc8
   __DATA_CONST.__objc_protolist: 0x90
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xaf0
-  __DATA_CONST.__objc_superrefs: 0xd0
-  __DATA_CONST.__got: 0x300
-  __AUTH_CONST.__const: 0xb20
-  __AUTH_CONST.__cfstring: 0x460
-  __AUTH_CONST.__objc_const: 0x2768
+  __DATA_CONST.__objc_selrefs: 0x9d0
+  __DATA_CONST.__objc_superrefs: 0xc8
+  __DATA_CONST.__got: 0x2c8
+  __AUTH_CONST.__const: 0xa90
+  __AUTH_CONST.__cfstring: 0x3a0
+  __AUTH_CONST.__objc_const: 0x24a0
   __AUTH_CONST.__auth_got: 0x0
-  __AUTH.__objc_data: 0x50
-  __DATA.__objc_ivar: 0x19c
+  __DATA.__objc_ivar: 0x174
   __DATA.__data: 0x6c0
   __DATA_DIRTY.__objc_data: 0x7d0
-  __DATA_DIRTY.__bss: 0x40
+  __DATA_DIRTY.__bss: 0x20
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation
   - /System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices
   - /System/Library/Frameworks/Foundation.framework/Versions/C/Foundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 416
-  Symbols:   1324
-  CStrings:  101
+  Functions: 380
+  Symbols:   1234
+  CStrings:  75
 
Symbols:
+ _BSDispatchQueueCreateSerialWithQoS
+ _objc_msgSend$_setQueue:
+ _objc_msgSend$remoteObjectProxy
- +[STStatusDomainXPCClientWakeUpAssertion _watchdogQueue]
- -[STStatusDomainXPCClientWakeUpAssertion .cxx_destruct]
- -[STStatusDomainXPCClientWakeUpAssertion _acquireNewHandleMessageAssertion]
- -[STStatusDomainXPCClientWakeUpAssertion _cancelWatchdogTimer]
- -[STStatusDomainXPCClientWakeUpAssertion _invalidateHandleMessageAssertion]
- -[STStatusDomainXPCClientWakeUpAssertion _startNewWatchdogTimer]
- -[STStatusDomainXPCClientWakeUpAssertion _terminateClient]
- -[STStatusDomainXPCClientWakeUpAssertion _watchdogQueue_cancelWatchdogTimer]
- -[STStatusDomainXPCClientWakeUpAssertion acquire]
- -[STStatusDomainXPCClientWakeUpAssertion assertionAcquisitionCount]
- -[STStatusDomainXPCClientWakeUpAssertion clientIsRunningBoardManaged]
- -[STStatusDomainXPCClientWakeUpAssertion clientPID]
- -[STStatusDomainXPCClientWakeUpAssertion dealloc]
- -[STStatusDomainXPCClientWakeUpAssertion handleMessageAssertionAcquisitionTimestamp]
- -[STStatusDomainXPCClientWakeUpAssertion handleMessageAssertion]
- -[STStatusDomainXPCClientWakeUpAssertion initWithClientAuditToken:queue:]
- -[STStatusDomainXPCClientWakeUpAssertion invalidateHandleMessageAssertionTimer]
- -[STStatusDomainXPCClientWakeUpAssertion invalidate]
- -[STStatusDomainXPCClientWakeUpAssertion isInvalidated]
- -[STStatusDomainXPCClientWakeUpAssertion queue]
- -[STStatusDomainXPCClientWakeUpAssertion relinquish]
- -[STStatusDomainXPCClientWakeUpAssertion setAssertionAcquisitionCount:]
- -[STStatusDomainXPCClientWakeUpAssertion setHandleMessageAssertion:]
- -[STStatusDomainXPCClientWakeUpAssertion setHandleMessageAssertionAcquisitionTimestamp:]
- -[STStatusDomainXPCClientWakeUpAssertion setInvalidateHandleMessageAssertionTimer:]
- -[STStatusDomainXPCClientWakeUpAssertion setInvalidated:]
- -[STStatusDomainXPCClientWakeUpAssertion setWatchdogTimer:]
- -[STStatusDomainXPCClientWakeUpAssertion watchdogTimer]
- GCC_except_table12
- GCC_except_table5
- OBJC_IVAR_$_STStatusDomainXPCClientHandle._clientWakeUpAssertion
- OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._assertionAcquisitionCount
- OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._clientIsRunningBoardManaged
- OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._clientPID
- OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._handleMessageAssertion
- OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._handleMessageAssertionAcquisitionTimestamp
- OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._invalidateHandleMessageAssertionTimer
- OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._invalidated
- OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._queue
- OBJC_IVAR_$_STStatusDomainXPCClientWakeUpAssertion._watchdogTimer
- _BSFloatLessThanFloat
- _BSStringFromBOOL
- _OBJC_CLASS_$_RBSAssertion
- _OBJC_CLASS_$_RBSDomainAttribute
- _OBJC_CLASS_$_RBSProcessPredicate
- _OBJC_CLASS_$_RBSTarget
- _OBJC_CLASS_$_RBSTerminateContext
- _OBJC_CLASS_$_RBSTerminateRequest
- _OBJC_CLASS_$_STStatusDomainXPCClientWakeUpAssertion
- _OBJC_METACLASS_$_STStatusDomainXPCClientWakeUpAssertion
- _STSystemStatusLogClientWakeUp
- __64-[STStatusDomainXPCClientWakeUpAssertion _startNewWatchdogTimer]_block_invoke
- __OBJC_$_CLASS_METHODS_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_$_INSTANCE_METHODS_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_$_INSTANCE_VARIABLES_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_$_PROP_LIST_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_CLASS_PROTOCOLS_$_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_CLASS_RO_$_STStatusDomainXPCClientWakeUpAssertion
- __OBJC_METACLASS_RO_$_STStatusDomainXPCClientWakeUpAssertion
- ___52-[STStatusDomainXPCClientWakeUpAssertion relinquish]_block_invoke
- ___56+[STStatusDomainXPCClientWakeUpAssertion _watchdogQueue]_block_invoke
- ___62-[STStatusDomainXPCClientWakeUpAssertion _cancelWatchdogTimer]_block_invoke
- ___64-[STStatusDomainXPCClientWakeUpAssertion _startNewWatchdogTimer]_block_invoke
- ___73-[STStatusDomainXPCClientHandle observeData:forDomain:withChangeContext:]_block_invoke_4
- ___STSystemStatusLogClientWakeUp_block_invoke
- ___block_descriptor_40_e8_32w_e31_v16?0"BSContinuousMachTimer"8l
- __os_log_debug_impl
- _objc_msgSend$_acquireNewHandleMessageAssertion
- _objc_msgSend$_cancelWatchdogTimer
- _objc_msgSend$_invalidateHandleMessageAssertion
- _objc_msgSend$_startNewWatchdogTimer
- _objc_msgSend$_terminateClient
- _objc_msgSend$_watchdogQueue
- _objc_msgSend$_watchdogQueue_cancelWatchdogTimer
- _objc_msgSend$acquire
- _objc_msgSend$acquireWithError:
- _objc_msgSend$attributeWithDomain:name:
- _objc_msgSend$clientPID
- _objc_msgSend$execute:
- _objc_msgSend$initWithClientAuditToken:queue:
- _objc_msgSend$initWithExplanation:
- _objc_msgSend$initWithExplanation:target:attributes:
- _objc_msgSend$initWithPredicate:context:
- _objc_msgSend$isApplication
- _objc_msgSend$localizedDescription
- _objc_msgSend$predicateMatching:
- _objc_msgSend$relinquish
- _objc_msgSend$setExceptionCode:
- _objc_msgSend$setInvalidateHandleMessageAssertionTimer:
- _objc_msgSend$setMaximumTerminationResistance:
- _objc_msgSend$setReportType:
- _objc_msgSend$setWatchdogTimer:
- _objc_msgSend$targetWithPid:
CStrings:
+ "com.apple.systemstatus.publisher.xpcconnectionqueue.client-%d"
- "ClientWakeUp"
- "Observer-HandleMessage"
- "STStatusDomainXPCClientWakeUpAssertion-Watchdog:%d"
- "STStatusDomainXPCClientWakeUpAssertion:%d"
- "SYSTEMSTATUSSERVER CLIENT ERROR: attempted to acquire wake up assertion that was invalidated"
- "SYSTEMSTATUSSERVER CLIENT ERROR: attempted to relinquish wake up assertion that was invalidated"
- "SYSTEMSTATUSSERVER CLIENT ERROR: invalidated wake up assertion that was already invalidated"
- "SYSTEMSTATUSSERVER CLIENT ERROR: wake up assertion deallocated without being invalidated"
- "SystemStatus observer watchdog - unresponsive client: %d"
- "SystemStatus sending update to observer client: %d"
- "cancelling scheduled invalidation of Observer-HandleMessage assertion for client: %d"
- "cancelling watchdog timer for client: %d"
- "com.apple.systemstatus.observer.watchdogqueue"
- "com.apple.systemstatusd"
- "creating new Observer-HandleMessage assertion for client: %d"
- "failed to acquire Observer-HandleMessage assertion for client: %d"
- "initialized wake up assertion for client: %d - RunningBoard managed: %@"
- "invalidating Observer-HandleMessage assertion immediately for client: %d"
- "invalidating wake up assertion for client: %d"
- "performing scheduled invalidation of Observer-HandleMessage assertion for client: %d"
- "reusing Observer-HandleMessage assertion for client: %d"
- "scheduling invalidation of Observer-HandleMessage assertion for client: %d"
- "starting new watchdog timer for client: %d"
- "wake up assertion failed to create process handle for client: %d"
- "wake up assertion failed to create process handle for client: %d - error: %@"
- "watchdog failed to terminate client: %d - error: %@"
- "watchdog terminating client: %d"
```
