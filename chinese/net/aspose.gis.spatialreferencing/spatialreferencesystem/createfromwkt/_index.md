---
title: CreateFromWkt
second_title: Aspose.GIS for .NET API 参考
description: 基于 WKT众所周知的文本字符串创建一个新的 SpatialReferenceSystem 
type: docs
weight: 20
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystem/createfromwkt/
---
## SpatialReferenceSystem.CreateFromWkt method

基于 WKT（众所周知的文本）字符串创建一个新的` SpatialReferenceSystem` 。

```csharp
public static SpatialReferenceSystem CreateFromWkt(string wkt)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| wkt | String | WKT 字符串。 |

### 返回值

新` SpatialReferenceSystem` 。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 参数是`null`。 |
| FormatException | wkt 值的层次结构、它们的顺序或类型是错误的。 |
| NotSupportedException | WKT 根元素不受支持（例如它是 FITTED_CS）。 |

### 也可以看看

* class [SpatialReferenceSystem](../../spatialreferencesystem)
* 命名空间 [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->