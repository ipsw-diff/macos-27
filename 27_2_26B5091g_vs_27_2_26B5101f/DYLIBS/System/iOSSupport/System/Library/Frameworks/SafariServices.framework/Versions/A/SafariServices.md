## SafariServices

> `/System/iOSSupport/System/Library/Frameworks/SafariServices.framework/Versions/A/SafariServices`

```diff

-625.2.5.11.1
-  __TEXT.__text: 0x1b2d8
+625.2.7.1.0
+  __TEXT.__text: 0x1b2ec
   __TEXT.__objc_methlist: 0x2c5c
   __TEXT.__cstring: 0xecf
   __TEXT.__gcc_except_tab: 0xe40
Symbols:
+ -[_SFReaderController setUpReaderWebViewIfNeededWithTimeout:completionHandler:]
+ ___79-[_SFReaderController setUpReaderWebViewIfNeededWithTimeout:completionHandler:]_block_invoke
+ _objc_msgSend$setUpReaderWebViewIfNeededWithTimeout:completionHandler:
- -[_SFReaderController setUpReaderWebViewIfNeededAndPerformBlock:]
- ___65-[_SFReaderController setUpReaderWebViewIfNeededAndPerformBlock:]_block_invoke
- _objc_msgSend$setUpReaderWebViewIfNeededAndPerformBlock:
Functions:
~ -[_SFReaderController prepareReaderPrintingIFrameWithCompletion:] : 256 -> 260
~ -[_SFReaderController setUpReaderWebViewIfNeededAndPerformBlock:] -> -[_SFReaderController setUpReaderWebViewIfNeededWithTimeout:completionHandler:] : 392 -> 404
~ -[_SFReaderController collectReaderContentForMailWithCompletion:] : 228 -> 232
```
