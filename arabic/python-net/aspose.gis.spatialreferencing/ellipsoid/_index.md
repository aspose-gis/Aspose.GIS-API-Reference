---
title: "فئة الإهليلج"
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
| **Name** | **الوصف** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | إنشاء Ellipsoid جديد. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | القطيع الهوائي Airy. |
| epsg_code | int | r | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | القطيع الهوائي GRS 1980. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | معرف هذا الكائن القابل للتعريف. |
| inverse_flattening | double | r | العكسية المسطحة للقطيع. 0 إذا كان هذا كرة. |
| is_sphere | bool | r | يكشف ما إذا كان هذا القطع الناقص كرة. |
| is_valid | bool | r | يكشف ما إذا كان القطع الناقص صالحًا: نصف المحور الرئيسي أكبر من 0 والعكسية المسطحة موجبة أو مساوية لـ 0. |
| الاسم | string | r | اسم هذا الكائن. |
| semi_major_axis | double | r | نصف المحور الرئيسي للقطيع. |
| semi_minor_axis | double | r | نصف المحور الثانوي للقطيع. يساوي نصف المحور الرئيسي إذا كان هذا كرة. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | القطيع الهوائي WGS 72. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | القطيع الهوائي WGS 84. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | يحدد ما إذا كان قطعتان ناقصتان متكافئتين.<br/>            إذا كان القطع الناقص A متكافئًا مع القطع الناقص B، فإنهما يمتلكان نفس نصف المحور الرئيسي والعكسية المسطحة. |
| [is_equivalent(other)](#is_equivalent_other_2) | يحدد ما إذا كان قطعتان ناقصتان متكافئتين.<br/>            إذا كان القطع الناقص A متكافئًا مع القطع الناقص B، فإنهما يمتلكان نفس نصف المحور الرئيسي والعكسية المسطحة. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

إنشاء Ellipsoid جديد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم القطع الناقص. |
| semi_major_axis | double | نصف المحور الرئيسي للقطيع. |
| inverse_flattening | double | العكسية المسطحة للقطيع. يجب أن تكون 0 لإنشاء كروية. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | معرف القطع الناقص. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

يحدد ما إذا كان قطعتان ناقصتان متكافئتين.<br/>            إذا كان القطع الناقص A متكافئًا مع القطع الناقص B، فإنهما يمتلكان نفس نصف المحور الرئيسي والعكسية المسطحة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | القطيع الأول. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | القطيع الثاني. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | قيمة منطقية، تشير إلى ما إذا كان قطعتان ناقصتان متكافئتين. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

يحدد ما إذا كان قطعتان ناقصتان متكافئتين.<br/>            إذا كان القطع الناقص A متكافئًا مع القطع الناقص B، فإنهما يمتلكان نفس نصف المحور الرئيسي والعكسية المسطحة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | القطيع الآخر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | قيمة منطقية، تشير إلى ما إذا كان قطعتان ناقصتان متكافئتين. |


