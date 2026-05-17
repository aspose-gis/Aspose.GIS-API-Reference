---
title: "WarpOptions Sınıfı"
type: docs
weight: 100
url: /tr/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | WarpOptions sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Raster hücresinin yeni yüksekliğini (hedef coğrafi referans birimlerinde) belirtir.<br/>            Değer 0 olarak ayarlanırsa, [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) otomatik olarak hesaplanır. Varsayılan değer "0" dır. |
| cell_width | double | r/w | Raster hücresinin yeni genişliğini (hedef coğrafi referans birimlerinde) belirtir.<br/>            Değer 0 olarak ayarlanırsa, [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) otomatik olarak hesaplanır. Varsayılan değer "0" dır. |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Kaynak mekansal referans eksikse, bir değer belirtir. |
| yükseklik | int | r/w | Çıktı raster yüksekliğini piksel ve sütun cinsinden belirtir.<br/>            Değer 0 olarak ayarlanırsa, yükseklik otomatik olarak hesaplanır. Varsayılan değer "0" dır. |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Warp yapılacak raster katmanının sınırlarını belirtir.<br/>            <see langword="null" /> olarak ayarlanırsa, uzama rasterdaki tüm hücreleri kapsayacak şekilde warp sırasında hesaplanır. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Hedef mekansal referansı belirtir.<br/>            <see langword="null" /> olarak ayarlanırsa, varsayılan veya kaynak mekansal referans kullanılır. |
| genişlik | int | r/w | Çıktı raster genişliğini piksel ve sütun cinsinden belirtir.<br/>            Değer 0 olarak ayarlanırsa, genişlik otomatik olarak hesaplanır. Varsayılan değer "0" dır. |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

WarpOptions sınıfının yeni bir örneğini başlatır

