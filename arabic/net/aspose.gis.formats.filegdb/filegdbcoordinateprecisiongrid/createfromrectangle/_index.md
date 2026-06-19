---
title: "FileGdbCoordinatePrecisionGrid.CreateFromRectangle"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FileGdbCoordinatePrecisionGrid. تنشئ FileGdbCoordinatePrecisionGrid جديد بحيث تكون جميع القيم داخل المستطيل قابلة للتمثيل."
type: docs
weight: 20
url: /ar/net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/createfromrectangle/
---
## FileGdbCoordinatePrecisionGrid.CreateFromRectangle method

ينشئ `FileGdbCoordinatePrecisionGrid` جديد بحيث تكون جميع القيم داخل مستطيل قابلة للتمثيل.

```csharp
public static FileGdbCoordinatePrecisionGrid CreateFromRectangle(IPoint p1, IPoint p2)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| p1 | IPoint | إحدى زوايا المستطيل. |
| p2 | IPoint | الزاوية المقابلة للمستطيل. يجب أن تكون ذات أبعاد مماثلة لـ *p1*. |

### قيمة الإرجاع

الـ `FileGdbCoordinatePrecisionGrid` بحيث تكون جميع القيم داخل المستطيل قابلة للتمثيل. القيم خارج المستطيل غير قابلة للتمثيل، لذا يجب أن تكون جميع الإحداثيات التي ستُكتب إلى طبقة FileGDB داخل المستطيل.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | *p1* و *p2* لا يشكلان مستطيلًا صالحًا غير فارغ: *p1* أو *p2* فارغ. علم 'HasZ' لـ *p1* لا يساوي علم 'HasZ' لـ *p2*، علم 'HasM' لـ *p1* لا يساوي علم 'HasM' لـ *p2*، إحداثي 'X' لـ *p1* يساوي إحداثي 'X' لـ *p2*، إحداثي 'Y' لـ *p1* يساوي إحداثي 'Y' لـ *p2*، إحداثي 'Z' لـ *p1* يساوي إحداثي 'Z' لـ *p2*، إحداثي 'M' لـ *p1* يساوي إحداثي 'M' لـ *p2*. أي إحداثي هو NaN أو لا نهائي. |

### انظر أيضًا

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [FileGdbCoordinatePrecisionGrid](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbcoordinateprecisiongrid/)
* assembly [Aspose.GIS](../../../)


