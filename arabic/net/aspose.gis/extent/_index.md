---
title: "الفئة Extent"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Extent. صندوق حدود فضائي ثنائي الأبعاد"
type: docs
weight: 1610
url: /ar/net/aspose.gis/extent/
---
## Extent class

صندوق حدود فضائي ثنائي الأبعاد.

```csharp
public class Extent : IEquatable<Extent>
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Extent](extent/#constructor)() | ينشئ مثيلًا جديدًا. |
| [Extent](extent/#constructor_1)(SpatialReferenceSystem) | ينشئ مثيلًا جديدًا. |
| [Extent](extent/#constructor_2)(double, double, double, double, SpatialReferenceSystem) | ينشئ مثيلًا جديدًا. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Center](../../aspose.gis/extent/center/) { get; } | مركز الامتداد. |
| [Height](../../aspose.gis/extent/height/) { get; } | ارتفاع الامتداد. |
| [IsValid](../../aspose.gis/extent/isvalid/) { get; } | يحدد ما إذا كان هذا `Extent` صالحًا. |
| [SpatialReferenceSystem](../../aspose.gis/extent/spatialreferencesystem/) { get; set; } | [`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/) المرتبط بهذا الامتداد. يمكن أن يكون `null` إذا كان [`SpatialReferenceSystem`](./spatialreferencesystem/) غير معروف. استخدم [`GetTransformed`](./gettransformed/) لتحويل الامتداد بين أنظمة الإسناد المكاني المختلفة. |
| [Width](../../aspose.gis/extent/width/) { get; } | عرض الامتداد. |
| [XMax](../../aspose.gis/extent/xmax/) { get; set; } | القيمة القصوى لإحداثي X. |
| [XMin](../../aspose.gis/extent/xmin/) { get; set; } | القيمة الدنيا لإحداثي X. |
| [YMax](../../aspose.gis/extent/ymax/) { get; set; } | القيمة القصوى لإحداثي Y. |
| [YMin](../../aspose.gis/extent/ymin/) { get; set; } | القيمة الدنيا لإحداثي Y. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../aspose.gis/extent/clone/)() | ينسخ هذا الكائن. |
| [Contains](../../aspose.gis/extent/contains/#contains)(Extent) | يحدد ما إذا كان هذا الامتداد يحتوي على الوسيط. |
| [Contains](../../aspose.gis/extent/contains/#contains_1)(IGeometry) | يحدد ما إذا كان هذا الامتداد يحتوي على الوسيط. |
| [Contains](../../aspose.gis/extent/contains/#contains_2)(double, double) | يحدد ما إذا كان هذا الامتداد يحتوي على إحداثي معرف بالوسائط. |
| [Equals](../../aspose.gis/extent/equals/#equals)(Extent) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| override [Equals](../../aspose.gis/extent/equals/#equals_1)(object) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| override [GetHashCode](../../aspose.gis/extent/gethashcode/)() | يعمل كدالة التجزئة الافتراضية. |
| [GetTransformed](../../aspose.gis/extent/gettransformed/)(SpatialReferenceSystem) | يعيد نطاقًا جديدًا في نظام الإحداثيات المحدد [`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/) الذي يحتوي على هذا النطاق. |
| [Grow](../../aspose.gis/extent/grow/#grow)(Extent) | يوسّع هذا النطاق بحيث يشمل الوسيط. |
| [Grow](../../aspose.gis/extent/grow/#grow_1)(double, double) | يوسّع هذا النطاق بحيث يشمل النقطة المحددة. |
| [GrowX](../../aspose.gis/extent/growx/)(double) | يوسّع هذا النطاق على محور X بحيث يشمل القيمة المحددة. |
| [GrowY](../../aspose.gis/extent/growy/)(double) | يوسّع هذا النطاق على محور Y بحيث يشمل القيمة المحددة. |
| [Intersects](../../aspose.gis/extent/intersects/#intersects)(Extent) | يحدد ما إذا كان هذا النطاق يتقاطع مع الوسيط. |
| [Intersects](../../aspose.gis/extent/intersects/#intersects_1)(IGeometry) | يحدد ما إذا كان هذا النطاق يتقاطع مع الوسيط. |
| [Normalize](../../aspose.gis/extent/normalize/)() | يبدّل [`XMin`](./xmin/) مع [`XMax`](./xmax/) إذا كان [`Width`](./width/) سالبًا و[`YMin`](./ymin/) مع [`YMax`](./ymax/) إذا كان [`Height`](./height/) سالبًا. |
| [ToPolygon](../../aspose.gis/extent/topolygon/)() | يحوّل هذا النطاق إلى مضلع مستطيل يمثلّه. |
| override [ToString](../../aspose.gis/extent/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |
| [operator ==](../../aspose.gis/extent/op_equality/) | ينفّذ العامل '=='. |
| [operator !=](../../aspose.gis/extent/op_inequality/) | ينفّذ العامل '!='. |

### انظر أيضًا

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


