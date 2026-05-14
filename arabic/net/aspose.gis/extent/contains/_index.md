---
title: "Extent.Contains"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Extent. تحدد ما إذا كان هذا الامتداد يحتوي على إحداثي محدد بالوسائط"
type: docs
weight: 120
url: /ar/net/aspose.gis/extent/contains/
---
## Contains(double, double) {#contains_2}

يحدد ما إذا كان هذا الامتداد يحتوي على إحداثي معرف بالوسائط.

```csharp
public bool Contains(double x, double y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | X للإحداثي. |
| y | Double | Y للإحداثي. |

### قيمة الإرجاع

قيمة تشير إلى ما إذا كان الإحداثي داخل صندوق الحدود.

## ملاحظات

الإحداثيات الموجودة على حدود هذا [`Extent`](../) تُعتبر محتواة في هذا [`Extent`](../).

### انظر أيضًا

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)

---

## Contains(Extent) {#contains}

يحدد ما إذا كان هذا الامتداد يحتوي على الوسيط.

```csharp
public bool Contains(Extent extent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مدى | مدى | نطاق آخر. |

### قيمة الإرجاع

قيمة تشير إلى ما إذا كان هذا الامتداد يحتوي على الوسيط.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا النطاق والوسيط كلاهما ليس `null` وليسا متساويين. |

## ملاحظات

الإحداثيات الموجودة على حدود هذا [`Extent`](../) تُعتبر محتواة في هذا [`Extent`](../). لهذا السبب، تُعتبر الامتدادات المتساوية محتواة بعضها البعض.

### انظر أيضًا

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)

---

## Contains(IGeometry) {#contains_1}

يحدد ما إذا كان هذا الامتداد يحتوي على الوسيط.

```csharp
public bool Contains(IGeometry geometry)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| هندسة | IGeometry | هندسة لاختبار الاحتواء. |

### قيمة الإرجاع

قيمة تشير إلى ما إذا كان هذا الامتداد يحتوي على الوسيط.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا النطاق والوسيط كلاهما ليس `null` وليسا متساويين. |

## ملاحظات

الإحداثيات الموجودة على حدود هذا [`Extent`](../) تُعتبر محتواة في هذا [`Extent`](../).

### انظر أيضًا

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)


