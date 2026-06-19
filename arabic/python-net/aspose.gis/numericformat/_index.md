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
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | يقوم بتحويل ويحاول التأكد من أن القيمة الرقمية التي تم تحويلها إلى<br/>            سلسلة يتم تحليلها مرة أخرى إلى نفس القيمة الرقمية. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | يقوم بتحويل رقم إلى نص ثابت النقطة دون استخدام التدوين العلمي. |
| [general(precision)](#general_precision_2) | يقوم بتحويل رقم إلى الشكل الأكثر اختصارًا إما ثابت النقطة أو التدوين العلمي،<br/>            اعتمادًا على نوع الرقم وما إذا كان محدد الدقة موجودًا. يوصى باستخدامه. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

يقوم بتحويل رقم إلى نص ثابت النقطة دون استخدام التدوين العلمي.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| significant_digits | int | عدد الأرقام ذات الدقة. الحد الأقصى للدقة المتاحة هو "308" |

**Returns**

| نوع | وصف |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | محدد دقة التقريب. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

يقوم بتحويل رقم إلى الشكل الأكثر اختصارًا إما ثابت النقطة أو التدوين العلمي،<br/>            اعتمادًا على نوع الرقم وما إذا كان محدد الدقة موجودًا. يوصى باستخدامه.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| precision | int | تحدد الدقة الحد الأقصى لعدد الأرقام ذات الدقة التي يمكن أن تظهر في سلسلة النتيجة.<br/>            إذا كانت الدقة صفرًا، تُستخدم القيمة "15". الحد الأقصى للدقة المتاحة هو "17". |

**Returns**

| نوع | وصف |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | محدد الصيغة العامة. |


