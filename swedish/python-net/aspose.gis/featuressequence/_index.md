---
title: "FeaturesSequence-klass"
type: docs
weight: 870
url: /sv/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Hämtar samlingen av anpassade attribut för funktioner i denna [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Hämtar det rumsliga referenssystemet för den här funktionssekvensen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_extent()](#get_extent__1) | Hämtar ett rumsligt omfång för detta lager. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Sparar objektssekvensen till lagret. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Sparar objektssekvensen till lagret. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Sparar objektssekvensen till lagret. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Sparar objektssekvensen till lagret. |
| [split_to()](#split_to__6) | Dela upp objekt efter geometrityp. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Väljer objekt med attributvärde lika med det angivna värdet. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Väljer objekt med attributvärde större än det angivna värdet. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Väljer objekt med attributvärde större än eller lika med det angivna värdet. |
| [where_intersects(extent)](#where_intersects_extent_10) | Filtrerar funktioner baserat på omfånget. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Filtrerar funktioner baserat på den angivna geometrin. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Filtrerar funktioner baserat på unionen av alla geometrier i den andra funktionssekvensen. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Väljer funktioner med attributvärde som inte är lika med det angivna värdet. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Väljer funktioner med attribut som inte är null. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Väljer funktioner med attribut lika med null. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Väljer funktioner med attribut satt. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Väljer funktioner med attributvärde mindre än det angivna värdet. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Väljer funktioner med attributvärde mindre än eller lika med det angivna värdet. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Väljer funktioner där specificerat attribut inte är satt. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Hämtar ett rumsligt omfång för detta lager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ett rumsligt omfång för detta lager. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Sparar objektssekvensen till lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_path | string | Sökväg till utdatalagret. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för utdatalagret. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Sparar objektssekvensen till lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till utdatalagret. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för utdatalagret. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

Sparar objektssekvensen till lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_path | string | Sökväg till utdatalagret. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för utdatalagret. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Alternativ för sparningsproceduren. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

Sparar objektssekvensen till lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till utdatalagret. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för utdatalagret. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Alternativ för sparningsproceduren. |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Dela upp objekt efter geometrityp.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Lager med samma geometrityp. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

Väljer objekt med attributvärde lika med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objekt med attributvärde lika med det angivna värdet. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

Väljer objekt med attributvärde större än det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objekt med attributvärde större än det angivna värdet. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

Väljer objekt med attributvärde större än eller lika med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objekt med attributvärde större än eller lika med det angivna värdet. |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

Filtrerar funktioner baserat på omfånget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filtrera omfång. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner som skär med den angivna geometrin. |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

Filtrerar funktioner baserat på den angivna geometrin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filtrera geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner som skär med den angivna geometrin. |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

Filtrerar funktioner baserat på unionen av alla geometrier i den andra funktionssekvensen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sekvens för andra funktioner. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner som skär med unionen av alla geometrier i den andra funktionernas sekvens. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

Väljer funktioner med attributvärde som inte är lika med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde som inte är lika med det angivna värdet. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

Väljer funktioner med attribut som inte är null.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde som inte är lika med null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

Väljer funktioner med attribut lika med null.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde lika med null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

Väljer funktioner med attribut satt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med satt attributvärde. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

Väljer funktioner med attributvärde mindre än det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde mindre än det angivna värdet. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

Väljer funktioner med attributvärde mindre än eller lika med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde mindre än eller lika med det angivna värdet. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

Väljer funktioner där specificerat attribut inte är satt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med odefinierat attributvärde. |


