---
title: "FeatureAttributeCollection klass"
type: docs
weight: 850
url: /sv/python-net/aspose.gis/featureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttributeCollection

**Inheritance:** BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| count | int | r | Hämtar antalet attribut i en [Feature](/psd/python-net/aspose.gis/feature/). |
| is_locked | bool | r | Hämtar ett värde som indikerar om denna attributsamling är låst. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Lägger till ett attribut i samlingen. |
| [contains(name)](#contains_name_2) | Avgör om attributsamlingen innehåller ett attribut med det angivna namnet. |
| [index_of(name)](#index_of_name_3) | Söker efter attributet och returnerar dess nollbaserade index. |
| lock() | Låser denna attributsamling för att förhindra ytterligare ändringar. |
| [remove(index)](#remove_index_4) | Tar bort attributet från samlingen. |
| [remove(name)](#remove_name_5) | Tar bort attributet från samlingen. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Lägger till ett attribut i samlingen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | Attributet att lägga till. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Avgör om attributsamlingen innehåller ett attribut med det angivna namnet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnet på attributet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword="true" /> om attributsamlingen innehåller ett attribut med det angivna namnet; annars <see langword="false" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Söker efter attributet och returnerar dess nollbaserade index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnet på attributet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det nollbaserade indexet för attributet i samlingen, om det hittas; annars –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Tar bort attributet från samlingen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Index för attributet. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Tar bort attributet från samlingen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnet på attributet. |

