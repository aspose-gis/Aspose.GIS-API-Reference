---
title: FromBinary
second_title: Riferimento API Aspose.GIS per .NET
description: Crea una geometria dalla sua rappresentazione binaria ben nota.
type: docs
weight: 460
url: /it/net/aspose.gis.geometries/geometry/frombinary/
---
## FromBinary(byte[]) {#frombinary}

Crea una geometria dalla sua rappresentazione binaria ben nota.

```csharp
public static IGeometry FromBinary(byte[] wkb)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| wkb | Byte[] | Rappresentazione binaria ben nota di una geometria. |

### Valore di ritorno

Una geometria rappresentata dall'argomento.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'argomento è nullo. |
| NotSupportedException | L'argomento rappresenta una geometria di tipo non supportato. |
| FormatException | L'argomento non è un binario noto valido. |

### Guarda anche

* interface [IGeometry](../../igeometry)
* class [Geometry](../../geometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../geometry)
* assemblea [Aspose.GIS](../../../)

---

## FromBinary(byte[], SpatialReferenceSystem) {#frombinary_1}

Crea una geometria dalla sua rappresentazione binaria ben nota.

```csharp
public static IGeometry FromBinary(byte[] wkb, SpatialReferenceSystem spatialReferenceSystem)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| wkb | Byte[] | Rappresentazione binaria ben nota di una geometria. |
| spatialReferenceSystem | SpatialReferenceSystem | Sistema di riferimento spaziale da assegnare alla geometria. |

### Valore di ritorno

Una geometria rappresentata dall'argomento.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'argomento è nullo. |
| NotSupportedException | L'argomento rappresenta una geometria di tipo non supportato. |
| FormatException | L'argomento non è un binario noto valido. |

### Osservazioni

Se sono presenti byte extra dopo la geometria aFormatException viene generata un'eccezione.

### Guarda anche

* interface [IGeometry](../../igeometry)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [Geometry](../../geometry)
* spazio dei nomi [Aspose.Gis.Geometries](../../geometry)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->