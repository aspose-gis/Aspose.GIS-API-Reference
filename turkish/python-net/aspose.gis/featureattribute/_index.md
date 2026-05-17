---
title: "FeatureAttribute Sınıfı"
type: docs
weight: 840
url: /tr/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Yeni bir [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) sınıf örneği başlatır. |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Yeni bir [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) sınıf örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | Bu örneğin null olabileceğini belirten bir değeri alır. |
| can_be_unset | bool | r/w | Bu öznitelik için değerin atlanıp atlanamayacağını gösteren bir değeri alır veya ayarlar. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Özniteliğin veri tipini alır. |
| default_value | object | r/w | Öznitelik için eksik veriyi gösteren bir değeri alır veya ayarlar. |
| has_custom_default_value | bool | r | Bu öznitelik için önceden tanımlı varsayılan değerin özel bir değerle geçersiz kılınıp kılınmadığını gösteren bir değeri alır. |
| is_locked | bool | r | Bu öznitelğin kilitli olup olmadığını gösteren bir değeri alır. |
| ad | string | r/w | Özniteliğin adını alır. |
| precision | Nullable<int> | r/w | Depolanacak azami ondalık basamak sayısını alır veya ayarlar. |
| type_name | string | r/w | Özniteliğin tip adı. |
| genişlik | Nullable<int> | r/w | Özniteliğin karakter temsili için izin verilen azami genişliği alır veya ayarlar. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| lock() | Bu özniteliği kilitler. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Yeni bir [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) sınıf örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Özniteliğin adı. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Özniteliğin veri tipi. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Yeni bir [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) sınıf örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Özniteliğin adı. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Özniteliğin veri tipi. |
| can_be_null | bool | <see langword=\"true\" /> bu örnek null olabiliyorsa; aksi takdirde, <see langword=\"false\" />. |

