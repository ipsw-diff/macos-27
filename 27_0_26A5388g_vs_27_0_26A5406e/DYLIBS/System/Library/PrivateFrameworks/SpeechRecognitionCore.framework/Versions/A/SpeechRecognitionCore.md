## SpeechRecognitionCore

> `/System/Library/PrivateFrameworks/SpeechRecognitionCore.framework/Versions/A/SpeechRecognitionCore`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__cstring`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_classlist`
- `__DATA_CONST.__objc_protolist`
- `__DATA_CONST.__weak_got`
- `__DATA_CONST.__objc_selrefs`
- `__DATA_CONST.__objc_protorefs`
- `__DATA_CONST.__objc_superrefs`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__objc_const`
- `__AUTH_CONST.__objc_dictobj`
- `__AUTH_CONST.__objc_intobj`
- `__AUTH.__objc_data`
- `__AUTH.__data`
- `__DATA.__data`

```diff

-39.0.0.0.0
-  __TEXT.__text: 0x1d0d0
+40.1.0.0.0
+  __TEXT.__text: 0x1d148
   __TEXT.__objc_methlist: 0xe3c
   __TEXT.__cstring: 0x1a84
   __TEXT.__gcc_except_tab: 0x1000
Symbols:
+ -[SRDBuiltInLMMatchingCache hasLinguisticExtensionForItem:forIdentifier:]
+ -[SRDCommandMatcher _matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:]
+ -[SRDCommandMatcher _matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:]
+ -[SRDCommandMatcher _matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:]
+ -[SRDCommandMatcher _matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:]
+ -[SRDCommandMatcher _segmentMatchForTranscription:withTemplate:isSpellingMode:checkLinguisticPrefix:]
+ _objc_msgSend$_matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:
+ _objc_msgSend$_matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:
+ _objc_msgSend$_matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:
+ _objc_msgSend$_matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:
+ _objc_msgSend$_segmentMatchForTranscription:withTemplate:isSpellingMode:checkLinguisticPrefix:
+ _objc_msgSend$hasLinguisticExtensionForItem:forIdentifier:
- -[SRDBuiltInLMMatchingCache hasAmbiguousPrefixForItem:forIdentifier:]
- -[SRDCommandMatcher _matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:]
- -[SRDCommandMatcher _matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:]
- -[SRDCommandMatcher _matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:]
- -[SRDCommandMatcher _matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:]
- -[SRDCommandMatcher _segmentMatchForTranscription:withTemplate:isSpellingMode:]
- _objc_msgSend$_matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:
- _objc_msgSend$_matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:
- _objc_msgSend$_matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:
- _objc_msgSend$_matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:
- _objc_msgSend$_segmentMatchForTranscription:withTemplate:isSpellingMode:
- _objc_msgSend$hasAmbiguousPrefixForItem:forIdentifier:
Functions:
~ -[SRDCommandMatcher matchWithTranscriptionResult:] : 5548 -> 5552
~ -[SRDCommandMatcher _matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:] -> -[SRDCommandMatcher _matchLiteralSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:] : 1024 -> 1008
~ -[SRDCommandMatcher _matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:] -> -[SRDCommandMatcher _matchDictationSegment:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:] : 1260 -> 1272
~ -[SRDCommandMatcher _matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:] -> -[SRDCommandMatcher _matchCacheSegment:segments:remainingSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:] : 3612 -> 3668
~ -[SRDCommandMatcher _matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:] -> -[SRDCommandMatcher _matchSegments:transcription:cache:matchedObjects:consumedCacheKeys:shouldLog:isSpellingMode:checkLinguisticPrefix:] : 780 -> 824
~ -[SRDCommandMatcher _segmentMatchForTranscription:withTemplate:isSpellingMode:] -> -[SRDCommandMatcher _segmentMatchForTranscription:withTemplate:isSpellingMode:checkLinguisticPrefix:] : 252 -> 268
~ -[SRDCommandMatcher prefixMatchStatusForTranscription:isSpellingMode:] : 984 -> 988
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.P1R9YK/Sources/SpeechRecognitionCore/Sources/RXLanguageObject.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.P1R9YK/Sources/SpeechRecognitionCore/Sources/RXObject.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.P1R9YK/Sources/SpeechRecognitionCore/Sources/RXRecognitionSystem.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.P1R9YK/Sources/SpeechRecognitionCore/Sources/RXXPC.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.TP0rpJ/Sources/SpeechRecognitionCore/Sources/RXLanguageObject.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.TP0rpJ/Sources/SpeechRecognitionCore/Sources/RXObject.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.TP0rpJ/Sources/SpeechRecognitionCore/Sources/RXRecognitionSystem.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.TP0rpJ/Sources/SpeechRecognitionCore/Sources/RXXPC.mm"
```
