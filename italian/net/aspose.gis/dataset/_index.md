---
title: Class Dataset
second_title: Riferimento API Aspose.GIS per .NET
description: Aspose.Gis.Dataset classe. Un set di dati è la raccolta diVectorLayer istanze.
type: docs
weight: 80
url: /it/net/aspose.gis/dataset/
---
## Dataset class

Un set di dati è la raccolta di[`VectorLayer`](../vectorlayer/) istanze.

```csharp
public abstract class Dataset : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [CanCreateLayers](../../aspose.gis/dataset/cancreatelayers/) { get; } | Ottiene un valore che indica se questo set di dati può creare layer vettoriali. |
| virtual [CanRemoveLayers](../../aspose.gis/dataset/canremovelayers/) { get; } | Ottiene un valore che indica se questo set di dati può rimuovere layer vettoriali. |
| abstract [Driver](../../aspose.gis/dataset/driver/) { get; } | Ottiene il[`Driver`](./driver/) che ha istanziato questo set di dati. |
| abstract [LayersCount](../../aspose.gis/dataset/layerscount/) { get; } | Ottiene il numero di livelli in questo set di dati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../aspose.gis/dataset/create/#create)(AbstractPath, FileDriver) | Crea un set di dati. |
| static [Create](../../aspose.gis/dataset/create/#create_2)(string, FileDriver) | Crea un set di dati. |
| static [Create](../../aspose.gis/dataset/create/#create_1)(AbstractPath, FileDriver, DriverOptions) | Crea un set di dati. |
| static [Create](../../aspose.gis/dataset/create/#create_3)(string, FileDriver, DriverOptions) | Crea un set di dati. |
| static [Open](../../aspose.gis/dataset/open/#open)(AbstractPath, FileDriver) | Apre il set di dati. |
| static [Open](../../aspose.gis/dataset/open/#open_2)(IDbConnection, DatabaseDriver) | Apre il set di dati. |
| static [Open](../../aspose.gis/dataset/open/#open_3)(string, FileDriver) | Apre il set di dati. |
| static [Open](../../aspose.gis/dataset/open/#open_1)(AbstractPath, FileDriver, DriverOptions) | Apre il set di dati. |
| static [Open](../../aspose.gis/dataset/open/#open_4)(string, FileDriver, DriverOptions) | Apre il set di dati. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer)() | Crea un nuovo livello vettoriale e lo apre per l'aggiunta. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_2)(SpatialReferenceSystem) | Crea un nuovo livello vettoriale e lo apre per l'aggiunta. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_1)(DriverOptions, SpatialReferenceSystem) | Crea un nuovo livello vettoriale e lo apre per l'aggiunta. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_4)(string, SpatialReferenceSystem) | Crea un nuovo vettore con il nome specificato e lo apre per l'aggiunta. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_3)(string, DriverOptions, SpatialReferenceSystem) | Crea un nuovo vettore con il nome specificato e lo apre per l'aggiunta. |
| [Dispose](../../aspose.gis/dataset/dispose/)() | Rilascia le risorse utilizzate da`Dataset` . |
| abstract [EditLayer](../../aspose.gis/dataset/editlayer/)(string, DriverOptions, SpatialReferenceSystem) | Apre il livello con il nome specificato per la modifica. |
| abstract [GetLayerName](../../aspose.gis/dataset/getlayername/)(int) | Ottiene il nome del layer all'indice specificato. |
| abstract [OpenLayer](../../aspose.gis/dataset/openlayer/)(string, DriverOptions) | Apre il livello con il nome specificato per la lettura. |
| abstract [OpenLayerAt](../../aspose.gis/dataset/openlayerat/)(int, DriverOptions) | Apre il livello all'indice specificato per la lettura. |
| virtual [RemoveLayer](../../aspose.gis/dataset/removelayer/)(string) | Rimuove il livello vettoriale con il nome specificato. |
| virtual [RemoveLayerAt](../../aspose.gis/dataset/removelayerat/)(int) | Rimuove il livello vettoriale all'indice specificato. |

### Guarda anche

* spazio dei nomi [Aspose.Gis](../../aspose.gis/)
* assemblea [Aspose.GIS](../../)


