---
title: "LineString.LineString"
second_title: "Aspose.GIS for .NET API 参考"
description: "LineString 构造函数。初始化 LineString 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.gis.geometries/linestring/linestring/
---
## LineString() {#constructor}

初始化 [`LineString`](../) 类的新实例。

```csharp
public LineString()
```

### 另见

* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)

---

## LineString(IEnumerable&lt;IPoint&gt;) {#constructor_2}

初始化 [`LineString`](../) 类的新实例。

```csharp
public LineString(IEnumerable<IPoint> collection)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 集合 | IEnumerable`1 | 点的集合。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 任意点为空（其 [`IsEmpty`](../../igeometry/isempty/) 为 `true`）。 |

### 另见

* interface [IPoint](../../ipoint/)
* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)

---

## LineString(ILineString) {#constructor_1}

初始化 [`LineString`](../) 类的新实例。

```csharp
public LineString(ILineString other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | ILineString | 要从中复制数据的另一条线。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* interface [ILineString](../../ilinestring/)
* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)


