---
title: "KmlGroundOverlayInfo klass"
type: docs
weight: 20
url: /sv/python-net/aspose.gis.formats.kml.specificfields/kmlgroundoverlayinfo/
---

**Summary:** Specifies object from Kml 'GroundOverlay' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlGroundOverlayInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Hämtar barnen. |
| draw_order | double | läs/skriv | DrawOrder för 'GroundOverlay'-noden. |
| icon | [IconInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/iconinfo) | r/w | IconPath för 'GroundOverlay'-noden. |
| lat_lon_box | [KmlLatLonBox](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllatlonbox) | r/w | Specificerar objekt från Kml 'LatLonAltBox'-noden. |
| namn | string | läs/skriv | Namn på Ground Overlay |
| namn_utan_prefix | string | r | Hämtar namnet utan prefix. |
| node_name | string | läs/skriv | Hämtar eller anger namnet. |
| node_value | string | läs/skriv | Hämtar eller anger värdet. |
| prefix | string | r | Hämtar prefixet. |
| visibility | bool | läs/skriv | Synlighet för Ground Overlay |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Lägger till barnet. |
| [as_bool()](#as_bool__2) | Returnerar värdet kastat till bool |
| [as_double()](#as_double__3) | Returnerar värdet kastat till double. |
| [as_int()](#as_int__4) | Returnerar värdet kastat till int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Hittar XML-noderna efter namn. |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Hämtar noden efter namn. Observera att den här metoden kommer att returnera den första hittade noden.<br/>            Det spelar ingen roll på vilken nivå den hittas |
| [get_node_content()](#get_node_content__7) | Hämtar innehållet i noden. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Hämtar alla noder med det angivna namnet. <br/>            Det spelar ingen roll på vilken nivå de hittas |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Lägger till barnet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | Barnet. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Returnerar värdet kastat till bool

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Det booleska värdet för noden |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Returnerar värdet kastat till double.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Det double‑värdet för noden |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Returnerar värdet kastat till int.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det int‑värdet för noden |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

Hittar XML-noderna efter namn.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnet på noden |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Array av XML-noder efter namn. |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Hämtar noden efter namn. Observera att den här metoden kommer att returnera den första hittade noden.<br/>            Det spelar ingen roll på vilken nivå den hittas

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnet på den nod du vill hitta. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Den hittade noden med NodeLink‑API |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Hämtar innehållet i noden.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Innehållet i noden |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Hämtar alla noder med det angivna namnet. <br/>            Det spelar ingen roll på vilken nivå de hittas

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Arrayen av hittade noder. |


