---
title: "GeometryCollection.Add"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeometryCollection. تضيف الهندسة المحددة إلى المجموعة"
type: docs
weight: 110
url: /ar/net/aspose.gis.geometries/geometrycollection/add/
---
## GeometryCollection.Add method

يضيف الشكل المحدد إلى المجموعة.

```csharp
public void Add(IGeometry geometry)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| هندسة | IGeometry | الهندسة المراد إضافتها. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | المجموعة لا تقبل الهندسات من هذا النوع. |
| ArgumentException | الـ[`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) لهذا الشكل و[`SpatialReferenceSystem`](../spatialreferencesystem/) للمعامل كلاهما ليسا `null` ولا يتساويان. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [GeometryCollection](../)
* namespace [Aspose.Gis.Geometries](../../geometrycollection/)
* assembly [Aspose.GIS](../../../)


