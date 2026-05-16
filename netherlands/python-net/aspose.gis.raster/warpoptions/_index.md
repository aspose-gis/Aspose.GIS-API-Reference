---
title: "WarpOptions Klasse"
type: docs
weight: 100
url: /nl/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | Initialiseert een nieuwe instantie van de WarpOptions klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Specificeert een nieuwe hoogte van de rastercel (in doel-georeferentie-eenheden).<br/>            Als de waarde is ingesteld op 0, wordt de [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) automatisch berekend. De standaardwaarde is "0". |
| cell_width | double | r/w | Specificeert een nieuwe breedte van de rastercel (in doel-georeferentie-eenheden).<br/>            Als de waarde is ingesteld op 0, wordt de [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) automatisch berekend. De standaardwaarde is "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Specificeert een waarde voor een bron-ruimtelijke referentie als deze ontbreekt. |
| hoogte | int | r/w | Specificeert de uitvoer rasterhoogte in pixels en kolommen.<br/>            Als de waarde is ingesteld op 0, wordt de hoogte automatisch berekend. De standaardwaarde is "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Specificeert de grenzen van de rasterlaag om te transformeren.<br/>            Als ingesteld op <see langword="null" />, wordt de omvang berekend tijdens het transformeren om alle cellen van het raster op te nemen. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Specificeert de doel-ruimtelijke referentie.<br/>            Als ingesteld op <see langword="null" />, wordt de standaard- of bron-ruimtelijke referentie gebruikt. |
| width | int | r/w | Specificeert de uitvoer rasterbreedte in pixels en kolommen.<br/>            Als de waarde is ingesteld op 0, wordt de breedte automatisch berekend. De standaardwaarde is "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

Initialiseert een nieuwe instantie van de WarpOptions klasse

