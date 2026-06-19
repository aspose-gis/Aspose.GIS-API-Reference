---
title: "SpatialReferenceSystem.CreateFromWkt"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "SpatialReferenceSystem 方法。基于 WKT WellKnown Text 字符串创建一个新的 SpatialReferenceSystem"
type: docs
weight: 20
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/createfromwkt/
---
## SpatialReferenceSystem.CreateFromWkt method

基于 WKT（Well-Known Text）字符串创建新的 `SpatialReferenceSystem`。

```csharp
public static SpatialReferenceSystem CreateFromWkt(string wkt)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wkt | 字符串 | WKT 字符串。 |

### 返回值

新 `SpatialReferenceSystem`。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| FormatException | wkt 值的层次结构、顺序或类型错误。 |
| NotSupportedException | 不支持 WKT 根元素（例如它是 FITTED_CS）。 |

### 另见

* method [TryCreateFromWkt](../trycreatefromwkt/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


