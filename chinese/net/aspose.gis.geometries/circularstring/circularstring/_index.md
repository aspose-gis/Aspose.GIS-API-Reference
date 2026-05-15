---
title: "CircularString.CircularString"
second_title: "Aspose.GIS for .NET API 参考"
description: "CircularString 构造函数。初始化 CircularString 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.gis.geometries/circularstring/circularstring/
---
## CircularString() {#constructor}

初始化 [`CircularString`](../) 类的新实例。

```csharp
public CircularString()
```

### 另见

* class [CircularString](../)
* namespace [Aspose.Gis.Geometries](../../circularstring/)
* assembly [Aspose.GIS](../../../)

---

## CircularString(IEnumerable&lt;IPoint&gt;) {#constructor_2}

初始化 [`CircularString`](../) 类的新实例。

```csharp
public CircularString(IEnumerable<IPoint> collection)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 集合 | IEnumerable`1 | 点的集合。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| InvalidOperationException | 任意点为空（其 [`IsEmpty`](../../igeometry/isempty/) 为 `true`）。 |

### 另见

* interface [IPoint](../../ipoint/)
* class [CircularString](../)
* namespace [Aspose.Gis.Geometries](../../circularstring/)
* assembly [Aspose.GIS](../../../)

---

## CircularString(ICircularString) {#constructor_1}

初始化 [`CircularString`](../) 类的新实例。

```csharp
public CircularString(ICircularString other)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | ICircularString | 要从中复制数据的另一个字符串。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* interface [ICircularString](../../icircularstring/)
* class [CircularString](../)
* namespace [Aspose.Gis.Geometries](../../circularstring/)
* assembly [Aspose.GIS](../../../)


