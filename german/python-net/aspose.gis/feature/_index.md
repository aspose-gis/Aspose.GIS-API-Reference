---
title: "Feature Klasse"
type: docs
weight: 830
url: /de/python-net/aspose.gis/feature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Liest oder setzt die Geometrie des Features.<br/>            Darf nicht <see langword=\"null\" /> sein, verwende [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), um fehlende Geometrie anzuzeigen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Kopiert Werte von Attributen aus einem anderen Feature. |
| [get_value(attribute_name)](#get_value_attribute_name_2) | Liest den Wert eines Attributs. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_3) | Liest den Wert eines Attributs, oder [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/), wenn der Wert nicht gesetzt oder <c>null</c> ist. |
| [get_values(values, default_value)](#get_values_values_default_value_4) | Gibt die Werte aller Attribute in einem Array zurück. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_5) | Gibt die Werte aller Attribute in einem Array zurück. |
| [get_values_dump(default_value)](#get_values_dump_default_value_6) | Gibt die Werte aller Attribute in einem Array zurück.<br/>            Erwägen Sie die Verwendung der Methode Aspose.Gis.Feature.GetValues(int,System.Object), um zusätzliche Speicherzuweisungen zu vermeiden. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_7) | Ruft die Werteliste ab. Nicht-generische Analogie zu List T GetValuesList |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_8) | Bestimmt, ob das angegebene Attribut explizit auf den Wert <c>null</c> gesetzt wurde. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_9) | Prüft, ob der Attributwert in diesem Feature gesetzt ist. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_10) | Setzt den Wert. Nicht-generische Analogie zu void SetValue (string attributeName, T value) |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_11) | Setzt den Wert des Attributs auf <c>null</c>. |
| [set_values(values)](#set_values_values_12) | Setzt neue Werte für alle Attribute.<br/>            Erwägen Sie außerdem die Verwendung der Methode [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/), um das Setzen von Werten in einem Aufruf zu vereinfachen. |
| [unset_value(attribute_name)](#unset_value_attribute_name_13) | Entfernt den Attributwert aus diesem Feature. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Kopiert Werte von Attributen aus einem anderen Feature.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | Das Feature, aus dem Werte kopiert werden sollen. |

### Method: get_value(attribute_name) {#get_value_attribute_name_2}


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


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_3}


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


### Method: get_values(values, default_value) {#get_values_values_default_value_4}


```
 get_values(values, default_value) 
```

Gibt die Werte aller Attribute in einem Array zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Werte | object |  |
| default_value | object | Der zurückzugebende Wert, wenn der Attributwert fehlt (nicht gesetzt). Standardwert ist <see langword=\"null\" />.<br/>            Erwägen Sie die Verwendung von '.Value', um 'nicht gesetzt' und '<see langword=\"null\" />'-Werte zu unterscheiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Eine Anzahl von kopierten Attributen. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_5}


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


### Method: get_values_dump(default_value) {#get_values_dump_default_value_6}


```
 get_values_dump(default_value) 
```

Gibt die Werte aller Attribute in einem Array zurück.<br/>            Erwägen Sie die Verwendung der Methode Aspose.Gis.Feature.GetValues(int,System.Object), um zusätzliche Speicherzuweisungen zu vermeiden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| default_value | object | Der zurückzugebende Wert, wenn der Attributwert fehlt (nicht gesetzt). Standardwert ist <see langword=\"null\" />.<br/>            Erwägen Sie die Verwendung von '.Value', um 'nicht gesetzt' und '<see langword=\"null\" />'-Werte zu unterscheiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| object | Ein neues Array, in das die Attributwerte kopiert werden. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_7}


```
 get_values_list(attribute_name, separator, count) 
```

Ruft die Werteliste ab. Nicht-generische Analogie zu List T GetValuesList

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


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_8}


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


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_9}


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


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_10}


```
 set_value(attribute_name, value) 
```

Setzt den Wert. Nicht-generische Analogie zu void SetValue (string attributeName, T value)

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Der Name des Attributs. |
| value | object | Der Wert des Attributs. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_11}


```
 set_value_null(attribute_name) 
```

Setzt den Wert des Attributs auf <c>null</c>.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Der Name des Attributs. |

### Method: set_values(values) {#set_values_values_12}


```
 set_values(values) 
```

Setzt neue Werte für alle Attribute.<br/>            Erwägen Sie außerdem die Verwendung der Methode [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/), um das Setzen von Werten in einem Aufruf zu vereinfachen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Werte | object | Das Array neuer Werte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die Anzahl der gesetzten Attributwerte. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_13}


```
 unset_value(attribute_name) 
```

Entfernt den Attributwert aus diesem Feature.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Name des Attributs. |

