---
title: "WarpOptions-klass"
type: docs
weight: 100
url: /sv/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | Initierar en ny instans av WarpOptions-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Anger en ny höjd för rastercellen (i målgeorefererade enheter).<br/>            Om värdet är satt till 0, beräknas [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) automatiskt. Standardvärdet är "0". |
| cell_width | double | r/w | Anger en ny bredd för rastercellen (i målgeorefererade enheter).<br/>            Om värdet är satt till 0, beräknas [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) automatiskt. Standardvärdet är "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Anger ett värde för en källrumslig referens om den saknas. |
| höjd | int | läs/skriv | Anger utdata rasterhöjd i pixlar och kolumner.<br/>            Om värdet är satt till 0, beräknas höjden automatiskt. Standardvärdet är "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Anger gränserna för rasterlagret som ska warpas.<br/>            Om satt till <see langword="null" />, beräknas omfattningen under warpning för att inkludera alla celler från raster. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Anger målrumslig referens.<br/>            Om satt till <see langword="null" />, används standard- eller källreferensen. |
| bredd | int | läs/skriv | Anger utdata rasterbredd i pixlar och kolumner.<br/>            Om värdet är satt till 0, beräknas bredden automatiskt. Standardvärdet är "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

Initierar en ny instans av WarpOptions-klassen

