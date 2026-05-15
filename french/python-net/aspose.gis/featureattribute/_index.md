---
title: "Classe FeatureAttribute"
type: docs
weight: 840
url: /fr/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Initialise une nouvelle instance de la classe [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Initialise une nouvelle instance de la classe [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | Obtient une valeur indiquant si cette instance peut être nulle. |
| can_be_unset | bool | r/w | Obtient ou définit une valeur indiquant si la valeur de cet attribut peut être omise. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Obtient le type de données de l'attribut. |
| default_value | object | r/w | Obtient ou définit une valeur pour l'attribut, qui indique des données manquantes. |
| has_custom_default_value | bool | r | Obtient une valeur indiquant si la valeur par défaut pré‑définie pour cet attribut a été remplacée par une valeur personnalisée. |
| is_locked | bool | r | Obtient une valeur indiquant si cet attribut est verrouillé. |
| nom | string | r/w | Obtient le nom de l'attribut. |
| precision | Nullable<int> | r/w | Obtient ou définit le nombre maximal de chiffres décimaux à stocker. |
| type_name | string | r/w | Le nom du type de l'attribut. |
| width | Nullable<int> | r/w | Obtient ou définit la largeur maximale autorisée de la représentation en caractères de l'attribut. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| lock() | Verrouille cet attribut. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Initialise une nouvelle instance de la classe [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Le nom de l'attribut. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Le type de données de l'attribut. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Initialise une nouvelle instance de la classe [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Le nom de l'attribut. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Le type de données de l'attribut. |
| can_be_null | bool | <see langword=\"true\" /> si cette instance peut être nulle ; sinon, <see langword=\"false\" />. |

