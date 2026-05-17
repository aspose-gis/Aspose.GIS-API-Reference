---
title: "Класс FeatureAttribute"
type: docs
weight: 840
url: /ru/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Инициализирует новый экземпляр класса [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Инициализирует новый экземпляр класса [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | Возвращает значение, указывающее, может ли этот экземпляр быть null. |
| can_be_unset | bool | r/w | Получает или задает значение, указывающее, может ли значение этого атрибута быть опущено. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Получает тип данных атрибута. |
| default_value | object | r/w | Получает или задает значение для атрибута, указывающее на отсутствие данных. |
| has_custom_default_value | bool | r | Возвращает значение, указывающее, было ли предопределённое значение по умолчанию для этого атрибута переопределено пользовательским значением. |
| is_locked | bool | r | Возвращает значение, указывающее, заблокирован ли этот атрибут. |
| имя | string | r/w | Получает имя атрибута. |
| precision | Nullable<int> | r/w | Получает или задает максимальное количество десятичных знаков для хранения. |
| type_name | string | r/w | Имя типа атрибута. |
| width | Nullable<int> | r/w | Получает или задает максимальную допустимую ширину символьного представления атрибута. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| lock() | Блокирует этот атрибут. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Инициализирует новый экземпляр класса [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя атрибута. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Тип данных атрибута. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Инициализирует новый экземпляр класса [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя атрибута. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Тип данных атрибута. |
| can_be_null | bool | <see langword="true" /> если этот экземпляр может быть null; иначе <see langword="false" />. |

