---
title: Unit
second_title: Riferimento API Aspose.GIS per .NET
description: Rappresenta lunità di misura.
type: docs
weight: 2190
url: /it/net/aspose.gis.spatialreferencing/unit/
---
## Unit class

Rappresenta l'unità di misura.

```csharp
public class Unit : IdentifiableObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Unit](unit)(string, double, Identifier) | Crea nuova istanza. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Degree](../../aspose.gis.spatialreferencing/unit/degree) { get; } | Ottieni unità che rappresenta i gradi. |
| static [Meter](../../aspose.gis.spatialreferencing/unit/meter) { get; } | Ottieni unità che rappresenta i metri. |
| static [Radian](../../aspose.gis.spatialreferencing/unit/radian) { get; } | Ottieni unità che rappresenta i radianti. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode) { get; } | Se questo identificatore di oggetti è identificatore EPSG, restituisci il suo codice. Altrimenti - restituisce -1. |
| [Factor](../../aspose.gis.spatialreferencing/unit/factor) { get; } | Fattore in metro, se è l'unità di lunghezza, fattore in radianti, se è l'unità angolare. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier) { get; } | Identificatore di questo oggetto identificabile. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name) { get; } | Nome di questo oggetto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Apply](../../aspose.gis.spatialreferencing/unit/apply)(double) | Converte l'argomento in unità, descritto da questa istanza. |
| [Deapply](../../aspose.gis.spatialreferencing/unit/deapply)(double) | Converte l'argomento dall'unità, descritta da questa istanza, in radianti o metri. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring)() | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Guarda anche

* class [IdentifiableObject](../identifiableobject)
* spazio dei nomi [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing)
* assemblea [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->