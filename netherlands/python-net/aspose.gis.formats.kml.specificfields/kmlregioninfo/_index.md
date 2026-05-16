---
title: "KmlRegionInfo Klasse"
type: docs
weight: 70
url: /nl/python-net/aspose.gis.formats.kml.specificfields/kmlregioninfo/
---

**Summary:** Specifies object from Kml 'Region' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlRegionInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Haalt de kinderen op. |
| id | string | r/w | Id van 'Region' knooppunt. |
| lat_lon_alt_box | [KmlLatLonAltBox](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllatlonaltbox) | r/w | Specificeert object van Kml 'LatLonAltBox' knooppunt. |
| lod | [KmlLodSettings](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllodsettings) | r/w | Specificeert object van Kml 'Lod' knooppunt. |
| name_without_prefix | string | r | Haalt de naam op zonder prefix. |
| node_name | string | r/w | Haalt de naam op of stelt deze in. |
| node_value | string | r/w | Haalt de waarde op of stelt deze in. |
| prefix | string | r | Haalt de prefix op. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Voegt het kind toe. |
| [as_bool()](#as_bool__2) | Retourneert de waarde omgezet naar bool |
| [as_double()](#as_double__3) | Retourneert de waarde omgezet naar double. |
| [as_int()](#as_int__4) | Retourneert de waarde gecast naar een int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Zoekt de XML-nodes op basis van de naam. |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Haalt het knooppunt op op naam. Let op, deze methode retourneert het eerst gevonden Node.<br/>            Het maakt niet uit op welk niveau het wordt gevonden |
| [get_node_content()](#get_node_content__7) | Haalt de inhoud van het knooppunt op. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Haalt alle knooppunten op met de opgegeven naam. <br/>            Het maakt niet uit op welk niveau ze worden gevonden |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Voegt het kind toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | Het kind. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Retourneert de waarde omgezet naar bool

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | De bool-waarde van het knooppunt |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Retourneert de waarde omgezet naar double.

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | De double-waarde van het knooppunt |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Retourneert de waarde gecast naar een int.

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De int-waarde van het knooppunt |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

Zoekt de XML-nodes op basis van de naam.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | De naam van het knooppunt |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Array van XML-nodes op naam. |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Haalt het knooppunt op op naam. Let op, deze methode retourneert het eerst gevonden Node.<br/>            Het maakt niet uit op welk niveau het wordt gevonden

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | De naam van het knooppunt dat u wilt vinden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Het gevonden knooppunt met de NodeLink API |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Haalt de inhoud van het knooppunt op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | De inhoud van het knooppunt |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Haalt alle knooppunten op met de opgegeven naam. <br/>            Het maakt niet uit op welk niveau ze worden gevonden

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| namen | string | De namen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | De array van gevonden knooppunten. |


