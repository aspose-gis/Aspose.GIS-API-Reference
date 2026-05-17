---
title: "FeatureAttribute klass"
type: docs
weight: 840
url: /sv/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Initierar en ny instans av klassen [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Initierar en ny instans av klassen [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| can_be_null | bool | läs/skriv | Hämtar ett värde som indikerar om detta objekt kan vara null. |
| can_be_unset | bool | läs/skriv | Hämtar eller anger ett värde som indikerar om värdet för detta attribut kan utelämnas. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Hämtar datatypen för attributet. |
| default_value | objekt | läs/skriv | Hämtar eller anger ett värde för attributet som indikerar saknad data. |
| has_custom_default_value | bool | r | Hämtar ett värde som indikerar om det fördefinierade standardvärdet för detta attribut har ersatts med ett anpassat värde. |
| is_locked | bool | r | Hämtar ett värde som indikerar om detta attribut är låst. |
| namn | string | läs/skriv | Hämtar namnet på attributet. |
| precision | Nullable<int> | läs/skriv | Hämtar eller anger maximalt antal decimaler som ska lagras. |
| type_name | string | läs/skriv | Typnamnet för attributet. |
| bredd | Nullable<int> | läs/skriv | Hämtar eller anger maximal tillåten bredd för teckenrepresentationen av attributet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| lock() | Låser detta attribut. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Initierar en ny instans av klassen [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnet på attributet. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Datatypen för attributet. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Initierar en ny instans av klassen [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namnet på attributet. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Datatypen för attributet. |
| can_be_null | bool | <see langword=\"true\" /> om detta objekt kan vara null; annars <see langword=\"false\" />. |

