---
title: "FileGdbOptions.EnsureValidCoordinatesRange"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية FileGdbOptions. ما إذا كان يجب أن تكون الإحداثيات ضمن النطاق الصالح"
type: docs
weight: 30
url: /ar/net/aspose.gis.formats.filegdb/filegdboptions/ensurevalidcoordinatesrange/
---
## FileGdbOptions.EnsureValidCoordinatesRange property

ما إذا كان يجب أن تكون الإحداثيات ضمن النطاق الصالح.

```csharp
public bool EnsureValidCoordinatesRange { get; set; }
```

## ملاحظات

هذا خيار إنشاء ولا يؤثر على القراءة والتحرير. إذا تم تعيينه إلى `true` سيتم رمي استثناء عند محاولة كتابة إحداثية بقيم خارج النطاق الصالح. إذا تم تعيينه إلى `false` سيتم كتابة تلك الإحداثية بصمت. يتم تعريف النطاق الصالح بواسطة [`CoordinatePrecisionGrid`](../coordinateprecisiongrid/). ارجع إلى وثائق [`CoordinatePrecisionGrid`](../coordinateprecisiongrid/) لقراءة كيفية تحديد النطاق الصالح من شبكة دقة الإحداثيات. القيمة الافتراضية هي `false`.

### انظر أيضًا

* class [FileGdbOptions](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdboptions/)
* assembly [Aspose.GIS](../../../)


