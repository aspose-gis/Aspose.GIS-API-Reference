---
title: "GeographicDatum 类"
type: docs
weight: 70
url: /zh/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | 椭球体，用于此基准以近似地球。 |
| epsg_code | int | r | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | ETRS 89 基准。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 此可识别对象的标识符。 |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | NAD 83 基准。 |
| 名称 | string | r | 此对象的名称。 |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | OSGB 1936 基准。 |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | 可用于将此基准中的坐标转换为 WGS84 基准坐标的 BursaWolfParamters。 |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 72 基准。 |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 84 基准。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | 确定两个基准是否等价。<br/>            等价基准的相同坐标对应地球上的同一位置。<br/>            等价基准的某些参数可能不同，例如 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/)。 |
| [is_equivalent(other)](#is_equivalent_other_2) | 确定两个基准是否等价。<br/>            等价基准的相同坐标对应地球上的同一位置。<br/>            等价基准的某些参数可能不同，例如 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/)。 |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 此基准的名称。 |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | 此基准的椭球体。不能为空。 |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | 可提供给 bursa wolf 公式的参数，用于将此基准中的坐标转换为 WGS84 基准的坐标。<br/>            如果此基准接近 WGS84 且不需要转换，请传入所有值为 0 的 bursa wolf 参数。<br/>            如果为 null，ToWgs84 将被设置为 [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) 参数。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 此基准的标识符。 |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

确定两个基准是否等价。<br/>            等价基准的相同坐标对应地球上的同一位置。<br/>            等价基准的某些参数可能不同，例如 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | 第一个基准。 |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | 第二个基准。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 布尔值，指示两个基准是否等价。 |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

确定两个基准是否等价。<br/>            等价基准的相同坐标对应地球上的同一位置。<br/>            等价基准的某些参数可能不同，例如 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | 其他基准。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 布尔值，指示两个基准是否等价。 |


