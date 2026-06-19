---
title: "PrecisionModel Class"
type: docs
weight: 3200
url: /ar/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | يرجع نموذج دقة دقيق.<br/>            وفقًا لنموذج الدقة الدقيق جميع الأرقام في قيمة مزدوجة ذات أهمية. |
| is_exact | bool | r | يحصل على قيمة تشير إلى ما إذا كان نموذج الدقة هذا دقيقًا. |
| is_rounding | bool | r | يحصل على قيمة تشير إلى ما إذا كان نموذج الدقة هذا يقوم بالتقريب. |
| significant_digits | int | r | يحصل على عدد الأرقام ذات الأهمية في نموذج الدقة إذا كان يقوم بالتقريب. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | يرجع نموذج دقة تقريبي.<br/>            وفقًا لنموذج الدقة التقريبي عدد محدود فقط من الأرقام ذات الأهمية. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

يرجع نموذج دقة تقريبي.<br/>            وفقًا لنموذج الدقة التقريبي عدد محدود فقط من الأرقام ذات الأهمية.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| significant_digits | int | عدد الأرقام ذات الأهمية. |

**Returns**

| نوع | وصف |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | نموذج دقة تقريبي. |


