---
title: "类 VectorLayer"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.VectorLayer 类。表示矢量图层。矢量图层是存储在文件中的地理要素集合。"
type: docs
weight: 5050
url: /zh/net/aspose.gis/vectorlayer/
---
## VectorLayer class

表示矢量图层。矢量图层是存储在文件中的地理要素集合。

```csharp
public abstract class VectorLayer : FeaturesSequence, IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Attributes](../../aspose.gis/vectorlayer/attributes/) { get; } | 获取此 `VectorLayer` 中特征的自定义属性集合。 |
| virtual [Count](../../aspose.gis/vectorlayer/count/) { get; } | 获取此图层中的特征数量。 |
| abstract [Driver](../../aspose.gis/vectorlayer/driver/) { get; } | 获取实例化此图层的[`Driver`](./driver/)。 |
| abstract [GeometryType](../../aspose.gis/vectorlayer/geometrytype/) { get; } | 获取图层几何体的类型。 |
| virtual [Item](../../aspose.gis/vectorlayer/item/) { get; } | 获取指定索引处的[`Feature`](../feature/)。 |
| abstract [SpatialReferenceSystem](../../aspose.gis/featuressequence/spatialreferencesystem/) { get; } | 获取此特征序列的空间参考系统。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.gis/vectorlayer/create/#create)(AbstractPath, FileDriver) | 创建图层并打开以添加新特征。 |
| static [Create](../../aspose.gis/vectorlayer/create/#create_4)(string, FileDriver) | 创建图层并打开以添加新特征。 |
| static [Create](../../aspose.gis/vectorlayer/create/#create_1)(AbstractPath, FileDriver, DriverOptions) | 创建图层并打开以添加新特征。 |
| static [Create](../../aspose.gis/vectorlayer/create/#create_3)(AbstractPath, FileDriver, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| static [Create](../../aspose.gis/vectorlayer/create/#create_5)(string, FileDriver, DriverOptions) | 创建图层并打开以添加新特征。 |
| static [Create](../../aspose.gis/vectorlayer/create/#create_7)(string, FileDriver, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| static [Create](../../aspose.gis/vectorlayer/create/#create_2)(AbstractPath, FileDriver, DriverOptions, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| static [Create](../../aspose.gis/vectorlayer/create/#create_6)(string, FileDriver, DriverOptions, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| static [Open](../../aspose.gis/vectorlayer/open/#open)(AbstractPath, FileDriver) | 打开图层进行读取。 |
| static [Open](../../aspose.gis/vectorlayer/open/#open_2)(string, FileDriver) | 打开图层进行读取。 |
| static [Open](../../aspose.gis/vectorlayer/open/#open_1)(AbstractPath, FileDriver, DriverOptions) | 打开图层进行读取。 |
| static [Open](../../aspose.gis/vectorlayer/open/#open_3)(string, FileDriver, DriverOptions) | 打开图层进行读取。 |
| virtual [Add](../../aspose.gis/vectorlayer/add/#add)(Feature) | 向图层添加新特征（如果 `VectorLayer` 的[`Driver`](./driver/) 支持）。 |
| virtual [Add](../../aspose.gis/vectorlayer/add/#add_1)(Feature, IFeatureStyle) | 向图层添加具有指定样式的新特征（如果 `VectorLayer` 的[`Driver`](./driver/) 支持）。 |
| [AsInMemory](../../aspose.gis/vectorlayer/asinmemory/)() | 创建一个 InMemory 格式的图层克隆。 |
| [ConstructFeature](../../aspose.gis/vectorlayer/constructfeature/)() | 创建（但不添加到图层）一个新特征，其属性与此图层的属性集合匹配。设置完特征数据后，使用[`Add`](./add/)将特征添加到图层。 |
| [CopyAttributes](../../aspose.gis/vectorlayer/copyattributes/#copyattributes)(FeaturesSequence) | 复制其他 `VectorLayer` 的属性到此图层。 |
| [CopyAttributes](../../aspose.gis/vectorlayer/copyattributes/#copyattributes_1)(FeaturesSequence, IAttributesConverter) | 复制其他 `VectorLayer` 的属性到此图层。 |
| [Dispose](../../aspose.gis/vectorlayer/dispose/)() | 释放 `VectorLayer` 使用的资源。 |
| override [Equals](../../aspose.gis/vectorlayer/equals/)(object) | 确定指定对象是否等于当前对象。 |
| virtual [FindIndex](../../aspose.gis/vectorlayer/findindex/)(Func&lt;Feature, bool&gt;) | 根据条件搜索[`Feature`](../feature/)的索引。 |
| abstract [GetEnumerator](../../aspose.gis/featuressequence/getenumerator/)() | 返回遍历集合的枚举器。 |
| virtual [GetExtent](../../aspose.gis/featuressequence/getextent/)() | 获取此图层的空间范围。 |
| [Join](../../aspose.gis/vectorlayer/join/)(VectorLayer, JoinOptions) | 将一个图层加入当前图层。 |
| [JoinByGeometry](../../aspose.gis/vectorlayer/joinbygeometry/)(VectorLayer, JoinByGeometryOptions) | 通过几何体将一个图层加入当前图层。 |
| [NearestTo](../../aspose.gis/vectorlayer/nearestto/#nearestto)(IPoint) | 获取最近于提供的点的特征。 |
| [NearestTo](../../aspose.gis/vectorlayer/nearestto/#nearestto_1)(double, double) | 获取最近于提供的坐标的特征。 |
| virtual [RemoveAt](../../aspose.gis/vectorlayer/removeat/)(int) | 移除指定索引处的[`Feature`](../feature/)。 |
| virtual [ReplaceAt](../../aspose.gis/vectorlayer/replaceat/)(int, Feature) | 替换指定索引处的[`Feature`](../feature/)。 |
| [SaveTo](../../aspose.gis/featuressequence/saveto/)(AbstractPath, FileDriver) | 将特征序列保存到图层。 |
| [SaveTo](../../aspose.gis/featuressequence/saveto/)(string, FileDriver) | 将特征序列保存到图层。 |
| [SaveTo](../../aspose.gis/featuressequence/saveto/)(AbstractPath, FileDriver, SavingOptions) | 将特征序列保存到图层。 |
| [SaveTo](../../aspose.gis/featuressequence/saveto/)(string, FileDriver, SavingOptions) | 将特征序列保存到图层。 |
| [SplitTo](../../aspose.gis/featuressequence/splitto/)() | 按几何类型拆分特征。 |
| virtual [UseAttributesIndex](../../aspose.gis/vectorlayer/useattributesindex/#useattributesindex)(AbstractPath, string, bool) | 加载属性索引以加快在过滤方法（如[`WhereGreater`](../featuressequence/wheregreater/)）中按属性值进行过滤的速度。如果索引不存在，则先创建。使用 *forceRebuild* 强制重新创建索引。 |
| [UseAttributesIndex](../../aspose.gis/vectorlayer/useattributesindex/#useattributesindex_1)(string, string, bool) | 加载属性索引以加快在过滤方法（如[`WhereGreater`](../featuressequence/wheregreater/)）中按属性值进行过滤的速度。如果索引不存在，则先创建。使用 *forceRebuild* 强制重新创建索引。 |
| virtual [UseSpatialIndex](../../aspose.gis/vectorlayer/usespatialindex/#usespatialindex)(AbstractPath, bool) | 加载空间索引以加快在过滤方法（如 [`WhereIntersects`](../featuressequence/whereintersects/) 和 [`NearestTo`](./nearestto/)）中按属性值进行过滤的速度。如果索引不存在，则先创建它。使用 *forceRebuild* 强制重新创建索引。 |
| [UseSpatialIndex](../../aspose.gis/vectorlayer/usespatialindex/#usespatialindex_1)(string, bool) | 加载空间索引以加快在过滤方法（如 [`WhereIntersects`](../featuressequence/whereintersects/) 和 [`NearestTo`](./nearestto/)）中按属性值进行过滤的速度。如果索引不存在，则先创建它。使用 *forceRebuild* 强制重新创建索引。 |
| virtual [WhereEqual&lt;T&gt;](../../aspose.gis/featuressequence/whereequal/)(string, T) | 选择属性值等于提供值的要素。 |
| virtual [WhereGreater&lt;T&gt;](../../aspose.gis/featuressequence/wheregreater/)(string, T) | 选择属性值大于提供值的要素。 |
| virtual [WhereGreaterOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheregreaterorequal/)(string, T) | 选择属性值大于或等于提供值的要素。 |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/)(Extent) | 根据范围过滤要素。 |
| [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/)(FeaturesSequence) | 根据其他要素序列中所有几何的联合过滤要素。 |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/)(IGeometry) | 根据提供的几何过滤要素。 |
| virtual [WhereLinq](../../aspose.gis/featuressequence/wherelinq/)(Func&lt;Feature, bool&gt;) | 使用 linq 将选择条件合并为单个查询。 |
| virtual [WhereNotEqual&lt;T&gt;](../../aspose.gis/featuressequence/wherenotequal/)(string, T) | 选择属性值不等于提供值的要素。 |
| virtual [WhereNotNull](../../aspose.gis/featuressequence/wherenotnull/)(string) | 选择属性不等于 null 的要素。 |
| virtual [WhereNull](../../aspose.gis/featuressequence/wherenull/)(string) | 选择属性等于 null 的要素。 |
| virtual [WhereSet](../../aspose.gis/featuressequence/whereset/)(string) | 选择已设置属性的要素。 |
| virtual [WhereSmaller&lt;T&gt;](../../aspose.gis/featuressequence/wheresmaller/)(string, T) | 选择属性值小于提供值的要素。 |
| virtual [WhereSmallerOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheresmallerorequal/)(string, T) | 选择属性值小于或等于提供值的要素。 |
| virtual [WhereUnset](../../aspose.gis/featuressequence/whereunset/)(string) | 选择指定属性未设置的要素。 |
| static [Convert](../../aspose.gis/vectorlayer/convert/#convert)(AbstractPath, FileDriver, AbstractPath, FileDriver) | 将图层转换为不同的格式。 |
| static [Convert](../../aspose.gis/vectorlayer/convert/#convert_2)(string, FileDriver, string, FileDriver) | 将图层转换为不同的格式。 |
| static [Convert](../../aspose.gis/vectorlayer/convert/#convert_1)(AbstractPath, FileDriver, AbstractPath, FileDriver, ConversionOptions) | 将图层转换为不同的格式。 |
| static [Convert](../../aspose.gis/vectorlayer/convert/#convert_3)(string, FileDriver, string, FileDriver, ConversionOptions) | 将图层转换为不同的格式。 |

### 另见

* class [FeaturesSequence](../featuressequence/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


