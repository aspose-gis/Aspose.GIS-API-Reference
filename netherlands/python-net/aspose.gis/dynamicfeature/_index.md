---
title: "DynamicFeature Klasse"
type: docs
weight: 650
url: /nl/python-net/aspose.gis/dynamicfeature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.DynamicFeature

**Inheritance:** Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Haalt of stelt de geometrie van de feature in.<br/>            Kan niet <see langword="null" /> zijn, gebruik [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) om ontbrekende geometrie aan te geven. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Kopieert waarden van attributen van een andere feature. |
| [get_as_node()](#get_as_node__2) | Haalt de feature op als knoop. Dit kan nuttig zijn voor de aangepaste gegevens |
| [get_value(attribute_name)](#get_value_attribute_name_3) | Haalt de waarde van een attribuut op. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_4) | Haalt de waarde van een attribuut op, of [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) als de waarde niet is ingesteld of <c>null</c>. |
| [get_values(values, default_value)](#get_values_values_default_value_5) | Retourneert de waarden voor alle attributen in een array. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_6) | Retourneert de waarden voor alle attributen in een array. |
| [get_values_dump(default_value)](#get_values_dump_default_value_7) | Retourneert de waarden voor alle attributen in een array.<br/>            Overweeg om de Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) methode te gebruiken om extra geheugenallocatie te voorkomen. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_8) | Haalt de waarden van een reeks attributen op als lijst. |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_9) | Bepaalt of het opgegeven attribuut expliciet is ingesteld op <c>null</c> waarde. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_10) | Controleert of de attribuutwaarde is ingesteld in deze feature. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_11) | Stelt een nieuwe waarde voor een attribuut in. |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_12) | Stelt de waarde van het attribuut in op <c>null</c>. |
| [set_values(values)](#set_values_values_13) | Stelt nieuwe waarden voor alle attributen in.<br/>            Overweeg ook om de [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) methode te gebruiken om het instellen van waarden in één oproep te stroomlijnen. |
| [unset_value(attribute_name)](#unset_value_attribute_name_14) | Verwijdert de attribuutwaarde uit deze feature. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Kopieert waarden van attributen van een andere feature.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | Het kenmerk waarvan waarden gekopieerd moeten worden. |

### Method: get_as_node() {#get_as_node__2}


```
 get_as_node() 
```

Haalt de feature op als knoop. Dit kan nuttig zijn voor de aangepaste gegevens

**Returns**

| Type | Beschrijving |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | De NodeLink naar de feature |


### Method: get_value(attribute_name) {#get_value_attribute_name_3}


```
 get_value(attribute_name) 
```

Haalt de waarde van een attribuut op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Naam van het attribuut. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| object | Waarde van het attribuut. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_4}


```
 get_value_or_default(attribute_name, default_value) 
```

Haalt de waarde van een attribuut op, of [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) als de waarde niet is ingesteld of <c>null</c>.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Naam van het attribuut. |
| default_value | object | De waarde die moet worden geretourneerd als de attribuutwaarde ontbreekt. Standaardwaarde is <see langword=\"null\" />. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| object | Waarde van het attribuut. |


### Method: get_values(values, default_value) {#get_values_values_default_value_5}


```
 get_values(values, default_value) 
```

Retourneert de waarden voor alle attributen in een array.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| values | object | De array waarin de attribuutwaarden gekopieerd moeten worden. |
| default_value | object | De waarde die moet worden geretourneerd als de attribuutwaarde ontbreekt (niet ingesteld). Standaardwaarde is <see langword=\"null\" />.<br/>            Overweeg om '.Value' te gebruiken voor het scheiden van 'niet ingesteld' en '<see langword=\"null\" />' waarden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Een aantal attributen gekopieerd. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_6}


```
 get_values(values_count, default_value) 
```

Retourneert de waarden voor alle attributen in een array.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| values_count | int | Het aantal waarden. |
| default_value | object | De waarde die moet worden geretourneerd als de attribuutwaarde ontbreekt (niet ingesteld). Standaardwaarde is <see langword=\"null\" />.<br/>            Overweeg om '.Value' te gebruiken voor het scheiden van 'niet ingesteld' en '<see langword=\"null\" />' waarden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| object | Een aantal attributen gekopieerd. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_7}


```
 get_values_dump(default_value) 
```

Retourneert de waarden voor alle attributen in een array.<br/>            Overweeg om de Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) methode te gebruiken om extra geheugenallocatie te voorkomen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| default_value | object | De waarde die moet worden geretourneerd als de attribuutwaarde ontbreekt (niet ingesteld). Standaardwaarde is <see langword=\"null\" />.<br/>            Overweeg om '.Value' te gebruiken voor het scheiden van 'niet ingesteld' en '<see langword=\"null\" />' waarden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| object | Een nieuwe array waarin de attribuutwaarden gekopieerd moeten worden. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_8}


```
 get_values_list(attribute_name, separator, count) 
```

Haalt de waarden van een reeks attributen op als lijst.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Naam van het attribuut. |
| separator | string | Een string die wordt gebruikt om de attribuutnaam en indexwaarde van de reeks te scheiden. |
| aantal | int | Aantal waarden om te retourneren (ontbrekende waarden vullen met null) |

**Returns**

| Type | Beschrijving |
| :- | :- |
| object | Lijst van waarden van de attributen waarvan de namen verschillen per indexwaarde van de reeks. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_9}


```
 is_value_null(attribute_name) 
```

Bepaalt of het opgegeven attribuut expliciet is ingesteld op <c>null</c> waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Naam van het attribuut. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword=\"true\" /> als de attribuutwaarde <c>null</c> is; anders <see langword=\"false\" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_10}


```
 is_value_set(attribute_name) 
```

Controleert of de attribuutwaarde is ingesteld in deze feature.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Naam van het attribuut. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword=\"true\" /> als de waarde voor het opgegeven attribuut is ingesteld; anders <see langword=\"false\" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_11}


```
 set_value(attribute_name, value) 
```

Stelt een nieuwe waarde voor een attribuut in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | De naam van het attribuut. |
| waarde | object | De waarde van het attribuut. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_12}


```
 set_value_null(attribute_name) 
```

Stelt de waarde van het attribuut in op <c>null</c>.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | De naam van het attribuut. |

### Method: set_values(values) {#set_values_values_13}


```
 set_values(values) 
```

Stelt nieuwe waarden voor alle attributen in.<br/>            Overweeg ook om de [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) methode te gebruiken om het instellen van waarden in één oproep te stroomlijnen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| values | object | De array met nieuwe waarden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Het aantal ingestelde attribuutwaarden. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_14}


```
 unset_value(attribute_name) 
```

Verwijdert de attribuutwaarde uit deze feature.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Naam van het attribuut. |

