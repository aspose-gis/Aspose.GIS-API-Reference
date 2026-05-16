---
title: "WebTile क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| cell_x | इंट | r | टाइल की X-स्तंभ। |
| cell_y | इंट | r | टाइल की Y-पंक्ति। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [as_binary()](#as_binary__1) | छवि बाइट अनुक्रम लौटाता है। |
| [as_path()](#as_path__2) | टाइल की सामग्री को URL या फ़ाइल के पथ के रूप में प्रस्तुत करता है। |
| [as_raster()](#as_raster__3) | टाइल सामग्री को एक रास्टर लेयर के रूप में प्रस्तुत करता है। |
| [get_extent()](#get_extent__4) | इस लेयर का स्थानिक विस्तार प्रस्तुत करता है। |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

छवि बाइट अनुक्रम लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | बाइट अनुक्रम |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

टाइल की सामग्री को URL या फ़ाइल के पथ के रूप में प्रस्तुत करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | फ़ाइल का URL या पथ |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

टाइल सामग्री को एक रास्टर लेयर के रूप में प्रस्तुत करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | रास्टर। |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

इस लेयर का स्थानिक विस्तार प्रस्तुत करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | इस लेयर का स्थानिक विस्तार। |


