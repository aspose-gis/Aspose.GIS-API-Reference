---
title: ProducePoints
second_title: Référence de l'API Aspose.GIS pour .NET
description: Crée un tableau de points appartenant à la zone spécifiée.
type: docs
weight: 20
url: /fr/net/aspose.gis.geotools/geogenerator/producepoints/
---
## GeoGenerator.ProducePoints method

Crée un tableau de points appartenant à la zone spécifiée.

```csharp
public static IEnumerable<IGeometry> ProducePoints(Extent rect, PointGeneratorOptions options)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rect | Extent | Zone spécifiée (voir[`Le degré`](../../../aspose.gis/extent)). |
| options | PointGeneratorOptions | Options de création de points (voir[`Options du générateur de points`](../../pointgeneratoroptions)). |

### Return_Value

Tableau de points (voir énumération des[`IGéométrie`](../../../aspose.gis.geometries/igeometry)).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Le nombre de points doit être supérieur à un. |
| NullReferenceException | L'étendue doit avoir une valeur (et non NULL). |

### Voir également

* interface [IGeometry](../../../aspose.gis.geometries/igeometry)
* class [Extent](../../../aspose.gis/extent)
* class [PointGeneratorOptions](../../pointgeneratoroptions)
* class [GeoGenerator](../../geogenerator)
* espace de noms [Aspose.Gis.GeoTools](../../geogenerator)
* Assemblée [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->