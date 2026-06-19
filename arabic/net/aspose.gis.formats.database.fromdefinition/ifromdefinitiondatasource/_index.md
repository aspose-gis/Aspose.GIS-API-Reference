---
title: "واجهة IFromDefinitionDataSource"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "واجهة Aspose.Gis.Formats.Database.FromDefinition.IFromDefinitionDataSource. توفر القدرة على قراءة البيانات الجغرافية المكانية من قاعدة البيانات عبر LINQ وتحديثها"
type: docs
weight: 1770
url: /ar/net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/
---
## IFromDefinitionDataSource interface

توفر القدرة على قراءة البيانات الجغرافية المكانية من قاعدة البيانات عبر LINQ وتحديثها.

```csharp
public interface IFromDefinitionDataSource
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Layer](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/layer/) { get; } | خاصية تُعيد كائنًا ينفّذ IQueryable يسمح بإجراء استعلامات LINQ ضد قاعدة البيانات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetEmptyLayer](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/getemptylayer/)() | يسمح بإنشاء طبقة فارغة. يمكن أن يكون ذلك مفيدًا عند إضافة سجل جديد إلى قاعدة البيانات فقط. لكن لاحقًا يمكن استخدام الطبقة لتعديل السجلات التي أضيفت حديثًا. |
| [SubmitChangesAsync](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/submitchangesasync/)() | يسمح بحفظ التغييرات المتراكمة في الطبقة المستخرجة الأخيرة. |
| [UseConnection](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/useconnection/)(DbConnection) | إعداد إلزامي، الاتصال الحالي. |
| [UseTransaction](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/usetransaction/)(DbTransaction) | ليس إعدادًا إلزاميًا، في حال كان من الضروري تنفيذ مجموعة من العمليات داخل معاملة. |

### انظر أيضًا

* namespace [Aspose.Gis.Formats.Database.FromDefinition](../../aspose.gis.formats.database.fromdefinition/)
* assembly [Aspose.GIS](../../)


