---
title: "投影类"
type: docs
weight: 170
url: /zh/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 用于角度参数的单位。 |
| epsg_code | int | r | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 此可识别对象的标识符。 |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 用于线性参数的单位。 |
| 名称 | string | r | 此对象的名称。 |
| parameters_names | System.Collections.Generic.IList<string> | r | 获取提供给此投影的参数名称的可枚举集合 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | 获取此投影中具有指定名称的参数。 |
| [is_equivalent(other)](#is_equivalent_other_2) | 确定两个投影是否等价。等价投影以相同方式将（经度，纬度）映射到（x，y）<br/>            以相同的方式。 |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | 获取此投影中具有指定名称的参数。如果不存在此类参数 - 返回 <see langword="null" />。 |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

获取此投影中具有指定名称的参数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 参数的名称。 |
