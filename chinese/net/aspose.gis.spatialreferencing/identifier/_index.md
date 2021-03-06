---
title: Identifier
second_title: Aspose.GIS for .NET API 参考
description: 表示标识符 - 对对象外部描述的引用 如果您从 WKT 创建 SRS则Identifier./identifier对应于AUTHORITY关键字
type: docs
weight: 2050
url: /zh/net/aspose.gis.spatialreferencing/identifier/
---
## Identifier class

表示标识符 - 对对象外部描述的引用。 如果您从 WKT 创建 SRS，则[`Identifier`](../identifier)对应于“AUTHORITY”关键字。

```csharp
public class Identifier : IEquatable<Identifier>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Identifier](identifier)(string, string) | 创建新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AuthorityName](../../aspose.gis.spatialreferencing/identifier/authorityname) { get; } | 权威名称，它给出了[`AuthorityUniqueIdentifier`](./authorityuniqueidentifier)。 |
| [AuthorityUniqueIdentifier](../../aspose.gis.spatialreferencing/identifier/authorityuniqueidentifier) { get; } | 在[`AuthorityName`](./authorityname)中表示对象的独特方式。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Epsg](../../aspose.gis.spatialreferencing/identifier/epsg)(int) | 使用代码*epsgCode*创建表示 EPSG 标识符的新标识符。 |
| [Equals](../../aspose.gis.spatialreferencing/identifier/equals#equals)(Identifier) | 表示当前对象是否等于另一个同类型的对象。 |
| override [Equals](../../aspose.gis.spatialreferencing/identifier/equals#equals_1)(object) | 判断指定对象是否等于当前对象。 |
| [GetEpsgCode](../../aspose.gis.spatialreferencing/identifier/getepsgcode)() | 如果此对象表示有效的 EPSG 标识符（例如 - 权限名称为“EPSG”且权限唯一标识符为整数） - 返回它。否则 - 返回 -1。 |
| override [GetHashCode](../../aspose.gis.spatialreferencing/identifier/gethashcode)() | 用作默认哈希函数。 |
| [operator ==](../../aspose.gis.spatialreferencing/identifier/op_equality) | 实现运算符 ==。 |
| [operator !=](../../aspose.gis.spatialreferencing/identifier/op_inequality) | 实现运算符 !=。 |

### 例子

WGS 84 空间参考系统具有 EPSG 代码 4326，因此它可能包含标识符: WGS 84 Ellipsoid 具有 EPSG 代码 7030，它可能包含标识符:

```csharp
new  {  = "EPSG",  = 4326 };
```

```csharp
new  {  = "EPSG",  = 7030 };
```

### 也可以看看

* 命名空间 [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
