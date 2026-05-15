---
title: "PrimeMeridian 类"
type: docs
weight: 140
url: /zh/python-net/aspose.gis.spatialreferencing/primemeridian/
---

**Summary:** PrimeMeridian represents a meridian at which longitude is defined to be 0.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.PrimeMeridian

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [PrimeMeridian(name, longitude, identifier)](#PrimeMeridian_name_longitude_identifier_1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| epsg_code | int | r | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| greenwich [static] | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | 格林威治子午线。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 此可识别对象的标识符。 |
| 经度 | double | r | 格林威治子午线到本初子午线的距离（以度为单位）。 |
| 名称 | string | r | 此对象的名称。 |


### Constructor: PrimeMeridian(name, longitude, identifier) {#PrimeMeridian_name_longitude_identifier_1}


```
 PrimeMeridian(name, longitude, identifier) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 本初子午线的名称。 |
| 经度 | double | 本初子午线相对于格林威治的经度（以度为单位）。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 本初子午线的标识符。 |

