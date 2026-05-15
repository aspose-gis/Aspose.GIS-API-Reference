---
title: "GeoGenerator.ProduceStars"
second_title: "Aspose.GIS for .NET API 参考"
description: "GeoGenerator 方法。创建一个星形数组，所有星形都位于给定范围内"
type: docs
weight: 40
url: /zh/net/aspose.gis.geotools/geogenerator/producestars/
---
## GeoGenerator.ProduceStars method

创建一个星形数组，所有星形都位于给定范围内。

```csharp
public static IEnumerable<IPolygon> ProduceStars(Extent rect, StarGeneratorOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Extent | 指定区域（参见 [`Extent`](../../../aspose.gis/extent/)） |
| options | StarGeneratorOptions | 多边形创建选项（参见 [`StarGeneratorOptions`](../../stargeneratoroptions/)） |

### 返回值

星形数组（参见 [`IPolygon`](../../../aspose.gis.geometries/ipolygon/) 的枚举）

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 星形数量必须大于 1。 |
| NullReferenceException | Extent 必须有值（不能为空） |
| ArgumentException | 最小长度和最大长度必须不相等且大于 3 |
| ArgumentException | 最大长度必须大于最小长度 |

### 另见

* interface [IPolygon](../../../aspose.gis.geometries/ipolygon/)
* class [Extent](../../../aspose.gis/extent/)
* class [StarGeneratorOptions](../../stargeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


