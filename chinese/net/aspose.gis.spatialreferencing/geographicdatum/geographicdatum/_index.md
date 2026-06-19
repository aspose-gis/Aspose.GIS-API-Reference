---
title: "GeographicDatum.GeographicDatum"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "GeographicDatum 构造函数。创建新实例"
type: docs
weight: 10
url: /zh/net/aspose.gis.spatialreferencing/geographicdatum/geographicdatum/
---
## GeographicDatum constructor

创建新实例。

```csharp
public GeographicDatum(string name, Ellipsoid ellipsoid, 
    BursaWolfParameters toWgs84Parameters = null, Identifier identifier = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | 字符串 | 此基准面的名称。 |
| 椭球体 | Ellipsoid | 此基准面的椭球体。不能为空。 |
| toWgs84Parameters | BursaWolfParameters | 可提供给 bursa wolf 公式的参数，用于将此基准面的坐标转换为 WGS84 基准面的坐标。如果此基准面接近 WGS84 且不需要转换，则传入所有值为 0 的 bursa wolf 参数。如果为 null，ToWgs84 将被设置为 [`IsNull`](../../bursawolfparameters/isnull/) 参数。 |
| 标识符 | 标识符 | 此基准面的标识符。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 椭球体为 null。 |

### 另见

* class [Ellipsoid](../../ellipsoid/)
* class [BursaWolfParameters](../../bursawolfparameters/)
* class [Identifier](../../identifier/)
* class [GeographicDatum](../)
* namespace [Aspose.Gis.SpatialReferencing](../../geographicdatum/)
* assembly [Aspose.GIS](../../../)


