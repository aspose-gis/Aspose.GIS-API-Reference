---
title: "Feature-klass"
type: docs
weight: 830
url: /sv/python-net/aspose.gis/feature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Hämtar eller anger geometri för feature.<br/>            Kan inte vara <see langword="null" />, använd [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) för att ange saknad geometri. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Kopierar attributvärden från en annan feature. |
| [get_value(attribute_name)](#get_value_attribute_name_2) | Hämtar värdet på ett attribut. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_3) | Hämtar värdet på ett attribut, eller [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) om värdet är odefinierat eller <c>null</c>. |
| [get_values(values, default_value)](#get_values_values_default_value_4) | Returnerar värdena för alla attribut i en array. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_5) | Returnerar värdena för alla attribut i en array. |
| [get_values_dump(default_value)](#get_values_dump_default_value_6) | Returnerar värdena för alla attribut i en array.<br/>            Överväg att använda Aspose.Gis.Feature.GetValues(int,System.Object) för att undvika extra minnesallokering. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_7) | Hämtar värdelistan. Icke-generisk motsvarighet till List T GetValuesList |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_8) | Bestämmer om det angivna attributet har uttryckligen satts till <c>null</c>-värde. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_9) | Kontrollerar om attributvärdet är satt i detta objekt. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_10) | Sätter värdet. Icke-generisk motsvarighet till void SetValue (string attributeName, T value) |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_11) | Sätter attributets värde till <c>null</c>. |
| [set_values(values)](#set_values_values_12) | Sätter nya värden för alla attribut.<br/>            Överväg också att använda metoden [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) för att effektivisera att sätta värden i ett enda anrop. |
| [unset_value(attribute_name)](#unset_value_attribute_name_13) | Tar bort attributvärdet från detta objekt. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Kopierar attributvärden från en annan feature.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | Objektet att kopiera värden från. |

### Method: get_value(attribute_name) {#get_value_attribute_name_2}


```
 get_value(attribute_name) 
```

Hämtar värdet på ett attribut.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Namnet på attributet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| objekt | Värdet på attributet. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_3}


```
 get_value_or_default(attribute_name, default_value) 
```

Hämtar värdet på ett attribut, eller [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) om värdet är odefinierat eller <c>null</c>.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Namnet på attributet. |
| default_value | objekt | Värdet att returnera om attributvärdet saknas. Standardvärdet är <see langword="null" />. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| objekt | Värdet på attributet. |


### Method: get_values(values, default_value) {#get_values_values_default_value_4}


```
 get_values(values, default_value) 
```

Returnerar värdena för alla attribut i en array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värden | objekt |  |
| default_value | objekt | Värdet att returnera om attributvärdet saknas (ej satt). Standardvärdet är <see langword="null" />.<br/>            Överväg att använda '.Value' för att skilja mellan 'ej satt' och '<see langword="null" />'-värden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Antalet kopierade attribut. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_5}


```
 get_values(values_count, default_value) 
```

Returnerar värdena för alla attribut i en array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| values_count | int | Antalet värden. |
| default_value | objekt | Värdet att returnera om attributvärdet saknas (ej satt). Standardvärdet är <see langword="null" />.<br/>            Överväg att använda '.Value' för att skilja mellan 'ej satt' och '<see langword="null" />'-värden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| objekt | Antalet kopierade attribut. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_6}


```
 get_values_dump(default_value) 
```

Returnerar värdena för alla attribut i en array.<br/>            Överväg att använda Aspose.Gis.Feature.GetValues(int,System.Object) för att undvika extra minnesallokering.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| default_value | objekt | Värdet att returnera om attributvärdet saknas (ej satt). Standardvärdet är <see langword="null" />.<br/>            Överväg att använda '.Value' för att skilja mellan 'ej satt' och '<see langword="null" />'-värden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| objekt | En ny array att kopiera attributvärdena till. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_7}


```
 get_values_list(attribute_name, separator, count) 
```

Hämtar värdelistan. Icke-generisk motsvarighet till List T GetValuesList

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Namnet på attributet. |
| separator | string | En sträng som används för att separera attributnamn och indexvärde i sekvensen. |
| antal | int | Antal värden att returnera (saknade värden fylls med null) |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| objekt | Lista med värden för attributen vars namn skiljer sig åt efter sekvensens indexvärde. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_8}


```
 is_value_null(attribute_name) 
```

Bestämmer om det angivna attributet har uttryckligen satts till <c>null</c>-värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Namnet på attributet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword="true" /> om attributvärdet är <c>null</c>; annars <see langword="false" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_9}


```
 is_value_set(attribute_name) 
```

Kontrollerar om attributvärdet är satt i detta objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Namnet på attributet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword="true" /> om värdet för det angivna attributet är satt; annars <see langword="false" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_10}


```
 set_value(attribute_name, value) 
```

Sätter värdet. Icke-generisk motsvarighet till void SetValue (string attributeName, T value)

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Namnet på attributet. |
| value | objekt | Värdet på attributet. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_11}


```
 set_value_null(attribute_name) 
```

Sätter attributets värde till <c>null</c>.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Namnet på attributet. |

### Method: set_values(values) {#set_values_values_12}


```
 set_values(values) 
```

Sätter nya värden för alla attribut.<br/>            Överväg också att använda metoden [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) för att effektivisera att sätta värden i ett enda anrop.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| värden | objekt | Arrayen med nya värden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Antalet attributvärden som har satts. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_13}


```
 unset_value(attribute_name) 
```

Tar bort attributvärdet från detta objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Namnet på attributet. |

