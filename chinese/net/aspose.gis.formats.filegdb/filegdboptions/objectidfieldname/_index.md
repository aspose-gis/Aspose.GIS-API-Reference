---
title: "FileGdbOptions.ObjectIdFieldName"
second_title: "Aspose.GIS for .NET API 参考"
description: "FileGdbOptions 属性。对象 ID 字段的名称"
type: docs
weight: 90
url: /zh/net/aspose.gis.formats.filegdb/filegdboptions/objectidfieldname/
---
## FileGdbOptions.ObjectIdFieldName property

对象 ID 字段的名称。

```csharp
public string ObjectIdFieldName { get; set; }
```

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 值不是有效的字段名称。有效的字段名称必须：不是 `null` 且不为空；以拉丁字母或下划线开头；仅包含拉丁字母、数字或下划线 |

## 备注

这是一个创建选项，不影响读取和编辑。定义对象 ID 字段（列）的名称。默认值为 "OBJECTID"。如果 [`Attributes`](../../../aspose.gis/vectorlayer/attributes/) 中的任何属性名称等于此属性的值，则该属性将被重命名。

### 另见

* class [FileGdbOptions](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdboptions/)
* assembly [Aspose.GIS](../../../)


