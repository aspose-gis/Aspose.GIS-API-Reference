---
title: "Identifier 类"
type: docs
weight: 110
url: /zh/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| authority_name | string | r | 授予 [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) 的权威名称。 |
| authority_unique_identifier | string | r | 在 [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) 中表示对象的唯一方式。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | 创建一个新的 Identifier，表示代码为 <paramref name="epsgCode" /> 的 EPSG 标识符。 |
| [get_epsg_code()](#get_epsg_code__2) | 如果此对象表示有效的 EPSG 标识符（例如 - 权威名称为 "EPSG" 且权威唯一标识符为整数） -<br/>            返回它。否则返回 -1。 |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

创建一个新的 Identifier，表示代码为 <paramref name="epsgCode" /> 的 EPSG 标识符。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| epsg_code | 整数 | Epsg 代码。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 使用 [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) “EPSG” 和 [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name="epsgCode" /> 创建的新标识符。<br/>如果 <paramref name="epsgCode" /> 小于 0，则返回 <see langword="null" />； |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

如果此对象表示有效的 EPSG 标识符（例如 - 权威名称为 "EPSG" 且权威唯一标识符为整数） -<br/>            返回它。否则返回 -1。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 整数 | 此对象表示的 EPSG 标识符。如果此对象不表示 EPSG 标识符，则返回 -1。 |


