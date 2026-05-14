---
title: "VectorLayer.NearestTo"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorLayer. الحصول على أقرب feature إلى الإحداثي المقدم"
type: docs
weight: 170
url: /ar/net/aspose.gis/vectorlayer/nearestto/
---
## NearestTo(double, double) {#nearestto_1}

يحصل على أقرب ميزة إلى الإحداثي المقدم.

```csharp
public Feature NearestTo(double x, double y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | X للإحداثي. |
| y | Double | Y للإحداثي. |

### قيمة الإرجاع

أقرب feature إلى الإحداثي المقدم.

### انظر أيضًا

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## NearestTo(IPoint) {#nearestto}

يحصل على أقرب ميزة إلى النقطة المقدمة.

```csharp
public Feature NearestTo(IPoint point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نقطة | IPoint | النقطة. |

### قيمة الإرجاع

أقرب feature إلى النقطة المقدمة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | النقطة هي `null`. |
| ArgumentException | النقطة فارغة أو غير صالحة. |

### انظر أيضًا

* class [Feature](../../feature/)
* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


