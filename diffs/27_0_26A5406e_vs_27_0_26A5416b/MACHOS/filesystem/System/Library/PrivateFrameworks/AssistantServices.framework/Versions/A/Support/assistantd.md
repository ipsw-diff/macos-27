## assistantd

> `/System/Library/PrivateFrameworks/AssistantServices.framework/Versions/A/Support/assistantd`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_catlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_dictobj`
- `__DATA_CONST.__got`
- `__DATA_CONST.__auth_ptr`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-3600.68.61.0.0
-  __TEXT.__text: 0x533548
-  __TEXT.__auth_stubs: 0x3210
-  __TEXT.__objc_stubs: 0x424c0
-  __TEXT.__objc_methlist: 0x21884
-  __TEXT.__cstring: 0x4a1c2
+3600.68.61.14.4
+  __TEXT.__text: 0x533dac
+  __TEXT.__auth_stubs: 0x3220
+  __TEXT.__objc_stubs: 0x42560
+  __TEXT.__objc_methlist: 0x2189c
+  __TEXT.__cstring: 0x4a2b9
   __TEXT.__const: 0xa2ec0
-  __TEXT.__dlopen_cstrs: 0x56f
-  __TEXT.__gcc_except_tab: 0x30dc
-  __TEXT.__oslogstring: 0x3e8f6
+  __TEXT.__dlopen_cstrs: 0x5bb
+  __TEXT.__gcc_except_tab: 0x3118
+  __TEXT.__oslogstring: 0x3e9f3
   __TEXT.__objc_classname: 0x4dc9
-  __TEXT.__objc_methname: 0x5b370
-  __TEXT.__objc_methtype: 0xebcd
+  __TEXT.__objc_methname: 0x5b466
+  __TEXT.__objc_methtype: 0xebfd
   __TEXT.__ustring: 0x32
-  __TEXT.__unwind_info: 0x9710
+  __TEXT.__unwind_info: 0x9728
   __TEXT.__eh_frame: 0x140
-  __DATA_CONST.__const: 0x231c0
+  __DATA_CONST.__const: 0x231d8
   __DATA_CONST.__cfstring: 0x113e0
   __DATA_CONST.__objc_classlist: 0xcb0
   __DATA_CONST.__objc_catlist: 0x630

   __DATA_CONST.__objc_dictobj: 0x2f8
   __DATA_CONST.__objc_doubleobj: 0x20
   __DATA_CONST.__objc_floatobj: 0x30
-  __DATA_CONST.__auth_got: 0x1918
+  __DATA_CONST.__auth_got: 0x1920
   __DATA_CONST.__got: 0x39b0
   __DATA_CONST.__auth_ptr: 0x20
-  __DATA.__objc_const: 0x320c8
-  __DATA.__objc_selrefs: 0x13da0
-  __DATA.__objc_ivar: 0x247c
+  __DATA.__objc_const: 0x320e8
+  __DATA.__objc_selrefs: 0x13dd0
+  __DATA.__objc_ivar: 0x2480
   __DATA.__objc_data: 0x7ee0
   __DATA.__data: 0x5af8
-  __DATA.__bss: 0x9c8
+  __DATA.__bss: 0x9d8
   __DATA.__common: 0x1428
   - /System/Library/Frameworks/AVFoundation.framework/Versions/A/AVFoundation
   - /System/Library/Frameworks/AVRouting.framework/Versions/A/AVRouting

   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libresolv.9.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 13838
-  Symbols:   2757
-  CStrings:  25633
+  Functions: 13844
+  Symbols:   2758
+  CStrings:  25650
 
Symbols:
+ _NSStringFromAFSiriStatus
CStrings:
+ "%s #SiriAvailability computed status=%{public}@ restrictionReasons=%{public}@ isAssistantEnabled=%{bool}d"
+ "%s #SiriAvailability recomputing: assessment mode active changed"
+ "%s Siri restriction lifted - restoring assistant to its pre-restriction state: %d"
+ "-[ADSiriCapabilitiesStore handleAssessmentModeActiveDidChange]"
+ "/System/Library/PrivateFrameworks/AACCore.framework/Contents/MacOS/AACCore"
+ "@\"AEAssessmentModeGestalt\""
+ "AEAssessmentModeGestalt"
+ "Class getAEAssessmentModeGestaltClass(void)_block_invoke"
+ "MobileAssistantDaemons-3600.68.61.14.4"
+ "_assessmentModeGestalt"
+ "addObserver:forKeyPath:options:context:"
+ "assistantEnabledBeforeRestriction"
+ "handleAssessmentModeActiveDidChange"
+ "observeValueForKeyPath:ofObject:change:context:"
+ "removeObserver:forKeyPath:"
+ "setAssistantEnabledBeforeRestriction:"
+ "softlink:o:path:/System/Library/PrivateFrameworks/AACCore.framework/AACCore"
+ "v48@0:8@16@24@32^v40"
+ "void *AACCoreLibrary(void)"
- "177"
- "MobileAssistantDaemons-3600.68.61"
```
