---
title: "Classe WarpOptions"
type: docs
weight: 100
url: /it/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | Inizializza una nuova istanza della classe WarpOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Specifica una nuova altezza della cella raster (nelle unità georiferite di destinazione).<br/>            Se il valore è impostato a 0, il [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) viene calcolato automaticamente. Il valore predefinito è "0". |
| cell_width | double | r/w | Specifica una nuova larghezza della cella raster (nelle unità georiferite di destinazione).<br/>            Se il valore è impostato a 0, il [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) viene calcolato automaticamente. Il valore predefinito è "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Specifica un valore per un riferimento spaziale di origine se manca. |
| altezza | int | r/w | Specifica l'altezza raster di output in pixel e colonne.<br/>            Se il valore è impostato a 0, l'altezza viene calcolata automaticamente. Il valore predefinito è "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Specifica i limiti del livello raster da deformare.<br/>            Se impostato a <see langword="null" />, l'estensione viene calcolata durante la deformazione per includere tutte le celle del raster. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Specifica il riferimento spaziale di destinazione.<br/>            Se impostato a <see langword="null" />, viene utilizzato il riferimento spaziale predefinito o di origine. |
| width | int | r/w | Specifica la larghezza raster di output in pixel e colonne.<br/>            Se il valore è impostato a 0, la larghezza viene calcolata automaticamente. Il valore predefinito è "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

Inizializza una nuova istanza della classe WarpOptions

