---
title: ToLinearGeometry
second_title: Riferimento API Aspose.GIS per .NET
description: Ottiene una versione non curva approssimativa o equivalente di questa geometria utilizzando limpostazione predefinitatolleranza .
type: docs
weight: 20
url: /it/net/aspose.gis.geometries/imulticurve/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

Ottiene una versione non curva approssimativa o equivalente di questa geometria utilizzando l'impostazione predefinita`tolleranza` .

```csharp
public IMultiLineString ToLinearGeometry()
```

### Valore di ritorno

A[`IMultiLineString`](../../imultilinestring) che si avvicina o equivale a questo[`IMultiCurve`](../../imulticurve). Questo è l'equivalente di[`ToLinearGeometry`](../tolineargeometry) con predefinito`tolleranza` . Predefinito`tolleranza` Il valore di s dipende da[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem) di questa geometria:  Per la tolleranza SRS prevista è 0,001 metri (in unità SRS) Per la tolleranza SRS geografica è`1e-5` gradi (in unità SRS) Per la tolleranza SRS sconosciuta è`1e-5` Per maggiori dettagli su quali trasformazioni vengono applicate fare riferimento[`ToLinearGeometry`](../tolineargeometry) specifica.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | Questa geometria non è valida in modo tale che l'operazione non può essere completata. |

### Guarda anche

* interface [IMultiLineString](../../imultilinestring)
* interface [IMultiCurve](../../imulticurve)
* spazio dei nomi [Aspose.Gis.Geometries](../../imulticurve)
* assemblea [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

Ottiene una versione non curva approssimativa o equivalente di questa geometria utilizzando l'elemento specificato`tolleranza` .

```csharp
public IMultiLineString ToLinearGeometry(double tolerance)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tolerance | Double | Il`tolleranza`usare. Il risultato è garantito inferiore a`tolleranza` lontano dalla geometria curva , a meno che il numero di punti necessari per linearizzare la geometria non ecceda il massimo per quadrante, attualmente pari a 10000 punti. |

### Valore di ritorno

A[`IMultiLineString`](../../imultilinestring) che si avvicina o equivale a questo[`IMultiCurve`](../../imulticurve) :  Se questo oggetto è[`IMultiLineString`](../../imultilinestring) stesso il risultato è equivalente a questo oggetto Se questo oggetto non lo è[`IMultiLineString`](../../imultilinestring) - tutte le curve sono linearizzate e nuove`IMultiLineString` viene creato

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | `tolleranza` è minore o uguale a`0` . |
| InvalidOperationException | Questa geometria non è valida in modo tale che l'operazione non può essere completata. |

### Guarda anche

* interface [IMultiLineString](../../imultilinestring)
* interface [IMultiCurve](../../imulticurve)
* spazio dei nomi [Aspose.Gis.Geometries](../../imulticurve)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->