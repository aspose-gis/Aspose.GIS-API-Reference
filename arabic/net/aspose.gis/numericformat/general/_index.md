---
title: "NumericFormat.General"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة NumericFormat. تقوم بتحويل رقم إلى الشكل الأكثر اختصارًا إما بنقطة ثابتة أو بالصيغة العلمية اعتمادًا على نوع الرقم وما إذا كان محدد الدقة موجودًا. يوصى باستخدامها"
type: docs
weight: 30
url: /ar/net/aspose.gis/numericformat/general/
---
## NumericFormat.General method

يحول عددًا إلى الشكل الأكثر اختصارًا إما ثابت النقطة أو الصيغة العلمية، اعتمادًا على نوع العدد وما إذا كان محدد الدقة موجودًا. يُنصح باستخدامه.

```csharp
public static NumericFormat General(int precision = 0)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الدقة | Int32 | تحدد الدقة الحد الأقصى لعدد الأرقام المهمة التي يمكن أن تظهر في سلسلة النتيجة. إذا كانت الدقة صفرًا، يتم استخدام القيمة "15". الحد الأقصى المتاح للدقة هو "17". |

### قيمة الإرجاع

محدد الصيغة العامة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | عدد الأرقام المهمة أقل من 0 أو أكثر من 17. |

## ملاحظات

يقوم الكود داخليًا بإنشاء سلاسل أرقام لـ WKT عبر: coordinate.ToString("G", CultureInfo.InvariantCulture).

### انظر أيضًا

* class [NumericFormat](../)
* namespace [Aspose.Gis](../../numericformat/)
* assembly [Aspose.GIS](../../../)


