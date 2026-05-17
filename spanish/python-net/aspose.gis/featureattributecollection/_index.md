---
title: "Clase FeatureAttributeCollection"
type: docs
weight: 850
url: /es/python-net/aspose.gis/featureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttributeCollection

**Inheritance:** BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| count | int | r | Obtiene el número de atributos en un [Feature](/psd/python-net/aspose.gis/feature/). |
| is_locked | bool | r | Obtiene un valor que indica si esta colección de atributos está bloqueada. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Agrega un atributo a la colección. |
| [contains(name)](#contains_name_2) | Determina si la colección de atributos contiene un atributo con el nombre especificado. |
| [index_of(name)](#index_of_name_3) | Busca el atributo y devuelve su índice basado en cero. |
| lock() | Bloquea esta colección de atributos para evitar modificaciones posteriores. |
| [remove(index)](#remove_index_4) | Elimina el atributo de la colección. |
| [remove(name)](#remove_name_5) | Elimina el atributo de la colección. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Agrega un atributo a la colección.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | El atributo a agregar. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Determina si la colección de atributos contiene un atributo con el nombre especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del atributo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword="true" /> si la colección de atributos contiene un atributo con el nombre especificado; de lo contrario, <see langword="false" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Busca el atributo y devuelve su índice basado en cero.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del atributo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El índice basado en cero del atributo dentro de la colección, si se encuentra; de lo contrario, –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Elimina el atributo de la colección.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Índice del atributo. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Elimina el atributo de la colección.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del atributo. |

