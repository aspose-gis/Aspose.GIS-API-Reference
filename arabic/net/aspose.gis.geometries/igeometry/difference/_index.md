---
title: "IGeometry.Difference"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تطرح شكلًا هندسيًا محددًا من هذا الشكل الهندسي"
type: docs
weight: 170
url: /ar/net/aspose.gis.geometries/igeometry/difference/
---
## IGeometry.Difference method

يطرح هندسة محددة من هذه الهندسة.

```csharp
public IGeometry Difference(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | شكل هندسي للطرح. |

### قيمة الإرجاع

شكل هندسي يمثل الفرق بين هذا الشكل الهندسي ومعامل. يحتوي الشكل الناتج على مجموعة نقاط موجودة في هذا الشكل الهندسي ولكن غير موجودة في المعامل.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *other* هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


