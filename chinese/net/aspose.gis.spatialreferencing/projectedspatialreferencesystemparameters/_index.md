---
title: "类 ProjectedSpatialReferenceSystemParameters"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.SpatialReferencing.ProjectedSpatialReferenceSystemParameters 类。用于创建投影 SRS 的参数。某些参数有默认值。某些参数具有合理的默认值，因此您无需仅为它们赋值。如果将 null 赋给这些参数，将使用默认值。ProjectionMethodName 和 Base 没有默认值，您必须为这些属性分配非 null 值。"
type: docs
weight: 4680
url: /zh/net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---
## ProjectedSpatialReferenceSystemParameters class

用于创建投影 SRS 的参数。某些参数有默认值。某些参数具有合理的默认值，因此您无需仅为它们赋值。如果将 `null` 赋给这些参数，将使用默认值。[`ProjectionMethodName`](./projectionmethodname/) 和 [`Base`](./base/) 没有默认值——您必须为这些属性分配非 `null` 值。

```csharp
public class ProjectedSpatialReferenceSystemParameters
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ProjectedSpatialReferenceSystemParameters](projectedspatialreferencesystemparameters/)() | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AxisesOrder](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/axisesorder/) { get; set; } | 轴的顺序。默认是 XY。 |
| [Base](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/base/) { get; set; } | 基础地理 SRS（投影应用的 SRS）。您必须将此属性设置为非 `null` 值，以创建有效的 SRS，此属性没有任何默认值。 |
| [LinearUnit](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/linearunit/) { get; set; } | 此 SRS 中使用的单位。默认是 [`Meter`](../unit/meter/)。 |
| [Name](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/name/) { get; set; } | 投影 SRS 的名称。默认是 "Unnamed"。 |
| [ProjectionMethodIdentifier](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/projectionmethodidentifier/) { get; set; } | 投影方法的标识符。没有默认值，您可以将此参数设置为非 `null` 值，如果您想为投影附加标识符。若这样做——您需确保标识符与投影方法名称保持一致（设置此属性时投影方法名称不会改变）。 |
| [ProjectionMethodName](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/projectionmethodname/) { get; set; } | 投影方法的名称。没有默认值，您必须将此参数设置为非 `null` 值，因为没有投影名称的投影 SRS 没有意义。 |
| [XAxis](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/xaxis/) { get; set; } | 描述 X（水平）维度的轴。默认是指向东的轴。 |
| [YAxis](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/yaxis/) { get; set; } | 描述 Y（垂直）维度的轴。默认使用指向北方的轴。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddProjectionParameter](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/addprojectionparameter/)(string, double) | 向此 SRS 添加投影参数。如果已存在同名参数，则更新它。 |
| [GetProjectionParameter](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/getprojectionparameter/)(string) | 获取具有指定名称的投影参数。 |

### 另见

* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


