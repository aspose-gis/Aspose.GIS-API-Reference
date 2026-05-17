---
title: "Класс WarpOptions"
type: docs
weight: 100
url: /ru/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | Инициализирует новый экземпляр класса WarpOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Указывает новую высоту ячейки растра (в целевых геопривязанных единицах).<br/>            Если значение установлено в 0, [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) вычисляется автоматически. Значение по умолчанию — "0". |
| cell_width | double | r/w | Указывает новую ширину ячейки растра (в целевых геопривязанных единицах).<br/>            Если значение установлено в 0, [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) вычисляется автоматически. Значение по умолчанию — "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Указывает значение для исходной пространственной привязки, если оно отсутствует. |
| высота | int | r/w | Указывает высоту выходного растра в пикселях и столбцах.<br/>            Если значение установлено в 0, высота вычисляется автоматически. Значение по умолчанию — "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Указывает границы растр-слоя для преобразования.<br/>            Если установлено <see langword="null" />, область рассчитывается во время преобразования, чтобы включить все ячейки растра. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Указывает целевую пространственную привязку.<br/>            Если установлено <see langword="null" />, используется привязка по умолчанию или исходная. |
| width | int | r/w | Указывает ширину выходного растра в пикселях и столбцах.<br/>            Если значение установлено в 0, ширина вычисляется автоматически. Значение по умолчанию — "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

Инициализирует новый экземпляр класса WarpOptions

