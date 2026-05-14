---
title: "SpatialReferenceSystem.CreateFromEpsg"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. إنشاء نظام إسناد مكاني بناءً على رمز EPSG المحدد"
type: docs
weight: 10
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/createfromepsg/
---
## SpatialReferenceSystem.CreateFromEpsg method

إنشاء نظام إحداثيات بناءً على رمز EPSG المحدد.

```csharp
public static SpatialReferenceSystem CreateFromEpsg(int epsg)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| epsg | Int32 | رمز EPSG لنظام الإسناد المكاني. |

### قيمة الإرجاع

نظام إسناد مكاني جديد بالرمز EPSG المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | المعطى ليس إيجابيًا. |
| NotSupportedException | رمز EPSG المحدد غير معروف. |

### انظر أيضًا

* method [TryCreateFromEpsg](../trycreatefromepsg/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


