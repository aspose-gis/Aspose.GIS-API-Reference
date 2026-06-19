---
title: "Dataset.EditLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Dataset 方法。打开具有指定名称的图层以进行编辑"
type: docs
weight: 90
url: /zh/net/aspose.gis/dataset/editlayer/
---
## Dataset.EditLayer method

以编辑模式打开具有指定名称的图层。

```csharp
public abstract VectorLayer EditLayer(string name, DriverOptions options = null, 
    SpatialReferenceSystem spatialReferenceSystem = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | 字符串 | 要编辑的图层名称。 |
| options | DriverOptions | 打开选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 新几何体的空间参考系统。 |

### 返回值

已打开用于编辑的图层。

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
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


