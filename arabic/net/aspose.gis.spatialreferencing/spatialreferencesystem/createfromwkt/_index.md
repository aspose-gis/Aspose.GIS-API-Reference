---
title: "SpatialReferenceSystem.CreateFromWkt"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. تنشئ SpatialReferenceSystem جديدة بناءً على سلسلة نصية WKT WellKnown Text"
type: docs
weight: 20
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/createfromwkt/
---
## SpatialReferenceSystem.CreateFromWkt method

ينشئ `SpatialReferenceSystem` جديدًا بناءً على سلسلة WKT (نص معروف جيدًا).

```csharp
public static SpatialReferenceSystem CreateFromWkt(string wkt)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| wkt | String | سلسلة WKT. |

### قيمة الإرجاع

جديد `SpatialReferenceSystem`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| FormatException | تسلسل قيم wkt، ترتيبها أو أنواعها، غير صحيح. |
| NotSupportedException | عنصر الجذر WKT غير مدعوم (على سبيل المثال هو FITTED_CS). |

### انظر أيضًا

* method [TryCreateFromWkt](../trycreatefromwkt/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


