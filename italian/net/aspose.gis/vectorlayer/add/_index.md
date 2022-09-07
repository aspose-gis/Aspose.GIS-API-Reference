---
title: Add
second_title: Riferimento API Aspose.GIS per .NET
description: Aggiunge una nuova funzionalità al livello se supportata daVectorLayeraspose.gis/vectorlayer SDriveraspose.gis/vectorlayer/driver .
type: docs
weight: 80
url: /it/net/aspose.gis/vectorlayer/add/
---
## Add(Feature) {#add}

Aggiunge una nuova funzionalità al livello, se supportata da[`VectorLayer`](../../vectorlayer) S[`Driver`](../driver) .

```csharp
public void Add(Feature feature)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| feature | Feature | La funzione da aggiungere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | viene lanciato se il livello è di sola lettura. |

### Guarda anche

* class [Feature](../../feature)
* class [VectorLayer](../../vectorlayer)
* spazio dei nomi [Aspose.Gis](../../vectorlayer)
* assemblea [Aspose.GIS](../../../)

---

## Add(Feature, IFeatureStyle) {#add_1}

Aggiunge una nuova funzionalità con lo stile specificato al livello, se supportata da[`VectorLayer`](../../vectorlayer) S[`Driver`](../driver) .

```csharp
public virtual void Add(Feature feature, IFeatureStyle style)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| feature | Feature | La funzione da aggiungere. |
| style | IFeatureStyle | Lo stile delle caratteristiche. Uso`null` per indicare lo stile mancante. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| InvalidOperationException | viene generato se il livello non supporta gli stili o se il livello è di sola lettura. |
| InvalidOperationException | viene generato se i livelli modificabili non supportano gli stili. |
| ArgumentException | viene generato se lo stile non corrisponde al tipo di driver. |

### Guarda anche

* class [Feature](../../feature)
* interface [IFeatureStyle](../../ifeaturestyle)
* class [VectorLayer](../../vectorlayer)
* spazio dei nomi [Aspose.Gis](../../vectorlayer)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->