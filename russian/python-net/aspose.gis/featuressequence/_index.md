---
title: "Класс FeaturesSequence"
type: docs
weight: 870
url: /ru/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Получает коллекцию пользовательских атрибутов для объектов в этом [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Получает систему пространственной привязки этой последовательности объектов. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_extent()](#get_extent__1) | Получает пространственное ограничение этого слоя. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Сохраняет последовательность объектов в слой. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Сохраняет последовательность объектов в слой. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Сохраняет последовательность объектов в слой. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Сохраняет последовательность объектов в слой. |
| [split_to()](#split_to__6) | Разделяет объекты по типу геометрии. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Выбирает объекты, у которых значение атрибута равно указанному значению. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Выбирает объекты, у которых значение атрибута больше указанного значения. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Выбирает объекты, у которых значение атрибута больше или равно указанному значению. |
| [where_intersects(extent)](#where_intersects_extent_10) | Фильтрует объекты на основе экстента. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Фильтрует объекты на основе предоставленной геометрии. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Фильтрует объекты на основе объединения всех геометрий в последовательности других объектов. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Выбирает объекты, у которых значение атрибута не равно предоставленному значению. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Выбирает объекты, у которых атрибут не равен null. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Выбирает объекты, у которых атрибут равен null. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Выбирает объекты, у которых атрибут установлен. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Выбирает объекты, у которых значение атрибута меньше предоставленного значения. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Выбирает объекты, у которых значение атрибута меньше или равно предоставленному значению. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Выбирает объекты, у которых указанный атрибут не установлен. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Получает пространственное ограничение этого слоя.

**Returns**

| Тип | Описание |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Пространственный экстент этого слоя. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Сохраняет последовательность объектов в слой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_path | string | Путь к выходному слою. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для выходного слоя. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Сохраняет последовательность объектов в слой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к выходному слою. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для выходного слоя. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

Сохраняет последовательность объектов в слой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_path | string | Путь к выходному слою. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для выходного слоя. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Параметры процедуры сохранения. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

Сохраняет последовательность объектов в слой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к выходному слою. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для выходного слоя. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Параметры процедуры сохранения. |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Разделяет объекты по типу геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Слои с одинаковым типом геометрии. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

Выбирает объекты, у которых значение атрибута равно указанному значению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |
| value | object | Значение для сравнения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты, у которых значение атрибута равно указанному значению. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

Выбирает объекты, у которых значение атрибута больше указанного значения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |
| value | object | Значение для сравнения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты, у которых значение атрибута больше указанного значения. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

Выбирает объекты, у которых значение атрибута больше или равно указанному значению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |
| value | object | Значение для сравнения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты, у которых значение атрибута больше или равно указанному значению. |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

Фильтрует объекты на основе экстента.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Фильтровать охват. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты, пересекающие предоставленную геометрию. |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

Фильтрует объекты на основе предоставленной геометрии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Фильтровать геометрию. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты, пересекающие предоставленную геометрию. |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

Фильтрует объекты на основе объединения всех геометрий в последовательности других объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Последовательность других объектов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты, пересекающие объединение всех геометрий в последовательности других объектов. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

Выбирает объекты, у которых значение атрибута не равно предоставленному значению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |
| value | object | Значение для сравнения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты со значением атрибута, не равным предоставленному значению. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

Выбирает объекты, у которых атрибут не равен null.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты со значением атрибута, не равным null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

Выбирает объекты, у которых атрибут равен null.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты со значением атрибута, равным null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

Выбирает объекты, у которых атрибут установлен.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты с установленным значением атрибута. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

Выбирает объекты, у которых значение атрибута меньше предоставленного значения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |
| value | object | Значение для сравнения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты со значением атрибута, меньшим предоставленного значения. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

Выбирает объекты, у которых значение атрибута меньше или равно предоставленному значению.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |
| value | object | Значение для сравнения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты со значением атрибута, меньшим или равным предоставленному значению. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

Выбирает объекты, у которых указанный атрибут не установлен.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Атрибут для фильтрации. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Объекты с неустановленным значением атрибута. |


