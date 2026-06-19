---
title: "类 Identifier"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.SpatialReferencing.Identifier 类。表示标识符——对象的外部描述引用。如果从 WKT 创建 SRS，Identifier 对应于 AUTHORITY 关键字"
type: docs
weight: 4610
url: /zh/net/aspose.gis.spatialreferencing/identifier/
---
## Identifier class

表示标识符——对象的外部描述引用。如果从 WKT 创建 SRS，`Identifier` 对应于 \"AUTHORITY\" 关键字。

```csharp
public class Identifier : IEquatable<Identifier>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Identifier](identifier/)(string, string) | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AuthorityName](../../aspose.gis.spatialreferencing/identifier/authorityname/) { get; } | 一个授权机构的名称，提供了[`AuthorityUniqueIdentifier`](./authorityuniqueidentifier/)。 |
| [AuthorityUniqueIdentifier](../../aspose.gis.spatialreferencing/identifier/authorityuniqueidentifier/) { get; } | 一种在[`AuthorityName`](./authorityname/) 中表示对象的唯一方式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Epsg](../../aspose.gis.spatialreferencing/identifier/epsg/)(int) | 创建一个新的 Identifier，表示代码为 *epsgCode* 的 EPSG 标识符。 |
| [Equals](../../aspose.gis.spatialreferencing/identifier/equals/#equals)(Identifier) | 指示当前对象是否等于同类型的另一个对象。 |
| override [Equals](../../aspose.gis.spatialreferencing/identifier/equals/#equals_1)(object) | 确定指定的对象是否等于当前对象。 |
| [GetEpsgCode](../../aspose.gis.spatialreferencing/identifier/getepsgcode/)() | 如果此对象表示有效的 EPSG 标识符（例如——授权机构名称为 \"EPSG\" 且授权唯一标识符为整数），则返回它。否则返回 -1。 |
| override [GetHashCode](../../aspose.gis.spatialreferencing/identifier/gethashcode/)() | 用作默认的哈希函数。 |
| [operator ==](../../aspose.gis.spatialreferencing/identifier/op_equality/) | 实现运算符 ==。 |
| [operator !=](../../aspose.gis.spatialreferencing/identifier/op_inequality/) | 实现运算符 !=。 |

## 示例

WGS 84 空间参考系统的 EPSG 代码为 4326，因此它可能包含标识符：

```csharp
new  {  = "EPSG",  = 4326 };
```

WGS 84 椭球体的 EPSG 代码为 7030，可能包含标识符：

```csharp
new  {  = "EPSG",  = 7030 };
```

### 另见

* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


