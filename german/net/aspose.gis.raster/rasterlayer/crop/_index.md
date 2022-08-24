---
title: Crop
second_title: Aspose.GIS für .NET-API-Referenz
description: Beschneidet die Rasterebene mithilfe eines Formformulars.
type: docs
weight: 110
url: /de/net/aspose.gis.raster/rasterlayer/crop/
---
## RasterLayer.Crop method

Beschneidet die Rasterebene mithilfe eines Formformulars.

```csharp
public RasterLayer Crop(IGeometry geometry)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| geometry | IGeometry | Geometrie stellte die Formform dar. |

### Rückgabewert

Die zugeschnittene Rasterebene. Wenn keine Schnittpunkte gefunden werden, kehrt zurück`null`.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Das Argument darf nicht null sein. Parametername: Geometrie. |
| NotSupportedException | Das Argument darf sich nicht von Polygon oder Oberfläche unterscheiden. Parametername: Geometrie. |
| InvalidOperationException | Die ursprüngliche Ebene kann keine andere CropRasterLayer sein. |
| [GisException](../../../aspose.gis/gisexception) | Fehler beim Zuschneiden der Ebene. |

### Siehe auch

* interface [IGeometry](../../../aspose.gis.geometries/igeometry)
* class [RasterLayer](../../rasterlayer)
* namensraum [Aspose.Gis.Raster](../../rasterlayer)
* Montage [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->