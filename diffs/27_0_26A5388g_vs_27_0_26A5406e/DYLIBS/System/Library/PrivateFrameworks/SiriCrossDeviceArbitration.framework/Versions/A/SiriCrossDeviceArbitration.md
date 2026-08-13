## SiriCrossDeviceArbitration

> `/System/Library/PrivateFrameworks/SiriCrossDeviceArbitration.framework/Versions/A/SiriCrossDeviceArbitration`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH_CONST.__objc_dictobj`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-3600.49.11.0.0
-  __TEXT.__text: 0x31460
+3600.49.15.0.0
+  __TEXT.__text: 0x314dc
   __TEXT.__objc_methlist: 0x310c
   __TEXT.__const: 0x1b0
   __TEXT.__dlopen_cstrs: 0xc2
Symbols:
+ -[SCDACoordinator _shouldLoseElectionForTVState]
+ _objc_msgSend$_shouldLoseElectionForTVState
- -[SCDACoordinator _shouldSuppressElectionForTVState]
- _objc_msgSend$_shouldSuppressElectionForTVState
Functions:
~ ___63-[SCDACoordinator startAdvertisingFromVoiceTriggerWithContext:]_block_invoke : 216 -> 252
~ ___88-[SCDACoordinator startAdvertisingFromVoiceTriggerWithGoodnessScoreContext:withContext:]_block_invoke : 1100 -> 1144
~ -[SCDACoordinator _startAdvertisingFromInTaskVoiceTrigger] : 424 -> 468
```
