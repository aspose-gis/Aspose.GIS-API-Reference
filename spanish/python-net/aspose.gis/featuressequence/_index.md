---
title: "Clase FeaturesSequence"
type: docs
weight: 870
url: /es/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Obtiene la colección de atributos personalizados para las características en este [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Obtiene el sistema de referencia espacial de esta secuencia de características. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_extent()](#get_extent__1) | Obtiene la extensión espacial de esta capa. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Guarda la secuencia de características en la capa. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Guarda la secuencia de características en la capa. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Guarda la secuencia de características en la capa. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Guarda la secuencia de características en la capa. |
| [split_to()](#split_to__6) | Divide las características por tipo de geometría. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Selecciona características cuyo valor de atributo sea igual al valor proporcionado. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Selecciona características cuyo valor de atributo sea mayor que el valor proporcionado. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Selecciona características cuyo valor de atributo sea mayor o igual al valor proporcionado. |
| [where_intersects(extent)](#where_intersects_extent_10) | Filtra características según la extensión. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Filtra características según la geometría proporcionada. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Filtra características según la unión de todas las geometrías en la secuencia de otras características. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Selecciona características cuyo valor de atributo no es igual al valor proporcionado. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Selecciona características cuyo atributo no es nulo. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Selecciona características cuyo atributo es nulo. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Selecciona características con atributo establecido. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Selecciona características cuyo valor de atributo es menor que el valor proporcionado. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Selecciona características cuyo valor de atributo es menor o igual al valor proporcionado. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Selecciona características donde el atributo especificado no está establecido. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Obtiene la extensión espacial de esta capa.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Una extensión espacial de esta capa. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Guarda la secuencia de características en la capa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_path | string | Ruta a la capa de salida. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de salida. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Guarda la secuencia de características en la capa.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ruta a la capa de salida. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | El controlador de formato para la capa de salida. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


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

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


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

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Divide las características por tipo de geometría.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Capas con el mismo tipo de geometría. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


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


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


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


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


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


### Method: where_intersects(extent) {#where_intersects_extent_10}


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


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


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


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


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


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


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


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


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


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


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


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


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


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


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


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


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


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


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


