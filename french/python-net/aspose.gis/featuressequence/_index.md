---
title: "FeaturesSequence Classe"
type: docs
weight: 870
url: /fr/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Obtient la collection d'attributs personnalisés pour les entités de ce [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Obtient le système de référence spatiale de cette séquence de caractéristiques. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_extent()](#get_extent__1) | Obtient l'étendue spatiale de cette couche. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Enregistre la séquence d'entités dans la couche. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Enregistre la séquence d'entités dans la couche. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Enregistre la séquence d'entités dans la couche. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Enregistre la séquence d'entités dans la couche. |
| [split_to()](#split_to__6) | Divise les entités par type de géométrie. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Sélectionne les entités dont la valeur d'attribut est égale à la valeur fournie. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Sélectionne les entités dont la valeur d'attribut est supérieure à la valeur fournie. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Sélectionne les entités dont la valeur d'attribut est supérieure ou égale à la valeur fournie. |
| [where_intersects(extent)](#where_intersects_extent_10) | Filtre les entités en fonction de l'étendue. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Filtre les entités en fonction de la géométrie fournie. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Filtre les entités en fonction de l'union de toutes les géométries dans la séquence d'autres entités. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Sélectionne les entités dont la valeur d'attribut n'est pas égale à la valeur fournie. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Sélectionne les entités dont l'attribut n'est pas nul. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Sélectionne les entités dont l'attribut est nul. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Sélectionne les entités dont l'attribut est défini. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Sélectionne les entités dont la valeur d'attribut est inférieure à la valeur fournie. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Sélectionne les entités dont la valeur d'attribut est inférieure ou égale à la valeur fournie. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Sélectionne les entités où l'attribut spécifié n'est pas défini. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Obtient l'étendue spatiale de cette couche.

**Returns**

| Type | Description |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Une étendue spatiale de cette couche. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Enregistre la séquence d'entités dans la couche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_path | string | Chemin vers la couche de sortie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de sortie. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Enregistre la séquence d'entités dans la couche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers la couche de sortie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de sortie. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

Enregistre la séquence d'entités dans la couche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_path | string | Chemin vers la couche de sortie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de sortie. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Options pour la procédure d'enregistrement. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

Enregistre la séquence d'entités dans la couche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers la couche de sortie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de sortie. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Options pour la procédure d'enregistrement. |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Divise les entités par type de géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Couches avec le même type de géométrie. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est égale à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est égale à la valeur fournie. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est supérieure à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est supérieure à la valeur fournie. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est supérieure ou égale à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est supérieure ou égale à la valeur fournie. |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

Filtre les entités en fonction de l'étendue.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filtrer l'étendue. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités qui intersectent la géométrie fournie. |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

Filtre les entités en fonction de la géométrie fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filtrer la géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités qui intersectent la géométrie fournie. |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

Filtre les entités en fonction de l'union de toutes les géométries dans la séquence d'autres entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Autre séquence d'entités. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités qui intersectent l'union de toutes les géométries de l'autre séquence d'entités. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut n'est pas égale à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut n'est pas égale à la valeur fournie. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

Sélectionne les entités dont l'attribut n'est pas nul.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut n'est pas égale à null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

Sélectionne les entités dont l'attribut est nul.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est égale à null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

Sélectionne les entités dont l'attribut est défini.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités avec une valeur d'attribut définie. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est inférieure à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est inférieure à la valeur fournie. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est inférieure ou égale à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est inférieure ou égale à la valeur fournie. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

Sélectionne les entités où l'attribut spécifié n'est pas défini.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut n'est pas définie. |


