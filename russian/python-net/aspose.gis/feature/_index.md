---
title: "Feature Класс"
type: docs
weight: 830
url: /ru/python-net/aspose.gis/feature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Получает или задает геометрию объекта.<br/>            Не может быть <see langword="null" />, используйте [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) для указания отсутствующей геометрии. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Копирует значения атрибутов из другого объекта. |
| [get_value(attribute_name)](#get_value_attribute_name_2) | Получает значение атрибута. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_3) | Получает значение атрибута или [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/), если значение не установлено или <c>null</c>. |
| [get_values(values, default_value)](#get_values_values_default_value_4) | Возвращает значения всех атрибутов в массиве. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_5) | Возвращает значения всех атрибутов в массиве. |
| [get_values_dump(default_value)](#get_values_dump_default_value_6) | Возвращает значения всех атрибутов в массиве.<br/>            Рассмотрите возможность использования метода Aspose.Gis.Feature.GetValues(int,System.Object), чтобы избежать дополнительного выделения памяти. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_7) | Получает список значений. Необобщённый аналог List T GetValuesList |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_8) | Определяет, было ли указанное свойство явно установлено в значение <c>null</c>. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_9) | Проверяет, установлено ли значение свойства в этом объекте. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_10) | Устанавливает значение. Необобщённый аналог void SetValue (string attributeName, T value) |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_11) | Устанавливает значение свойства в <c>null</c>. |
| [set_values(values)](#set_values_values_12) | Устанавливает новые значения для всех свойств.<br/>            Также рассмотрите возможность использования метода [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) для упрощения установки значений одним вызовом. |
| [unset_value(attribute_name)](#unset_value_attribute_name_13) | Удаляет значение свойства из этого объекта. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Копирует значения атрибутов из другого объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | Объект, из которого копировать значения. |

### Method: get_value(attribute_name) {#get_value_attribute_name_2}


```
 get_value(attribute_name) 
```

Получает значение атрибута.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Имя атрибута. |

**Returns**

| Тип | Описание |
| :- | :- |
| object | Значение свойства. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_3}


```
 get_value_or_default(attribute_name, default_value) 
```

Получает значение атрибута или [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/), если значение не установлено или <c>null</c>.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Имя атрибута. |
| default_value | object | Значение, которое возвращается, если значение свойства отсутствует. Значение по умолчанию — <see langword="null" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| object | Значение свойства. |


### Method: get_values(values, default_value) {#get_values_values_default_value_4}


```
 get_values(values, default_value) 
```

Возвращает значения всех атрибутов в массиве.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| values | object |  |
| default_value | object | Значение, которое возвращается, если значение свойства отсутствует (не установлено). Значение по умолчанию — <see langword="null" />.<br/>            Рассмотрите возможность использования '.Value' для различения значений 'не установлено' и '<see langword="null" />' значений. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Количество скопированных свойств. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_5}


```
 get_values(values_count, default_value) 
```

Возвращает значения всех атрибутов в массиве.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| values_count | int | Количество значений. |
| default_value | object | Значение, которое возвращается, если значение свойства отсутствует (не установлено). Значение по умолчанию — <see langword="null" />.<br/>            Рассмотрите возможность использования '.Value' для различения значений 'не установлено' и '<see langword="null" />' значений. |

**Returns**

| Тип | Описание |
| :- | :- |
| object | Количество скопированных свойств. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_6}


```
 get_values_dump(default_value) 
```

Возвращает значения всех атрибутов в массиве.<br/>            Рассмотрите возможность использования метода Aspose.Gis.Feature.GetValues(int,System.Object), чтобы избежать дополнительного выделения памяти.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| default_value | object | Значение, которое возвращается, если значение свойства отсутствует (не установлено). Значение по умолчанию — <see langword="null" />.<br/>            Рассмотрите возможность использования '.Value' для различения значений 'не установлено' и '<see langword="null" />' значений. |

**Returns**

| Тип | Описание |
| :- | :- |
| object | Новый массив, в который копируются значения свойств. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_7}


```
 get_values_list(attribute_name, separator, count) 
```

Получает список значений. Необобщённый аналог List T GetValuesList

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Имя атрибута. |
| separator | string | Строка, используемая для разделения имени свойства и индексного значения последовательности. |
| количество | int | Количество возвращаемых значений (отсутствующие заполняются null). |

**Returns**

| Тип | Описание |
| :- | :- |
| object | Список значений свойств, имена которых различаются по индексному значению последовательности. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_8}


```
 is_value_null(attribute_name) 
```

Определяет, было ли указанное свойство явно установлено в значение <c>null</c>.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Имя атрибута. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword="true" /> если значение свойства равно <c>null</c>; иначе <see langword="false" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_9}


```
 is_value_set(attribute_name) 
```

Проверяет, установлено ли значение свойства в этом объекте.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Имя атрибута. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword="true" /> если значение указанного свойства установлено; иначе <see langword="false" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_10}


```
 set_value(attribute_name, value) 
```

Устанавливает значение. Необобщённый аналог void SetValue (string attributeName, T value)

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Имя атрибута. |
| value | object | Значение свойства. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_11}


```
 set_value_null(attribute_name) 
```

Устанавливает значение свойства в <c>null</c>.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Имя атрибута. |

### Method: set_values(values) {#set_values_values_12}


```
 set_values(values) 
```

Устанавливает новые значения для всех свойств.<br/>            Также рассмотрите возможность использования метода [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) для упрощения установки значений одним вызовом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| values | object | Массив новых значений. |

**Returns**

| Тип | Описание |
| :- | :- |
| int | Количество установленных значений атрибутов. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_13}


```
 unset_value(attribute_name) 
```

Удаляет значение свойства из этого объекта.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| attribute_name | string | Имя атрибута. |

