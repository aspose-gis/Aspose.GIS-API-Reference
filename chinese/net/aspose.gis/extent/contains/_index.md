---
title: "Extent.Contains"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Extent 方法。确定此范围是否包含由参数定义的坐标"
type: docs
weight: 120
url: /zh/net/aspose.gis/extent/contains/
---
## Contains(double, double) {#contains_2}

确定此范围是否包含由参数定义的坐标。

```csharp
public bool Contains(double x, double y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | 坐标的 X。 |
| y | Double | 坐标的 Y。 |

### 返回值

指示坐标是否在边界框内的值。

## 备注

位于此 [`Extent`](../) 边界上的坐标被视为被此 [`Extent`](../) 包含。

### 另见

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)

---

## Contains(Extent) {#contains}

确定此范围是否包含该参数。

```csharp
public bool Contains(Extent extent)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 范围 | 范围 | 另一个范围。 |

### 返回值

指示此范围是否包含参数的值。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 此范围和参数的[`SpatialReferenceSystem`](../spatialreferencesystem/)均不为 `null` 且彼此不相等。 |

## 备注

位于此 [`Extent`](../) 边界上的坐标被视为被此 [`Extent`](../) 包含。因此，等同的范围被视为相互包含。

### 另见

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)

---

## Contains(IGeometry) {#contains_1}

确定此范围是否包含该参数。

```csharp
public bool Contains(IGeometry geometry)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 几何体 | IGeometry | 用于测试包含性的几何体。 |

### 返回值

指示此范围是否包含参数的值。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 此范围和参数的[`SpatialReferenceSystem`](../spatialreferencesystem/)均不为 `null` 且彼此不相等。 |

## 备注

位于此 [`Extent`](../) 边界上的坐标被视为被此 [`Extent`](../) 包含。

### 另见

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)


