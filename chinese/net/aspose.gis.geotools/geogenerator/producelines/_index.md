---
title: "GeoGenerator.ProduceLines"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "GeoGenerator 方法。创建一个新的 ILineString 枚举器，包含给定数量的随机项，所有项都位于给定范围内"
type: docs
weight: 10
url: /zh/net/aspose.gis.geotools/geogenerator/producelines/
---
## GeoGenerator.ProduceLines method

创建一个新的 ILineString 枚举器，包含指定数量的随机项，所有项都位于给定范围内。

```csharp
public static IEnumerable<ILineString> ProduceLines(Extent rect, LineGeneratorOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rect | Extent | 指定区域（参见 [`Extent`](../../../aspose.gis/extent/)） |
| options | LineGeneratorOptions | 线创建选项（参见 [`LineGeneratorOptions`](../../linegeneratoroptions/)） |

### 返回值

线数组（参见 [`ILineString`](../../../aspose.gis.geometries/ilinestring/) 的枚举）

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 线的数量必须大于1。 |
| NullReferenceException | Extent 必须有值（不能为 NULL） |

### 另见

* interface [ILineString](../../../aspose.gis.geometries/ilinestring/)
* class [Extent](../../../aspose.gis/extent/)
* class [LineGeneratorOptions](../../linegeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


