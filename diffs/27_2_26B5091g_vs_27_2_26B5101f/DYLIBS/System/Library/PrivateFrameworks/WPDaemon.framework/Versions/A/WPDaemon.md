## WPDaemon

> `/System/Library/PrivateFrameworks/WPDaemon.framework/Versions/A/WPDaemon`

### Sections with Same Size but Changed Content

- `__TEXT.__oslogstring`

```diff

-2701.4.0.0.0
-  __TEXT.__text: 0x5cbb0
+2701.7.0.0.0
+  __TEXT.__text: 0x5cba0
   __TEXT.__objc_methlist: 0x43a4
-  __TEXT.__cstring: 0x47fa
+  __TEXT.__cstring: 0x480b
   __TEXT.__const: 0x238
   __TEXT.__oslogstring: 0x9e35
   __TEXT.__gcc_except_tab: 0x115c

   - /usr/lib/libobjc.A.dylib
   Functions: 3403
   Symbols:   4083
-  CStrings:  1461
+  CStrings:  1462
 
Functions:
~ sub_236855390 -> sub_235dc2390 : 64 -> 68
~ -[WPScanRequest convertUseCaseToString:] : 3668 -> 3648
CStrings:
+ "MusicHandoffScan"
+ "WPDaemon macOS 27.2 (26B5100u) (WirelessProximity-2701.7) (Release) built on 2026-09-27 23:33:10"
- "WPDaemon macOS 27.2 (26B5090s) (WirelessProximity-2701.4) (Release) built on 2026-09-13 19:18:39"
```
