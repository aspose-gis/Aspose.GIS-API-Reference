---
title: "FileGdbOptions.XYTolerance"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية FileGdbOptions. تحمل الالتقاط لمحوري X و Y"
type: docs
weight: 100
url: /ar/net/aspose.gis.formats.filegdb/filegdboptions/xytolerance/
---
## FileGdbOptions.XYTolerance property

تحمل الالتقاط للمحاور X و Y.

```csharp
public double? XYTolerance { get; set; }
```

## ملاحظات

هذا خيار إنشاء ولا يؤثر على القراءة والتحرير. يتحكم هذا المعامل في تحمل الالتقاط المستخدم لميزات ArcGIS المتقدمة. لا يؤثر على سلوك Aspose.GIS، لكنه يمكن أن يستخدمه ArcGIS. وحدة المعامل هي وحدة نظام الإسناد المكاني. إذا تم تعيينه إلى `null`، يتم استخدام القيمة الافتراضية. القيمة الافتراضية تعتمد على نظام الإسناد المكاني وتساوي 0.000000008983153 درجة للأنظمة الجغرافية أو 0.001 متر للأنظمة الإسقاطية (يتم تحويل القيم إلى وحدات نظام الإسناد المكاني). إذا كان نظام الإسناد المكاني غير معروف فإن القيمة الافتراضية هي 0.001.

### انظر أيضًا

* class [FileGdbOptions](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdboptions/)
* assembly [Aspose.GIS](../../../)


