---
title: "فئة WebTile"
type: docs
weight: 10
url: /ar/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| cell_x | int | r | عمود X للقطعة. |
| cell_y | int | r | صف Y للقطعة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [as_binary()](#as_binary__1) | يرجع تسلسل بايتات الصورة |
| [as_path()](#as_path__2) | يعرض محتوى القطعة كعنوان URL أو مسار إلى ملف. |
| [as_raster()](#as_raster__3) | يعرض محتوى البلاطة كطبقة Raster. |
| [get_extent()](#get_extent__4) | يعرض الامتداد المكاني لهذه الطبقة. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

يرجع تسلسل بايتات الصورة

**Returns**

| نوع | الوصف |
| :- | :- |
| byte | تسلسل بايت |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

يعرض محتوى القطعة كعنوان URL أو مسار إلى ملف.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | Url أو مسار إلى ملف |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

يعرض محتوى البلاطة كطبقة Raster.

**Returns**

| نوع | الوصف |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | الـ Raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

يعرض الامتداد المكاني لهذه الطبقة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | نطاق مكاني لهذه الطبقة. |


