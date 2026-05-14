---
title: "الفئة LayeredSymbolizer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Rendering.Symbolizers.LayeredSymbolizer. مُرمّز يقوم بتصيير عدة مُرمّزين آخرين."
type: docs
weight: 4280
url: /ar/net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---
## LayeredSymbolizer class

مُرمّز يقوم بعرض عدة مُرمّزين آخرين.

```csharp
public class LayeredSymbolizer : VectorSymbolizer, IReadOnlyList<VectorSymbolizer>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [LayeredSymbolizer](layeredsymbolizer/#constructor)() | ينشئ مثيلًا جديدًا. |
| [LayeredSymbolizer](layeredsymbolizer/#constructor_1)(RenderingOrder) | ينشئ مثيلًا جديدًا. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/count/) { get; } | يحصل على عدد المُرمّزين. |
| [Item](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/item/) { get; } | يحصل على المُرمّز عند الفهرس المحدد. |
| [RenderingOrder](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/renderingorder/) { get; set; } | يحدد ترتيب التصيير. ByFeatures - صِر جميع المُرمّزين للميزة، ثم الانتقال إلى الميزة التالية. ByLayers - صِر جميع الميزات بالمُرمّز، ثم الانتقال إلى المُرمّز التالي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/add/)(VectorSymbolizer) | يضيف المُرمّز المحدد. |
| [GetEnumerator](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/getenumerator/)() | يعيد عدّادًا يتنقل عبر المجموعة. |

### انظر أيضًا

* class [VectorSymbolizer](../vectorsymbolizer/)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers/)
* assembly [Aspose.GIS](../../)


