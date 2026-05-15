---
title: "فئة NumericFormat"
type: docs
weight: 2870
url: /ar/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | يحوّل ويحاول التأكد من أن القيمة الرقمية التي تم تحويلها إلى<br/>            سلسلة نصية يتم تحليلها مرة أخرى إلى نفس القيمة الرقمية. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | يحوّل عددًا إلى نص بنقطة ثابتة دون استخدام التدوين العلمي. |
| [general(precision)](#general_precision_2) | يحوّل عددًا إلى الشكل الأكثر اختصارًا إما بنقطة ثابتة أو بالتدوين العلمي،<br/>            اعتمادًا على نوع العدد وما إذا كان محدد الدقة موجودًا. يُنصح باستخدامه. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

يحوّل عددًا إلى نص بنقطة ثابتة دون استخدام التدوين العلمي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| significant_digits | int | عدد الأرقام ذات الدلالة. الحد الأقصى للدقة المتاحة هو "308" |

**Returns**

| نوع | الوصف |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | محدد دقة التقريب. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

يحوّل عددًا إلى الشكل الأكثر اختصارًا إما بنقطة ثابتة أو بالتدوين العلمي،<br/>            اعتمادًا على نوع العدد وما إذا كان محدد الدقة موجودًا. يُنصح باستخدامه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| precision | int | تحدد الدقة الحد الأقصى لعدد الأرقام ذات الدلالة التي يمكن أن تظهر في سلسلة النتيجة.<br/>            إذا كانت الدقة صفرًا، يتم استخدام القيمة "15". الحد الأقصى للدقة المتاحة هو "17". |

**Returns**

| نوع | الوصف |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | محدد الصيغة العامة. |


