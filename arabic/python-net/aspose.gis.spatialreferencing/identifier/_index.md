---
title: "فئة Identifier"
type: docs
weight: 110
url: /ar/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | إنشاء مثال جديد. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| authority_name | string | r | اسم السلطة التي أعطت [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | r | طريقة فريدة لتمثيل كائن داخل [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | ينشئ معرفًا جديدًا يمثل معرف EPSG بالرمز <paramref name="epsgCode" />. |
| [get_epsg_code()](#get_epsg_code__2) | إذا كان هذا الكائن يمثل معرف EPSG صالح (مثال: - اسم السلطة هو "EPSG" ومعرف السلطة الفريد هو عدد صحيح) -<br/>            إرجاعه. وإلا - إرجاع -1. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

إنشاء مثال جديد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

ينشئ معرفًا جديدًا يمثل معرف EPSG بالرمز <paramref name="epsgCode" />.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| epsg_code | int | رمز EPSG. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | معرف جديد مع [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" و [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name="epsgCode" />.<br/> إذا كان <paramref name="epsgCode" /> أقل من 0 - إرجاع <see langword="null" />; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

إذا كان هذا الكائن يمثل معرف EPSG صالح (مثال: - اسم السلطة هو "EPSG" ومعرف السلطة الفريد هو عدد صحيح) -<br/>            إرجاعه. وإلا - إرجاع -1.

**Returns**

| نوع | وصف |
| :- | :- |
| int | معرف EPSG الممثل بهذا الكائن. إذا لم يمثل هذا الكائن معرف EPSG - إرجاع -1. |


