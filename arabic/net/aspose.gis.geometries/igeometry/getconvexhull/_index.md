---
title: "IGeometry.GetConvexHull"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحسب الغلاف المحدب لهذا الشكل الهندسي"
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

شكل هندسي يمثل غلافًا محدبًا لهذا الشكل الهندسي. إذا لم يكن لهذا الشكل الهندسي أي نقاط فإن النتيجة هي [`Null`](../../geometry/null/). إذا كان لهذا الشكل الهندسي نقطة واحدة فقط فإن النتيجة هي تلك النقطة. إذا كان لهذا الشكل الهندسي نقطتين فقط فإن النتيجة هي [`ILineString`](../../ilinestring/) مع النقاط. إذا كان لهذا الشكل الهندسي ثلاث نقاط أو أكثر فإن النتيجة هي [`ILinearRing`](../../ilinearring/) التي تمثل غلافًا محدبًا حول جميع نقاط الأشكال الهندسية.

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


