---
title: "Classe FeaturesSequence"
type: docs
weight: 870
url: /it/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Ottiene la collezione di attributi personalizzati per le feature in questo [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Restituisce il sistema di riferimento spaziale di questa sequenza di feature. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_extent()](#get_extent__1) | Restituisce l'estensione spaziale di questo layer. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Salva la sequenza di feature nel layer. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Salva la sequenza di feature nel layer. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Salva la sequenza di feature nel layer. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Salva la sequenza di feature nel layer. |
| [split_to()](#split_to__6) | Dividi le feature per tipo di geometria. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Seleziona le feature con valore dell'attributo uguale al valore fornito. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Seleziona le feature con valore dell'attributo maggiore del valore fornito. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Seleziona le feature con valore dell'attributo maggiore o uguale al valore fornito. |
| [where_intersects(extent)](#where_intersects_extent_10) | Filtra le feature in base all'estensione. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Filtra le feature in base alla geometria fornita. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Filtra le feature in base all'unione di tutte le geometrie nella sequenza di altre feature. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Seleziona le feature il cui valore dell'attributo non è uguale al valore fornito. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Seleziona le feature il cui attributo non è uguale a null. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Seleziona le feature il cui attributo è uguale a null. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Seleziona le feature con attributo impostato. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Seleziona le feature il cui valore dell'attributo è inferiore al valore fornito. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Seleziona le feature il cui valore dell'attributo è inferiore o uguale al valore fornito. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Seleziona le feature dove l'attributo specificato non è impostato. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Restituisce l'estensione spaziale di questo layer.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Un'estensione spaziale di questo layer. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Salva la sequenza di feature nel layer.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_path | string | Percorso del livello di output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il livello di output. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Salva la sequenza di feature nel layer.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del livello di output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il livello di output. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

Salva la sequenza di feature nel layer.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_path | string | Percorso del livello di output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il livello di output. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opzioni per la procedura di salvataggio. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

Salva la sequenza di feature nel layer.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del livello di output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il livello di output. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opzioni per la procedura di salvataggio. |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Dividi le feature per tipo di geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Livelli con lo stesso tipo di geometria. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

Seleziona le feature con valore dell'attributo uguale al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Caratteristiche con valore dell'attributo uguale al valore fornito. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

Seleziona le feature con valore dell'attributo maggiore del valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Caratteristiche con valore dell'attributo maggiore del valore fornito. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

Seleziona le feature con valore dell'attributo maggiore o uguale al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Caratteristiche con valore dell'attributo maggiore o uguale al valore fornito. |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

Filtra le feature in base all'estensione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filtra l'estensione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features che si intersecano con la geometria fornita. |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

Filtra le feature in base alla geometria fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filtra la geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features che si intersecano con la geometria fornita. |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

Filtra le feature in base all'unione di tutte le geometrie nella sequenza di altre feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sequenza di altre feature. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature che si intersecano con l'unione di tutte le geometrie nella sequenza di altre feature. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

Seleziona le feature il cui valore dell'attributo non è uguale al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo diverso dal valore fornito. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

Seleziona le feature il cui attributo non è uguale a null.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo diverso da null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

Seleziona le feature il cui attributo è uguale a null.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo uguale a null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

Seleziona le feature con attributo impostato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo impostato. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

Seleziona le feature il cui valore dell'attributo è inferiore al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo inferiore al valore fornito. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

Seleziona le feature il cui valore dell'attributo è inferiore o uguale al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo inferiore o uguale al valore fornito. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

Seleziona le feature dove l'attributo specificato non è impostato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo non impostato. |


