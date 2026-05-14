---
title: "الفئة Map"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Rendering.Map. الـ Map هي مجموعة من الطبقات يمكن تصييرها فوق بعضها البعض عبر Renderer"
type: docs
weight: 4170
url: /ar/net/aspose.gis.rendering/map/
---
## Map class

الـ Map هي مجموعة من الطبقات يمكن تصييرها فوق بعضها البعض عبر [`Renderer`](../renderer/).

```csharp
public class Map : IDisposable, IReadOnlyList<MapLayer>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Map](map/#constructor)() | ينشئ نسخة جديدة من الفئة `Map`. |
| [Map](map/#constructor_1)(Measurement, Measurement) | ينشئ نسخة جديدة من الفئة `Map`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../aspose.gis.rendering/map/backgroundcolor/) { get; set; } | لون الخلفية للخريطة. القيمة الافتراضية هي شفاف. |
| [Count](../../aspose.gis.rendering/map/count/) { get; } | يحصل على عدد الطبقات في الخريطة. |
| [Extent](../../aspose.gis.rendering/map/extent/) { get; set; } | يحدد حدود الخريطة لتصيرها. إذا تم تعيينه إلى `null`، يتم حساب الامتداد أثناء التصيير لتضمين جميع الأشكال في جميع الطبقات. |
| [Height](../../aspose.gis.rendering/map/height/) { get; set; } | الارتفاع البصري للخريطة. |
| [Item](../../aspose.gis.rendering/map/item/) { get; } | يحصل على الطبقة عند الفهرس المحدد. |
| [Padding](../../aspose.gis.rendering/map/padding/) { get; set; } | يحدد الحشو لإضافته إلى الامتداد. |
| [Resolution](../../aspose.gis.rendering/map/resolution/) { get; set; } | الدقة المستخدمة لتصير هذه الخريطة وللتحويل بين [`Measurement`](../measurement/). القيمة الافتراضية هي 96. |
| [SpatialReferenceSystem](../../aspose.gis.rendering/map/spatialreferencesystem/) { get; set; } | [`SpatialReferenceSystem`](./spatialreferencesystem/) للخريطة. |
| [Width](../../aspose.gis.rendering/map/width/) { get; set; } | العرض البصري للخريطة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.gis.rendering/map/add/#add)(FeaturesSequence) | ينشئ ويضيف [`VectorMapLayer`](../vectormaplayer/) إلى الخريطة. يتم تصيير الطبقات بترتيب الإضافة. |
| [Add](../../aspose.gis.rendering/map/add/#add_4)(MapLayer) | يضيف طبقة إلى الخريطة. يتم تصيير الطبقات بترتيب الإضافة. |
| [Add](../../aspose.gis.rendering/map/add/#add_1)(FeaturesSequence, VectorSymbolizer) | ينشئ ويضيف [`VectorMapLayer`](../vectormaplayer/) إلى الخريطة. يتم تصيير الطبقات بترتيب الإضافة. |
| [Add](../../aspose.gis.rendering/map/add/#add_8)(VectorLayer, bool) | ينشئ [`VectorMapLayer`](../vectormaplayer/) مع المُرمّز الافتراضي ويضيفه إلى الخريطة. يتم تصيير الطبقات بترتيب الإضافة. |
| [Add](../../aspose.gis.rendering/map/add/#add_2)(FeaturesSequence, VectorSymbolizer, Labeling) | ينشئ ويضيف [`VectorMapLayer`](../vectormaplayer/) إلى الخريطة. يتم تصيير الطبقات بترتيب الإضافة. |
| [Add](../../aspose.gis.rendering/map/add/#add_3)(RasterLayer, RasterColorizer, bool) | ينشئ [`RasterMapLayer`](../rastermaplayer/) مع المُلوّن الافتراضي ويضيفه إلى الخريطة. |
| [Add](../../aspose.gis.rendering/map/add/#add_7)(VectorLayer, VectorSymbolizer, bool) | ينشئ ويضيف [`VectorMapLayer`](../vectormaplayer/) إلى الخريطة. يتم تصيير الطبقات بترتيب الإضافة. |
| [Add](../../aspose.gis.rendering/map/add/#add_6)(VectorLayer, VectorSymbolizer, Labeling, bool) | ينشئ ويضيف [`VectorMapLayer`](../vectormaplayer/) إلى الخريطة. يتم تصيير الطبقات بترتيب الإضافة. |
| [Add](../../aspose.gis.rendering/map/add/#add_5)(VectorLayer, VectorSymbolizer, Labeling, SpatialReferenceSystem, bool) | ينشئ ويضيف [`VectorMapLayer`](../vectormaplayer/) إلى الخريطة. يتم تصيير الطبقات بترتيب الإضافة. |
| [Dispose](../../aspose.gis.rendering/map/dispose/)() | يحرّر الموارد. |
| [GetEnumerator](../../aspose.gis.rendering/map/getenumerator/)() | يعيد عدّادًا يتنقل عبر الطبقات في الخريطة. |
| [Render](../../aspose.gis.rendering/map/render/#render)(AbstractPath, Renderer) | يصير الخريطة إلى ملف. |
| [Render](../../aspose.gis.rendering/map/render/#render_1)(string, Renderer) | يصير الخريطة إلى ملف. |

### انظر أيضًا

* class [MapLayer](../maplayer/)
* namespace [Aspose.Gis.Rendering](../../aspose.gis.rendering/)
* assembly [Aspose.GIS](../../)


