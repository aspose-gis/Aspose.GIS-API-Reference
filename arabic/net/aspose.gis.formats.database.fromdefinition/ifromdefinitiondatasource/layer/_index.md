---
title: "IFromDefinitionDataSource.Layer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية IFromDefinitionDataSource. الخاصية التي تُعيد كائنًا يُنفّذ واجهة IQueryable التي تسمح بإجراء استعلامات LINQ ضد قاعدة بيانات"
type: docs
weight: 10
url: /ar/net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/layer/
---
## IFromDefinitionDataSource.Layer property

خاصية تُعيد كائنًا ينفّذ IQueryable يسمح بإجراء استعلامات LINQ ضد قاعدة البيانات.

```csharp
public IQueryable<Feature> Layer { get; }
```

### قيمة الإرجاع

IQueryable

## ملاحظات

علاوة على ذلك، يمكن تنفيذ الاستعلام بالطريقة القياسية عبر ToArray() أو ToList() بشكل متزامن، أو بطريقة غير متزامنة باستخدام استخراج الطبقة كاملةً عبر [`ToVectorLayerAsync`](../../queryablelayerextension/tovectorlayerasync/).

### انظر أيضًا

* class [Feature](../../../aspose.gis/feature/)
* interface [IFromDefinitionDataSource](../)
* namespace [Aspose.Gis.Formats.Database.FromDefinition](../../ifromdefinitiondatasource/)
* assembly [Aspose.GIS](../../../)


