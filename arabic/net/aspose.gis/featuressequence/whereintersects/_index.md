---
title: "FeaturesSequence.WhereIntersects"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FeaturesSequence. تقوم بترشيح العناصر بناءً على اتحاد جميع الأشكال الهندسية في تسلسل العناصر الآخر"
type: docs
weight: 100
url: /ar/net/aspose.gis/featuressequence/whereintersects/
---
## WhereIntersects(FeaturesSequence) {#whereintersects_1}

يفلتر المعالم بناءً على اتحاد جميع الأشكال الهندسية في تسلسل المعالم الأخرى.

```csharp
public FeaturesSequence WhereIntersects(FeaturesSequence sequence)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تسلسل | FeaturesSequence | تسلسل العناصر الآخر. |

### قيمة الإرجاع

العناصر التي تتقاطع مع اتحاد جميع الأشكال الهندسية في تسلسل العناصر الآخر.

### انظر أيضًا

* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## WhereIntersects(IGeometry) {#whereintersects_2}

يفلتر المعالم بناءً على الشكل الهندسي المقدم.

```csharp
public virtual FeaturesSequence WhereIntersects(IGeometry geometry)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| هندسة | IGeometry | الجيومتري للترشيح. |

### قيمة الإرجاع

العناصر التي تتقاطع مع الشكل الهندسي المقدم.

### انظر أيضًا

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## WhereIntersects(Extent) {#whereintersects}

يفلتر المعالم بناءً على النطاق.

```csharp
public virtual FeaturesSequence WhereIntersects(Extent extent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مدى | مدى | الامتداد للترشيح. |

### قيمة الإرجاع

العناصر التي تتقاطع مع الشكل الهندسي المقدم.

### انظر أيضًا

* class [Extent](../../extent/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)


