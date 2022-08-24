---
title: ValidateGeometriesOnWrite
second_title: Référence de l'API Aspose.GIS pour .NET
description: Détermine si les géométries doivent être validées lorsquelles sont ajoutées au calque. Si défini surtrue IsValidaspose.gis.geometries/geometry/isvalidest appelée pour chaque géométrie lorsquelle est ajoutée à la couche et si la validation échoue IsValidaspose.gis.geometries/geometry/isvalid estfalse GisExceptionaspose.gis/gisexception est lancé.
type: docs
weight: 90
url: /fr/net/aspose.gis/driveroptions/validategeometriesonwrite/
---
## DriverOptions.ValidateGeometriesOnWrite property

Détermine si les géométries doivent être validées lorsqu'elles sont ajoutées au calque. Si défini sur`true` ,[`IsValid`](../../../aspose.gis.geometries/geometry/isvalid)est appelée pour chaque géométrie lorsqu'elle est ajoutée à la couche, et si la validation échoue ([`IsValid`](../../../aspose.gis.geometries/geometry/isvalid) est`false` ),[`GisException`](../../gisexception) est lancé.

```csharp
public bool ValidateGeometriesOnWrite { get; set; }
```

### Remarques

Ceci est une option de création - cela n'affecte pas l'ouverture.

### Voir également

* class [DriverOptions](../../driveroptions)
* espace de noms [Aspose.Gis](../../driveroptions)
* Assemblée [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->