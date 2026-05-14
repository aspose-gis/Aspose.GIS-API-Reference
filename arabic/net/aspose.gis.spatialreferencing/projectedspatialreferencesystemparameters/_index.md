---
title: "الفئة ProjectedSpatialReferenceSystemParameters"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.ProjectedSpatialReferenceSystemParameters. معلمات لإنشاء SRS مُسقَّط. بعض المعلمات لها قيم افتراضية. بعض المعلمات لها قيم افتراضية معقولة بحيث لا تحتاج إلى تعيينها فقط. إذا قمت بتعيين null لتلك المعلمات سيتم استخدام قيمة افتراضية. لا تحتوي ProjectionMethodName و Base على قيم افتراضية؛ عليك تعيين قيمة غير null لهذه الخصائص"
type: docs
weight: 4680
url: /ar/net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---
## ProjectedSpatialReferenceSystemParameters class

معلمات لإنشاء SRS مُسقَّط. بعض المعلمات لها قيم افتراضية. بعض المعلمات لها قيم افتراضية معقولة، لذلك لا تحتاج إلى تعيينها فقط. إذا قمت بتعيين `null` لتلك المعلمات، سيتم استخدام قيمة افتراضية. [`ProjectionMethodName`](./projectionmethodname/) و [`Base`](./base/) لا تحتوي على قيم افتراضية - عليك تعيين قيمة غير `null` لهذه الخصائص.

```csharp
public class ProjectedSpatialReferenceSystemParameters
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [ProjectedSpatialReferenceSystemParameters](projectedspatialreferencesystemparameters/)() | ينشئ مثيلًا جديدًا. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AxisesOrder](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/axisesorder/) { get; set; } | ترتيب المحاور. الافتراضي XY. |
| [Base](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/base/) { get; set; } | SRS الجغرافي الأساسي (SRS الذي يُطبق عليه الإسقاط). يجب عليك تعيين هذه الخاصية إلى قيمة غير `null` لإنشاء SRS صالح، هذه الخاصية لا تحتوي على أي قيمة افتراضية. |
| [LinearUnit](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/linearunit/) { get; set; } | الوحدات المستخدمة في هذا SRS. الافتراضي هو [`Meter`](../unit/meter/). |
| [Name](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/name/) { get; set; } | اسم SRS المُسقَّط. الافتراضي هو \"Unnamed\". |
| [ProjectionMethodIdentifier](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/projectionmethodidentifier/) { get; set; } | معرّف طريقة الإسقاط. لا توجد قيمة افتراضية، يمكنك تعيين هذا المعامل إلى قيمة غير `null` إذا أردت إرفاق معرف بالإسقاط. إذا فعلت ذلك، فإن الأمر متروك لك لضمان أن المعرف يتطابق مع اسم طريقة الإسقاط (اسم طريقة الإسقاط لن يتغير عندما تقوم بتعيين هذه الخاصية). |
| [ProjectionMethodName](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/projectionmethodname/) { get; set; } | اسم طريقة الإسقاط. لا توجد قيمة افتراضية ويجب عليك تعيين هذا المعامل إلى قيمة غير `null`، لأن SRS المُسقَّط بدون اسم طريقة إسقاط لا فائدة منه. |
| [XAxis](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/xaxis/) { get; set; } | المحور الذي يصف البُعد X (الأفقي). الافتراضي هو المحور باتجاه الشرق. |
| [YAxis](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/yaxis/) { get; set; } | المحور الذي يصف البُعد Y (العمودي). الافتراضي هو المحور باتجاه الشمال. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddProjectionParameter](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/addprojectionparameter/)(string, double) | يضيف معامل الإسقاط إلى نظام الإسناد المكاني هذا. إذا كان معامل بنفس الاسم مضافًا بالفعل - يتم تحديثه. |
| [GetProjectionParameter](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/getprojectionparameter/)(string) | يحصل على معامل الإسقاط بالاسم المحدد. |

### انظر أيضًا

* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


