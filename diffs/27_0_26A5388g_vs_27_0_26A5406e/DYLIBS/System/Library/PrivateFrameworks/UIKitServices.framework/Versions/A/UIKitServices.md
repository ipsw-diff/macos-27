## UIKitServices

> `/System/Library/PrivateFrameworks/UIKitServices.framework/Versions/A/UIKitServices`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_doubleobj`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-9127.0.79.0.0
-  __TEXT.__text: 0x1ff50
-  __TEXT.__objc_methlist: 0x2f74
-  __TEXT.__const: 0x270
+9127.0.84.1.402
+  __TEXT.__text: 0x1ffa8
+  __TEXT.__objc_methlist: 0x2fe4
+  __TEXT.__const: 0x280
   __TEXT.__dlopen_cstrs: 0x298
   __TEXT.__cstring: 0x4311
   __TEXT.__oslogstring: 0x594
   __TEXT.__gcc_except_tab: 0x458
-  __TEXT.__unwind_info: 0xb58
+  __TEXT.__unwind_info: 0xb60
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_catlist: 0x10
   __DATA_CONST.__objc_protolist: 0xb0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x1758
+  __DATA_CONST.__objc_selrefs: 0x1768
   __DATA_CONST.__objc_protorefs: 0x38
   __DATA_CONST.__objc_superrefs: 0x1e0
   __DATA_CONST.__objc_arraydata: 0x5a0

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 994
-  Symbols:   2865
+  Functions: 1005
+  Symbols:   2877
   CStrings:  576
 
Symbols:
+ -[UISActivityContinuationAction abortForUsageViolation:]
+ -[UISFetchContentInBackgroundAction abortForUsageViolation:]
+ -[UISHandleApplicationShortcutAction abortForUsageViolation:]
+ -[UISHandleBackgroundURLSessionAction abortForUsageViolation:]
+ -[UISHandleCloudKitShareAction abortForUsageViolation:]
+ -[UISHandleRemoteNotificationAction abortForUsageViolation:]
+ -[UISIntentForwardingActionResponse abortForUsageViolation:]
+ -[UISNotificationResponseAction abortForUsageViolation:]
+ -[UISOpenURLAction abortForUsageViolation:]
+ -[UISSceneConnectionValueAction abortForUsageViolation:]
+ -[_UISPlaygroundsPassthroughAction abortForUsageViolation:]
+ _objc_msgSend$abort
Functions:
+ -[UISSceneConnectionValueAction abortForUsageViolation:]
+ -[UISHandleRemoteNotificationAction abortForUsageViolation:]
+ -[UISNotificationResponseAction abortForUsageViolation:]
+ +[UISPasteSharingToken supportsSecureCoding]
+ -[UISHandleCloudKitShareAction abortForUsageViolation:]
+ -[UISOpenURLAction abortForUsageViolation:]
+ -[UISHandleBackgroundURLSessionAction abortForUsageViolation:]
+ -[UISIntentForwardingActionResponse abortForUsageViolation:]
+ +[UISSceneRequestOptions supportsBSXPCSecureCoding]
+ -[UISHandleApplicationShortcutAction abortForUsageViolation:]
+ -[_UISPlaygroundsPassthroughAction abortForUsageViolation:]
```
