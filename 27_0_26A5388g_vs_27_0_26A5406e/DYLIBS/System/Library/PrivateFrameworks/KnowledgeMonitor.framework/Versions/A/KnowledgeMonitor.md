## KnowledgeMonitor

> `/System/Library/PrivateFrameworks/KnowledgeMonitor.framework/Versions/A/KnowledgeMonitor`

### Sections with Same Size but Changed Content

- `__TEXT.__gcc_except_tab`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH_CONST.__objc_doubleobj`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-476.0.0.0.0
-  __TEXT.__text: 0x1be60
-  __TEXT.__objc_methlist: 0x1f04
+477.0.1.0.0
+  __TEXT.__text: 0x1bf28
+  __TEXT.__objc_methlist: 0x1f14
   __TEXT.__const: 0x110
   __TEXT.__gcc_except_tab: 0x45c
-  __TEXT.__cstring: 0x1695
+  __TEXT.__cstring: 0x16ab
   __TEXT.__oslogstring: 0x1a4f
-  __TEXT.__unwind_info: 0x750
+  __TEXT.__unwind_info: 0x758
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __DATA_CONST.__objc_classlist: 0xe0
   __DATA_CONST.__objc_protolist: 0x50
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x16a8
+  __DATA_CONST.__objc_selrefs: 0x16c0
   __DATA_CONST.__objc_superrefs: 0xb8
   __DATA_CONST.__objc_arraydata: 0x40
-  __DATA_CONST.__got: 0x3c8
-  __AUTH_CONST.__const: 0x710
-  __AUTH_CONST.__cfstring: 0xd60
+  __DATA_CONST.__got: 0x3d0
+  __AUTH_CONST.__const: 0x730
+  __AUTH_CONST.__cfstring: 0xd80
   __AUTH_CONST.__objc_const: 0x2ff8
   __AUTH_CONST.__objc_intobj: 0x108
   __AUTH_CONST.__objc_arrayobj: 0x90

   __AUTH_CONST.__auth_got: 0x0
   __DATA.__objc_ivar: 0x234
   __DATA.__data: 0x3c8
+  __DATA.__bss: 0x10
   __DATA_DIRTY.__objc_data: 0x8c0
   __DATA_DIRTY.__bss: 0x61
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 757
-  Symbols:   1938
-  CStrings:  312
+  Functions: 760
+  Symbols:   1946
+  CStrings:  313
 
Symbols:
+ -[_DKAssertionsPreventingRestartMonitor isIgnorableSleepPreventer:]
+ _OBJC_CLASS_$_NSRegularExpression
+ ___67-[_DKAssertionsPreventingRestartMonitor isIgnorableSleepPreventer:]_block_invoke
+ _objc_msgSend$isIgnorableSleepPreventer:
+ _objc_msgSend$numberOfMatchesInString:options:range:
+ _objc_msgSend$regularExpressionWithPattern:options:error:
+ isIgnorableSleepPreventer:.onceToken
+ isIgnorableSleepPreventer:.usbxdciRegex
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gxxwvI/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBacklightMonitor.m:193"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gxxwvI/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBatteryMonitor.m:138"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gxxwvI/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBatteryMonitor.m:68"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gxxwvI/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBluetoothMonitor.m:385"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gxxwvI/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBluetoothMonitor.m:446"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gxxwvI/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBluetoothMonitor.m:488"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gxxwvI/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBluetoothMonitor.m:707"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gxxwvI/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKNotificationTimeZoneChangeMonitor.m:163"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gxxwvI/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKNowPlayingMonitor.m:494"
+ "^AppleT[0-9]+USBXDCI$"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8D3wu6/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBacklightMonitor.m:193"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8D3wu6/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBatteryMonitor.m:138"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8D3wu6/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBatteryMonitor.m:68"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8D3wu6/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBluetoothMonitor.m:385"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8D3wu6/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBluetoothMonitor.m:446"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8D3wu6/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBluetoothMonitor.m:488"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8D3wu6/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKBluetoothMonitor.m:707"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8D3wu6/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKNotificationTimeZoneChangeMonitor.m:163"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.8D3wu6/Sources/DuetKnowledgeCollector/KnowledgeMonitor/KnowledgeMonitor/Monitors/_DKNowPlayingMonitor.m:494"
```
