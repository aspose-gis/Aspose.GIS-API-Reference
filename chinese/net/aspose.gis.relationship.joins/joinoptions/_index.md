---
title: "类 JoinOptions"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Relationship.Joins.JoinOptions 类。图层连接的选项"
type: docs
weight: 3930
url: /zh/net/aspose.gis.relationship.joins/joinoptions/
---
## JoinOptions class

图层连接的选项。

```csharp
public class JoinOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [JoinOptions](joinoptions/)() | 创建一个新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ConditionComparer](../../aspose.gis.relationship.joins/joinoptions/conditioncomparer/) { get; set; } | 通过指定用于比较特征值的逻辑，定义在查询中两个图层的要素之间的关联方式。 |
| [JoinAttributeName](../../aspose.gis.relationship.joins/joinoptions/joinattributename/) { get; set; } | 指定已连接图层的属性名称，其值将用于[`ConditionComparer`](./conditioncomparer/)。 |
| [JoinAttributeNames](../../aspose.gis.relationship.joins/joinoptions/joinattributenames/) { get; set; } | 指定要连接的属性名称列表。如果为`null`或为空，则将连接已连接图层的所有属性。 |
| [JoinedAttributesPrefix](../../aspose.gis.relationship.joins/joinoptions/joinedattributesprefix/) { get; set; } | 指定已连接属性名称的前缀字符串。默认是"joined_"。 |
| [TargetAttributeName](../../aspose.gis.relationship.joins/joinoptions/targetattributename/) { get; set; } | 指定主图层的属性名称，其值将用于[`ConditionComparer`](./conditioncomparer/)。 |

### 另见

* namespace [Aspose.Gis.Relationship.Joins](../../aspose.gis.relationship.joins/)
* assembly [Aspose.GIS](../../)


