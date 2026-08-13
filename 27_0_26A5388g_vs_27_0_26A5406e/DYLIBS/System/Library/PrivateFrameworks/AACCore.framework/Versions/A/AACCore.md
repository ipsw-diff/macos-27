## AACCore

> `/System/Library/PrivateFrameworks/AACCore.framework/Versions/A/AACCore`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__objc_intobj`
- `__DATA.__data`
- `__DATA_DIRTY.__objc_data`

```diff

-56.0.0.0.0
-  __TEXT.__text: 0x139a8
-  __TEXT.__objc_methlist: 0x1a54
+56.0.3.0.0
+  __TEXT.__text: 0x13f24
+  __TEXT.__objc_methlist: 0x1abc
   __TEXT.__const: 0xe0
-  __TEXT.__cstring: 0x1aa0
+  __TEXT.__cstring: 0x1bb6
   __TEXT.__oslogstring: 0x5c3
   __TEXT.__gcc_except_tab: 0x124
-  __TEXT.__unwind_info: 0x598
+  __TEXT.__unwind_info: 0x5a0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0

   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0x128
   __DATA_CONST.__objc_classlist: 0x1b8
-  __DATA_CONST.__objc_catlist: 0x38
+  __DATA_CONST.__objc_catlist: 0x30
   __DATA_CONST.__objc_protolist: 0xd0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0xcc8
+  __DATA_CONST.__objc_selrefs: 0xd10
   __DATA_CONST.__objc_protorefs: 0x30
   __DATA_CONST.__objc_superrefs: 0x120
   __DATA_CONST.__got: 0x1d8
   __AUTH_CONST.__const: 0x600
-  __AUTH_CONST.__cfstring: 0x1640
-  __AUTH_CONST.__objc_const: 0x46f8
+  __AUTH_CONST.__cfstring: 0x16e0
+  __AUTH_CONST.__objc_const: 0x47a0
   __AUTH_CONST.__objc_intobj: 0x18
   __AUTH_CONST.__auth_got: 0x0
-  __DATA.__objc_ivar: 0x28c
+  __DATA.__objc_ivar: 0x2a0
   __DATA.__data: 0x9f8
   __DATA.__bss: 0x10
   __DATA_DIRTY.__objc_data: 0x1130

   - /usr/lib/libMobileGestalt.dylib
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 641
-  Symbols:   1806
-  CStrings:  223
+  Functions: 651
+  Symbols:   1826
+  CStrings:  228
 
Symbols:
+ -[AEAssessmentApplicationDescriptor executablePath]
+ -[AEAssessmentApplicationDescriptor initWithExecutablePath:teamIdentifier:requiresSignatureValidation:]
+ -[AEAssessmentState _allowsAccessibilityIntelligence]
+ -[AEAssessmentState _allowsVisualIntelligence]
+ -[AEAssessmentState allowVirtualMachine]
+ -[AEAssessmentState allowsForceQuit]
+ -[AEAssessmentState setAllowVirtualMachine:]
+ -[AEAssessmentState setAllowsForceQuit:]
+ -[AEAssessmentState set_allowsAccessibilityIntelligence:]
+ -[AEAssessmentState set_allowsVisualIntelligence:]
+ -[AEPreferences useDeviceConfigurationProvider]
+ OBJC_IVAR_$_AEAssessmentApplicationDescriptor._executablePath
+ OBJC_IVAR_$_AEAssessmentState.__allowsAccessibilityIntelligence
+ OBJC_IVAR_$_AEAssessmentState.__allowsVisualIntelligence
+ OBJC_IVAR_$_AEAssessmentState._allowVirtualMachine
+ OBJC_IVAR_$_AEAssessmentState._allowsForceQuit
+ _objc_msgSend$_allowsAccessibilityIntelligence
+ _objc_msgSend$_allowsVisualIntelligence
+ _objc_msgSend$allowVirtualMachine
+ _objc_msgSend$allowsForceQuit
+ _objc_msgSend$executablePath
+ _objc_msgSend$setAllowVirtualMachine:
+ _objc_msgSend$setAllowsForceQuit:
+ _objc_msgSend$set_allowsAccessibilityIntelligence:
+ _objc_msgSend$set_allowsVisualIntelligence:
- -[NSData(AEAdditions) ae_hexString]
- __OBJC_$_CATEGORY_INSTANCE_METHODS_NSData_$_AEAdditions
- __OBJC_$_CATEGORY_NSData_$_AEAdditions
- __OBJC_$_PROP_LIST_NSData_$_AEAdditions
- _objc_msgSend$stringWithCapacity:
CStrings:
+ "<%@: %p { bundleIdentifier = %@, teamIdentifier = %@, requiresSignatureValidation = %@, pid = %@, executablePath = %@ }>"
+ "<%@: %p { isEnabled = %@, mainIndividualConfiguration = %@, configurationsByApplicationDescriptor = %@, allowsAutoCorrection = %@, allowsSmartPunctuation = %@, allowsSpellCheck = %@, allowsPredictiveKeyboard = %@, allowsActivityContinuation = %@, allowsDictation = %@, allowsAccessibilityAlternativeInputMethods = %@, allowsAccessibilityBackgroundSounds = %@, allowsAccessibilityFullKeyboardAccess = %@, allowsAccessibilityHoverText = %@, allowsAccessibilityKeyboard = %@, allowsAccessibilityLiveCaptions = %@, allowsAccessibilityLiveSpeech = %@, allowsAccessibilityReader = %@, allowsAccessibilitySpeech = %@, allowsAccessibilitySpokenContent = %@, allowsAccessibilitySwitchControl = %@, allowsAccessibilityTypingFeedback = %@, allowsAccessibilityVoiceControl = %@, allowsAccessibilityVoiceOver = %@, allowsAccessibilityZoom = %@, allowsPasswordAutoFill = %@, allowsContinuousPathKeyboard = %@, allowsKeyboardShortcuts = %@, allowsKeyboardMathSolving = %@, allowsMathPaperSolving = %@, allowsScreenshots = %@, allowsEmojiKeyboard = %@, allowedAppleMenuItems = %@, allowedDirectoriesAndFiles = %@, allowsAutoFill = %@, allowsStructuralInput = %@, allowsDock = %@, allowsMenuBar = %@, allowedMenuBarItems = %@, allowsUserScriptExecution = %@, allowOnlyParticipantsToRun = %@, allowsForceQuit = %@, maxBluetoothDevicesAllowed = %@, allowedBluetoothDeviceNames = %@, allowedBluetoothProfiles = %@, allowLockdownMode = %@, allowPrivateRelay = %@, allowVirtualMachine = %@, requiresManagedDevice = %@, requiresSIP = %@, requiresSingleUser = %@, requiresUserAccountType = %ld, _allowedCollaborationIDs = %@, _allowsAccessibilityIntelligence = %@, _allowsAirPlay = %@, _allowsContentCapture = %@, _allowsDonatingClipboardHistoryToSpotlight = %@, _allowsNetworkAccess = %@, _allowsSharingServices = %@, _allowsSpotlight = %@, _allowsVisualIntelligence = %@}>"
+ "UseDeviceConfigurationProvider"
+ "_allowsAccessibilityIntelligence"
+ "_allowsVisualIntelligence"
+ "allowVirtualMachine"
+ "allowsForceQuit"
+ "executablePath"
- "%02x"
- "<%@: %p { bundleIdentifier = %@, teamIdentifier = %@, requiresSignatureValidation = %@, pid = %@ }>"
- "<%@: %p { isEnabled = %@, mainIndividualConfiguration = %@, configurationsByApplicationDescriptor = %@, allowsAutoCorrection = %@, allowsSmartPunctuation = %@, allowsSpellCheck = %@, allowsPredictiveKeyboard = %@, allowsActivityContinuation = %@, allowsDictation = %@, allowsAccessibilityAlternativeInputMethods = %@, allowsAccessibilityBackgroundSounds = %@, allowsAccessibilityFullKeyboardAccess = %@, allowsAccessibilityHoverText = %@, allowsAccessibilityKeyboard = %@, allowsAccessibilityLiveCaptions = %@, allowsAccessibilityLiveSpeech = %@, allowsAccessibilityReader = %@, allowsAccessibilitySpeech = %@, allowsAccessibilitySpokenContent = %@, allowsAccessibilitySwitchControl = %@, allowsAccessibilityTypingFeedback = %@, allowsAccessibilityVoiceControl = %@, allowsAccessibilityVoiceOver = %@, allowsAccessibilityZoom = %@, allowsPasswordAutoFill = %@, allowsContinuousPathKeyboard = %@, allowsKeyboardShortcuts = %@, allowsKeyboardMathSolving = %@, allowsMathPaperSolving = %@, allowsScreenshots = %@, allowsEmojiKeyboard = %@, allowedAppleMenuItems = %@, allowedDirectoriesAndFiles = %@, allowsAutoFill = %@, allowsStructuralInput = %@, allowsDock = %@, allowsMenuBar = %@, allowedMenuBarItems = %@, allowsUserScriptExecution = %@, allowOnlyParticipantsToRun = %@, maxBluetoothDevicesAllowed = %@, allowedBluetoothDeviceNames = %@, allowedBluetoothProfiles = %@, allowLockdownMode = %@, allowPrivateRelay = %@, requiresManagedDevice = %@, requiresSIP = %@, requiresSingleUser = %@, requiresUserAccountType = %ld, _allowedCollaborationIDs = %@, _allowsAirPlay = %@, _allowsContentCapture = %@, _allowsDonatingClipboardHistoryToSpotlight = %@, _allowsNetworkAccess = %@, _allowsSharingServices = %@, _allowsSpotlight = %@}>"
```
