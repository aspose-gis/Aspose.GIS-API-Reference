---
title: "BaseFeatureAttributeCollection-klasse"
type: docs
weight: 90
url: /nl/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| count | int | r | Haalt het aantal attributen op in een [Feature](/psd/python-net/aspose.gis/feature/). |
| is_locked | bool | r | Haalt een waarde op die aangeeft of deze attributencollectie vergrendeld is. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Voegt een attribuut toe aan de collectie. |
| [contains(name)](#contains_name_2) | Bepaalt of de attributencollectie een attribuut met de opgegeven naam bevat. |
| [index_of(name)](#index_of_name_3) | Zoekt naar het attribuut en retourneert de nulgebaseerde index. |
| lock() | Vergrendelt deze attributencollectie om verdere wijzigingen te voorkomen. |
| [remove(index)](#remove_index_4) | Verwijdert het attribuut uit de collectie. |
| [remove(name)](#remove_name_5) | Verwijdert het attribuut uit de collectie. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Voegt een attribuut toe aan de collectie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | Het toe te voegen attribuut. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Bepaalt of de attributencollectie een attribuut met de opgegeven naam bevat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van het attribuut. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als de attributencollectie een attribuut met de opgegeven naam bevat; anders, <see langword="false" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Zoekt naar het attribuut en retourneert de nulgebaseerde index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van het attribuut. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De nulgebaseerde index van het attribuut binnen de collectie, indien gevonden; anders –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Verwijdert het attribuut uit de collectie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Index van het attribuut. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Verwijdert het attribuut uit de collectie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van het attribuut. |

