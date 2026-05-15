---
title: "XyzTiles فئة"
type: docs
weight: 20
url: /ar/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | أنشئ نسخة من [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | يحمّل البلاط المحدد. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | يحمّل البلاط المحدد. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | يحمّل البلاط وفقًا لمربع الحدود المكاني ومستوى التكبير. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | يحمّل البلاط وفقًا لمربع الحدود المكاني ومستوى التكبير. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

أنشئ نسخة من [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | اتصال يحتوي على خيارات الويب. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

يحمّل البلاط المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| zoom | int | مستوى التكبير لتحميل البلاط. أعلى مستوى تكبير هو 0. معظم مزودي البلاط لديهم حوالي 22 مستوى تكبير كحد أقصى. |
| x | int | عمود x للبلاط. |
| y | int | صف y للبلاط. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | بلاط الويب. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

يحمّل البلاط المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| zoom | int | مستوى التكبير لتحميل البلاط. أعلى مستوى تكبير هو 0. معظم مزودي البلاط لديهم حوالي 22 مستوى تكبير كحد أقصى. |
| x | int | عمود x للبلاط. |
| y | int | صف y للبلاط. |
| tile_size | int | حجم البلاط، افتراضيًا هو 256 (وهو المعيار لحجم البلاط). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | بلاط الويب. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

يحمّل البلاط وفقًا لمربع الحدود المكاني ومستوى التكبير.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| zoom | int | مستوى التكبير لتحميل البلاط. أعلى مستوى تكبير هو 0. معظم مزودي البلاط لديهم حوالي 22 مستوى تكبير كحد أقصى. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | مربع الحدود لتحميل البلاط. سيتم استخدام مرجع الفضاء Wgs84 إذا كان مفقودًا. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | بلاطات الويب. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

يحمّل البلاط وفقًا لمربع الحدود المكاني ومستوى التكبير.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| zoom | int | مستوى التكبير لتحميل البلاط. أعلى مستوى تكبير هو 0. معظم مزودي البلاط لديهم حوالي 22 مستوى تكبير كحد أقصى. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | مربع الحدود لتحميل البلاط. سيتم استخدام مرجع الفضاء Wgs84 إذا كان مفقودًا. |
| tile_size | int | حجم البلاط، افتراضيًا هو 256 (وهو المعيار لحجم البلاط). |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | بلاطات الويب. |


