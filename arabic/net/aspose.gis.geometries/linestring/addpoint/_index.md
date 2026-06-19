---
title: "LineString.AddPoint"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة LineString. تضيف نقطة إلى نهاية الخط"
type: docs
weight: 110
url: /ar/net/aspose.gis.geometries/linestring/addpoint/
---
## AddPoint(IPoint) {#addpoint}

يضيف نقطة إلى نهاية الخط.

```csharp
public void AddPoint(IPoint point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نقطة | IPoint | النقطة لإضافتها. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | المعامل فارغ (دالته [`IsEmpty`](../../igeometry/isempty/) هي `true`). |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) لهذا الشكل و[`SpatialReferenceSystem`](../spatialreferencesystem/) للمعامل كلاهما ليس `null` ولا يساويان بعضهما البعض. |

### انظر أيضًا

* interface [IPoint](../../ipoint/)
* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)

---

## AddPoint(double, double) {#addpoint_1}

يضيف نقطة إلى نهاية الخط.

```csharp
public void AddPoint(double x, double y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | القيمة لمحور X. |
| y | Double | القيمة لمحور Y. |

### انظر أيضًا

* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)

---

## AddPoint(double, double, double) {#addpoint_2}

يضيف نقطة إلى نهاية الخط.

```csharp
public void AddPoint(double x, double y, double z)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | القيمة لمحور X. |
| y | Double | القيمة لمحور Y. |
| z | Double | القيمة لمحور Z. |

### انظر أيضًا

* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)

---

## AddPoint(double, double, double, double) {#addpoint_3}

يضيف نقطة إلى نهاية الخط.

```csharp
public void AddPoint(double x, double y, double z, double m)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | القيمة لمحور X. |
| y | Double | القيمة لمحور Y. |
| z | Double | القيمة لمحور Z. |
| m | Double | القيمة لمحور M. |

### انظر أيضًا

* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)


