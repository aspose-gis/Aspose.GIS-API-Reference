---
title: "类 FeaturesSequence"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.FeaturesSequence 类。FeaturesSequence 表示一组矢量要素"
type: docs
weight: 1660
url: /zh/net/aspose.gis/featuressequence/
---
## FeaturesSequence class

`FeaturesSequence` 表示一组矢量要素。

```csharp
public abstract class FeaturesSequence : IEnumerable<Feature>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [Attributes](../../aspose.gis/featuressequence/attributes/) { get; } | 获取此 [`VectorLayer`](../vectorlayer/) 中要素的自定义属性集合。 |
| abstract [SpatialReferenceSystem](../../aspose.gis/featuressequence/spatialreferencesystem/) { get; } | 获取此特征序列的空间参考系统。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [GetEnumerator](../../aspose.gis/featuressequence/getenumerator/)() | 返回遍历集合的枚举器。 |
| virtual [GetExtent](../../aspose.gis/featuressequence/getextent/)() | 获取此图层的空间范围。 |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto)(AbstractPath, FileDriver) | 将特征序列保存到图层。 |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto_2)(string, FileDriver) | 将特征序列保存到图层。 |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto_1)(AbstractPath, FileDriver, SavingOptions) | 将特征序列保存到图层。 |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto_3)(string, FileDriver, SavingOptions) | 将特征序列保存到图层。 |
| [SplitTo](../../aspose.gis/featuressequence/splitto/)() | 按几何类型拆分特征。 |
| virtual [WhereEqual&lt;T&gt;](../../aspose.gis/featuressequence/whereequal/)(string, T) | 选择属性值等于提供值的要素。 |
| virtual [WhereGreater&lt;T&gt;](../../aspose.gis/featuressequence/wheregreater/)(string, T) | 选择属性值大于提供值的要素。 |
| virtual [WhereGreaterOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheregreaterorequal/)(string, T) | 选择属性值大于或等于提供值的要素。 |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/#whereintersects)(Extent) | 根据范围过滤要素。 |
| [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/#whereintersects_1)(FeaturesSequence) | 根据其他要素序列中所有几何的联合过滤要素。 |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/#whereintersects_2)(IGeometry) | 根据提供的几何过滤要素。 |
| virtual [WhereLinq](../../aspose.gis/featuressequence/wherelinq/)(Func&lt;Feature, bool&gt;) | 使用 linq 将选择条件合并为单个查询。 |
| virtual [WhereNotEqual&lt;T&gt;](../../aspose.gis/featuressequence/wherenotequal/)(string, T) | 选择属性值不等于提供值的要素。 |
| virtual [WhereNotNull](../../aspose.gis/featuressequence/wherenotnull/)(string) | 选择属性不等于 null 的要素。 |
| virtual [WhereNull](../../aspose.gis/featuressequence/wherenull/)(string) | 选择属性等于 null 的要素。 |
| virtual [WhereSet](../../aspose.gis/featuressequence/whereset/)(string) | 选择已设置属性的要素。 |
| virtual [WhereSmaller&lt;T&gt;](../../aspose.gis/featuressequence/wheresmaller/)(string, T) | 选择属性值小于提供值的要素。 |
| virtual [WhereSmallerOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheresmallerorequal/)(string, T) | 选择属性值小于或等于提供值的要素。 |
| virtual [WhereUnset](../../aspose.gis/featuressequence/whereunset/)(string) | 选择指定属性未设置的要素。 |

### 另见

* class [Feature](../feature/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


