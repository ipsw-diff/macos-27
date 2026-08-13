## CommCenter

> `/System/Library/Frameworks/CoreTelephony.framework/Support/CommCenter`

### Sections with Same Size but Changed Content

- `__TEXT.__init_offsets`
- `__TEXT.__objc_methlist`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-13482.0.0.0.0
-  __TEXT.__text: 0x761f8c
-  __TEXT.__auth_stubs: 0x7250
-  __TEXT.__objc_stubs: 0xbc20
+13487.1.0.0.0
+  __TEXT.__text: 0x7644d0
+  __TEXT.__auth_stubs: 0x7270
+  __TEXT.__objc_stubs: 0xbc40
   __TEXT.__init_offsets: 0x184
   __TEXT.__objc_methlist: 0x6d44
-  __TEXT.__const: 0x9696c
-  __TEXT.__cstring: 0x22817
-  __TEXT.__gcc_except_tab: 0x8b85c
-  __TEXT.__oslogstring: 0x8791a
+  __TEXT.__const: 0x9680c
+  __TEXT.__cstring: 0x2289c
+  __TEXT.__gcc_except_tab: 0x8bb18
+  __TEXT.__oslogstring: 0x87d3a
   __TEXT.__objc_classname: 0x18a2
-  __TEXT.__objc_methname: 0x12040
+  __TEXT.__objc_methname: 0x12045
   __TEXT.__objc_methtype: 0xe3e6
   __TEXT.__ustring: 0x3e2
-  __TEXT.__unwind_info: 0x2a5d0
-  __DATA_CONST.__const: 0x77c20
-  __DATA_CONST.__cfstring: 0xbd40
+  __TEXT.__unwind_info: 0x2a610
+  __DATA_CONST.__const: 0x77be0
+  __DATA_CONST.__cfstring: 0xbd80
   __DATA_CONST.__objc_classlist: 0x260
   __DATA_CONST.__objc_catlist: 0x88
   __DATA_CONST.__objc_protolist: 0x310

   __DATA_CONST.__objc_dictobj: 0x50
   __DATA_CONST.__linkguard: 0x1b
   __DATA_CONST.__objc_intobj: 0x60
-  __DATA_CONST.__auth_got: 0x3940
+  __DATA_CONST.__auth_got: 0x3950
   __DATA_CONST.__got: 0x1ea8
   __DATA_CONST.__auth_ptr: 0x30
   __DATA.__objc_const: 0x8050
-  __DATA.__objc_selrefs: 0x4a10
+  __DATA.__objc_selrefs: 0x4a18
   __DATA.__objc_ivar: 0x354
   __DATA.__objc_data: 0x17c0
   __DATA.__data: 0x3498

   - /usr/lib/libsqlite3.dylib
   - /usr/lib/libxml2.2.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 32867
-  Symbols:   2977
-  CStrings:  19601
+  Functions: 32876
+  Symbols:   2979
+  CStrings:  19625
 
Symbols:
+ __ZNK16CSIPacketAddress23isPublicRoutableAddressEv
+ __ZNK16CSIPacketAddress28isDefaultGatewayForInterfaceERKNSt3__112basic_stringIcNS0_11char_traitsIcEENS0_9allocatorIcEEEE
CStrings:
+ "%s%s%s%sJoined enquiryID(s):%{public}s with existing %@:-> %{public}s"
+ "%s%s%s%sKicking out existing %@ enquiryID(s):%{public}s in favor of %@"
+ "%s%s%s%sKicking out existing %@ enquiryID(s):%{public}s in favor of update %{public}s"
+ "%s%s'%s' is super"
+ "%s%s'%s' lost its super role"
+ "%s%sEnquiryID:%llu, cancelEnquiry removing getSIMStatus consumer"
+ "%s%sEnquiryID:%llu, cancelEnquiry removing setActiveICCID consumer"
+ "%s%sEnquiryID:%llu, unable to setActiveICCID - canceling"
+ "%s%sdecoupling label %s and last owner %s"
+ "%s%shandle getAuthorizationTokens response: Event cause is %s, enquiryID(s):%{public}s"
+ "%s%shandleGetSIMStatusResponse_sync: Event cause is %s, enquiryID(s):%{public}s"
+ "%s%shandleSetActiveICCIDResponse, cannot find callback for EnquiryID:%llu"
+ "%s%shandleSetActiveICCIDResponse: Event cause is %s, enquiryID(s):%{public}s"
+ ", oob-provisioned-ts:"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/CallModule/CallStateModel.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/APNStorage.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/DataAPNSettings.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/DataCollocationCommon.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/DataConnectionAgent.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/DataConnectionIMS.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/DataConnectionInterface.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/DataPDPActivator.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/DataServiceController.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/DataiRatControlleriOSBase.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/IPCU_CellProfile.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/Data/Source/IWLANDataContext.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Modules/SystemObserver/PowerObserver.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Source/Common/CSIPersistentProperties.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CSI/Source/PlatformSpecific/CSIFlatFileNvpStore.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CommCenter/Location/CTLocationBasedCountryDetermination.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CommCenter/Source/CSI/DarwinPDPConfig.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CommCenter/Source/DarwinPDPManager.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZgbWJk/Sources/CoreTelephony/CommCenter/Source/Startup/StartupActions.cpp"
+ "13487.1"
+ "13487.1~66"
+ "Checking ePDG address: is a default gateway: %{public}s [%{public}s] [%s]"
+ "Checking ePDG address: is not publicly routable: %{public}s [%{public}s] [%s]"
+ "Checking ePDG address: success: %{public}s [%{public}s] [%s]"
+ "DATA::          fMsgCounters is empty"
+ "DATA::          fMsgCounters.msgID = %llu counter = %llu"
+ "DATA::      fSlot: %s"
+ "Development Signed Carrier Bundles: Not Allowed"
+ "Sending reply for request (cid=%lu, rid=%lu): retrieveMessage: identifier=%@, from=%@, secure=%{BOOL}d content=%{sensitive}@, error=%@"
+ "Unknown fLinkType[%s]: %s (contextType)"
+ "Unknown fLinkType[%s]: %s (transportType)"
+ "ValidateEPDGAddress"
+ "VoWiFi provisioning state changing from null to %{bool}d"
+ "destroying local label '%s' owned by %s"
+ "epdgIp"
+ "from"
+ "metricCCBadIMSePDGAddress"
+ "oob-provisioned-ts"
+ "oobProvisionedTs"
+ "oobProvisionedTs:'"
+ "startIPSecConnection: NEIPSecIKESession startConnection failed, trying next address..."
+ "startIPSecConnection: ePDG Address is: %s but the IP address is not acceptable"
+ "startIPSecConnection: ePDG Address is: empty"
+ "startIPSecConnection: ePDG Address is: good: %{public}s"
- "%s%s%s go dangling, last owner %s"
- "%s%s%s%sJoined enquiryID(s):%s with existing %@:-> %s"
- "%s%s%s%sKicking out existing %@ enquiryID(s):%s in favor of %@"
- "%s%s%s%sKicking out existing %@ enquiryID(s):%s in favor of update %s"
- "%s%sEnquiryID:%llu, cancelEnquiry removing consumer"
- "%s%sNumber of consumers in setActiveICCID callback list: %ld"
- "%s%sUnable to setActiveICCID"
- "%s%shandle getAuthorizationTokens response: Event cause is %s, enquiryID(s):%s"
- "%s%shandleGetSIMStatusResponse_sync: Event cause is %s, enquiryID(s):%s"
- "%s%shandleSetActiveICCIDResponse: Event cause is %s"
- "%s%slabel %s stopped being super"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/CallModule/CallStateModel.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/APNStorage.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/DataAPNSettings.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/DataCollocationCommon.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/DataConnectionAgent.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/DataConnectionIMS.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/DataConnectionInterface.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/DataPDPActivator.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/DataServiceController.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/DataiRatControlleriOSBase.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/IPCU_CellProfile.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/Data/Source/IWLANDataContext.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Modules/SystemObserver/PowerObserver.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Source/Common/CSIPersistentProperties.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CSI/Source/PlatformSpecific/CSIFlatFileNvpStore.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CommCenter/Location/CTLocationBasedCountryDetermination.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CommCenter/Source/CSI/DarwinPDPConfig.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CommCenter/Source/DarwinPDPManager.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.m4D9TN/Sources/CoreTelephony/CommCenter/Source/Startup/StartupActions.cpp"
- "13482"
- "13482~72"
- "Development Signed Carrier Bundles: Allowed"
- "Sending reply for request (cid=%lu, rid=%lu): retrieveMessage: result=%@, error=%@"
```
