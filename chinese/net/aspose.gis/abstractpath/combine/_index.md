---
title: Combine
second_title: Aspose.GIS for .NET API 参考
description: 将此AbstractPathaspose.gis/abstractpath与指定的路径组件组合
type: docs
weight: 50
url: /zh/net/aspose.gis/abstractpath/combine/
---
## AbstractPath.Combine method

将此[`AbstractPath`](../../abstractpath)与指定的路径组件组合。

```csharp
public virtual AbstractPath Combine(string location)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| location | String | 附加到此[`AbstractPath`](../../abstractpath)的路径组件。 |

### 返回值

一个新的[`AbstractPath`](../../abstractpath)指向[`Location`](../location)是这个[`AbstractPath`](../../abstractpath)和 参数的位置组合。

### 评论

通常此方法不应被继承者覆盖。默认实现 将此[`Location`](../location)与参数连接并调用[`WithLocation`](../withlocation) 方法，将连接的字符串作为参数。&lt;cr /&gt; 组合结果定义如下: &lt;ul&gt;&lt;li&gt;如果参数以[`Separator`](../separator)开头，则组合结果等于参数；&lt;/li&gt;&lt;li&gt;否则，如果[`Location`](../location)以[`Separator`](../separator)结尾， 组合结果等于`+` ;&lt;/li&gt;&lt;li&gt;否则，结果等于`++` &lt;/li&gt;&lt;/ul&gt;

### 也可以看看

* class [AbstractPath](../../abstractpath)
* 命名空间 [Aspose.Gis](../../abstractpath)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
