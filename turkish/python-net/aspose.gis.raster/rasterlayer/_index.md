---
title: "RasterLayer Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| band_count | int | r | Raster katmanındaki bant sayısını alır. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Raster sınırlarını alır. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Rasterin hücre veya piksel boyutunu alır. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Bu katmanı başlatan [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) öğesini alır. |
| yükseklik | int | r | Rasterin yüksekliğini piksel cinsinden alır. Ayrıca satır sayısı olarak da bilinir. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Rasterin arka planını veya 'veri yok' değerlerini temsil eden değerleri alır. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Rasterin bir uzamsal referans sistemini alır.<br/>            Bilinmiyorsa <see langword="null" /> olabilir. |
| upper_left_x | double | r | Rasterin sol üst köşesinin x koordinatını alır. |
| upper_left_y | double | r | Rasterin sol üst köşesinin y koordinatını alır. |
| genişlik | int | r | Rasterin genişliğini piksel cinsinden alır. Ayrıca sütun sayısı olarak da bilinir. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Bir şekil formu (ve bant maskesi) kullanarak raster katmanını kırpar. |
| [crop(masks)](#crop_masks_2) | Bir bant maskesi kullanarak raster katmanını kırpar). |
| [get_band(index)](#get_band_index_3) | Belirtilen indeksle bir band alır. |
| [get_extent()](#get_extent__4) | Bu katmanın uzamsal kapsamını hesaplar. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Belirtilen sütun ve satırı uzamsal koordinata dönüştürür. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Sayım, toplam, ortalama, minimum ve maksimumdan oluşan özet istatistikleri hesaplar. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Belirtilen hücredeki değerleri okur. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Belirtilen bloktaki değerleri 1 boyutlu dizi olarak okur. |
| [warp(options)](#warp_options_9) | Raster katmanını başka birine dönüştürür. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Bir şekil formu (ve bant maskesi) kullanarak raster katmanını kırpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri şekil formunu temsil eder. |
| maskeler | double | Kırpma katmanı için maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Kırpılmış raster katmanı. Kesişme bulunamazsa <see langword=\"null\" /> döndürür. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Bir bant maskesi kullanarak raster katmanını kırpar).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| maskeler | double | Kırpma katmanı için maske |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Kırpılmış raster katmanı. Kesişme bulunamazsa <see langword=\"null\" /> döndürür. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Belirtilen indeksle bir band alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | int | Bant numaraları 0'dan başlar ve bant belirtilmezse 0 varsayılır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Bir raster bandı hakkında temel meta verileri döndürür. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Bu katmanın uzamsal kapsamını hesaplar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Bu katmanın uzamsal kapsamı. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Belirtilen sütun ve satırı uzamsal koordinata dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cell_x | int | Sütun (x-koordinatı) değeri. Numaralandırma 0'dan başlar. |
| cell_y | int | Satır (y-koordinatı) değeri. Numaralandırma 0'dan başlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Bir sütun ve satır verildiğinde sol üst köşenin x-koordinatını döndürür. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Sayım, toplam, ortalama, minimum ve maksimumdan oluşan özet istatistikleri hesaplar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| band_index | int | Bandın indeksi. Numaralandırma 0'dan başlar. |
| exclude_nodata_value | bool | ‘nodata’ değerlerini hariç tutmaya izin verir. 'excludeNodataValue' false olarak ayarlanırsa, tüm pikseller dikkate alınır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | Özet istatistikler. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Belirtilen hücredeki değerleri okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| cell_x | int | Sütun (x-koordinatı) değeri. Numaralandırma 0'dan başlar. |
| cell_y | int | Satır (y-koordinatı) değeri. Numaralandırma 0'dan başlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | Raster değerleri. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Belirtilen bloktaki değerleri 1 boyutlu dizi olarak okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Dökümün okunduğu raster hücre bloğu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | Değerlerin dökümü. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Raster katmanını başka birine dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Yeniden projeksiyon prosedürü için seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Bükülmüş raster katmanı. |


