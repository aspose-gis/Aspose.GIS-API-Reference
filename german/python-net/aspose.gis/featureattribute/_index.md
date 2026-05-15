---
title: "FeatureAttribute-Klasse"
type: docs
weight: 840
url: /de/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Initialisiert eine neue Instanz der [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) Klasse. |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Initialisiert eine neue Instanz der [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | Gibt einen Wert zurück, der angibt, ob diese Instanz null sein kann. |
| can_be_unset | bool | r/w | Liest oder setzt einen Wert, der angibt, ob der Wert für dieses Attribut weggelassen werden kann. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Liest den Datentyp des Attributs. |
| default_value | object | r/w | Liest oder setzt einen Wert für das Attribut, der fehlende Daten anzeigt. |
| has_custom_default_value | bool | r | Gibt einen Wert zurück, der angibt, ob der vordefinierte Standardwert für dieses Attribut durch einen benutzerdefinierten Wert überschrieben wurde. |
| is_locked | bool | r | Gibt einen Wert zurück, der angibt, ob dieses Attribut gesperrt ist. |
| Name | string | r/w | Liest den Namen des Attributs. |
| precision | Nullable<int> | r/w | Liest oder setzt die maximale Anzahl von Dezimalstellen, die gespeichert werden sollen. |
| type_name | string | r/w | Der Typname des Attributs. |
| width | Nullable<int> | r/w | Liest oder setzt die maximal zulässige Breite der Zeichenrepräsentation des Attributs. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| lock() | Sperrt dieses Attribut. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Initialisiert eine neue Instanz der [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Der Name des Attributs. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Der Datentyp des Attributs. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Initialisiert eine neue Instanz der [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Der Name des Attributs. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Der Datentyp des Attributs. |
| can_be_null | bool | <see langword=\"true\" /> wenn diese Instanz null sein kann; andernfalls <see langword=\"false\" />. |

