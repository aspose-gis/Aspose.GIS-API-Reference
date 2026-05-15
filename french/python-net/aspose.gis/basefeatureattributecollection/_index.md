---
title: "Classe BaseFeatureAttributeCollection"
type: docs
weight: 90
url: /fr/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Obtient le nombre d'attributs dans un [Feature](/psd/python-net/aspose.gis/feature/). |
| is_locked | bool | r | Obtient une valeur indiquant si cette collection d'attributs est verrouillée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Ajoute un attribut à la collection. |
| [contains(name)](#contains_name_2) | Détermine si la collection d'attributs contient un attribut portant le nom spécifié. |
| [index_of(name)](#index_of_name_3) | Recherche l'attribut et renvoie son indice basé sur zéro. |
| lock() | Verrouille cette collection d'attributs pour empêcher d'autres modifications. |
| [remove(index)](#remove_index_4) | Supprime l'attribut de la collection. |
| [remove(name)](#remove_name_5) | Supprime l'attribut de la collection. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Ajoute un attribut à la collection.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | L'attribut à ajouter. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Détermine si la collection d'attributs contient un attribut portant le nom spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de l'attribut. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si la collection d'attributs contient un attribut avec le nom spécifié ; sinon, <see langword=\"false\" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Recherche l'attribut et renvoie son indice basé sur zéro.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de l'attribut. |

**Returns**

| Type | Description |
| :- | :- |
| int | L'indice basé sur zéro de l'attribut dans la collection, s'il est trouvé ; sinon, –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Supprime l'attribut de la collection.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Indice de l'attribut. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Supprime l'attribut de la collection.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom de l'attribut. |

