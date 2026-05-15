---
title: "فئة Projection"
type: docs
weight: 170
url: /ar/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | الوحدة المستخدمة للمعلمات الزاوية. |
| epsg_code | int | r | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | معرف هذا الكائن القابل للتعريف. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | الوحدة المستخدمة للمعلمات الخطية. |
| الاسم | string | r | اسم هذا الكائن. |
| parameters_names | System.Collections.Generic.IList<string> | r | يحصل على مجموعة قابلة للتعداد من أسماء المعلمات المعطاة لهذا الإسقاط |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | يحصل على المعلمة بالاسم المحدد لهذا الإسقاط. |
| [is_equivalent(other)](#is_equivalent_other_2) | يحدد ما إذا كان الإسقاطان متكافئان. الإسقاطات المتكافئة تقوم بتحويل (خط الطول، خط العرض) إلى (x, y) في<br/>            نفس الطريقة. |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | يحصل على المعلمة بالاسم المحدد لهذا الإسقاط. إذا لم توجد مثل هذه المعلمة - تُرجع <see langword="null" />. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

يحصل على المعلمة بالاسم المحدد لهذا الإسقاط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم المعامل. |
