---
title: "RasterLayer क्लास"
type: docs
weight: 70
url: /hi/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| band_count | इंट | r | रास्टर लेयर में बैंडों की संख्या प्राप्त करता है। |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | रास्टर की सीमाएँ प्राप्त करता है। |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | रास्टर के सेल या पिक्सेल आकार को प्राप्त करता है। |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | इस लेयर को इंस्टैंशिएट करने वाले [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) को प्राप्त करता है। |
| ऊँचाई | इंट | r | रास्टर की ऊँचाई पिक्सेल में प्राप्त करता है। इसे पंक्तियों की गिनती भी कहा जाता है। |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | रास्टर की पृष्ठभूमि या 'नो डेटा' को दर्शाने वाले मानों को प्राप्त करता है। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | रास्टर की स्पैशियल रेफ़रेंस सिस्टम प्राप्त करता है।<br/>            यदि अज्ञात हो तो <see langword="null" /> हो सकता है। |
| upper_left_x | double | r | रास्टर के ऊपरी बाएँ कोने का x-निर्देशांक प्राप्त करता है। |
| upper_left_y | double | r | रास्टर के ऊपरी बाएँ कोने का y-निर्देशांक प्राप्त करता है। |
| width | इंट | r | रास्टर की चौड़ाई पिक्सेल में प्राप्त करता है। इसे कॉलम की गिनती भी कहा जाता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | एक आकार रूप (और बैंड मास्क) का उपयोग करके रास्टर लेयर को क्रॉप करता है। |
| [crop(masks)](#crop_masks_2) | बैंड मास्क का उपयोग करके रास्टर लेयर को क्रॉप करता है। |
| [get_band(index)](#get_band_index_3) | निर्दिष्ट सूचकांक द्वारा एक बैंड प्राप्त करता है। |
| [get_extent()](#get_extent__4) | इस लेयर का स्पैशियल विस्तार गणना करता है। |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | निर्दिष्ट कॉलम और पंक्ति को स्पैशियल निर्देशांक में परिवर्तित करता है। |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | गणना करता है सारांश सांख्यिकी जिसमें गिनती, योग, औसत, न्यूनतम, अधिकतम शामिल हैं। |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | निर्दिष्ट सेल में मान पढ़ता है। |
| [get_values_dump(rect)](#get_values_dump_rect_8) | निर्दिष्ट ब्लॉक में मानों को 1-आयामी सरणी के रूप में पढ़ता है। |
| [warp(options)](#warp_options_9) | रास्टर लेयर को दूसरे में वर्प करता है। |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

एक आकार रूप (और बैंड मास्क) का उपयोग करके रास्टर लेयर को क्रॉप करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | ज्यामिति आकार रूप को दर्शाती है। |
| मास्क | double | क्रॉप लेयर के लिए मास्क |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | क्रॉप किया गया रास्टर लेयर। यदि कोई प्रतिच्छेद नहीं मिला तो <see langword="null" /> लौटाता है। |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

बैंड मास्क का उपयोग करके रास्टर लेयर को क्रॉप करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| मास्क | double | क्रॉप लेयर के लिए मास्क |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | क्रॉप किया गया रास्टर लेयर। यदि कोई प्रतिच्छेद नहीं मिला तो <see langword="null" /> लौटाता है। |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

निर्दिष्ट सूचकांक द्वारा एक बैंड प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | बैंड नंबर 0 से शुरू होते हैं और यदि निर्दिष्ट न किया गया हो तो बैंड को 0 माना जाता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | एक रास्टर बैंड के बारे में मूल मेटा डेटा लौटाता है। |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

इस लेयर का स्पैशियल विस्तार गणना करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | इस लेयर का स्थानिक विस्तार। |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

निर्दिष्ट कॉलम और पंक्ति को स्पैशियल निर्देशांक में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cell_x | इंट | कॉलम (x-निर्देशांक) के लिए मान। क्रमांक 0 से शुरू होता है। |
| cell_y | इंट | पंक्ति (y-निर्देशांक) के लिए मान। क्रमांक 0 से शुरू होता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | कॉलम और पंक्ति के आधार पर ऊपरी बाएँ कोने का x-निर्देशांक लौटाता है। |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

गणना करता है सारांश सांख्यिकी जिसमें गिनती, योग, औसत, न्यूनतम, अधिकतम शामिल हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| band_index | इंट | बैंड का सूचकांक। क्रमांक 0 से शुरू होता है। |
| exclude_nodata_value | bool | ‘nodata’ मानों को बाहर करने की अनुमति देता है। यदि ‘excludeNodataValue’ को false सेट किया गया है, तो सभी पिक्सेल को माना जाता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | सारांश सांख्यिकी। |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

निर्दिष्ट सेल में मान पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| cell_x | इंट | कॉलम (x-निर्देशांक) के लिए मान। क्रमांक 0 से शुरू होता है। |
| cell_y | इंट | पंक्ति (y-निर्देशांक) के लिए मान। क्रमांक 0 से शुरू होता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | रास्टर मान। |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

निर्दिष्ट ब्लॉक में मानों को 1-आयामी सरणी के रूप में पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | डम्प पढ़े जाने वाले रास्टर कोशिकाओं का ब्लॉक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | मानों का डम्प। |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

रास्टर लेयर को दूसरे में वर्प करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | रीप्रोजेक्शन प्रक्रिया के विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | वॉर्प रास्टर लेयर। |


