---
title: "FeaturesSequence Class"
type: docs
weight: 870
url: /nl/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Haalt de collectie van aangepaste attributen op voor objecten in deze [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Haalt het ruimtelijk referentiesysteem van deze kenmerkenreeks op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_extent()](#get_extent__1) | Haalt de ruimtelijke omvang van deze laag op. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Slaat de kenmerkenreeks op in de laag. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Slaat de kenmerkenreeks op in de laag. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Slaat de kenmerkenreeks op in de laag. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Slaat de kenmerkenreeks op in de laag. |
| [split_to()](#split_to__6) | Splits kenmerken op type geometrie. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Selecteert kenmerken met een attribuutwaarde gelijk aan de opgegeven waarde. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Selecteert kenmerken met een attribuutwaarde groter dan de opgegeven waarde. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Selecteert kenmerken met een attribuutwaarde groter dan of gelijk aan de opgegeven waarde. |
| [where_intersects(extent)](#where_intersects_extent_10) | Filtert features op basis van de omvang. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Filtert features op basis van de opgegeven geometrie. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Filtert features op basis van de unie van alle geometrieën in de andere features-reeks. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Selecteert features met een attribuutwaarde die niet gelijk is aan de opgegeven waarde. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Selecteert features met een attribuut dat niet gelijk is aan null. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Selecteert features met een attribuut dat gelijk is aan null. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Selecteert features met een ingesteld attribuut. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Selecteert features met een attribuutwaarde kleiner dan de opgegeven waarde. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Selecteert features met een attribuutwaarde kleiner dan of gelijk aan de opgegeven waarde. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Selecteert features waarbij het opgegeven attribuut niet is ingesteld. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Haalt de ruimtelijke omvang van deze laag op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Een ruimtelijke omvang van deze laag. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Slaat de kenmerkenreeks op in de laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_path | string | Pad naar de uitvoerlaag. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De formatdriver voor de uitvoerlaag. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Slaat de kenmerkenreeks op in de laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de uitvoerlaag. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De formatdriver voor de uitvoerlaag. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

Slaat de kenmerkenreeks op in de laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_path | string | Pad naar de uitvoerlaag. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De formatdriver voor de uitvoerlaag. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opties voor de opslaanprocedure. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

Slaat de kenmerkenreeks op in de laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de uitvoerlaag. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De formatdriver voor de uitvoerlaag. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opties voor de opslaanprocedure. |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Splits kenmerken op type geometrie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Lagen met hetzelfde type geometrie. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

Selecteert kenmerken met een attribuutwaarde gelijk aan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objecten met attribuutwaarde gelijk aan de opgegeven waarde. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

Selecteert kenmerken met een attribuutwaarde groter dan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objecten met attribuutwaarde groter dan de opgegeven waarde. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

Selecteert kenmerken met een attribuutwaarde groter dan of gelijk aan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objecten met attribuutwaarde groter of gelijk aan de opgegeven waarde. |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

Filtert features op basis van de omvang.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filterbereik. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features die snijden met de opgegeven geometrie. |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

Filtert features op basis van de opgegeven geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filter geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features die snijden met de opgegeven geometrie. |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

Filtert features op basis van de unie van alle geometrieën in de andere features-reeks.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Andere featuresreeks. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features die snijden met de unie van alle geometrieën in de andere featuresreeks. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

Selecteert features met een attribuutwaarde die niet gelijk is aan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde die niet gelijk is aan de opgegeven waarde. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

Selecteert features met een attribuut dat niet gelijk is aan null.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde die niet gelijk is aan null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

Selecteert features met een attribuut dat gelijk is aan null.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde gelijk aan null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

Selecteert features met een ingesteld attribuut.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met ingestelde attribuutwaarde. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

Selecteert features met een attribuutwaarde kleiner dan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde kleiner dan de opgegeven waarde. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

Selecteert features met een attribuutwaarde kleiner dan of gelijk aan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde kleiner dan of gelijk aan de opgegeven waarde. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

Selecteert features waarbij het opgegeven attribuut niet is ingesteld.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met niet-ingestelde attribuutwaarde. |


