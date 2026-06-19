---
title: "AbstractPath.GetFileName"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "AbstractPath method. 返回此 AbstractPath 的文件名和扩展名。"
type: docs
weight: 80
url: /zh/net/aspose.gis/abstractpath/getfilename/
---
## AbstractPath.GetFileName method

返回此 [`AbstractPath`](../) 的文件名和扩展名。

```csharp
public string GetFileName()
```

### 返回值

在 [`Location`](../location/) 中最后一个 [`Separator`](../separator/) 字符之后的字符。如果最后一个字符是 [`Separator`](../separator/) 字符，则返回空字符串。如果 [`Location`](../location/) 中没有 [`Separator`](../separator/) 字符，则返回 [`Location`](../location/) 本身。

## 示例

对于 `AbstractPath`，其 [`Location`](../location/) 等于 \"/directory/file.txt\" 且 [`Separator`](../separator/) 等于 '/'，此方法返回 \"file.txt\"。

### 另见

* class [AbstractPath](../)
* namespace [Aspose.Gis](../../abstractpath/)
* assembly [Aspose.GIS](../../../)


