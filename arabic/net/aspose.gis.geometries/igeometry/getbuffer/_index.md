---
title: "IGeometry.GetBuffer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "IGeometry طريقة. يحسب منطقة العازلة حول هذه الهندسة"
type: docs
weight: 200
url: /ar/net/aspose.gis.geometries/igeometry/getbuffer/
---
## IGeometry.GetBuffer method

يحسب منطقة عازلة حول هذه الهندسة.

```csharp
public IGeometry GetBuffer(double distance, int quadrantSegments = 30)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسافة | Double | عرض منطقة العازلة (بوحدات الإشارة المكانية). |
| quadrantSegments | Int32 | عدد القطاعات المستخدمة لتقريب انحناء 90 درجة. كلما كان هذا العدد أكبر، كلما كان تقريب المنحنيات أفضل. القيمة الافتراضية هي 30. |

### قيمة الإرجاع

هندسة تمثل جميع النقاط التي تقع ضمن مسافة محددة من هذه الهندسة. نوع النتيجة يكون إما [`Null`](../../geometry/null/)، [`IPolygon`](../../ipolygon/) أو [`IMultiPolygon`](../../imultipolygon/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | هذه الهندسة غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentOutOfRangeException | عدد قطاعات الربع أقل من أو يساوي 0. |

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


