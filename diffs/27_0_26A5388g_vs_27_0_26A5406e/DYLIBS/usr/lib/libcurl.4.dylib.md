## libcurl.4.dylib

> `/usr/lib/libcurl.4.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__const`
- `__TEXT.__cstring`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH.__data`
- `__DATA.__data`

```diff

-168.0.0.0.0
-  __TEXT.__text: 0x6c2f8
+168.0.2.0.0
+  __TEXT.__text: 0x6c310
   __TEXT.__const: 0xee4
   __TEXT.__cstring: 0x10aa5
-  __TEXT.__unwind_info: 0x1180
+  __TEXT.__unwind_info: 0x1190
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x2040
   __DATA_CONST.__got: 0x0

   - /usr/lib/libcrypto.46.dylib
   - /usr/lib/libssl.48.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1438
-  Symbols:   2091
+  Functions: 1440
+  Symbols:   2093
   CStrings:  2861
 
Symbols:
+ _Curl_doh_cleanup
+ _Curl_doh_close
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.Dp5Ikr/Sources/curl/curl/lib/vtls/openssl.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.0aLz2f/Sources/curl/curl/lib/vtls/openssl.c"
```
