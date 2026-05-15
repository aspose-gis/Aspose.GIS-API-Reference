---
title: "Feature.IsValueSet"
second_title: "Aspose.GIS for .NET API 参考"
description: "Feature 方法。检查此特性中是否已设置属性值"
type: docs
weight: 90
url: /zh/net/aspose.gis/feature/isvalueset/
---
## Feature.IsValueSet method

检查此特性中是否已设置属性值。

```csharp
public bool IsValueSet(string attributeName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeName | String | 属性的名称。 |

### 返回值

`true` 如果已为指定属性设置值；否则为 `false`。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 属性未被锁定。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| ArgumentNullException | 属性名称为 `null`。 |

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


