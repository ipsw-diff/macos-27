## EmbeddingCore

> `/System/Library/PrivateFrameworks/EmbeddingCore.framework/Versions/A/EmbeddingCore`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-460.8.2.0.0
-  __TEXT.__text: 0x6b860
+460.12.1.0.0
+  __TEXT.__text: 0x6b934
   __TEXT.__objc_methlist: 0x1954
   __TEXT.__const: 0x1150
-  __TEXT.__gcc_except_tab: 0x7330
+  __TEXT.__gcc_except_tab: 0x7358
   __TEXT.__cstring: 0x6476
-  __TEXT.__oslogstring: 0x19ef
+  __TEXT.__oslogstring: 0x1a2f
   __TEXT.__swift5_typeref: 0xc3
   __TEXT.__constg_swiftt: 0x1b8
   __TEXT.__swift5_builtin: 0x14

   __TEXT.__swift5_fieldmd: 0xec
   __TEXT.__swift5_proto: 0x8
   __TEXT.__swift5_types: 0x14
-  __TEXT.__unwind_info: 0x2f30
+  __TEXT.__unwind_info: 0x2f38
   __TEXT.__eh_frame: 0xb0
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/swift/libswiftXPC.dylib
   - /usr/lib/swift/libswift_Builtin_float.dylib
   - /usr/lib/swift/libswiftos.dylib
-  Functions: 2139
+  Functions: 2141
   Symbols:   3656
-  CStrings:  747
+  CStrings:  748
 
Functions:
~ -[MADCrossEncoder _createBatchedInputIdsWithBatchSize:queryTokens:chunks:realCount:] : 1128 -> 1200
~ -[MADCrossEncoder _processNextBatch:] : 1808 -> 1812
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:] : 1956 -> 2040
~ _OUTLINED_FUNCTION_7 : 12 -> 20
+ _OUTLINED_FUNCTION_8
~ __ZNKSt3__114default_deleteIN13sentencepiece4util6Status3RepEEclB9nqe220106EPS4_ : 108 -> 88
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:].cold.2 : 56 -> 64
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:].cold.3 : 60 -> 56
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:].cold.7 : 56 -> 60
~ -[MADCrossEncoder _processQuery:documents:maxNumChunks:chunkOverlap:outputs:].cold.8 : 80 -> 56
+ +[MADTextEmbeddingSafety createForEmbeddingVersion:].cold.1
CStrings:
+ "MADCrossEncoder: no room for document tokens (ctx %lu, query %lu)"
+ "cross_encoder_v140_ane_8bit_combined"
- "cross_encoder_v130_ane_8bit_combined"
```
