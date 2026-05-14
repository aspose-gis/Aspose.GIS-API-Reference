---
title: "Map.Add"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Map. تُنشئ VectorMapLayer مع المُرمّز الافتراضي وتضيفه إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة"
type: docs
weight: 110
url: /ar/net/aspose.gis.rendering/map/add/
---
## Add(VectorLayer, bool) {#add_8}

ينشئ [`VectorMapLayer`](../../vectormaplayer/) مع المُرمّز الافتراضي ويضيفه إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

```csharp
public void Add(VectorLayer layer, bool keepOpen = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| layer | VectorLayer | طبقة متجهة لتمثيلها بواسطة [`VectorMapLayer`](../../vectormaplayer/). |
| keepOpen | Boolean | `true` لترك طبقة المتجه مفتوحة بعد التخلص من كائن [`Map`](../)؛ `false` للتخلص من الطبقة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(VectorLayer, VectorSymbolizer, bool) {#add_7}

ينشئ ويضيف [`VectorMapLayer`](../../vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

```csharp
public void Add(VectorLayer layer, VectorSymbolizer symbolizer, bool keepOpen = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| layer | VectorLayer | طبقة متجهة لتمثيلها بواسطة [`VectorMapLayer`](../../vectormaplayer/). |
| symbolizer | VectorSymbolizer | رمز لتحديد الشكل يُستخدم في التصيير. إذا كان `null`، يُستخدم رمز التحديد الافتراضي. |
| keepOpen | Boolean | `true` لترك طبقة المتجه مفتوحة بعد التخلص من كائن [`Map`](../)؛ `false` للتخلص من الطبقة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(VectorLayer, VectorSymbolizer, Labeling, bool) {#add_6}

ينشئ ويضيف [`VectorMapLayer`](../../vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

```csharp
public void Add(VectorLayer layer, VectorSymbolizer symbolizer, Labeling labeling, 
    bool keepOpen = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| layer | VectorLayer | طبقة متجهة لتمثيلها بواسطة [`VectorMapLayer`](../../vectormaplayer/). |
| symbolizer | VectorSymbolizer | رمز لتحديد الشكل يُستخدم في التصيير. إذا كان `null`، يُستخدم رمز التحديد الافتراضي. |
| labeling | Labeling | التصنيف المستخدم لتسمية المميزات في الطبقة. إذا كان `null`، سيتم استخدام [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| keepOpen | Boolean | `true` لترك الطبقة مفتوحة بعد التخلص من كائن [`Map`](../)؛ وإلا `false`. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(VectorLayer, VectorSymbolizer, Labeling, SpatialReferenceSystem, bool) {#add_5}

ينشئ ويضيف [`VectorMapLayer`](../../vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

```csharp
public void Add(VectorLayer layer, VectorSymbolizer symbolizer, Labeling labeling, 
    SpatialReferenceSystem defaultReferenceSystem, bool keepOpen = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| layer | VectorLayer | طبقة متجهة لتمثيلها بواسطة [`VectorMapLayer`](../../vectormaplayer/). |
| symbolizer | VectorSymbolizer | رمز لتحديد الشكل يُستخدم في التصيير. إذا كان `null`، يُستخدم رمز التحديد الافتراضي. |
| labeling | Labeling | التصنيف المستخدم لتسمية المميزات في الطبقة. إذا كان `null`، سيتم استخدام [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| defaultReferenceSystem | SpatialReferenceSystem | يحدد قيمة للمرجع المكاني المصدر (layer\sequence) إذا كان مفقودًا. سيتم استخدام **null** الافتراضي. |
| keepOpen | Boolean | `true` لترك الطبقة مفتوحة بعد التخلص من كائن [`Map`](../)؛ وإلا `false`. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(FeaturesSequence) {#add}

ينشئ ويضيف [`VectorMapLayer`](../../vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

```csharp
public void Add(FeaturesSequence featuresSequence)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | تسلسل المميزات لتمثيله بواسطة [`VectorMapLayer`](../../vectormaplayer/). |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | تسلسل المميزات هو `null`. |

### انظر أيضًا

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(FeaturesSequence, VectorSymbolizer) {#add_1}

ينشئ ويضيف [`VectorMapLayer`](../../vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

```csharp
public void Add(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | تسلسل المميزات لتمثيله بواسطة [`VectorMapLayer`](../../vectormaplayer/). |
| symbolizer | VectorSymbolizer | رمز لتحديد الشكل يُستخدم في التصيير. إذا كان `null`، يُستخدم رمز التحديد الافتراضي. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | تسلسل المميزات هو `null`. |

### انظر أيضًا

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(FeaturesSequence, VectorSymbolizer, Labeling) {#add_2}

ينشئ ويضيف [`VectorMapLayer`](../../vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

```csharp
public void Add(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer, Labeling labeling)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | تسلسل المميزات لتمثيله بواسطة [`VectorMapLayer`](../../vectormaplayer/). |
| symbolizer | VectorSymbolizer | مُرمّز للاستخدام في العرض. |
| labeling | Labeling | التصنيف المستخدم لتسمية المميزات في الطبقة. إذا كان `null`، سيتم استخدام [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/). |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | تسلسل المميزات هو `null`. |

### انظر أيضًا

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(MapLayer) {#add_4}

يضيف طبقة إلى الخريطة. يتم تصيير الطبقات بترتيب الإضافة.

```csharp
public void Add(MapLayer mapLayer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| mapLayer | MapLayer | الطبقة التي سيتم إضافتها. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |

### انظر أيضًا

* class [MapLayer](../../maplayer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(RasterLayer, RasterColorizer, bool) {#add_3}

ينشئ [`RasterMapLayer`](../../rastermaplayer/) مع مُلوّن افتراضي ويضيفه إلى الخريطة.

```csharp
public void Add(RasterLayer layer, RasterColorizer colorizer = null, bool keepOpen = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| layer | RasterLayer | طبقة متجهة لتمثيلها بواسطة [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/). |
| colorizer | RasterColorizer | مُلوّن للاستخدام في العرض. إذا كان `null`، يُستخدم المُلوّن الافتراضي. |
| keepOpen | Boolean | `true` لترك طبقة الراستر مفتوحة بعد التخلص من كائن [`Map`](../)؛ `false` للتخلص من الطبقة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [RasterColorizer](../../../aspose.gis.rendering.colorizers/rastercolorizer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)


