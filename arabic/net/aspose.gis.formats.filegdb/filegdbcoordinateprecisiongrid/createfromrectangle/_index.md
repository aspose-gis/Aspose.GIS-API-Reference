---
title: "FileGdbCoordinatePrecisionGrid.CreateFromRectangle"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FileGdbCoordinatePrecisionGrid. تنشئ FileGdbCoordinatePrecisionGrid جديد بحيث تكون جميع القيم داخل مستطيل قابلة للتمثيل."
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
| ArgumentException | *p1* و *p2* لا يشكلان مستطيلًا صالحًا غير فارغ: *p1* أو *p2* فارغ. علم 'HasZ' في *p1* لا يساوي علم 'HasZ' في *p2*، وعلم 'HasM' في *p1* لا يساوي علم 'HasM' في *p2*، وإحداثي 'X' في *p1* يساوي إحداثي 'X' في *p2*، وإحداثي 'Y' في *p1* يساوي إحداثي 'Y' في *p2*، وإحداثي 'Z' في *p1* يساوي إحداثي 'Z' في *p2*، وإحداثي 'M' في *p1* يساوي إحداثي 'M' في *p2*. أي إحداثي هو NaN أو لا نهائي. |

### انظر أيضًا

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [FileGdbCoordinatePrecisionGrid](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbcoordinateprecisiongrid/)
* assembly [Aspose.GIS](../../../)


