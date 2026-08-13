## wifip2pd

> `/usr/libexec/wifip2pd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__swift5_entry`
- `__TEXT.__swift5_builtin`
- `__TEXT.__swift5_assocty`
- `__TEXT.__swift5_protos`
- `__TEXT.__swift5_mpenum`
- `__TEXT.__swift_as_entry`
- `__TEXT.__swift_as_ret`
- `__TEXT.__swift_as_cont`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__auth_got`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`

```diff

-875.71.0.0.0
-  __TEXT.__text: 0x605c84
+875.79.0.0.0
+  __TEXT.__text: 0x609f78
   __TEXT.__auth_stubs: 0x4f90
   __TEXT.__objc_stubs: 0x47e0
   __TEXT.__objc_methlist: 0x1c2c
-  __TEXT.__const: 0x407f0
+  __TEXT.__const: 0x409f0
   __TEXT.__cstring: 0xfb54
-  __TEXT.__swift5_typeref: 0xd513
+  __TEXT.__swift5_typeref: 0xd5d7
   __TEXT.__swift5_entry: 0x8
-  __TEXT.__oslogstring: 0x235bc
-  __TEXT.__constg_swiftt: 0x10634
-  __TEXT.__swift5_fieldmd: 0x16b0c
-  __TEXT.__swift5_types: 0x1300
+  __TEXT.__oslogstring: 0x2379c
+  __TEXT.__constg_swiftt: 0x10688
+  __TEXT.__swift5_fieldmd: 0x16bd8
+  __TEXT.__swift5_types: 0x130c
   __TEXT.__swift5_builtin: 0x175c
-  __TEXT.__swift5_reflstr: 0x14df9
+  __TEXT.__swift5_reflstr: 0x14e99
   __TEXT.__swift5_assocty: 0x2d78
-  __TEXT.__swift5_proto: 0x3090
+  __TEXT.__swift5_proto: 0x3094
   __TEXT.__objc_methtype: 0x2367
   __TEXT.__swift5_protos: 0x108
-  __TEXT.__swift5_capture: 0x838c
-  __TEXT.__objc_methname: 0xa4e5
+  __TEXT.__swift5_capture: 0x8408
+  __TEXT.__objc_methname: 0xa505
   __TEXT.__objc_classname: 0x11f7
   __TEXT.__swift5_mpenum: 0x1b8
   __TEXT.__swift_as_entry: 0x244
   __TEXT.__swift_as_ret: 0x194
   __TEXT.__swift_as_cont: 0x668
-  __TEXT.__unwind_info: 0x11148
-  __TEXT.__eh_frame: 0x1ed5c
-  __DATA_CONST.__const: 0x3a6c0
+  __TEXT.__unwind_info: 0x111a0
+  __TEXT.__eh_frame: 0x1eeac
+  __DATA_CONST.__const: 0x3a948
   __DATA_CONST.__cfstring: 0x20
   __DATA_CONST.__objc_classlist: 0x208
   __DATA_CONST.__objc_protolist: 0x2f0
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__objc_protorefs: 0x178
   __DATA_CONST.__auth_got: 0x27d0
-  __DATA_CONST.__got: 0x1080
-  __DATA_CONST.__auth_ptr: 0x7a40
-  __DATA.__objc_const: 0xb080
+  __DATA_CONST.__got: 0x1070
+  __DATA_CONST.__auth_ptr: 0x7a20
+  __DATA.__objc_const: 0xb0e0
   __DATA.__objc_selrefs: 0x16f8
   __DATA.__objc_data: 0x1a70
-  __DATA.__data: 0x15530
-  __DATA.__bss: 0x5e450
-  __DATA.__common: 0xba8
+  __DATA.__data: 0x155d0
+  __DATA.__bss: 0x5e4d0
+  __DATA.__common: 0xbb8
   - /System/Library/Frameworks/Combine.framework/Versions/A/Combine
   - /System/Library/Frameworks/CoreBluetooth.framework/Versions/A/CoreBluetooth
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/swift/libswift_DarwinFoundation1.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 25219
-  Symbols:   2285
+  Functions: 25251
+  Symbols:   2284
   CStrings:  5615
 
Symbols:
- _$sSTsE3max2by7ElementQzSgSbAD_ADtKXE_tKF
CStrings:
+ "%@: Discovered Peers updated (%ld -> %ld): %s"
+ "%@: Expected .second pairingResponder for autoReply, got %s; skipping bootstrap for %s"
+ "%@: No discovered peers matched filter %s"
+ "%@: RESET Discovery Results: %s"
+ "%@: [BLOOM FILTER] Remove %s (ResetDiscoveryResults)"
+ "%@: [BLOOM FILTER] Remove ALL (ResetDiscoveryResults)"
+ "%@: cross layer key: %s"
+ "%@: cross layer key: failed to derive CL Setup Key: %@"
+ "%@: ignoring bootstrap request, already bootstrapped in state: %s"
+ "%@: reactivatePublish skipped — publish not active"
+ "%@: received: bootstrap request, dialogToken: %hhu"
+ "%s: Indicating pairing completed for %s to observers"
+ "349ddcf3fd6a6736d9e90f125d7847d129cf1d7da9cd63a5cecc4558564d5fc3"
+ "7fb5baf3b892a280021a2d9e63083a09a018050a2bcfe4c8b27474cf7dce3337"
+ "Completed(peerAddress: "
+ "Could not get the cross layer key derivation key since the PASN state is not confirmed"
+ "Failed to re-activate publish %@: %@"
+ "Reactivating %ld publish service(s)"
+ "Resetting bloom filters for Unpaired devices on ALL active subscribe instances ..."
+ "Resetting subscribe discovery results for (%ld) subscribes (Filter: %s)"
+ "WiFiP2P-875.79 Aug 04 2026 00:08:07"
+ "cross layer key inputs: ndpID: %hhu, listenerIPv6Address: %s, listenerPortNumber: %hu, service: %s, protocolName: %s, context: %s, pairingSession: %s"
+ "cross layer key: could not derive the CL-KDK"
+ "cross layer key: failed to derive the CL-KDK: %@"
+ "cross layer key: no pairing PASN found for the session"
+ "pairingObserverTasks"
+ "{\n  \"43089747ca3d9598cf03e9de1e1107494106392b1f61eb46a08a947222cf7114\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"573b6726934732678b34cf0f638d95579bf5245ee4e7c192ab12c50a07f45731\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"f8fc5cc66dc54b5618ffefcdf98fa55c44d03bd67288a940f07f0f6d8cdaa6d3\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"713c1fc19d3d365be619aafe84000243cbb1f56e269f77b12b68793818285100\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"b61d44bd7c8fb438a5e27acf728eef70ad53e6fa5e7674a03b76dffee10093d2\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"f990721d915cce59181e84ab5c9adb26796cb2197ed572d1a04670016ae94efe\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"da53396adabbe88b7670b56aa674e9a7032c67d7b6ef122f94d9a81eb4f3f4fb\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"59233f5cbf6baf36b65a817bed47728eedffeba9d1570098eafb2a2aafafb62d\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"abe29d9e1689bba54377c01b824887de442f64604b5c5bb9fbd80365f695393c\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"649f29b74a454b7a5ceaefe6c075ff5be9f6168f7db5189d52f3b67a8f3d5b1e\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"50385c8d0350cee7142b7029baf479489bb51e868e3d93ca3f0c528455e4f52e\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"20f1d0c48647f5818c133885ed69c9828de281be3709374aef3801987947cc96\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"611195731d40ce5c6e41c1d91f2b3838795a70054c562e32bb69e9ad7f924600\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
+ "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"66f7b71a029af0f28559b1f966d732f353530d32153ec648da1bda5dc0e47063\": {\n      \"WiFiAwareServices\": {\n        \"e4bbbe7b833e0abb0101c9661aae7533e943cf2c4580ffdf3fc0ba3635732843\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"80f288edad60a2e0e247ce79a18e2bb93d4c42304958867bc30db925bfbb7eeb\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"9641feb0b32d6ab5c42b8b4ca28102b1a95020b3454d2ad564eef6b153ae532e\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"946b944e2801765e307835e557a29c84c71a6572cae1c9f50fb13faafde1571d\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"c52fe4e3d6e1aaad3edba60ec7c57edff571c65b2a8edef1cb0a62ab63d81278\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"e09795484b013e1700f79c7fbb9a1562d6e58d8b4b3802777de0f13e23040472\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"20d0eeb12bc818f997da0bf7b57cfb7eba520b9e566d7cb8b474265905a5d089\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"7612ca01a8e5ab0160612ca1f8daf5986ec25f7c825e76b1d7c3a01f04dc017c\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"e5a874d0a2e8d31c0818cc3c2b7d26912c95b1e4faa4cf378bec6ae571c81e4f\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"ed78ae7fefe011ec7f9f7c4c1cef47aa2c2a4374de50a07826da9c5650c2339a\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"f4e206f3605c00c3b90acb445e389258ad804a601b167681328150e2675ae7e5\": {\n      \"WiFiAwareServices\": {\n        \"8b126f376c995cf275a195aa0add7422a103727b920bd89f949ee5c4956c2713\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"6d8b56a293328985870a9453adeefd11cb8c6182d282fa2520c001f78c0900ad\": {\n      \"WiFiAwareServices\": {\n        \"73afa5b7301b773bb235da1b43787f0d8149d222fec8b6fcbc4c7816c1f6859b\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"d2d6cacfe22897ca15e3c7b57ce65cd69b8fab203007f64b0e0174a7be774931\": {\n      \"WiFiAwareServices\": {\n        \"bfcdfa2bbf482ee2081d5b691c6fb7ff7af18ea20133275052aa26930ee29889\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"ca5a1bd86bdcea9d67eb4d7c289a6c390107f13fdbad9c60022374d9bc563f2b\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"9d29a68ae0661ba702590958a875e08fb546fa4ede84b2d9dd5a23bc566b8f01\": {\n      \"WiFiAwareServices\": {\n        \"8b126f376c995cf275a195aa0add7422a103727b920bd89f949ee5c4956c2713\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"c2e6cb20597f40b61f6eb9c42536f50cd3b483361463f7441a78cbfc1364ab06\": {\n      \"WiFiAwareServices\": {\n        \"73afa5b7301b773bb235da1b43787f0d8149d222fec8b6fcbc4c7816c1f6859b\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
- "  context: %s"
- "  listenerIPv6Address: %s"
- "  listenerPortNumber: %hu"
- "  ndpID: %hhu"
- "  pairingSession: %s"
- "  protocolName: %s"
- "  service: %s"
- "%@: Clearing discovered peers"
- "%@: Clearing discovered peers for %s"
- "%@: [BLOOM FILTER] Remove All (ResetDiscoveryResults)"
- "%@: [BLOOM FILTER] Remove for %s"
- "%@: received: bootstrap request"
- "%s: Indicating pairing completed for %s to the discovery engine"
- "%s: cross layer key: %s"
- "%s: cross layer key: not authenticated"
- "068725a644067b4149059ac75c8b2f99ecbf93b3f6c04b00b0d383cd813d84eb"
- "Could not get the cross layer set-up key since the PASN state is not confirmed"
- "Failed to derive shared secret: invalid state"
- "NANPairing.deriveSharedSecret inputs:"
- "PairingCompleted(peerAddress: "
- "Resetting ALL(%ld) subscribe discovery results"
- "Resetting bloom filters on ALL active subscribe instances ..."
- "Resetting subscribe discovery results for %s"
- "WiFiP2P-875.71 Jul 10 2026 23:07:34"
- "cross layer key: generating the CL set-up key..."
- "d5680f5e08b306b03a3615a649939405c7d3a4c8df8a32c25f57cc6f6aa94ca5"
- "{\n  \"557ea4a4b1fd96e1d27309f2e8ee2d13dc26b90533be275371f1df768d0cbc62\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASKAdvertiser\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"6028608c041aa2ea6f3045e84e89ea2697702e7f66fb82c59ad02c33ab3555ec\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"de7a6c16add714d244b486d99b4e60d22819a7fb25b53a68dd1ae0562be83f9e\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"macOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"dfef93f0404160ea8cd924e38e661c2e830da67d1a6d2ba586616c261d5a5169\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"ASK\",\n        \"DDUI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"866abc60e741cc972b544cff72e31a7bd08492c184168dfa7c3df93b18ba6305\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"tvOS\"\n      ]\n    }\n  },\n  \"1b80aa02a3faf0a64683e0745d77998383f9257fe952cf902dd73f47580b9e1a\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"MARS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  },\n  \"5ff458bbf4fede8aa1fd5c09567362e659d91355f9c6ce0fe6653ac6704169f9\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\"\n      ],\n      \"ClientID\": [\n        \"CLI\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"TDS\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\",\n        \"tvOS\",\n        \"visionOS\",\n        \"watchOS\"\n      ]\n    }\n  },\n  \"6b0216815315a86361625ff373d971a04cb9042633e724fe541d93687219aacd\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"visionOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"visionOS\"\n      ]\n    }\n  },\n  \"0233a3e4d4235903228f498616d001c6b4d52b67f94932df5ef9faa1a1e0a553\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Airplay\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"6f914d0cbbf7c35d8f88ec19c9cfd6be2cbb6d3bc6bf0381ce67ef1c3e1e881e\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ],\n      \"ClientID\": [\n        \"Terminus\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"tvOS\"\n      ]\n    }\n  },\n  \"d81bc47a6f885fea9a56ae93c2530748d1dba92224a9e4cdf7252ded84f6ffa8\": {\n    \"Publish\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"macOS\"\n      ]\n    }\n  },\n  \"4f4b041ce3640ec663e0e9e7075eefd352ff1cf10e8595ed5623206a2ea14083\": {\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"NoConsoleUser\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\",\n        \"macOS\"\n      ]\n    }\n  },\n  \"8416b7b00e4fba5693ba82b35df6f747397f1ebf4c1eb9e8e2e21caae19c5eaf\": {\n    \"Pairing\": {\n      \"Platforms\": [\n        \"iOS\"\n      ],\n      \"ClientID\": [\n        \"Migration\"\n      ]\n    },\n    \"Datapath\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Publish\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    },\n    \"Subscribe\": {\n      \"Platforms\": [\n        \"iOS\"\n      ]\n    }\n  }\n}"
- "{\n  \"WiFiAwareAllowedBundleIds\": {\n    \"b9c89e60858e411275036629cf710d145b49a180a7a5c3faf5b1f05019ed6324\": {\n      \"WiFiAwareServices\": {\n        \"f2134725adcaf72045a603a09b99c8f2ff5605766ca6a8ddc7d06632a9effd5d\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"4b0f9d6cb3d45d7bc4d835265838db8615f9506c3a96b16caa4f10a63590f020\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"5f20358788a8ad2cab175fd2e13a947294f221de2f8d4af48b011bfaec74fbce\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"c3ec6668f96d44fa26a7a74a21925b13972e41a9a4625c1202266dd7369689cc\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"20159b927a3cedb8333cb53f183fe36b3331b20ef078957a547da10d7d0842c5\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"5ee458cdbf5374000567cbcbdf8bba21234b718a8e93dc8f887489b6dbb22328\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"1d09a11e52e6a778f410ee69f0e4da1432879bf36e8c336c5cd9e94f1f8071cd\": {\n          \"Subscribable\": {},\n          \"Publishable\": {}\n        },\n        \"c40e609544ed71ee55204ef89c539c087cb929880397d3126ce64cda5b9c431c\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"faa3bdf0864766b6b41668b20c6282e984f75f10dc5c14750a10308bc056dc1e\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"6a2c40420567bbdab6e79766ae0c2e5303ad5513506eee78ce1f281deadb6400\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"e320024fca2dd8018ff87b396c60a45b5deb68f4571a2849b59aaeaa4f4585fa\": {\n      \"WiFiAwareServices\": {\n        \"c84279e2637f040cc507f90c5985d6ec029d34ecee9571d719ad6c1dcdb4c9c6\": {\n          \"Publishable\": {}\n        }\n      }\n    },\n    \"7a96a627c3422a1e85bf353a81642bda98acb5540da296d2db02d2c80f6d07d5\": {\n      \"WiFiAwareServices\": {\n        \"d9e41f7df5202bcfa17d2293d3ac2153f23e55b76d0dab925665e68cfdcebed9\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"b23fa33904a4abb2b63efadd69e91a4da2e95ae1a901434c08e4c24038e4189e\": {\n      \"WiFiAwareServices\": {\n        \"25a7d63541e2e8f7c03f5ab6cac9b434dfe6cabdaf29b612f0a2548ab09567a1\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        },\n        \"d707f4595f899d2f3a75d34c8aa749d3f7a44ced2fea745c2ac6ce244b2cdb08\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"82bcada2796339690bcde79c312f3499ce4c73e76b992564efd0b02d40b3c720\": {\n      \"WiFiAwareServices\": {\n        \"c84279e2637f040cc507f90c5985d6ec029d34ecee9571d719ad6c1dcdb4c9c6\": {\n          \"Subscribable\": {}\n        }\n      }\n    },\n    \"692c11b31797bab81abe68f8c4078a51010551613b5a8060f782b5bd6877e442\": {\n      \"WiFiAwareServices\": {\n        \"d9e41f7df5202bcfa17d2293d3ac2153f23e55b76d0dab925665e68cfdcebed9\": {\n          \"Publishable\": {},\n          \"Subscribable\": {}\n        }\n      }\n    }\n  }\n}"
```
