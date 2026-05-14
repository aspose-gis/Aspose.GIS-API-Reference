---
title: "FileGdbOptions.GeometryFieldName"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية FileGdbOptions. اسم حقل الهندسة"
type: docs
weight: 50
url: /ar/net/aspose.gis.formats.filegdb/filegdboptions/geometryfieldname/
---
## FileGdbOptions.GeometryFieldName property

اسم حقل الهندسة.

```csharp
public string GeometryFieldName { get; set; }
```

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | القيمة ليست اسم حقل صالح. يجب أن يكون اسم الحقل الصالح: غير `null` وغير فارغ، يبدأ بحرف لاتيني أو شرطة سفلية، يحتوي فقط على أحرف لاتينية أو أرقام أو شرطات سفلية |

## ملاحظات

هذا خيار إنشاء ولا يؤثر على القراءة والتحرير. يحدد اسم حقل الهندسة (العمود). القيمة الافتراضية هي "SHAPE". إذا كان أي سمة في [`Attributes`](../../../aspose.gis/vectorlayer/attributes/) لها اسم يساوي قيمة هذه الخاصية، فسيتم إعادة تسمية تلك السمة.

### انظر أيضًا

* class [FileGdbOptions](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdboptions/)
* assembly [Aspose.GIS](../../../)


