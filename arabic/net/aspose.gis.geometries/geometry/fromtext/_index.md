---
title: "Geometry.FromText"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تنشئ شكلًا هندسيًا من تمثيله بنص Well-Known Text."
type: docs
weight: 480
url: /ar/net/aspose.gis.geometries/geometry/fromtext/
---
## FromText(string) {#fromtext}

ينشئ شكلاً هندسياً من تمثيله النصي المعروف (Well-Known Text).

```csharp
public static IGeometry FromText(string wkt)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| wkt | String | تمثيل نص Well-Known لشكل هندسي. |

### قيمة الإرجاع

شكل هندسي ممثل بالمعطى.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المعطى فارغ. |
| NotSupportedException | المعطى يمثل شكلًا هندسيًا من نوع غير مدعوم. |
| FormatException | المعامل ليس Well-Known Text صالحًا. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## FromText(string, SpatialReferenceSystem) {#fromtext_1}

ينشئ شكلاً هندسياً من تمثيله النصي المعروف (Well-Known Text).

```csharp
public static IGeometry FromText(string wkt, SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| wkt | String | تمثيل نص Well-Known لشكل هندسي. |
| spatialReferenceSystem | SpatialReferenceSystem | Spatial Reference System لتعيينه إلى الشكل الهندسي. |

### قيمة الإرجاع

شكل هندسي ممثل بالمعطى.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المعطى فارغ. |
| NotSupportedException | المعطى يمثل شكلًا هندسيًا من نوع غير مدعوم. |
| FormatException | المعامل ليس Well-Known Text صالحًا. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


