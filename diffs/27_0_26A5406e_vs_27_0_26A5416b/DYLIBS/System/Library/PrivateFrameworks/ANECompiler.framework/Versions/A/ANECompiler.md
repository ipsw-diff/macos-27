## ANECompiler

> `/System/Library/PrivateFrameworks/ANECompiler.framework/Versions/A/ANECompiler`

```diff

-10.26.4.0.0
-  __TEXT.__text: 0x1c441a0
+10.26.6.0.0
+  __TEXT.__text: 0x1c4420c
   __TEXT.__init_offsets: 0x8
   __TEXT.__const: 0xc601e
   __TEXT.__cstring: 0x122212
-  __TEXT.__oslogstring: 0x2096b
+  __TEXT.__oslogstring: 0x209f5
   __TEXT.__gcc_except_tab: 0xd6080
   __TEXT.__unwind_info: 0x68048
   __TEXT.__eh_frame: 0x2b6c

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
   - /usr/lib/libncurses.5.4.dylib
-  Functions: 122689
-  Symbols:   168266
-  CStrings:  27385
+  Functions: 122691
+  Symbols:   168267
+  CStrings:  27386
 
Symbols:
+ _ZNK30ZinMirKernelSizeSplitterEngine17PartitionLinearlyE15ZinKernelFormatP11ZinIrTensormmmRKNSt3__18optionalIN19ZinIrLayerSplitInfo4Part11ConstraintsEEERKNS_12OCGSizeRangeEbRK19ZinMirDynamicKernelRK24ZinMirKernelStrideConfigPK14ZinNEConvLayerRNS_16LinerarPartitionE
Functions:
~ __ZNK30ZinMirKernelSizeSplitterEngine17PartitionLinearlyE15ZinKernelFormatP11ZinIrTensormmmRKNSt3__18optionalIN19ZinIrLayerSplitInfo4Part11ConstraintsEEERKNS_12OCGSizeRangeEbRK19ZinMirDynamicKernelRK24ZinMirKernelStrideConfigPK14ZinNEConvLayerRNS_16LinerarPartitionE : 1388 -> 1432
+ _OUTLINED_FUNCTION_4
+ _ZNK30ZinMirKernelSizeSplitterEngine17PartitionLinearlyE15ZinKernelFormatP11ZinIrTensormmmRKNSt3__18optionalIN19ZinIrLayerSplitInfo4Part11ConstraintsEEERKNS_12OCGSizeRangeEbRK19ZinMirDynamicKernelRK24ZinMirKernelStrideConfigPK14ZinNEConvLayerRNS_16LinerarPartitionE.cold.1
~ _ZL20DetermineNumNesToUseRK18ZinIrHalParametersPK14ZinNEConvLayermR11ZinIrStatus.cold.1 : 80 -> 64
~ _ZNK30ZinMirKernelSizeSplitterEngine33AnalyzeMultiPaletteLUTConstraintsEPK14ZinNEConvLayerRNS_8AnalysisE.cold.2 : 80 -> 64
CStrings:
+ "Kernel split: no legal partition for %zu output channels (num_nes=%zu, max_channels_per_ne=%zu); one aligned output channel exceeds KMEM."
```
