---
title: "Geometry.GetConvexHull"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحسب الغلاف المحدب لهذه الهندسة."
type: docs
weight: 230
url: /ar/net/aspose.gis.geometries/geometry/getconvexhull/
---
## Geometry.GetConvexHull method

يحسب الغلاف المحدب لهذه الهندسة.

```csharp
public IGeometry GetConvexHull()
```

### قيمة الإرجاع

هندسة تمثل الغلاف المحدب لهذه الهندسة. إذا لم تكن لهذه الهندسة أي نقاط فإن النتيجة هي [`Null`](../null/). إذا كان لديها نقطة واحدة فقط فإن النتيجة هي تلك النقطة. إذا كان لديها نقطتان فقط فإن النتيجة هي [`ILineString`](../../ilinestring/) مع النقطتين. إذا كان لديها ثلاث نقاط أو أكثر فإن النتيجة هي [`ILinearRing`](../../ilinearring/) الذي يمثل الغلاف المحدب حول جميع نقاط الهندسة.

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


