---
title: "LocalDatum 类"
type: docs
weight: 120
url: /zh/python-net/aspose.gis.spatialreferencing/localdatum/
---

**Summary:** Indicates method used for measurements in local spatial reference system.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.LocalDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [LocalDatum(name, datum_type, identifier)](#LocalDatum_name_datum_type_identifier_1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| datum_type | int | r | 整数，指示已使用的测量方法。 |
| epsg_code | int | r | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 此可识别对象的标识符。 |
| 名称 | string | r | 此对象的名称。 |


### Constructor: LocalDatum(name, datum_type, identifier) {#LocalDatum_name_datum_type_identifier_1}


```
 LocalDatum(name, datum_type, identifier) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 基准名称。 |
| datum_type | int | 整数，表示基准类型。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 基准的标识符。 |

