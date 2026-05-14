---
title: "SpatialReferenceSystem.CreateProjected"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. أنشئ SRS مسقَّط من معلمات مخصصة"
type: docs
weight: 380
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/createprojected/
---
## SpatialReferenceSystem.CreateProjected method

إنشاء نظام إسناد إسقاطي من معلمات مخصصة.

```csharp
public static ProjectedSpatialReferenceSystem CreateProjected(
    ProjectedSpatialReferenceSystemParameters parameters, Identifier identifier = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المعلمات | ProjectedSpatialReferenceSystemParameters | المعلمات لإنشاء منها. |
| معرّف | معرّف | Identifier، الذي سيُرفق بـ SRS. إرفاق Identifier لن يغيّر معلمات SRS الأخرى. الأمر متروك لك لضمان اتساق Identifier ومعلمات SRS. |

### قيمة الإرجاع

نظام إحداثيات إسقاطي جديد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | نظام الإحداثيات الأساسي في المعلمات هو `null`. طريقة الإسقاط في المعلمات هي `null`. |

### انظر أيضًا

* class [ProjectedSpatialReferenceSystem](../../projectedspatialreferencesystem/)
* class [ProjectedSpatialReferenceSystemParameters](../../projectedspatialreferencesystemparameters/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


