---
title: "Feature.SetValueNull"
second_title: "Aspose.GIS for .NET API 参考"
description: "Feature 方法。将属性的值设为 null"
type: docs
weight: 110
url: /zh/net/aspose.gis/feature/setvaluenull/
---
## Feature.SetValueNull method

将属性的值设置为 `null`。

```csharp
public void SetValueNull(string attributeName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeName | String | 属性的名称。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 属性未被锁定。 |
| InvalidOperationException | 此属性的值不能为 Null。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| ArgumentNullException | 属性名称为 `null`。 |

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


