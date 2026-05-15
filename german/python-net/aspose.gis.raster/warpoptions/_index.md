---
title: "WarpOptions Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | Initialisiert eine neue Instanz der WarpOptions Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Gibt eine neue Höhe der Rasterzelle an (in den Ziel-Georeferenzierungseinheiten).<br/>            Wenn der Wert auf 0 gesetzt ist, wird [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) automatisch berechnet. Der Standardwert ist "0". |
| cell_width | double | r/w | Gibt eine neue Breite der Rasterzelle an (in den Ziel-Georeferenzierungseinheiten).<br/>            Wenn der Wert auf 0 gesetzt ist, wird [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) automatisch berechnet. Der Standardwert ist "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Gibt einen Wert für eine Quell-Raumreferenz an, falls diese fehlt. |
| Höhe | int | r/w | Gibt die Ausgabe‑Rasterhöhe in Pixeln und Spalten an.<br/>            Wenn der Wert auf 0 gesetzt ist, wird die Höhe automatisch berechnet. Der Standardwert ist "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Gibt die Grenzen der zu verzerrenden Rasterebene an.<br/>            Wenn auf <see langword="null" /> gesetzt, wird das Ausdehnungsgebiet während der Verzerrung berechnet, um alle Zellen des Rasters einzuschließen. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Gibt die Ziel‑Raumreferenz an.<br/>            Wenn auf <see langword="null" /> gesetzt, wird die Standard‑ oder Quell‑Raumreferenz verwendet. |
| width | int | r/w | Gibt die Ausgabe‑Rasterbreite in Pixeln und Spalten an.<br/>            Wenn der Wert auf 0 gesetzt ist, wird die Breite automatisch berechnet. Der Standardwert ist "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

Initialisiert eine neue Instanz der WarpOptions Klasse

