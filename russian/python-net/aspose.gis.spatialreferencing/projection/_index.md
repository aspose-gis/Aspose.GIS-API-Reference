---
title: "Класс Projection"
type: docs
weight: 170
url: /ru/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Единица, используемая для угловых параметров. |
| epsg_code | int | r | Если идентификатор этого объекта является EPSG‑идентификатором — вернуть его код. В противном случае — вернуть -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Идентификатор этого идентифицируемого объекта. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Единица, используемая для линейных параметров. |
| имя | string | r | Имя этого объекта. |
| parameters_names | System.Collections.Generic.IList<string> | r | Получает перечисляемую коллекцию имен параметров, переданных этой проекции. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Получает параметр с указанным именем этой проекции. |
| [is_equivalent(other)](#is_equivalent_other_2) | Определяет, являются ли две проекции эквивалентными. Эквивалентные проекции отображают (longitude, latitude) в (x, y) в <br/>            том же самом порядке. |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Получает параметр с указанным именем этой проекции. Если такого параметра нет — возвращает <see langword="null" />. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Получает параметр с указанным именем этой проекции.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя параметра. |
