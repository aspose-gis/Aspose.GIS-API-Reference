---
title: "SpatialReferenceSystem.TryCreateFromEpsg"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. إنشاء نظام إسناد مكاني بناءً على رمز EPSG المحدد"
type: docs
weight: 400
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/trycreatefromepsg/
---
## SpatialReferenceSystem.TryCreateFromEpsg method

إنشاء نظام إحداثيات بناءً على رمز EPSG المحدد.

```csharp
public static bool TryCreateFromEpsg(int epsg, out SpatialReferenceSystem value)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| epsg | Int32 | رمز EPSG لنظام الإسناد المكاني. |
| قيمة | SpatialReferenceSystem& | عند إرجاع هذه الطريقة `true`، تحتوي على SRS بالرمز EPSG المحدد؛ وإلا، تحتوي على `null`. |

### قيمة الإرجاع

`true` إذا كان رمز EPSG المحدد معروفًا وتم إنشاء SRS؛ `false` خلاف ذلك.

### انظر أيضًا

* method [CreateFromEpsg](../createfromepsg/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


