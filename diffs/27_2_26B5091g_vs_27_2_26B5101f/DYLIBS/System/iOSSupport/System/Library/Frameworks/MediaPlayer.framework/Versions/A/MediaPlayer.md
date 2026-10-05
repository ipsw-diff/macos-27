## MediaPlayer

> `/System/iOSSupport/System/Library/Frameworks/MediaPlayer.framework/Versions/A/MediaPlayer`

```diff

-4026.200.17.0.0
-  __TEXT.__text: 0x20d6f4
-  __TEXT.__objc_methlist: 0x21784
+4026.200.22.2.0
+  __TEXT.__text: 0x20db50
+  __TEXT.__objc_methlist: 0x2178c
   __TEXT.__const: 0x4d90
-  __TEXT.__cstring: 0x29c75
-  __TEXT.__oslogstring: 0xfe00
+  __TEXT.__cstring: 0x29cd5
+  __TEXT.__oslogstring: 0xfe90
   __TEXT.__gcc_except_tab: 0xa480
   __TEXT.__dlopen_cstrs: 0x25c
   __TEXT.__ustring: 0x1dc

   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_protos: 0x4
   __TEXT.__swift5_types2: 0x4
-  __TEXT.__unwind_info: 0xc1f8
+  __TEXT.__unwind_info: 0xc200
   __TEXT.__eh_frame: 0x4a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   __DATA_CONST.__objc_protolist: 0x368
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x10
-  __DATA_CONST.__objc_selrefs: 0x10368
+  __DATA_CONST.__objc_selrefs: 0x10388
   __DATA_CONST.__objc_protorefs: 0xa8
   __DATA_CONST.__objc_superrefs: 0xbb0
   __DATA_CONST.__objc_arraydata: 0x828
-  __DATA_CONST.__got: 0x1ec0
+  __DATA_CONST.__got: 0x1ed8
   __AUTH_CONST.__const: 0x4b80
-  __AUTH_CONST.__cfstring: 0x205a0
-  __AUTH_CONST.__objc_const: 0x38260
+  __AUTH_CONST.__cfstring: 0x205e0
+  __AUTH_CONST.__objc_const: 0x38280
   __AUTH_CONST.__weak_auth_got: 0x10
   __AUTH_CONST.__objc_intobj: 0x348
   __AUTH_CONST.__objc_arrayobj: 0xea0

   __AUTH_CONST.__auth_got: 0x1c70
   __AUTH.__objc_data: 0x6ff0
   __AUTH.__data: 0x100
-  __DATA.__objc_ivar: 0x2224
+  __DATA.__objc_ivar: 0x2228
   __DATA.__data: 0x2c30
   __DATA.__bss: 0x1bf0
   __DATA.__common: 0x18

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 13701
-  Symbols:   29974
-  CStrings:  5945
+  Functions: 13703
+  Symbols:   29984
+  CStrings:  5949
 
Symbols:
+ -[MPVolumeHardwareButtonController _isForeground]
+ -[MPVolumeHardwareButtonController _registerForButtonNotifications]
+ -[MPVolumeHardwareButtonController _unregisterForButtonNotifications]
+ -[MPVolumeHardwareButtonController _updateButtonNotificationRegistration]
+ OBJC_IVAR_$_MPVolumeHardwareButtonController._didEverRegisterForButtonNotifications
+ _UISceneDidActivateNotification
+ _UISceneDidDisconnectNotification
+ _UISceneDidEnterBackgroundNotification
+ _objc_msgSend$_isForeground
+ _objc_msgSend$_registerForButtonNotifications
+ _objc_msgSend$_unregisterForButtonNotifications
+ _objc_msgSend$_updateButtonNotificationRegistration
+ _objc_msgSend$activationState
+ _objc_msgSend$connectedScenes
+ _objc_msgSend$isWatch
- -[MPVolumeHardwareButtonController _applicationDidBecomeActiveNotification]
- -[MPVolumeHardwareButtonController _registerForButtonNotificationsIfNeeded]
- -[MPVolumeHardwareButtonController _unregisterForButtonNotificationsIfNeeded]
- _objc_msgSend$_registerForButtonNotificationsIfNeeded
- _objc_msgSend$_unregisterForButtonNotificationsIfNeeded
CStrings:
+ "MPVolumeHardwareButtonController.m"
+ "UIApplication and scene state must be read on the main thread."
+ "[HardwareButtonController] Registering for hardware volume button events"
+ "[HardwareButtonController] Unregistering for hardware volume button events"
```
