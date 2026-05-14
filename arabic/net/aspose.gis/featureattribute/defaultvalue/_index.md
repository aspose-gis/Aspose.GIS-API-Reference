---
title: "FeatureAttribute.DefaultValue"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية FeatureAttribute. يحصل أو يضبط قيمة للخاصية التي تشير إلى البيانات المفقودة"
type: docs
weight: 50
url: /ar/net/aspose.gis/featureattribute/defaultvalue/
---
## FeatureAttribute.DefaultValue property

يحصل أو يضبط قيمة للسمة، تشير إلى بيانات مفقودة.

```csharp
public object DefaultValue { get; set; }
```

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الخاصية مقفلة. |
| InvalidOperationException | الخاصية لا تسمح بقيم `null`. |

## ملاحظات

هذه هي القيمة التي تمثل قطعة مفقودة من المعلومات، عندما لا تسمح الخاصية بقيمة `null`. بالنسبة للخصائص التي تسمح بقيم `null` ([`CanBeNull`](../canbenull/) == `true`)، تكون `DefaultValue` هي `null` ما لم يتم تغييرها صراحةً.

### انظر أيضًا

* class [FeatureAttribute](../)
* namespace [Aspose.Gis](../../featureattribute/)
* assembly [Aspose.GIS](../../../)


