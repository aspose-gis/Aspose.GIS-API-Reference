---
title: "Класс EsriJsonDriver"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.formats.esrijson/esrijsondriver/
---

**Summary:** A driver for the EsriJson format.

**Module:** [aspose.gis.formats.esrijson](/psd/python-net/aspose.gis.formats.esrijson/)

**Full Name:** aspose.gis.formats.esrijson.EsriJsonDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Возвращает значение, указывающее, может ли данный драйвер создавать наборы данных. |
| can_create_layers | bool | r | Возвращает значение, указывающее, может ли данный драйвер создавать векторные слои. |
| can_open_datasets | bool | r | Возвращает значение, указывающее, может ли данный драйвер открывать наборы данных. |
| can_open_layers | bool | r | Возвращает значение, указывающее, может ли данный драйвер открывать векторные слои. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Создаёт набор данных. |
| [create_dataset(path)](#create_dataset_path_2) | Создаёт набор данных. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Создаёт набор данных. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Создаёт набор данных. |
| [create_layer(path)](#create_layer_path_5) | Создаёт слой и открывает его для добавления. |
| [create_layer(path)](#create_layer_path_6) | Создаёт слой и открывает его для добавления. |
| [create_layer(path, options)](#create_layer_path_options_7) | Создаёт слой и открывает его для добавления новых объектов. |
| [create_layer(path, options)](#create_layer_path_options_8) | Создаёт слой и открывает его для добавления новых объектов. |
| [create_layer(path, options)](#create_layer_path_options_9) | Создаёт слой и открывает его для добавления новых объектов. |
| [create_layer(path, options)](#create_layer_path_options_10) | Создаёт слой и открывает его для добавления новых объектов. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | Создаёт слой и открывает его для добавления новых объектов. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Создаёт слой и открывает его для добавления новых объектов. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Создаёт слой и открывает его для добавления новых объектов. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | Создаёт слой и открывает его для добавления. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | Создаёт слой и открывает его для добавления. |
| [edit_layer(path, options)](#edit_layer_path_options_16) | Открывает слой для редактирования. |
| [edit_layer(path, options)](#edit_layer_path_options_17) | Открывает слой для редактирования. |
| [open_dataset(path)](#open_dataset_path_18) | Открывает набор данных. |
| [open_dataset(path)](#open_dataset_path_19) | Открывает набор данных. |
| [open_dataset(path, options)](#open_dataset_path_options_20) | Открывает набор данных. |
| [open_dataset(path, options)](#open_dataset_path_options_21) | Открывает набор данных. |
| [open_layer(path)](#open_layer_path_22) | Открывает слой для чтения. |
| [open_layer(path)](#open_layer_path_23) | Открывает слой для чтения. |
| [open_layer(path, options)](#open_layer_path_options_24) | Открывает слой для чтения. |
| [open_layer(path, options)](#open_layer_path_options_25) | Открывает слой для чтения. |
| [open_layer(path, options)](#open_layer_path_options_26) | Открывает слой для чтения. |
| [open_layer(path, options)](#open_layer_path_options_27) | Открывает слой для чтения. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_28) | Определяет, поддерживается ли указанная система координат драйвером. |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Создаёт набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к набору данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Создаёт набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к набору данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Создаёт набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к набору данных. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Создаёт набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к набору данных. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

Создаёт слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

Создаёт слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| options | [EsriJsonOptions](/psd/python-net/aspose.gis.formats.esrijson/esrijsonoptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| options | [EsriJsonOptions](/psd/python-net/aspose.gis.formats.esrijson/esrijsonoptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| options | [EsriJsonOptions](/psd/python-net/aspose.gis.formats.esrijson/esrijsonoptions) | Опции, специфичные для драйвера. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Создаёт слой и открывает его для добавления новых объектов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


```
 create_layer(path, spatial_reference_system) 
```

Создаёт слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


```
 create_layer(path, spatial_reference_system) 
```

Создаёт слой и открывает его для добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


```
 edit_layer(path, options) 
```

Открывает слой для редактирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


```
 edit_layer(path, options) 
```

Открывает слой для редактирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_18}


```
 open_dataset(path) 
```

Открывает набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к набору данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_19}


```
 open_dataset(path) 
```

Открывает набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к набору данных. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_20}


```
 open_dataset(path, options) 
```

Открывает набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к набору данных. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


```
 open_dataset(path, options) 
```

Открывает набор данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к набору данных. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Экземпляр [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_22}


```
 open_layer(path) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_23}


```
 open_layer(path) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_24}


```
 open_layer(path, options) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| options | [EsriJsonOptions](/psd/python-net/aspose.gis.formats.esrijson/esrijsonoptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |
| options | [EsriJsonOptions](/psd/python-net/aspose.gis.formats.esrijson/esrijsonoptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

Открывает слой для чтения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Опции, специфичные для драйвера. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Экземпляр [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_28}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Определяет, поддерживается ли указанная система координат драйвером.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система координат. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Булево значение, указывающее, поддерживается ли указанная система координат драйвером. |


