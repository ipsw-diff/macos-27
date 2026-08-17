## tccd

> `/System/Library/PrivateFrameworks/TCC.framework/Support/tccd`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA.__objc_ivar`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-913.0.0.0.0
-  __TEXT.__text: 0x8ab58
+913.3.2.0.1
+  __TEXT.__text: 0x8cf40
   __TEXT.__auth_stubs: 0x1600
   __TEXT.__lazy_helpers: 0x54
-  __TEXT.__objc_stubs: 0x99e0
-  __TEXT.__objc_methlist: 0x41dc
-  __TEXT.__cstring: 0x123d3
+  __TEXT.__objc_stubs: 0x9a80
+  __TEXT.__objc_methlist: 0x4214
+  __TEXT.__cstring: 0x125da
   __TEXT.__const: 0x648
-  __TEXT.__gcc_except_tab: 0x33dc
-  __TEXT.__objc_methname: 0xfe21
-  __TEXT.__oslogstring: 0xecc9
+  __TEXT.__gcc_except_tab: 0x34c4
+  __TEXT.__objc_methname: 0xfeca
+  __TEXT.__oslogstring: 0xf026
   __TEXT.__objc_classname: 0x4ae
-  __TEXT.__objc_methtype: 0x14bd
-  __TEXT.__unwind_info: 0x1608
-  __DATA_CONST.__const: 0x26a8
+  __TEXT.__objc_methtype: 0x14e3
+  __TEXT.__unwind_info: 0x1678
+  __DATA_CONST.__const: 0x2738
   __DATA_CONST.__cfstring: 0x8480
   __DATA_CONST.__objc_classlist: 0x188
   __DATA_CONST.__objc_catlist: 0x8

   __DATA_CONST.__auth_got: 0xb10
   __DATA_CONST.__got: 0x4a8
   __DATA_CONST.__auth_ptr: 0x30
-  __DATA.__objc_const: 0x7d78
-  __DATA.__objc_selrefs: 0x2ce8
+  __DATA.__objc_const: 0x7d80
+  __DATA.__objc_selrefs: 0x2d08
   __DATA.__objc_ivar: 0x65c
   __DATA.__objc_data: 0xf50
   __DATA.__lazy_load_got: 0x8
   __DATA.__data: 0x34c
   __DATA.__crash_info: 0x148
-  __DATA.__bss: 0x35c
+  __DATA.__bss: 0x360
   __DATA.__common: 0x30
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/libbsm.0.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
-  Functions: 2569
+  Functions: 2606
   Symbols:   504
-  CStrings:  5157
+  CStrings:  5184
 
CStrings:
+ "%s: failed to clear pending flag for %{public}s:%{public}s"
+ "%s: failed to create records array"
+ "%s: failed to forward disclosure-prompt acknowledgement to system tccd: %{public}s"
+ "%s: failed to select pending enable-notification rows"
+ "%s: merging %zu system tccd records for service=%{public}s client=%{public}s"
+ "%s: no reply from system tccd for disclosure-prompt acknowledgement"
+ "%s: returning %zu pending enable-notification record(s)"
+ "@\"NSObject<OS_dispatch_queue>\"16@0:8"
+ "ManagedSettings: %{public}@ is not eligible for managed_overrides; skipping %{public}@:%{public}@"
+ "ManagedSettings: pruned ineligible managed_overrides rows for %{public}@ (result=%d)"
+ "Override: enable notification failed to post for %{public}@:%{public}@; leaving pending flag set for retry"
+ "Override: failed to acknowledge enable notification for %{public}@:%{public}@; will retry"
+ "Override: failed to fetch pending enable notifications from system tccd"
+ "Override: pruned ineligible managed_overrides rows for %{public}@ (result=%d)"
+ "SELECT DISTINCT service FROM managed_overrides"
+ "SELECT service, client, client_type FROM managed_overrides WHERE (flags & ?)"
+ "TB,N,V_mdm_eligibleForManagedOverrides"
+ "TCCAccessAcknowledgeEnableNotifications"
+ "TCCAccessGetPendingEnableNotifications"
+ "UPDATE managed_overrides SET flags = (flags & ~?) WHERE service = ? AND client = ? AND client_type = ?"
+ "_mdm_eligibleForManagedOverrides"
+ "_pruneIneligibleManagedOverrides"
+ "acknowledgeEnableNotificationForService:client:clientType:"
+ "com.apple.tcc.access-enabled-notification-pending"
+ "handle_TCCAccessAcknowledgeEnableNotifications"
+ "handle_TCCAccessAcknowledgeEnableNotifications_block_invoke"
+ "handle_TCCAccessGetPendingEnableNotifications"
+ "mdm_eligibleForManagedOverrides"
+ "pppc_eligibleForManagedOverrides"
+ "pruneIneligibleManagedOverrides"
+ "records"
+ "setMdm_eligibleForManagedOverrides:"
+ "unknown"
+ "v12@?0B8"
+ "v36@0:8@16@24i32"
- " AND auth_value != ? AND auth_value != ?"
- "%@|%@"
- "%s: merging %zu system tccd records (auth_value != unknown) for service=%{public}s client=%{public}s"
- "@\"NSMutableSet\""
- "T@\"NSMutableSet\",&,N,V_notifiedEnableRecordKeys"
- "_notifiedEnableRecordKeys"
- "notifiedEnableRecordKeys"
- "setNotifiedEnableRecordKeys:"
```
