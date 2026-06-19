---
title: "SpatialReferenceSystem.CreateTransformationTo"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. تنشئ تحويلًا من هذا SpatialReferenceSystem إلى SpatialReferenceSystem آخر"
type: docs
weight: 180
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/
---
## SpatialReferenceSystem.CreateTransformationTo method

ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر.

```csharp
public SpatialReferenceSystemTransformation CreateTransformationTo(SpatialReferenceSystem targetSrs)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| targetSrs | SpatialReferenceSystem | آخر `SpatialReferenceSystem`. |

### قيمة الإرجاع

تحويل من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر.

### استثناءات

| استثناء | شرط |
| --- | --- |
| NotSupportedException | التحويل بين هذا `SpatialReferenceSystem` والوسيط غير مدعوم. قد يحدث هذا لأن أحد الإسقاطات غير مدعوم، أو أحد الأنظمة هو [`VerticalSpatialReferenceSystem`](../../verticalspatialreferencesystem/) أو [`LocalSpatialReferenceSystem`](../../localspatialreferencesystem/). |
| [TransformationException](../../transformationexception/) | فشل إنشاء التحويل بسبب معلمات خاطئة داخل `SpatialReferenceSystem`. |

### انظر أيضًا

* method [TryCreateTransformationTo](../trycreatetransformationto/)
* class [SpatialReferenceSystemTransformation](../../spatialreferencesystemtransformation/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


