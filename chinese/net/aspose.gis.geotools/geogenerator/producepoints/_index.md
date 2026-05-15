---
title: "GeoGenerator.ProducePoints"
second_title: "Aspose.GIS for .NET API 参考"
description: "GeoGenerator 方法。创建一个点数组，属于指定区域"
type: docs
weight: 20
url: /zh/net/aspose.gis.geotools/geogenerator/producepoints/
---
## GeoGenerator.ProducePoints method

创建一个属于指定区域的点数组。

```csharp
public static IEnumerable<IGeometry> ProducePoints(Extent rect, PointGeneratorOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Extent | 指定区域（参见 [`Extent`](../../../aspose.gis/extent/)）。 |
| options | PointGeneratorOptions | 点创建选项（参见 [`PointGeneratorOptions`](../../pointgeneratoroptions/)）。 |

### 返回值

点数组（参见 [`IGeometry`](../../../aspose.gis.geometries/igeometry/) 的枚举）。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 点的数量必须大于 1。 |
| NullReferenceException | Extent 必须有值（不能为空）。 |

### 另见

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [Extent](../../../aspose.gis/extent/)
* class [PointGeneratorOptions](../../pointgeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


