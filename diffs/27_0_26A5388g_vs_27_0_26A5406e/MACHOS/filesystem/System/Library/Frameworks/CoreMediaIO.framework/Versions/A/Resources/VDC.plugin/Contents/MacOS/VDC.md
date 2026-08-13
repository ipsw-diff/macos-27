## VDC

> `/System/Library/Frameworks/CoreMediaIO.framework/Versions/A/Resources/VDC.plugin/Contents/MacOS/VDC`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`

```diff

-520.0.0.0.0
-  __TEXT.__text: 0x354d8
+520.21.1.0.0
+  __TEXT.__text: 0x35460
   __TEXT.__auth_stubs: 0xe30
-  __TEXT.__gcc_except_tab: 0x2d3c
+  __TEXT.__gcc_except_tab: 0x2d20
   __TEXT.__const: 0x818
   __TEXT.__oslogstring: 0x5f6c
   __TEXT.__cstring: 0x305d
-  __TEXT.__unwind_info: 0x1370
+  __TEXT.__unwind_info: 0x1378
   __DATA_CONST.__const: 0x2210
   __DATA_CONST.__cfstring: 0x920
   __DATA_CONST.__auth_got: 0x720

   - /System/Library/Frameworks/IOSurface.framework/Versions/A/IOSurface
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 1399
+  Functions: 1400
   Symbols:   1120
   CStrings:  596
 
Functions:
~ __ZN4CMIO2DP3VDC6PlugIn18UpdateDevicesStateEv : 1380 -> 988
+ sub_27448
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/Assistant/Client/CMIO_DPA_VDC_ClientExtras.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/PlugIn/CMIO_DP_VDC_Control.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/PlugIn/CMIO_DP_VDC_Device.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/PlugIn/CMIO_DP_VDC_PlugIn.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/PlugIn/CMIO_DP_VDC_Stream.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_Control.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_Device.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_HardwarePlugInInterface.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_HogMode.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_Object.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_Stream.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_Clock.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_DeviceMaster.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_FormatList.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_HogMode.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_SuspendedByUser.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CMIODebugMacros.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CMIO_Buffer.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CoreMediaAssistant/CMIO_CMA_BlockBuffer.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CoreMediaAssistant/CMIO_CMA_FormatDescription.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CoreMediaAssistant/CMIO_CMA_SimpleQueue.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CoreVideoAssistant/CMIO_CVA_Pixel_Buffer.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/DALAssistant/CMIO_DALA_System.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/IOKitAssistant/CMIO_IOKA_NotificationPort.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/IOKitAssistant/CMIO_IOKA_PowerNotification.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/POSIXThreadAssistant/CMIO_PTA_Assistance.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/POSIXThreadAssistant/CMIO_PTA_CFMachPortThread.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/POSIXThreadAssistant/CMIO_PTA_IsochronousThread.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/POSIXThreadAssistant/CMIO_PTA_NotificationPortThread.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.7v1tQZ/Sources/AppleUSBCamera/Sources/Utility/CMIO_CallbackDrivenFigDerivedClock.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/Assistant/Client/CMIO_DPA_VDC_ClientExtras.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/PlugIn/CMIO_DP_VDC_Control.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/PlugIn/CMIO_DP_VDC_Device.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/PlugIn/CMIO_DP_VDC_PlugIn.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/DeviceAbstractionLayer/Devices/VDC/PlugIn/CMIO_DP_VDC_Stream.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_Control.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_Device.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_HardwarePlugInInterface.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_HogMode.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_Object.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Base/CMIO_DP_Stream.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_Clock.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_DeviceMaster.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_FormatList.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_HogMode.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/DeviceAbstractionLayer/Devices/DP/Properties/CMIO_DP_Property_SuspendedByUser.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CMIODebugMacros.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CMIO_Buffer.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CoreMediaAssistant/CMIO_CMA_BlockBuffer.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CoreMediaAssistant/CMIO_CMA_FormatDescription.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CoreMediaAssistant/CMIO_CMA_SimpleQueue.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/CoreVideoAssistant/CMIO_CVA_Pixel_Buffer.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/DALAssistant/CMIO_DALA_System.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/IOKitAssistant/CMIO_IOKA_NotificationPort.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/IOKitAssistant/CMIO_IOKA_PowerNotification.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/POSIXThreadAssistant/CMIO_PTA_Assistance.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/POSIXThreadAssistant/CMIO_PTA_CFMachPortThread.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/POSIXThreadAssistant/CMIO_PTA_IsochronousThread.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Extras/CoreMediaIO/PublicUtility/POSIXThreadAssistant/CMIO_PTA_NotificationPortThread.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.O01a2o/Sources/AppleUSBCamera/Sources/Utility/CMIO_CallbackDrivenFigDerivedClock.cpp"
```
