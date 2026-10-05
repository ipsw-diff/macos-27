## ExchangeSync

> `/System/Library/PrivateFrameworks/ExchangeSync.framework/Versions/A/ExchangeSync`

```diff

-2080.200.41.0.0
-  __TEXT.__text: 0x16ff74
-  __TEXT.__objc_methlist: 0x5f44
-  __TEXT.__const: 0x85e4
-  __TEXT.__gcc_except_tab: 0xf80
-  __TEXT.__cstring: 0x11a82
-  __TEXT.__oslogstring: 0x6ada
-  __TEXT.__swift5_typeref: 0x2a10
-  __TEXT.__swift5_reflstr: 0x299c
-  __TEXT.__swift5_assocty: 0x920
-  __TEXT.__constg_swiftt: 0x2f58
-  __TEXT.__swift5_fieldmd: 0x29d8
-  __TEXT.__swift5_proto: 0x3e0
-  __TEXT.__swift5_types: 0x350
-  __TEXT.__swift5_protos: 0xcc
-  __TEXT.__swift5_capture: 0x808
-  __TEXT.__swift5_builtin: 0xb4
-  __TEXT.__swift5_mpenum: 0x20
-  __TEXT.__swift_as_entry: 0x8c
-  __TEXT.__swift_as_ret: 0x90
-  __TEXT.__swift_as_cont: 0x128
-  __TEXT.__unwind_info: 0x5e10
-  __TEXT.__eh_frame: 0x5f24
+2080.200.61.0.0
+  __TEXT.__text: 0x1ba4dc
+  __TEXT.__objc_methlist: 0x6cf4
+  __TEXT.__const: 0x9808
+  __TEXT.__gcc_except_tab: 0x1588
+  __TEXT.__cstring: 0xb5bc
+  __TEXT.__oslogstring: 0x11beb
+  __TEXT.__swift5_typeref: 0x2cea
+  __TEXT.__swift5_reflstr: 0x3076
+  __TEXT.__swift5_assocty: 0xa10
+  __TEXT.__constg_swiftt: 0x31b4
+  __TEXT.__swift5_fieldmd: 0x3280
+  __TEXT.__swift5_proto: 0x498
+  __TEXT.__swift5_types: 0x3fc
+  __TEXT.__swift5_protos: 0xbc
+  __TEXT.__swift5_capture: 0x82c
+  __TEXT.__swift5_builtin: 0xa0
+  __TEXT.__swift5_mpenum: 0x18
+  __TEXT.__unwind_info: 0x6640
+  __TEXT.__eh_frame: 0x5784
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
-  __DATA_CONST.__const: 0x4d0
-  __DATA_CONST.__objc_classlist: 0x370
+  __DATA_CONST.__const: 0x6b0
+  __DATA_CONST.__objc_classlist: 0x3c8
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0xb0
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_selrefs: 0x3cb8
+  __DATA_CONST.__objc_selrefs: 0x43c0
   __DATA_CONST.__objc_protorefs: 0x38
-  __DATA_CONST.__objc_superrefs: 0x1c0
+  __DATA_CONST.__objc_superrefs: 0x1f0
   __DATA_CONST.__objc_arraydata: 0x20
-  __DATA_CONST.__got: 0x14c8
-  __AUTH_CONST.__const: 0x8830
-  __AUTH_CONST.__cfstring: 0x4540
-  __AUTH_CONST.__objc_const: 0xd110
+  __DATA_CONST.__got: 0x1580
+  __AUTH_CONST.__const: 0xa480
+  __AUTH_CONST.__cfstring: 0x4d80
+  __AUTH_CONST.__objc_const: 0xe768
   __AUTH_CONST.__objc_arrayobj: 0x18
-  __AUTH_CONST.__auth_got: 0x2090
-  __AUTH.__objc_data: 0x1d90
-  __AUTH.__data: 0x2fd8
-  __DATA.__objc_ivar: 0x764
-  __DATA.__data: 0x16b8
-  __DATA.__bss: 0x67b0
-  __DATA.__common: 0x290
+  __AUTH_CONST.__auth_got: 0x2160
+  __AUTH.__objc_data: 0x2130
+  __AUTH.__data: 0x35e0
+  __DATA.__objc_ivar: 0x880
+  __DATA.__data: 0x1820
+  __DATA.__bss: 0x85c0
+  __DATA.__common: 0x518
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts
   - /System/Library/Frameworks/AppKit.framework/Versions/C/AppKit
   - /System/Library/Frameworks/ApplicationServices.framework/Versions/A/ApplicationServices

   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 7056
-  Symbols:   6821
-  CStrings:  1738
+  Functions: 7792
+  Symbols:   7606
+  CStrings:  1966
 
Symbols:
+ +[EXSAccountAction terminalRemovalActionForAccount:]
+ +[EXSAccountAction terminalRemovalActionForDelegateAccount:]
+ +[EXSFeatureFlagManager graphMigrationEnabled]
+ +[EXSGSMigrationGate _logGateOutcome:forAccount:dataManager:state:reason:]
+ +[EXSGSMigrationGate _resolveArmedOutcomeForAccount:dataManager:state:requiresCutover:]
+ +[EXSGSMigrationGate accountHasEverUsedEWS:dataManager:]
+ +[EXSGSMigrationGate accountIsVerifiedForLatchCommit:dataManager:]
+ +[EXSGSMigrationGate accountPropertySourceForAccount:]
+ +[EXSGSMigrationGate commitVerifiedGraphMigrationForAccount:dataManager:]
+ +[EXSGSMigrationGate conversionVerdictForAccount:dataManager:]
+ +[EXSGSMigrationGate evaluateForAccount:dataManager:]
+ +[EXSGSMigrationGate evaluateForAccount:dataManager:requiresCutover:]
+ +[EXSGSMigrationGate log]
+ +[EXSGSMigrationGate migrationStateForAccount:]
+ +[EXSGSMigrationGate setConversionVerifierForTesting:]
+ +[EXSGSMigrationPausedSyncProtocol changeSourceIDForAccountKey:]
+ +[EXSGSMigrationPausedSyncProtocol log]
+ +[EXSGraphIDMigrationOptions defaultOptions]
+ +[EXSSyncEngine _accountActionCouldStartOrRestartAccount:]
+ +[EXSSyncProtocolFactory newSyncProtocolInstanceForKind:account:dataManager:dispatchWorkloop:]
+ +[EXSSyncProtocolFactory protocolKindForAccount:dataManager:]
+ +[EXSSyncProtocolFactory protocolKindForAccount:dataManager:requiresGraphCutover:]
+ -[EXSAccount isExchangeOnlineForACAccount:]
+ -[EXSAccountAction _markAsTerminalRemoval]
+ -[EXSAccountAction terminalRemoval]
+ -[EXSAccountManager _beginPendingAddForClaimKey:ifNoneMatches:]
+ -[EXSAccountManager _commitKeepAliveDecision:forSequence:]
+ -[EXSAccountManager _createDelegateMetadataForACAccount:delegateKey:email:fullname:readOnly:]
+ -[EXSAccountManager _finishPendingAddForClaimKey:insertingAccount:]
+ -[EXSAccountManager evaluateOurNeedToRunReturningSequence:]
+ -[EXSAccountManager keepAliveCommitLock]
+ -[EXSAccountManager setKeepAliveCommitLock:]
+ -[EXSDataConsumerInstance _repushInterestedFolders]
+ -[EXSDataManager _graphMigrationColumn:isSetWithFailSafe:]
+ -[EXSDataManager _setGraphMigrationColumn:toValue:context:]
+ -[EXSDataManager activeSyncDialectStorage]
+ -[EXSDataManager activeSyncDialect]
+ -[EXSDataManager hasCompletedGraphMigrationHousekeeping]
+ -[EXSDataManager hasOpenDatabaseConnection]
+ -[EXSDataManager hasVerifiedGraphMigration]
+ -[EXSDataManager isChangeSourceCurrentlyRegistered:]
+ -[EXSDataManager lastLoggedMigrationGateOutcomeRawValueStorage]
+ -[EXSDataManager lastLoggedMigrationGateOutcomeRawValue]
+ -[EXSDataManager recordActiveSyncDialect:]
+ -[EXSDataManager recordGraphMigrationHousekeepingCompleted]
+ -[EXSDataManager recordGraphMigrationVerified]
+ -[EXSDataManager recordLastLoggedMigrationGateOutcomeRawValue:]
+ -[EXSDataManager seedChangeSourceWatermarkFromExistingSources:inAccount:]
+ -[EXSDataManager setActiveSyncDialectStorage:]
+ -[EXSDataManager setLastLoggedMigrationGateOutcomeRawValueStorage:]
+ -[EXSDataManager(ChangeItems) _resolveParentFolderForItemChangeItem:]
+ -[EXSDataManager(Folders) clearExternalSyncStateForAllFoldersInAccount:]
+ -[EXSDataManager(Folders_Private) _parentFolderAssociatedWithChangeItem:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationAbort:report:reason:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationApplyWrites:columnReport:report:state:db:write:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationClassifyValue:columnReport:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertAttachmentsWithOptions:report:state:db:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertChangeItemsWithOptions:report:state:db:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertDistinguishedFoldersWithOptions:report:state:db:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertFoldersWithOptions:report:state:db:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertItemsWithOptions:report:state:db:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationDistinctAccountCount]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationHasGraphNotesFolderMap]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationNotesOutsideRootFolderCount]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationPreconditionWithLegacyTablesPresent:schemaVersion:databaseOpenResult:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationRewriteBlob:rowID:dataClass:columnReport:report:state:options:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationSchemaVersion]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationShouldStop:options:]
+ -[EXSDataManager(GraphIDMigration) _graphIDMigrationTranslate:rowIDs:dataClasses:columnReport:report:state:options:]
+ -[EXSDataManager(GraphIDMigration) _logGraphIDMigrationReport:]
+ -[EXSDataManager(GraphIDMigration) _runGraphIDMigrationWithOptions:legacyTablesPresent:report:]
+ -[EXSDataManager(GraphIDMigration) migrateExternalIDsToGraphWithOptions:]
+ -[EXSEWSSyncProtocol prepareForShutdown]
+ -[EXSEWSSyncProtocol pushChangeItemsWithOutcome:withTrackingToken:]
+ -[EXSGSMigrationPausedSyncProtocol canStoreChangeTokens]
+ -[EXSGSMigrationPausedSyncProtocol changeSourceID]
+ -[EXSGSMigrationPausedSyncProtocol dataConsumersDidStartUp]
+ -[EXSGSMigrationPausedSyncProtocol downloadAttachmentWithRequestID:attachmentUUID:responseManager:]
+ -[EXSGSMigrationPausedSyncProtocol getDelegateFolderPermissionsForEmailSynchronously:error:]
+ -[EXSGSMigrationPausedSyncProtocol lastProcessedChangeToken]
+ -[EXSGSMigrationPausedSyncProtocol locateDeletedItemFolderIDAfterMigration]
+ -[EXSGSMigrationPausedSyncProtocol locateImportantFolders]
+ -[EXSGSMigrationPausedSyncProtocol pausedError]
+ -[EXSGSMigrationPausedSyncProtocol postPausedSyncStateChangedNotification]
+ -[EXSGSMigrationPausedSyncProtocol processOutstandingChangeItemsWithDispatchGroup:]
+ -[EXSGSMigrationPausedSyncProtocol pushChangeItems:withTrackingToken:]
+ -[EXSGSMigrationPausedSyncProtocol pushChangeItemsWithOutcome:withTrackingToken:]
+ -[EXSGSMigrationPausedSyncProtocol repushFolders:completionHandler:]
+ -[EXSGSMigrationPausedSyncProtocol resyncFolderHierarchyInitiatedBy:dispatchGroup:]
+ -[EXSGSMigrationPausedSyncProtocol resyncItemsForFolder:initiatedBy:dispatchGroup:]
+ -[EXSGSMigrationPausedSyncProtocol sendAvailabilityRequestWithComponents:]
+ -[EXSGSMigrationPausedSyncProtocol sendGetGrantedDelegatesRequest:]
+ -[EXSGSMigrationPausedSyncProtocol sendGrantedDelegateRequest:]
+ -[EXSGSMigrationPausedSyncProtocol sendSearchDirectoryRequest:]
+ -[EXSGSMigrationPausedSyncProtocol startup]
+ -[EXSGSMigrationPausedSyncProtocol syncAllFolderItemsForDataclasses:withDispatchGroup:]
+ -[EXSGSMigrationPausedSyncProtocol syncAllFolderItems]
+ -[EXSGSMigrationPausedSyncProtocol syncFolderHierarchyForFolderIDs:initiatedBy:dispatchGroup:]
+ -[EXSGSMigrationPausedSyncProtocol syncFolderHierarchyInitiatedBy:dispatchGroup:]
+ -[EXSGSMigrationPausedSyncProtocol syncItemsForFolder:initiatedBy:dispatchGroup:]
+ -[EXSGlobalDataManager legacyPerAccountTablesPresent]
+ -[EXSGraphIDMigrationColumnReport .cxx_destruct]
+ -[EXSGraphIDMigrationColumnReport addFailure:]
+ -[EXSGraphIDMigrationColumnReport column]
+ -[EXSGraphIDMigrationColumnReport failures]
+ -[EXSGraphIDMigrationColumnReport initWithTable:column:]
+ -[EXSGraphIDMigrationColumnReport mutableFailures]
+ -[EXSGraphIDMigrationColumnReport rowsAlreadyGraphShaped]
+ -[EXSGraphIDMigrationColumnReport rowsEmpty]
+ -[EXSGraphIDMigrationColumnReport rowsFailed]
+ -[EXSGraphIDMigrationColumnReport rowsNull]
+ -[EXSGraphIDMigrationColumnReport rowsScanned]
+ -[EXSGraphIDMigrationColumnReport rowsSkippedByPolicy]
+ -[EXSGraphIDMigrationColumnReport rowsTranslated]
+ -[EXSGraphIDMigrationColumnReport setMutableFailures:]
+ -[EXSGraphIDMigrationColumnReport setRowsAlreadyGraphShaped:]
+ -[EXSGraphIDMigrationColumnReport setRowsEmpty:]
+ -[EXSGraphIDMigrationColumnReport setRowsFailed:]
+ -[EXSGraphIDMigrationColumnReport setRowsNull:]
+ -[EXSGraphIDMigrationColumnReport setRowsScanned:]
+ -[EXSGraphIDMigrationColumnReport setRowsSkippedByPolicy:]
+ -[EXSGraphIDMigrationColumnReport setRowsTranslated:]
+ -[EXSGraphIDMigrationColumnReport setTranslateNanos:]
+ -[EXSGraphIDMigrationColumnReport setWriteNanos:]
+ -[EXSGraphIDMigrationColumnReport table]
+ -[EXSGraphIDMigrationColumnReport translateNanos]
+ -[EXSGraphIDMigrationColumnReport writeNanos]
+ -[EXSGraphIDMigrationDataClassReport .cxx_destruct]
+ -[EXSGraphIDMigrationDataClassReport alreadyGraphShaped]
+ -[EXSGraphIDMigrationDataClassReport attachments]
+ -[EXSGraphIDMigrationDataClassReport changeItems]
+ -[EXSGraphIDMigrationDataClassReport dataClass]
+ -[EXSGraphIDMigrationDataClassReport failed]
+ -[EXSGraphIDMigrationDataClassReport folders]
+ -[EXSGraphIDMigrationDataClassReport initWithDataClass:]
+ -[EXSGraphIDMigrationDataClassReport items]
+ -[EXSGraphIDMigrationDataClassReport setAlreadyGraphShaped:]
+ -[EXSGraphIDMigrationDataClassReport setAttachments:]
+ -[EXSGraphIDMigrationDataClassReport setChangeItems:]
+ -[EXSGraphIDMigrationDataClassReport setFailed:]
+ -[EXSGraphIDMigrationDataClassReport setFolders:]
+ -[EXSGraphIDMigrationDataClassReport setItems:]
+ -[EXSGraphIDMigrationDataClassReport setTranslated:]
+ -[EXSGraphIDMigrationDataClassReport translated]
+ -[EXSGraphIDMigrationFailure .cxx_destruct]
+ -[EXSGraphIDMigrationFailure column]
+ -[EXSGraphIDMigrationFailure initWithTable:column:rowID:outcome:reason:]
+ -[EXSGraphIDMigrationFailure outcome]
+ -[EXSGraphIDMigrationFailure reason]
+ -[EXSGraphIDMigrationFailure rowID]
+ -[EXSGraphIDMigrationFailure table]
+ -[EXSGraphIDMigrationOptions .cxx_destruct]
+ -[EXSGraphIDMigrationOptions abortsOnTranslationFailure]
+ -[EXSGraphIDMigrationOptions chunkSize]
+ -[EXSGraphIDMigrationOptions databaseOpenResult]
+ -[EXSGraphIDMigrationOptions dryRun]
+ -[EXSGraphIDMigrationOptions init]
+ -[EXSGraphIDMigrationOptions setAbortsOnTranslationFailure:]
+ -[EXSGraphIDMigrationOptions setChunkSize:]
+ -[EXSGraphIDMigrationOptions setDatabaseOpenResult:]
+ -[EXSGraphIDMigrationOptions setDryRun:]
+ -[EXSGraphIDMigrationOptions setShouldCancel:]
+ -[EXSGraphIDMigrationOptions shouldCancel]
+ -[EXSGraphIDMigrationReport .cxx_destruct]
+ -[EXSGraphIDMigrationReport abortReason]
+ -[EXSGraphIDMigrationReport accountKey]
+ -[EXSGraphIDMigrationReport allFailures]
+ -[EXSGraphIDMigrationReport cancelled]
+ -[EXSGraphIDMigrationReport chunkSize]
+ -[EXSGraphIDMigrationReport columnReportForTable:column:]
+ -[EXSGraphIDMigrationReport columnReports]
+ -[EXSGraphIDMigrationReport committed]
+ -[EXSGraphIDMigrationReport dataClassReportFor:]
+ -[EXSGraphIDMigrationReport dataClassReports]
+ -[EXSGraphIDMigrationReport databaseSchemaVersion]
+ -[EXSGraphIDMigrationReport dryRun]
+ -[EXSGraphIDMigrationReport init]
+ -[EXSGraphIDMigrationReport isDelegateAccount]
+ -[EXSGraphIDMigrationReport mutableColumnReports]
+ -[EXSGraphIDMigrationReport mutableDataClassReports]
+ -[EXSGraphIDMigrationReport notesOutsideRootFolder]
+ -[EXSGraphIDMigrationReport precondition]
+ -[EXSGraphIDMigrationReport setAbortReason:]
+ -[EXSGraphIDMigrationReport setAccountKey:]
+ -[EXSGraphIDMigrationReport setCancelled:]
+ -[EXSGraphIDMigrationReport setChunkSize:]
+ -[EXSGraphIDMigrationReport setCommitted:]
+ -[EXSGraphIDMigrationReport setDatabaseSchemaVersion:]
+ -[EXSGraphIDMigrationReport setDryRun:]
+ -[EXSGraphIDMigrationReport setIsDelegateAccount:]
+ -[EXSGraphIDMigrationReport setMutableColumnReports:]
+ -[EXSGraphIDMigrationReport setMutableDataClassReports:]
+ -[EXSGraphIDMigrationReport setNotesOutsideRootFolder:]
+ -[EXSGraphIDMigrationReport setPrecondition:]
+ -[EXSGraphIDMigrationReport setTotalNanos:]
+ -[EXSGraphIDMigrationReport setTransactionNanos:]
+ -[EXSGraphIDMigrationReport totalNanos]
+ -[EXSGraphIDMigrationReport totalRowsFailed]
+ -[EXSGraphIDMigrationReport totalRowsTranslated]
+ -[EXSGraphIDMigrationReport transactionNanos]
+ -[EXSGraphIDMigrationRunState cancelled]
+ -[EXSGraphIDMigrationRunState fatalFailure]
+ -[EXSGraphIDMigrationRunState setCancelled:]
+ -[EXSGraphIDMigrationRunState setFatalFailure:]
+ -[EXSSyncEngine _deferralPriorityForAccountAction:]
+ -[EXSSyncEngine _recordRefusedTransitionClaimForInstance:account:refusal:]
+ -[EXSSyncEngine accountKeysStartingUp]
+ -[EXSSyncEngine accountShutdown:isRemovedAccount:terminalRemoval:completion:]
+ -[EXSSyncEngine completeGraphMigrationTransitionForInstance:newKind:requiresGraphCutover:delegateAccount:parentAccount:]
+ -[EXSSyncEngine enterPendingDeferredStartupWork]
+ -[EXSSyncEngine enterPendingGraphMigrationTransitionWork]
+ -[EXSSyncEngine executeExchangeAccountAction:capturedEarlierInTime:completion:]
+ -[EXSSyncEngine executeExchangeAccountAction:completion:]
+ -[EXSSyncEngine handleExchangeAccountAction:completion:]
+ -[EXSSyncEngine isShuttingDown]
+ -[EXSSyncEngine lastCommittedNeedToRunSequence]
+ -[EXSSyncEngine leavePendingDeferredStartupWork]
+ -[EXSSyncEngine leavePendingGraphMigrationTransitionWork]
+ -[EXSSyncEngine pendingAccountInstanceWorkGroup]
+ -[EXSSyncEngine pendingDeferredStartupActionsGroup]
+ -[EXSSyncEngine pendingGraphMigrationTransitionsGroup]
+ -[EXSSyncEngine refreshShouldStayRunning]
+ -[EXSSyncEngine removeInactiveAccount:terminalRemoval:]
+ -[EXSSyncEngine setAccountKeysStartingUp:]
+ -[EXSSyncEngine setIsShuttingDown:]
+ -[EXSSyncEngine setLastCommittedNeedToRunSequence:]
+ -[EXSSyncEngine setPendingAccountInstanceWorkGroup:]
+ -[EXSSyncEngine setPendingDeferredStartupActionsGroup:]
+ -[EXSSyncEngine setPendingGraphMigrationTransitionsGroup:]
+ -[EXSSyncEngine setShouldStayRunningLock:]
+ -[EXSSyncEngine shouldStayRunningLock]
+ -[EXSSyncEngine syncEngineInstance:replayDeferredAccountAction:]
+ -[EXSSyncEngine transitionEngineInstance:toProtocolKind:requiresGraphCutover:]
+ -[EXSSyncEngine updateDelegates:forParentAccountChange:terminalRemoval:]
+ -[EXSSyncEngine waitForPendingAccountInstanceWorkUntilDeadline:]
+ -[EXSSyncEngineInstance _createAndRegisterSyncProtocolExpectingGraphKind:]
+ -[EXSSyncEngineInstance _deferAccountAction:priority:policy:isFirstDeferralInWindow:recorded:]
+ -[EXSSyncEngineInstance _installSyncProtocolForKind:]
+ -[EXSSyncEngineInstance _performGraphMigrationCutoverHousekeeping]
+ -[EXSSyncEngineInstance _performIdempotentGraphArmedLaunchStepsForAccount:]
+ -[EXSSyncEngineInstance _replayDeferredAccountAction:]
+ -[EXSSyncEngineInstance _startupEXSSyncEngineInstanceAfterGraphMigrationCutover]
+ -[EXSSyncEngineInstance _startupSyncProtocolExpectingGraphKind:]
+ -[EXSSyncEngineInstance dataConsumerInstanceAccountIsPausedForMigration:]
+ -[EXSSyncEngineInstance deferAccountActionDuringStartupWindow:priority:isFirstDeferralInWindow:]
+ -[EXSSyncEngineInstance deferAccountActionDuringStartupWindowWithoutClobbering:priority:isFirstDeferralInWindow:recorded:]
+ -[EXSSyncEngineInstance deferAccountActionForPendingGraphMigrationTransitionIsRemoval:terminalRemoval:]
+ -[EXSSyncEngineInstance deferredAccountActionPriority]
+ -[EXSSyncEngineInstance deferredAccountAction]
+ -[EXSSyncEngineInstance derivedGraphMigrationCutoverRequired]
+ -[EXSSyncEngineInstance endPendingGraphMigrationTransitionHonoringRemoval:]
+ -[EXSSyncEngineInstance endStartupWindowReturningDeferredAction]
+ -[EXSSyncEngineInstance isStartingUp]
+ -[EXSSyncEngineInstance pendingGraphMigrationTransition]
+ -[EXSSyncEngineInstance protocolKind]
+ -[EXSSyncEngineInstance removalPending]
+ -[EXSSyncEngineInstance removalRequestedDuringGraphMigrationTransitionIsTerminal]
+ -[EXSSyncEngineInstance removalRequestedDuringGraphMigrationTransition]
+ -[EXSSyncEngineInstance setDeferredAccountAction:]
+ -[EXSSyncEngineInstance setDeferredAccountActionPriority:]
+ -[EXSSyncEngineInstance setDerivedGraphMigrationCutoverRequired:]
+ -[EXSSyncEngineInstance setIsStartingUp:]
+ -[EXSSyncEngineInstance setPendingGraphMigrationTransition:]
+ -[EXSSyncEngineInstance setProtocolKind:]
+ -[EXSSyncEngineInstance setRemovalPending:]
+ -[EXSSyncEngineInstance setRemovalRequestedDuringGraphMigrationTransition:]
+ -[EXSSyncEngineInstance setRemovalRequestedDuringGraphMigrationTransitionIsTerminal:]
+ -[EXSSyncEngineInstance setStartupInProgress:]
+ -[EXSSyncEngineInstance shutdownWithGroup:]
+ -[EXSSyncEngineInstance startup:isGraphMigrationCutover:]
+ -[EXSSyncEngineInstance startupAfterGraphMigrationCutover:]
+ -[EXSSyncEngineInstance startupInProgress]
+ -[EXSSyncEngineInstance startupWithPermissionCheck:migratedData:isGraphMigrationCutover:]
+ -[EXSSyncEngineInstance tryBeginPendingGraphMigrationTransitionReportingRefusal:]
+ -[EXSSyncEngineInstance tryBeginPendingGraphMigrationTransition]
+ -[EXSSyncEngineInstance tryBeginStartupWindow]
+ -[EXSSyncProtocol dataConsumersDidStartUp]
+ -[EXSSyncProtocol isTearingDown]
+ GCC_except_table12
+ GCC_except_table145
+ GCC_except_table32
+ GCC_except_table40
+ GCC_except_table49
+ GCC_except_table52
+ GCC_except_table54
+ GCC_except_table55
+ GCC_except_table56
+ GCC_except_table58
+ GCC_except_table62
+ GCC_except_table64
+ GCC_except_table68
+ GCC_except_table75
+ GCC_except_table79
+ GCC_except_table80
+ OBJC_IVAR_$_EXSAccountAction._terminalRemoval
+ OBJC_IVAR_$_EXSAccountManager._keepAliveCommitLock
+ OBJC_IVAR_$_EXSAccountManager._lastCommittedKeepAliveSequence
+ OBJC_IVAR_$_EXSAccountManager._needToRunEvaluationSequence
+ OBJC_IVAR_$_EXSAccountManager._pendingAccountAdds
+ OBJC_IVAR_$_EXSDataManager._activeSyncDialectStorage
+ OBJC_IVAR_$_EXSDataManager._lastLoggedMigrationGateOutcomeRawValueStorage
+ OBJC_IVAR_$_EXSEWSSyncProtocol._pushRequestCancelledByTeardown
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._column
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._mutableFailures
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._rowsAlreadyGraphShaped
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._rowsEmpty
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._rowsFailed
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._rowsNull
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._rowsScanned
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._rowsSkippedByPolicy
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._rowsTranslated
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._table
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._translateNanos
+ OBJC_IVAR_$_EXSGraphIDMigrationColumnReport._writeNanos
+ OBJC_IVAR_$_EXSGraphIDMigrationDataClassReport._alreadyGraphShaped
+ OBJC_IVAR_$_EXSGraphIDMigrationDataClassReport._attachments
+ OBJC_IVAR_$_EXSGraphIDMigrationDataClassReport._changeItems
+ OBJC_IVAR_$_EXSGraphIDMigrationDataClassReport._dataClass
+ OBJC_IVAR_$_EXSGraphIDMigrationDataClassReport._failed
+ OBJC_IVAR_$_EXSGraphIDMigrationDataClassReport._folders
+ OBJC_IVAR_$_EXSGraphIDMigrationDataClassReport._items
+ OBJC_IVAR_$_EXSGraphIDMigrationDataClassReport._translated
+ OBJC_IVAR_$_EXSGraphIDMigrationFailure._column
+ OBJC_IVAR_$_EXSGraphIDMigrationFailure._outcome
+ OBJC_IVAR_$_EXSGraphIDMigrationFailure._reason
+ OBJC_IVAR_$_EXSGraphIDMigrationFailure._rowID
+ OBJC_IVAR_$_EXSGraphIDMigrationFailure._table
+ OBJC_IVAR_$_EXSGraphIDMigrationOptions._abortsOnTranslationFailure
+ OBJC_IVAR_$_EXSGraphIDMigrationOptions._chunkSize
+ OBJC_IVAR_$_EXSGraphIDMigrationOptions._databaseOpenResult
+ OBJC_IVAR_$_EXSGraphIDMigrationOptions._dryRun
+ OBJC_IVAR_$_EXSGraphIDMigrationOptions._shouldCancel
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._abortReason
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._accountKey
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._cancelled
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._chunkSize
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._committed
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._databaseSchemaVersion
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._dryRun
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._isDelegateAccount
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._mutableColumnReports
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._mutableDataClassReports
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._notesOutsideRootFolder
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._precondition
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._totalNanos
+ OBJC_IVAR_$_EXSGraphIDMigrationReport._transactionNanos
+ OBJC_IVAR_$_EXSGraphIDMigrationRunState._cancelled
+ OBJC_IVAR_$_EXSGraphIDMigrationRunState._fatalFailure
+ OBJC_IVAR_$_EXSSyncEngine._accountKeysStartingUp
+ OBJC_IVAR_$_EXSSyncEngine._isShuttingDown
+ OBJC_IVAR_$_EXSSyncEngine._lastCommittedNeedToRunSequence
+ OBJC_IVAR_$_EXSSyncEngine._pendingAccountInstanceWorkGroup
+ OBJC_IVAR_$_EXSSyncEngine._pendingDeferredStartupActionsGroup
+ OBJC_IVAR_$_EXSSyncEngine._pendingGraphMigrationTransitionsGroup
+ OBJC_IVAR_$_EXSSyncEngine._shouldStayRunningLock
+ OBJC_IVAR_$_EXSSyncEngineInstance._deferredAccountAction
+ OBJC_IVAR_$_EXSSyncEngineInstance._deferredAccountActionPriority
+ OBJC_IVAR_$_EXSSyncEngineInstance._derivedGraphMigrationCutoverRequired
+ OBJC_IVAR_$_EXSSyncEngineInstance._isStartingUp
+ OBJC_IVAR_$_EXSSyncEngineInstance._pendingGraphMigrationTransition
+ OBJC_IVAR_$_EXSSyncEngineInstance._protocolKind
+ OBJC_IVAR_$_EXSSyncEngineInstance._removalPending
+ OBJC_IVAR_$_EXSSyncEngineInstance._removalRequestedDuringGraphMigrationTransition
+ OBJC_IVAR_$_EXSSyncEngineInstance._removalRequestedDuringGraphMigrationTransitionIsTerminal
+ OBJC_IVAR_$_EXSSyncEngineInstance._startupInProgress
+ _EXSDefaultsKeyGraphMigration
+ _EXSGraphIDMigrationReadFaultReason
+ _EXSGraphIDMigrationWalkBlob
+ _OBJC_CLASS_$_EXSGSMigrationGate
+ _OBJC_CLASS_$_EXSGSMigrationPausedSyncProtocol
+ _OBJC_CLASS_$_EXSGraphIDMigrationColumnReport
+ _OBJC_CLASS_$_EXSGraphIDMigrationDataClassReport
+ _OBJC_CLASS_$_EXSGraphIDMigrationFailure
+ _OBJC_CLASS_$_EXSGraphIDMigrationOptions
+ _OBJC_CLASS_$_EXSGraphIDMigrationReport
+ _OBJC_CLASS_$_EXSGraphIDMigrationRunState
+ _OBJC_CLASS_$_NSISO8601DateFormatter
+ _OBJC_CLASS_$__TtC12ExchangeSync17EXSGSIdTranslator
+ _OBJC_CLASS_$__TtC12ExchangeSync19EXSWebPushTransport
+ _OBJC_CLASS_$__TtC12ExchangeSync24EXSGSIdTranslationResult
+ _OBJC_METACLASS_$_EXSGSMigrationGate
+ _OBJC_METACLASS_$_EXSGSMigrationPausedSyncProtocol
+ _OBJC_METACLASS_$_EXSGraphIDMigrationColumnReport
+ _OBJC_METACLASS_$_EXSGraphIDMigrationDataClassReport
+ _OBJC_METACLASS_$_EXSGraphIDMigrationFailure
+ _OBJC_METACLASS_$_EXSGraphIDMigrationOptions
+ _OBJC_METACLASS_$_EXSGraphIDMigrationReport
+ _OBJC_METACLASS_$_EXSGraphIDMigrationRunState
+ _OBJC_METACLASS_$__TtC12ExchangeSync17EXSGSIdTranslator
+ _OBJC_METACLASS_$__TtC12ExchangeSync19EXSWebPushTransport
+ _OBJC_METACLASS_$__TtC12ExchangeSync24EXSGSIdTranslationResult
+ __120-[EXSSyncEngine completeGraphMigrationTransitionForInstance:newKind:requiresGraphCutover:delegateAccount:parentAccount:]_block_invoke
+ __54-[EXSAccountManager accountChangedWithType:accountId:]_block_invoke
+ __59-[EXSDataManager _setGraphMigrationColumn:toValue:context:]_block_invoke
+ __64-[EXSSyncEngine syncEngineInstance:replayDeferredAccountAction:]_block_invoke
+ __72-[EXSDataManager(Folders) clearExternalSyncStateForAllFoldersInAccount:]_block_invoke
+ __73-[EXSDataManager seedChangeSourceWatermarkFromExistingSources:inAccount:]_block_invoke
+ __CLASS_METHODS__TtC12ExchangeSync17EXSGSIdTranslator
+ __DATA__TtC12ExchangeSync17EXSGSIdTranslator
+ __DATA__TtC12ExchangeSync19EXSWebPushTransport
+ __DATA__TtC12ExchangeSync23EXSGSWebPushCoordinator
+ __DATA__TtC12ExchangeSync24EXSGSIdTranslationResult
+ __DATA__TtC12ExchangeSync26EXSWebPushVapidKeyProvider
+ __DATA__TtC12ExchangeSync27EXSGSVapidPublicKeyProvider
+ __DATA__TtC12ExchangeSync31EXSGSWebPushSubscriptionService
+ __DATA__TtC12ExchangeSync34EXSWebPushGraphSubscriptionService
+ __DATA__TtC12ExchangeSync37EXSGSInMemoryWebPushSubscriptionStore
+ __DATA__TtCC12ExchangeSync19EXSWebPushTransportP33_F599398DB63F31C565EB854B8922C17D12WeakReceiver
+ __EXSGraphIDMigrationWalkBlob_block_invoke
+ __INSTANCE_METHODS__TtC12ExchangeSync17EXSGSIdTranslator
+ __INSTANCE_METHODS__TtC12ExchangeSync24EXSGSIdTranslationResult
+ __IVARS__TtC12ExchangeSync19EXSWebPushTransport
+ __IVARS__TtC12ExchangeSync23EXSGSWebPushCoordinator
+ __IVARS__TtC12ExchangeSync24EXSGSIdTranslationResult
+ __IVARS__TtC12ExchangeSync26EXSWebPushVapidKeyProvider
+ __IVARS__TtC12ExchangeSync27EXSGSVapidPublicKeyProvider
+ __IVARS__TtC12ExchangeSync31EXSGSWebPushSubscriptionService
+ __IVARS__TtC12ExchangeSync34EXSWebPushGraphSubscriptionService
+ __IVARS__TtC12ExchangeSync37EXSGSInMemoryWebPushSubscriptionStore
+ __IVARS__TtCC12ExchangeSync19EXSWebPushTransportP33_F599398DB63F31C565EB854B8922C17D12WeakReceiver
+ __METACLASS_DATA__TtC12ExchangeSync17EXSGSIdTranslator
+ __METACLASS_DATA__TtC12ExchangeSync19EXSWebPushTransport
+ __METACLASS_DATA__TtC12ExchangeSync23EXSGSWebPushCoordinator
+ __METACLASS_DATA__TtC12ExchangeSync24EXSGSIdTranslationResult
+ __METACLASS_DATA__TtC12ExchangeSync26EXSWebPushVapidKeyProvider
+ __METACLASS_DATA__TtC12ExchangeSync27EXSGSVapidPublicKeyProvider
+ __METACLASS_DATA__TtC12ExchangeSync31EXSGSWebPushSubscriptionService
+ __METACLASS_DATA__TtC12ExchangeSync34EXSWebPushGraphSubscriptionService
+ __METACLASS_DATA__TtC12ExchangeSync37EXSGSInMemoryWebPushSubscriptionStore
+ __METACLASS_DATA__TtCC12ExchangeSync19EXSWebPushTransportP33_F599398DB63F31C565EB854B8922C17D12WeakReceiver
+ __OBJC_$_CLASS_METHODS_EXSGSMigrationGate
+ __OBJC_$_CLASS_METHODS_EXSGSMigrationPausedSyncProtocol
+ __OBJC_$_CLASS_METHODS_EXSGraphIDMigrationOptions
+ __OBJC_$_INSTANCE_METHODS_EXSDataManager(Folders|Folders_Private|Items|Items_Private|Migration|GraphIDMigration|Attachments|ChangeItems)
+ __OBJC_$_INSTANCE_METHODS_EXSGSMigrationPausedSyncProtocol
+ __OBJC_$_INSTANCE_METHODS_EXSGSSyncProtocol(ExchangeSync|ExchangeSync|ExchangeSync1|ExchangeSync)
+ __OBJC_$_INSTANCE_METHODS_EXSGraphIDMigrationColumnReport
+ __OBJC_$_INSTANCE_METHODS_EXSGraphIDMigrationDataClassReport
+ __OBJC_$_INSTANCE_METHODS_EXSGraphIDMigrationFailure
+ __OBJC_$_INSTANCE_METHODS_EXSGraphIDMigrationOptions
+ __OBJC_$_INSTANCE_METHODS_EXSGraphIDMigrationReport
+ __OBJC_$_INSTANCE_METHODS_EXSGraphIDMigrationRunState
+ __OBJC_$_INSTANCE_METHODS__TtC12ExchangeSync19EXSWebPushTransport(ExchangeSync)
+ __OBJC_$_INSTANCE_VARIABLES_EXSGraphIDMigrationColumnReport
+ __OBJC_$_INSTANCE_VARIABLES_EXSGraphIDMigrationDataClassReport
+ __OBJC_$_INSTANCE_VARIABLES_EXSGraphIDMigrationFailure
+ __OBJC_$_INSTANCE_VARIABLES_EXSGraphIDMigrationOptions
+ __OBJC_$_INSTANCE_VARIABLES_EXSGraphIDMigrationReport
+ __OBJC_$_INSTANCE_VARIABLES_EXSGraphIDMigrationRunState
+ __OBJC_$_PROP_LIST_EXSGraphIDMigrationColumnReport
+ __OBJC_$_PROP_LIST_EXSGraphIDMigrationDataClassReport
+ __OBJC_$_PROP_LIST_EXSGraphIDMigrationFailure
+ __OBJC_$_PROP_LIST_EXSGraphIDMigrationOptions
+ __OBJC_$_PROP_LIST_EXSGraphIDMigrationReport
+ __OBJC_$_PROP_LIST_EXSGraphIDMigrationRunState
+ __OBJC_$_PROTOCOL_INSTANCE_METHODS_OPT_EXSSyncEngineDelegate
+ __OBJC_CLASS_PROTOCOLS_$_EXSGSSyncProtocol(ExchangeSync|ExchangeSync|ExchangeSync1|ExchangeSync)
+ __OBJC_CLASS_PROTOCOLS_$__TtC12ExchangeSync19EXSWebPushTransport(ExchangeSync)
+ __OBJC_CLASS_RO_$_EXSGSMigrationGate
+ __OBJC_CLASS_RO_$_EXSGSMigrationPausedSyncProtocol
+ __OBJC_CLASS_RO_$_EXSGraphIDMigrationColumnReport
+ __OBJC_CLASS_RO_$_EXSGraphIDMigrationDataClassReport
+ __OBJC_CLASS_RO_$_EXSGraphIDMigrationFailure
+ __OBJC_CLASS_RO_$_EXSGraphIDMigrationOptions
+ __OBJC_CLASS_RO_$_EXSGraphIDMigrationReport
+ __OBJC_CLASS_RO_$_EXSGraphIDMigrationRunState
+ __OBJC_METACLASS_RO_$_EXSGSMigrationGate
+ __OBJC_METACLASS_RO_$_EXSGSMigrationPausedSyncProtocol
+ __OBJC_METACLASS_RO_$_EXSGraphIDMigrationColumnReport
+ __OBJC_METACLASS_RO_$_EXSGraphIDMigrationDataClassReport
+ __OBJC_METACLASS_RO_$_EXSGraphIDMigrationFailure
+ __OBJC_METACLASS_RO_$_EXSGraphIDMigrationOptions
+ __OBJC_METACLASS_RO_$_EXSGraphIDMigrationReport
+ __OBJC_METACLASS_RO_$_EXSGraphIDMigrationRunState
+ __PROPERTIES__TtC12ExchangeSync24EXSGSIdTranslationResult
+ ___100-[EXSDataManager(GraphIDMigration) _graphIDMigrationApplyWrites:columnReport:report:state:db:write:]_block_invoke
+ ___108-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertDistinguishedFoldersWithOptions:report:state:db:]_block_invoke
+ ___116-[EXSDataManager(GraphIDMigration) _graphIDMigrationTranslate:rowIDs:dataClasses:columnReport:report:state:options:]_block_invoke
+ ___120-[EXSSyncEngine completeGraphMigrationTransitionForInstance:newKind:requiresGraphCutover:delegateAccount:parentAccount:]_block_invoke
+ ___25+[EXSGSMigrationGate log]_block_invoke
+ ___39+[EXSGSMigrationPausedSyncProtocol log]_block_invoke
+ ___40-[EXSEWSSyncProtocol prepareForShutdown]_block_invoke
+ ___43-[EXSSyncEngineInstance shutdownWithGroup:]_block_invoke
+ ___52-[EXSDataManager isChangeSourceCurrentlyRegistered:]_block_invoke
+ ___53-[EXSGlobalDataManager legacyPerAccountTablesPresent]_block_invoke
+ ___54-[EXSAccountManager accountChangedWithType:accountId:]_block_invoke
+ ___57-[EXSSyncEngineInstance startup:isGraphMigrationCutover:]_block_invoke
+ ___58-[EXSDataManager _graphMigrationColumn:isSetWithFailSafe:]_block_invoke
+ ___59-[EXSDataManager _setGraphMigrationColumn:toValue:context:]_block_invoke
+ ___63-[EXSDataManager(GraphIDMigration) _logGraphIDMigrationReport:]_block_invoke
+ ___64-[EXSSyncEngine syncEngineInstance:replayDeferredAccountAction:]_block_invoke
+ ___72-[EXSDataManager(Folders) clearExternalSyncStateForAllFoldersInAccount:]_block_invoke
+ ___73-[EXSDataManager seedChangeSourceWatermarkFromExistingSources:inAccount:]_block_invoke
+ ___73-[EXSDataManager(GraphIDMigration) migrateExternalIDsToGraphWithOptions:]_block_invoke
+ ___77-[EXSSyncEngine accountShutdown:isRemovedAccount:terminalRemoval:completion:]_block_invoke
+ ___78-[EXSSyncEngine transitionEngineInstance:toProtocolKind:requiresGraphCutover:]_block_invoke
+ ___80-[EXSSyncEngineInstance _startupEXSSyncEngineInstanceAfterGraphMigrationCutover]_block_invoke
+ ___80-[EXSSyncEngineInstance _startupEXSSyncEngineInstanceAfterGraphMigrationCutover]_block_invoke_2
+ ___92-[EXSAccountManager _addDelegateForOwningACAccount:delegateEmail:delegateFullname:readOnly:]_block_invoke
+ ___93-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertItemsWithOptions:report:state:db:]_block_invoke
+ ___93-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertItemsWithOptions:report:state:db:]_block_invoke_2
+ ___95-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertFoldersWithOptions:report:state:db:]_block_invoke
+ ___95-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertFoldersWithOptions:report:state:db:]_block_invoke_2
+ ___95-[EXSDataManager(GraphIDMigration) _runGraphIDMigrationWithOptions:legacyTablesPresent:report:]_block_invoke
+ ___99-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertAttachmentsWithOptions:report:state:db:]_block_invoke
+ ___99-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertChangeItemsWithOptions:report:state:db:]_block_invoke
+ ___99-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertChangeItemsWithOptions:report:state:db:]_block_invoke_2
+ ___99-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertChangeItemsWithOptions:report:state:db:]_block_invoke_3
+ ___99-[EXSDataManager(GraphIDMigration) _graphIDMigrationConvertChangeItemsWithOptions:report:state:db:]_block_invoke_4
+ ___EXSGraphIDMigrationWalkBlob_block_invoke
+ ___EXSGraphIDMigrationWalkBlob_block_invoke_2
+ ___EXSGraphIDMigrationWalkBlob_block_invoke_3
+ ___NSDictionary0__struct
+ ___block_descriptor_104_e8_32s40s48s56s64s72s80s88r96r_e61_v32?0"_TtC12ExchangeSync24EXSGSIdTranslationResult"8Q16^B24l
+ ___block_descriptor_32_e39_B32?0"PQLConnection"8"NSNumber"1624l
+ ___block_descriptor_40_e8_32bs_e8_v16?08l
+ ___block_descriptor_40_e8_32s_e20_B16?0"EXSAccount"8l
+ ___block_descriptor_48_e8_32bs40bs_e8_v16?08l
+ ___block_descriptor_48_e8_32s40s_e20_B16?0"EXSAccount"8l
+ ___block_descriptor_56_e8_32s40s_e42_v24?0"NSMutableDictionary"8"NSString"16l
+ ___block_descriptor_57_e8_32s40s48s_e5_v8?0l
+ ___block_descriptor_58_e8_32s40r48r_e5_v8?0l
+ ___block_descriptor_61_e8_32s40s48s_e5_v8?0l
+ ___block_descriptor_64_e8_32s40bs48r56r_e25_v32?0"NSNumber"816^B24l
+ ___block_descriptor_72_e8_32s40s48s56s64bs_e5_v8?0l
+ ___block_descriptor_73_e8_32s40s48s56s_e5_v8?0l
+ ___copy_helper_block_e8_32b40b
+ ___copy_helper_block_e8_32s40b48r56r
+ ___copy_helper_block_e8_32s40s48s56s64b
+ ___copy_helper_block_e8_32s40s48s56s64s72s80s88r96r
+ ___destroy_helper_block_e8_32s40s48s56s64s72s80s88r96r
+ ___swift_destroy_boxed_opaque_existential_0Tm
+ ___swift_memcpy128_8
+ ___swift_memcpy161_8
+ ___unnamed_3
+ __objc_autoreleasePoolPop
+ __objc_autoreleasePoolPush
+ __os_log_fault_impl
+ __testConversionVerifier
+ _associated conformance 12ExchangeSync17EXSGSLogSubsystemOSHAASQ
+ _associated conformance 12ExchangeSync17EXSGSWebPushTopicVSHAASQ
+ _associated conformance 12ExchangeSync18EXSGSDownsyncScopeVs10SetAlgebraAASQ
+ _associated conformance 12ExchangeSync18EXSGSDownsyncScopeVs10SetAlgebraAAs25ExpressibleByArrayLiteral
+ _associated conformance 12ExchangeSync18EXSGSDownsyncScopeVs9OptionSetAASY
+ _associated conformance 12ExchangeSync18EXSGSDownsyncScopeVs9OptionSetAAs0F7Algebra
+ _associated conformance 12ExchangeSync20EXSWebPushChangeTypeOSHAASQ
+ _associated conformance 12ExchangeSync20EXSWebPushChangeTypeOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 12ExchangeSync21EXSGSWebPushDataClassOSHAASQ
+ _associated conformance 12ExchangeSync21EXSGSWebPushDataClassOs12CaseIterableAA8AllCasessADP_Sl
+ _associated conformance 12ExchangeSync21EXSGSWebPushRecordKeyVSHAASQ
+ _associated conformance 12ExchangeSync24EXSWebPushTransportErrorO10Foundation09LocalizedF0AAs0F0
+ _associated conformance 12ExchangeSync25EXSGSIdTranslationOutcomeOSHAASQ
+ _associated conformance 12ExchangeSync25EXSGSWebPushIneligibilityOSHAASQ
+ _associated conformance 12ExchangeSync26EXSWebPushVapidKeyProviderC6SourceOSHAASQ
+ _associated conformance 12ExchangeSync27EXSGSVapidPublicKeyProviderC6SourceOSHAASQ
+ _associated conformance 12ExchangeSync27EXSWebPushSubscriptionErrorO10Foundation09LocalizedF0AAs0F0
+ _associated conformance 12ExchangeSync29EXSGSWebPushSubscriptionScopeOSHAASQ
+ _associated conformance 12ExchangeSync29EXSWebPushNotificationPayloadO5Entry33_11C9EA1F0ECBCB5FB3573C385F075516LLV6AnyKeyVs06CodingP0AAs23CustomStringConvertible
+ _associated conformance 12ExchangeSync29EXSWebPushNotificationPayloadO5Entry33_11C9EA1F0ECBCB5FB3573C385F075516LLV6AnyKeyVs06CodingP0AAs28CustomDebugStringConvertible
+ _associated conformance 12ExchangeSync29EXSWebPushNotificationPayloadO8Envelope33_11C9EA1F0ECBCB5FB3573C385F075516LLV10CodingKeysOSHAASQ
+ _associated conformance 12ExchangeSync29EXSWebPushNotificationPayloadO8Envelope33_11C9EA1F0ECBCB5FB3573C385F075516LLV10CodingKeysOs0O3KeyAAs23CustomStringConvertible
+ _associated conformance 12ExchangeSync29EXSWebPushNotificationPayloadO8Envelope33_11C9EA1F0ECBCB5FB3573C385F075516LLV10CodingKeysOs0O3KeyAAs28CustomDebugStringConvertible
+ _associated conformance 12ExchangeSync38EXSGSCalendarPermissionResourceBuilderO08DelegateD12UpdateActionOSHAASQ
+ _get_enum_tag_for_layout_string 12ExchangeSync22EXSGSLogCategorySourceO
+ _get_enum_tag_for_layout_string 12ExchangeSync24EXSWebPushTransportErrorO
+ _get_enum_tag_for_layout_string 12ExchangeSync27EXSWebPushSubscriptionErrorO
+ _kEXSGSGraphMigrationExchangeSyncKey
+ _logGraphIDMigrationReport:.log
+ _logGraphIDMigrationReport:.onceToken
+ _objc_msgSend$_accountActionCouldStartOrRestartAccount:
+ _objc_msgSend$_beginPendingAddForClaimKey:ifNoneMatches:
+ _objc_msgSend$_commitKeepAliveDecision:forSequence:
+ _objc_msgSend$_createAndRegisterSyncProtocolExpectingGraphKind:
+ _objc_msgSend$_deferAccountAction:priority:policy:isFirstDeferralInWindow:recorded:
+ _objc_msgSend$_deferralPriorityForAccountAction:
+ _objc_msgSend$_finishPendingAddForClaimKey:insertingAccount:
+ _objc_msgSend$_graphIDMigrationAbort:report:reason:
+ _objc_msgSend$_graphIDMigrationApplyWrites:columnReport:report:state:db:write:
+ _objc_msgSend$_graphIDMigrationClassifyValue:columnReport:
+ _objc_msgSend$_graphIDMigrationConvertAttachmentsWithOptions:report:state:db:
+ _objc_msgSend$_graphIDMigrationConvertChangeItemsWithOptions:report:state:db:
+ _objc_msgSend$_graphIDMigrationConvertDistinguishedFoldersWithOptions:report:state:db:
+ _objc_msgSend$_graphIDMigrationConvertFoldersWithOptions:report:state:db:
+ _objc_msgSend$_graphIDMigrationConvertItemsWithOptions:report:state:db:
+ _objc_msgSend$_graphIDMigrationDistinctAccountCount
+ _objc_msgSend$_graphIDMigrationHasGraphNotesFolderMap
+ _objc_msgSend$_graphIDMigrationNotesOutsideRootFolderCount
+ _objc_msgSend$_graphIDMigrationPreconditionWithLegacyTablesPresent:schemaVersion:databaseOpenResult:
+ _objc_msgSend$_graphIDMigrationRewriteBlob:rowID:dataClass:columnReport:report:state:options:
+ _objc_msgSend$_graphIDMigrationSchemaVersion
+ _objc_msgSend$_graphIDMigrationShouldStop:options:
+ _objc_msgSend$_graphIDMigrationTranslate:rowIDs:dataClasses:columnReport:report:state:options:
+ _objc_msgSend$_graphMigrationColumn:isSetWithFailSafe:
+ _objc_msgSend$_installSyncProtocolForKind:
+ _objc_msgSend$_logGateOutcome:forAccount:dataManager:state:reason:
+ _objc_msgSend$_logGraphIDMigrationReport:
+ _objc_msgSend$_markAsTerminalRemoval
+ _objc_msgSend$_performGraphMigrationCutoverHousekeeping
+ _objc_msgSend$_performIdempotentGraphArmedLaunchStepsForAccount:
+ _objc_msgSend$_recordRefusedTransitionClaimForInstance:account:refusal:
+ _objc_msgSend$_replayDeferredAccountAction:
+ _objc_msgSend$_repushInterestedFolders
+ _objc_msgSend$_resolveArmedOutcomeForAccount:dataManager:state:requiresCutover:
+ _objc_msgSend$_resolveParentFolderForItemChangeItem:
+ _objc_msgSend$_runGraphIDMigrationWithOptions:legacyTablesPresent:report:
+ _objc_msgSend$_setGraphMigrationColumn:toValue:context:
+ _objc_msgSend$_startupEXSSyncEngineInstanceAfterGraphMigrationCutover
+ _objc_msgSend$_startupSyncProtocolExpectingGraphKind:
+ _objc_msgSend$abortReason
+ _objc_msgSend$abortsOnTranslationFailure
+ _objc_msgSend$accountHasEverUsedEWS:dataManager:
+ _objc_msgSend$accountIsVerifiedForLatchCommit:dataManager:
+ _objc_msgSend$accountKeysStartingUp
+ _objc_msgSend$accountPropertySourceForAccount:
+ _objc_msgSend$accountShutdown:isRemovedAccount:terminalRemoval:completion:
+ _objc_msgSend$activeSyncDialectStorage
+ _objc_msgSend$addFailure:
+ _objc_msgSend$alreadyGraphShaped
+ _objc_msgSend$cancelled
+ _objc_msgSend$changeItems
+ _objc_msgSend$changeSourceIDForAccountKey:
+ _objc_msgSend$chunkSize
+ _objc_msgSend$clearExternalSyncStateForAllFoldersInAccount:
+ _objc_msgSend$column
+ _objc_msgSend$columnReportForTable:column:
+ _objc_msgSend$columnReports
+ _objc_msgSend$commitVerifiedGraphMigrationForAccount:dataManager:
+ _objc_msgSend$committed
+ _objc_msgSend$completeGraphMigrationTransitionForInstance:newKind:requiresGraphCutover:delegateAccount:parentAccount:
+ _objc_msgSend$conversionVerdictForAccount:dataManager:
+ _objc_msgSend$dataClass
+ _objc_msgSend$dataClassReportFor:
+ _objc_msgSend$dataConsumerInstanceAccountIsPausedForMigration:
+ _objc_msgSend$dataConsumersDidStartUp
+ _objc_msgSend$databaseOpenResult
+ _objc_msgSend$databaseSchemaVersion
+ _objc_msgSend$deferAccountActionDuringStartupWindow:priority:isFirstDeferralInWindow:
+ _objc_msgSend$deferAccountActionDuringStartupWindowWithoutClobbering:priority:isFirstDeferralInWindow:recorded:
+ _objc_msgSend$deferAccountActionForPendingGraphMigrationTransitionIsRemoval:terminalRemoval:
+ _objc_msgSend$deferredAccountAction
+ _objc_msgSend$deferredAccountActionPriority
+ _objc_msgSend$derivedGraphMigrationCutoverRequired
+ _objc_msgSend$dictionary
+ _objc_msgSend$dryRun
+ _objc_msgSend$endPendingGraphMigrationTransitionHonoringRemoval:
+ _objc_msgSend$endStartupWindowReturningDeferredAction
+ _objc_msgSend$enterPendingDeferredStartupWork
+ _objc_msgSend$enterPendingGraphMigrationTransitionWork
+ _objc_msgSend$enumerateKeysAndObjectsUsingBlock:
+ _objc_msgSend$enumerateObjectsUsingBlock:
+ _objc_msgSend$evaluateForAccount:dataManager:requiresCutover:
+ _objc_msgSend$evaluateOurNeedToRunReturningSequence:
+ _objc_msgSend$executeExchangeAccountAction:capturedEarlierInTime:completion:
+ _objc_msgSend$executeExchangeAccountAction:completion:
+ _objc_msgSend$failed
+ _objc_msgSend$failureReason
+ _objc_msgSend$failures
+ _objc_msgSend$fatalFailure
+ _objc_msgSend$folders
+ _objc_msgSend$graphMigrationEnabled
+ _objc_msgSend$handleExchangeAccountAction:completion:
+ _objc_msgSend$hasCompletedGraphMigrationHousekeeping
+ _objc_msgSend$hasOpenDatabaseConnection
+ _objc_msgSend$hasVerifiedGraphMigration
+ _objc_msgSend$initWithDataClass:
+ _objc_msgSend$initWithTable:column:
+ _objc_msgSend$initWithTable:column:rowID:outcome:reason:
+ _objc_msgSend$isChangeSourceCurrentlyRegistered:
+ _objc_msgSend$isExchangeOnlineForACAccount:
+ _objc_msgSend$isShuttingDown
+ _objc_msgSend$isStartingUp
+ _objc_msgSend$isTearingDown
+ _objc_msgSend$items
+ _objc_msgSend$keepAliveCommitLock
+ _objc_msgSend$lastCommittedNeedToRunSequence
+ _objc_msgSend$lastLoggedMigrationGateOutcomeRawValue
+ _objc_msgSend$lastLoggedMigrationGateOutcomeRawValueStorage
+ _objc_msgSend$leavePendingDeferredStartupWork
+ _objc_msgSend$leavePendingGraphMigrationTransitionWork
+ _objc_msgSend$legacyPerAccountTablesPresent
+ _objc_msgSend$lowercaseString
+ _objc_msgSend$migrationStateForAccount:
+ _objc_msgSend$mutableColumnReports
+ _objc_msgSend$mutableDataClassReports
+ _objc_msgSend$mutableFailures
+ _objc_msgSend$newSyncProtocolInstanceForKind:account:dataManager:dispatchWorkloop:
+ _objc_msgSend$outcome
+ _objc_msgSend$pausedError
+ _objc_msgSend$pendingAccountInstanceWorkGroup
+ _objc_msgSend$pendingDeferredStartupActionsGroup
+ _objc_msgSend$pendingGraphMigrationTransition
+ _objc_msgSend$pendingGraphMigrationTransitionsGroup
+ _objc_msgSend$postPausedSyncStateChangedNotification
+ _objc_msgSend$precondition
+ _objc_msgSend$protocolKind
+ _objc_msgSend$protocolKindForAccount:dataManager:
+ _objc_msgSend$protocolKindForAccount:dataManager:requiresGraphCutover:
+ _objc_msgSend$rebaselinesOnNilChangeToken
+ _objc_msgSend$recordActiveSyncDialect:
+ _objc_msgSend$recordGraphMigrationHousekeepingCompleted
+ _objc_msgSend$recordGraphMigrationVerified
+ _objc_msgSend$recordLastLoggedMigrationGateOutcomeRawValue:
+ _objc_msgSend$refreshShouldStayRunning
+ _objc_msgSend$removalPending
+ _objc_msgSend$removalRequestedDuringGraphMigrationTransition
+ _objc_msgSend$removalRequestedDuringGraphMigrationTransitionIsTerminal
+ _objc_msgSend$removeInactiveAccount:terminalRemoval:
+ _objc_msgSend$rowsAlreadyGraphShaped
+ _objc_msgSend$rowsEmpty
+ _objc_msgSend$rowsFailed
+ _objc_msgSend$rowsNull
+ _objc_msgSend$rowsScanned
+ _objc_msgSend$rowsSkippedByPolicy
+ _objc_msgSend$rowsTranslated
+ _objc_msgSend$seedChangeSourceWatermarkFromExistingSources:inAccount:
+ _objc_msgSend$setAbortReason:
+ _objc_msgSend$setAccountKeysStartingUp:
+ _objc_msgSend$setActiveSyncDialectStorage:
+ _objc_msgSend$setAlreadyGraphShaped:
+ _objc_msgSend$setCancelled:
+ _objc_msgSend$setChangeItems:
+ _objc_msgSend$setChunkSize:
+ _objc_msgSend$setCommitted:
+ _objc_msgSend$setDatabaseSchemaVersion:
+ _objc_msgSend$setDeferredAccountAction:
+ _objc_msgSend$setDeferredAccountActionPriority:
+ _objc_msgSend$setDerivedGraphMigrationCutoverRequired:
+ _objc_msgSend$setDryRun:
+ _objc_msgSend$setFailed:
+ _objc_msgSend$setFatalFailure:
+ _objc_msgSend$setIsShuttingDown:
+ _objc_msgSend$setIsStartingUp:
+ _objc_msgSend$setKeepAliveCommitLock:
+ _objc_msgSend$setLastCommittedNeedToRunSequence:
+ _objc_msgSend$setLastLoggedMigrationGateOutcomeRawValueStorage:
+ _objc_msgSend$setNotesOutsideRootFolder:
+ _objc_msgSend$setPendingAccountInstanceWorkGroup:
+ _objc_msgSend$setPendingDeferredStartupActionsGroup:
+ _objc_msgSend$setPendingGraphMigrationTransition:
+ _objc_msgSend$setPendingGraphMigrationTransitionsGroup:
+ _objc_msgSend$setPrecondition:
+ _objc_msgSend$setProtocolKind:
+ _objc_msgSend$setRemovalPending:
+ _objc_msgSend$setRemovalRequestedDuringGraphMigrationTransition:
+ _objc_msgSend$setRemovalRequestedDuringGraphMigrationTransitionIsTerminal:
+ _objc_msgSend$setRowsAlreadyGraphShaped:
+ _objc_msgSend$setRowsEmpty:
+ _objc_msgSend$setRowsFailed:
+ _objc_msgSend$setRowsNull:
+ _objc_msgSend$setRowsScanned:
+ _objc_msgSend$setRowsSkippedByPolicy:
+ _objc_msgSend$setRowsTranslated:
+ _objc_msgSend$setShouldStayRunningLock:
+ _objc_msgSend$setStartupInProgress:
+ _objc_msgSend$setSyncState:forChangeSource:inAccount:
+ _objc_msgSend$setTotalNanos:
+ _objc_msgSend$setTransactionNanos:
+ _objc_msgSend$setTranslateNanos:
+ _objc_msgSend$setTranslated:
+ _objc_msgSend$setWriteNanos:
+ _objc_msgSend$shouldCancel
+ _objc_msgSend$shouldStayRunningLock
+ _objc_msgSend$shutdownWithGroup:
+ _objc_msgSend$sourceID
+ _objc_msgSend$startup:isGraphMigrationCutover:
+ _objc_msgSend$startupAfterGraphMigrationCutover:
+ _objc_msgSend$startupInProgress
+ _objc_msgSend$startupWithPermissionCheck:migratedData:isGraphMigrationCutover:
+ _objc_msgSend$syncEngineInstance:replayDeferredAccountAction:
+ _objc_msgSend$table
+ _objc_msgSend$targetID
+ _objc_msgSend$terminalRemoval
+ _objc_msgSend$terminalRemovalActionForAccount:
+ _objc_msgSend$terminalRemovalActionForDelegateAccount:
+ _objc_msgSend$totalNanos
+ _objc_msgSend$totalRowsFailed
+ _objc_msgSend$totalRowsTranslated
+ _objc_msgSend$transitionEngineInstance:toProtocolKind:requiresGraphCutover:
+ _objc_msgSend$translate:
+ _objc_msgSend$translateNanos
+ _objc_msgSend$translated
+ _objc_msgSend$tryBeginPendingGraphMigrationTransitionReportingRefusal:
+ _objc_msgSend$tryBeginStartupWindow
+ _objc_msgSend$updateDelegates:forParentAccountChange:terminalRemoval:
+ _objc_msgSend$waitForPendingAccountInstanceWorkUntilDeadline:
+ _objc_msgSend$writeNanos
+ _swift_cvw_initEnumMetadataMultiPayloadWithLayoutString
+ _swift_cvw_multiPayloadEnumGeneric_destructiveInjectEnumTag
+ _swift_cvw_multiPayloadEnumGeneric_getEnumTag
+ _swift_getEnumCaseMultiPayload
+ _swift_storeEnumTagMultiPayload
+ _swift_unknownObjectRelease_n
+ _symbolic $s12ExchangeSync18EXSWebPushReceiverP
+ _symbolic $s12ExchangeSync29EXSGSWebPushSubscriptionStoreP
+ _symbolic $s12ExchangeSync29EXSWebPushSubscriptionServiceP
+ _symbolic $ss10SetAlgebraP
+ _symbolic $ss25ExpressibleByArrayLiteralP
+ _symbolic $ss9OptionSetP
+ _symbolic SDySS_____G 12ExchangeSync14EXSWebPushKeysV
+ _symbolic SDySS_____G 12ExchangeSync18EXSWebPushEndpointV
+ _symbolic SDySS_____G 12ExchangeSync19EXSWebPushTransportC12WeakReceiver33_F599398DB63F31C565EB854B8922C17DLLC
+ _symbolic SDySS_____G 12ExchangeSync19EXSWebPushTransportC16PendingHandshake33_F599398DB63F31C565EB854B8922C17DLLV
+ _symbolic SDy_____SDy__________GG 12ExchangeSync29EXSGSWebPushSubscriptionScopeO AA0cD9RecordKeyV AA0cdeG0V
+ _symbolic SDy_____SbG 12ExchangeSync21EXSGSWebPushDataClassO
+ _symbolic SDy__________G 12ExchangeSync21EXSGSWebPushDataClassO 10Foundation4DateV
+ _symbolic SDy__________G 12ExchangeSync21EXSGSWebPushDataClassO AA06EXSWebD8EndpointV
+ _symbolic SS14subscriptionID______10expirationt 10Foundation4DateV
+ _symbolic SS3key______5valuet 12ExchangeSync30EXSGSWebPushSubscriptionRecordV
+ _symbolic SS9operation_t
+ _symbolic SS______t 12ExchangeSync19EXSWebPushTransportC16PendingHandshake33_F599398DB63F31C565EB854B8922C17DLLV
+ _symbolic SS______t 12ExchangeSync30EXSGSWebPushSubscriptionRecordV
+ _symbolic SSyKc
+ _symbolic Say_____G 12ExchangeSync20EXSWebPushChangeTypeO
+ _symbolic Say_____G 12ExchangeSync21EXSGSWebPushDataClassO
+ _symbolic Say_____G 12ExchangeSync29EXSWebPushNotificationPayloadO5Entry33_11C9EA1F0ECBCB5FB3573C385F075516LLV
+ _symbolic Say_____GSg 12ExchangeSync29EXSWebPushNotificationPayloadO5Entry33_11C9EA1F0ECBCB5FB3573C385F075516LLV
+ _symbolic Sayy_____y___________pGYbcG s6ResultOsRi_zRi0_zrlE 12ExchangeSync18EXSWebPushEndpointV s5ErrorP
+ _symbolic Sb9refreshed_t
+ _symbolic Sbyc
+ _symbolic So10EXSAccountC
+ _symbolic So22NSISO8601DateFormatterC
+ _symbolic So9OS_os_logC
+ _symbolic _____ 12ExchangeSync11EXSGSConfigO7WebPushO
+ _symbolic _____ 12ExchangeSync14EXSWebPushKeysV
+ _symbolic _____ 12ExchangeSync15EXSGSWebPushLogO
+ _symbolic _____ 12ExchangeSync16EXSGSLogCategoryO
+ _symbolic _____ 12ExchangeSync17EXSGSIdTranslatorC
+ _symbolic _____ 12ExchangeSync17EXSGSLogSubsystemO
+ _symbolic _____ 12ExchangeSync17EXSGSWebPushTopicV
+ _symbolic _____ 12ExchangeSync18EXSGSDownsyncScopeV
+ _symbolic _____ 12ExchangeSync18EXSWebPushEndpointV
+ _symbolic _____ 12ExchangeSync19EXSWebPushTransportC
+ _symbolic _____ 12ExchangeSync19EXSWebPushTransportC12WeakReceiver33_F599398DB63F31C565EB854B8922C17DLLC
+ _symbolic _____ 12ExchangeSync19EXSWebPushTransportC16PendingHandshake33_F599398DB63F31C565EB854B8922C17DLLV
+ _symbolic _____ 12ExchangeSync20EXSGSWebPushCoverageO
+ _symbolic _____ 12ExchangeSync20EXSGSWebPushCoverageO10AssessmentV
+ _symbolic _____ 12ExchangeSync20EXSWebPushChangeTypeO
+ _symbolic _____ 12ExchangeSync21EXSGSWebPushDataClassO
+ _symbolic _____ 12ExchangeSync21EXSGSWebPushRecordKeyV
+ _symbolic _____ 12ExchangeSync22EXSGSLogCategorySourceO
+ _symbolic _____ 12ExchangeSync23EXSAPSConnectionFactoryO
+ _symbolic _____ 12ExchangeSync23EXSGSOccurrenceResolverV
+ _symbolic _____ 12ExchangeSync23EXSGSWebPushCoordinatorC
+ _symbolic _____ 12ExchangeSync23EXSGSWebPushCoordinatorC12DependenciesV
+ _symbolic _____ 12ExchangeSync23EXSGSWebPushEligibilityO
+ _symbolic _____ 12ExchangeSync23EXSWebPushConfigurationV
+ _symbolic _____ 12ExchangeSync24EXSGSIdTranslationResultC
+ _symbolic _____ 12ExchangeSync24EXSGSPushDownsyncOutcomeO
+ _symbolic _____ 12ExchangeSync24EXSWebPushTransportErrorO
+ _symbolic _____ 12ExchangeSync25EXSGSIdTranslationOutcomeO
+ _symbolic _____ 12ExchangeSync25EXSGSWebPushIneligibilityO
+ _symbolic _____ 12ExchangeSync26EXSWebPushVapidKeyProviderC
+ _symbolic _____ 12ExchangeSync26EXSWebPushVapidKeyProviderC10CacheState33_6A506C5CC0FDE89847C953FF440BC446LLO
+ _symbolic _____ 12ExchangeSync26EXSWebPushVapidKeyProviderC6SourceO
+ _symbolic _____ 12ExchangeSync27EXSGSVapidPublicKeyProviderC
+ _symbolic _____ 12ExchangeSync27EXSGSVapidPublicKeyProviderC10CacheState33_4B04DF1C961A5D37B139A6F9D7B666D4LLO
+ _symbolic _____ 12ExchangeSync27EXSGSVapidPublicKeyProviderC6SourceO
+ _symbolic _____ 12ExchangeSync27EXSWebPushSubscriptionErrorO
+ _symbolic _____ 12ExchangeSync28EXSWebPushSubscriptionRecordV
+ _symbolic _____ 12ExchangeSync29EXSGSWebPushSubscriptionScopeO
+ _symbolic _____ 12ExchangeSync29EXSGSWebPushTransportProviderO
+ _symbolic _____ 12ExchangeSync29EXSWebPushNotificationPayloadO
+ _symbolic _____ 12ExchangeSync29EXSWebPushNotificationPayloadO5Entry33_11C9EA1F0ECBCB5FB3573C385F075516LLV
+ _symbolic _____ 12ExchangeSync29EXSWebPushNotificationPayloadO5Entry33_11C9EA1F0ECBCB5FB3573C385F075516LLV6AnyKeyV
+ _symbolic _____ 12ExchangeSync29EXSWebPushNotificationPayloadO5ParseV
+ _symbolic _____ 12ExchangeSync29EXSWebPushNotificationPayloadO8Envelope33_11C9EA1F0ECBCB5FB3573C385F075516LLV
+ _symbolic _____ 12ExchangeSync29EXSWebPushNotificationPayloadO8Envelope33_11C9EA1F0ECBCB5FB3573C385F075516LLV10CodingKeysO
+ _symbolic _____ 12ExchangeSync29EXSWebPushSubscriptionRequestV
+ _symbolic _____ 12ExchangeSync30EXSGSWebPushNotificationRouterO
+ _symbolic _____ 12ExchangeSync30EXSGSWebPushNotificationRouterO9NarrowingV
+ _symbolic _____ 12ExchangeSync30EXSGSWebPushSubscriptionRecordV
+ _symbolic _____ 12ExchangeSync30EXSGSWebPushSubscriptionRecordV5StateO
+ _symbolic _____ 12ExchangeSync31EXSGSRenewSubscriptionOperationV
+ _symbolic _____ 12ExchangeSync31EXSGSWebPushSubscriptionServiceC
+ _symbolic _____ 12ExchangeSync32EXSGSCreateSubscriptionOperationV
+ _symbolic _____ 12ExchangeSync32EXSGSCreateSubscriptionOperationV7CreatedV
+ _symbolic _____ 12ExchangeSync34EXSWebPushGraphSubscriptionServiceC
+ _symbolic _____ 12ExchangeSync37EXSGSInMemoryWebPushSubscriptionStoreC
+ _symbolic _____ 12ExchangeSync38EXSGSCalendarPermissionResourceBuilderO08DelegateD12UpdateActionO
+ _symbolic _____ s6UInt64V
+ _symbolic _____11requestedAt_t 10Foundation4DateV
+ _symbolic _____3key______5valuet 12ExchangeSync21EXSGSWebPushRecordKeyV AA0cd12SubscriptionE0V
+ _symbolic _____5since______5leaset 10Foundation4DateV s6UInt64V
+ _symbolic _____5since_t 10Foundation4DateV
+ _symbolic _____Sg 10Foundation4DataV
+ _symbolic _____Sg 12ExchangeSync14EXSWebPushKeysV
+ _symbolic _____Sg 12ExchangeSync16EXSGSRetryPolicyO6BudgetC
+ _symbolic _____Sg 12ExchangeSync19EXSWebPushTransportC16PendingHandshake33_F599398DB63F31C565EB854B8922C17DLLV
+ _symbolic _____Sg 12ExchangeSync30EXSGSWebPushSubscriptionRecordV
+ _symbolic _____Sg 12ExchangeSync32EXSGSAdoptNoteFolderMapOperationV6ResultV
+ _symbolic _____Sg 9GraphSync0aB12IdTranslatorO16TranslationErrorO
+ _symbolic _____Sg 9GraphSync0aB20EventMessageResourceV
+ _symbolic _____Sg 9GraphSync0aB20SubscriptionResourceV
+ _symbolic _____Sg 9GraphSync0aB20SubscriptionResourceV10TlsVersionO
+ _symbolic _____Sg 9GraphSync0aB22SubscriptionChangeTypeO
+ _symbolic _____Sg 9GraphSync0aB22VapidPublicKeyResourceV
+ _symbolic _____Sg 9GraphSync0aB30SubscriptionCollectionResponseV
+ _symbolic _____Sg 9GraphSync0aB9UserScopeO
+ _symbolic _____SgXw 12ExchangeSync19EXSWebPushTransportC
+ _symbolic _____SgXw 12ExchangeSync23EXSGSWebPushCoordinatorC
+ _symbolic _____SgXwz_Xx 12ExchangeSync19EXSWebPushTransportC
+ _symbolic _____SgXwz_Xx 12ExchangeSync23EXSGSWebPushCoordinatorC
+ _symbolic _____Sg_ABt 9GraphSync0aB9UserScopeO
+ _symbolic _____XDXMT 12ExchangeSync19EXSWebPushTransportC
+ _symbolic _____XDXMT 12ExchangeSync23EXSGSWebPushCoordinatorC
+ _symbolic _____XDXMT 12ExchangeSync34EXSWebPushGraphSubscriptionServiceC
+ _symbolic _____XMT 12ExchangeSync19EXSWebPushTransportC
+ _symbolic ______AAt 12ExchangeSync30EXSGSWebPushSubscriptionRecordV5StateO
+ _symbolic ___________SSShySSGtc 12ExchangeSync24EXSGSPushDownsyncOutcomeO AA18EXSGSDownsyncScopeV
+ _symbolic ___________t 12ExchangeSync21EXSGSWebPushDataClassO 10Foundation4DateV
+ _symbolic ___________t 12ExchangeSync21EXSGSWebPushRecordKeyV AA0cd12SubscriptionE0V
+ _symbolic ______p 12ExchangeSync29EXSGSWebPushSubscriptionStoreP
+ _symbolic ______p 9GraphSync0aB21UserScopedRequestableP
+ _symbolic ______pSg 12ExchangeSync24EXSAPSConnectionProtocolP
+ _symbolic ______pSgXw 12ExchangeSync18EXSWebPushReceiverP
+ _symbolic ______pSgyc 12ExchangeSync24EXSAPSConnectionProtocolP
+ _symbolic ______pyc 9GraphSync0aB8BindableP
+ _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync14EXSWebPushKeysV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync18EXSWebPushEndpointV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync19EXSWebPushTransportC12WeakReceiver33_F599398DB63F31C565EB854B8922C17DLLC
+ _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync19EXSWebPushTransportC16PendingHandshake33_F599398DB63F31C565EB854B8922C17DLLV
+ _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync30EXSGSWebPushSubscriptionRecordV
+ _symbolic _____y_____G s11_SetStorageC 12ExchangeSync21EXSGSWebPushDataClassO
+ _symbolic _____y_____G s11_SetStorageC So13EXSFolderTypeV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12ExchangeSync29EXSWebPushNotificationPayloadO5Entry33_11C9EA1F0ECBCB5FB3573C385F075516LLV6AnyKeyV
+ _symbolic _____y_____G s22KeyedDecodingContainerV 12ExchangeSync29EXSWebPushNotificationPayloadO8Envelope33_11C9EA1F0ECBCB5FB3573C385F075516LLV10CodingKeysO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12ExchangeSync21EXSGSWebPushDataClassO
+ _symbolic _____y_____G s23_ContiguousArrayStorageC 12ExchangeSync28EXSWebPushSubscriptionRecordV
+ _symbolic _____y_____SDy__________GG s18_DictionaryStorageC 12ExchangeSync29EXSGSWebPushSubscriptionScopeO AC0eF9RecordKeyV AC0efgI0V
+ _symbolic _____y_____SbG s18_DictionaryStorageC 12ExchangeSync21EXSGSWebPushDataClassO
+ _symbolic _____y__________G s18_DictionaryStorageC 12ExchangeSync21EXSGSWebPushDataClassO 10Foundation4DateV
+ _symbolic _____y__________G s18_DictionaryStorageC 12ExchangeSync21EXSGSWebPushDataClassO AC06EXSWebF8EndpointV
+ _symbolic _____y__________G s18_DictionaryStorageC 12ExchangeSync21EXSGSWebPushRecordKeyV AC0ef12SubscriptionG0V
+ _symbolic _____y___________pG s6ResultOsRi_zRi0_zrlE 12ExchangeSync18EXSWebPushEndpointV s5ErrorP
+ _symbolic _____y___________pGIeghn_ s6ResultOsRi_zRi0_zrlE 12ExchangeSync18EXSWebPushEndpointV s5ErrorP
+ _symbolic _____yc 10Foundation4DateV
+ _symbolic _____yy_____y___________pGYbcG s23_ContiguousArrayStorageC s6ResultOsRi_zRi0_zrlE 12ExchangeSync18EXSWebPushEndpointV s5ErrorP
+ _symbolic ySd_yyYbctc
+ _symbolic y______pc s5ErrorP
+ _symbolic y_____y___________pGYbc s6ResultOsRi_zRi0_zrlE 12ExchangeSync18EXSWebPushEndpointV s5ErrorP
+ _symbolic ypXp
+ _symbolic yyycc
+ _type_layout_string 12ExchangeSync14EXSWebPushKeysV
+ _type_layout_string 12ExchangeSync17EXSGSWebPushTopicV
+ _type_layout_string 12ExchangeSync18EXSGSDownsyncScopeV
+ _type_layout_string 12ExchangeSync18EXSWebPushEndpointV
+ _type_layout_string 12ExchangeSync20EXSGSWebPushCoverageO10AssessmentV
+ _type_layout_string 12ExchangeSync21EXSGSWebPushRecordKeyV
+ _type_layout_string 12ExchangeSync22EXSGSLogCategorySourceO
+ _type_layout_string 12ExchangeSync23EXSGSOccurrenceResolverV
+ _type_layout_string 12ExchangeSync23EXSGSWebPushCoordinatorC12DependenciesV
+ _type_layout_string 12ExchangeSync23EXSWebPushConfigurationV
+ _type_layout_string 12ExchangeSync24EXSWebPushTransportErrorO
+ _type_layout_string 12ExchangeSync27EXSWebPushSubscriptionErrorO
+ _type_layout_string 12ExchangeSync29EXSGSWebPushSubscriptionScopeO
+ _type_layout_string 12ExchangeSync29EXSWebPushNotificationPayloadO5Entry33_11C9EA1F0ECBCB5FB3573C385F075516LLV
+ _type_layout_string 12ExchangeSync29EXSWebPushNotificationPayloadO5Entry33_11C9EA1F0ECBCB5FB3573C385F075516LLV6AnyKeyV
+ _type_layout_string 12ExchangeSync29EXSWebPushNotificationPayloadO5ParseV
+ _type_layout_string 12ExchangeSync29EXSWebPushNotificationPayloadO8Envelope33_11C9EA1F0ECBCB5FB3573C385F075516LLV
+ _type_layout_string 12ExchangeSync30EXSGSWebPushNotificationRouterO9NarrowingV
- -[EXSAccountManager evaluateOurNeedToRun]
- -[EXSDataManager(Folders) _parentFolderAssociatedWithChangeItem:]
- -[EXSSyncEngine removeInactiveAccount:]
- -[EXSSyncEngine updateDelegates:forParentAccountChange:]
- -[EXSSyncEngineInstance _createAndRegisterSyncProtocol]
- -[EXSSyncEngineInstance _startupSyncProtocol]
- -[EXSSyncEngineInstance startupWithPermissionCheck:migratedData:]
- GCC_except_table142
- GCC_except_table24
- GCC_except_table30
- GCC_except_table51
- GCC_except_table72
- GCC_except_table76
- _NSSearchPathForDirectoriesInDomains
- _OBJC_CLASS_$__TtC12ExchangeSync28EXSAPNSPushServiceConnection
- _OBJC_METACLASS_$__TtC12ExchangeSync28EXSAPNSPushServiceConnection
- __DATA__TtC12ExchangeSync16EXSPushDataStore
- __DATA__TtC12ExchangeSync16EXSWebPushPlugin
- __DATA__TtC12ExchangeSync19EXSAPNSPushProvider
- __DATA__TtC12ExchangeSync20EXSGSWebPushConsumer
- __DATA__TtC12ExchangeSync23EXSAPSConnectionFactory
- __DATA__TtC12ExchangeSync28EXSAPNSPushServiceConnection
- __DATA__TtC12ExchangeSync35GraphSyncSubscriptionManagerAdapter
- __IVARS__TtC12ExchangeSync16EXSPushDataStore
- __IVARS__TtC12ExchangeSync16EXSWebPushPlugin
- __IVARS__TtC12ExchangeSync19EXSAPNSPushProvider
- __IVARS__TtC12ExchangeSync20EXSGSWebPushConsumer
- __IVARS__TtC12ExchangeSync28EXSAPNSPushServiceConnection
- __IVARS__TtC12ExchangeSync35GraphSyncSubscriptionManagerAdapter
- __METACLASS_DATA__TtC12ExchangeSync16EXSPushDataStore
- __METACLASS_DATA__TtC12ExchangeSync16EXSWebPushPlugin
- __METACLASS_DATA__TtC12ExchangeSync19EXSAPNSPushProvider
- __METACLASS_DATA__TtC12ExchangeSync20EXSGSWebPushConsumer
- __METACLASS_DATA__TtC12ExchangeSync23EXSAPSConnectionFactory
- __METACLASS_DATA__TtC12ExchangeSync28EXSAPNSPushServiceConnection
- __METACLASS_DATA__TtC12ExchangeSync35GraphSyncSubscriptionManagerAdapter
- __OBJC_$_INSTANCE_METHODS_EXSDataManager(Folders|Folders_Private|Items|Items_Private|Migration|Attachments|ChangeItems)
- __OBJC_$_INSTANCE_METHODS_EXSGSSyncProtocol(ExchangeSync|ExchangeSync|ExchangeSync)
- __OBJC_$_INSTANCE_METHODS__TtC12ExchangeSync28EXSAPNSPushServiceConnection(ExchangeSync)
- __OBJC_CLASS_PROTOCOLS_$_EXSGSSyncProtocol(ExchangeSync|ExchangeSync|ExchangeSync)
- __OBJC_CLASS_PROTOCOLS_$__TtC12ExchangeSync28EXSAPNSPushServiceConnection(ExchangeSync)
- ___33-[EXSSyncEngineInstance shutdown]_block_invoke
- ___33-[EXSSyncEngineInstance startup:]_block_invoke
- ___50-[EXSSyncEngine accountShutdown:isRemovedAccount:]_block_invoke
- ___block_descriptor_57_e8_32s40r48r_e5_v8?0l
- ___swift_assign_boxed_opaque_existential_1
- ___swift_async_cont_functlets
- ___swift_async_entry_functlets
- ___swift_async_ret_functlets
- ___swift_memcpy138_8
- ___unnamed_2
- __swift_closure_destructor.20Tm
- __swift_implicitisolationactor_to_executor_cast
- _associated conformance 12ExchangeSync08EXSGraphB16PushServiceErrorO10Foundation09LocalizedF0AAs0F0
- _associated conformance 12ExchangeSync15EXSWebPushErrorO10Foundation09LocalizedE0AAs0E0
- _associated conformance 12ExchangeSync15EXSWebPushErrorOSHAASQ
- _associated conformance 12ExchangeSync20EXSAPNSProviderErrorO10Foundation09LocalizedD0AAs0D0
- _associated conformance 12ExchangeSync22EXSWebPushResourceTypeOSHAASQ
- _associated conformance 12ExchangeSync22EXSWebPushResourceTypeOs12CaseIterableAA8AllCasessADP_Sl
- _flat unique So21APSConnectionDelegate_p
- _get_enum_tag_for_layout_string 12ExchangeSync08EXSGraphB16PushServiceErrorO
- _get_enum_tag_for_layout_string 12ExchangeSync20EXSAPNSProviderErrorO
- _objc_msgSend$_createAndRegisterSyncProtocol
- _objc_msgSend$_startupSyncProtocol
- _objc_msgSend$accountShutdown:isRemovedAccount:
- _objc_msgSend$evaluateOurNeedToRun
- _objc_msgSend$firePushChannelStarted
- _objc_msgSend$firePushChannelStopped
- _objc_msgSend$isExchangeOnline
- _objc_msgSend$newSyncProtocolInstanceForAccount:dataManager:dispatchWorkloop:
- _objc_msgSend$reEmitFolderAsAdded:
- _objc_msgSend$removeInactiveAccount:
- _objc_msgSend$startupWithPermissionCheck:migratedData:
- _objc_msgSend$stringByAppendingPathComponent:
- _objc_msgSend$updateDelegates:forParentAccountChange:
- _swift_continuation_await
- _swift_continuation_init
- _swift_defaultActor_deallocate
- _swift_defaultActor_destroy
- _swift_defaultActor_initialize
- _swift_isaMask
- _swift_taskGroup_wait_next_throwing
- _swift_task_alloc
- _swift_task_create
- _swift_task_dealloc
- _swift_task_switch
- _symbolic $s12ExchangeSync12DataConsumerP
- _symbolic $s12ExchangeSync14ResourceMapperP
- _symbolic $s12ExchangeSync16PushNotificationP
- _symbolic $s12ExchangeSync18WebPushSubscribingP
- _symbolic $s12ExchangeSync19SubscriptionManagerP
- _symbolic $s12ExchangeSync24EXSPushServiceConnectionP
- _symbolic $s12ExchangeSync24PushNotificationProviderP
- _symbolic BD
- _symbolic SDyS2SG
- _symbolic SDySS_____G 12ExchangeSync19EXSPushSubscriptionV
- _symbolic SDySS_____G 12ExchangeSync23WebPushSubscriptionInfoV
- _symbolic SDySS______pG 12ExchangeSync12DataConsumerP
- _symbolic SDySS______pG 12ExchangeSync22EXSAPSURLTokenProtocolP
- _symbolic SS3key______5valuet 12ExchangeSync19EXSPushSubscriptionV
- _symbolic SS3key_______p5valuet 12ExchangeSync22EXSAPSURLTokenProtocolP
- _symbolic SS5topic_______pSg10underlyingt s5ErrorP
- _symbolic SS5topic_t
- _symbolic SS______t 10Foundation3URLV
- _symbolic Say_____G 12ExchangeSync22EXSWebPushResourceTypeO
- _symbolic Sb8inserted_SS17memberAfterInsertt
- _symbolic ScA_pSg
- _symbolic ScCy___________pG 12ExchangeSync25WebPushSubscriptionResultV s5ErrorP
- _symbolic ScCyyt______pG s5ErrorP
- _symbolic ScPSg
- _symbolic Scgyyt______pG s5ErrorP
- _symbolic _____ 12ExchangeSync05GraphB26SubscriptionManagerAdapterC
- _symbolic _____ 12ExchangeSync08EXSGraphB16PushServiceErrorO
- _symbolic _____ 12ExchangeSync15EXSWebPushErrorO
- _symbolic _____ 12ExchangeSync16EXSPushDataStoreC
- _symbolic _____ 12ExchangeSync16EXSWebPushPluginC
- _symbolic _____ 12ExchangeSync19EXSAPNSPushProviderC
- _symbolic _____ 12ExchangeSync20EXSAPNSProviderErrorO
- _symbolic _____ 12ExchangeSync20EXSGSWebPushConsumerC
- _symbolic _____ 12ExchangeSync21DefaultResourceMapper33_2D7730C1940426EFB80AB116A2BE92EELLV
- _symbolic _____ 12ExchangeSync22EXSWebPushResourceTypeO
- _symbolic _____ 12ExchangeSync23EXSAPNSPushNotificationV
- _symbolic _____ 12ExchangeSync23EXSAPSConnectionFactoryC
- _symbolic _____ 12ExchangeSync23WebPushSubscriptionInfoV
- _symbolic _____ 12ExchangeSync25WebPushSubscriptionResultV
- _symbolic _____ 12ExchangeSync28EXSAPNSPushServiceConnectionC
- _symbolic _____ 9GraphSync0aB19SubscriptionManagerC
- _symbolic _____Sg 12ExchangeSync16EXSPushDataStoreC
- _symbolic _____Sg 12ExchangeSync19EXSPushSubscriptionV
- _symbolic _____SgXw 12ExchangeSync28EXSAPNSPushServiceConnectionC
- _symbolic _____SgXwz_Xx 12ExchangeSync28EXSAPNSPushServiceConnectionC
- _symbolic _____XDXMT 12ExchangeSync19EXSAPNSPushProviderC
- _symbolic ___________pIeggzo_ 10Foundation4DataV s5ErrorP
- _symbolic ______p 12ExchangeSync14ResourceMapperP
- _symbolic ______p 12ExchangeSync16PushNotificationP
- _symbolic ______p 12ExchangeSync24EXSAPSConnectionProtocolP
- _symbolic ______p 12ExchangeSync24EXSPushServiceConnectionP
- _symbolic ______pIegg_ s5ErrorP
- _symbolic ______pSg 12ExchangeSync12DataConsumerP
- _symbolic ______pSg 12ExchangeSync14ResourceMapperP
- _symbolic ______pSg 12ExchangeSync19SubscriptionManagerP
- _symbolic ______pSg 12ExchangeSync24EXSPushServiceConnectionP
- _symbolic ______pSg 12ExchangeSync24PushNotificationProviderP
- _symbolic ______pSg So21APSConnectionDelegateP
- _symbolic ______pSg10underlying_t s5ErrorP
- _symbolic ______pytIegnr_ s5ErrorP
- _symbolic _____m 12ExchangeSync27EXSGSEventPropertiesBuilderO
- _symbolic _____m 12ExchangeSync29EXSGSSearchDirectoryOperationV
- _symbolic _____m 12ExchangeSync33EXSGSAddCalendarDelegateOperationV
- _symbolic _____m 12ExchangeSync33EXSGSCalendarEventResourceBuilderO
- _symbolic _____m 12ExchangeSync34EXSGSRemoveMeetingRequestOperationC
- _symbolic _____m 12ExchangeSync35EXSGSGetCalendarPermissionOperationV
- _symbolic _____m 12ExchangeSync36EXSGSGetCalendarEventsDeltaOperationV
- _symbolic _____m 12ExchangeSync37EXSGSGetCalendarAvailabilityOperationV
- _symbolic _____m 12ExchangeSync37EXSGSListCalendarPermissionsOperationV
- _symbolic _____m 12ExchangeSync38EXSGSCreateCalendarPermissionOperationV
- _symbolic _____m 12ExchangeSync38EXSGSDeleteCalendarPermissionOperationV
- _symbolic _____m 12ExchangeSync38EXSGSUpdateCalendarPermissionOperationV
- _symbolic _____ySS_____G s18_DictionaryStorageC 10Foundation3URLV
- _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync19EXSPushSubscriptionV
- _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync20EXSGSWebPushConsumerC
- _symbolic _____ySS_____G s18_DictionaryStorageC 12ExchangeSync23WebPushSubscriptionInfoV
- _symbolic _____ySS______pG s18_DictionaryStorageC 12ExchangeSync12DataConsumerP
- _symbolic _____ySS______pG s18_DictionaryStorageC 12ExchangeSync22EXSAPSURLTokenProtocolP
- _symbolic _____yYaYbKc 10Foundation4DataV
- _symbolic _____y_____G s23_ContiguousArrayStorageC 12ExchangeSync19EXSPushSubscriptionV
- _symbolic _____yt______pIegnrzo_ 10Foundation4DataV s5ErrorP
- _symbolic y_____KcSg 10Foundation4DataV
- _symbolic y______pcSg s5ErrorP
- _symbolic ytIeAgHr_
- _type_layout_string 12ExchangeSync08EXSGraphB16PushServiceErrorO
- _type_layout_string 12ExchangeSync20EXSAPNSProviderErrorO
- _type_layout_string 12ExchangeSync23EXSAPNSPushNotificationV
- _type_layout_string 12ExchangeSync23WebPushSubscriptionInfoV
- _type_layout_string 12ExchangeSync25WebPushSubscriptionResultV
CStrings:
+ " request returned an unexpected response type"
+ "!"
+ "$"
+ "$batch %{public}s chunk failed with no confirmed deletes; abandoning %ld remaining id(s) as failed rather than re-attempting a server-wide fault"
+ "$batch %{public}s did not confirm %ld of %ld delete(s); local rows kept for the next drain"
+ "$batch %{public}s failed authorization (HTTP 401) on %ld sub-request(s) and renewal was unavailable or already spent (requestID=%{public}s)"
+ "$batch %{public}s retrying failed sub-request(s) after reactive credential renewal"
+ "$batch %{public}s skipping reactive renewal — account is unauthenticated"
+ "$batch %{public}s throttled (HTTP 429) on %ld sub-request(s); over inline budget or retries exhausted"
+ "$batch %{public}s throttled (HTTP 429) on %ld sub-request(s); waiting %{public}.*fs then retrying just those"
+ "$batch delete failed for the whole chunk (httpStatus=%{public}s requestID=%{public}s); %ld id(s) keep their local rows and retry next cycle"
+ "$batch hydration failed non-transiently (httpStatus=%{public}s requestID=%{public}s); dropping %ld id(s) this round, cursor will advance — they re-hydrate on next change"
+ "$batch hydration sub-request(s) failed deterministically for %ld id(s) (status:requestID=%{public}s); dropping them, they re-hydrate on next change"
+ "$batch hydration sub-response body failed to decode for %ld id(s) (requestIDs=%{public}s); dropping them, they re-hydrate on next change"
+ "$batch hydration sub-response missing from envelope for %ld id(s) (externalIDs=%{public}s); dropping them, they re-hydrate on next change"
+ "%@|%@"
+ "%{private}s"
+ "%{public}ld event(s) reported attachments with no inline collection; leaving their cached attachments untouched (reconverges on next change)"
+ "%{public}s %{public}s"
+ "%{public}s %{public}s confirmed invalid delta sync state (httpStatus=%{public}s graphErrorCode=%{public}s requestID=%{public}s pagesHydrated=%ld pagesPersisted=%ld); cursor clear %{public}s to re-seed next cycle"
+ "%{public}s %{public}s delta round complete: pages=%ld items=%ld skipped=%ld cursor=%{public}s reconciled=%{public}s"
+ "%{public}s %{public}s starting %{public}s delta round: maxpagesize=%{public}s"
+ "%{public}s : page count: %ld, items retrieved: %ld, cursor: %{public}s, pageSize: %ld"
+ "%{public}s account=%{public}s %{public}s delta failure (transient or mid-progress; next cycle resumes): kind=%{public}s httpStatus=%{public}s graphErrorCode=%{public}s requestID=%{public}s pagesHydrated=%ld pagesPersisted=%ld cursorPresent=%{public}s details=%{private}s"
+ "%{public}s delta page %ld: items=%ld skipped=%ld total=%ld totalSkipped=%ld"
+ "%{public}s delta page limit guard has been exceeded."
+ "%{public}s failed: %{private}s"
+ "%{public}s gateway/request timeout on page %ld at maxpagesize=%ld — halving to %ld and retrying the same cursor"
+ "%{public}s hydration skipped %ld id(s) as 404/410 (deletion race), %ld as empty-bodied 2xx, and dropped %ld on non-transient errors (cursor advances; re-hydrate on next change)"
+ "%{public}s non-transient delta failure — does not trigger a list re-sync: account=%{public}s %{public}s kind=%{public}s httpStatus=%{public}s graphErrorCode=%{public}s requestID=%{public}s pagesHydrated=%ld pagesPersisted=%ld cursorPresent=%{public}s unexpectedType=%{public}s details=%{private}s"
+ "%{public}s returned error %{private}s"
+ "%{public}s returned no changeKey for %{public}s; keeping the stored token"
+ "%{public}s skipped — item already has externalID %{public}s"
+ "%{public}s skipped: missing externalID on change item %ld"
+ "%{public}s skipped: parent folder unresolved for change item %ld: %{private}s"
+ "%{public}s succeeded on server but failed to refresh local externalChangeKey for %{public}s"
+ "%{public}s succeeded on server but failed to update local database"
+ "%{public}s terminal page had no continuation link (%{public}s) — full re-seed next cycle"
+ "%{public}s: %{public}s"
+ "%{public}s: buildDeleteRequest called outside the performDelete pipeline"
+ "%{public}s: item %{public}s gone on server (%{public}s); treating as success"
+ "%{public}s: no updatable fields specified, skipping network call"
+ "%{public}s: refreshed item %{public}s after recoverable failure; retrying PATCH once"
+ ", re-emitting unchanged"
+ "-shutdownWithGroup: reentered for account %{public}@ while its own startup is still in progress -- this instance's state is about to be corrupted."
+ "/me/calendars/{id}/events"
+ "/me/todo/lists/{id}/tasks"
+ "A delta request for operation \"%{public}s\" has returned %ld consecutive blank pages."
+ "Account %{public}@ was added concurrently. Not adding it twice."
+ "Account %{public}@ was restarted concurrently. Not adding it twice."
+ "Account is paused pending Graph migration verification."
+ "Add Calendar Delegate Operation returned error %{private}s"
+ "Adding item with no resolvable parent folder; storing folder_id=-1 [externalParentFolderID=%{public}@ internalParentFolderID=%{private}@]"
+ "Ambiguous occurrence match for master %{public}s: %{public}ld candidates"
+ "An add for this delegate on account %{public}@ is already in flight. Not creating a second one."
+ "Another caller is fetching the VAPID public key; ask again next pass"
+ "Applied folder map revision %ld from %{public}s (%ld folder(s), hash %{public}s): %ld row change(s), %ld removal(s), %ld kept%{public}s%{public}s"
+ "Attachment '%{private}s' is %ld bytes — exceeds the %ld-byte single-request upload limit"
+ "Attachment uploaded successfully, server ID: %{public}s"
+ "Authored TZ original=%{private}s wire=%{private}s did not resolve; falling back to current"
+ "Availability request missing requestID; dropping (emails=%{public}ld)"
+ "B16@?0@\"EXSAccount\"8"
+ "B32@?0@\"PQLConnection\"8@\"NSNumber\"16@24"
+ "CREATE TABLE IF NOT EXISTS exs_graph_migration_verified (id INTEGER PRIMARY KEY CHECK (id = 1), verified_at bigint, housekeeping_completed_at bigint, converted_at bigint, conversion_attempt_count integer, conversion_last_failure_at bigint)"
+ "Calendar permission operation (type=%ld) returned error %{private}s"
+ "Calendar upsync: %{public}s has no authored time zone (floating; specified=%{bool,public}d); declaring the fallback zone"
+ "Calendar upsync: %{public}s time zone is an empty string; declaring the fallback zone"
+ "Cannot check for legacy per-account tables: global database is closed"
+ "Cannot download attachment %{public}s: missing parent item external ID"
+ "Collection already deleted on server, treating as success (op=%{public}s, externalID=%{public}s)"
+ "Conflict changeKey refresh GET failed inconclusively for %{public}s: %{private}s"
+ "Conflict changeKey refresh for %{public}s found the note soft-deleted — declining the retry"
+ "Conflict changeKey refresh for %{public}s yielded no usable changeKey"
+ "Conflict changeKey refresh for %{public}s yielded no usable etag"
+ "Conflict changeKey refresh for %{public}s yielded no usable response"
+ "Could not derive originalStartDate from occurrenceId %{public}s"
+ "Could not parse Order extended property value %{public}s as an integer for calendar folder."
+ "Couldn't create Graph migration verified row in sync engine database: %{public}@"
+ "Couldn't create graph migration verified table in sync engine database: %{public}@"
+ "Couldn't record %@ in sync engine database: %{public}@"
+ "Couldn't refetch live parent ACAccount for delegate %{public}@: %{public}@ %ld"
+ "Create Subscription"
+ "Created note folder %{public}s"
+ "DataConsumer-%"
+ "Delete Subscription"
+ "Deleting %ld stale note(s) confirmed gone server-side that were pinning a refused folder removal"
+ "Deleting attachment %{public}s from item %{public}s"
+ "Delta operation %{public}s is configured with a list type that is not GraphSyncResponsive."
+ "Detached item %@ names no parent item"
+ "Directory search did not return any results. %{private}s"
+ "Directory search returned %{public}ld results"
+ "Download failed for attachment %{public}s: %{private}s"
+ "Downloaded attachment %{public}s (%ld bytes) to %{public}s"
+ "Dropping note folder map entry whose id collides with the synthetic folder %{public}s"
+ "Dropping unparseable cancelledOccurrence OID %{public}s"
+ "Dropping unparseable travel time extended property for event %{public}s"
+ "EXSAccountManager: discarding a stale keep-alive evaluation; a fresher one already committed."
+ "EXSDataConsumerInstance: abandoning a data class re-enable -- the instance was torn down (or replaced) while waiting for the consumer to become ready."
+ "EXSDataConsumerInstance: ignoring a full resync request from a consumer this instance no longer owns (caller %{public}@, current %{public}@). Skipping the reset and the folder repush together."
+ "EXSEWSSyncProtocol is tearing down."
+ "EXSGSAttachmentManager initialized for accountKey=%{public}s"
+ "EXSGSAttachmentXPCRequest.addRequestID called after finish for attachmentUUID=%{public}s requestID=%{public}s"
+ "EXSGSAttachmentXPCRequest.downloadProgressed called after finish for attachmentUUID=%{public}s"
+ "EXSGSAttachmentXPCRequest.finish called twice for attachmentUUID=%{public}s"
+ "EXSGSConflictResolvingUpdateOperation"
+ "EXSGSDeleteItemOperationTests"
+ "EXSGSGetMeetingRequestItemsOperation failed (non-fatal): %{private}s"
+ "EXSGSGetMeetingRequestItemsOperation found %ld stale invitation(s) for event %{public}s"
+ "EXSGSMigrationGate"
+ "EXSGSMigrationPausedSyncProtocol"
+ "EXSGSNoteFolderMetadata"
+ "EXSGSRemoveMeetingRequestOperation failed (non-fatal): %{private}s"
+ "EXSGSRemoveMeetingRequestOperation: cleanup incomplete for event %{public}s — at least one stale meeting-request message could not be removed"
+ "EXSSyncEngine: Graph migration gate restart failed for account %{public}@."
+ "EXSSyncEngine: Graph migration gate transition for account %{public}@ (new kind %ld), cycling %lu delegate(s)."
+ "EXSSyncEngine: a concurrent start is already in flight for account %{public}@; not starting a second instance."
+ "EXSSyncEngine: a failed startup for account %{public}@ found its own instance now running; leaving the entry in place."
+ "EXSSyncEngine: a failed startup for account %{public}@ no longer owns its dictionary slot; leaving it alone."
+ "EXSSyncEngine: account %{public}@ disabled for every interesting dataclass during a Graph migration gate transition -- not restarting."
+ "EXSSyncEngine: account action %ld for account %{public}@ was superseded by a more recent action already deferred for its startup window."
+ "EXSSyncEngine: async account work drained during the shutdown timeout window; proceeding."
+ "EXSSyncEngine: declining to replay account action %ld for account %{public}@ -- the daemon is shutting down and this action would start or restart the account."
+ "EXSSyncEngine: deferring account action %ld for account %{public}@, its startup is still in progress."
+ "EXSSyncEngine: deferring shutdown/removal for account %{public}@, Graph migration gate transition in flight."
+ "EXSSyncEngine: delegate add for account %{public}@ was deferred behind an in-flight startup; it will be applied when that startup finishes. Replying with its source identifier, which is already durable."
+ "EXSSyncEngine: delegate removal for account %{public}@ was deferred behind an in-flight startup; replying accepted, the removal will complete when that startup finishes."
+ "EXSSyncEngine: discarding a stale keep-alive evaluation; a fresher one already committed."
+ "EXSSyncEngine: honoring a removal deferred during a Graph migration gate transition for account %{public}@."
+ "EXSSyncEngine: not cycling delegate account %{public}@ for its parent's Graph migration gate transition -- its own startup is still in progress."
+ "EXSSyncEngine: not handing out the instance for account %{public}@ -- a removal is recorded against it and has not been replayed yet."
+ "EXSSyncEngine: not handing out the instance for account %{public}@ -- it is not running (starting up, shut down, or mid-transition)."
+ "EXSSyncEngine: refusing account action %ld for account %{public}@ -- the daemon is shutting down and this action would start or restart the account."
+ "EXSSyncEngine: replaying account action %ld deferred during startup of account %{public}@."
+ "EXSSyncEngine: shutdown proceeding with a Graph migration gate transition still in flight after 10s."
+ "EXSSyncEngine: shutdown proceeding with async account work still in flight (deferred startup-window action: %{public}s, Graph migration gate transition: %{public}s)."
+ "EXSSyncEngine: transition claim refused for account %{public}@ because a transition is already in flight; that one will run the cutover."
+ "EXSSyncEngine: transition claim refused for account %{public}@ but its startup window had already closed; not recording a retry."
+ "EXSSyncEngine: transition claim refused for account %{public}@; a real account action is already deferred for its window, so that one will drive the retry."
+ "EXSSyncEngine: transition claim refused for account %{public}@; recorded an account change into its open startup window so the cutover is retried."
+ "EXSSyncEngineInstance: account %@ needs both an EventKit calendar-data migration and a Graph migration cutover in the same startup -- taking the calendar-data migration post-startup path."
+ "EXSSyncEngineInstance: dropping a plain shutdown for account %{public}@ -- a removal is already recorded for this startup window and does strictly more work."
+ "EXSSyncEngineInstance: dropping account action %ld deferred during startup of account %{public}@ -- no engine to replay it to."
+ "EXSSyncEngineInstance: dropping deferred account action %ld for account %{public}@ -- a higher-priority action is already recorded for this startup window."
+ "EXSSyncEngineInstance: not recording a non-clobbering account action for %{public}@ -- a more recent action is already deferred for this startup window and will be handled on its own merits."
+ "EXSSyncEngineInstance: refusing to start up an instance with no account."
+ "EXSSyncEngineInstance: startup already in progress for account %{public}@, not starting a second one."
+ "EXSSyncProtocol: discarding %lu change item(s) up to change %ld after a failed push; the watermark advances past them and they will not be retried (change source %{public}@)"
+ "EXSSyncProtocol: push drain discarded %lu change item(s) in total, first change %ld, last change %ld (change source %{public}@)"
+ "EXSSyncProtocol: reached %lu per-item discard log lines in this drain; suppressing the rest, see the drain total below (change source %{public}@)"
+ "EXSXPCInterfaceImplementation: Received an XPC call accountChangedWithType:accountId: changeType=%ld accountId=%{public}@"
+ "Exception %{public}s of master %{public}s arrived as a tombstone; dropping"
+ "Exception %{public}s of master %{public}s has neither a usable originalStart nor a parseable occurrenceId; cannot name its slot, so its detachment may be removed"
+ "Exception hydration failed; using the masters' inline entries (attachments and extended properties reconverge on the next change). httpStatus=%{public}ld requestID=%{public}s reason=%{private}s"
+ "Exception resource %{public}s has no seriesMasterId (unexpected: MS Graph contract requires it on every exception); dropping to avoid duplicating against the master's rule expansion."
+ "ExchangeGraphMigrationExchangeSync"
+ "ExchangeSync.EXSGSIdTranslationResult"
+ "ExchangeSync.EXSWebPushTransport"
+ "Executing %{public}s"
+ "Executing %{public}s for change item %ld"
+ "Executing search user list (directory) operation for search query %{private}s"
+ "Expected GraphSyncEventResource from cancelledOccurrences probe GET"
+ "Failed to clear the change token after a resync teardown. The next drain may push the teardown to the server as deletions."
+ "Failed to echo note folder id %{public}s to the consumer"
+ "Failed to expand resource for hydration operation %{public}s (page advances): %{private}s"
+ "Failed to generate web push subscriber keys"
+ "Failed to mark the subtree of note folder %{public}s deleted — peers may promote its children to the root"
+ "Failed to persist %{public}ld exception(s) across %{public}ld master(s) in folder %{public}s; they reconverge on each master's next change"
+ "Failed to persist resolved occurrence identifiers for %{public}s"
+ "Failed to record the distinguished task list; folder update and delete guards will not fire"
+ "Failed to remove stale attachment file %{public}s: %{private}s"
+ "Failed to remove stale paused change source for account %{public}@ while transitioning to Graph."
+ "Failed to retrieve item count for operation %{public}s: %{private}s"
+ "Failed to store the fresh changeKey for folder map carrier note %{public}s"
+ "Folder map carrier %{public}s is gone server-side; trying another"
+ "Folder map publish owed but nothing publishable is stored (adopted=%{public}s)"
+ "Folder map published to note %{public}s but the response carried no usable changeKey; the stored key is now stale, so this note will re-hydrate every round until the next write"
+ "Folder map revision %ld abandoned: note %{public}s already carries revision %ld (hash %{public}s)"
+ "Folder map revision %ld not published: no usable carrier in %ld attempt(s)"
+ "Folder not found for change item ID: "
+ "Get VAPID Public Key"
+ "Graph ID migration column %{public}@.%{public}@: scanned=%{public}lu translated=%{public}lu null=%{public}lu empty=%{public}lu alreadyGraph=%{public}lu skipped=%{public}lu failed=%{public}lu"
+ "Graph ID migration for account %{public}@ rolled back: %{public}@"
+ "Graph ID migration for account %{public}@ translated zero identifiers. On a populated store that means the conversion did not run; also expected on an empty store or a cancelled run."
+ "Graph ID migration for account %{public}@: dryRun=%{public}d committed=%{public}d cancelled=%{public}d translated=%{public}lu failed=%{public}lu totalMs=%{public}.1f"
+ "Graph ID migration refused for account %{public}@: precondition %ld (schemaVersion=%ld)"
+ "Graph Sync: %ld note(s) name a folder no map described — homing to the default folder, which does not self-heal"
+ "Graph Sync: %ld note(s) pinning a folder removal answered inconclusively — keeping those rows"
+ "Graph Sync: %{public}ld sync inactive (flag/dataclass); skipping delta for folder %{private}s"
+ "Graph Sync: %{public}s failed - %{public}s httpStatus=%{public}s retryAfter=%{public}s requestID=%{public}s"
+ "Graph Sync: %{public}s proactive credential renewal (expires in %{public}.*fs, lead=%{public}.*fs)"
+ "Graph Sync: %{public}s retrying after %{public}.*fs backoff (attempt %{public}ld)"
+ "Graph Sync: %{public}s retrying after reactive credential renewal"
+ "Graph Sync: %{public}s skipping reactive renewal — account is unauthenticated"
+ "Graph Sync: %{public}s succeeded"
+ "Graph Sync: Calendar delta sync completed: %ld page(s), %ld event(s), %ld skipped (unchanged)"
+ "Graph Sync: Executing %{public}s for change item %ld"
+ "Graph Sync: Notes delta sync persisted %ld notes across %ld page(s), %ld skipped (unchanged)"
+ "Graph Sync: Operation failed - %{public}s requestID=%{public}s"
+ "Graph Sync: Performing delta sync for folder %{private}s (token: %{public}s)"
+ "Graph Sync: Performing notes delta sync for folder %{private}s (token: %{public}s)"
+ "Graph Sync: Performing task delta sync for folder %{private}s (token: %{public}s)"
+ "Graph Sync: Tasks delta sync completed: %ld page(s), %ld task(s), %ld skipped (unchanged)"
+ "Graph Sync: Unknown change type %ld for item type %ld"
+ "Graph Sync: Unsupported folder type for creation: %ld"
+ "Graph Sync: Unsupported folder type for deletion: %ld"
+ "Graph Sync: Unsupported item type for creation: %ld"
+ "Graph Sync: Unsupported item type for deletion: %ld"
+ "Graph Sync: Unsupported item type for update: %ld"
+ "Graph Sync: accountChanged for account \"%{public}s\""
+ "Graph Sync: added deferred attendees to calendar event %{public}s after attachment reconciliation"
+ "Graph Sync: adopted folder map revision %ld with %ld local folder(s) still owed — rebased to revision %ld"
+ "Graph Sync: candidate %{public}s event.iCalUId %{public}s does not match target %{public}s"
+ "Graph Sync: candidate %{public}s has no associated event; skipping"
+ "Graph Sync: carrier %{public}s holds revision %ld but not our content — leaving the publish owed"
+ "Graph Sync: carrier %{public}s holds revision %ld but we cannot read our own map — leaving the publish owed"
+ "Graph Sync: coalescing credential renewal for account %{private}s (waiters=%{public}ld)"
+ "Graph Sync: credential renewal failed for account %{private}s - %{public}s (waiters=%{public}ld)"
+ "Graph Sync: credential renewal successful for account %{private}s (waiters=%{public}ld)"
+ "Graph Sync: credential renewal watchdog fired for account %{private}s (waiters=%{public}ld)"
+ "Graph Sync: declining server deletion, dataclass sync is inactive - itemType %ld account %{public}s item %{public}s"
+ "Graph Sync: declining to rename the distinguished Tasks list, the server does not permit it - account %{public}s folder %{public}s"
+ "Graph Sync: distinct RenewableAccount instances coalesced onto identifier %{private}s — leader-only reload invariant violated; followers may cache stale credentials. See class doc on EXSGSCredentialRenewalManager."
+ "Graph Sync: downsync change item requested with an empty externalID for item type %ld"
+ "Graph Sync: dropping note folder blob whose GUID collides with synthetic folder externalID %{public}s"
+ "Graph Sync: dropping sticky-note resource whose id collides with synthetic folder externalID %{public}s"
+ "Graph Sync: dropping todo task resource with no usable external id (tombstone=%{public}s)"
+ "Graph Sync: failed to drop the task-list delta cursor after a refused rename; the distinguished Tasks list keeps the rejected name locally"
+ "Graph Sync: failed to encode note folder metadata for folder %{public}s"
+ "Graph Sync: failed to record note folder %{public}s (%{public}s) for publish"
+ "Graph Sync: failed to remove meeting-request message %{public}s: %{private}s"
+ "Graph Sync: fetchTaskLists failed - %{public}s"
+ "Graph Sync: folder map revision %{public}s is no longer on its carrier %{public}s — re-owing the publish"
+ "Graph Sync: folder-removal pin probe failed for %ld note(s) — keeping every row requestID=%{public}s"
+ "Graph Sync: found folder named %{private}s and id %{public}s"
+ "Graph Sync: heartbeat deferForPush (draining) consecutiveDefers=%{public}ld account=%{public}s"
+ "Graph Sync: heartbeat not stamped (refreshCompleted=%{bool,public}d errorSurfaced=%{bool,public}d) account=%{public}s"
+ "Graph Sync: heartbeat runFullSync account=%{public}s"
+ "Graph Sync: heartbeat skip (%{public}s) account=%{public}s"
+ "Graph Sync: hostname not reachable: %{public}s"
+ "Graph Sync: hostname reachable: %{public}s"
+ "Graph Sync: inbox meeting-request lookup hit %ld-page cap; %ld matched so far, remaining pages skipped"
+ "Graph Sync: item tier skip declined, folder never seeded %{private}s"
+ "Graph Sync: keeping calendar %{sensitive}s with no owner address (fail-open)"
+ "Graph Sync: late credential renewal failed after watchdog — reloading account to pick up accountsd auth-flag flip for %{private}s"
+ "Graph Sync: late credential renewal succeeded after watchdog — reloading account %{private}s"
+ "Graph Sync: locateDefaultCalendarFolder failed - %{public}s"
+ "Graph Sync: locateDefaultNotesFolder ensured synthetic folder %{public}s"
+ "Graph Sync: meeting-request lookup filter: %{public}s"
+ "Graph Sync: meeting-request lookup matched %ld message(s) for target iCalUId %{public}s: %{public}s"
+ "Graph Sync: meeting-request message %{public}s already removed from the inbox, treating as success"
+ "Graph Sync: meeting-request page %ld — %ld candidate(s), %ld with associated event, %ld matched so far"
+ "Graph Sync: meeting-request window %ld of %ld failed; keeping %ld match(es) already collected and ending the scan: %{private}s"
+ "Graph Sync: note %{public}s has no resolvable folder (extParent=%{public}s intParent=%{public}s) — no folder blob written"
+ "Graph Sync: note %{public}s resolved to the default folder — writing an explicit top-level edge"
+ "Graph Sync: note %{public}s writing folder edge folderID=%{public}s"
+ "Graph Sync: note folder %{public}s (%{public}s) recorded at map revision %ld"
+ "Graph Sync: note folder map entry %{public}s has an unresolvable parent — treating as top level"
+ "Graph Sync: note folder map has a parent cycle of %ld folders — reparenting %{public}s to top level"
+ "Graph Sync: note folder map is too large to publish (%ld folders, %ld bytes, cap %ld) — publishing nothing"
+ "Graph Sync: note folder map publish failed — %{public}s requestID=%{public}s"
+ "Graph Sync: note folder map state did not persist (adopted=%{public}s published=%{public}s)"
+ "Graph Sync: notes round done: adopted=%{public}s published=%{public}s carrier=%{public}s pages=%ld folders=%ld rows=%ld removed=%ld kept=%ld staleNotes=%ld divergentAtRevision=%ld publishOwed=%{public}s"
+ "Graph Sync: observed folder map revision %ld on carrier %{public}s — settling the publish debt from the server's copy"
+ "Graph Sync: performTaskDeltaSync failed - %{public}s for folder %{private}s"
+ "Graph Sync: poll skipping item tiers for %{public}ld covered dataclass(es), creditAsRefresh=%{bool,public}d account=%{public}s"
+ "Graph Sync: removing %ld stale meeting-request message(s) for event %{public}s"
+ "Graph Sync: repush failed to persist folder re-add for %{public}s"
+ "Graph Sync: repush has no stored Notes folder map — re-emitting each folder row instead"
+ "Graph Sync: repush skipping folder re-add for %{public}s (no external ID or unsupported type %ld)"
+ "Graph Sync: repushFolders called for %ld folders"
+ "Graph Sync: reseed reap failed to persist %{public}ld of %{public}ld orphan tombstone(s) for change source %{public}s; the failures will be retried on the next full seed."
+ "Graph Sync: resyncFolderHierarchy initiated by %{public}s"
+ "Graph Sync: resyncItemsForFolder %{public}s initiated by %{public}s"
+ "Graph Sync: shutdown for account \"%{private}s\""
+ "Graph Sync: skipping meeting-request lookup for a delegate mailbox; the inbox legs are /me-only"
+ "Graph Sync: skipping meeting-request lookup for target iCalUId %{public}s — event has no createdDateTime/lastModifiedDateTime to bound the scan"
+ "Graph Sync: skipping meeting-request lookup; could not resolve iCalUId for event %{public}s"
+ "Graph Sync: skipping unsupported folder type %ld"
+ "Graph Sync: starting credential renewal for account %{private}s"
+ "Graph Sync: startup for account \"%{private}s\""
+ "Graph Sync: surfacing auth state to data consumers (authenticated: %{public}s)"
+ "Graph Sync: syncAllFolderItems reason=%{public}s skippedItemTiers=%{public}ld"
+ "Graph Sync: syncAllFolderItemsForDataclasses: %ld"
+ "Graph Sync: syncCalendarFolderHierarchy failed - %{public}s requestID=%{public}s"
+ "Graph Sync: syncDelegateCalendarFolders failed - %{public}s requestID=%{public}s"
+ "Graph Sync: syncFolderHierarchy initiated by %{public}s"
+ "Graph Sync: syncItemsForFolder %{public}s initiated by %{public}s"
+ "Graph Sync: synchronous credential renewal timed out after %{public}lds"
+ "Graph Sync: synthetic Notes folder %{public}s already current"
+ "Graph Sync: the server holds folder map revision %ld, newer than ours (%{public}s) — note writes will not carry ours until we catch up"
+ "Graph Sync: throttle gate cleared after %{public}ld skipped round(s) (%{public}s)"
+ "Graph Sync: throttle gate closed for %{public}.*fs (retryAfter=%{public}s deferrals=%{public}ld)"
+ "Graph Sync: throttle gate reopened after %{public}.*fs (skipped=%{public}ld rounds, %{public}s)"
+ "Graph Sync: unexpected error escaped push item handling - %{private}s"
+ "Graph migration cutover housekeeping failed for account %{public}@ -- holding on the paused protocol instead of starting Graph unseeded."
+ "Graph migration cutover housekeeping failed for account %{public}@ -- will retry next startup."
+ "Graph migration cutover housekeeping for account %{public}@ aborted -- watermark seed failed."
+ "Graph migration gate transition for account %{public}@ was expected to resolve to Graph at capture time, but a fresh re-check at restart now resolves to kind %ld instead -- honoring the fresh result."
+ "Graph migration gate: account %{public}@ (state %ld) now %{public}@ -- %{public}@."
+ "Graph migration gate: account %{public}@ state %ld -> %{public}@ (%{public}@)"
+ "Graph migration housekeeping completion"
+ "Graph migration property for account %{public}@ reads %ld (not-yet-migrating) despite an already-verified local Graph migration -- property is stale or unexpected; trusting the local latch, not the property."
+ "Graph migration property has reserved/undefined value %ld for account %{public}@."
+ "Graph migration property present for account %{public}@ (state %ld) with no local EWS history -- treating as a mis-arm, proceeding to Graph rather than stranding this account paused indefinitely."
+ "Graph migration property present with non-numeric value for account %{public}@."
+ "Graph migration verified"
+ "GraphMigration"
+ "GraphWebPushEnabled"
+ "GraphWebPushFreshnessMinutes"
+ "Hydrated exception %{public}s belongs to no discovered master; dropping"
+ "INSERT OR IGNORE INTO exs_graph_migration_verified (id) VALUES (1)"
+ "If-Match decision for event %{public}s: isOrganizer=%{public}s, isResolvedOccurrence=%{public}s, forwardingChangeKey=%{public}s"
+ "Ignoring a replayed delete of note folder %{public}s: it names row %ld, but row %ld is live"
+ "Instances paging hit max pages (%ld) for %{private}s; remaining instances not fetched"
+ "Item already gone on server (%{public}s); treating as success (op=%{public}s, externalID=%{public}s)"
+ "Item sync failed for change item with no externalID (changeID=%ld itemType=%ld resolvedExternalID=%{public}s) — cannot surface to consumer; underlying=%{public}s"
+ "List Subscriptions"
+ "Listed %ld attachments for %{public}s"
+ "Migration"
+ "Move attachment copy — %ld copied, %ld skipped of %ld source attachment(s)"
+ "Move attachment copy — fetching source attachment bytes failed (%{private}s); skipping this attachment"
+ "Move attachment copy — listing source attachments failed (%{private}s); moving without attachments"
+ "Move attachment copy — re-creating attachment on the moved event failed (%{private}s); skipping this attachment"
+ "Move attachment copy — skipping %{public}s attachment (no copiable content over addAttachment)"
+ "Move attachment copy — skipping file attachment of %ld byte(s); over the %ld-byte single-POST cap"
+ "Move attachment copy — skipping zero-byte file attachment"
+ "Move attachment copy — source attachment returned no content bytes; skipping"
+ "Move attachment copy — source calendar unknown; moving without attachments"
+ "Move recreation built the series master id %{public}s for a cancelled slot; refusing to delete the whole series"
+ "Move recreation could not parse a date from a cancelled occurrence id"
+ "Move recreation — cancelled occurrence already gone on the new master (404/410), treating as success"
+ "Move skipped — event has no recognizable type; not moving something whose shape is unknown."
+ "Move skipped — event type %{public}s is a single occurrence of a series, not the whole series (unsupported)."
+ "Move skipped — series has %ld exception(s) (recurrence with exceptions unsupported)."
+ "Move skipped — unrecognized event type %{public}s."
+ "No APS connection is available for web push"
+ "Note folder %{public}s cascade left notes on the server — the folder can resurrect"
+ "Note folder %{public}s delete: %ld folder(s) in subtree, cascading to %ld note(s)"
+ "Note folder %{public}s has no live row — nothing to move"
+ "Note folder %{public}s is absent from the map but %{public}s — leaving it"
+ "Note folder %{public}s is already in %{public}s — not a move"
+ "Note folder %{public}s move → %{public}s (from %{public}s) %{public}s"
+ "Note folder %{public}s update changed nothing — not republishing"
+ "Note folder delete reached push: externalID=%{public}s itemID=%ld"
+ "Operation %{public}s did not attempt to handle a thrown error."
+ "Operation %{public}s did not run a post update hook."
+ "Operation %{public}s specified an invalid batch size: %{public}ld"
+ "Other"
+ "Per-recipient availability error code=%{public}s message=%{private}s"
+ "Published folder map revision %ld (%ld folder(s), hash %{public}s) on note %{public}s"
+ "Published folder map revision %ld to note %{public}s but could not record it; the publish stays owed and this carrier is re-PATCHed every round until the store persists again"
+ "Reconciler: %ld known attachments in DB, %ld consumer attachments"
+ "Refusing to move note folder %{public}s into %{public}s — it is the folder itself or one of its descendants"
+ "Reminders"
+ "Renew Subscription"
+ "Resolved-occurrence change item has no internalID; cannot persist externalID %{public}s"
+ "SELECT COALESCE(MAX(last_change_item_id), 0) FROM exs_change_sources WHERE account_id=%ld AND change_source_id!=%@ AND change_source_id NOT LIKE %@"
+ "SELECT change_source_id FROM exs_change_sources WHERE change_source_id=%@ AND account_id=%ld LIMIT 1"
+ "SELECT count(*) FROM (SELECT DISTINCT account_id FROM exs_items UNION SELECT DISTINCT account_id FROM exs_folders)"
+ "SELECT count(*) FROM exs_change_sources WHERE account_id=%ld AND data_consumer_blob IS NOT NULL AND instr(CAST(data_consumer_blob AS TEXT), 'notesFolderMap') > 0"
+ "SELECT count(*) FROM exs_items i WHERE i.account_id=%ld AND i.item_type=%ld AND i.folder_id NOT IN (   SELECT f.folder_id FROM exs_folders f   JOIN exs_distinguished_folders d ON f.external_folderID = d.external_folderID   WHERE d.account_id=%ld AND d.folder_type=%ld)"
+ "SELECT id FROM exs_graph_migration_verified WHERE %@ IS NOT NULL LIMIT 1"
+ "SELECT rowid, external_unique_requestID FROM exs_attachments WHERE account_id=%ld AND rowid > %ld ORDER BY rowid LIMIT %ld"
+ "SELECT rowid, folder_type, external_folderID FROM exs_distinguished_folders WHERE account_id=%ld AND rowid > %ld ORDER BY rowid LIMIT %ld"
+ "SELECT rowid, folder_type, external_folderID, external_parentFolderID FROM exs_folders WHERE account_id=%ld AND rowid > %ld ORDER BY rowid LIMIT %ld"
+ "SELECT rowid, item_type, external_itemID, external_parentFolderID FROM exs_items WHERE account_id=%ld AND rowid > %ld ORDER BY rowid LIMIT %ld"
+ "SELECT rowid, item_type, external_itemID, external_parentFolderID, parentExternalID, properties_blob FROM exs_change_items WHERE account_id=%ld AND rowid > %ld ORDER BY rowid LIMIT %ld"
+ "Schedule entry scheduleId=%{private}s does not match any requested email — skipping (responseCount=%ld, requestCount=%ld)"
+ "Series master %{public}s arrived with no exceptionOccurrences key; modifiedOccurrences stays unspecified, which tells the consumer to delete every detachment of the series"
+ "Series master %{public}s exception list: returned=%{public}ld"
+ "Series master %{public}s exception list: returned=%{public}ld derived=%{public}ld"
+ "Skipped %ld unchanged note folder(s)"
+ "Subscription create returned no subscription id"
+ "Subscription renew returned an unexpected response"
+ "SyncProtocol-GraphMigrationPaused-%@"
+ "Synchronizing folder with ID %{public}s"
+ "The APS URL token request failed"
+ "The APS URL token request returned no token"
+ "The APS endpoint request was abandoned before it completed"
+ "The VAPID public key could not be fetched"
+ "The VAPID public key is empty"
+ "The VAPID public key is not valid base64URL"
+ "The subscription response contained no subscription id"
+ "UPDATE exs_attachments SET external_unique_requestID=%@ WHERE rowid=%ld"
+ "UPDATE exs_change_items SET external_itemID=%@ WHERE rowid=%ld"
+ "UPDATE exs_change_items SET external_parentFolderID=%@ WHERE rowid=%ld"
+ "UPDATE exs_change_items SET parentExternalID=%@ WHERE rowid=%ld"
+ "UPDATE exs_change_items SET properties_blob=%@ WHERE rowid=%ld"
+ "UPDATE exs_change_sources SET last_change_item_id=%ld WHERE change_source_id=%@ AND account_id=%ld AND last_change_item_id<%ld"
+ "UPDATE exs_distinguished_folders SET external_folderID=%@ WHERE rowid=%ld"
+ "UPDATE exs_folders SET external_folderID=%@ WHERE rowid=%ld"
+ "UPDATE exs_folders SET external_parentFolderID=%@ WHERE rowid=%ld"
+ "UPDATE exs_folders SET external_syncState=%@ WHERE account_id=%ld"
+ "UPDATE exs_graph_migration_verified SET %@=%lld WHERE id=1"
+ "UPDATE exs_items SET external_itemID=%@ WHERE rowid=%ld"
+ "UPDATE exs_items SET external_parentFolderID=%@ WHERE rowid=%ld"
+ "Unable to add delegate for an unknown permission level."
+ "Unable to update delegate to an unresolved permission."
+ "Unsupported subscription change type"
+ "Uploading attachment '%{private}s' to item %{public}s"
+ "VAPID public key response was missing or invalid"
+ "Web Push: VAPID key fetch failed; suppressing for %{public}ld min. error=%{public}s requestID=%{public}s"
+ "WebPushEncryptionTest"
+ "Working-hours TZ %{public}s did not resolve; falling back to current"
+ "[EXSDataConsumerInstance _drainOutstandingChangeItems] -- Skipped, account paused for Graph migration"
+ "[EXSDataConsumerInstance _drainOutstandingChangeItems] Stopping without advancing the watermark -- the instance was shut down during the push."
+ "[EXSDataConsumerInstance _drainOutstandingChangeItems] Stopping, the instance was shut down mid-drain."
+ "[EXSDataConsumerInstance processChangesSinceLastSync] -- Skipped, account paused for Graph migration"
+ "a translation failed and abortsOnTranslationFailure is set"
+ "accountKey=%{public}s received download request requestID=%{public}s attachmentUUID=%{public}s"
+ "attachment download lanes %{public}s — background %ld/%ld active, %ld queued; interactive %ld/%ld active, %ld queued"
+ "attachment serverID=%{public}s is new; inserting row (ownerID=%{public}s)"
+ "attachmentUUID=%{public}s already on disk; short-circuiting"
+ "attachmentUUID=%{public}s has no server ID; cannot download"
+ "beginning download for attachmentUUID=%{public}s serverID=%{public}s"
+ "cache"
+ "calendar"
+ "cancelledOccurrences"
+ "cancelling %ld queued attachment download(s) on teardown"
+ "chunk read on %@ faulted with error %ld"
+ "chunk read on %@ returned no result set"
+ "clearExternalSyncStateForAllFoldersInAccount: Error while updating folder sync state in sync engine database: %{public}@"
+ "com.apple.aps.exchangesync."
+ "com.apple.exchangesync.graphMigrationPaused"
+ "conversion verified"
+ "createSubscription"
+ "created"
+ "created,deleted"
+ "created,updated"
+ "created,updated,deleted"
+ "deleteSubscription"
+ "deleted"
+ "events/delta exception protection batch failed for folder %{public}s: requestID=%{public}s"
+ "events/delta exception protection for folder %{public}s resolved locally: probed=%ld matchedLocal=%ld"
+ "events/delta exception protection for folder %{public}s: skippedMasters=%ld already enumerated this round, no probe needed"
+ "events/delta exception protection for folder %{public}s: skippedMasters=%ld alreadyEnumerated=%ld probed=%ld exceptions=%ld unanswered=%ld"
+ "events/delta hydration skipped %ld event(s) as 404/410 (deletion race), %ld as empty-bodied 2xx, and dropped %ld on non-transient errors (cursor advances; re-hydrate on next change)"
+ "events/delta re-seeding folder %{public}s: stored cursor is not an events/delta continuation"
+ "ewsId to restId conversion is unavailable"
+ "exs_attachments"
+ "exs_change_items"
+ "exs_distinguished_folders"
+ "exs_folders"
+ "exs_items"
+ "external_folderID"
+ "external_itemID"
+ "external_parentFolderID"
+ "external_unique_requestID"
+ "fetched"
+ "flushing %ld completed attachment handoff(s) inline"
+ "graph"
+ "graphMigration"
+ "heartbeatRefresh"
+ "housekeeping_completed_at"
+ "inFlight"
+ "inline attachment metadata applied: %{public}ld event(s) with %{public}ld attachment(s), %{public}ld event(s) cleared, %{public}ld unknown, of %{public}ld change item(s)"
+ "listSubscriptions"
+ "no"
+ "no (claim reclaimed)"
+ "noWork"
+ "operation %{public}s did not attempt to handle a thrown error."
+ "operation %{public}s did not run a post create hook."
+ "parentExternalID"
+ "pausedForMigration"
+ "promoted queued prefetch attachmentUUID=%{public}s to the interactive lane"
+ "properties blob is not a JSON object"
+ "properties_blob"
+ "q!"
+ "real EWS history confirmed, conversion not yet verified"
+ "reconcileAttachments - drain-level failure (%{public}s); aborting push drain"
+ "reconcileAttachments - fetched %ld server attachments"
+ "reconcileAttachments - have %ld consumer attachments"
+ "reconcileAttachments - item internalID=%{public}s externalID=%{public}s calendarExternalID=%{public}s"
+ "reconcileAttachments - server fetch failed: %{private}s; server state unknown"
+ "renewSubscription"
+ "rewritten properties blob failed to serialize"
+ "scheduleItems missing — falling back to availabilityView (length=%ld)"
+ "scheduleItems non-empty but yielded no spans — falling through to availabilityView (inputCount=%ld)"
+ "seedChangeSourceWatermarkFromExistingSources: Error reading max watermark for change source (%{public}@) in sync engine database: %{public}@"
+ "seedChangeSourceWatermarkFromExistingSources: Error while seeding change source (%{public}@) watermark in sync engine database: %{public}@"
+ "seedChangeSourceWatermarkFromExistingSources: seeded change source %{public}@ to %ld for account %ld."
+ "since lease "
+ "starting download attachmentUUID=%{public}s lane=%{public}s waitedMs=%llu active=%ld/%ld queued=%ld"
+ "subscriptionID expiration "
+ "suppressed"
+ "tasks"
+ "the conversion did not commit"
+ "throttled"
+ "translator result order does not match the candidate order on %@.%@"
+ "translator returned %lu results for %lu candidates on %@.%@"
+ "undecryptableStructure"
+ "unknown"
+ "unrecognized translation error"
+ "unsupported"
+ "unsupported source format "
+ "unsupported target format "
+ "unsupportedEncoding"
+ "updated"
+ "updated,deleted"
+ "v16@?0@8"
+ "v24@?0@\"NSMutableDictionary\"8@\"NSString\"16"
+ "v32@?0@\"NSNumber\"8@16^B24"
+ "v32@?0@\"_TtC12ExchangeSync24EXSGSIdTranslationResult\"8Q16^B24"
+ "verified_at"
+ "webpush APS public token received (%{public}ld bytes); connection is live"
+ "webpush coverage transition dataClass=%{public}s covered=%{public}s folders=%{public}ld account=%{public}s"
+ "webpush graph %{public}@ failed httpStatus=%{public}@ requestID=%{public}@ error=%{public}@"
+ "webpush graph %{public}@ ok"
+ "webpush no push: APS connection unavailable (daemon likely not signed with the APS entitlements); polling only"
+ "webpush renew failed subscriptionID=%{public}s kept=%{public}s error=%{public}s requestID=%{public}s"
+ "webpush renew subscriptionID=%{public}s grantedExpiry=%{public}s"
+ "webpush stage=0 flag GraphWebPushEnabled=%{public}s previous=%{public}s account=%{public}s"
+ "webpush stage=1 eligibility dataClass=%{public}s eligible=no reason=%{public}s account=%{public}s"
+ "webpush stage=10 downsync scope=%{public}s reason=%{public}s narrowed=%{public}s folderTiers=%{public}ld itemTiers=%{public}ld refreshed=%{public}s"
+ "webpush stage=10 downsync scope=%{public}s reason=%{public}s skipped=throttled"
+ "webpush stage=10b pushRefresh dataClass=%{public}s refreshed=%{public}s narrowed=%{public}ld"
+ "webpush stage=2 coverage dataClass=%{public}s covered=%{public}ld needsRenewal=%{public}ld expired=%{public}ld stalePending=%{public}ld needsSubscribe=%{public}ld account=%{public}s"
+ "webpush stage=2 coverage skipped=throttled account=%{public}s"
+ "webpush stage=3 vapid source=%{public}s available=%{public}s"
+ "webpush stage=3 vapid unusable error=%{private}s"
+ "webpush stage=4 apsTokenRequested abandoned=staleHandshake topic=%{private}@"
+ "webpush stage=4 apsTokenRequested failed=emptyVapidKey topic=%{private}@"
+ "webpush stage=4 apsTokenRequested failed=keyGeneration topic=%{private}@"
+ "webpush stage=4 apsTokenRequested joined=inFlight topic=%{private}@"
+ "webpush stage=4 apsTokenRequested reused=existing topic=%{private}@"
+ "webpush stage=4 apsTokenRequested topic=%{private}@"
+ "webpush stage=5 apsTokenReceived deferred=throttled dataClass=%{public}s"
+ "webpush stage=5 apsTokenReceived discarded=supersededOrRemoved topic=%{private}@"
+ "webpush stage=5 apsTokenReceived failed=neverAnswered topic=%{private}@"
+ "webpush stage=5 apsTokenReceived failed=tokenMissing topic=%{private}@"
+ "webpush stage=5 apsTokenReceived failed=tokenRequest topic=%{private}@ error=%{public}@"
+ "webpush stage=5 apsTokenReceived topic=%{private}@ host=%{public}@ len=%{public}ld fp=%{private}@"
+ "webpush stage=6 graphCreate dataClass=%{public}s resourceShape=%{public}s changeType=%{public}s topic=%{private}s"
+ "webpush stage=6 graphCreate halted=throttled remaining=%{public}ld"
+ "webpush stage=7 graphCreate failed dataClass=%{public}s resourceShape=%{public}s error=%{public}s requestID=%{public}s"
+ "webpush stage=7 graphCreateConflict409 dataClass=%{public}s resourceShape=%{public}s changeType=%{public}s requestID=%{public}s message=%{private}s"
+ "webpush stage=7 graphCreated subscriptionID=%{public}s grantedExpiry=%{public}s resourceShape=%{public}s"
+ "webpush stage=8 inbound dropped=decryptFailed topic=%{private}@"
+ "webpush stage=8 inbound dropped=noKeys topic=%{private}@"
+ "webpush stage=8 inbound dropped=noReceiver topic=%{private}@; pruning topic"
+ "webpush stage=8 inbound dropped=noTopic"
+ "webpush stage=8 inbound payload=decrypted bytes=%{public}ld topic=%{private}@"
+ "webpush stage=8 inbound payload=shoulderTap degraded=%{public}@ detail=%{public}@ topic=%{private}@"
+ "webpush stage=8 inbound payload=shoulderTap topic=%{private}@"
+ "webpush stage=9 routed dropped=unknownTopic topic=%{private}s"
+ "webpush stage=9 routed topic=%{private}s payload=%{public}s account=%{public}s"
+ "webpush stage=9b narrow dataClass=%{public}s entries=%{public}ld rejectedClientState=%{public}ld missingSubID=%{public}ld named=%{public}ld matchedLocal=%{public}ld keys=%{public}s"
+ "webpush subscription delete found it already gone id=%{public}@"
+ "webpush vapid fetch claim reclaimed after %{public}ld s; the previous fetcher never returned or threw"
+ "webpush vapid fetch failed; suppressing for %{public}ld min. recorded=%{public}@ error=%{public}@"
+ "write to %@.%@ faulted with error %ld"
+ "yes"
- "$!"
- "$batch %{public}@ chunk failed with no confirmed deletes; abandoning %d remaining id(s) as failed rather than re-attempting a server-wide fault"
- "$batch %{public}@ did not confirm %d of %d delete(s); local rows kept for the next drain"
- "$batch %{public}@ failed authorization (HTTP 401) on %d sub-request(s) and renewal was unavailable or already spent (requestID=%{public}@)"
- "$batch %{public}@ retrying failed sub-request(s) after reactive credential renewal"
- "$batch %{public}@ skipping reactive renewal — account is unauthenticated"
- "$batch %{public}@ throttled (HTTP 429) on %d sub-request(s); over inline budget or retries exhausted"
- "$batch %{public}@ throttled (HTTP 429) on %d sub-request(s); waiting %{public}.2fs then retrying just those"
- "$batch delete failed for the whole chunk (httpStatus=%{public}@ requestID=%{public}@); %d id(s) keep their local rows and retry next cycle"
- "$batch hydration failed non-transiently (httpStatus=%{public}@ requestID=%{public}@); dropping %d id(s) this round, cursor will advance — they re-hydrate on next change"
- "$batch hydration sub-request(s) failed deterministically for %d id(s) (status:requestID=%{public}@); dropping them, they re-hydrate on next change"
- "$batch hydration sub-response body failed to decode for %d id(s) (requestIDs=%{public}@); dropping them, they re-hydrate on next change"
- "$batch hydration sub-response missing from envelope for %d id(s) (externalIDs=%{public}@); dropping them, they re-hydrate on next change"
- "%{public}@ %{public}@"
- "%{public}@ %{public}@ confirmed invalid delta sync state (httpStatus=%{public}@ graphErrorCode=%{public}@ requestID=%{public}@ pagesHydrated=%d pagesPersisted=%d); cursor clear %{public}@ to re-seed next cycle"
- "%{public}@ %{public}@ delta round complete: pages=%d items=%d skipped=%d cursor=%{public}@ reconciled=%{public}@"
- "%{public}@ %{public}@ starting %{public}@ delta round: maxpagesize=%{public}@"
- "%{public}@ : page count: %d, items retrieved: %d, cursor: %{public}@, pageSize: %d"
- "%{public}@ account=%{private}@ %{public}@ delta failure (transient or mid-progress; next cycle resumes): kind=%{public}@ httpStatus=%{public}@ graphErrorCode=%{public}@ requestID=%{public}@ pagesHydrated=%d pagesPersisted=%d cursorPresent=%{public}@ details=%{private}@"
- "%{public}@ delta page %d: items=%d skipped=%d total=%d totalSkipped=%d"
- "%{public}@ delta page limit guard has been exceeded."
- "%{public}@ failed: %{public}@"
- "%{public}@ gateway/request timeout on page %d at maxpagesize=%d — halving to %d and retrying the same cursor"
- "%{public}@ hydration skipped %d id(s) as 404/410 (deletion race), %d as empty-bodied 2xx, and dropped %d on non-transient errors (cursor advances; re-hydrate on next change)"
- "%{public}@ non-transient delta failure — does not trigger a list re-sync: account=%{private}@ %{public}@ kind=%{public}@ httpStatus=%{public}@ graphErrorCode=%{public}@ requestID=%{public}@ pagesHydrated=%d pagesPersisted=%d cursorPresent=%{public}@ unexpectedType=%{public}@ details=%{private}@"
- "%{public}@ returned error %{public}@"
- "%{public}@ returned no changeKey for %{public}@; keeping the stored token"
- "%{public}@ skipped — item already has externalID %{public}@"
- "%{public}@ skipped: missing externalID on change item %ld"
- "%{public}@ skipped: parent folder unresolved for change item %ld: %{private}@"
- "%{public}@ succeeded on server but failed to refresh local externalChangeKey for %{public}@"
- "%{public}@ succeeded on server but failed to update local database"
- "%{public}@ terminal page had no continuation link (%{public}@) — full re-seed next cycle"
- "%{public}@: %{public}@"
- "%{public}@: buildDeleteRequest called outside the performDelete pipeline"
- "%{public}@: item %{public}@ gone on server (%{public}@); treating as success"
- "%{public}@: no updatable fields specified, skipping network call"
- "%{public}@: refreshed item %{public}@ after recoverable failure; retrying PATCH once"
- "%{public}d event(s) reported attachments with no inline collection; leaving their cached attachments untouched (reconverges on next change)"
- "%{public}s"
- "/me/onenote/notebooks"
- "A delta request for operation \"%{public}@\" has returned %d consecutive blank pages."
- "APNS connection is not available"
- "APNS subscription failed: "
- "APNS unsubscription failed: "
- "Add Calendar Delegate Operation returned error %{public}@"
- "Ambiguous occurrence match for master %{public}@: %{public}d candidates"
- "Apple Push Service connection not available"
- "Applied folder map revision %ld from %{public}@ (%d folder(s), hash %{public}@): %d row change(s), %d removal(s), %d kept%{public}@"
- "Attachment '%{private}@' is %ld bytes — exceeds the %ld-byte single-request upload limit"
- "Attachment uploaded successfully, server ID: %{public}@"
- "Authored TZ original=%{private}@ wire=%{private}@ did not resolve; falling back to current"
- "Availability request missing requestID; dropping (emails=%{public}d)"
- "B!"
- "Calendar permission operation (type=%ld) returned error %{public}@"
- "Calendar upsync: %{public}@ has no authored time zone (floating; specified=%{public}d); declaring the fallback zone"
- "Calendar upsync: %{public}@ time zone is an empty string; declaring the fallback zone"
- "Cannot download attachment %{public}@: missing parent item external ID"
- "Collection already deleted on server, treating as success (op=%{public}@, externalID=%{public}@)"
- "Conflict changeKey refresh GET failed inconclusively for %{public}@: %{private}@"
- "Conflict changeKey refresh for %{public}@ found the note soft-deleted — declining the retry"
- "Conflict changeKey refresh for %{public}@ yielded no usable changeKey"
- "Conflict changeKey refresh for %{public}@ yielded no usable etag"
- "Conflict changeKey refresh for %{public}@ yielded no usable response"
- "Could not derive originalStartDate from occurrenceId %{public}@"
- "Created note folder %{public}@"
- "Deleting %d stale note(s) confirmed gone server-side that were pinning a refused folder removal"
- "Deleting attachment %{public}@ from item %{public}@"
- "Delta operation %{public}@ is configured with a list type that is not GraphSyncResponsive."
- "Detached item %@ missing parent external ID"
- "Directory search did not return any results. %@"
- "Directory search returned @{public}%ld results"
- "Download failed for attachment %{public}@: %{public}@"
- "Downloaded attachment %{public}@ (%d bytes) to %{public}@"
- "Dropping note folder map entry whose id collides with the synthetic folder %{public}@"
- "Dropping unparseable cancelledOccurrence OID %{public}@"
- "Dropping unparseable travel time extended property for event %{public}@"
- "EXSGSAttachmentManager initialized for accountKey=%{private}@"
- "EXSGSAttachmentXPCRequest.addRequestID called after finish for attachmentUUID=%{public}@ requestID=%{public}@"
- "EXSGSAttachmentXPCRequest.downloadProgressed called after finish for attachmentUUID=%{public}@"
- "EXSGSAttachmentXPCRequest.finish called twice for attachmentUUID=%{public}@"
- "EXSGSGetMeetingRequestItemsOperation failed (non-fatal): %{public}@"
- "EXSGSGetMeetingRequestItemsOperation found %d stale invitation(s) for event %{public}@"
- "EXSGSRemoveMeetingRequestOperation failed (non-fatal): %{public}@"
- "EXSGSRemoveMeetingRequestOperation: cleanup incomplete for event %{public}@ — at least one stale meeting-request message could not be removed"
- "EXSXPCInterfaceImplementation: Received an XPC call accountChangedWithType:accountId:"
- "Exception %{public}@ of master %{public}@ arrived as a tombstone; dropping"
- "Exception %{public}@ of master %{public}@ has neither a usable originalStart nor a parseable occurrenceId; cannot name its slot, so its detachment may be removed"
- "Exception hydration failed; using the masters' inline entries (attachments and extended properties reconverge on the next change). httpStatus=%{public}d requestID=%{public}@ reason=%{private}@"
- "Exception resource %{public}@ has no seriesMasterId (unexpected: MS Graph contract requires it on every exception); dropping to avoid duplicating against the master's rule expansion."
- "ExchangeSync.EXSAPNSPushServiceConnection"
- "ExchangeSync/EXSAPNSPushProvider.swift"
- "Executing %{public}@"
- "Executing %{public}@ for change item %ld"
- "Executing search user list (directory) operation for search query %{public}@"
- "Failed to create APSConnection for ExchangeSync with environment: "
- "Failed to create or manage subscription"
- "Failed to decrypt APNS payload"
- "Failed to decrypt push message: "
- "Failed to echo note folder id %{public}@ to the consumer"
- "Failed to expand resource for hydration operation %{public}@: %{public}@"
- "Failed to generate cryptographic key pair"
- "Failed to mark the subtree of note folder %{public}@ deleted — peers may promote its children to the root"
- "Failed to persist %{public}d exception(s) across %{public}d master(s) in folder %{public}@; they reconverge on each master's next change"
- "Failed to persist resolved occurrence identifiers for %{public}@"
- "Failed to process push notification"
- "Failed to remove stale attachment file %{public}@: %{public}@"
- "Failed to retrieve item count for operation %{public}@: %{private}@"
- "Failed to subscribe to topic "
- "Fatal error"
- "Folder map carrier %{public}@ is gone server-side; trying another"
- "Folder map publish owed but nothing publishable is stored (adopted=%{public}@)"
- "Folder map revision %ld abandoned: note %{public}@ already carries revision %ld (hash %{public}@)"
- "Folder map revision %ld not published: no usable carrier in %d attempt(s)"
- "Folder not found for item ID: "
- "Graph Sync: %d note(s) name a folder no map described — homing to the default folder, which does not self-heal"
- "Graph Sync: %d note(s) pinning a folder removal answered inconclusively — keeping those rows"
- "Graph Sync: %{public}@ failed - %{public}@ requestID=%{public}@"
- "Graph Sync: %{public}@ proactive credential renewal (expires in %{public}.0fs, lead=%{public}.0fs)"
- "Graph Sync: %{public}@ retrying after %{public}.2fs backoff (attempt %{public}d)"
- "Graph Sync: %{public}@ retrying after reactive credential renewal"
- "Graph Sync: %{public}@ skipping reactive renewal — account is unauthenticated"
- "Graph Sync: %{public}@ succeeded"
- "Graph Sync: %{public}ld sync inactive (flag/dataclass); skipping delta for folder %{private}@"
- "Graph Sync: All web push subscriptions active; polling stopped"
- "Graph Sync: Calendar delta sync completed: %d page(s), %d event(s), %d skipped (unchanged)"
- "Graph Sync: Cannot start web push - no account identifier; falling back to polling"
- "Graph Sync: Configuring web push"
- "Graph Sync: Error unregistering web push subscriptions: %{public}@"
- "Graph Sync: Executing %{public}@ for change item %ld"
- "Graph Sync: Failed to create web push subscription for %{public}@: %{public}@"
- "Graph Sync: Network not reachable for %{public}@"
- "Graph Sync: Network reachable for %{public}@"
- "Graph Sync: No folders found for type, triggering hierarchy sync"
- "Graph Sync: Notes delta sync persisted %d notes across %d page(s), %d skipped (unchanged)"
- "Graph Sync: Operation failed - %{public}@ requestID=%{public}@"
- "Graph Sync: Performing delta sync for folder %{private}@ (token: %{public}@)"
- "Graph Sync: Performing notes delta sync for folder %{private}@ (token: %{public}@)"
- "Graph Sync: Performing task delta sync for folder %{private}@ (token: %{public}@)"
- "Graph Sync: Processing web push notification for %{public}@ (change: %{public}@)"
- "Graph Sync: Some web push subscriptions failed; falling back to polling"
- "Graph Sync: Starting web push subscriptions"
- "Graph Sync: Stopping web push subscriptions"
- "Graph Sync: System woken from sleep"
- "Graph Sync: Tasks delta sync completed: %d page(s), %d task(s), %d skipped (unchanged)"
- "Graph Sync: Unknown change type %d for item type %d"
- "Graph Sync: Unknown resource type in notification: %{public}@"
- "Graph Sync: Unsupported folder type for creation: %d"
- "Graph Sync: Unsupported folder type for deletion: %d"
- "Graph Sync: Unsupported item type for creation: %d"
- "Graph Sync: Unsupported item type for deletion: %d"
- "Graph Sync: Unsupported item type for update: %d"
- "Graph Sync: Web push configured with real subscription manager for %d resource types"
- "Graph Sync: Web push plugin not yet configured; falling back to polling"
- "Graph Sync: Web push subscription created for %{public}@ (id: %{public}@)"
- "Graph Sync: accountChanged for account \"%{private}@\""
- "Graph Sync: added deferred attendees to calendar event %{public}@ after attachment reconciliation"
- "Graph Sync: adopted folder map revision %ld with %d local folder(s) still owed — rebased to revision %ld"
- "Graph Sync: candidate %{public}@ event.iCalUId %{public}@ does not match target %{public}@"
- "Graph Sync: candidate %{public}@ has no associated event; skipping"
- "Graph Sync: coalescing credential renewal for account %{private}@ (waiters=%{public}d)"
- "Graph Sync: credential renewal failed for account %{private}@ - %{public}@ (waiters=%{public}d)"
- "Graph Sync: credential renewal successful for account %{private}@ (waiters=%{public}d)"
- "Graph Sync: credential renewal watchdog fired for account %{private}@ (waiters=%{public}d)"
- "Graph Sync: declining server deletion, dataclass sync is inactive - itemType %ld account %{public}@ item %{public}@"
- "Graph Sync: distinct RenewableAccount instances coalesced onto identifier %{private}@ — leader-only reload invariant violated; followers may cache stale credentials. See class doc on EXSGSCredentialRenewalManager."
- "Graph Sync: downsync change item requested with an empty externalID for item type %d"
- "Graph Sync: dropping note folder blob whose GUID collides with synthetic folder externalID %{public}@"
- "Graph Sync: dropping sticky-note resource whose id collides with synthetic folder externalID %{public}@"
- "Graph Sync: dropping todo task resource with no usable external id (tombstone=%{public}@)"
- "Graph Sync: failed to encode note folder metadata for folder %{public}@"
- "Graph Sync: failed to record note folder %{public}@ (%{public}@) for publish"
- "Graph Sync: failed to remove meeting-request message %{public}@: %{public}@"
- "Graph Sync: fetchTaskLists failed - %{public}@"
- "Graph Sync: folder map revision %{public}@ is no longer on its carrier %{public}@ — re-owing the publish"
- "Graph Sync: folder-removal pin probe failed for %d note(s) — keeping every row requestID=%{public}@"
- "Graph Sync: found folder named %{public}@ and id %{public}@"
- "Graph Sync: heartbeat deferForPush (draining) consecutiveDefers=%{public}ld account=%{private}@"
- "Graph Sync: heartbeat not stamped (refreshCompleted=%{public}d errorSurfaced=%{public}d) account=%{private}@"
- "Graph Sync: heartbeat runFullSync account=%{private}@"
- "Graph Sync: heartbeat skip (%{public}@) account=%{private}@"
- "Graph Sync: hostname not reachable: %{public}@"
- "Graph Sync: hostname reachable: %{public}@"
- "Graph Sync: inbox meeting-request lookup hit %d-page cap; %d matched so far, remaining pages skipped"
- "Graph Sync: keeping calendar %{sensitive}@ with no owner address (fail-open)"
- "Graph Sync: late credential renewal failed after watchdog — reloading account to pick up accountsd auth-flag flip for %{private}@"
- "Graph Sync: late credential renewal succeeded after watchdog — reloading account %{private}@"
- "Graph Sync: locateDefaultCalendarFolder failed - %{public}@"
- "Graph Sync: locateDefaultNotesFolder ensured synthetic folder %{public}@"
- "Graph Sync: meeting-request lookup filter: %{public}@"
- "Graph Sync: meeting-request lookup matched %d message(s) for target iCalUId %{public}@: %{public}@"
- "Graph Sync: meeting-request message %{public}@ already removed from the inbox, treating as success"
- "Graph Sync: meeting-request page %d — %d candidate(s), %d with associated event, %d matched so far"
- "Graph Sync: meeting-request window %d of %d failed; keeping %d match(es) already collected and ending the scan: %{public}@"
- "Graph Sync: note %{public}@ has no resolvable folder (extParent=%{public}@ intParent=%{public}@) — no folder blob written"
- "Graph Sync: note %{public}@ resolved to the default folder — writing an explicit top-level edge"
- "Graph Sync: note %{public}@ writing folder edge folderID=%{public}@"
- "Graph Sync: note folder %{public}@ (%{public}@) recorded at map revision %ld"
- "Graph Sync: note folder map entry %{public}@ has an unresolvable parent — treating as top level"
- "Graph Sync: note folder map has a parent cycle of %d folders — reparenting %{public}@ to top level"
- "Graph Sync: note folder map is too large to publish (%d folders, %d bytes, cap %d) — publishing nothing"
- "Graph Sync: note folder map publish failed — %{public}@ requestID=%{public}@"
- "Graph Sync: note folder map state did not persist (adopted=%{public}@ published=%{public}@)"
- "Graph Sync: notes round done: adopted=%{public}@ published=%{public}@ carrier=%{public}@ pages=%d folders=%d rows=%d removed=%d kept=%d staleNotes=%d divergentAtRevision=%d publishOwed=%{public}@"
- "Graph Sync: performTaskDeltaSync failed - %{public}@ for folder %{private}@"
- "Graph Sync: removing %d stale meeting-request message(s) for event %{public}@"
- "Graph Sync: repush failed to persist folder re-add for %{public}@"
- "Graph Sync: repush skipping folder re-add for %{public}@ (no external ID or unsupported type %d)"
- "Graph Sync: repushFolders called for %d folders"
- "Graph Sync: reseed reap failed to persist %{public}d of %{public}d orphan tombstone(s) for change source %{public}@; the failures will be retried on the next full seed."
- "Graph Sync: resyncFolderHierarchy initiated by %{public}@"
- "Graph Sync: resyncItemsForFolder %{public}@ initiated by %{public}@"
- "Graph Sync: shutdown for account \"%{private}@\""
- "Graph Sync: skipping meeting-request lookup for target iCalUId %{public}@ — event has no createdDateTime/lastModifiedDateTime to bound the scan"
- "Graph Sync: skipping meeting-request lookup; could not resolve iCalUId for event %{public}@"
- "Graph Sync: skipping unsupported folder type %d"
- "Graph Sync: starting credential renewal for account %{private}@"
- "Graph Sync: startup for account \"%{private}@\""
- "Graph Sync: surfacing auth state to data consumers (authenticated: %{public}@)"
- "Graph Sync: syncAllFolderItems"
- "Graph Sync: syncAllFolderItemsForDataclasses: %d"
- "Graph Sync: syncCalendarFolderHierarchy failed - %{public}@ requestID=%{public}@"
- "Graph Sync: syncDelegateCalendarFolders failed - %{public}@ requestID=%{public}@"
- "Graph Sync: syncFolderHierarchy initiated by %{public}@"
- "Graph Sync: syncItemsForFolder %{public}@ initiated by %{public}@"
- "Graph Sync: synchronous credential renewal timed out after %{public}ds"
- "Graph Sync: synthetic Notes folder %{public}@ already current"
- "Graph Sync: the server holds folder map revision %ld, newer than ours (%{public}@) — note writes will not carry ours until we catch up"
- "Graph Sync: throttle gate cleared after %{public}ld skipped round(s) (%{public}@)"
- "Graph Sync: throttle gate closed for %{public}.0fs (retryAfter=%{public}@ deferrals=%{public}ld)"
- "Graph Sync: throttle gate reopened after %{public}.0fs (skipped=%{public}ld rounds, %{public}@)"
- "Graph Sync: unexpected error escaped push item handling - %{private}@"
- "Hydrated exception %{public}@ belongs to no discovered master; dropping"
- "If-Match decision for event %{public}@: isOrganizer=%{public}@, isResolvedOccurrence=%{public}@, forwardingChangeKey=%{public}@"
- "Ignoring a replayed delete of note folder %{public}@: it names row %ld, but row %ld is live"
- "Instances paging hit max pages (%d) for %{public}@; remaining instances not fetched"
- "Invalid APNS payload format"
- "Invalid VAPID public key provided"
- "Invalid or empty VAPID public key provided"
- "Invalid push notification payload"
- "Invalid response from APNS"
- "Item already gone on server (%{public}@); treating as success (op=%{public}@, externalID=%{public}@)"
- "Item sync failed for change item with no externalID (changeID=%ld itemType=%ld resolvedExternalID=%{public}@) — cannot surface to consumer; underlying=%{public}@"
- "Listed %d attachments for %{public}@"
- "Move skipped — event type %{public}@ is not a single instance (recurrence unsupported in v1)."
- "Note folder %{public}@ cascade left notes on the server — the folder can resurrect"
- "Note folder %{public}@ delete: %d folder(s) in subtree, cascading to %d note(s)"
- "Note folder %{public}@ has no live row — nothing to move"
- "Note folder %{public}@ is absent from the map but %{public}@ — leaving it"
- "Note folder %{public}@ is already in %{public}@ — not a move"
- "Note folder %{public}@ move → %{public}@ (from %{public}@) %{public}@"
- "Note folder %{public}@ update changed nothing — not republishing"
- "Note folder delete reached push: externalID=%{public}@ itemID=%ld"
- "Notification URL not available for topic: "
- "Operation %{public}@ did not attempt to handle a thrown error."
- "Operation %{public}@ did not run a post update hook."
- "Operation %{public}@ specified an invalid batch size: %{public}d"
- "Per-recipient availability error code=%{public}@ message=%{private}@"
- "Published folder map revision %ld (%d folder(s), hash %{public}@) on note %{public}@"
- "Push subscription data store is unavailable"
- "Received push message has invalid format"
- "Reconciler: %d known attachments in DB, %d consumer attachments"
- "Refusing to move note folder %{public}@ into %{public}@ — it is the folder itself or one of its descendants"
- "Resolved-occurrence change item has no internalID; cannot persist externalID %{public}@"
- "Schedule entry scheduleId=%{private}@ does not match any requested email — skipping (responseCount=%d, requestCount=%d)"
- "Series master %{public}@ arrived with no exceptionOccurrences key; modifiedOccurrences stays unspecified, which tells the consumer to delete every detachment of the series"
- "Series master %{public}@ exception list: returned=%{public}d"
- "Series master %{public}@ exception list: returned=%{public}d derived=%{public}d"
- "Skipped %d unchanged note folder(s)"
- "Synchronizing folder with ID %{public}@"
- "Uploading attachment '%{public}@' to item %{public}@"
- "Web Push: APS returned notification URL for topic %{private}@ (host %{public}@, %{public}d chars, fp %{public}@)"
- "Web Push: Graph create failed for %{private}@/%{public}@; rolling back APS topic subscription"
- "Web Push: Graph create-subscription for resource %{public}@ returned no subscription id"
- "Web Push: VAPID public key is empty; cannot subscribe topic %{private}@"
- "Web Push: cannot subscribe topic for account %{private}@/%{public}@ — APS connection unavailable"
- "Web Push: failed to decrypt payload for topic %{private}@: %{public}@"
- "Web Push: failed to handle incoming notification: %{private}@"
- "Web Push: incoming message handler failed for topic %{private}@: %{public}@"
- "Web Push: incoming message with no topic; dropping"
- "Web Push: incoming notification JSON missing required fields"
- "Web Push: incoming notification payload was not valid JSON"
- "Web Push: malformed base64 payload for topic %{private}@; dropping"
- "Web Push: no notification URL for topic %{private}@ after subscribe; APS token may not have arrived yet"
- "Web Push: no stored push subscription (encryption keys) for topic %{private}@ after subscribe"
- "Web Push: no subscription for incoming message topic %{private}@; dropping"
- "Web Push: registerWebPush(%{private}@/%{public}@) called before plugin was configured"
- "Web Push: subscribe failed for topic %{private}@: %{private}@"
- "Web Push: unsupported content encoding %{public}@ for topic %{private}@; dropping"
- "Web push plugin is not properly configured"
- "WebPushConnection"
- "WebPushSubscriptionAdapter"
- "Working-hours TZ %{public}@ did not resolve; falling back to current"
- "accountKey=%{private}@ received download request requestID=%{public}@ attachmentUUID=%{public}@"
- "attachment download lanes %{public}@ — background %d/%d active, %d queued; interactive %d/%d active, %d queued"
- "attachment serverID=%{public}@ is new; inserting row (ownerID=%{public}@)"
- "attachmentUUID=%{public}@ already on disk; short-circuiting"
- "attachmentUUID=%{public}@ has no server ID; cannot download"
- "beginning download for attachmentUUID=%{public}@ serverID=%{public}@"
- "cancelling %d queued attachment download(s) on teardown"
- "com.exchangesync.pushservice"
- "events/delta exception protection batch failed for folder %{public}@: requestID=%{public}@"
- "events/delta exception protection for folder %{public}@ resolved locally: probed=%d matchedLocal=%d"
- "events/delta exception protection for folder %{public}@: skippedMasters=%d already enumerated this round, no probe needed"
- "events/delta exception protection for folder %{public}@: skippedMasters=%d alreadyEnumerated=%d probed=%d exceptions=%d unanswered=%d"
- "events/delta hydration skipped %d event(s) as 404/410 (deletion race), %d as empty-bodied 2xx, and dropped %d on non-transient errors (cursor advances; re-hydrate on next change)"
- "events/delta re-seeding folder %{public}@: stored cursor is not an events/delta continuation"
- "exchangesync_push_subscriptions.json"
- "flushing %d completed attachment handoff(s) inline"
- "https://web.push.apple.com/"
- "inline attachment metadata applied: %{public}d event(s) with %{public}d attachment(s), %{public}d event(s) cleared, %{public}d unknown, of %{public}d change item(s)"
- "operation %{public}@ did not attempt to handle a thrown error."
- "operation %{public}@ did not run a post create hook."
- "promoted queued prefetch attachmentUUID=%{public}@ to the interactive lane"
- "reconcileAttachments - drain-level failure (%{public}@); aborting push drain"
- "reconcileAttachments - fetched %d server attachments"
- "reconcileAttachments - have %d consumer attachments"
- "reconcileAttachments - item internalID=%{public}@ externalID=%{public}@ calendarExternalID=%{public}@"
- "reconcileAttachments - server fetch failed: %{public}@; server state unknown"
- "scheduleItems missing — falling back to availabilityView (length=%d)"
- "scheduleItems non-empty but yielded no spans — falling through to availabilityView (inputCount=%d)"
- "starting download attachmentUUID=%{public}@ lane=%{public}@ waitedMs=%llu active=%d/%d queued=%d"
- "subscribeToTopic(accountId:resource:)"
- "unsubscribeFromTopic(accountId:resource:)"
```
