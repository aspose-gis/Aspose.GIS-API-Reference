---
title: "IGeometry.GetConvexHull"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحسب الغلاف المحدب لهذه الهندسة"
type: docs
weight: 220
url: /ar/net/aspose.gis.geometries/igeometry/getconvexhull/
---
## IGeometry.GetConvexHull method

يحسب الغلاف المحدب لهذه الهندسة.

```csharp
public IGeometry GetConvexHull()
```

### قيمة الإرجاع

هندسة تمثل الغلاف المحدب لهذه الهندسة. إذا كانت هذه الهندسة لا تحتوي على نقاط فإن النتيجة هي [`Null`](../../geometry/null/). إذا كانت هذه الهندسة تحتوي على نقطة واحدة فقط فإن النتيجة هي تلك النقطة. إذا كانت هذه الهندسة تحتوي على نقطتين فقط فإن النتيجة هي [`ILineString`](../../ilinestring/) مع النقاط. إذا كانت هذه الهندسة تحتوي على ثلاث نقاط أو أكثر فإن النتيجة هي [`ILinearRing`](../../ilinearring/) التي تمثل غلافًا محدبًا حول جميع نقاط الهندسة.

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


