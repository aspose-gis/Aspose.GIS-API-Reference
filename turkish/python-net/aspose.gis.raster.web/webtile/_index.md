---
title: "WebTile Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_x | int | r | Bir karonun X-Sütunu. |
| cell_y | int | r | Bir karonun Y-Satırı. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | Görüntünün bayt dizisini döndürür |
| [as_path()](#as_path__2) | Karo içeriğini bir URL olarak ya da bir dosya yolu şeklinde sunar. |
| [as_raster()](#as_raster__3) | Döşeme içeriğini Raster katmanı olarak sunar. |
| [get_extent()](#get_extent__4) | Bu katmanın uzamsal kapsamını sunar. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Görüntünün bayt dizisini döndürür

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Bayt dizisi |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

Karo içeriğini bir URL olarak ya da bir dosya yolu şeklinde sunar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Dosyanın URL'si veya yolu |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

Döşeme içeriğini Raster katmanı olarak sunar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Bu katmanın uzamsal kapsamını sunar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Bu katmanın uzamsal kapsamı. |


