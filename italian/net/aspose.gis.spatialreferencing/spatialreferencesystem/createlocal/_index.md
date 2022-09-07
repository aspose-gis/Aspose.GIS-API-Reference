---
title: CreateLocal
second_title: Riferimento API Aspose.GIS per .NET
description: Crea SRS locale.
type: docs
weight: 370
url: /it/net/aspose.gis.spatialreferencing/spatialreferencesystem/createlocal/
---
## SpatialReferenceSystem.CreateLocal method

Crea SRS locale.

```csharp
public static LocalSpatialReferenceSystem CreateLocal(string name, LocalDatum datum, Unit unit, 
    ICollection<Axis> axises, Identifier identifier = null)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | String | Nome di SRS. |
| datum | LocalDatum | Datum da utilizzare in SRS. |
| unit | Unit | Unità da utilizzare in SRS. |
| axises | ICollection`1 | Assi da utilizzare in SRS. Deve essere non vuoto |
| identifier | Identifier | Identificatore, che sarà allegato a SRS. Allegare un identificatore non modificherà altri parametri SRS. Sta a te garantire la coerenza dell'identificatore e dei parametri SRS. |

### Valore di ritorno

Nuovo SRS locale.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | *axises* è vuoto. |
| ArgumentNullException | Qualsiasi argomento, tranne*identifier* è zero. |

### Guarda anche

* class [LocalSpatialReferenceSystem](../../localspatialreferencesystem)
* class [LocalDatum](../../localdatum)
* class [Unit](../../unit)
* class [Axis](../../axis)
* class [Identifier](../../identifier)
* class [SpatialReferenceSystem](../../spatialreferencesystem)
* spazio dei nomi [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->