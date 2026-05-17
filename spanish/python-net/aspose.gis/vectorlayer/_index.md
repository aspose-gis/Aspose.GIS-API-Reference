---
title: "Clase VectorLayer"
type: docs
weight: 4060
url: /es/python-net/aspose.gis/vectorlayer/
---

**Summary:** Represents a vector layer.<br/>            A vector layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.VectorLayer

**Inheritance:** FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Obtiene la colección de atributos personalizados para las características en este [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| conteo | int | r | Obtiene el número de características en esta capa. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Obtiene el [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) que instanció esta capa. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Obtiene el tipo de la geometría de la capa. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Obtiene el sistema de referencia espacial de esta secuencia de características. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(feature)](#add_feature_1) | Agrega una nueva característica a la capa, si es compatible con el [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [add(feature, style)](#add_feature_style_2) | Agrega una nueva característica con el estilo especificado a la capa, si es compatible con el [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [as_in_memory()](#as_in_memory__3) | Crea una capa clon en el formato InMemory. |
| [construct_feature()](#construct_feature__4) | Crea (pero no agrega a la capa) una nueva característica con atributos que coinciden con la colección de atributos de esta capa.<br/>            Cuando haya terminado de establecer los datos para la característica, use [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) para agregar la característica a la capa. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Convierte una capa a un formato diferente. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Convierte una capa a un formato diferente. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Convierte una capa a un formato diferente. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Convierte una capa a un formato diferente. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Copia los atributos de otro [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) a esta. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Copia los atributos de otro [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) a esta. |
| [create(path, driver)](#create_path_driver_11) | Crea la capa y la abre para agregar nuevas características. |
| [create(path, driver)](#create_path_driver_12) | Crea la capa y la abre para agregar nuevas características. |
| [create(path, driver, options)](#create_path_driver_options_13) | Crea la capa y la abre para agregar nuevas características. |
| [create(path, driver, options)](#create_path_driver_options_14) | Crea la capa y la abre para agregar nuevas características. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Crea la capa y la abre para añadir. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Crea la capa y la abre para añadir. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Crea la capa y la abre para añadir. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Crea la capa y la abre para añadir. |
| [get_extent()](#get_extent__19) | Obtiene la extensión espacial de esta capa. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Interseca una capa con la capa actual por geometría. |
| [join(layer, options)](#join_layer_options_21) | Une una capa a la capa actual. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Une una capa a la capa actual por geometría. |
| [nearest_to(point)](#nearest_to_point_23) | Obtiene la característica más cercana al punto proporcionado. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Obtiene la característica más cercana a la coordenada proporcionada. |
| [open(path, driver)](#open_path_driver_25) | Abre la capa para lectura. |
| [open(path, driver)](#open_path_driver_26) | Abre la capa para lectura. |
| [open(path, driver, options)](#open_path_driver_options_27) | Abre la capa para lectura. |
| [open(path, driver, options)](#open_path_driver_options_28) | Abre la capa para lectura. |
| [remove_at(index)](#remove_at_index_29) | Elimina el [Feature](/psd/python-net/aspose.gis/feature/) en el índice especificado. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Reemplaza el [Feature](/psd/python-net/aspose.gis/feature/) en el índice especificado. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Guarda la secuencia de características en la capa. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Guarda la secuencia de características en la capa. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Guarda la secuencia de características en la capa. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Guarda la secuencia de características en la capa. |
| [split_to()](#split_to__35) | Divide las características por tipo de geometría. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Carga el índice de atributos para acelerar el filtrado por valor de atributos en métodos de filtro como Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Si el índice no existe, lo crea primero. Use <paramref name="forceRebuild" /> para forzar la recreación del índice. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Carga el índice de atributos para acelerar el filtrado por valor de atributos en métodos de filtro como Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Si el índice no existe, lo crea primero. Use <paramref name="forceRebuild" /> para forzar la recreación del índice. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Carga el índice espacial para acelerar el filtrado por valor de atributos en métodos de filtro como Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            y Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Si el índice no existe, lo crea primero. Use <paramref name="forceRebuild" /> para forzar la recreación del índice. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Carga el índice espacial para acelerar el filtrado por valor de atributos en métodos de filtro como Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            y Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Si el índice no existe, lo crea primero. Use <paramref name="forceRebuild" /> para forzar la recreación del índice. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Selecciona características cuyo valor de atributo sea igual al valor proporcionado. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Selecciona características cuyo valor de atributo sea mayor que el valor proporcionado. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Selecciona características cuyo valor de atributo sea mayor o igual al valor proporcionado. |
| [where_intersects(extent)](#where_intersects_extent_43) | Filtra características según la extensión. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Filtra características según la geometría proporcionada. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Filtra características según la unión de todas las geometrías en la secuencia de otras características. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Selecciona características cuyo valor de atributo no es igual al valor proporcionado. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Selecciona características cuyo atributo no es nulo. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Selecciona características cuyo atributo es nulo. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Selecciona características con atributo establecido. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Selecciona características cuyo valor de atributo es menor que el valor proporcionado. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Selecciona características cuyo valor de atributo es menor o igual al valor proporcionado. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Selecciona características donde el atributo especificado no está establecido. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Agrega una nueva característica a la capa, si es compatible con el [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | La característica a agregar. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Agrega una nueva característica con el estilo especificado a la capa, si es compatible con el [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | La característica a agregar. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | El estilo de la característica. Use <see langword=\"null\" /> para indicar estilo ausente. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Crea una capa clon en el formato InMemory.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La capa InMemory. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Crea (pero no agrega a la capa) una nueva característica con atributos que coinciden con la colección de atributos de esta capa.<br/>            Cuando haya terminado de establecer los datos para la característica, use [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) para agregar la característica a la capa.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Una nueva característica. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Convierte una capa a un formato diferente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_path | string | Ruta a la capa que será convertida. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de origen. |
| destination_path | string | Ruta a la capa que será creada como resultado de la conversión. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de destino. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Convierte una capa a un formato diferente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta a la capa que será convertida. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de origen. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta a la capa que será creada como resultado de la conversión. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de destino. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Convierte una capa a un formato diferente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_path | string | Ruta a la capa que será convertida. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de origen. |
| destination_path | string | Ruta a la capa que será creada como resultado de la conversión. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de destino. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Opciones para el procedimiento de conversión. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Convierte una capa a un formato diferente.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta a la capa que será convertida. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de origen. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta a la capa que será creada como resultado de la conversión. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de destino. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Opciones para el procedimiento de conversión. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Copia los atributos de otro [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) a esta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | La secuencia de características de la cual copiar atributos. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Copia los atributos de otro [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) a esta.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | La secuencia de características de la cual copiar atributos. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | Una instancia de [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) personalizada que procesará los atributos uno por uno. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Crea la capa y la abre para agregar nuevas características.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa de solo escritura. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Crea la capa y la abre para agregar nuevas características.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa de solo escritura. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Crea la capa y la abre para agregar nuevas características.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa de solo escritura. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Crea la capa y la abre para agregar nuevas características.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa de solo escritura. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Crea la capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Crea la capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Crea la capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Crea la capa y la abre para añadir.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema de referencia espacial. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una instancia de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Obtiene la extensión espacial de esta capa.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Una extensión espacial de esta capa. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Interseca una capa con la capa actual por geometría.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa para intersectar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una nueva capa como resultado de intersectar dos capas. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Une una capa a la capa actual.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa para unir. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Parámetros de unión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una nueva capa como resultado de unir dos capas. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Une una capa a la capa actual por geometría.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa para unir. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Parámetros de unión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una nueva capa como resultado de unir dos capas. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Obtiene la característica más cercana al punto proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | El punto. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | La característica más cercana al punto proporcionado. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Obtiene la característica más cercana a la coordenada proporcionada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| x | double | X de la coordenada. |
| y | double | Y de la coordenada. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | La característica más cercana a la coordenada proporcionada. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Abre la capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa de solo lectura. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Abre la capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa de solo lectura. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Abre la capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa de solo lectura. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Abre la capa para lectura.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Controlador a usar. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opciones específicas del controlador. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Una capa de solo lectura. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Elimina el [Feature](/psd/python-net/aspose.gis/feature/) en el índice especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | El índice de la característica. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Reemplaza el [Feature](/psd/python-net/aspose.gis/feature/) en el índice especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | El índice de la característica. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | La característica a establecer. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Guarda la secuencia de características en la capa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_path | string | Ruta a la capa de salida. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de salida. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Guarda la secuencia de características en la capa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta a la capa de salida. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de salida. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

Guarda la secuencia de características en la capa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_path | string | Ruta a la capa de salida. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de salida. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opciones para el procedimiento de guardado. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

Guarda la secuencia de características en la capa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta a la capa de salida. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de salida. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opciones para el procedimiento de guardado. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Divide las características por tipo de geometría.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Capas con el mismo tipo de geometría. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Carga el índice de atributos para acelerar el filtrado por valor de atributos en métodos de filtro como Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Si el índice no existe, lo crea primero. Use <paramref name="forceRebuild" /> para forzar la recreación del índice.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index_path | string | Ruta al archivo de índice. |
| attribute_name | string | Nombre del atributo sobre el cual construir el índice. |
| force_rebuild | bool | Si se debe recrear el índice aunque ya exista. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Carga el índice de atributos para acelerar el filtrado por valor de atributos en métodos de filtro como Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Si el índice no existe, lo crea primero. Use <paramref name="forceRebuild" /> para forzar la recreación del índice.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo de índice. |
| attribute_name | string | Nombre del atributo sobre el cual construir el índice. |
| force_rebuild | bool | Si se debe recrear el índice aunque ya exista. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Carga el índice espacial para acelerar el filtrado por valor de atributos en métodos de filtro como Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            y Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Si el índice no existe, lo crea primero. Use <paramref name="forceRebuild" /> para forzar la recreación del índice.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index_path | string | Ruta al archivo de índice. |
| force_rebuild | bool | Si se debe recrear el índice aunque ya exista. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Carga el índice espacial para acelerar el filtrado por valor de atributos en métodos de filtro como Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            y Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Si el índice no existe, lo crea primero. Use <paramref name="forceRebuild" /> para forzar la recreación del índice.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta al archivo de índice. |
| force_rebuild | bool | Si se debe recrear el índice aunque ya exista. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

Selecciona características cuyo valor de atributo sea igual al valor proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |
| value | object | Valor contra el cual comparar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo igual al valor proporcionado. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

Selecciona características cuyo valor de atributo sea mayor que el valor proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |
| value | object | Valor contra el cual comparar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo mayor que el valor proporcionado. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

Selecciona características cuyo valor de atributo sea mayor o igual al valor proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |
| value | object | Valor contra el cual comparar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo mayor o igual al valor proporcionado. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

Filtra características según la extensión.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filtrar extensión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características que intersectan con la geometría proporcionada. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

Filtra características según la geometría proporcionada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filtrar geometría. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características que intersectan con la geometría proporcionada. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

Filtra características según la unión de todas las geometrías en la secuencia de otras características.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Secuencia de otras características. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características que intersectan con la unión de todas las geometrías en la secuencia de otras características. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

Selecciona características cuyo valor de atributo no es igual al valor proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |
| value | object | Valor contra el cual comparar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo distinto del valor proporcionado. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

Selecciona características cuyo atributo no es nulo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo distinto de null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

Selecciona características cuyo atributo es nulo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo igual a null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

Selecciona características con atributo establecido.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo establecido. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

Selecciona características cuyo valor de atributo es menor que el valor proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |
| value | object | Valor contra el cual comparar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo menor que el valor proporcionado. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

Selecciona características cuyo valor de atributo es menor o igual al valor proporcionado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |
| value | object | Valor contra el cual comparar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo menor o igual al valor proporcionado. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

Selecciona características donde el atributo especificado no está establecido.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Atributo por el cual filtrar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Características con valor de atributo no establecido. |


