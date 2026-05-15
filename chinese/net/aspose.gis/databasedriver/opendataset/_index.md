---
title: "DatabaseDriver.OpenDataset"
second_title: "Aspose.GIS for .NET API 参考"
description: "DatabaseDriver 方法。打开数据集。"
type: docs
weight: 10
url: /zh/net/aspose.gis/databasedriver/opendataset/
---
## DatabaseDriver.OpenDataset method

打开数据集。

```csharp
public abstract Dataset OpenDataset(IDbConnection connection)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 连接 | IDbConnection | 已打开到数据库的连接。 |

### 返回值

一个 [`Dataset`](../../dataset/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 连接为 `null`。 |
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [Dataset](../../dataset/)
* class [DatabaseDriver](../)
* namespace [Aspose.Gis](../../databasedriver/)
* assembly [Aspose.GIS](../../../)


