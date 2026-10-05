## PeopleSuggester

> `/System/Library/PrivateFrameworks/PeopleSuggester.framework/Versions/A/PeopleSuggester`

```diff

-1975.0.0.0.0
-  __TEXT.__text: 0x124490
+1976.0.0.0.0
+  __TEXT.__text: 0x124570
   __TEXT.__objc_methlist: 0xaca4
   __TEXT.__const: 0x978
   __TEXT.__gcc_except_tab: 0x42b4

   __AUTH_CONST.__objc_arrayobj: 0x11d18
   __AUTH_CONST.__objc_doubleobj: 0xe0
   __AUTH_CONST.__objc_dictobj: 0x226c8
-  __AUTH_CONST.__auth_got: 0x6d0
+  __AUTH_CONST.__auth_got: 0x6d8
   __DATA.__objc_ivar: 0xf0c
   __DATA.__bss: 0x778
   __DATA_DIRTY.__objc_data: 0x3610

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 5237
-  Symbols:   10539
+  Symbols:   10540
   CStrings:  17732
 
Symbols:
+ __CDStringByConvertingPhoneNumberStringToASCII
Functions:
~ -[_PSEnsembleModel suggestionsFromSuggestionProxies:supportedBundleIDs:contactKeysToFetch:meContactIdentifier:maxSuggestions:predictionContext:] : 16732 -> 16764
~ -[_PSEnsembleModel psr_suggestionsFromSuggestionProxies:interactionsStatistics:maxSuggestions:predictionContext:] : 2116 -> 2148
~ ___37-[_PSFamilyRecommender currentFamily]_block_invoke : 1528 -> 1552
~ -[_PSContactResolver resolveContactIdentifier:] : 812 -> 832
~ -[_PSContactResolver resolveContactIfPossibleFromContactIdentifierString:pickFirstOfMultiple:] : 292 -> 324
~ +[_PSContactResolver normalizedHandlesDictionaryFromHandles:] : 428 -> 464
~ -[_PSContactCache getContactForHandle:handleType:] : 1188 -> 1212
~ -[_PSContactCatalog resolveVisualIdentifiersForHandles:catalogContactData:keepGoing:] : 9340 -> 9364
```
