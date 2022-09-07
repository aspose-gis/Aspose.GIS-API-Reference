---
title: Relate
second_title: Riferimento API Aspose.GIS per .NET
description: Determina se la matrice di intersezione DE9IM di questa geometria e una geometria specificata corrisponde al modello fornito.
type: docs
weight: 290
url: /it/net/aspose.gis.geometries/igeometry/relate/
---
## IGeometry.Relate method

Determina se la matrice di intersezione DE-9IM di questa geometria e una geometria specificata corrisponde al modello fornito.

```csharp
public bool Relate(IGeometry other, string intersectionPatternMatrix)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | IGeometry | Una geometria |
| intersectionPatternMatrix | String | Un pattern con cui abbinare. Dovrebbe essere una stringa con lunghezza pari a 9. Ogni carattere della stringa rappresenta la dimensione prevista di un'intersezione: carattere 0 - tra gli interni delle geometrie.carattere 1 - tra l'interno di questa geometria e il confine di un'altra geometria.carattere 2 - tra l'interno di questa geometria e l'esterno di un'altra geometria.carattere 3 - tra il confine di questa geometria e l'interno di un'altra geometria.carattere 4 - tra i confini delle geometrie.carattere 5 - tra il confine di questa geometria e l'esterno di un'altra geometria.carattere 6 - tra l'esterno di questa geometria e l'interno di un'altra geometria.carattere 7 - tra l'esterno di questa geometria e il confine di un'altra geometria.carattere 8 - tra gli esterni delle geometrie. I possibili valori di ogni carattere sono: * - qualsiasi valore;F - nessun incrocio;T - qualsiasi incrocio;0 - punto di intersezione (es. punto condiviso);1 - intersezione di linea (es. segmento di linea condiviso);2 - intersezione area (es. parte condivisa di poligono); Ad esempio, un modello di intersezione "F0*******" significa che non dovrebbe esserci un'intersezione tra le geometrie interiors e l'intersezione tra i confini delle geometrie deve essere un punto. Vedere la specifica delle funzioni semplici di OpenGIS per maggiori dettagli sulla matrice di intersezione modello. |

### Valore di ritorno

`true` se questa matrice di intersezione corrisponde al pattern;`false` altrimenti.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *other* è`null`. |
| ArgumentException | Una delle geometrie non è valida in modo tale che l'operazione non possa essere completata. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) di geometrie non sono equivalenti. Puoi usare[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) per convertire le geometrie nello stesso sistema di riferimento spaziale . |

### Osservazioni

Questo metodo crea la matrice di intersezione DE-9IM e la abbina al pattern Vedere la specifica delle funzioni semplici di OpenGIS per maggiori dettagli sulla matrice di intersezione DE-9IM.

### Esempi

Il seguente codice:  rileverà se le geometrie sono spazialmente uguali.

```csharp
geometry.Relate(other, "T*F**FFF*");
```

### Guarda anche

* interface [IGeometry](../../igeometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../igeometry)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->