---
title: "Kelas WarpOptions"
type: docs
weight: 100
url: /id/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | Menginisialisasi sebuah instance baru dari kelas WarpOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Menentukan tinggi baru sel raster (dalam unit georeferensi target).<br/>            Jika nilai diatur ke 0, [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) akan dihitung secara otomatis. Nilai default adalah "0". |
| cell_width | double | r/w | Menentukan lebar baru sel raster (dalam unit georeferensi target).<br/>            Jika nilai diatur ke 0, [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) akan dihitung secara otomatis. Nilai default adalah "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Menentukan nilai untuk referensi spasial sumber jika tidak ada. |
| tinggi | int | r/w | Menentukan tinggi raster output dalam piksel dan kolom.<br/>            Jika nilai diatur ke 0, tinggi akan dihitung secara otomatis. Nilai default adalah "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Menentukan batas lapisan raster untuk diwarp.<br/>            Jika diatur ke <see langword="null" />, batas akan dihitung selama proses warping untuk mencakup semua sel dari raster. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Menentukan referensi spasial target.<br/>            Jika diatur ke <see langword="null" />, referensi spasial default atau sumber akan digunakan. |
| width | int | r/w | Menentukan lebar raster output dalam piksel dan kolom.<br/>            Jika nilai diatur ke 0, lebar akan dihitung secara otomatis. Nilai default adalah "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

Menginisialisasi sebuah instance baru dari kelas WarpOptions

