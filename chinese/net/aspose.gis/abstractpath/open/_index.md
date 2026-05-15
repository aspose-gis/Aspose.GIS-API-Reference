---
title: "AbstractPath.Open"
second_title: "Aspose.GIS for .NET API 参考"
description: "AbstractPath 方法。将此 AbstractPath 作为文件打开"
type: docs
weight: 120
url: /zh/net/aspose.gis/abstractpath/open/
---
## AbstractPath.Open method

将此 `AbstractPath` 作为文件打开。

```csharp
public abstract Stream Open(FileAccess access)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 访问 | FileAccess | 指定可以在 Stream 上执行的操作子集。 |

### 返回值

使用指定的 FileAccess 打开的 Stream。

## 备注

如果 *access* 设置了 Write 标志，并且文件不存在，继承者必须创建它。`AbstractPath` 可以被 `Aspose.GIS` 多次打开。这是为了能够使用多个流独立读取文件所必需的。您不应缓存结果，而应在每次调用此方法时返回新的 Stream。

### 另见

* class [AbstractPath](../)
* namespace [Aspose.Gis](../../abstractpath/)
* assembly [Aspose.GIS](../../../)


