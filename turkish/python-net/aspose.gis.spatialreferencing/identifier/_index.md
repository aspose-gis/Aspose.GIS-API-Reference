---
title: "Identifier Sınıfı"
type: docs
weight: 110
url: /tr/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Yeni bir örnek oluştur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| authority_name | string | r | Bir yetkilinin adı, [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) sağlayan. |
| authority_unique_identifier | string | r | Bir nesneyi [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) içinde temsil etmenin benzersiz yolu. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Kod <paramref name=\"epsgCode\" /> ile EPSG tanımlayıcısını temsil eden yeni Identifier oluşturur. |
| [get_epsg_code()](#get_epsg_code__2) | Bu nesne geçerli bir EPSG tanımlayıcısını temsil ediyorsa (ör. - yetki adı \"EPSG\" ve yetki benzersiz tanımlayıcısı tamsayıdır) -<br/>            onu döndür. Aksi takdirde -1 döndür. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Yeni bir örnek oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Kod <paramref name=\"epsgCode\" /> ile EPSG tanımlayıcısını temsil eden yeni Identifier oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| epsg_code | int | Epsg kodu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Yeni tanımlayıcı, [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" ve [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name=\"epsgCode\" /> ile birlikte.<br/>            Eğer <paramref name=\"epsgCode\" /> 0'dan küçükse - <see langword=\"null\" /> döndürülür; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Bu nesne geçerli bir EPSG tanımlayıcısını temsil ediyorsa (ör. - yetki adı \"EPSG\" ve yetki benzersiz tanımlayıcısı tamsayıdır) -<br/>            onu döndür. Aksi takdirde -1 döndür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Bu nesne tarafından temsil edilen EPSG tanımlayıcısı. Bu nesne bir EPSG tanımlayıcısı temsil etmiyorsa - -1 döndürülür. |


