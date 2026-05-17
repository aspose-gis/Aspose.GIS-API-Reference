---
title: "Projection Sınıfı"
type: docs
weight: 170
url: /tr/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Açısal parametreler için kullanılan birim. |
| epsg_code | int | r | Eğer bu nesnenin tanımlayıcısı EPSG tanımlayıcısıysa - kodunu döndür. Aksi takdirde -1 döndür. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Bu tanımlanabilir nesnenin tanımlayıcısı. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Doğrusal parametreler için kullanılan birim. |
| ad | string | r | Bu nesnenin adı. |
| parameters_names | System.Collections.Generic.IList<string> | r | Bu projeksiyona verilen parametre adlarının bir enumerable koleksiyonunu alır |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Bu projeksiyonun belirtilen adındaki parametresini alır. |
| [is_equivalent(other)](#is_equivalent_other_2) | İki projeksiyonun eşdeğer olup olmadığını belirler. Eşdeğer projeksiyonlar (boylam, enlem) koordinatlarını (x, y) koordinatlarına aynı şekilde haritalar.<br/>             |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Bu projeksiyonun belirtilen adındaki parametresini alır. Böyle bir parametre yoksa - <see langword=\"null\" /> döndürür. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Bu projeksiyonun belirtilen adındaki parametresini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Parametrenin adı. |
