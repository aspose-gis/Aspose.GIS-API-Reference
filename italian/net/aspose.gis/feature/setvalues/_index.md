---
title: SetValues
second_title: Riferimento API Aspose.GIS per .NET
description: Imposta nuovi valori per tutti gli attributi. Considera anche di utilizzareCopyValuesaspose.gis/feature/copyvalues metodo per semplificare limpostazione dei valori in una chiamata.
type: docs
weight: 120
url: /it/net/aspose.gis/feature/setvalues/
---
## Feature.SetValues method

Imposta nuovi valori per tutti gli attributi. Considera anche di utilizzare[`CopyValues`](../copyvalues) metodo per semplificare l'impostazione dei valori in una chiamata.

```csharp
public int SetValues(object[] values)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| values | Object[] | L'array di nuovi valori. |

### Valore di ritorno

Il numero di valori di attributo impostati.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | L'argomento non può essere`null`. |
| ArgumentException | L'attributo con questo nome non esiste in questo livello. |
| InvalidOperationException | L'attributo non è bloccato. |
| InvalidCastException | Il tipo del valore non viene implementatoIConvertible. |
| FormatException | Conversione non riuscita perché il valore è in un formato errato. |
| OverflowException | Conversione non riuscita a causa di overflow. |

### Osservazioni

Questo metodo converte automaticamente ogni valore nel tipo dell'attributo.  La lunghezza dell'array dei valori non deve necessariamente corrispondere al numero di attributi nella funzione. Se la lunghezza dell'array è maggiore del numero di attributi, tutti i valori dell'array vengono copiati negli attributi; se è inferiore, solo il numero di valori della lunghezza dell'array viene copiato negli attributi, a partire dal valore dell'attributo con ordinale 0.

### Guarda anche

* class [Feature](../../feature)
* spazio dei nomi [Aspose.Gis](../../feature)
* assemblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->