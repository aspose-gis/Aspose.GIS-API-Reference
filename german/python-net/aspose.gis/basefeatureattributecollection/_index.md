---
title: "BaseFeatureAttributeCollection Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| count | int | r | Gibt die Anzahl der Attribute in einem [Feature](/psd/python-net/aspose.gis/feature/) zurück. |
| is_locked | bool | r | Gibt einen Wert zurück, der angibt, ob diese Attributsammlung gesperrt ist. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Fügt ein Attribut zur Sammlung hinzu. |
| [contains(name)](#contains_name_2) | Bestimmt, ob die Attributsammlung ein Attribut mit dem angegebenen Namen enthält. |
| [index_of(name)](#index_of_name_3) | Durchsucht das Attribut und gibt dessen nullbasierten Index zurück. |
| lock() | Sperrt diese Attributsammlung, um weitere Änderungen zu verhindern. |
| [remove(index)](#remove_index_4) | Entfernt das Attribut aus der Sammlung. |
| [remove(name)](#remove_name_5) | Entfernt das Attribut aus der Sammlung. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Fügt ein Attribut zur Sammlung hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | Das hinzuzufügende Attribut. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Bestimmt, ob die Attributsammlung ein Attribut mit dem angegebenen Namen enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Attributs. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword=\"true\" /> wenn die Attributsammlung ein Attribut mit dem angegebenen Namen enthält; andernfalls <see langword=\"false\" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Durchsucht das Attribut und gibt dessen nullbasierten Index zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Attributs. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der nullbasierte Index des Attributs innerhalb der Sammlung, falls gefunden; andernfalls –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Entfernt das Attribut aus der Sammlung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Index des Attributs. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Entfernt das Attribut aus der Sammlung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Attributs. |

