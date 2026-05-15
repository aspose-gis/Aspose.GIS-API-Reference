---
title: "椭球体类"
type: docs
weight: 40
url: /zh/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | 创建新的椭球体。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Airy 椭球体。 |
| epsg_code | int | r | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | GRS 1980 椭球体。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 此可识别对象的标识符。 |
| inverse_flattening | double | r | 椭球体的倒数展平率。如果这是球体，则为 0。 |
| is_sphere | bool | r | 检测此椭球体是否为球体。 |
| is_valid | bool | r | 检测椭球体是否有效：其半长轴大于 0，且倒数展平率为正或等于 0。 |
| 名称 | string | r | 此对象的名称。 |
| semi_major_axis | double | r | 椭球体的半长轴。 |
| semi_minor_axis | double | r | 椭球体的半短轴。如果这是球体，则等于半长轴。 |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 72 椭球体。 |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 84 椭球体。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | 确定两个椭球体是否等价。<br/>            如果椭球体 A 等价于椭球体 B，则它们具有相同的半长轴和倒数展平率。 |
| [is_equivalent(other)](#is_equivalent_other_2) | 确定两个椭球体是否等价。<br/>            如果椭球体 A 等价于椭球体 B，则它们具有相同的半长轴和倒数展平率。 |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

创建新的椭球体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 椭球体的名称。 |
| semi_major_axis | double | 椭球体的半长轴。 |
| inverse_flattening | double | 椭球体的倒数展平率。应为 0 以创建球体。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 椭球体的标识符。 |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

确定两个椭球体是否等价。<br/>            如果椭球体 A 等价于椭球体 B，则它们具有相同的半长轴和倒数展平率。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 第一个椭球体。 |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 第二个椭球体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 布尔值，指示两个椭球体是否等价。 |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

确定两个椭球体是否等价。<br/>            如果椭球体 A 等价于椭球体 B，则它们具有相同的半长轴和倒数展平率。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 其他椭球体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 布尔值，指示两个椭球体是否等价。 |


