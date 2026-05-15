---
title: "الفئة PrecisionModel"
type: docs
weight: 3200
url: /ar/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | يعيد نموذج دقة دقيق.<br/>            وفقًا لنموذج الدقة الدقيق جميع الأرقام في قيمة مزدوجة تعتبر ذات أهمية. |
| is_exact | bool | r | يحصل على قيمة تشير إلى ما إذا كان نموذج الدقة هذا دقيقًا. |
| is_rounding | bool | r | يحصل على قيمة تشير إلى ما إذا كان نموذج الدقة هذا يستخدم التقريب. |
| significant_digits | int | r | يحصل على عدد الأرقام ذات الأهمية في نموذج الدقة إذا كان يستخدم التقريب. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | يعيد نموذج دقة تقريبي.<br/>            وفقًا لنموذج الدقة التقريبي يتم اعتبار عدد محدود فقط من الأرقام ذات أهمية. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

يعيد نموذج دقة تقريبي.<br/>            وفقًا لنموذج الدقة التقريبي يتم اعتبار عدد محدود فقط من الأرقام ذات أهمية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| significant_digits | int | عدد الأرقام ذات الأهمية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | نموذج دقة التقريب. |


