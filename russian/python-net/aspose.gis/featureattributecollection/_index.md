---
title: "Класс FeatureAttributeCollection"
type: docs
weight: 850
url: /ru/python-net/aspose.gis/featureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttributeCollection

**Inheritance:** BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| count | int | r | Возвращает количество атрибутов в [Feature](/psd/python-net/aspose.gis/feature/). |
| is_locked | bool | r | Возвращает значение, указывающее, заблокирована ли эта коллекция атрибутов. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Добавляет атрибут в коллекцию. |
| [contains(name)](#contains_name_2) | Определяет, содержит ли коллекция атрибутов атрибут с указанным именем. |
| [index_of(name)](#index_of_name_3) | Ищет атрибут и возвращает его нулевой (начиная с нуля) индекс. |
| lock() | Блокирует эту коллекцию атрибутов, чтобы предотвратить дальнейшие изменения. |
| [remove(index)](#remove_index_4) | Удаляет атрибут из коллекции. |
| [remove(name)](#remove_name_5) | Удаляет атрибут из коллекции. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Добавляет атрибут в коллекцию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | Атрибут для добавления. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Определяет, содержит ли коллекция атрибутов атрибут с указанным именем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя атрибута. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword="true" /> если коллекция атрибутов содержит атрибут с указанным именем; иначе <see langword="false" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Ищет атрибут и возвращает его нулевой (начиная с нуля) индекс.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя атрибута. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Нулевой (начиная с нуля) индекс атрибута в коллекции, если найден; иначе –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Удаляет атрибут из коллекции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс атрибута. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Удаляет атрибут из коллекции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя атрибута. |

