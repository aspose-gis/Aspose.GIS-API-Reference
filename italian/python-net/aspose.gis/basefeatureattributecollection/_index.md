---
title: "BaseFeatureAttributeCollection Classe"
type: docs
weight: 90
url: /it/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| count | int | r | Restituisce il numero di attributi in un [Feature](/psd/python-net/aspose.gis/feature/). |
| is_locked | bool | r | Restituisce un valore che indica se questa raccolta di attributi è bloccata. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Aggiunge un attributo alla raccolta. |
| [contains(name)](#contains_name_2) | Determina se la raccolta di attributi contiene un attributo con il nome specificato. |
| [index_of(name)](#index_of_name_3) | Cerca l'attributo e restituisce il suo indice a base zero. |
| lock() | Blocca questa raccolta di attributi per impedire ulteriori modifiche. |
| [remove(index)](#remove_index_4) | Rimuove l'attributo dalla raccolta. |
| [remove(name)](#remove_name_5) | Rimuove l'attributo dalla raccolta. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Aggiunge un attributo alla raccolta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | L'attributo da aggiungere. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Determina se la raccolta di attributi contiene un attributo con il nome specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome dell'attributo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se la raccolta di attributi contiene un attributo con il nome specificato; altrimenti, <see langword="false" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Cerca l'attributo e restituisce il suo indice a base zero.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome dell'attributo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'indice a base zero dell'attributo nella raccolta, se trovato; altrimenti, –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Rimuove l'attributo dalla raccolta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | Indice dell'attributo. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Rimuove l'attributo dalla raccolta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome dell'attributo. |

