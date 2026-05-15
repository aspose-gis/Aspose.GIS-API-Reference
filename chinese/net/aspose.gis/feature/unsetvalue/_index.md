---
title: "Feature.UnsetValue"
second_title: "Aspose.GIS for .NET API 参考"
description: "Feature 方法。从此特性中移除属性值"
type: docs
weight: 130
url: /zh/net/aspose.gis/feature/unsetvalue/
---
## Feature.UnsetValue method

从此特性中移除属性值。

```csharp
public void UnsetValue(string attributeName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeName | String | 属性的名称。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 属性未被锁定。 |
| InvalidOperationException | 此属性的值不能被取消设置。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| ArgumentNullException | 属性名称为 `null`。 |

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


