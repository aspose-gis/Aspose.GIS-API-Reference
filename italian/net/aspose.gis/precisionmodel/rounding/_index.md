---
title: Rounding
second_title: Riferimento API Aspose.GIS per .NET
description: Restituisce un modello di precisione di arrotondamento. Secondo il modello di precisione di arrotondamento solo un numero limitato di cifre è significativo.
type: docs
weight: 20
url: /it/net/aspose.gis/precisionmodel/rounding/
---
## PrecisionModel.Rounding method

Restituisce un modello di precisione di arrotondamento. Secondo il modello di precisione di arrotondamento solo un numero limitato di cifre è significativo.

```csharp
public static PrecisionModel Rounding(int significantDigits)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| significantDigits | Int32 | Numero di cifre significative. |

### Valore di ritorno

Modello di precisione di arrotondamento.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | Il numero di cifre significative è inferiore a 0 o superiore a 15. |

### Osservazioni

Quando applicato a una coordinata, il codice seguente viene utilizzato per ridurre la precisione:

```csharp
double rounded = Math.Round(value, significantDigits);
```

### Guarda anche

* class [PrecisionModel](../../precisionmodel)
* spazio dei nomi [Aspose.Gis](../../precisionmodel)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->