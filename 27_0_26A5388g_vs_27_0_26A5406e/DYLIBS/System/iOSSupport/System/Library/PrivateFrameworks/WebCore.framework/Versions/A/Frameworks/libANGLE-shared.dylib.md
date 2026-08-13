## libANGLE-shared.dylib

> `/System/iOSSupport/System/Library/PrivateFrameworks/WebCore.framework/Versions/A/Frameworks/libANGLE-shared.dylib`

### Sections with Same Size but Changed Content

- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_selrefs`
- `__AUTH_CONST.__const`
- `__AUTH_CONST.__cfstring`
- `__AUTH_CONST.__weak_auth_got`
- `__DATA.__data`
- `__DATA_DIRTY.__data`

```diff

-625.1.24.11.2
-  __TEXT.__text: 0x2588a4
-  __TEXT.__const: 0x84140
-  __TEXT.__cstring: 0x44e6c
+625.1.29.11.2
+  __TEXT.__text: 0x258b58
+  __TEXT.__const: 0x84180
+  __TEXT.__cstring: 0x450f5
   __TEXT.__gcc_except_tab: 0x2c60
   __TEXT.__oslogstring: 0xf
-  __TEXT.__unwind_info: 0x92a0
+  __TEXT.__unwind_info: 0x92a8
   __TEXT.__objc_stubs: 0x0
   __TEXT.__auth_stubs: 0x0
   __TEXT.__objc_methname: 0x0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libobjc.A.dylib
   - /usr/lib/libz.1.dylib
-  Functions: 9085
-  Symbols:   13515
-  CStrings:  7017
+  Functions: 9086
+  Symbols:   13516
+  CStrings:  7020
 
Symbols:
+ __ZN12_GLOBAL__N_114ProgramPrelude9negateIntEv
+ __ZN2gl33ValidateDrawElementsInstancedBaseEPKNS_7ContextEN5angle10EntryPointENS_13PrimitiveModeEiNS_16DrawElementsTypeEPKviij
- __ZN2gl33ValidateDrawElementsInstancedBaseEPKNS_7ContextEN5angle10EntryPointENS_13PrimitiveModeEiNS_16DrawElementsTypeEPKvij
CStrings:
+ "\ntemplate <typename T, int N>\nstruct ANGLE_VectorElemRef\n{\n    thread metal::vec<T, N> &mVec;\n    T mRef;\n    const int mIndex;\n    ~ANGLE_VectorElemRef() { mVec[mIndex] = mRef; }\n    ANGLE_VectorElemRef(thread metal::vec<T, N> &vec, int index)\n        : mVec(vec), mRef(vec[index]), mIndex(index)\n    {}\n    operator thread T &() thread { return mRef; }\n};\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_VectorElemRef<T, N> ANGLE_elem_ref(thread metal::vec<T, N> &vec, int index)\n{\n    return ANGLE_VectorElemRef<T, N>(vec, metal::clamp(index, 0, N - 1));\n}\n\n"
+ "\ntemplate <typename T, int VN, int SN>\nstruct ANGLE_SwizzleRef\n{\n    thread metal::vec<T, VN> &mVec;\n    metal::vec<T, SN> mRef;\n    int mIndices[SN];\n    ~ANGLE_SwizzleRef()\n    {\n        for (int i = 0; i < SN; ++i)\n        {\n            const int j = mIndices[i];\n            mVec[j] = mRef[i];\n        }\n    }\n    ANGLE_SwizzleRef(thread metal::vec<T, VN> &vec, thread const int *indices)\n        : mVec(vec)\n    {\n        for (int i = 0; i < SN; ++i)\n        {\n            const int j = indices[i];\n            mIndices[i] = j;\n            mRef[i] = mVec[j];\n        }\n    }\n    operator thread metal::vec<T, SN> &() thread { return mRef; }\n};\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_VectorElemRef<T, N> ANGLE_swizzle_ref(thread metal::vec<T, N> &vec, int i0)\n{\n    return ANGLE_VectorElemRef<T, N>(vec, i0);\n}\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_SwizzleRef<T, N, 2> ANGLE_swizzle_ref(thread metal::vec<T, N> &vec, int i0, int i1)\n{\n    const int is[] = { i0, i1 };\n    return ANGLE_SwizzleRef<T, N, 2>(vec, is);\n}\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_SwizzleRef<T, N, 3> ANGLE_swizzle_ref(thread metal::vec<T, N> &vec, int i0, int i1, int i2)\n{\n    const int is[] = { i0, i1, i2 };\n    return ANGLE_SwizzleRef<T, N, 3>(vec, is);\n}\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_SwizzleRef<T, N, 4> ANGLE_swizzle_ref(thread metal::vec<T, N> &vec, int i0, int i1, int i2, int i3)\n{\n    const int is[] = { i0, i1, i2, i3 };\n    return ANGLE_SwizzleRef<T, N, 4>(vec, is);\n}\n\n"
+ "\ntemplate <typename T>\nANGLE_ALWAYS_INLINE T ANGLE_negateInt(T x)\n{\n    return as_type<T>(metal::make_unsigned_t<T>(0) - metal::make_unsigned_t<T>(x));\n}\n\n"
+ "\ntemplate <typename T>\nstruct ANGLE_InOut\n{\n    T mTemp;\n    thread T &mDest;\n    ~ANGLE_InOut() { mDest = mTemp; }\n    ANGLE_InOut(thread T &dest)\n        : mTemp(dest), mDest(dest)\n    {}\n    operator thread T &() thread { return mTemp; }\n};\ntemplate <typename T>\nANGLE_ALWAYS_INLINE ANGLE_InOut<T> ANGLE_inout(thread T &dest)\n{\n    return ANGLE_InOut<T>(dest);\n}\n\n"
+ "\ntemplate <typename T>\nstruct ANGLE_Out\n{\n    T mTemp;\n    thread T &mDest;\n    ~ANGLE_Out() { mDest = mTemp; }\n    ANGLE_Out(thread T &dest)\n        : mTemp(dest), mDest(dest)\n    {}\n    operator thread T &() thread { return mTemp; }\n};\ntemplate <typename T>\nANGLE_ALWAYS_INLINE ANGLE_Out<T> ANGLE_out(thread T &dest)\n{\n    return ANGLE_Out<T>(dest);\n}\n\n"
+ "\ntemplate<typename X, typename Y, typename Z = metal::conditional_t<metal::is_scalar_v<Y>, X, Y>>\nANGLE_ALWAYS_INLINE Z ANGLE_div(X x, Y y)\n{\n    Z zx = Z(x);\n    Z zy = Z(y);\n    if constexpr (metal::is_signed_v<Z>) {\n        using U = metal::make_unsigned_t<Z>;\n        Z safeY = metal::select(zy, Z(1), zy == Z(0));\n        auto isNegOne = safeY == Z(-1);\n        safeY = metal::select(safeY, Z(1), isNegOne);\n        Z q = zx / safeY;\n        return metal::select(q, as_type<Z>(U(0) - U(zx)), isNegOne);\n    } else {\n        return zx / metal::select(zy, Z(1), zy == Z(0));\n    }\n}\n\n"
+ "\ntemplate<typename X, typename Y, typename Z = metal::conditional_t<metal::is_scalar_v<Y>, X, Y>>\nANGLE_ALWAYS_INLINE Z ANGLE_imod(X x, Y y)\n{\n    if constexpr (metal::is_signed_v<Z>) {\n        Z y_or_one = metal::select(Z(y), Z(1), Z(y) == Z(0));\n        y_or_one = metal::select(y_or_one, Z(1), y_or_one == Z(-1));\n        if (metal::any(((Z(x) | y_or_one) & Z(2147483648u)) != Z(0u)))\n        {\n            return as_type<Z>(\n                metal::make_unsigned_t<Z>(x) - metal::make_unsigned_t<Z>(x / y_or_one) * metal::make_unsigned_t<Z>(y_or_one)\n            );\n        }\n        else\n        {\n            return x % y_or_one;\n        }\n    }\n    else\n    {\n        return x % metal::select(Z(y), Z(1u), Z(y) == Z(0u));\n    }\n}\n\n"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/common/aligned_memory.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/common/android_util.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/common/apple_platform_utils.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/compiler/translator/IntermNode.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/image_util/loadimage_astc.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/BlobCache.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Context.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Debug.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Display.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/GLES1Renderer.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/HandleAllocator.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Platform.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Program.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Shader.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/State.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Surface.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Texture.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/angletypes.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/queryconversions.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/BufferMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/ContextMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/DisplayMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/FrameBufferMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/IOSurfaceSurfaceMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/ProgramExecutableMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/ProvokingVertexHelper.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/RenderBufferMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/SurfaceMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/TextureMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/TransformFeedbackMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/VertexArrayMtl.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_command_buffer.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_context_device.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_pipeline_cache.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_render_utils.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_resources.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_utils.mm"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/renderer_utils.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/validationES.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.ZrmQgC/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/validationES2.cpp"
+ "ANGLE_negateInt"
+ "Effective vertex index (index + basevertex) is negative."
- "\ntemplate <typename T, int N>\nstruct ANGLE_VectorElemRef\n{\n    thread metal::vec<T, N> &mVec;\n    T mRef;\n    const int mIndex;\n    ~ANGLE_VectorElemRef() { mVec[mIndex] = mRef; }\n    ANGLE_VectorElemRef(thread metal::vec<T, N> &vec, int index)\n        : mVec(vec), mRef(vec[index]), mIndex(index)\n    {}\n    operator thread T &() { return mRef; }\n};\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_VectorElemRef<T, N> ANGLE_elem_ref(thread metal::vec<T, N> &vec, int index)\n{\n    return ANGLE_VectorElemRef<T, N>(vec, metal::clamp(index, 0, N - 1));\n}\n\n"
- "\ntemplate <typename T, int VN, int SN>\nstruct ANGLE_SwizzleRef\n{\n    thread metal::vec<T, VN> &mVec;\n    metal::vec<T, SN> mRef;\n    int mIndices[SN];\n    ~ANGLE_SwizzleRef()\n    {\n        for (int i = 0; i < SN; ++i)\n        {\n            const int j = mIndices[i];\n            mVec[j] = mRef[i];\n        }\n    }\n    ANGLE_SwizzleRef(thread metal::vec<T, VN> &vec, thread const int *indices)\n        : mVec(vec)\n    {\n        for (int i = 0; i < SN; ++i)\n        {\n            const int j = indices[i];\n            mIndices[i] = j;\n            mRef[i] = mVec[j];\n        }\n    }\n    operator thread metal::vec<T, SN> &() { return mRef; }\n};\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_VectorElemRef<T, N> ANGLE_swizzle_ref(thread metal::vec<T, N> &vec, int i0)\n{\n    return ANGLE_VectorElemRef<T, N>(vec, i0);\n}\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_SwizzleRef<T, N, 2> ANGLE_swizzle_ref(thread metal::vec<T, N> &vec, int i0, int i1)\n{\n    const int is[] = { i0, i1 };\n    return ANGLE_SwizzleRef<T, N, 2>(vec, is);\n}\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_SwizzleRef<T, N, 3> ANGLE_swizzle_ref(thread metal::vec<T, N> &vec, int i0, int i1, int i2)\n{\n    const int is[] = { i0, i1, i2 };\n    return ANGLE_SwizzleRef<T, N, 3>(vec, is);\n}\ntemplate <typename T, int N>\nANGLE_ALWAYS_INLINE ANGLE_SwizzleRef<T, N, 4> ANGLE_swizzle_ref(thread metal::vec<T, N> &vec, int i0, int i1, int i2, int i3)\n{\n    const int is[] = { i0, i1, i2, i3 };\n    return ANGLE_SwizzleRef<T, N, 4>(vec, is);\n}\n\n"
- "\ntemplate <typename T>\nstruct ANGLE_InOut\n{\n    T mTemp;\n    thread T &mDest;\n    ~ANGLE_InOut() { mDest = mTemp; }\n    ANGLE_InOut(thread T &dest)\n        : mTemp(dest), mDest(dest)\n    {}\n    operator thread T &() { return mTemp; }\n};\ntemplate <typename T>\nANGLE_ALWAYS_INLINE ANGLE_InOut<T> ANGLE_inout(thread T &dest)\n{\n    return ANGLE_InOut<T>(dest);\n}\n\n"
- "\ntemplate <typename T>\nstruct ANGLE_Out\n{\n    T mTemp;\n    thread T &mDest;\n    ~ANGLE_Out() { mDest = mTemp; }\n    ANGLE_Out(thread T &dest)\n        : mTemp(dest), mDest(dest)\n    {}\n    operator thread T &() { return mTemp; }\n};\ntemplate <typename T>\nANGLE_ALWAYS_INLINE ANGLE_Out<T> ANGLE_out(thread T &dest)\n{\n    return ANGLE_Out<T>(dest);\n}\n\n"
- "\ntemplate<typename X, typename Y, typename Z = metal::conditional_t<metal::is_scalar_v<Y>, X, Y>>\nANGLE_ALWAYS_INLINE Z ANGLE_div(X x, Y y)\n{\n    Z zx = Z(x);\n    Z zy = Z(y);\n    auto predicate = zy == Z(0);\n    return zx / metal::select(zy, Z(1), predicate);\n}\n\n"
- "\ntemplate<typename X, typename Y, typename Z = metal::conditional_t<metal::is_scalar_v<Y>, X, Y>>\nANGLE_ALWAYS_INLINE Z ANGLE_imod(X x, Y y)\n{\n    if constexpr (metal::is_signed_v<Z>) {\n        Z y_or_one = metal::select(Z(y), Z(1), Z(y) == Z(0));\n        if (metal::any(((Z(x) | y_or_one) & Z(2147483648u)) != Z(0u)))\n        {\n            return as_type<Z>(\n                metal::make_unsigned_t<Z>(x) - metal::make_unsigned_t<Z>(x / y_or_one) * metal::make_unsigned_t<Z>(y_or_one)\n            );\n        }\n        else\n        {\n            return x % y_or_one;\n        }\n    }\n    else\n    {\n        return x % metal::select(Z(y), Z(1u), Z(y) == Z(0u));\n    }\n}\n\n"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/common/aligned_memory.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/common/android_util.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/common/apple_platform_utils.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/compiler/translator/IntermNode.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/image_util/loadimage_astc.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/BlobCache.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Context.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Debug.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Display.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/GLES1Renderer.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/HandleAllocator.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Platform.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Program.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Shader.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/State.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Surface.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/Texture.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/angletypes.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/queryconversions.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/BufferMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/ContextMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/DisplayMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/FrameBufferMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/IOSurfaceSurfaceMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/ProgramExecutableMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/ProvokingVertexHelper.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/RenderBufferMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/SurfaceMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/TextureMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/TransformFeedbackMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/VertexArrayMtl.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_command_buffer.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_context_device.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_pipeline_cache.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_render_utils.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_resources.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/metal/mtl_utils.mm"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/renderer/renderer_utils.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/validationES.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.wQUhk7/Sources/ANGLE_iosmac/Source/ThirdParty/ANGLE/src/libANGLE/validationES2.cpp"
```
