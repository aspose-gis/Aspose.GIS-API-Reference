---
title: "الفئة VectorMapLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.Rendering.VectorMapLayer. طبقة داخل Map تمثل بيانات طبقة متجهة"
type: docs
weight: 4450
url: /ar/net/aspose.gis.rendering/vectormaplayer/
---
## VectorMapLayer class

طبقة داخل [`Map`](../map/) تمثل بيانات طبقة متجهة.

```csharp
public class VectorMapLayer : MapLayer
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [VectorMapLayer](vectormaplayer/#constructor)(FeaturesSequence) | ينشئ نسخة جديدة مع المُرمّز الافتراضي. |
| [VectorMapLayer](vectormaplayer/#constructor_1)(FeaturesSequence, VectorSymbolizer) | ينشئ نسخة جديدة مع المُرمّز الافتراضي. |
| [VectorMapLayer](vectormaplayer/#constructor_6)(VectorLayer, bool) | ينشئ نسخة جديدة مع المُرمّز الافتراضي. |
| [VectorMapLayer](vectormaplayer/#constructor_5)(VectorLayer, VectorSymbolizer, bool) | ينشئ نسخة جديدة. |
| [VectorMapLayer](vectormaplayer/#constructor_2)(FeaturesSequence, VectorSymbolizer, Labeling, SpatialReferenceSystem) | ينشئ نسخة جديدة مع المُرمّز الافتراضي. |
| [VectorMapLayer](vectormaplayer/#constructor_4)(VectorLayer, VectorSymbolizer, Labeling, bool) | ينشئ نسخة جديدة. |
| [VectorMapLayer](vectormaplayer/#constructor_3)(VectorLayer, VectorSymbolizer, Labeling, SpatialReferenceSystem, bool) | ينشئ نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FeaturesSequence](../../aspose.gis.rendering/vectormaplayer/featuressequence/) { get; } | تسلسل الميزات الممثل بواسطة هذا `VectorMapLayer`. |
| [Labeling](../../aspose.gis.rendering/vectormaplayer/labeling/) { get; set; } | يحدد خيارات الالتواء لطبقة الخريطة. |
| [Opacity](../../aspose.gis.rendering/maplayer/opacity/) { get; set; } | شفافية الطبقة. |
| [Symbolizer](../../aspose.gis.rendering/vectormaplayer/symbolizer/) { get; set; } | المُرمّز المستخدم لتصوير ميزات الطبقة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Dispose](../../aspose.gis.rendering/vectormaplayer/dispose/)() | يقوم بتحرير الموارد. |
| [ImportSld](../../aspose.gis.rendering/vectormaplayer/importsld/#importsld)(AbstractPath, SldImportOptions) | يستورد النمط من ملف Styled Layer Descriptor الموجود في المسار المحدد. |
| [ImportSld](../../aspose.gis.rendering/vectormaplayer/importsld/#importsld_1)(string, SldImportOptions) | يستورد النمط من ملف Styled Layer Descriptor الموجود في المسار المحدد. |
| [ImportSldFromString](../../aspose.gis.rendering/vectormaplayer/importsldfromstring/)(string, SldImportOptions) | يستورد النمط من سلسلة Styled Layer Descriptor المحددة. |

### انظر أيضًا

* class [MapLayer](../maplayer/)
* namespace [Aspose.Gis.Rendering](../../aspose.gis.rendering/)
* assembly [Aspose.GIS](../../)


