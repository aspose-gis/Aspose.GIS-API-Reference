---
title: "FeatureAttribute Klasse"
type: docs
weight: 840
url: /nl/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Initialiseert een nieuw exemplaar van de [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) klasse. |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Initialiseert een nieuw exemplaar van de [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | Haalt een waarde op die aangeeft of deze instantie null kan zijn. |
| can_be_unset | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of de waarde voor dit attribuut kan worden weggelaten. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Haalt het gegevenstype van het attribuut op. |
| default_value | object | r/w | Haalt een waarde voor het attribuut op of stelt deze in, die ontbrekende gegevens aangeeft. |
| has_custom_default_value | bool | r | Haalt een waarde op die aangeeft of de vooraf gedefinieerde standaardwaarde voor dit attribuut is overschreven met een aangepaste waarde. |
| is_locked | bool | r | Haalt een waarde op die aangeeft of dit attribuut vergrendeld is. |
| naam | string | r/w | Haalt de naam van het attribuut op. |
| precision | Nullable<int> | r/w | Haalt het maximum aantal decimale cijfers op of stelt dit in om op te slaan. |
| type_name | string | r/w | De typenaam van het attribuut. |
| width | Nullable<int> | r/w | Haalt de maximaal toegestane breedte van de tekenrepresentatie van het attribuut op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| lock() | Vergrendelt dit attribuut. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Initialiseert een nieuw exemplaar van de [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | De naam van het attribuut. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Het gegevenstype van het attribuut. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Initialiseert een nieuw exemplaar van de [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | De naam van het attribuut. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Het gegevenstype van het attribuut. |
| can_be_null | bool | <see langword=\"true\" /> als deze instantie null kan zijn; anders <see langword=\"false\" />. |

