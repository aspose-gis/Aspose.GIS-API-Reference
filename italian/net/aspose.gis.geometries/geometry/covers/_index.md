---
title: Covers
second_title: Riferimento API Aspose.GIS per .NET
description: Determina se questa geometria copre una geometria specificata.
type: docs
weight: 160
url: /it/net/aspose.gis.geometries/geometry/covers/
---
## Geometry.Covers method

Determina se questa geometria copre una geometria specificata.

```csharp
public bool Covers(IGeometry other)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | IGeometry | Una geometria |

### Valore di ritorno

`true` se questa geometria è "copre spazialmente" un'altra geometria.`false` altrimenti.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'argomento è`null`. |
| ArgumentException | Una delle geometrie non è valida in modo tale che l'operazione non possa essere completata. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) di geometrie non sono equivalenti. Puoi usare[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) per convertire le geometrie nello stesso sistema di riferimento spaziale . |

### Osservazioni

Questo metodo verifica se una geometria ne copre un'altra in termini di matrice di intersezione DE-9IM. Una geometria ne copre un'altra, se la geometria contiene tutti i punti di un'altra geometria. Questo metodo è simile a[`SpatiallyContains`](../../igeometry/spatiallycontains) , ma ritorna`true` più spesso, poiché non distingue tra punti interni e punti di confine. Quindi, se la geometria A giace sul confine della geometria B,[`SpatiallyContains`](../../igeometry/spatiallycontains) ritorna`false` , mentre questo metodo ritorna`true`. Questo metodo equivale a:

```csharp
this.Relate(other, "T*****FF*") || this.Relate(other, "*T****FF*") || this.Relate(other, "***T**FF*) || this.Relate(other, "***T*FF*");
```

### Guarda anche

* method [SpatiallyContains](../../igeometry/spatiallycontains)
* method [CoveredBy](../../igeometry/coveredby)
* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../geometry)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->