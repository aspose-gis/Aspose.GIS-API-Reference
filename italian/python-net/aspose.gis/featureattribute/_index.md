---
title: "FeatureAttribute Classe"
type: docs
weight: 840
url: /it/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Inizializza una nuova istanza della classe [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Inizializza una nuova istanza della classe [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | Restituisce un valore che indica se questa istanza può essere null. |
| can_be_unset | bool | r/w | Ottiene o imposta un valore che indica se il valore per questo attributo può essere omesso. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Restituisce il tipo di dato dell'attributo. |
| default_value | object | r/w | Ottiene o imposta un valore per l'attributo, che indica dati mancanti. |
| has_custom_default_value | bool | r | Restituisce un valore che indica se il valore predefinito per questo attributo è stato sovrascritto con un valore personalizzato. |
| is_locked | bool | r | Restituisce un valore che indica se questo attributo è bloccato. |
| nome | string | r/w | Restituisce il nome dell'attributo. |
| precision | Nullable<int> | r/w | Ottiene o imposta il numero massimo di cifre decimali da memorizzare. |
| type_name | string | r/w | Il nome del tipo dell'attributo. |
| width | Nullable<int> | r/w | Ottiene o imposta la larghezza massima consentita della rappresentazione dei caratteri dell'attributo. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| lock() | Blocca questo attributo. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Inizializza una nuova istanza della classe [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Il nome dell'attributo. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Il tipo di dato dell'attributo. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Inizializza una nuova istanza della classe [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Il nome dell'attributo. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Il tipo di dato dell'attributo. |
| can_be_null | bool | <see langword="true" /> se questa istanza può essere null; altrimenti, <see langword="false" />. |

