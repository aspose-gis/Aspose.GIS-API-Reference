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
| **Name** | **Description** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | إنشاء مثال على [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | يقوم بتحميل البلاطة المحددة. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | يقوم بتحميل البلاطة المحددة. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | يقوم بتحميل البلاط وفقاً لمربع الحد المكاني ومستوى التكبير. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | يقوم بتحميل البلاط وفقاً لمربع الحد المكاني ومستوى التكبير. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

إنشاء مثال على [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | اتصال يحتوي على خيارات الويب. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

يقوم بتحميل البلاطة المحددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| zoom | int | مستوى التكبير لتحميل البلاط. أعلى مستوى تكبير هو 0. معظم مزودي البلاط لديهم حوالي 22 مستوى تكبير كحد أقصى. |
| x | int | عمود x للبلاطة. |
| y | int | صف y للبلاطة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | بلاطة الويب. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

يقوم بتحميل البلاطة المحددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| zoom | int | مستوى التكبير لتحميل البلاط. أعلى مستوى تكبير هو 0. معظم مزودي البلاط لديهم حوالي 22 مستوى تكبير كحد أقصى. |
| x | int | عمود x للبلاطة. |
| y | int | صف y للبلاطة. |
| tile_size | int | حجم البلاط، بشكل افتراضي هو 256 (وهو المعيار لحجم البلاط). |

**Returns**

| نوع | وصف |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | بلاطة الويب. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

يقوم بتحميل البلاط وفقاً لمربع الحد المكاني ومستوى التكبير.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| zoom | int | مستوى التكبير لتحميل البلاط. أعلى مستوى تكبير هو 0. معظم مزودي البلاط لديهم حوالي 22 مستوى تكبير كحد أقصى. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | مربع الحد لتحميل البلاط. سيتم استخدام المرجع المكاني Wgs84 إذا كان مفقوداً. |

**Returns**

| نوع | وصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | بلاط الويب. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

يقوم بتحميل البلاط وفقاً لمربع الحد المكاني ومستوى التكبير.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| zoom | int | مستوى التكبير لتحميل البلاط. أعلى مستوى تكبير هو 0. معظم مزودي البلاط لديهم حوالي 22 مستوى تكبير كحد أقصى. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | مربع الحد لتحميل البلاط. سيتم استخدام المرجع المكاني Wgs84 إذا كان مفقوداً. |
| tile_size | int | حجم البلاط، بشكل افتراضي هو 256 (وهو المعيار لحجم البلاط). |

**Returns**

| نوع | وصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | بلاط الويب. |


