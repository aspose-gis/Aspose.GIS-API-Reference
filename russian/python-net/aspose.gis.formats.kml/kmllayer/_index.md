---
title: "Класс KmlLayer"
type: docs
weight: 140
url: /ru/python-net/aspose.gis.formats.kml/kmllayer/
---

**Summary:** Represents a Kml layer with non-destructive behavior that supports read and writing of features and attributes at one time.<br/>            A Kml layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlLayer

**Inheritance:** VectorLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Получает коллекцию пользовательских атрибутов для объектов в этом [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| количество | int | r | Получает количество объектов в этом слое. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Получает [KmlLayer.driver](/psd/python-net/aspose.gis.formats.kml/kmllayer/), который создал этот слой. |
| features | [Feature[]](/psd/python-net/aspose.gis/feature) | r | Получает список объектов. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Получает тип геометрии для слоя. |
| ground_overlay_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlGroundOverlayInfo> | r | Список KmlGroundOverlayInfo из узлов GroundOverlay |
| network_link_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlNetworkLinkInfo> | r | Список KmlNetworkLinkInfo из узлов NetworkLink |
| region_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlRegionInfo> | r | Список KmlRegionInfo из узлов Region |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Получить систему пространственных координат этого слоя. Для KML она всегда WGS84. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add(feature)](#add_feature_1) | Добавляет новый объект в слой, если это поддерживается [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [add(feature, style)](#add_feature_style_2) | Добавляет новый объект с указанным стилем в слой, если это поддерживается [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [as_in_memory()](#as_in_memory__3) | Создаёт слой‑клон в формате InMemory. |
| [construct_feature()](#construct_feature__4) | Создаёт (но не добавляет в слой) новый объект с атрибутами, соответствующими набору атрибутов этого слоя.<br/>            После завершения задания данных для объекта используйте [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) для добавления объекта в слой. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Преобразует слой в другой формат. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Преобразует слой в другой формат. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Преобразует слой в другой формат. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Преобразует слой в другой формат. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Копирует атрибуты другого [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) в текущий. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Копирует атрибуты другого [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) в текущий. |
| [create(path, driver)](#create_path_driver_11) | Создаёт слой и открывает его для добавления новых объектов. |
| [create(path, driver)](#create_path_driver_12) | Создаёт слой и открывает его для добавления новых объектов. |
| [create(path, driver, options)](#create_path_driver_options_13) | Создаёт слой и открывает его для добавления новых объектов. |
| [create(path, driver, options)](#create_path_driver_options_14) | Создаёт слой и открывает его для добавления новых объектов. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Создаёт слой и открывает его для добавления. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Создаёт слой и открывает его для добавления. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Создаёт слой и открывает его для добавления. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Создаёт слой и открывает его для добавления. |
| [get_extent()](#get_extent__19) | Получает пространственное ограничение этого слоя. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Пересекает слой с текущим слоем по геометрии. |
| [join(layer, options)](#join_layer_options_21) | Объединяет слой с текущим слоем. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Объединяет слой с текущим слоем по геометрии. |
| [nearest_to(point)](#nearest_to_point_23) | Получает ближайший объект к указанной точке. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Получает ближайший объект к указанной координате. |
| [open(path, driver)](#open_path_driver_25) | Открывает слой для чтения. |
| [open(path, driver)](#open_path_driver_26) | Открывает слой для чтения. |
| [open(path, driver, options)](#open_path_driver_options_27) | Открывает слой для чтения. |
| [open(path, driver, options)](#open_path_driver_options_28) | Открывает слой для чтения. |
| [remove_at(index)](#remove_at_index_29) | Удаляет [Feature](/psd/python-net/aspose.gis/feature/) по указанному индексу. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Заменяет [Feature](/psd/python-net/aspose.gis/feature/) по указанному индексу. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Сохраняет последовательность объектов в слой. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Сохраняет последовательность объектов в слой. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Сохраняет последовательность объектов в слой. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Сохраняет последовательность объектов в слой. |
| [split_to()](#split_to__35) | Разделяет объекты по типу геометрии. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Загружает индекс атрибутов для ускорения фильтрации по значению атрибутов в методах фильтрации, таких как Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Если индекс не существует, сначала создаёт его. Используйте <paramref name="forceRebuild" /> для принудительного воссоздания индекса. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Загружает индекс атрибутов для ускорения фильтрации по значению атрибутов в методах фильтрации, таких как Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Если индекс не существует, сначала создаёт его. Используйте <paramref name="forceRebuild" /> для принудительного воссоздания индекса. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Загружает пространственный индекс для ускорения фильтрации по значению атрибутов в методах фильтрации, таких как Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            и Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Если индекс не существует, сначала создаёт его. Используйте <paramref name="forceRebuild" /> для принудительного воссоздания индекса. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Загружает пространственный индекс для ускорения фильтрации по значению атрибутов в методах фильтрации, таких как Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            и Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Если индекс не существует, сначала создаёт его. Используйте <paramref name="forceRebuild" /> для принудительного воссоздания индекса. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Выбирает объекты, у которых значение атрибута равно указанному значению. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Выбирает объекты, у которых значение атрибута больше указанного значения. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Выбирает объекты, у которых значение атрибута больше или равно указанному значению. |
| [where_intersects(extent)](#where_intersects_extent_43) | Фильтрует объекты на основе экстента. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Фильтрует объекты на основе предоставленной геометрии. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Фильтрует объекты на основе объединения всех геометрий в последовательности других объектов. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Выбирает объекты, у которых значение атрибута не равно предоставленному значению. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Выбирает объекты, у которых атрибут не равен null. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Выбирает объекты, у которых атрибут равен null. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Выбирает объекты, у которых атрибут установлен. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Выбирает объекты, у которых значение атрибута меньше предоставленного значения. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Выбирает объекты, у которых значение атрибута меньше или равно предоставленному значению. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Выбирает объекты, у которых указанный атрибут не установлен. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Добавляет новый объект в слой, если это поддерживается [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Объект для добавления. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Добавляет новый объект с указанным стилем в слой, если это поддерживается [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Объект для добавления. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | Стиль объекта. Используйте <see langword="null" /> для указания отсутствующего стиля. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Создаёт слой‑клон в формате InMemory.

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой InMemory. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Создаёт (но не добавляет в слой) новый объект с атрибутами, соответствующими набору атрибутов этого слоя.<br/>            После завершения задания данных для объекта используйте [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) для добавления объекта в слой.

**Returns**

| Тип | Описание |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Новый объект. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Преобразует слой в другой формат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_path | string | Путь к слою, который будет конвертирован. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для исходного слоя. |
| destination_path | string | Путь к слою, который будет создан в результате конвертации. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для целевого слоя. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Преобразует слой в другой формат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к слою, который будет конвертирован. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для исходного слоя. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к слою, который будет создан в результате конвертации. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для целевого слоя. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Преобразует слой в другой формат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_path | string | Путь к слою, который будет конвертирован. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для исходного слоя. |
| destination_path | string | Путь к слою, который будет создан в результате конвертации. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для целевого слоя. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Параметры процедуры конвертации. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Преобразует слой в другой формат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к слою, который будет конвертирован. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для исходного слоя. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к слою, который будет создан в результате конвертации. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для целевого слоя. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Параметры процедуры конвертации. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Копирует атрибуты другого [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) в текущий.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Последовательность объектов, из которой копировать атрибуты. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Копирует атрибуты другого [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) в текущий.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Последовательность объектов, из которой копировать атрибуты. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | Экземпляр пользовательского [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/), который будет обрабатывать атрибуты по одному. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой только для записи. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой только для записи. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой только для записи. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой только для записи. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Создаёт слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Создаёт слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Создаёт слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Создаёт слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Получает пространственное ограничение этого слоя.

**Returns**

| Тип | Описание |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Пространственный экстент этого слоя. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Пересекает слой с текущим слоем по геометрии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой для пересечения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Новый слой в результате пересечения двух слоёв. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Объединяет слой с текущим слоем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой для объединения. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Параметры объединения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Новый слой в результате объединения двух слоёв. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Объединяет слой с текущим слоем по геометрии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой для объединения. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Параметры объединения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Новый слой в результате объединения двух слоёв. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Получает ближайший объект к указанной точке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Точка. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Ближайший объект к указанной точке. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Получает ближайший объект к указанной координате.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double | X координаты. |
| y | double | Y координаты. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Ближайший объект к указанной координате. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой только для чтения. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой только для чтения. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой только для чтения. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой только для чтения. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Удаляет [Feature](/psd/python-net/aspose.gis/feature/) по указанному индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс объекта. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Заменяет [Feature](/psd/python-net/aspose.gis/feature/) по указанному индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс объекта. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Объект для установки. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Сохраняет последовательность объектов в слой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_path | string | Путь к выходному слою. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для выходного слоя. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Сохраняет последовательность объектов в слой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к выходному слою. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер формата для выходного слоя. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


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

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


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

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Разделяет объекты по типу геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Слои с одинаковым типом геометрии. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Загружает индекс атрибутов для ускорения фильтрации по значению атрибутов в методах фильтрации, таких как Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Если индекс не существует, сначала создаёт его. Используйте <paramref name="forceRebuild" /> для принудительного воссоздания индекса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index_path | string | Путь к файлу индекса. |
| attribute_name | string | Имя атрибута, по которому строится индекс. |
| force_rebuild | bool | Нужно ли пересоздавать индекс, даже если он уже существует. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Загружает индекс атрибутов для ускорения фильтрации по значению атрибутов в методах фильтрации, таких как Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Если индекс не существует, сначала создаёт его. Используйте <paramref name="forceRebuild" /> для принудительного воссоздания индекса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу индекса. |
| attribute_name | string | Имя атрибута, по которому строится индекс. |
| force_rebuild | bool | Нужно ли пересоздавать индекс, даже если он уже существует. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Загружает пространственный индекс для ускорения фильтрации по значению атрибутов в методах фильтрации, таких как Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            и Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Если индекс не существует, сначала создаёт его. Используйте <paramref name="forceRebuild" /> для принудительного воссоздания индекса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index_path | string | Путь к файлу индекса. |
| force_rebuild | bool | Нужно ли пересоздавать индекс, даже если он уже существует. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Загружает пространственный индекс для ускорения фильтрации по значению атрибутов в методах фильтрации, таких как Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            и Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Если индекс не существует, сначала создаёт его. Используйте <paramref name="forceRebuild" /> для принудительного воссоздания индекса.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу индекса. |
| force_rebuild | bool | Нужно ли пересоздавать индекс, даже если он уже существует. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


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


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


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


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


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


### Method: where_intersects(extent) {#where_intersects_extent_43}


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


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


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


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


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


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


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


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


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


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


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


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


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


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


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


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


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


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


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


