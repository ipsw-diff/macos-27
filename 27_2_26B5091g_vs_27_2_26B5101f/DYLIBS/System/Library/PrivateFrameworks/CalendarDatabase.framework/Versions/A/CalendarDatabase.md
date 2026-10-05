## CalendarDatabase

> `/System/Library/PrivateFrameworks/CalendarDatabase.framework/Versions/A/CalendarDatabase`

```diff

-1291.1.3.0.0
-  __TEXT.__text: 0xdca3c
+1291.2.3.0.0
+  __TEXT.__text: 0xdd0ec
   __TEXT.__objc_methlist: 0x1f24
-  __TEXT.__cstring: 0x2052d
+  __TEXT.__cstring: 0x20580
   __TEXT.__const: 0xab4
   __TEXT.__gcc_except_tab: 0x1830
-  __TEXT.__oslogstring: 0xccaf
+  __TEXT.__oslogstring: 0xcf31
   __TEXT.__dlopen_cstrs: 0xc0
   __TEXT.__unwind_info: 0x4060
   __TEXT.__objc_stubs: 0x0

   __DATA_CONST.__objc_selrefs: 0x24e8
   __DATA_CONST.__objc_superrefs: 0xd0
   __DATA_CONST.__objc_arraydata: 0xc8
-  __DATA_CONST.__got: 0x9d0
+  __DATA_CONST.__got: 0x9d8
   __AUTH_CONST.__const: 0x29e0
-  __AUTH_CONST.__cfstring: 0xcc40
+  __AUTH_CONST.__cfstring: 0xcc60
   __AUTH_CONST.__objc_const: 0x37d0
   __AUTH_CONST.__objc_arrayobj: 0x78
   __AUTH_CONST.__objc_intobj: 0x30

   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 4282
-  Symbols:   7677
-  CStrings:  3130
+  Functions: 4284
+  Symbols:   7680
+  CStrings:  3139
 
Symbols:
+ GCC_except_table344
+ GCC_except_table347
+ _CalDatabaseClearDefaultCalendarIfDefaultIsInAuxDatabaseWithID
+ _CalDatabaseCopyOrCreateDefaultCalendarForNewEventsUpdateIfNeeded
+ _CalPersonaUtilsErrorDomain
+ _objc_msgSend$containerForAccountIdentifier:error:
+ _objc_msgSend$containerInfoForAccount:error:
+ _objc_msgSend$containerInfoForAccountIdentifier:error:
+ _objc_msgSend$containerInfoForPersonaIdentifier:error:
- GCC_except_table342
- GCC_except_table345
- _objc_msgSend$containerForAccountIdentifier:
- _objc_msgSend$containerInfoForAccount:
- _objc_msgSend$containerInfoForAccountIdentifier:
- _objc_msgSend$containerInfoForPersonaIdentifier:
CStrings:
+ "Aux database containing the default calendar was deleted"
+ "CalCalendarRef CalDatabaseCopyDefaultOrAnyReadWriteCalendarForNewEvents(CalDatabaseRef, CalStoreRef, BOOL)"
+ "CalCalendarRef CalDatabaseCopyOrCreateDefaultCalendarForNewEventsUpdateIfNeeded(CalDatabaseRef, BOOL)"
+ "Could not get a container info for account ID %{public}@: %@"
+ "Could not get new calendar data container. store uuid = %{public}@: %@"
+ "Could not open %@: %s"
+ "Couldn't get container info for persona %{public}@. Using main database for this persona. error = %@"
+ "Couldn't look up persona %{public}@: %@"
+ "Couldn't look up persona ID %{public}@: %@"
+ "Failed to get URL for data container of account %{public}@: %@"
+ "Failed to get container info for account [%{public}@]: %@"
+ "Failed to get container info for persona %{public}@: %@"
+ "_CalAttachmentFileGetAttachmentContainerURLsForStoreProperties: Failed to get container for account %{public}@: %@"
+ "_CalAttachmentFileGetCalendarDataContainerForAttachmentFile: Failed to get container for account %{public}@: %@"
+ "_CalAttachmentFileMigrateAttachmentsInStoreFromOldPersistentIDToNewPersistentID: Failed to get container for account %{public}@: %@"
+ "commit at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4352"
+ "write at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4329"
- "CalCalendarRef CalDatabaseCopyDefaultOrAnyReadWriteCalendarForNewEvents(CalDatabaseRef, CalStoreRef)"
- "CalCalendarRef CalDatabaseCopyOrCreateDefaultCalendarForNewEvents(CalDatabaseRef)"
- "Could not get new calendar data container. store uuid = %{public}@"
- "Couldn't get container info for persona %{public}@. Using main database for this persona."
- "Couldn't look up persona %{public}@"
- "Couldn't look up persona ID %{public}@"
- "commit at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4338"
- "write at /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.<TMP>/Sources/CalendarDatabase/CalendarDatabase/CalCalendar.m:4315"
```
