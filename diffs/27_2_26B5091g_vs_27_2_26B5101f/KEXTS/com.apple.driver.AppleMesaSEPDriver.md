## com.apple.driver.AppleMesaSEPDriver

> `com.apple.driver.AppleMesaSEPDriver`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-10321.40.6.0.0
-  __TEXT.__const: 0x150
+10321.40.10.0.0
+  __TEXT.__const: 0x160
   __TEXT.__cstring: 0x6df7
   __TEXT.__os_log: 0x3728
-  __TEXT_EXEC.__text: 0x3225c
+  __TEXT_EXEC.__text: 0x32438
   __TEXT_EXEC.__auth_stubs: 0x780
   __DATA.__data: 0xc4
   __DATA.__common: 0x2b0
Symbols:
+ __ZZN18AppleMesaSEPDriver11handleMatchEbP17IOMesaCaptureDatabPbhE21kalloc_type_view_8852
+ __ZZN18AppleMesaSEPDriver11handleMatchEbP17IOMesaCaptureDatabPbhE21kalloc_type_view_9185
+ __ZZN18AppleMesaSEPDriver19applyPostponedMatchEP24postponed_match_result_tbE22kalloc_type_view_10880
+ __ZZN18AppleMesaSEPDriver19applyPostponedMatchEP24postponed_match_result_tbE22kalloc_type_view_10932
- __ZZN18AppleMesaSEPDriver11handleMatchEbP17IOMesaCaptureDatabPbhE21kalloc_type_view_8842
- __ZZN18AppleMesaSEPDriver11handleMatchEbP17IOMesaCaptureDatabPbhE21kalloc_type_view_9156
- __ZZN18AppleMesaSEPDriver19applyPostponedMatchEP24postponed_match_result_tbE22kalloc_type_view_10851
- __ZZN18AppleMesaSEPDriver19applyPostponedMatchEP24postponed_match_result_tbE22kalloc_type_view_10903
Functions:
~ __ZN18AppleMesaSEPDriver19asyncCaptureHandlerEP18IOTimerEventSource : 6748 -> 7064
~ __ZN18AppleMesaSEPDriver11handleMatchEbP17IOMesaCaptureDatabPbh : 4848 -> 5008
CStrings:
+ "AssertMacros: %s (value = 0x%lx), version: Mesa-10321.40.10~76, %s file: %s, line: %d\n"
- "AssertMacros: %s (value = 0x%lx), version: Mesa-10321.40.6~146, %s file: %s, line: %d\n"
```
