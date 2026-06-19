---
title: "الفئة ProjectedSpatialReferenceSystemParameters"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.ProjectedSpatialReferenceSystemParameters. معلمات لإنشاء SRS مُسقَّط. بعض المعلمات لها قيم افتراضية. بعض المعلمات لها قيم افتراضية معقولة لذا لا تحتاج إلى تعيينها فقط. إذا قمت بتعيين null لتلك المعلمات سيتم استخدام قيمة افتراضية. لا تحتوي ProjectionMethodName و Base على قيم افتراضية؛ يجب تعيين قيمة غير null لهذه الخصائص."
type: docs
weight: 4680
url: /ar/net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---
## ProjectedSpatialReferenceSystemParameters class

معلمات لإنشاء SRS مُسقَّط. بعض المعلمات لها قيم افتراضية. بعض المعلمات لها قيم افتراضية معقولة، لذا لا تحتاج إلى تعيينها فقط. إذا قمت بتعيين `null` لتلك المعلمات، سيتم استخدام قيمة افتراضية. [`ProjectionMethodName`](./projectionmethodname/) و [`Base`](./base/) لا تحتويان على قيم افتراضية - يجب تعيين قيمة غير `null` لهذه الخصائص.

```csharp
public class ProjectedSpatialReferenceSystemParameters
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ProjectedSpatialReferenceSystemParameters](projectedspatialreferencesystemparameters/)() | ينشئ نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AxisesOrder](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/axisesorder/) { get; set; } | ترتيب المحاور. القيمة الافتراضية XY. |
| [Base](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/base/) { get; set; } | نظام الإحداثيات الجغرافي الأساسي (SRS الذي يُطبق عليه الإسقاط). يجب عليك ضبط هذه الخاصية لتكون غير `null` لإنشاء SRS صالح، هذه الخاصية لا تحتوي على قيمة افتراضية. |
| [LinearUnit](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/linearunit/) { get; set; } | الوحدات المستخدمة في هذا SRS. القيمة الافتراضية هي [`Meter`](../unit/meter/). |
| [Name](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/name/) { get; set; } | اسم SRS المُسقَّط. القيمة الافتراضية هي "Unnamed". |
| [ProjectionMethodIdentifier](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/projectionmethodidentifier/) { get; set; } | معرّف طريقة الإسقاط. لا توجد قيمة افتراضية، يمكنك ضبط هذا المعامل ليكون غير `null` إذا رغبت في إرفاق معرف بالإسقاط. إذا فعلت ذلك، عليك التأكد من أن المعرف يتطابق مع اسم طريقة الإسقاط المتسقة (اسم طريقة الإسقاط لن يتغير عندما تضبط هذه الخاصية). |
| [ProjectionMethodName](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/projectionmethodname/) { get; set; } | اسم طريقة الإسقاط. لا توجد قيمة افتراضية ويجب عليك ضبط هذا المعامل ليكون غير `null`، لأن SRS المُسقَّط بدون اسم طريقة إسقاط لا فائدة منه. |
| [XAxis](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/xaxis/) { get; set; } | المحور الذي يصف البُعد X (الأفقي). القيمة الافتراضية هي المحور المتجه شرقًا. |
| [YAxis](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/yaxis/) { get; set; } | المحور الذي يصف البُعد Y (العمودي). الافتراضي هو المحور باتجاه الشمال. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddProjectionParameter](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/addprojectionparameter/)(string, double) | يضيف معامل الإسقاط إلى هذا SRS. إذا كان معامل بهذا الاسم مضافًا بالفعل - يتم تحديثه. |
| [GetProjectionParameter](../../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/getprojectionparameter/)(string) | يحصل على معامل الإسقاط بالاسم المحدد. |

### انظر أيضًا

* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


