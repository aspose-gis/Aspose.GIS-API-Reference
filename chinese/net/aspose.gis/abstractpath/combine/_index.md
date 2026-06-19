---
title: "AbstractPath.Combine"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "AbstractPath 方法。将此 AbstractPath 与指定的路径组件组合"
type: docs
weight: 50
url: /zh/net/aspose.gis/abstractpath/combine/
---
## AbstractPath.Combine method

将此 [`AbstractPath`](../) 与指定的路径组件组合。

```csharp
public virtual AbstractPath Combine(string location)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| location | String | 要追加到此 [`AbstractPath`](../) 的路径组件。 |

### 返回值

一个新的 [`AbstractPath`](../)，指向一个 [`Location`](../location/)，该位置是此 [`AbstractPath`](../) 与参数的位置的组合。

## 备注

通常不应在子类中重写此方法。默认实现将此 [`Location`](../location/) 与参数连接起来，并使用连接后的字符串作为参数调用 [`WithLocation`](../withlocation/) 方法。组合结果的定义如下：如果参数以 [`Separator`](../separator/) 开头，组合结果等于该参数；否则，如果 [`Location`](../location/) 以 [`Separator`](../separator/) 结尾，组合结果等于 ` + `；否则，结果等于 ` + + `。

### 另见

* class [AbstractPath](../)
* namespace [Aspose.Gis](../../abstractpath/)
* assembly [Aspose.GIS](../../../)


