## CalendarDaemon

> `/System/Library/PrivateFrameworks/CalendarDaemon.framework/Versions/A/CalendarDaemon`

```diff

-1246.1.4.0.0
-  __TEXT.__text: 0x79a4c
+1246.2.1.0.0
+  __TEXT.__text: 0x79b38
   __TEXT.__objc_methlist: 0x67c4
   __TEXT.__cstring: 0x7447
   __TEXT.__const: 0x190
-  __TEXT.__oslogstring: 0x8bab
+  __TEXT.__oslogstring: 0x8be3
   __TEXT.__gcc_except_tab: 0x1c0c
   __TEXT.__dlopen_cstrs: 0xc0
   __TEXT.__ustring: 0x4

   __AUTH_CONST.__objc_intobj: 0x498
   __AUTH_CONST.__objc_dictobj: 0x28
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x1b00
+  __AUTH_CONST.__auth_got: 0x1b10
   __AUTH.__objc_data: 0x8c0
   __AUTH.__data: 0xa50
   __DATA.__objc_ivar: 0x838

   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
   Functions: 2378
-  Symbols:   6880
-  CStrings:  1796
+  Symbols:   6882
+  CStrings:  1797
 
Symbols:
+ +[CADOperationGroupUtil _defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:updateDefaultIfNeeded:defaultExists:]
+ _CalDatabaseClearDefaultCalendarIfDefaultIsInAuxDatabaseWithID
+ _CalDatabaseCopyOrCreateDefaultCalendarForNewEventsUpdateIfNeeded
+ _objc_msgSend$_defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:updateDefaultIfNeeded:defaultExists:
+ _objc_msgSend$containerInfoForAccountIdentifier:error:
- +[CADOperationGroupUtil defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:defaultExists:]
- _objc_msgSend$containerInfoForAccountIdentifier:
- _objc_msgSend$defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:defaultExists:
Functions:
~ __142-[CADXPCImplementation(CADDatabaseOperationGroup) CADDatabaseCommitDeletes:updatesAndInserts:options:andFetchChangesSinceTimestamp:withReply:]_block_invoke.50 : 1448 -> 1476
~ ___116-[CADXPCImplementation(CADDatabaseOperationGroup) findDatabaseForObject:withUpdates:personas:accounts:nextTempDBID:]_block_invoke : 896 -> 1036
~ +[CADOperationGroupUtil defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:defaultExists:] -> +[CADOperationGroupUtil _defaultCalendarIDForNewEventsInStoreWithID:connection:inDatabase:updateDefaultIfNeeded:defaultExists:] : 980 -> 992
~ __98+[CADOperationGroupUtil defaultCalendarForNewEventsInDelegateSource:withConnection:limitedAccess:]_block_invoke.1 : 332 -> 376
~ ___98+[CADOperationGroupUtil defaultCalendarForNewEventsInDelegateSource:withConnection:limitedAccess:]_block_invoke_2 : 92 -> 96
~ __98+[CADOperationGroupUtil defaultCalendarForNewEventsInDelegateSource:withConnection:limitedAccess:]_block_invoke.2 : 348 -> 352
~ __98+[CADOperationGroupUtil defaultCalendarForNewEventsInDelegateSource:withConnection:limitedAccess:]_block_invoke.5 : 80 -> 84
CStrings:
+ "Failed to get container info for account %{public}@: %@"
```
