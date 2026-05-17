---
title: "Clase WarpOptions"
type: docs
weight: 100
url: /es/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | Inicializa una nueva instancia de la clase WarpOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Especifica una nueva altura de la celda raster (en unidades georreferenciadas de destino).<br/>            Si el valor se establece en 0, la [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) se calcula automáticamente. El valor predeterminado es "0". |
| cell_width | double | r/w | Especifica una nueva anchura de la celda raster (en unidades georreferenciadas de destino).<br/>            Si el valor se establece en 0, la [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) se calcula automáticamente. El valor predeterminado es "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Especifica un valor para la referencia espacial de origen si falta. |
| altura | int | r/w | Especifica la altura del raster de salida en píxeles y columnas.<br/>            Si el valor se establece en 0, la altura se calcula automáticamente. El valor predeterminado es "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Especifica los límites de la capa raster a deformar.<br/>            Si se establece en <see langword="null" />, la extensión se calcula durante la deformación para incluir todas las celdas del raster. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Especifica la referencia espacial de destino.<br/>            Si se establece en <see langword="null" />, se utiliza la referencia espacial predeterminada o la de origen. |
| width | int | r/w | Especifica la anchura del raster de salida en píxeles y columnas.<br/>            Si el valor se establece en 0, la anchura se calcula automáticamente. El valor predeterminado es "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

Inicializa una nueva instancia de la clase WarpOptions

