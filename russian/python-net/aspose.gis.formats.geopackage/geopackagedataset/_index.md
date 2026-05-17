---
title: "GeoPackageDataset Класс"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | Создаёт новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Возвращает значение, указывающее, может ли этот набор данных создавать векторные слои. |
| can_remove_layers | bool | r | Возвращает значение, указывающее, может ли этот набор данных удалять векторные слои. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Получает [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/), который создал этот набор данных. |
| layers_count | int | r | Возвращает количество слоёв в этом наборе данных. |
| tile_layers_count | int | r | Получает количество тайловых слоёв в этом наборе данных. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Создаёт набор данных. |
| [create(path, driver)](#create_path_driver_2) | Создаёт набор данных. |
| [create(path, driver, options)](#create_path_driver_options_3) | Создаёт набор данных. |
| [create(path, driver, options)](#create_path_driver_options_4) | Создаёт набор данных. |
| [create_layer()](#create_layer__5) | Создает новый векторный слой и открывает его для добавления. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Создает новый векторный слой с указанным именем и открывает его для добавления. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Создает новый векторный слой с указанным именем и открывает его для добавления. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Создает новый векторный слой и открывает его для добавления. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Создает новый векторный слой и открывает его для добавления. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Этот метод всё ещё находится в разработке. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Этот метод всё ещё находится в разработке. |
| [get_layer_name(index)](#get_layer_name_index_12) | Получает имя слоя по указанному индексу. |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | Получает имя тайлового слоя по указанному индексу. |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | Проверяет, имеет ли текущий набор данных слой с конкретным именем. |
| [open(path, driver)](#open_path_driver_15) | Открывает набор данных. |
| [open(path, driver)](#open_path_driver_16) | Открывает набор данных. |
| [open(path, driver, options)](#open_path_driver_options_17) | Открывает набор данных. |
| [open(path, driver, options)](#open_path_driver_options_18) | Открывает набор данных. |
| [open(path, options)](#open_path_options_19) | Фабричный метод для создания набора данных из файла gpkg. |
| [open_layer(name, options)](#open_layer_name_options_20) | Открывает слой с указанным именем для чтения. |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | Открывает слой по указанному индексу для чтения. |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | Открывает слой по указанному индексу для чтения. |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | Открывает тайловый слой с указанным именем для чтения. |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | Открывает тайловый слой по указанному индексу для чтения. |
| [remove_layer(name)](#remove_layer_name_25) | Удаляет векторный слой с указанным именем. |
| [remove_layer_at(index)](#remove_layer_at_index_26) | Удаляет векторный слой по указанному индексу. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | Переименовать слой в наборе данных |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Настройки, касающиеся особенностей чтения файла gpkg. |

### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Создаёт набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к набору данных. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Создаёт набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к набору данных. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Создаёт набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к набору данных. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Создаёт набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к набору данных. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Создает новый векторный слой и открывает его для добавления.

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Объект [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) открыт для записи. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Создает новый векторный слой с указанным именем и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя слоя. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Параметры открытия. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система пространственных координат нового слоя. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Объект [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) открыт для записи. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Создает новый векторный слой с указанным именем и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя слоя. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система пространственных координат нового слоя. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Объект [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) открыт для записи. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Создает новый векторный слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Параметры открытия. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система пространственных координат нового слоя. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Объект [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) открыт для записи. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Создает новый векторный слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система пространственных координат нового слоя. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Объект [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) открыт для записи. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Этот метод всё ещё находится в разработке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя слоя для редактирования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Параметры открытия. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система пространственных координат для новых геометрий. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Этот метод всё ещё находится в разработке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс слоя для редактирования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Параметры открытия. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система пространственных координат для новых геометрий. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Получает имя слоя по указанному индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс слоя. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Имя слоя. |


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

Получает имя тайлового слоя по указанному индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс слоя. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Имя слоя. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


```
 has_layer_with_name(name) 
```

Проверяет, имеет ли текущий набор данных слой с конкретным именем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя слоя |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" />, если набор данных имеет слой с этим именем; иначе, <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Открывает набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к набору данных. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_16}


```
 open(path, driver) 
```

Открывает набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к набору данных. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Открывает набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к набору данных. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


```
 open(path, driver, options) 
```

Открывает набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к набору данных. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Драйвер для использования. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

Фабричный метод для создания набора данных из файла gpkg.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Настройки, касающиеся особенностей чтения файла gpkg. |

**Returns**

| Тип | Описание |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


```
 open_layer(name, options) 
```

Открывает слой с указанным именем для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя слоя для открытия. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Параметры открытия. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой, открытый для чтения. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


```
 open_layer_at(index, options) 
```

Открывает слой по указанному индексу для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс слоя для открытия. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Параметры открытия. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой, открытый для чтения. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

Открывает слой по указанному индексу для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс слоя для открытия. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Параметры открытия. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Слой, открытый для чтения. |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

Открывает тайловый слой с указанным именем для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя слоя для открытия. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Параметры открытия. |

**Returns**

| Тип | Описание |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | Слой плиток открыт для чтения. |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

Открывает тайловый слой по указанному индексу для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс слоя для открытия. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Параметры открытия. |

**Returns**

| Тип | Описание |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

Удаляет векторный слой с указанным именем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя слоя |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

Удаляет векторный слой по указанному индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Индекс слоя |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

Переименовать слой в наборе данных

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| current_name | string | Текущее имя слоя |
| new_name | string | Новое имя слоя |

