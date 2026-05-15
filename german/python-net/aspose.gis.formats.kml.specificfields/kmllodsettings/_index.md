---
title: "KmlLodSettings Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.gis.formats.kml.specificfields/kmllodsettings/
---

**Summary:** Specifies object from Kml 'Lod' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlLodSettings

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Liefert die Kind‑Elemente. |
| max_fade_extent | int | r/w | MaxFadeExtent des 'Lod'-Knotens. |
| max_lod_pixels | int | r/w | MaxLodPixels des 'Lod'-Knotens. |
| min_fade_extent | int | r/w | MinFadeExtent des 'Lod'-Knotens. |
| min_lod_pixels | int | r/w | MinLodPixels des 'Lod'-Knotens. |
| name_without_prefix | string | r | Gibt den Namen ohne Präfix zurück. |
| node_name | string | r/w | Liefert oder setzt den Namen. |
| node_value | string | r/w | Liefert oder setzt den Wert. |
| Präfix | string | r | Gibt das Präfix zurück. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Fügt das Kind hinzu. |
| [as_bool()](#as_bool__2) | Gibt den Wert als bool zurück |
| [as_double()](#as_double__3) | Gibt den Wert als double zurück |
| [as_int()](#as_int__4) | Gibt den Wert als int zurück. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Findet die XML-Knoten nach dem Namen |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Liest den Knoten nach Namen aus. Bitte beachten Sie, dass diese Methode den zuerst gefundenen Node zurückgibt.<br/>            Es spielt keine Rolle, auf welcher Ebene er gefunden wird. |
| [get_node_content()](#get_node_content__7) | Liest den Inhalt des Knotens. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Liest alle Knoten mit dem angegebenen Namen aus. <br/>            Es spielt keine Rolle, auf welcher Ebene sie gefunden werden. |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Fügt das Kind hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | Das Kind. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Gibt den Wert als bool zurück

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | Der boolesche Wert des Knotens |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Gibt den Wert als double zurück

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Der double-Wert des Knotens |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Gibt den Wert als int zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der int-Wert des Knotens |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

Findet die XML-Knoten nach dem Namen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Der Name des Knotens |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Array von XML-Knoten nach Name |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Liest den Knoten nach Namen aus. Bitte beachten Sie, dass diese Methode den zuerst gefundenen Node zurückgibt.<br/>            Es spielt keine Rolle, auf welcher Ebene er gefunden wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Der Name des Knotens, den Sie finden möchten. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Der gefundene Knoten mit der NodeLink-API |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Liest den Inhalt des Knotens.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Der Inhalt des Knotens |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Liest alle Knoten mit dem angegebenen Namen aus. <br/>            Es spielt keine Rolle, auf welcher Ebene sie gefunden werden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Namen | string | Die Namen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Das Array gefundener Knoten. |


