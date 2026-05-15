---
title: "IGeometry.ToEditable"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometry 方法。获取此几何体的可编辑副本"
type: docs
weight: 340
url: /zh/net/aspose.gis.geometries/igeometry/toeditable/
---
## ToEditable() {#toeditable}

获取此几何体的可编辑副本。

```csharp
public Geometry ToEditable()
```

### 返回值

此几何体的可编辑副本。

### 另见

* class [Geometry](../../geometry/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## ToEditable&lt;T&gt;() {#toeditable_1}

获取此几何体的可编辑副本。

```csharp
public T ToEditable<T>()
    where T : Geometry
```

| 参数 | 描述 |
| --- | --- |
| T | 要获取的几何体类型。必须是 [`Geometry`](../../geometry/) 类的子类。 |

### 返回值

此几何体的可编辑副本。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidCastException | 无法将此几何体的可编辑副本强制转换为类型 *T*。 |

### 另见

* class [Geometry](../../geometry/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


