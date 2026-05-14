---
title: "Geometry.FromBinary"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تنشئ شكلًا هندسيًا من تمثيله WellKnown Binary"
type: docs
weight: 470
url: /ar/net/aspose.gis.geometries/geometry/frombinary/
---
## FromBinary(byte[]) {#frombinary}

ينشئ شكلاً هندسياً من تمثيله الثنائي المعروف (Well-Known Binary).

```csharp
public static IGeometry FromBinary(byte[] wkb)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| wkb | Byte[] | تمثيل Well-Known Binary لشكل هندسي. |

### قيمة الإرجاع

شكل هندسي ممثل بالمعطى.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المعطى فارغ. |
| NotSupportedException | المعطى يمثل شكلًا هندسيًا من نوع غير مدعوم. |
| FormatException | المعامل ليس Well-Known Binary صالحًا. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## FromBinary(byte[], SpatialReferenceSystem) {#frombinary_1}

ينشئ شكلاً هندسياً من تمثيله الثنائي المعروف (Well-Known Binary).

```csharp
public static IGeometry FromBinary(byte[] wkb, SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| wkb | Byte[] | تمثيل Well-Known Binary لشكل هندسي. |
| spatialReferenceSystem | SpatialReferenceSystem | Spatial Reference System لتعيينه إلى الشكل الهندسي. |

### قيمة الإرجاع

شكل هندسي ممثل بالمعطى.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المعطى فارغ. |
| NotSupportedException | المعطى يمثل شكلًا هندسيًا من نوع غير مدعوم. |
| FormatException | المعامل ليس Well-Known Binary صالحًا. |

## ملاحظات

إذا كان هناك بايتات إضافية بعد الشكل الهندسي، يتم إلقاء استثناء FormatException.

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


