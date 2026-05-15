---
title: "Geometry.Relate"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。确定此几何体与指定几何体的 DE9IM 交叉矩阵是否匹配提供的模式"
type: docs
weight: 300
url: /zh/net/aspose.gis.geometries/geometry/relate/
---
## Geometry.Relate method

确定此几何体与指定几何体的 DE-9IM 交叉矩阵是否匹配提供的模式。

```csharp
public bool Relate(IGeometry other, string intersectionPatternMatrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 其他 | IGeometry | 一个几何体。 |
| intersectionPatternMatrix | String | 用于匹配的模式。该字符串长度应为 9。字符串的每个字符表示交叉的预期维度：字符 0 - 几何体内部之间；字符 1 - 此几何体的内部与另一几何体的边界之间；字符 2 - 此几何体的内部与另一几何体的外部之间；字符 3 - 此几何体的边界与另一几何体的内部之间；字符 4 - 几何体边界之间；字符 5 - 此几何体的边界与另一几何体的外部之间；字符 6 - 此几何体的外部与另一几何体的内部之间；字符 7 - 此几何体的外部与另一几何体的边界之间；字符 8 - 几何体外部之间。每个字符的可能取值为：* - 任意值；F - 无交叉；T - 任意交叉；0 - 点交叉（例如共享点）；1 - 线交叉（例如共享线段）；2 - 面交叉（例如共享多边形部分）。例如，交叉模式 "F0*******" 表示几何体内部之间不应有交叉，而几何体边界之间的交叉必须是一个点。有关交叉矩阵模式的更多细节，请参阅 OpenGIS Simple Features Specification。 |

### 返回值

`true` 如果此交叉矩阵匹配模式；`false` 否则。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *other* 为 `null`。 |
| ArgumentException | 其中一个几何体无效，导致操作无法完成。 |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 不等价。您可以使用 [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) 将几何体转换为相同的空间参考系统。 |

## 备注

此方法构建 DE-9IM 交叉矩阵并将其与模式匹配。有关 DE-9IM 交叉矩阵的更多细节，请参阅 OpenGIS Simple Features Specification。

## 示例

以下代码：

```csharp
geometry.Relate(other, "T*F**FFF*");
```

将检测几何体是否在空间上相等。

### 另见

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


