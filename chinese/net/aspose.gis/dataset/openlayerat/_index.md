---
title: "Dataset.OpenLayerAt"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Dataset 方法。打开指定索引处的图层以进行读取"
type: docs
weight: 140
url: /zh/net/aspose.gis/dataset/openlayerat/
---
## Dataset.OpenLayerAt method

以读取模式打开指定索引处的图层。

```csharp
public abstract VectorLayer OpenLayerAt(int index, DriverOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 要打开的图层索引。 |
| options | DriverOptions | 打开选项。 |

### 返回值

已打开用于读取的图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象对该 Dataset 的类型不正确。 |
| ArgumentOutOfRangeException | 索引超出范围 |
| ArgumentException | Options 对象对该 Dataset 的类型不正确。 |
| [GisException](../../gisexception/) | 读取图层要素时出错。 |
| IOException | 发生了 I/O 错误。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


