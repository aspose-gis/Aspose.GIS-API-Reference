---
title: "CircularString.AddPoint"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة CircularString. تضيف نقطة إلى نهاية السلسلة الدائرية"
type: docs
weight: 120
url: /ar/net/aspose.gis.geometries/circularstring/addpoint/
---
## AddPoint(IPoint) {#addpoint}

يضيف نقطة إلى نهاية السلسلة الدائرية.

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
* class [CircularString](../)
* namespace [Aspose.Gis.Geometries](../../circularstring/)
* assembly [Aspose.GIS](../../../)

---

## AddPoint(double, double) {#addpoint_1}

يضيف نقطة إلى نهاية السلسلة الدائرية.

```csharp
public void AddPoint(double x, double y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | القيمة لمحور X. |
| y | Double | القيمة لمحور Y. |

### انظر أيضًا

* class [CircularString](../)
* namespace [Aspose.Gis.Geometries](../../circularstring/)
* assembly [Aspose.GIS](../../../)

---

## AddPoint(double, double, double) {#addpoint_2}

يضيف نقطة إلى نهاية السلسلة الدائرية.

```csharp
public void AddPoint(double x, double y, double z)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | القيمة لمحور X. |
| y | Double | القيمة لمحور Y. |
| z | Double | القيمة لمحور Z. |

### انظر أيضًا

* class [CircularString](../)
* namespace [Aspose.Gis.Geometries](../../circularstring/)
* assembly [Aspose.GIS](../../../)

---

## AddPoint(double, double, double, double) {#addpoint_3}

يضيف نقطة إلى نهاية السلسلة الدائرية.

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

* class [CircularString](../)
* namespace [Aspose.Gis.Geometries](../../circularstring/)
* assembly [Aspose.GIS](../../../)


