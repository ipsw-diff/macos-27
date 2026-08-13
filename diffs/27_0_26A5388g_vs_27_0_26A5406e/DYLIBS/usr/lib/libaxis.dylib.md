## libaxis.dylib

> `/usr/lib/libaxis.dylib`

### Sections with Same Size but Changed Content

- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__got`
- `__AUTH_CONST.__weak_auth_got`
- `__AUTH.__data`

```diff

-8.1.9.0.0
-  __TEXT.__text: 0x54d4ac
-  __TEXT.__gcc_except_tab: 0x481f0
-  __TEXT.__cstring: 0x16f65
-  __TEXT.__const: 0xf3f4
-  __TEXT.__unwind_info: 0x118a0
+8.1.11.0.0
+  __TEXT.__text: 0x554794
+  __TEXT.__gcc_except_tab: 0x48928
+  __TEXT.__cstring: 0x16f7b
+  __TEXT.__const: 0xf5a4
+  __TEXT.__unwind_info: 0x11b50
   __TEXT.__eh_frame: 0x80
   __TEXT.__auth_stubs: 0x0
   __DATA_CONST.__const: 0xc0
-  __DATA_CONST.__weak_got: 0x640
+  __DATA_CONST.__weak_got: 0x680
   __DATA_CONST.__got: 0x1a8
-  __AUTH_CONST.__const: 0x9120
+  __AUTH_CONST.__const: 0x9138
   __AUTH_CONST.__weak_auth_got: 0x440
   __AUTH_CONST.__auth_got: 0x0
   __AUTH.__data: 0x10
   __AUTH.__thread_vars: 0x288
   __AUTH.__thread_data: 0x10
   __AUTH.__thread_bss: 0x180
-  __DATA.__data: 0x1800
+  __DATA.__data: 0x1840
   __DATA.__bss: 0x13ee8
   __DATA.__common: 0x8
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libc++.1.dylib
-  Functions: 9921
-  Symbols:   2753
-  CStrings:  1930
+  Functions: 9987
+  Symbols:   2774
+  CStrings:  1931
 
Symbols:
+ __ZGVZNK4axis16DynamicIndexImpl22find_intersects_workerINS_10Triangle2DEEENSt3__13setIPNS_18DynamicIndexHandleENS3_4lessIS6_EENS3_9allocatorIS6_EEEERKT_E3acc
+ __ZGVZNK4axis16DynamicIndexImpl27find_within_distance_workerINS_10Triangle2DEEENSt3__13mapIPNS_18DynamicIndexHandleEdNS3_4lessIS6_EENS3_9allocatorINS3_4pairIKS6_dEEEEEERKT_dE3acc
+ __ZGVZNK4axis16DynamicIndexImpl27find_within_distance_workerINS_6BBox2DEEENSt3__13mapIPNS_18DynamicIndexHandleEdNS3_4lessIS6_EENS3_9allocatorINS3_4pairIKS6_dEEEEEERKT_dE3acc
+ __ZGVZNK4axis16DynamicIndexImpl29find_nearest_neighbors_workerINS_10Triangle2DEEENSt3__16vectorINS3_4pairIPNS_18DynamicIndexHandleEdEENS3_9allocatorIS8_EEEERKT_mdE3acc
+ __ZGVZNK4axis16DynamicIndexImpl29find_nearest_neighbors_workerINS_6BBox2DEEENSt3__16vectorINS3_4pairIPNS_18DynamicIndexHandleEdEENS3_9allocatorIS8_EEEERKT_mdE3acc
+ __ZGVZNK4axis16SpatialIndexImpl22find_intersects_workerINS_10Triangle2DEEENSt3__13setImNS3_4lessImEENS3_9allocatorImEEEERKT_E3acc
+ __ZGVZNK4axis16SpatialIndexImpl27find_within_distance_workerINS_10Triangle2DEEENSt3__13mapImdNS3_4lessImEENS3_9allocatorINS3_4pairIKmdEEEEEERKT_dE3acc
+ __ZGVZNK4axis16SpatialIndexImpl27find_within_distance_workerINS_6BBox2DEEENSt3__13mapImdNS3_4lessImEENS3_9allocatorINS3_4pairIKmdEEEEEERKT_dE3acc
+ __ZGVZNK4axis16SpatialIndexImpl29find_nearest_neighbors_workerINS_10Triangle2DEEENSt3__16vectorINS3_4pairImdEENS3_9allocatorIS6_EEEERKT_mdE3acc
+ __ZGVZNK4axis16SpatialIndexImpl29find_nearest_neighbors_workerINS_6BBox2DEEENSt3__16vectorINS3_4pairImdEENS3_9allocatorIS6_EEEERKT_mdE3acc
+ __ZNK4axis10Triangle2D16distance_squaredERKNS_11PointData2DE
+ __ZNK4axis10Triangle2D16distance_squaredERKNS_9LineSeg2DE
+ __ZNK4axis10Triangle2D16distance_squaredERKS0_
+ __ZNK4axis16DynamicIndexImpl15find_intersectsERKNS_10Triangle2DE
+ __ZNK4axis16DynamicIndexImpl20find_within_distanceERKNS_10Triangle2DEd
+ __ZNK4axis16DynamicIndexImpl20find_within_distanceERKNS_6BBox2DEd
+ __ZNK4axis16DynamicIndexImpl24find_k_nearest_neighborsERKNS_10Triangle2DEmd
+ __ZNK4axis16DynamicIndexImpl24find_k_nearest_neighborsERKNS_6BBox2DEmd
+ __ZNK4axis16SpatialIndexImpl15find_intersectsERKNS_10Triangle2DE
+ __ZNK4axis16SpatialIndexImpl20find_within_distanceERKNS_10Triangle2DEd
+ __ZNK4axis16SpatialIndexImpl20find_within_distanceERKNS_6BBox2DEd
+ __ZNK4axis16SpatialIndexImpl24find_k_nearest_neighborsERKNS_10Triangle2DEmd
+ __ZNK4axis16SpatialIndexImpl24find_k_nearest_neighborsERKNS_6BBox2DEmd
+ __ZNK4axis6BBox2D16distance_squaredERKNS_10Triangle2DE
+ __ZNK4axis6BBox2D16distance_squaredERKS0_
+ __ZZNK4axis16DynamicIndexImpl22find_intersects_workerINS_10Triangle2DEEENSt3__13setIPNS_18DynamicIndexHandleENS3_4lessIS6_EENS3_9allocatorIS6_EEEERKT_E3acc
+ __ZZNK4axis16DynamicIndexImpl27find_within_distance_workerINS_10Triangle2DEEENSt3__13mapIPNS_18DynamicIndexHandleEdNS3_4lessIS6_EENS3_9allocatorINS3_4pairIKS6_dEEEEEERKT_dE3acc
+ __ZZNK4axis16DynamicIndexImpl27find_within_distance_workerINS_6BBox2DEEENSt3__13mapIPNS_18DynamicIndexHandleEdNS3_4lessIS6_EENS3_9allocatorINS3_4pairIKS6_dEEEEEERKT_dE3acc
+ __ZZNK4axis16DynamicIndexImpl29find_nearest_neighbors_workerINS_10Triangle2DEEENSt3__16vectorINS3_4pairIPNS_18DynamicIndexHandleEdEENS3_9allocatorIS8_EEEERKT_mdE3acc
+ __ZZNK4axis16DynamicIndexImpl29find_nearest_neighbors_workerINS_6BBox2DEEENSt3__16vectorINS3_4pairIPNS_18DynamicIndexHandleEdEENS3_9allocatorIS8_EEEERKT_mdE3acc
+ __ZZNK4axis16SpatialIndexImpl22find_intersects_workerINS_10Triangle2DEEENSt3__13setImNS3_4lessImEENS3_9allocatorImEEEERKT_E3acc
+ __ZZNK4axis16SpatialIndexImpl27find_within_distance_workerINS_10Triangle2DEEENSt3__13mapImdNS3_4lessImEENS3_9allocatorINS3_4pairIKmdEEEEEERKT_dE3acc
+ __ZZNK4axis16SpatialIndexImpl27find_within_distance_workerINS_6BBox2DEEENSt3__13mapImdNS3_4lessImEENS3_9allocatorINS3_4pairIKmdEEEEEERKT_dE3acc
+ __ZZNK4axis16SpatialIndexImpl29find_nearest_neighbors_workerINS_10Triangle2DEEENSt3__16vectorINS3_4pairImdEENS3_9allocatorIS6_EEEERKT_mdE3acc
+ __ZZNK4axis16SpatialIndexImpl29find_nearest_neighbors_workerINS_6BBox2DEEENSt3__16vectorINS3_4pairImdEENS3_9allocatorIS6_EEEERKT_mdE3acc
- __ZGVZNK4axis16DynamicIndexImpl22find_intersects_workerINS_7Point2DEEENSt3__13setIPNS_18DynamicIndexHandleENS3_4lessIS6_EENS3_9allocatorIS6_EEEERKT_E3acc
- __ZGVZNK4axis16DynamicIndexImpl27find_within_distance_workerINS_7Point2DEEENSt3__13mapIPNS_18DynamicIndexHandleEdNS3_4lessIS6_EENS3_9allocatorINS3_4pairIKS6_dEEEEEERKT_dE3acc
- __ZGVZNK4axis16DynamicIndexImpl29find_nearest_neighbors_workerINS_7Point2DEEENSt3__16vectorINS3_4pairIPNS_18DynamicIndexHandleEdEENS3_9allocatorIS8_EEEERKT_mdE3acc
- __ZGVZNK4axis16SpatialIndexImpl22find_intersects_workerINS_7Point2DEEENSt3__13setImNS3_4lessImEENS3_9allocatorImEEEERKT_E3acc
- __ZGVZNK4axis16SpatialIndexImpl27find_within_distance_workerINS_7Point2DEEENSt3__13mapImdNS3_4lessImEENS3_9allocatorINS3_4pairIKmdEEEEEERKT_dE3acc
- __ZGVZNK4axis16SpatialIndexImpl29find_nearest_neighbors_workerINS_7Point2DEEENSt3__16vectorINS3_4pairImdEENS3_9allocatorIS6_EEEERKT_mdE3acc
- __ZNK4axis10Triangle2D8distanceERKNS_11PointData2DE
- __ZNK4axis10Triangle2D8distanceERKNS_9LineSeg2DE
- __ZZNK4axis16DynamicIndexImpl22find_intersects_workerINS_7Point2DEEENSt3__13setIPNS_18DynamicIndexHandleENS3_4lessIS6_EENS3_9allocatorIS6_EEEERKT_E3acc
- __ZZNK4axis16DynamicIndexImpl27find_within_distance_workerINS_7Point2DEEENSt3__13mapIPNS_18DynamicIndexHandleEdNS3_4lessIS6_EENS3_9allocatorINS3_4pairIKS6_dEEEEEERKT_dE3acc
- __ZZNK4axis16DynamicIndexImpl29find_nearest_neighbors_workerINS_7Point2DEEENSt3__16vectorINS3_4pairIPNS_18DynamicIndexHandleEdEENS3_9allocatorIS8_EEEERKT_mdE3acc
- __ZZNK4axis16SpatialIndexImpl22find_intersects_workerINS_7Point2DEEENSt3__13setImNS3_4lessImEENS3_9allocatorImEEEERKT_E3acc
- __ZZNK4axis16SpatialIndexImpl27find_within_distance_workerINS_7Point2DEEENSt3__13mapImdNS3_4lessImEENS3_9allocatorINS3_4pairIKmdEEEEEERKT_dE3acc
- __ZZNK4axis16SpatialIndexImpl29find_nearest_neighbors_workerINS_7Point2DEEENSt3__16vectorINS3_4pairImdEENS3_9allocatorIS6_EEEERKT_mdE3acc
CStrings:
+ ") RowsColumns( "
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/CGAL/Segment_Delaunay_graph_adapter_2.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/CGAL/Triangulation_adapter_2.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/Angle.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/AxisCompressionDecoder.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/AxisCompressionEncoderImpl.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/AxisCompressionHeader.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/Boundary.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/CDT.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/ChaikinRefiner.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/Clipper.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/ConcaveHull.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/DE9IM.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/Diameter.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/DuplicatePointRemover.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/HausdorffSquaredDistance.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/InteriorPoint.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/Interpolate.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/NormalFormCompare.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/PolesOfInaccessibility.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/SegmentDelaunay.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/SegmentDelaunayImpl.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/SegmentDelaunayTraits.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/Simplification.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/Smoothing.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/algorithm/Stitcher.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/geometry/Polygon2D.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/geometry/Triangle2D.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/geometry/VertexChain.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/index/ClosestFeatureIndexWrapper.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/io/ACFReader.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/io/WKBWriter.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/misc/Dispatch.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/Covers.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/Covers.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/Crosses.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/DispatchPredicate.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/GetDE9IM.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/Intersects.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/Overlaps.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/PointGeometryEquals.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/PointGeometryIntersects.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/Touches.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/predicates/Within.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/axis/triangulation/PolygonExtractor.hpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/algorithm/Angle3D.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/algorithm/CutAndReplace.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/algorithm/From2D.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/algorithm/MeshRefine.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/algorithm/MeshStitcher.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/algorithm/NormalForm3D.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/algorithm/PolylineCompression.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/algorithm/TerrainSimplificationImpl.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/geometry/BasicMeshUtils.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/geometry/GeoRaster.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.K5Cr2H/Sources/AxisGeometry/src/terra/geometry/TriangulatedTerrain.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PgXYIA/Sources/LEDA/incl/LEDA/numbers/interval.h"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PgXYIA/Sources/LEDA/src/core/basic/_dlist.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PgXYIA/Sources/LEDA/src/core/basic/_string.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PgXYIA/Sources/LEDA/src/numbers/types/_bigfloat.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PgXYIA/Sources/LEDA/src/numbers/types/_digit_vector.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PgXYIA/Sources/LEDA/src/numbers/types/_integer.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PgXYIA/Sources/LEDA/src/numbers/types/_rational.cpp"
+ "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.PgXYIA/Sources/LEDA/src/numbers/types/_real.cpp"
+ "[BBox2D] logic error"
- " RowsColumns( "
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/CGAL/Segment_Delaunay_graph_adapter_2.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/CGAL/Triangulation_adapter_2.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/Angle.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/AxisCompressionDecoder.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/AxisCompressionEncoderImpl.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/AxisCompressionHeader.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/Boundary.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/CDT.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/ChaikinRefiner.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/Clipper.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/ConcaveHull.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/DE9IM.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/Diameter.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/DuplicatePointRemover.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/HausdorffSquaredDistance.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/InteriorPoint.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/Interpolate.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/NormalFormCompare.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/PolesOfInaccessibility.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/SegmentDelaunay.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/SegmentDelaunayImpl.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/SegmentDelaunayTraits.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/Simplification.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/Smoothing.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/algorithm/Stitcher.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/geometry/Polygon2D.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/geometry/Triangle2D.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/geometry/VertexChain.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/index/ClosestFeatureIndexWrapper.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/io/ACFReader.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/io/WKBWriter.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/misc/Dispatch.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/Covers.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/Covers.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/Crosses.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/DispatchPredicate.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/GetDE9IM.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/Intersects.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/Overlaps.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/PointGeometryEquals.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/PointGeometryIntersects.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/Touches.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/predicates/Within.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/axis/triangulation/PolygonExtractor.hpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/algorithm/Angle3D.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/algorithm/CutAndReplace.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/algorithm/From2D.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/algorithm/MeshRefine.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/algorithm/MeshStitcher.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/algorithm/NormalForm3D.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/algorithm/PolylineCompression.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/algorithm/TerrainSimplificationImpl.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/geometry/BasicMeshUtils.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/geometry/GeoRaster.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.84rSVn/Sources/AxisGeometry/src/terra/geometry/TriangulatedTerrain.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.WgslUu/Sources/LEDA/incl/LEDA/numbers/interval.h"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.WgslUu/Sources/LEDA/src/core/basic/_dlist.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.WgslUu/Sources/LEDA/src/core/basic/_string.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.WgslUu/Sources/LEDA/src/numbers/types/_bigfloat.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.WgslUu/Sources/LEDA/src/numbers/types/_digit_vector.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.WgslUu/Sources/LEDA/src/numbers/types/_integer.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.WgslUu/Sources/LEDA/src/numbers/types/_rational.cpp"
- "/AppleInternal/Library/BuildRoots/<BUILDROOT>/Library/Caches/com.apple.xbs/TemporaryDirectory.WgslUu/Sources/LEDA/src/numbers/types/_real.cpp"
```
