---
title: "XyzTiles क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | एक उदाहरण बनाएं [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | निर्दिष्ट टाइल को लोड करता है। |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | निर्दिष्ट टाइल को लोड करता है। |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | स्पेशियल बाउंडिंग बॉक्स और ज़ूम लेवल द्वारा टाइल्स लोड करता है। |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | स्पेशियल बाउंडिंग बॉक्स और ज़ूम लेवल द्वारा टाइल्स लोड करता है। |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

एक उदाहरण बनाएं [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | वेब विकल्पों को शामिल करने वाला कनेक्शन। |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

निर्दिष्ट टाइल को लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| zoom | इंट | टाइल्स लोड करने के लिए ज़ूम लेवल। सबसे उच्च ज़ूम लेवल 0 है। अधिकांश टाइल प्रदाताओं के पास लगभग 22 अधिकतम ज़ूम लेवल होते हैं। |
| x | इंट | टाइल का x-स्तंभ। |
| y | इंट | टाइल की y-पंक्ति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | वेब टाइल। |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

निर्दिष्ट टाइल को लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| zoom | इंट | टाइल्स लोड करने के लिए ज़ूम लेवल। सबसे उच्च ज़ूम लेवल 0 है। अधिकांश टाइल प्रदाताओं के पास लगभग 22 अधिकतम ज़ूम लेवल होते हैं। |
| x | इंट | टाइल का x-स्तंभ। |
| y | इंट | टाइल की y-पंक्ति। |
| tile_size | इंट | टाइल्स का आकार, डिफ़ॉल्ट रूप से 256 है (यह टाइल आकार के लिए मानक है)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | वेब टाइल। |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

स्पेशियल बाउंडिंग बॉक्स और ज़ूम लेवल द्वारा टाइल्स लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| zoom | इंट | टाइल्स लोड करने के लिए ज़ूम लेवल। सबसे उच्च ज़ूम लेवल 0 है। अधिकांश टाइल प्रदाताओं के पास लगभग 22 अधिकतम ज़ूम लेवल होते हैं। |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | टाइल्स लोड करने के लिए बाउंडिंग बॉक्स। यदि नहीं दिया गया तो Wgs84 स्पेशियल रेफ़रेंस उपयोग किया जाएगा। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | वेब टाइल्स। |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

स्पेशियल बाउंडिंग बॉक्स और ज़ूम लेवल द्वारा टाइल्स लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| zoom | इंट | टाइल्स लोड करने के लिए ज़ूम लेवल। सबसे उच्च ज़ूम लेवल 0 है। अधिकांश टाइल प्रदाताओं के पास लगभग 22 अधिकतम ज़ूम लेवल होते हैं। |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | टाइल्स लोड करने के लिए बाउंडिंग बॉक्स। यदि नहीं दिया गया तो Wgs84 स्पेशियल रेफ़रेंस उपयोग किया जाएगा। |
| tile_size | इंट | टाइल्स का आकार, डिफ़ॉल्ट रूप से 256 है (यह टाइल आकार के लिए मानक है)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | वेब टाइल्स। |


