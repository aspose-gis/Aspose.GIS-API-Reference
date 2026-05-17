---
title: "BaseFeatureAttributeCollection Sınıfı"
type: docs
weight: 90
url: /tr/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Bir [Feature](/psd/python-net/aspose.gis/feature/) içindeki öznitelik sayısını alır. |
| is_locked | bool | r | Bu öznitelik koleksiyonunun kilitli olup olmadığını gösteren bir değer alır. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Koleksiyona bir öznitelik ekler. |
| [contains(name)](#contains_name_2) | Öznitelik koleksiyonunun belirtilen ada sahip bir öznitelik içerip içermediğini belirler. |
| [index_of(name)](#index_of_name_3) | Özniteliği arar ve sıfır tabanlı indeksini döndürür. |
| lock() | Bu öznitelik koleksiyonunu kilitleyerek daha fazla değişikliği önler. |
| [remove(index)](#remove_index_4) | Özniteliği koleksiyondan kaldırır. |
| [remove(name)](#remove_name_5) | Özniteliği koleksiyondan kaldırır. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Koleksiyona bir öznitelik ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | Eklenecek öznitelik. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Öznitelik koleksiyonunun belirtilen ada sahip bir öznitelik içerip içermediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Öznitelik adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword="true" /> eğer öznitelik koleksiyonu belirtilen ada sahip bir öznitelik içeriyorsa; aksi takdirde <see langword="false" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Özniteliği arar ve sıfır tabanlı indeksini döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Öznitelik adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Öznitelik koleksiyon içinde bulunduğunda, sıfır tabanlı indeks; aksi takdirde –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Özniteliği koleksiyondan kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | int | Öznitelik indeksi. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Özniteliği koleksiyondan kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Öznitelik adı. |

