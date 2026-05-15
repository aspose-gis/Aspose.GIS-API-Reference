---
title: "DynamicFeature Klasse"
type: docs
weight: 650
url: /de/python-net/aspose.gis/dynamicfeature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.DynamicFeature

**Inheritance:** Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Liest oder setzt die Geometrie des Features.<br/>            Darf nicht <see langword=\"null\" /> sein, verwende [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), um fehlende Geometrie anzuzeigen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Kopiert Werte von Attributen aus einem anderen Feature. |
| [get_as_node()](#get_as_node__2) | Liefert das Feature als Knoten. Dies kann für benutzerdefinierte Daten hilfreich sein. |
| [get_value(attribute_name)](#get_value_attribute_name_3) | Liest den Wert eines Attributs. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_4) | Liest den Wert eines Attributs, oder [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/), wenn der Wert nicht gesetzt oder <c>null</c> ist. |
| [get_values(values, default_value)](#get_values_values_default_value_5) | Gibt die Werte aller Attribute in einem Array zurück. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_6) | Gibt die Werte aller Attribute in einem Array zurück. |
| [get_values_dump(default_value)](#get_values_dump_default_value_7) | Gibt die Werte aller Attribute in einem Array zurück.<br/>            Erwäge die Verwendung der Methode Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object), um zusätzliche Speicherzuweisungen zu vermeiden. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_8) | Liefert die Werte einer Attributsequenz als Liste. |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_9) | Bestimmt, ob das angegebene Attribut explizit auf den Wert <c>null</c> gesetzt wurde. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_10) | Prüft, ob der Attributwert in diesem Feature gesetzt ist. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_11) | Setzt einen neuen Wert eines Attributs. |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_12) | Setzt den Wert des Attributs auf <c>null</c>. |
| [set_values(values)](#set_values_values_13) | Setzt neue Werte für alle Attribute.<br/>            Erwäge außerdem die Verwendung der Methode [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/), um das Setzen von Werten in einem Aufruf zu vereinfachen. |
| [unset_value(attribute_name)](#unset_value_attribute_name_14) | Entfernt den Attributwert aus diesem Feature. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Kopiert Werte von Attributen aus einem anderen Feature.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | Das Feature, aus dem Werte kopiert werden sollen. |

### Method: get_as_node() {#get_as_node__2}


```
 get_as_node() 
```

Liefert das Feature als Knoten. Dies kann für benutzerdefinierte Daten hilfreich sein.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Der NodeLink zum Feature |


### Method: get_value(attribute_name) {#get_value_attribute_name_3}


```
 get_value(attribute_name) 
```

Liest den Wert eines Attributs.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Name des Attributs. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| object | Wert des Attributs. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_4}


```
 get_value_or_default(attribute_name, default_value) 
```

Liest den Wert eines Attributs, oder [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/), wenn der Wert nicht gesetzt oder <c>null</c> ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Name des Attributs. |
| default_value | object | Der zurückzugebende Wert, wenn der Attributwert fehlt. Standardwert ist <see langword=\"null\" />. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| object | Wert des Attributs. |


### Method: get_values(values, default_value) {#get_values_values_default_value_5}


```
 get_values(values, default_value) 
```

Gibt die Werte aller Attribute in einem Array zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Werte | object | Das Array, in das die Attributwerte kopiert werden. |
| default_value | object | Der zurückzugebende Wert, wenn der Attributwert fehlt (nicht gesetzt). Standardwert ist <see langword=\"null\" />.<br/>            Erwägen Sie die Verwendung von '.Value', um 'nicht gesetzt' und '<see langword=\"null\" />'-Werte zu unterscheiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Eine Anzahl von kopierten Attributen. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_6}


```
 get_values(values_count, default_value) 
```

Gibt die Werte aller Attribute in einem Array zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| values_count | int | Die Anzahl der Werte. |
| default_value | object | Der zurückzugebende Wert, wenn der Attributwert fehlt (nicht gesetzt). Standardwert ist <see langword=\"null\" />.<br/>            Erwägen Sie die Verwendung von '.Value', um 'nicht gesetzt' und '<see langword=\"null\" />'-Werte zu unterscheiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| object | Eine Anzahl von kopierten Attributen. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_7}


```
 get_values_dump(default_value) 
```

Gibt die Werte aller Attribute in einem Array zurück.<br/>            Erwäge die Verwendung der Methode Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object), um zusätzliche Speicherzuweisungen zu vermeiden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| default_value | object | Der zurückzugebende Wert, wenn der Attributwert fehlt (nicht gesetzt). Standardwert ist <see langword=\"null\" />.<br/>            Erwägen Sie die Verwendung von '.Value', um 'nicht gesetzt' und '<see langword=\"null\" />'-Werte zu unterscheiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| object | Ein neues Array, in das die Attributwerte kopiert werden. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_8}


```
 get_values_list(attribute_name, separator, count) 
```

Liefert die Werte einer Attributsequenz als Liste.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Name des Attributs. |
| separator | string | Eine Zeichenkette, die verwendet wird, um den Attributnamen und den Indexwert der Sequenz zu trennen. |
| Anzahl | int | Anzahl der zurückzugebenden Werte (fehlende Werte mit null füllen) |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| object | Liste von Werten der Attribute, deren Namen sich durch den Sequenzindexwert unterscheiden. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_9}


```
 is_value_null(attribute_name) 
```

Bestimmt, ob das angegebene Attribut explizit auf den Wert <c>null</c> gesetzt wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Name des Attributs. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn der Attributwert <c>null</c> ist; andernfalls <see langword=\"false\" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_10}


```
 is_value_set(attribute_name) 
```

Prüft, ob der Attributwert in diesem Feature gesetzt ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Name des Attributs. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn der Wert für das angegebene Attribut gesetzt ist; andernfalls <see langword=\"false\" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_11}


```
 set_value(attribute_name, value) 
```

Setzt einen neuen Wert eines Attributs.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Der Name des Attributs. |
| value | object | Der Wert des Attributs. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_12}


```
 set_value_null(attribute_name) 
```

Setzt den Wert des Attributs auf <c>null</c>.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Der Name des Attributs. |

### Method: set_values(values) {#set_values_values_13}


```
 set_values(values) 
```

Setzt neue Werte für alle Attribute.<br/>            Erwäge außerdem die Verwendung der Methode [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/), um das Setzen von Werten in einem Aufruf zu vereinfachen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Werte | object | Das Array neuer Werte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Anzahl der gesetzten Attributwerte. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_14}


```
 unset_value(attribute_name) 
```

Entfernt den Attributwert aus diesem Feature.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Name des Attributs. |

