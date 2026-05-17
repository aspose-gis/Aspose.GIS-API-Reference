---
title: "FromDefinitionDataSourceBuilder Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Özellik özniteliği için bilgi içerecek alanın adını yapılandırır. |
| [build()](#build__2) | Yöntem, [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) uygulamasını alır. |
| [geometry_field(name)](#geometry_field_name_3) | Geometrinin çıkarılacağı alanın adını yapılandırır. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | Değişikliklerin izlenmesine izin veren zorunlu ayar. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Özellik özniteliği için bilgi içerecek alanın adını yapılandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Öznitelik için veritabanı alanının adı. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Veritabanından gelen verilerin dönüştürülmesi gereken veri tipi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

Yöntem, [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) uygulamasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | Uygulaması [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


```
 geometry_field(name) 
```

Geometrinin çıkarılacağı alanın adını yapılandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Geometri alanının adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

Değişikliklerin izlenmesine izin veren zorunlu ayar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Bir özelliğin benzersiz olarak tanımlanmasını sağlayacak bir öznitelik. |
| overwrite_same_key | bool | Bu bayrak true olarak ayarlanırsa, katmanda zaten bulunan aynı benzersiz tanımlayıcıya sahip yeni eklenen özellikler, <br/>            mevcut olanı üzerine yazılacak ve farklılıklar bulunursa veri güncellenmiş olarak okunacaktır.<br/>            Aksi takdirde bir istisna fırlatılacaktır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


