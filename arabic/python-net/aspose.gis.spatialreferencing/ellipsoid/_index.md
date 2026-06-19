---
title: "فئة القطع الناقص"
type: docs
weight: 40
url: /ar/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | ينشئ قطعًا ناقصًا جديدًا. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | البيضاوي Airy. |
| epsg_code | int | r | إذا كان معرف هذا الكائن هو معرف EPSG - يتم إرجاع رمزه. وإلا - يتم إرجاع -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | البيضاوي GRS 1980. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | معرف هذا الكائن القابل للتعريف. |
| inverse_flattening | double | r | معكوس الانسداد للبيضاوي. 0 إذا كان هذا كرة. |
| is_sphere | bool | r | يكشف ما إذا كان هذا البيضاوي كرة. |
| is_valid | bool | r | يكشف ما إذا كان البيضاوي صالحًا: نصف المحور الرئيسي أكبر من 0 ومعكوس الانسداد إيجابي أو يساوي 0. |
| الاسم | string | r | اسم هذا الكائن. |
| semi_major_axis | double | r | نصف المحور الرئيسي للبيضاوي. |
| semi_minor_axis | double | r | نصف المحور الثانوي للبيضاوي. يساوي نصف المحور الرئيسي إذا كان هذا كرة. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | البيضاوي WGS 72. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | البيضاوي WGS 84. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | يحدد ما إذا كان بيضاويان متكافئان.<br/>            إذا كان البيضاوي A متكافئًا مع البيضاوي B، فإنهما يمتلكان نفس نصف المحور الرئيسي ومعكوس الانسداد. |
| [is_equivalent(other)](#is_equivalent_other_2) | يحدد ما إذا كان بيضاويان متكافئان.<br/>            إذا كان البيضاوي A متكافئًا مع البيضاوي B، فإنهما يمتلكان نفس نصف المحور الرئيسي ومعكوس الانسداد. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

ينشئ قطعًا ناقصًا جديدًا.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم البيضاوي. |
| semi_major_axis | double | نصف المحور الرئيسي للبيضاوي. |
| inverse_flattening | double | معكوس الانسداد للبيضاوي. يجب أن يكون 0 لإنشاء شبه كروي. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | معرف البيضاوي. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

يحدد ما إذا كان بيضاويان متكافئان.<br/>            إذا كان البيضاوي A متكافئًا مع البيضاوي B، فإنهما يمتلكان نفس نصف المحور الرئيسي ومعكوس الانسداد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | البيضاوي الأول. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | البيضاوي الثاني. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | قيمة منطقية، تشير إلى ما إذا كان بيضاويان متكافئان. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

يحدد ما إذا كان بيضاويان متكافئان.<br/>            إذا كان البيضاوي A متكافئًا مع البيضاوي B، فإنهما يمتلكان نفس نصف المحور الرئيسي ومعكوس الانسداد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | البيضاوي الآخر. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | قيمة منطقية، تشير إلى ما إذا كان بيضاويان متكافئان. |


