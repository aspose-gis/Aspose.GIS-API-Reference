---
title: "LinkInfo Classe"
type: docs
weight: 80
url: /it/python-net/aspose.gis.formats.kml.specificfields/linkinfo/
---

**Summary:** The LinkInfo node of KML format

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.LinkInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Ottiene i figli. |
| href | string | r/w | Ottiene o imposta l'href. |
| name_without_prefix | string | r | Restituisce il nome senza prefisso. |
| node_name | string | r/w | Ottiene o imposta il nome. |
| node_value | string | r/w | Ottiene o imposta il valore. |
| prefisso | string | r | Restituisce il prefisso. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Aggiunge il figlio. |
| [as_bool()](#as_bool__2) | Restituisce il valore convertito in bool |
| [as_double()](#as_double__3) | Restituisce il valore convertito in double. |
| [as_int()](#as_int__4) | Restituisce il valore convertito in int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Trova i nodi XML per nome |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Ottiene il nodo per nome. Si prega di notare, questo metodo restituirà il primo Nodo trovato.<br/>            Non importa a quale livello venga trovato |
| [get_node_content()](#get_node_content__7) | Ottiene il contenuto del nodo. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Ottiene tutti i nodi con il nome specificato. <br/>            Non importa a quale livello venga trovato |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Aggiunge il figlio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | Il figlio. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Restituisce il valore convertito in bool

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Il valore booleano del nodo |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Restituisce il valore convertito in double.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | Il valore double del nodo |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Restituisce il valore convertito in int.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore int del nodo |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

Trova i nodi XML per nome

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Il nome del nodo |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Array di nodi XML per nome |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Ottiene il nodo per nome. Si prega di notare, questo metodo restituirà il primo Nodo trovato.<br/>            Non importa a quale livello venga trovato

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Il nome del nodo che vuoi trovare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Il nodo trovato con l'API NodeLink |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Ottiene il contenuto del nodo.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Il contenuto del nodo |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Ottiene tutti i nodi con il nome specificato. <br/>            Non importa a quale livello venga trovato

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nomi | string | I nomi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | L'array dei nodi trovati. |


