---
title: Open
second_title: Aspose.GIS for .NET API 参考
description: 打开这个 抽象路径 作为一个文件
type: docs
weight: 120
url: /zh/net/aspose.gis/abstractpath/open/
---
## AbstractPath.Open method

打开这个 `抽象路径` 作为一个文件。

```csharp
public abstract Stream Open(FileAccess access)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| access | FileAccess | 指定可以在 Stream. |

### 返回值

一个 Stream 以指定的方式打开 FileAccess.

### 评论

如果 *access* 有国旗 Write 设置，并且文件不存在， 继承者必须创建它。  一个 `抽象路径` 可以多次打开 `Aspose.GIS`. 这是读取文件所必需的 独立地与多个流。 您不应该缓存结果，而是返回新的 Stream 每次 调用此方法。

### 也可以看看

* class [AbstractPath](../../abstractpath)
* 命名空间 [Aspose.Gis](../../abstractpath)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
