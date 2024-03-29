---
title: Class Dataset
second_title: Aspose.GIS för .NET API Referens
description: Aspose.Gis.Dataset klass. En datauppsättning är samlingen avVectorLayer instanser.
type: docs
weight: 80
url: /sv/net/aspose.gis/dataset/
---
## Dataset class

En datauppsättning är samlingen av[`VectorLayer`](../vectorlayer/) instanser.

```csharp
public abstract class Dataset : IDisposable
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [CanCreateLayers](../../aspose.gis/dataset/cancreatelayers/) { get; } | Får ett värde som indikerar om denna datauppsättning kan skapa vektorlager. |
| virtual [CanRemoveLayers](../../aspose.gis/dataset/canremovelayers/) { get; } | Får ett värde som indikerar om denna datauppsättning kan ta bort vektorlager. |
| abstract [Driver](../../aspose.gis/dataset/driver/) { get; } | Får[`Driver`](./driver/) som instansierade denna datauppsättning. |
| abstract [LayersCount](../../aspose.gis/dataset/layerscount/) { get; } | Hämtar antalet lager i denna datauppsättning. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Create](../../aspose.gis/dataset/create/#create)(AbstractPath, FileDriver) | Skapar en datauppsättning. |
| static [Create](../../aspose.gis/dataset/create/#create_2)(string, FileDriver) | Skapar en datauppsättning. |
| static [Create](../../aspose.gis/dataset/create/#create_1)(AbstractPath, FileDriver, DriverOptions) | Skapar en datauppsättning. |
| static [Create](../../aspose.gis/dataset/create/#create_3)(string, FileDriver, DriverOptions) | Skapar en datauppsättning. |
| static [Open](../../aspose.gis/dataset/open/#open)(AbstractPath, FileDriver) | Öppnar datasetet. |
| static [Open](../../aspose.gis/dataset/open/#open_2)(IDbConnection, DatabaseDriver) | Öppnar datasetet. |
| static [Open](../../aspose.gis/dataset/open/#open_3)(string, FileDriver) | Öppnar datasetet. |
| static [Open](../../aspose.gis/dataset/open/#open_1)(AbstractPath, FileDriver, DriverOptions) | Öppnar datasetet. |
| static [Open](../../aspose.gis/dataset/open/#open_4)(string, FileDriver, DriverOptions) | Öppnar datasetet. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer)() | Skapar ett nytt vektorlager och öppnar det för tillägg. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_2)(SpatialReferenceSystem) | Skapar ett nytt vektorlager och öppnar det för tillägg. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_1)(DriverOptions, SpatialReferenceSystem) | Skapar ett nytt vektorlager och öppnar det för tillägg. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_4)(string, SpatialReferenceSystem) | Skapar ett nytt vektorlager med angivet namn och öppnar det för tillägg. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_3)(string, DriverOptions, SpatialReferenceSystem) | Skapar ett nytt vektorlager med angivet namn och öppnar det för tillägg. |
| [Dispose](../../aspose.gis/dataset/dispose/)() | Frigör resurserna som används av`Dataset` . |
| abstract [EditLayer](../../aspose.gis/dataset/editlayer/)(string, DriverOptions, SpatialReferenceSystem) | Öppnar lagret med angivet namn för redigering. |
| abstract [GetLayerName](../../aspose.gis/dataset/getlayername/)(int) | Hämtar namnet på lagret vid angivet index. |
| abstract [OpenLayer](../../aspose.gis/dataset/openlayer/)(string, DriverOptions) | Öppnar lagret med angivet namn för läsning. |
| abstract [OpenLayerAt](../../aspose.gis/dataset/openlayerat/)(int, DriverOptions) | Öppnar lagret vid angivet index för läsning. |
| virtual [RemoveLayer](../../aspose.gis/dataset/removelayer/)(string) | Tar bort vektorlagret med angivet namn. |
| virtual [RemoveLayerAt](../../aspose.gis/dataset/removelayerat/)(int) | Tar bort vektorlagret vid angivet index. |

### Se även

* namnutrymme [Aspose.Gis](../../aspose.gis/)
* hopsättning [Aspose.GIS](../../)


