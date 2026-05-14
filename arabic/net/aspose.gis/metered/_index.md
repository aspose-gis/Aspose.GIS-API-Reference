---
title: "الفئة Metered"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Metered. توفر طرقاً لتعيين المفتاح المتعقب."
type: docs
weight: 3420
url: /ar/net/aspose.gis/metered/
---
## Metered class

يوفر طرقًا لتعيين المفتاح المقيس.

```csharp
public class Metered
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [GetConsumptionCredit](../../aspose.gis/metered/getconsumptioncredit/)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.gis/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |
| static [ResetMeteredKey](../../aspose.gis/metered/resetmeteredkey/)() | يزيل الترخيص الذي تم إعداده مسبقاً |
| static [SetMeteredKey](../../aspose.gis/metered/setmeteredkey/)(string, string) | يضبط المفتاح العام والخاص المتعقب |

## أمثلة

في هذا المثال، سيتم محاولة تعيين المفتاح العام والخاص المتعقب

```csharp
[C#]

Metered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Metered.SetMeteredKey("PublicKey", "PrivateKey")
```

ملف jar المكوّن:

```csharp
Metered.setMeteredKey("PublicKey", "PrivateKey");
```

### انظر أيضًا

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


