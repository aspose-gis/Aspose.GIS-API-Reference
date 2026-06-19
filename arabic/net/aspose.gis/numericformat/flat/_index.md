---
title: "NumericFormat.Flat"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة NumericFormat. يحول عددًا إلى نص ثابت النقطة دون تدوين علمي"
type: docs
weight: 20
url: /ar/net/aspose.gis/numericformat/flat/
---
## NumericFormat.Flat method

يحول عددًا إلى نص ثابت النقطة دون استخدام الصيغة العلمية.

```csharp
public static NumericFormat Flat(int significantDigits)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| significantDigits | Int32 | عدد الأرقام ذات الدلالة. الحد الأقصى المتاح للدقة هو "308" |

### قيمة الإرجاع

محدد دقة التقريب.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | عدد الأرقام ذات الدلالة أقل من 0 أو أكثر من 308. |

## ملاحظات

يقوم الكود داخليًا بإنشاء سلاسل أرقام لـ WKT عبر: coordinate.ToString("0.##..", CultureInfo.InvariantCulture) decision.

### انظر أيضًا

* class [NumericFormat](../)
* namespace [Aspose.Gis](../../numericformat/)
* assembly [Aspose.GIS](../../../)


