---
title: "JoinOptions.ConditionComparer"
second_title: "Aspose.GIS for .NET API 参考"
description: "JoinOptions 属性。通过指定用于比较要素值的逻辑，定义查询中两个图层要素之间的关联方式"
type: docs
weight: 20
url: /zh/net/aspose.gis.relationship.joins/joinoptions/conditioncomparer/
---
## JoinOptions.ConditionComparer property

通过指定用于比较特征值的逻辑，定义查询中两个图层特征之间的关联方式。

```csharp
public IEqualityComparer<object> ConditionComparer { get; set; }
```

## 备注

默认情况下，它确定两个对象是否相等：

```csharp
EqualityComparer<object>.Default;  
```

### 另见

* class [JoinOptions](../)
* namespace [Aspose.Gis.Relationship.Joins](../../joinoptions/)
* assembly [Aspose.GIS](../../../)


