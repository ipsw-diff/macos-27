## Bom

> `/System/Library/PrivateFrameworks/Bom.framework/Versions/A/Bom`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH.__data`

```diff

-277.0.0.0.0
-  __TEXT.__text: 0x611b8
-  __TEXT.__cstring: 0x13dbb
+279.2.0.0.0
+  __TEXT.__text: 0x62160
+  __TEXT.__cstring: 0x13d95
   __TEXT.__const: 0x1738
   __TEXT.__oslogstring: 0x10b9
-  __TEXT.__unwind_info: 0xb80
+  __TEXT.__unwind_info: 0xb78
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0x978
   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x1b0
   __AUTH_CONST.__cfstring: 0x13e0
-  __AUTH_CONST.__auth_got: 0xd08
+  __AUTH_CONST.__auth_got: 0xd10
   __AUTH.__data: 0x160
   __DATA.__data: 0x168
   __DATA.__bss: 0x8dc

   - /usr/lib/libarchive.2.dylib
   - /usr/lib/libbz2.1.0.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 1117
-  Symbols:   1599
-  CStrings:  2500
+  Functions: 1122
+  Symbols:   1605
+  CStrings:  2499
 
Symbols:
+ _BOM_calloc_typed
+ _BOM_malloc_typed
+ _BOM_malloczero_typed
+ _BOM_realloc_typed
+ _BOM_realloczero_typed
+ __qtn_file_apply_to_fd
+ _platform_calloc_typed
+ _platform_malloc_typed
+ _platform_realloc_typed
+ _platform_valloc_typed
- _platform_calloc
- _platform_malloc
- _platform_realloc
- _platform_valloc
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Bom/BOMBom.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Bom/BOMBomEnumerator.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Bom/BOMFSEnumerator.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Common/BOMBufferManager.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Common/BOMCRC32.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Common/BOMFile.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Common/BOMPatternList.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Common/BOMSystemCmds.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/BOMCopier2.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/BOMCopierDataAnalyzer.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/BOMCopierDestination.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/BOMCopierMatchRecord.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/BOMCopierSource.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/BOMCopierSourceEntry.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/data_archive/data_archive.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/data_archive/data_archive_decoder.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/data_archive/data_archive_entry.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/data_archive/data_stack.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Copier/data_archive/fts_agent.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/FSObject/BOMFSOArchInfo.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/FSObject/BOMFSOTypeInfo.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Storage/BOMStorage.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Storage/BOMStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.MFp49U/Sources/Bom/Storage/BOMTree.c"
+ "Aug  3 2026"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Bom/BOMBom.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Bom/BOMBomEnumerator.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Bom/BOMFSEnumerator.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Common/BOMBufferManager.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Common/BOMCRC32.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Common/BOMFile.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Common/BOMPatternList.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Common/BOMSystemCmds.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/BOMCopier2.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/BOMCopierDataAnalyzer.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/BOMCopierDestination.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/BOMCopierMatchRecord.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/BOMCopierSource.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/BOMCopierSourceEntry.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/data_archive/data_archive.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/data_archive/data_archive_decoder.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/data_archive/data_archive_entry.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/data_archive/data_stack.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Copier/data_archive/fts_agent.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/FSObject/BOMFSOArchInfo.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/FSObject/BOMFSOTypeInfo.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Storage/BOMStorage.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Storage/BOMStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.X6y1J8/Sources/Bom/Storage/BOMTree.c"
- "Could not create empty hardlink path\n"
- "Jul  7 2026"
```
