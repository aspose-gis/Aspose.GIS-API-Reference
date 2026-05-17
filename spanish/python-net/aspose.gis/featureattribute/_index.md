---
title: "Clase FeatureAttribute"
type: docs
weight: 840
url: /es/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Inicializa una nueva instancia de la clase [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Inicializa una nueva instancia de la clase [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | Obtiene un valor que indica si esta instancia puede ser nula. |
| can_be_unset | bool | r/w | Obtiene o establece un valor que indica si el valor de este atributo puede omitirse. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Obtiene el tipo de datos del atributo. |
| default_value | object | r/w | Obtiene o establece un valor para el atributo que indica datos faltantes. |
| has_custom_default_value | bool | r | Obtiene un valor que indica si el valor predeterminado predefinido para este atributo fue sobrescrito con un valor personalizado. |
| is_locked | bool | r | Obtiene un valor que indica si este atributo está bloqueado. |
| nombre | string | r/w | Obtiene el nombre del atributo. |
| precision | Nullable<int> | r/w | Obtiene o establece el número máximo de dígitos decimales a almacenar. |
| type_name | string | r/w | El nombre del tipo del atributo. |
| width | Nullable<int> | r/w | Obtiene o establece el ancho máximo permitido de la representación de caracteres del atributo. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| lock() | Bloquea este atributo. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Inicializa una nueva instancia de la clase [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | El nombre del atributo. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | El tipo de datos del atributo. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Inicializa una nueva instancia de la clase [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | El nombre del atributo. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | El tipo de datos del atributo. |
| can_be_null | bool | <see langword="true" /> si esta instancia puede ser nula; de lo contrario, <see langword="false" />. |

