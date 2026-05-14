---
title: "Geometry.GetBuffer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحسب منطقة العازلة حول هذه الهندسة."
type: docs
weight: 210
url: /ar/net/aspose.gis.geometries/geometry/getbuffer/
---
## Geometry.GetBuffer method

يحسب منطقة عازلة حول هذه الهندسة.

```csharp
public IGeometry GetBuffer(double distance, int quadrantSegments = 30)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسافة | Double | عرض منطقة العازلة. |
| quadrantSegments | Int32 | عدد القطاعات المستخدمة لتقريب انحناء 90 درجة. كلما كان هذا العدد أكبر، كلما كان تقريب المنحنيات أفضل. القيمة الافتراضية هي 30. |

### قيمة الإرجاع

هندسة تمثل جميع النقاط التي تقع ضمن مسافة محددة من هذه الهندسة. نوع النتيجة يكون إما [`Null`](../null/)، أو [`IPolygon`](../../ipolygon/)، أو [`IMultiPolygon`](../../imultipolygon/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentOutOfRangeException | عدد قطاعات الربع أقل من أو يساوي 0. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


