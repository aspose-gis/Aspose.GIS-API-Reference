---
title: "Dataset.OpenLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Dataset 方法。打开具有指定名称的图层以进行读取"
type: docs
weight: 130
url: /zh/net/aspose.gis/dataset/openlayer/
---
## Dataset.OpenLayer method

以读取模式打开具有指定名称的图层。

```csharp
public abstract VectorLayer OpenLayer(string name, DriverOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | 字符串 | 要打开的图层名称。 |
| options | DriverOptions | 打开选项。 |

### 返回值

已打开用于读取的图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 具有指定名称的图层不存在；Options 对象对该 Dataset 的类型不正确。 |
| ArgumentException | Options 对象对该 Dataset 的类型不正确。 |
| ArgumentNullException | 名称为 `null`。 |
| [GisException](../../gisexception/) | 读取图层要素时出错。 |
| IOException | 发生了 I/O 错误。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


