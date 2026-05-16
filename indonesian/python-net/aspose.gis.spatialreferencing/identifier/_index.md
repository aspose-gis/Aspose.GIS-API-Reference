---
title: "Kelas Identifier"
type: docs
weight: 110
url: /id/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Buat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| authority_name | string | r | Nama otoritas, yang memberikan sebuah [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | r | Cara unik untuk merepresentasikan sebuah objek dalam sebuah [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Membuat Identifier baru yang merepresentasikan identifier EPSG dengan kode <paramref name="epsgCode" />. |
| [get_epsg_code()](#get_epsg_code__2) | Jika objek ini merepresentasikan identifier EPSG yang valid (misalnya - nama otoritas adalah "EPSG" dan identifier unik otoritas adalah integer) -<br/>            kembalikan nilai tersebut. Jika tidak - kembalikan -1. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Buat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Membuat Identifier baru yang merepresentasikan identifier EPSG dengan kode <paramref name="epsgCode" />.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| epsg_code | int | Kode EPSG. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identifier baru dengan [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) \"EPSG\" dan [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name=\"epsgCode\" />.<br/> Jika <paramref name=\"epsgCode\" /> kurang dari 0 - kembalikan <see langword=\"null\" />; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Jika objek ini merepresentasikan identifier EPSG yang valid (misalnya - nama otoritas adalah "EPSG" dan identifier unik otoritas adalah integer) -<br/>            kembalikan nilai tersebut. Jika tidak - kembalikan -1.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Identifier EPSG yang direpresentasikan oleh objek ini. Jika objek ini tidak merepresentasikan identifier EPSG - kembalikan -1. |


