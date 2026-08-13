## libAppleArchive.dylib

> `/usr/lib/libAppleArchive.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`

```diff

 469.0.0.0.0
-  __TEXT.__text: 0x837f8
-  __TEXT.__cstring: 0x143b0
+  __TEXT.__text: 0x83b28
+  __TEXT.__cstring: 0x1446b
   __TEXT.__const: 0x920
   __TEXT.__oslogstring: 0x31
   __TEXT.__unwind_info: 0xd60

   __DATA_CONST.__got: 0x0
   __AUTH_CONST.__const: 0x80
   __AUTH_CONST.__cfstring: 0x40
-  __AUTH_CONST.__auth_got: 0x7c8
+  __AUTH_CONST.__auth_got: 0x7d0
   __DATA_DIRTY.__data: 0x10
   __DATA_DIRTY.__bss: 0x8
   - /System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation

   - /usr/lib/libcompression.dylib
   - /usr/lib/liblzma.5.dylib
   Functions: 1074
-  Symbols:   1320
-  CStrings:  2911
+  Symbols:   1321
+  CStrings:  2917
 
Symbols:
+ _linkat
Functions:
~ _aeaInputStreamDecryptSegment : 1348 -> 1408
~ _aeaInputStreamLoadSegment : 1856 -> 1928
~ _aeaContainerCreateExisting : 4140 -> 4272
~ _copyFileWithAttributes : 920 -> 956
~ _removeFile : 140 -> 176
~ _aaEntryAttributesInitWithPath : 952 -> 1036
~ _aaEntryAttributesApplyToPath : 1608 -> 1640
~ _aaEntryAttributesApplyToFD : 1344 -> 1408
~ _aaCheckAndFixWithPath : 2012 -> 1956
~ _AARandomAccessDecodeAndExtract : 5356 -> 5324
~ _workerProc : 8192 -> 8200
~ _extractStreamClose : 3116 -> 3372
~ _extractThreadProc : 3588 -> 3508
~ _clusterEntryUpdateDAT : 464 -> 476
~ _aaHeaderInitWithEncodedData : 1204 -> 1308
~ _update_field_sizes : 672 -> 760
CStrings:
+ "'H' LNK not a regular file: %s"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/../Common/SharedArray.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAFSCStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAArchiveFileStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAArchiveStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAArchiveStreamProcess.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAssetBuilder.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAssetDecodeStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAssetDecompressionStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAssetDecryptionStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAssetExtractStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAssetExtractor.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAssetGenerate.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAsyncByteStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAAsyncByteStreamProcessAllRanges.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAByteRange.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAByteStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAByteStreamProcess.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AACacheStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAChunkAsyncStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAChunkInputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAChunkOutputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AACompositeChunkAsyncStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AACompressionStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAConvertArchiveOutputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AADecodeArchiveInputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AADecodeArchiveInputStreamCPIO.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AADecodeArchiveInputStreamTar.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAEncodeArchiveOutputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAExtractArchiveOutputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAFieldACL.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAFieldKeys.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAFieldMCO.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAFieldXAT.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAFieldYEC.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAFieldYFP.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAGenericRandomAccessInputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAHeader.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAInPlaceStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAJSONStreams.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAMemoryStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAPathFilter.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAPathList.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AARandomAccessByteStreamProcess.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AARandomAccessDecodeAndExtract.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AARandomAccessDecompressionStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AARangeInputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AARemoveArchiveOutputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AASequentialDecompressionStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AATempStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAUtils.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleArchive/AAVerifyDirectoryArchiveOutputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/../AppleArchive/../Common/SharedArray.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEAAuthData.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEACommon.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEAContainer.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEAContext.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEAContextValidate.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEACrypto.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptAndExtract.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptAndExtractAsyncStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptAsyncStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptToFile.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptToFileAsyncStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptToStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEADirectRandomAccessDecryptionStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEAEncryptionStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEAInplace.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEAKeychain.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEARandomAccessDecryptionStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/AppleEncryptedArchive/AEASequentialDecryptionStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/BlobBuffer.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/ErrorCorrection.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/ErrorCorrection_ECC65537.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/IOBasicStreams.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/IOBuffers.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/IOCompressedStreams.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/ParallelCompressionAFSCStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/SharedArray.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/SharedBuffer.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/StringTable.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/ThreadPipeline.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/ThreadPool.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/Threads.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/Common/Utils.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelCompression/Filter.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/BXDiff5.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/BXDiffBase.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/BXDiffControls.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/BXDiffMatches.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/ImageDiff/APFS/APFS.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/ImageDiff/GenericArray.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImageDiff.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImageDiffInPlace.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImageOutputStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImagePatch.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImageStreams.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/ImageDiff/InSituStream.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/ImageDiff/RawImage.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelDiff/LargeFile.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelPatch/BXPatch5.c"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.OKI5so/Sources/ParallelCompression/ParallelPatch/PagedFile.c"
+ "Invalid segment size in cluster header"
+ "bad donor for: %s"
+ "blob field size too large"
+ "cluster_id out of range"
+ "donor is not a regular file: %s"
+ "header payload too large"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/../Common/SharedArray.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAFSCStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAArchiveFileStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAArchiveStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAArchiveStreamProcess.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAssetBuilder.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAssetDecodeStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAssetDecompressionStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAssetDecryptionStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAssetExtractStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAssetExtractor.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAssetGenerate.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAsyncByteStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAAsyncByteStreamProcessAllRanges.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAByteRange.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAByteStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAByteStreamProcess.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AACacheStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAChunkAsyncStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAChunkInputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAChunkOutputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AACompositeChunkAsyncStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AACompressionStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAConvertArchiveOutputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AADecodeArchiveInputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AADecodeArchiveInputStreamCPIO.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AADecodeArchiveInputStreamTar.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAEncodeArchiveOutputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAExtractArchiveOutputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAFieldACL.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAFieldKeys.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAFieldMCO.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAFieldXAT.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAFieldYEC.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAFieldYFP.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAGenericRandomAccessInputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAHeader.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAInPlaceStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAJSONStreams.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAMemoryStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAPathFilter.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAPathList.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AARandomAccessByteStreamProcess.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AARandomAccessDecodeAndExtract.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AARandomAccessDecompressionStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AARangeInputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AARemoveArchiveOutputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AASequentialDecompressionStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AATempStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAUtils.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleArchive/AAVerifyDirectoryArchiveOutputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/../AppleArchive/../Common/SharedArray.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEAAuthData.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEACommon.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEAContainer.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEAContext.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEAContextValidate.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEACrypto.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptAndExtract.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptAndExtractAsyncStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptAsyncStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptToFile.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptToFileAsyncStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEADecryptToStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEADirectRandomAccessDecryptionStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEAEncryptionStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEAInplace.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEAKeychain.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEARandomAccessDecryptionStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/AppleEncryptedArchive/AEASequentialDecryptionStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/BlobBuffer.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/ErrorCorrection.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/ErrorCorrection_ECC65537.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/IOBasicStreams.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/IOBuffers.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/IOCompressedStreams.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/ParallelCompressionAFSCStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/SharedArray.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/SharedBuffer.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/StringTable.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/ThreadPipeline.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/ThreadPool.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/Threads.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/Common/Utils.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelCompression/Filter.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/BXDiff5.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/BXDiffBase.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/BXDiffControls.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/BXDiffMatches.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/ImageDiff/APFS/APFS.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/ImageDiff/GenericArray.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImageDiff.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImageDiffInPlace.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImageOutputStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImagePatch.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/ImageDiff/ImageStreams.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/ImageDiff/InSituStream.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/ImageDiff/RawImage.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelDiff/LargeFile.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelPatch/BXPatch5.c"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.4LGXc9/Sources/ParallelCompression/ParallelPatch/PagedFile.c"
- "link %s"
```
