## libswiftDemangle.dylib

> `/usr/lib/swift/libswiftDemangle.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__AUTH_CONST.__const`

```diff

-6.4.0.27.1
-  __TEXT.__text: 0x57ed4
-  __TEXT.__cstring: 0x5371
+6.4.0.31.4
+  __TEXT.__text: 0x58078
+  __TEXT.__cstring: 0x538d
   __TEXT.__const: 0x158
   __TEXT.__unwind_info: 0x748
   __TEXT.__auth_stubs: 0x0

   - /usr/lib/libc++.1.dylib
   Functions: 663
   Symbols:   663
-  CStrings:  1344
+  CStrings:  1345
 
Functions:
~ __ZN5swift8Demangle9Demangler30demangleFunctionSpecializationEv : 1096 -> 1104
~ __ZN5swift8Demangle9Demangler21demangleFuncSpecParamENS0_4Node4KindE : 2676 -> 2792
~ __ZN5swift8Demangle11NodePrinter5printEPNS0_4NodeEjb : 27628 -> 27640
~ __ZN5swift8Demangle11NodePrinter36printFunctionSigSpecializationParamsEPNS0_4NodeEj : 2760 -> 2792
~ __ZN12_GLOBAL__N_19Remangler42mangleFunctionSignatureSpecializationParamEPN5swift8Demangle4NodeEj : 5908 -> 6156
~ sub_1df28c874 -> sub_1de9a0a14 : 48 -> 52
CStrings:
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.VuCOtc/Sources/swiftlang_embedded_utils/swift/lib/Demangling/Demangler.cpp"
+ "Escaping Closure Propagated"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.oGAEEc/Sources/swiftlang_embedded_utils/swift/lib/Demangling/Demangler.cpp"
```
