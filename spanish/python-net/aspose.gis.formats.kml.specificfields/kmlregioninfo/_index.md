---
title: "Clase KmlRegionInfo"
type: docs
weight: 70
url: /es/python-net/aspose.gis.formats.kml.specificfields/kmlregioninfo/
---

**Summary:** Specifies object from Kml 'Region' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlRegionInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Obtiene los hijos. |
| id | string | r/w | Id del nodo 'Region'. |
| lat_lon_alt_box | [KmlLatLonAltBox](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllatlonaltbox) | r/w | Especifica el objeto del nodo Kml 'LatLonAltBox'. |
| lod | [KmlLodSettings](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllodsettings) | r/w | Especifica el objeto del nodo Kml 'Lod'. |
| name_without_prefix | string | r | Obtiene el nombre sin prefijo. |
| node_name | string | r/w | Obtiene o establece el nombre. |
| node_value | string | r/w | Obtiene o establece el valor. |
| prefijo | string | r | Obtiene el prefijo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Agrega el hijo. |
| [as_bool()](#as_bool__2) | Devuelve el valor convertido a bool |
| [as_double()](#as_double__3) | Devuelve el valor convertido a double. |
| [as_int()](#as_int__4) | Devuelve el valor convertido a int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Encuentra los nodos XML por el nombre |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Obtiene el nodo por nombre. Tenga en cuenta que este método devolverá el primer Nodo encontrado.<br/>            No importa en qué nivel se encuentre. |
| [get_node_content()](#get_node_content__7) | Obtiene el contenido del nodo. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Obtiene todos los nodos con el nombre especificado. <br/>            No importa en qué nivel se encuentren. |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Agrega el hijo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | El hijo. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Devuelve el valor convertido a bool

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | El valor booleano del nodo |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Devuelve el valor convertido a double.

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | El valor doble del nodo |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Devuelve el valor convertido a int.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor entero del nodo |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

Encuentra los nodos XML por el nombre

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | El nombre del nodo |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Arreglo de nodos XML por nombre |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Obtiene el nodo por nombre. Tenga en cuenta que este método devolverá el primer Nodo encontrado.<br/>            No importa en qué nivel se encuentre.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | El nombre del nodo que desea encontrar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | El nodo encontrado con la API NodeLink |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Obtiene el contenido del nodo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | El contenido del nodo |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Obtiene todos los nodos con el nombre especificado. <br/>            No importa en qué nivel se encuentren.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombres | string | Los nombres. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | La matriz de nodos encontrados. |


