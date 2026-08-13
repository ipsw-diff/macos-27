## ViceroyTrace

> `/System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/Versions/A/ViceroyTrace`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH_CONST.__objc_arrayobj`
- `__AUTH.__data`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`
- `__DATA_DIRTY.__data`

```diff

-2235.57.1.0.0
-  __TEXT.__text: 0xb84c8
+2235.62.1.0.0
+  __TEXT.__text: 0xb85f0
   __TEXT.__objc_methlist: 0x9308
   __TEXT.__const: 0x2720
-  __TEXT.__cstring: 0xf269
-  __TEXT.__oslogstring: 0xf79b
+  __TEXT.__cstring: 0xf27b
+  __TEXT.__oslogstring: 0xf7e8
   __TEXT.__gcc_except_tab: 0x370
   __TEXT.__dlopen_cstrs: 0x4e
   __TEXT.__unwind_info: 0x1848

   __DATA_CONST.__objc_arraydata: 0x220
   __DATA_CONST.__got: 0x280
   __AUTH_CONST.__const: 0xbd0
-  __AUTH_CONST.__cfstring: 0xec20
-  __AUTH_CONST.__objc_const: 0x17888
+  __AUTH_CONST.__cfstring: 0xec40
+  __AUTH_CONST.__objc_const: 0x178a8
   __AUTH_CONST.__objc_dictobj: 0x50
-  __AUTH_CONST.__objc_intobj: 0x480
+  __AUTH_CONST.__objc_intobj: 0x498
   __AUTH_CONST.__objc_arrayobj: 0x60
-  __AUTH_CONST.__auth_got: 0x650
+  __AUTH_CONST.__auth_got: 0x658
   __AUTH.__data: 0x30
-  __DATA.__objc_ivar: 0x21ec
+  __DATA.__objc_ivar: 0x21f0
   __DATA.__data: 0x748
   __DATA.__bss: 0x40
   __DATA.__common: 0x1

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 4235
-  Symbols:   8820
-  CStrings:  3322
+  Functions: 4236
+  Symbols:   8822
+  CStrings:  3324
 
Symbols:
+ OBJC_IVAR_$_VCAggregatorAirPlay._reportedMediaStreamType
+ _CFPropertyListCreateDeepCopy
Functions:
~ -[VCAggregatorAirPlay initWithDelegate:options:] : 1392 -> 1412
~ -[VCAggregatorAirPlay composeSegmentReport:] : 904 -> 956
~ -[VCAggregatorAirPlay updateSenderVideoStreamConfiguration:] : 448 -> 488
~ -[RTCReportingAgent reportPeriodicTelemetryWithCategory:type:payload:lock:] : 368 -> 420
~ -[VCPersistentDataStore finalizeInternal] : 144 -> 128
~ -[VCPersistentDataStore closeDatabase] : 100 -> 104
~ __VCPersistentDataStore_DumpMessage_block_invoke.62 : 296 -> 288
~ -[VCAggregatorHomeKitAudio dispatchedAggregatedSessionReport] : 324 -> 348
~ -[RTCReportingAgent reportPeriodicTelemetryWithCategory:type:payload:lock:].cold.1 : 124 -> 128
+ -[RTCReportingAgent reportPeriodicTelemetryWithCategory:type:payload:lock:].cold.3
CStrings:
+ " [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/Utilities/CompressionUtils.c:%d: Error ending deflate."
+ " [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/Utilities/CompressionUtils.c:%d: Error ending inflate."
+ " [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/Utilities/CompressionUtils.c:%d: Error initializing deflate."
+ " [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/Utilities/CompressionUtils.c:%d: Error initializing inflate."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: %s: CFBundleVersion for RTCReporting class returned nil. Defaulting it to 'Unknown'"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: (%p) Init time userInfo=%@"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: Agent is nil"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: ReportingVC(%s): agent is nil"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: ReportingVC(_validateClassAndSymbols): class or symbol don't exist."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: ReportingVC: error code=%d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: SymptomReporter: Couldn't find group symptomID, message=%@"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: _reportingVCRunOnce: can't load framework."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: algosScoreDictionary is nil"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: eventType:%d error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: eventType=%d error code=%d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: flushMessages: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: recipientUUID == NULL"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingAWDCallStart: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingCancelLog: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingConnecting: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingConnectionType: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingDisconnected: error code %d while sending final DTX stats"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingDisconnected: error code %d while sending final call stats"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingError: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingGetDefaults: pointers can't be NULL"
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingHandoverResult: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingLocalAndRemoteInterface: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingLog: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingModeRoleTransportLog: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingMomentsEvents: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingPerfTimes: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingProtectionLevel: error code=%d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingRemoteFrameSize: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingThermal: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingTierLog: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingVideoPaused: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingVideoProp: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingVisualRectangle: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingWiFiCallingLogCallEnd: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingWiFiCallingLogCallStart: error code %d."
+ "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.gf4w0V/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingWiFiCallingLogMetricSample: error code %d."
+ "ReportingVC [%s] %s:%d Failed to populate payload snapshot for Periodic Task"
+ "VCMediaStreamType"
- " [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/Utilities/CompressionUtils.c:%d: Error ending deflate."
- " [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/Utilities/CompressionUtils.c:%d: Error ending inflate."
- " [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/Utilities/CompressionUtils.c:%d: Error initializing deflate."
- " [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/Utilities/CompressionUtils.c:%d: Error initializing inflate."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: %s: CFBundleVersion for RTCReporting class returned nil. Defaulting it to 'Unknown'"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: (%p) Init time userInfo=%@"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: Agent is nil"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: ReportingVC(%s): agent is nil"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: ReportingVC(_validateClassAndSymbols): class or symbol don't exist."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: ReportingVC: error code=%d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: SymptomReporter: Couldn't find group symptomID, message=%@"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: _reportingVCRunOnce: can't load framework."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: algosScoreDictionary is nil"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: eventType:%d error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: eventType=%d error code=%d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: flushMessages: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: recipientUUID == NULL"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingAWDCallStart: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingCancelLog: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingConnecting: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingConnectionType: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingDisconnected: error code %d while sending final DTX stats"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingDisconnected: error code %d while sending final call stats"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingError: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingGetDefaults: pointers can't be NULL"
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingHandoverResult: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingLocalAndRemoteInterface: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingLog: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingModeRoleTransportLog: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingMomentsEvents: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingPerfTimes: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingProtectionLevel: error code=%d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingRemoteFrameSize: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingThermal: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingTierLog: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingVideoPaused: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingVideoProp: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingVisualRectangle: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingWiFiCallingLogCallEnd: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingWiFiCallingLogCallStart: error code %d."
- "ReportingVC [%s] %s:%d /AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.KRqKyh/Sources/AVConference/ViceroyTrace.subproj/Sources/ReportingVC.m:%d: reportingWiFiCallingLogMetricSample: error code %d."
```
