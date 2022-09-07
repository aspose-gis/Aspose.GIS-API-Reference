---
title: SpatiallyEquals
second_title: Riferimento API Aspose.GIS per .NET
description: Determina se questa geometria è spazialmente uguale a una geometria specificata.
type: docs
weight: 370
url: /it/net/aspose.gis.geometries/geometry/spatiallyequals/
---
## Geometry.SpatiallyEquals method

Determina se questa geometria è spazialmente uguale a una geometria specificata.

```csharp
public bool SpatiallyEquals(IGeometry other)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | IGeometry | Una geometria |

### Valore di ritorno

`true` se questa geometria "equivale nello spazio" alla geometria specificata.`false` altrimenti.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'argomento è`null`. |
| ArgumentException | Una delle geometrie non è valida in modo tale che l'operazione non possa essere completata. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem) di geometrie non sono equivalenti. Puoi usare[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) per convertire le geometrie nello stesso sistema di riferimento spaziale . |

### Osservazioni

Questo metodo verifica l'uguaglianza in termini di matrice di intersezione DE-9IM. Non dipende dall'ordine dei componenti (es. ordine degli anelli interni nel poligono), dai valori Z e M. Fondamentalmente, verifica che due geometrie occupino lo stesso "spazio" quando proiettate su uno spazio bidimensionale. Questo metodo equivale a: Vedere la specifica delle funzioni semplici di OpenGIS per maggiori dettagli su DE-9IM.

```csharp
this.Relate(other, "T*F**FFF*");
```

### Guarda anche

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../geometry)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->