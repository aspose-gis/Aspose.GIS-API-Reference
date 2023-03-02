---
title: Class GdalOptions
second_title: Aspose.GIS för .NET API Referens
description: Aspose.Gis.Formats.GDAL.GdalOptions klass. Drivrutinsspecifika alternativ för GDALformat.
type: docs
weight: 290
url: /sv/net/aspose.gis.formats.gdal/gdaloptions/
---
## GdalOptions class

Drivrutinsspecifika alternativ för GDAL-format.

```csharp
public class GdalOptions : DriverOptions
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [GdalOptions](gdaloptions/)(string) | Skapa en ny instans. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | Bestämmer om stänga en ostängdLinearRing i varje geometri. Standard till`false` . |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | Bestämmer om lägga till en ny punkt i mitten till varje segment av geometri. Standard till`false` . |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | Bestämmer om radera nära punkter i varje geometri. Standard till`false` . |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | Bestämmer avstånd för[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/) . Standard till`0` . |
| [FileName](../../aspose.gis.formats.gdal/gdaloptions/filename/) { get; set; } | Namn på programmet som ska starta |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | En tolerans att använda för att linjärisera kurvgeometrier. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel/) som kommer att tillämpas på M coordinate när geometrier läggs till[`VectorLayer`](../../aspose.gis/vectorlayer/) eller när de läses från[`VectorLayer`](../../aspose.gis/vectorlayer/) . Standardvärdet är[`Exact`](../../aspose.gis/precisionmodel/exact/) . |
| [PathToTempFile](../../aspose.gis.formats.gdal/gdaloptions/pathtotempfile/) { get; } | Sökväg till temporära filer. |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | Bestämmer om raderingspunkter som ligger på samma segment i varje geometri. Standard till`false` . |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | Bestämmer avstånd för[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/) . Standard till`0` . |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | Bestämmer om geometrier ska valideras när de läggs till i lagret. Om satt till`true` ,[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) anropas för each geometri när den läggs till i lagret och om valideringen misslyckas ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) är`false` ),[`GisException`](../../aspose.gis/gisexception/) kastas. |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | Bestämmer om transformation av polygon eller multipolygon till linjesträng är tillåten. Standard till`false` . |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel/) som kommer att tillämpas på X- och Y-koordinater när geometrier läggs till[`VectorLayer`](../../aspose.gis/vectorlayer/) eller när de läses från[`VectorLayer`](../../aspose.gis/vectorlayer/) . Standardvärdet är[`Exact`](../../aspose.gis/precisionmodel/exact/) . |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel/) som kommer att tillämpas på Z coordinate när geometrier läggs till[`VectorLayer`](../../aspose.gis/vectorlayer/) eller när de läses från[`VectorLayer`](../../aspose.gis/vectorlayer/) . Standardvärdet är[`Exact`](../../aspose.gis/precisionmodel/exact/) . |

### Se även

* class [DriverOptions](../../aspose.gis/driveroptions/)
* namnutrymme [Aspose.Gis.Formats.GDAL](../../aspose.gis.formats.gdal/)
* hopsättning [Aspose.GIS](../../)

