---
title: "FeaturesSequence Klasse"
type: docs
weight: 870
url: /de/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Ruft die Sammlung benutzerdefinierter Attribute für Features in diesem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ab. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Ermittelt das räumliche Referenzsystem dieser Feature‑Sequenz. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_extent()](#get_extent__1) | Ermittelt den räumlichen Umfang dieses Layers. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Speichert die Feature‑Sequenz im Layer. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Speichert die Feature‑Sequenz im Layer. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Speichert die Feature‑Sequenz im Layer. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Speichert die Feature‑Sequenz im Layer. |
| [split_to()](#split_to__6) | Teilt Features nach Geometrietyp. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Wählt Features aus, deren Attributwert dem angegebenen Wert entspricht. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Wählt Features aus, deren Attributwert größer als der angegebene Wert ist. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Wählt Features aus, deren Attributwert größer oder gleich dem angegebenen Wert ist. |
| [where_intersects(extent)](#where_intersects_extent_10) | Filtert Features basierend auf der Ausdehnung. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Filtert Features basierend auf der bereitgestellten Geometrie. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Filtert Features basierend auf der Vereinigung aller Geometrien in der anderen Feature‑Sequenz. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Wählt Features aus, deren Attributwert nicht dem bereitgestellten Wert entspricht. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Wählt Features aus, deren Attribut nicht null ist. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Wählt Features aus, deren Attribut null ist. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Wählt Features aus, bei denen das Attribut gesetzt ist. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Wählt Features aus, deren Attributwert kleiner als der bereitgestellte Wert ist. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Wählt Features aus, deren Attributwert kleiner oder gleich dem bereitgestellten Wert ist. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Wählt Features aus, bei denen das angegebene Attribut nicht gesetzt ist. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Ermittelt den räumlichen Umfang dieses Layers.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ein räumlicher Ausdehnungsbereich dieser Ebene. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Speichert die Feature‑Sequenz im Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_path | string | Pfad zur Ausgabeebene. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Formattreiber für die Ausgabeebene. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Speichert die Feature‑Sequenz im Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Ausgabeebene. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Formattreiber für die Ausgabeebene. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

Speichert die Feature‑Sequenz im Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_path | string | Pfad zur Ausgabeebene. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Formattreiber für die Ausgabeebene. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Optionen für den Speicherungsprozess. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

Speichert die Feature‑Sequenz im Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Ausgabeebene. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Formattreiber für die Ausgabeebene. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Optionen für den Speicherungsprozess. |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Teilt Features nach Geometrietyp.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Ebenen mit demselben Geometrietyp. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

Wählt Features aus, deren Attributwert dem angegebenen Wert entspricht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der dem angegebenen Wert entspricht. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

Wählt Features aus, deren Attributwert größer als der angegebene Wert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der größer ist als der angegebene Wert. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

Wählt Features aus, deren Attributwert größer oder gleich dem angegebenen Wert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der größer oder gleich dem angegebenen Wert ist. |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

Filtert Features basierend auf der Ausdehnung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filterbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features, die mit der bereitgestellten Geometrie schneiden. |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

Filtert Features basierend auf der bereitgestellten Geometrie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filtergeometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features, die mit der bereitgestellten Geometrie schneiden. |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

Filtert Features basierend auf der Vereinigung aller Geometrien in der anderen Feature‑Sequenz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Andere Feature-Sequenz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features, die mit der Vereinigung aller Geometrien in der anderen Feature-Sequenz schneiden. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

Wählt Features aus, deren Attributwert nicht dem bereitgestellten Wert entspricht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der nicht dem angegebenen Wert entspricht. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

Wählt Features aus, deren Attribut nicht null ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der nicht null ist. |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

Wählt Features aus, deren Attribut null ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der null ist. |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

Wählt Features aus, bei denen das Attribut gesetzt ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit gesetztem Attributwert. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

Wählt Features aus, deren Attributwert kleiner als der bereitgestellte Wert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert kleiner als der angegebene Wert. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

Wählt Features aus, deren Attributwert kleiner oder gleich dem bereitgestellten Wert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert kleiner oder gleich dem angegebenen Wert. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

Wählt Features aus, bei denen das angegebene Attribut nicht gesetzt ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit nicht gesetztem Attributwert. |


