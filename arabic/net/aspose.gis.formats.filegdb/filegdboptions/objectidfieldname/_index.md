---
title: "FileGdbOptions.ObjectIdFieldName"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية FileGdbOptions. اسم حقل معرف الكائن"
type: docs
weight: 90
url: /ar/net/aspose.gis.formats.filegdb/filegdboptions/objectidfieldname/
---
## FileGdbOptions.ObjectIdFieldName property

اسم حقل معرف الكائن.

```csharp
public string ObjectIdFieldName { get; set; }
```

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | القيمة ليست اسم حقل صالح. يجب أن يكون اسم الحقل الصالح: غير `null` وغير فارغ، يبدأ بحرف لاتيني أو شرطة سفلية، يحتوي فقط على أحرف لاتينية أو أرقام أو شرطات سفلية |

## ملاحظات

هذا خيار إنشاء ولا يؤثر على القراءة والتحرير. يحدد اسم حقل معرف الكائن (العمود). القيمة الافتراضية هي "OBJECTID". إذا كان أي سمة في [`Attributes`](../../../aspose.gis/vectorlayer/attributes/) لها اسم يساوي قيمة هذه الخاصية، فسيتم إعادة تسمية تلك السمة.

### انظر أيضًا

* class [FileGdbOptions](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdboptions/)
* assembly [Aspose.GIS](../../../)


