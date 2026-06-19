---
title: "فئة RasterLayer"
type: docs
weight: 70
url: /ar/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| band_count | int | r | يحصل على عدد القنوات في طبقة الراستر. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | يحصل على حدود الراستر. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | يحصل على حجم الخلية أو البكسل للراستر. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | يحصل على [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) الذي أنشأ هذه الطبقة. |
| الارتفاع | int | r | يحصل على ارتفاع الراستر بالبكسل. كما يُعرف أيضًا بعدد الصفوف. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | يحصل على القيم التي تمثل الخلفية أو 'لا بيانات' للراستر. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | يحصل على نظام الإحداثيات المكانية للراستر.<br/>            يمكن أن يكون <see langword="null" /> إذا كان غير معروف. |
| upper_left_x | double | r | يحصل على إحداثي x للزاوية العليا اليسرى للراستر. |
| upper_left_y | double | r | يحصل على إحداثي y للزاوية العليا اليسرى للراستر. |
| width | int | r | يحصل على عرض الراستر بالبكسل. كما يُعرف أيضًا بعدد الأعمدة. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | يقص طبقة الراستر باستخدام شكل (وقناع القنوات). |
| [crop(masks)](#crop_masks_2) | يقص طبقة الراستر باستخدام قناع القنوات). |
| [get_band(index)](#get_band_index_3) | يحصل على قناة وفق الفهرس المحدد. |
| [get_extent()](#get_extent__4) | يحسب الامتداد المكاني لهذه الطبقة. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | يحول العمود والصف المحددين إلى الإحداثيات المكانية. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | احسب الإحصاءات الملخصة التي تتضمن العدد، المجموع، المتوسط، الحد الأدنى، الحد الأقصى. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | يقرأ القيم في الخلية المحددة. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | يقرأ القيم في الكتلة المحددة كمصفوفة ذات بعد واحد. |
| [warp(options)](#warp_options_9) | يشوه طبقة الراستر إلى أخرى. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

يقص طبقة الراستر باستخدام شكل (وقناع القنوات).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | الجيومتري تمثل الشكل. |
| الأقنعة | double | قناع لطبقة القص |

**Returns**

| نوع | وصف |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | طبقة الراستر المقصوصة. إذا لم يتم العثور على تقاطعات تُعيد <see langword=\"null\" />. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

يقص طبقة الراستر باستخدام قناع القنوات).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الأقنعة | double | قناع لطبقة القص |

**Returns**

| نوع | وصف |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | طبقة الراستر المقصوصة. إذا لم يتم العثور على تقاطعات تُعيد <see langword=\"null\" />. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

يحصل على قناة وفق الفهرس المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | تبدأ أرقام النطاقات من 0 ويُفترض أن النطاق هو 0 إذا لم يُحدد. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | يعيد بيانات تعريف أساسية حول نطاق الراستر. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

يحسب الامتداد المكاني لهذه الطبقة.

**Returns**

| نوع | وصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | نطاق مكاني لهذه الطبقة. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

يحول العمود والصف المحددين إلى الإحداثيات المكانية.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| cell_x | int | القيمة للعمود (الإحداثي س). يبدأ الترقيم من 0. |
| cell_y | int | القيمة للصف (الإحداثي ص). يبدأ الترقيم من 0. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | يعيد إحداثي س للزاوية العليا اليسرى بناءً على العمود والصف. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

احسب الإحصاءات الملخصة التي تتضمن العدد، المجموع، المتوسط، الحد الأدنى، الحد الأقصى.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| band_index | int | فهرس النطاق. يبدأ الترقيم من 0. |
| exclude_nodata_value | bool | يسمح باستبعاد قيم 'nodata'. إذا تم تعيين 'excludeNodataValue' إلى false، فسيتم اعتبار جميع البكسلات. |

**Returns**

| نوع | وصف |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | إحصائيات الملخص. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

يقرأ القيم في الخلية المحددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| cell_x | int | القيمة للعمود (الإحداثي س). يبدأ الترقيم من 0. |
| cell_y | int | القيمة للصف (الإحداثي ص). يبدأ الترقيم من 0. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | قيم الراستر. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

يقرأ القيم في الكتلة المحددة كمصفوفة ذات بعد واحد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | كتلة من خلايا الراستر حيث يتم قراءة التفريغ. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | تفريغ القيم. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

يشوه طبقة الراستر إلى أخرى.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | خيارات إجراء إعادة الإسقاط. |

**Returns**

| نوع | وصف |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | طبقة الراستر المشوهة. |


