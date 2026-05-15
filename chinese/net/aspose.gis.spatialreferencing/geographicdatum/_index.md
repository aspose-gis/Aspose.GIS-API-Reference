---
title: "类 GeographicDatum"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.SpatialReferencing.GeographicDatum 类。地理基准将经度和纬度关联到地球上的特定位置。"
type: docs
weight: 4570
url: /zh/net/aspose.gis.spatialreferencing/geographicdatum/
---
## GeographicDatum class

地理基准将经度和纬度关联到地球上的特定位置。

```csharp
public class GeographicDatum : IdentifiableObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [GeographicDatum](geographicdatum/)(string, Ellipsoid, BursaWolfParameters, Identifier) | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Etrs89](../../aspose.gis.spatialreferencing/geographicdatum/etrs89/) { get; } | ETRS 89 基准。 |
| static [Nad83](../../aspose.gis.spatialreferencing/geographicdatum/nad83/) { get; } | NAD 83 基准。 |
| static [Osgb36](../../aspose.gis.spatialreferencing/geographicdatum/osgb36/) { get; } | OSGB 1936 基准。 |
| static [Wgs72](../../aspose.gis.spatialreferencing/geographicdatum/wgs72/) { get; } | WGS 72 基准。 |
| static [Wgs84](../../aspose.gis.spatialreferencing/geographicdatum/wgs84/) { get; } | WGS 84 基准。 |
| [Ellipsoid](../../aspose.gis.spatialreferencing/geographicdatum/ellipsoid/) { get; } | 椭球体，用于此基准以近似地球。 |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | 此可识别对象的标识符。 |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | 此对象的名称。 |
| [ToWgs84Parameters](../../aspose.gis.spatialreferencing/geographicdatum/towgs84parameters/) { get; } | BursaWolfParamters，可用于将此基准中的坐标转换为 WGS84 基准中的坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [IsEquivalent](../../aspose.gis.spatialreferencing/geographicdatum/isequivalent/)(GeographicDatum) | 确定两个基准是否等价。等价基准的相同坐标对应地球上的同一位置。等价基准的某些参数可能不同，例如 [`Name`](../identifiableobject/name/)。 |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | 返回表示当前对象的字符串。 |
| static [IsEquivalent](../../aspose.gis.spatialreferencing/geographicdatum/isequivalent/)(GeographicDatum, GeographicDatum) | 确定两个基准是否等价。等价基准的相同坐标对应地球上的同一位置。等价基准的某些参数可能不同，例如 [`Name`](../identifiableobject/name/)。 |

### 另见

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


