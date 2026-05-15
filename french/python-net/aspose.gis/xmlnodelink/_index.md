---
title: "XmlNodeLink Classe"
type: docs
weight: 4340
url: /fr/python-net/aspose.gis/xmlnodelink/
---

**Summary:** XML Node-Based links to parts of sources

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.XmlNodeLink

**Inheritance:** NodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Obtient les enfants. |
| name_without_prefix | string | r | Obtient le nom sans préfixe. |
| node_name | string | r/w | Obtient ou définit le nom. |
| node_value | string | r/w | Obtient ou définit la valeur. |
| préfixe | string | r | Obtient le préfixe. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Ajoute l'enfant. |
| [as_bool()](#as_bool__2) | Renvoie la valeur convertie en booléen |
| [as_double()](#as_double__3) | Renvoie la valeur convertie en double. |
| [as_int()](#as_int__4) | Renvoie la valeur convertie en int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Trouve les nœuds XML par le nom |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Obtient le nœud par son nom. Veuillez noter que cette méthode renverra le premier nœud trouvé.<br/>            Peu importe le niveau auquel il sera trouvé |
| [get_node_content()](#get_node_content__7) | Obtient le contenu du nœud. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Obtient tous les nœuds avec le nom spécifié. <br/>            Peu importe le niveau auquel ils seront trouvés |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Ajoute l'enfant.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | L'enfant. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Renvoie la valeur convertie en booléen

**Returns**

| Type | Description |
| :- | :- |
| bool | La valeur booléenne du nœud |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Renvoie la valeur convertie en double.

**Returns**

| Type | Description |
| :- | :- |
| double | La valeur double du nœud |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Renvoie la valeur convertie en int.

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur int du nœud |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

Trouve les nœuds XML par le nom

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Le nom du nœud |

**Returns**

| Type | Description |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Tableau de nœuds XML par nom |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Obtient le nœud par son nom. Veuillez noter que cette méthode renverra le premier nœud trouvé.<br/>            Peu importe le niveau auquel il sera trouvé

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Le nom du nœud que vous souhaitez trouver. |

**Returns**

| Type | Description |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Le nœud trouvé avec l'API NodeLink |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Obtient le contenu du nœud.

**Returns**

| Type | Description |
| :- | :- |
| string | Le contenu du nœud |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Obtient tous les nœuds avec le nom spécifié. <br/>            Peu importe le niveau auquel ils seront trouvés

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| noms | string | Les noms. |

**Returns**

| Type | Description |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Le tableau des nœuds trouvés. |


