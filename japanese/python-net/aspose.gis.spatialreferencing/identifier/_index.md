---
title: "Identifier クラス"
type: docs
weight: 110
url: /ja/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| authority_name | string | r | 権限の名前で、[Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) を付与したもの。 |
| authority_unique_identifier | string | r | オブジェクトを [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) 内で表すユニークな方法。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | コード <paramref name="epsgCode" /> を持つ EPSG 識別子を表す新しい Identifier を作成します。 |
| [get_epsg_code()](#get_epsg_code__2) | このオブジェクトが有効な EPSG 識別子を表す場合（例：権限名が "EPSG" で、権限固有識別子が整数の場合） -<br/>            それを返します。そうでない場合は -1 を返します。 |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

コード <paramref name="epsgCode" /> を持つ EPSG 識別子を表す新しい Identifier を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| epsg_code | int | Epsg コード。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 新しい識別子は、[Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" と [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name="epsgCode" /> を使用します。<br/>            <paramref name="epsgCode" /> が 0 未満の場合は <see langword="null" /> を返します; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

このオブジェクトが有効な EPSG 識別子を表す場合（例：権限名が "EPSG" で、権限固有識別子が整数の場合） -<br/>            それを返します。そうでない場合は -1 を返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| int | このオブジェクトが表す EPSG 識別子です。このオブジェクトが EPSG 識別子を表さない場合は -1 を返します。 |


