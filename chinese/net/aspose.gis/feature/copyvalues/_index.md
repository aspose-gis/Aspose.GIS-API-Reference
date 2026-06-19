---
title: "Feature.CopyValues"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Feature 方法。复制另一个要素的属性值"
type: docs
weight: 20
url: /zh/net/aspose.gis/feature/copyvalues/
---
## Feature.CopyValues method

从另一个要素复制属性值。

```csharp
public void CopyValues(Feature inputFeature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputFeature | Feature | 要从中复制值的要素。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| InvalidOperationException | 该属性未锁定。 |
| InvalidOperationException | 输入值为 null，而此要素中的属性不能为 null。 |
| [GisException](../../gisexception/) | 属性在特性中具有相同的名称但不同的数据类型。 |

## 备注

此方法仅复制名称匹配的属性。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


