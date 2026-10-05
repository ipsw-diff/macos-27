## HealthDaemon

> `/System/Library/PrivateFrameworks/HealthDaemon.framework/Versions/A/HealthDaemon`

```diff

-7027.1.45.0.0
-  __TEXT.__text: 0xd0bea8
-  __TEXT.__objc_methlist: 0x4942c
-  __TEXT.__const: 0x724a0
-  __TEXT.__cstring: 0x8d05a
+7027.1.54.0.0
+  __TEXT.__text: 0xd100cc
+  __TEXT.__objc_methlist: 0x4962c
+  __TEXT.__const: 0x724d0
+  __TEXT.__cstring: 0x8d370
   __TEXT.__swift5_typeref: 0x44af
   __TEXT.__swift5_capture: 0x1b48
   __TEXT.__constg_swiftt: 0x411c
   __TEXT.__swift5_builtin: 0x154
-  __TEXT.__swift5_reflstr: 0x2cc8
-  __TEXT.__swift5_fieldmd: 0x2fb4
+  __TEXT.__swift5_reflstr: 0x2cf8
+  __TEXT.__swift5_fieldmd: 0x2fc0
   __TEXT.__swift5_assocty: 0xa48
   __TEXT.__swift5_proto: 0x564
   __TEXT.__swift5_types: 0x364
-  __TEXT.__oslogstring: 0x45e9a
+  __TEXT.__oslogstring: 0x45e52
   __TEXT.__swift5_mpenum: 0x30
   __TEXT.__swift5_protos: 0xcc
   __TEXT.__swift5_types2: 0x4
   __TEXT.__swift_as_entry: 0x50
   __TEXT.__swift_as_ret: 0x30
   __TEXT.__swift_as_cont: 0x1c
-  __TEXT.__gcc_except_tab: 0x7a7e8
-  __TEXT.__ustring: 0x70
-  __TEXT.__unwind_info: 0x35310
-  __TEXT.__eh_frame: 0x6908
+  __TEXT.__gcc_except_tab: 0x7a824
+  __TEXT.__ustring: 0xb6
+  __TEXT.__unwind_info: 0x35478
+  __TEXT.__eh_frame: 0x6978
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_classname: 0x0
   __TEXT.__objc_methname: 0x0
   __TEXT.__objc_methtype: 0x0
   __DATA_CONST.__const: 0xc4c8
-  __DATA_CONST.__objc_classlist: 0x2d10
+  __DATA_CONST.__objc_classlist: 0x2d28
   __DATA_CONST.__objc_catlist: 0x518
-  __DATA_CONST.__objc_protolist: 0xb40
+  __DATA_CONST.__objc_protolist: 0xb48
   __DATA_CONST.__objc_imageinfo: 0x8
   __DATA_CONST.__weak_got: 0x18
-  __DATA_CONST.__objc_selrefs: 0x1bbc0
-  __DATA_CONST.__objc_protorefs: 0x2f8
-  __DATA_CONST.__objc_superrefs: 0x1ed0
-  __DATA_CONST.__objc_arraydata: 0x8a10
-  __DATA_CONST.__got: 0x5c60
-  __AUTH_CONST.__const: 0x3bb50
-  __AUTH_CONST.__cfstring: 0x41520
-  __AUTH_CONST.__objc_const: 0x87390
+  __DATA_CONST.__objc_selrefs: 0x1bc80
+  __DATA_CONST.__objc_protorefs: 0x300
+  __DATA_CONST.__objc_superrefs: 0x1ec8
+  __DATA_CONST.__objc_arraydata: 0x8a18
+  __DATA_CONST.__got: 0x5c88
+  __AUTH_CONST.__const: 0x3bbe0
+  __AUTH_CONST.__cfstring: 0x41780
+  __AUTH_CONST.__objc_const: 0x87ad0
   __AUTH_CONST.__weak_auth_got: 0x30
   __AUTH_CONST.__objc_dictobj: 0x168
   __AUTH_CONST.__objc_intobj: 0x3e10
-  __AUTH_CONST.__objc_arrayobj: 0x21c0
+  __AUTH_CONST.__objc_arrayobj: 0x21d8
   __AUTH_CONST.__objc_doubleobj: 0x3c0
-  __AUTH_CONST.__auth_got: 0x3860
-  __AUTH.__objc_data: 0x9690
-  __AUTH.__data: 0x1ad0
-  __DATA.__objc_ivar: 0x47dc
-  __DATA.__data: 0x9748
-  __DATA.__bss: 0x7cf0
+  __AUTH_CONST.__auth_got: 0x3898
+  __AUTH.__objc_data: 0x97e0
+  __AUTH.__data: 0x1b50
+  __DATA.__objc_ivar: 0x4850
+  __DATA.__data: 0x9810
+  __DATA.__bss: 0x7ce0
   __DATA.__common: 0x1a8
   __DATA_DIRTY.__objc_ivar: 0xe54
-  __DATA_DIRTY.__objc_data: 0x14440
-  __DATA_DIRTY.__data: 0x3b08
+  __DATA_DIRTY.__objc_data: 0x14448
+  __DATA_DIRTY.__data: 0x3ae0
   __DATA_DIRTY.__bss: 0x1d30
   __DATA_DIRTY.__common: 0x158
   - /System/Library/Frameworks/Accounts.framework/Versions/A/Accounts

   - /usr/lib/swift/libswift_Concurrency.dylib
   - /usr/lib/swift/libswiftos.dylib
   - /usr/lib/swift/libswiftsimd.dylib
-  Functions: 51287
-  Symbols:   90770
-  CStrings:  14252
+  Functions: 51397
+  Symbols:   90871
+  CStrings:  14283
 
Symbols:
+ +[HDDataEntity hasStaticJoinClauses]
+ +[HDMedicalRecordEntity hasStaticJoinClauses]
+ -[HDDaemon _forceExitAfterFailureToQuiesce]
+ -[HDDaemon _requestCleanExitFromXPC]
+ -[HDDataOriginProvenance effectiveSystemBuild]
+ -[HDQueryManager scheduleDatabaseAccessForQueryServer:handler:]
+ -[HDQueryServer debugIdentifier]
+ -[HDQueryUsageDailyAnalytics _addClientWaitTimingFieldsToEvent:stats:databaseAccessStats:]
+ -[HDQueryUsageDailyAnalytics _eventDictionaryForStats:databaseAccessStats:databaseSizeMB:dataCacheSizeMB:databaseShape:isIHAEnabled:]
+ -[HDQueryUsageDatabaseAccessStatistics backgroundAccessCount]
+ -[HDQueryUsageDatabaseAccessStatistics backgroundConnectionDelaySampleCount]
+ -[HDQueryUsageDatabaseAccessStatistics foregroundAccessCount]
+ -[HDQueryUsageDatabaseAccessStatistics foregroundConnectionDelaySampleCount]
+ -[HDQueryUsageDatabaseAccessStatistics maxBackgroundConnectionDelay]
+ -[HDQueryUsageDatabaseAccessStatistics maxBackgroundManagerDelay]
+ -[HDQueryUsageDatabaseAccessStatistics maxForegroundConnectionDelay]
+ -[HDQueryUsageDatabaseAccessStatistics maxForegroundManagerDelay]
+ -[HDQueryUsageDatabaseAccessStatistics recordAccessWithManagerDelay:connectionDelay:foreground:]
+ -[HDQueryUsageDatabaseAccessStatistics reset]
+ -[HDQueryUsageDatabaseAccessStatistics totalBackgroundConnectionDelay]
+ -[HDQueryUsageDatabaseAccessStatistics totalBackgroundManagerDelay]
+ -[HDQueryUsageDatabaseAccessStatistics totalForegroundConnectionDelay]
+ -[HDQueryUsageDatabaseAccessStatistics totalForegroundManagerDelay]
+ -[HDQueryUsageStatistics backgroundOneShotQueryCount]
+ -[HDQueryUsageStatistics foregroundOneShotQueryCount]
+ -[HDQueryUsageStatistics maxBackgroundOneShotQueryDuration]
+ -[HDQueryUsageStatistics maxForegroundOneShotQueryDuration]
+ -[HDQueryUsageStatistics recordOneShotQueryWithDuration:foreground:]
+ -[HDQueryUsageStatistics totalBackgroundOneShotQueryDuration]
+ -[HDQueryUsageStatistics totalForegroundOneShotQueryDuration]
+ -[HDQueryUsageTracker _lock_statisticsForQueryType:]
+ -[HDQueryUsageTracker drainStatisticsWithDatabaseAccessStatistics:]
+ -[HDQueryUsageTracker recordDatabaseAccessWithManagerDelay:connectionDelay:foreground:]
+ -[HDWorkoutSessionServer unitTest_rebuildSessionControllerFromServerConfiguration]
+ OBJC_IVAR_$_HDDaemon._forceExitTimerSource
+ OBJC_IVAR_$_HDDaemon._hasRequestedCleanExit
+ OBJC_IVAR_$_HDQueryServer._activationCount
+ OBJC_IVAR_$_HDQueryServer._activationDelay
+ OBJC_IVAR_$_HDQueryServer._databaseAccessDelay
+ OBJC_IVAR_$_HDQueryServer._debugIdentifier
+ OBJC_IVAR_$_HDQueryServer._lastExecutionDuration
+ OBJC_IVAR_$_HDQueryServer._lastTransactionDuration
+ OBJC_IVAR_$_HDQueryServer._pauseCount
+ OBJC_IVAR_$_HDQueryServer._pauseStartTime
+ OBJC_IVAR_$_HDQueryServer._pendingAccessesAtDequeue
+ OBJC_IVAR_$_HDQueryServer._runningAccessesAtDequeue
+ OBJC_IVAR_$_HDQueryServer._totalExecutionDuration
+ OBJC_IVAR_$_HDQueryServer._totalPausedDuration
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._backgroundAccessCount
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._backgroundConnectionDelaySampleCount
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._foregroundAccessCount
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._foregroundConnectionDelaySampleCount
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._maxBackgroundConnectionDelay
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._maxBackgroundManagerDelay
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._maxForegroundConnectionDelay
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._maxForegroundManagerDelay
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._totalBackgroundConnectionDelay
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._totalBackgroundManagerDelay
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._totalForegroundConnectionDelay
+ OBJC_IVAR_$_HDQueryUsageDatabaseAccessStatistics._totalForegroundManagerDelay
+ OBJC_IVAR_$_HDQueryUsageStatistics._backgroundOneShotQueryCount
+ OBJC_IVAR_$_HDQueryUsageStatistics._foregroundOneShotQueryCount
+ OBJC_IVAR_$_HDQueryUsageStatistics._maxBackgroundOneShotQueryDuration
+ OBJC_IVAR_$_HDQueryUsageStatistics._maxForegroundOneShotQueryDuration
+ OBJC_IVAR_$_HDQueryUsageStatistics._totalBackgroundOneShotQueryDuration
+ OBJC_IVAR_$_HDQueryUsageStatistics._totalForegroundOneShotQueryDuration
+ OBJC_IVAR_$_HDQueryUsageTracker._databaseAccessStatistics
+ OBJC_IVAR_$_HDWorkoutSessionServer._workoutConfigurationLock
+ OBJC_IVAR_$__HDQueryDatabaseAccessBlock._handler
+ _HDQuerySanitizedDebugIdentifier
+ _HDQueryServerLifetimeSummary
+ _HDQueryServerRunSummary
+ _HKLogQueryCategory
+ _OBJC_CLASS_$_HDMutableNewMedicalRecordsTally
+ _OBJC_CLASS_$_HDNewMedicalRecordsCounts
+ _OBJC_CLASS_$_HDNewMedicalRecordsTally
+ _OBJC_CLASS_$_HDQueryUsageDatabaseAccessStatistics
+ _OBJC_METACLASS_$_HDMutableNewMedicalRecordsTally
+ _OBJC_METACLASS_$_HDNewMedicalRecordsCounts
+ _OBJC_METACLASS_$_HDNewMedicalRecordsTally
+ _OBJC_METACLASS_$_HDQueryUsageDatabaseAccessStatistics
+ _PROTOCOLS_HDNewMedicalRecordsCounts
+ _PROTOCOLS_HDNewMedicalRecordsTally
+ __44-[HDDaemon _handleLaunchServicesEvent:name:]_block_invoke
+ __CLASS_METHODS_HDMutableNewMedicalRecordsTally
+ __CLASS_METHODS_HDNewMedicalRecordsCounts
+ __CLASS_METHODS_HDNewMedicalRecordsTally
+ __CLASS_PROPERTIES_HDMutableNewMedicalRecordsTally
+ __CLASS_PROPERTIES_HDNewMedicalRecordsCounts
+ __CLASS_PROPERTIES_HDNewMedicalRecordsTally
+ __DATA_HDMutableNewMedicalRecordsTally
+ __DATA_HDNewMedicalRecordsCounts
+ __DATA_HDNewMedicalRecordsTally
+ __HDQueryUsageSetAverageAndMaximum
+ __HDReserveRecordSyncCachedRequestColumns
+ __HDResetReceivedNanoSyncAnchorsOnWatchForBodyMetrics
+ __INSTANCE_METHODS_HDMutableNewMedicalRecordsTally
+ __INSTANCE_METHODS_HDNewMedicalRecordsCounts
+ __INSTANCE_METHODS_HDNewMedicalRecordsTally
+ __IVARS_HDNewMedicalRecordsCounts
+ __IVARS_HDNewMedicalRecordsTally
+ __METACLASS_DATA_HDMutableNewMedicalRecordsTally
+ __METACLASS_DATA_HDNewMedicalRecordsCounts
+ __METACLASS_DATA_HDNewMedicalRecordsTally
+ __OBJC_$_INSTANCE_METHODS_HDQueryUsageDatabaseAccessStatistics
+ __OBJC_$_INSTANCE_VARIABLES_HDQueryUsageDatabaseAccessStatistics
+ __OBJC_$_PROP_LIST_HDQueryUsageDatabaseAccessStatistics
+ __OBJC_CLASS_RO_$_HDQueryUsageDatabaseAccessStatistics
+ __OBJC_METACLASS_RO_$_HDQueryUsageDatabaseAccessStatistics
+ __PROPERTIES_HDNewMedicalRecordsCounts
+ __PROPERTIES_HDNewMedicalRecordsTally
+ __PROTOCOLS_HDNewMedicalRecordsCounts
+ __PROTOCOLS_HDNewMedicalRecordsTally
+ ___32-[HDDaemon _setUpSignalHandlers]_block_invoke_3
+ ___67-[HDQueryUsageTracker drainStatisticsWithDatabaseAccessStatistics:]_block_invoke
+ ___75-[HDCloudSyncSeizeAbandonedStoresOperation _childTargetsForSyncIdentities:]_block_invoke
+ ___82-[HDWorkoutSessionServer unitTest_rebuildSessionControllerFromServerConfiguration]_block_invoke
+ ___88-[HDQueryServer _scheduleDatabaseAccessWithBlock:enqueueTime:pendingCount:runningCount:]_block_invoke
+ ___block_descriptor_56_e8_32bs40w_e11_v24?0Q8Q16l
+ ___block_descriptor_56_e8_32s_e9_B16?0^8l
+ ___block_descriptor_72_e8_32s40bs_e5_v8?0l
+ ___block_descriptor_89_e8_32s40s48s56s_e5_v8?0l
+ _objc_msgSend$_addClientWaitTimingFieldsToEvent:stats:databaseAccessStats:
+ _objc_msgSend$_eventDictionaryForStats:databaseAccessStats:databaseSizeMB:dataCacheSizeMB:databaseShape:isIHAEnabled:
+ _objc_msgSend$_forceExitAfterFailureToQuiesce
+ _objc_msgSend$_initWithSource:version:productType:operatingSystemVersion:systemBuild:
+ _objc_msgSend$_lock_statisticsForQueryType:
+ _objc_msgSend$_requestCleanExitFromXPC
+ _objc_msgSend$backgroundAccessCount
+ _objc_msgSend$backgroundConnectionDelaySampleCount
+ _objc_msgSend$backgroundOneShotQueryCount
+ _objc_msgSend$conceptWithIdentifier:attributes:relationships:
+ _objc_msgSend$countsByMedicalType
+ _objc_msgSend$drainStatisticsWithDatabaseAccessStatistics:
+ _objc_msgSend$effectiveSystemBuild
+ _objc_msgSend$foregroundAccessCount
+ _objc_msgSend$foregroundConnectionDelaySampleCount
+ _objc_msgSend$foregroundOneShotQueryCount
+ _objc_msgSend$initWithInsertedCount:updatedCount:
+ _objc_msgSend$insertedCount
+ _objc_msgSend$maxBackgroundConnectionDelay
+ _objc_msgSend$maxBackgroundManagerDelay
+ _objc_msgSend$maxBackgroundOneShotQueryDuration
+ _objc_msgSend$maxForegroundConnectionDelay
+ _objc_msgSend$maxForegroundManagerDelay
+ _objc_msgSend$maxForegroundOneShotQueryDuration
+ _objc_msgSend$recordAccessWithManagerDelay:connectionDelay:foreground:
+ _objc_msgSend$recordDatabaseAccessWithManagerDelay:connectionDelay:foreground:
+ _objc_msgSend$recordOneShotQueryWithDuration:foreground:
+ _objc_msgSend$scheduleDatabaseAccessForQueryServer:handler:
+ _objc_msgSend$totalBackgroundConnectionDelay
+ _objc_msgSend$totalBackgroundManagerDelay
+ _objc_msgSend$totalBackgroundOneShotQueryDuration
+ _objc_msgSend$totalForegroundConnectionDelay
+ _objc_msgSend$totalForegroundManagerDelay
+ _objc_msgSend$totalForegroundOneShotQueryDuration
+ _objc_msgSend$transactions
+ _objc_msgSend$updatedCount
- -[HDAnchoredObjectQueryServer _queue_didChangeStateFromPreviousState:state:]
- -[HDCodableHealthReportState .cxx_destruct]
- -[HDCodableHealthReportState copyTo:]
- -[HDCodableHealthReportState copyWithZone:]
- -[HDCodableHealthReportState description]
- -[HDCodableHealthReportState dictionaryRepresentation]
- -[HDCodableHealthReportState evaluationBuddyLastCompletedDate]
- -[HDCodableHealthReportState evaluationBuddyLastStartedDate]
- -[HDCodableHealthReportState hasEvaluationBuddyLastCompletedDate]
- -[HDCodableHealthReportState hasEvaluationBuddyLastStartedDate]
- -[HDCodableHealthReportState hasLastGeneratedReportId]
- -[HDCodableHealthReportState hasLastReportGenerationDate]
- -[HDCodableHealthReportState hash]
- -[HDCodableHealthReportState isEqual:]
- -[HDCodableHealthReportState lastGeneratedReportId]
- -[HDCodableHealthReportState lastReportGenerationDate]
- -[HDCodableHealthReportState mergeFrom:]
- -[HDCodableHealthReportState readFrom:]
- -[HDCodableHealthReportState setEvaluationBuddyLastCompletedDate:]
- -[HDCodableHealthReportState setEvaluationBuddyLastStartedDate:]
- -[HDCodableHealthReportState setHasEvaluationBuddyLastCompletedDate:]
- -[HDCodableHealthReportState setHasEvaluationBuddyLastStartedDate:]
- -[HDCodableHealthReportState setHasLastReportGenerationDate:]
- -[HDCodableHealthReportState setLastGeneratedReportId:]
- -[HDCodableHealthReportState setLastReportGenerationDate:]
- -[HDCodableHealthReportState writeTo:]
- -[HDQueryManager scheduleDatabaseAccessForQueryServer:block:]
- -[HDQueryUsageDailyAnalytics _eventDictionaryForStats:databaseSizeMB:dataCacheSizeMB:databaseShape:isIHAEnabled:]
- -[HDQueryUsageTracker drainStatistics]
- OBJC_IVAR_$_HDCodableHealthReportState._evaluationBuddyLastCompletedDate
- OBJC_IVAR_$_HDCodableHealthReportState._evaluationBuddyLastStartedDate
- OBJC_IVAR_$_HDCodableHealthReportState._has
- OBJC_IVAR_$_HDCodableHealthReportState._lastGeneratedReportId
- OBJC_IVAR_$_HDCodableHealthReportState._lastReportGenerationDate
- OBJC_IVAR_$__HDQueryDatabaseAccessBlock._block
- _HDCodableHealthReportStateReadFrom
- _OBJC_CLASS_$_HDCodableHealthReportState
- _OBJC_METACLASS_$_HDCodableHealthReportState
- __32-[HDDaemon _setUpSignalHandlers]_block_invoke
- __OBJC_$_INSTANCE_METHODS_HDCodableHealthReportState
- __OBJC_$_INSTANCE_VARIABLES_HDCodableHealthReportState
- __OBJC_$_PROP_LIST_HDCodableHealthReportState
- __OBJC_CLASS_PROTOCOLS_$_HDCodableHealthReportState
- __OBJC_CLASS_RO_$_HDCodableHealthReportState
- __OBJC_METACLASS_RO_$_HDCodableHealthReportState
- ___29-[HDDaemon exitClean:reason:]_block_invoke_2
- ___38-[HDQueryUsageTracker drainStatistics]_block_invoke
- ___44-[HDDaemon _handleLaunchServicesEvent:name:]_block_invoke_2
- ___50-[HDQueryServer _scheduleDatabaseAccessWithBlock:]_block_invoke
- ___80-[HDCloudSyncSeizeAbandonedStoresOperation _childTargetBySyncIdentityForParent:]_block_invoke
- ___block_descriptor_73_e8_32s40s48s_e19_"NSDictionary"8?0l
- _objc_msgSend$_eventDictionaryForStats:databaseSizeMB:dataCacheSizeMB:databaseShape:isIHAEnabled:
- _objc_msgSend$drainStatistics
- _objc_msgSend$scheduleDatabaseAccessForQueryServer:block:
- _objc_msgSend$setLastGeneratedReportId:
- exitClean:reason:.onceToken
- exitClean:reason:.timerSource
CStrings:
+ " (%.3fs in database transactions)"
+ " window, which holds recent days only"
+ "%@\n%@\n%@\n%@"
+ "%@:%d"
+ "%lu activation%s, exec %.3fs total"
+ "%s wait %.3fs (sched %.3fs, queued %.3fs behind %lu/%lu), exec %.3fs"
+ "%{public}@ -> %{public}@"
+ "%{public}@ Concept not found in Ontology for \"bodySiteConceptIdentifiers\" on medical history record entity"
+ "%{public}@ Concept not found in Ontology for \"methodConceptIdentifiers\" on medical history record entity"
+ "%{public}@ Concept not found in Ontology for \"reasonConceptIdentifiers\" on medical history record entity"
+ "%{public}@: %{public}@ -> %{public}@ (+%.3fs)"
+ "%{public}@: %{public}s — %{public}@"
+ "%{public}@: finished %{public}@"
+ ", cache %ld/%ld hit/miss"
+ ", n=%lld"
+ ", paused %.3fs ×%lu"
+ "CountsByMedicalType"
+ "HealthDaemon.HDNewMedicalRecordsCounts"
+ "Posting zone change for %s: new: %s, previous: %s, last sample date: %s"
+ "UPDATE sync_anchors SET received=0, validated=0 WHERE schema = 'main' AND sync_anchors.type = 4 AND store IN (SELECT ROWID FROM sync_stores WHERE sync_stores.type=1);"
+ "[%s] Not advancing past generation %ld: a write failed this pass."
+ "[%{public}s:%{public}s] Enumerating live for padded request %{public}s (%{public}s)"
+ "[%{public}s] Merged state's size (%ld) above the limit (%ld), purge metadata and increment epoch, previous: %lld"
+ "after %.3fs — "
+ "avgClientBackgroundConnectionDelay"
+ "avgClientBackgroundManagerDelay"
+ "avgClientBackgroundOneShotQueryDuration"
+ "avgClientForegroundConnectionDelay"
+ "avgClientForegroundManagerDelay"
+ "avgClientForegroundOneShotQueryDuration"
+ "bg"
+ "by design: no profile covers this configuration"
+ "by design: reaches past the "
+ "by design: this configuration is not cacheable"
+ "countClientBackgroundAccess"
+ "countClientBackgroundOneShotQuery"
+ "countClientForegroundAccess"
+ "countClientForegroundOneShotQuery"
+ "did not run"
+ "fg"
+ "maxClientBackgroundConnectionDelay"
+ "maxClientBackgroundManagerDelay"
+ "maxClientBackgroundOneShotQueryDuration"
+ "maxClientForegroundConnectionDelay"
+ "maxClientForegroundManagerDelay"
+ "maxClientForegroundOneShotQueryDuration"
+ "no cache plan was built; see the error logged above"
+ "ran"
+ "v24@?0Q8Q16"
+ "\xf0q1a"
+ "\xf0\xf0\xf1"
- "%@\n%@\n%@"
- "%{public}@ Failed to apply concepts for \"bodySiteConceptIdentifiers\" to medical history record entity. Concept not found in Ontology"
- "%{public}@ Failed to apply concepts for \"methodConceptIdentifiers\" to medical history record entity. Concept not found in Ontology"
- "%{public}@ Failed to apply concepts for \"reasonConceptIdentifiers\" to medical history record entity. Concept not found in Ontology"
- "%{public}@: Ran in %.3fs"
- "%{public}@: Ran in %.3fs (%.3fs in database transactions)"
- "%{public}@: Total activation delay: %.3fs, database access delay: %.3fs"
- "%{public}@: changed state (%@) -> (%@)"
- "%{public}@: did deactivate"
- "Failed to apply concepts for 'bodySiteConceptIdentifiers' to medical history record entity. Concept not found in Ontology"
- "Failed to apply concepts for 'methodConceptIdentifiers' to medical history record entity. Concept not found in Ontology"
- "Failed to apply concepts for 'reasonConceptIdentifiers' to medical history record entity. Concept not found in Ontology"
- "Posting zone change for %s: current zone: %s, new duration: %s, previous duration: %s, last sample date: %s"
- "[%{public}s:%{public}s] Skipping caching for padded request %{public}s"
- "[%{public}s] Merged state's size (%ld above the limit (%ld, purge metadata and increment epoch, previous: %lld"
- "evaluationBuddyLastCompletedDate"
- "evaluationBuddyLastStartedDate"
- "lastGeneratedReportId"
- "lastReportGenerationDate"
- "\xb1!a"
```
