---
title: "CompoundSpatialReferenceSystem 类"
type: docs
weight: 30
url: /zh/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/
---

**Summary:** Compound SRS unites two underlying SRS, none of which can be compound.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.CompoundSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | 返回此。 |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | 返回将此 SRS 转换为 [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) 的结果。<br/>            使用 [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 来判断是否可以进行转换。 |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | 返回此 SRS 的地理表示。如果此复合 SRS 确实表示地理 SRS，则结果将<br/>            为三维地理 SRS（具有经度、纬度、高度维度）。否则将抛出异常。 |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | 返回此 SRS 转换为 [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/)。<br/>            使用 [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 来判断是否可以进行转换。 |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | 返回此 SRS 的投影表示。如果此复合 SRS 确实表示投影 SRS，则结果将<br/>            为三维投影 SRS（具有 X、Y、高度维度）。否则将抛出异常。 |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | 返回此 SRS 转换为 [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/)。<br/>            使用 [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 来判断是否可以进行转换。 |
| dimensions_count | int | r | 维度数量。对于复合 SRS，这等于底层 SRS 的维度数量之和。 |
| epsg_code | int | r | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) 空间参考系统。 |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert Azimuthal Equal Area (EPSG:3035) 空间参考系统。 |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert Conformal Conic (EPSG:3034) 空间参考系统。 |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | 返回此 SRS 的地理基准。<br/>            如果 [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) 和 [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) 都具有地理基准 - 返回头部的地理基准。 |
| has_geographic_datum | bool | r | 如果任意底层 SRS 具有地理基准，则 Compound SRS 具有地理基准。 |
| has_prime_meridian | bool | r | 如果任意底层 SRS 具有本初子午线，则 Compound SRS 具有本初子午线。 |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | 第一个底层 SRS。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | 此可识别对象的标识符。 |
| is_compound | bool | r | 返回 <see langword="true" />。 |
| is_single | bool | r | 返回此 SRS 是否为单一（不是两个 SRS 的联合）。 |
| is_valid | bool | r | 与 <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> 相同，但不返回错误信息。 |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) 空间参考系统。 |
| 名称 | string | r | 此对象的名称。 |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) 空间参考系统。 |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / British National Grid (EPSG:27700) 空间参考系统。 |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | 返回此 SRS 的本初子午线。<br/>            如果 [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) 和 [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) 都具有本初子午线 - 返回头部的本初子午线。 |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | 第二个底层 SRS。 |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | 此 Compound SRS 的类型。可以是 [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/)，如果<br/>            此 Compound SRS 是地理和垂直 SRS 的组合，或 [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/)，如果<br/>            此 Compound SRS 是投影和垂直 SRS 的组合。 |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Web Mercator (EPSG:3857) 空间参考系统。 |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 72 (EPSG:4322) 空间参考系统。 |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 84 (EPSG:4326) 空间参考系统。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | 创建复合 SRS。 |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | 基于指定的 EPSG 代码创建空间参考系统。 |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | 基于 WKT（Well-Known Text）字符串创建一个新的 <c>SpatialReferenceSystem</c>。 |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | 从自定义参数创建地心 SRS。 |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | 从自定义参数创建地理 SRS。 |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | 创建本地空间参考系统。 |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | 从自定义参数创建投影 SRS。 |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | 创建从此 <c>SpatialReferenceSystem</c> 到另一个 <c>SpatialReferenceSystem</c> 的转换。 |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | 创建垂直 SRS。 |
| [export_to_wkt()](#export_to_wkt__10) | 返回此 SRS 的 WKT 字符串表示。<br/>            结果 WKT 字符串将符合 OGC 01-009 规范，通常命名为 "WKT1"。 |
| [get_axis(dimension)](#get_axis_dimension_11) | 获取描述维度的 [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/)。 |
| [get_unit(dimension)](#get_unit_dimension_12) | 获取维度的 [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/)。 |
| [is_equivalent(other)](#is_equivalent_other_13) | 检测此 SRS 是否等价于其他 SRS。 [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)。 |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | 确定两个 SRS 是否等价。<br/>            等价 SRS 的相同坐标对应地球上的同一位置。<br/>            等价 SRS 的某些参数可能不同，例如 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/)。 |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | 基于指定的 EPSG 代码创建空间参考系统。 |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | 基于 WKT（Well-Known Text）字符串创建一个新的 <c>SpatialReferenceSystem</c>。 |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | 创建从此 <c>SpatialReferenceSystem</c> 到另一个 <c>SpatialReferenceSystem</c> 的转换。 |
| [validate(error_message)](#validate_error_message_18) | 确定此 SRS 是否有效。参见 <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" /> 获取有效性描述。 |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

创建复合 SRS。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 新 SRS 的名称。 |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 新 SRS 的头部 SRS。 |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 新 SRS 的尾部 SRS。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。<br/>            您需要确保标识符与 SRS 参数的一致性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | 新复合 SRS。 |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

基于指定的 EPSG 代码创建空间参考系统。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| epsg | int | 空间参考系统的 EPSG 代码。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 使用指定 EPSG 代码的新空间参考系统。 |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

基于 WKT（Well-Known Text）字符串创建一个新的 <c>SpatialReferenceSystem</c>。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| wkt | string | WKT 字符串。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 新的 <c>SpatialReferenceSystem</c>。 |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

从自定义参数创建地心 SRS。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | 用于创建的参数。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。<br/>            您需要确保标识符与 SRS 参数的一致性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | 新的地心 SRS。 |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

从自定义参数创建地理 SRS。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | 用于创建的参数。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。<br/>            您需要确保标识符与 SRS 参数的一致性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | 新的地理 SRS。 |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

创建本地空间参考系统。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 空间参考系统的名称。 |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | SRS 中使用的基准面。 |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS 中使用的单位。 |
| 轴 | System.Collections.Generic.ICollection<Axis> | SRS 中使用的轴。必须非空 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。<br/>            您需要确保标识符与 SRS 参数的一致性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | 新的本地空间参考系统。 |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

从自定义参数创建投影 SRS。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | 用于创建的参数。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。<br/>            您需要确保标识符与 SRS 参数的一致性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | 新的投影 SRS。 |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

创建从此 <c>SpatialReferenceSystem</c> 到另一个 <c>SpatialReferenceSystem</c> 的转换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 另一个 <c>SpatialReferenceSystem</c>。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | 从此 <c>SpatialReferenceSystem</c> 到另一个 <c>SpatialReferenceSystem</c> 的转换。 |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

创建垂直 SRS。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | SRS 的名称。如果 <see langword="null" />。 |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | SRS 中使用的基准面。 |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS 中使用的单位。如果 <see langword="null" />，将使用 [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/)。 |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | 具有 "up" 或 "down" 方向的轴，用于 SRS。如果 <see langword="null" />，将使用向上的轴。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 标识符，将附加到 SRS。附加标识符不会修改其他 SRS 参数。<br/>            您需要确保标识符与 SRS 参数的一致性。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | 新的垂直 SRS。 |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

返回此 SRS 的 WKT 字符串表示。<br/>            结果 WKT 字符串将符合 OGC 01-009 规范，通常命名为 "WKT1"。

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 此 SRS 的 WKT 表示。 |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

获取描述维度的 [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 维度 | int | 维度的数量。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | 描述维度的轴。 |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

获取维度的 [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 维度 | int | 维度的数量。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | 维度单位。 |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

检测此 SRS 是否等价于其他 SRS。 [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 其他 SRS。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | bool 值，指示此 SRS 是否等同于其他 SRS。 |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

确定两个 SRS 是否等价。<br/>            等价 SRS 的相同坐标对应地球上的同一位置。<br/>            等价 SRS 的某些参数可能不同，例如 [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 第一个 SRS。 |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 第二个 SRS。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | bool 值，指示两个 SRS 是否等价。 |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

基于指定的 EPSG 代码创建空间参考系统。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| epsg | int | 空间参考系统的 EPSG 代码。 |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 当此方法返回 <see langword="true" /> 时，包含具有指定 EPSG 代码的 SRS；否则，<br/>            包含 <see langword="null" />。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword="true" /> 如果已知指定的 EPSG 代码且已创建 SRS；<see langword="false" /> 否则。 |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

基于 WKT（Well-Known Text）字符串创建一个新的 <c>SpatialReferenceSystem</c>。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| wkt | string | WKT 字符串。 |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 当此方法返回 <see langword="true" /> 时，包含由 WKT 创建的 SRS；否则，<br/>            包含 <see langword="null" />。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword="true" /> 如果成功创建了 SRS；<see langword="false" /> 否则。 |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

创建从此 <c>SpatialReferenceSystem</c> 到另一个 <c>SpatialReferenceSystem</c> 的转换。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 另一个 <c>SpatialReferenceSystem</c>。 |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | 当此方法返回 <see langword="true" /> 时，包含一个转换；否则，包含 <see langword="null" />。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 从此 <c>SpatialReferenceSystem</c> 到另一个 <c>SpatialReferenceSystem</c> 的转换。 |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

确定此 SRS 是否有效。参见 <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" /> 获取有效性描述。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| error_message | 字符串 | 无效性的描述（如果结果为 <see langword="false" />） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果此 SRS 有效 - <see langword="true" />，否则 - <see langword="false" />。 |


