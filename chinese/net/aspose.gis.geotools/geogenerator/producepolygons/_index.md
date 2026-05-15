---
title: "GeoGenerator.ProducePolygons"
second_title: "Aspose.GIS for .NET API 参考"
description: "GeoGenerator 方法。创建一个新的 IPolygon 枚举器，包含给定数量的随机项，所有项都位于给定范围内"
type: docs
weight: 30
url: /zh/net/aspose.gis.geotools/geogenerator/producepolygons/
---
## GeoGenerator.ProducePolygons method

创建一个新的 IPolygon 枚举器，包含指定数量的随机项，所有项都位于给定范围内。

```csharp
public static IEnumerable<IPolygon> ProducePolygons(Extent rect, PolygonGeneratorOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Extent | 指定区域（参见 [`Extent`](../../../aspose.gis/extent/)） |
| options | PolygonGeneratorOptions | 多边形创建选项（参见 [`PolygonGeneratorOptions`](../../polygongeneratoroptions/)） |

### 返回值

多边形数组（参见 [`IPolygon`](../../../aspose.gis.geometries/ipolygon/) 的枚举）

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 多边形的数量必须大于一。 |
| NullReferenceException | Extent 必须有值（不能为空） |
| ArgumentException | 最小长度和最大长度必须不相等且大于 0 |
| ArgumentException | 最大长度必须大于最小长度 |

### 另见

* interface [IPolygon](../../../aspose.gis.geometries/ipolygon/)
* class [Extent](../../../aspose.gis/extent/)
* class [PolygonGeneratorOptions](../../polygongeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


