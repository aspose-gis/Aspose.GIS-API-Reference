---
title: "Class Dataset"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.Dataset فئة. مجموعة البيانات هي مجموعة من كائنات VectorLayer"
type: docs
weight: 1430
url: /ar/net/aspose.gis/dataset/
---
## Dataset class

مجموعة البيانات هي مجموعة من كائنات [`VectorLayer`](../vectorlayer/)

```csharp
public abstract class Dataset : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [CanCreateLayers](../../aspose.gis/dataset/cancreatelayers/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت مجموعة البيانات هذه يمكنها إنشاء طبقات متجهة. |
| virtual [CanRemoveLayers](../../aspose.gis/dataset/canremovelayers/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت مجموعة البيانات هذه يمكنها إزالة طبقات متجهة. |
| abstract [Driver](../../aspose.gis/dataset/driver/) { get; } | يحصل على [`Driver`](./driver/) الذي أنشأ مجموعة البيانات هذه. |
| abstract [LayersCount](../../aspose.gis/dataset/layerscount/) { get; } | يحصل على عدد الطبقات في مجموعة البيانات هذه. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.gis/dataset/create/#create)(AbstractPath, FileDriver) | ينشئ مجموعة بيانات. |
| static [Create](../../aspose.gis/dataset/create/#create_2)(string, FileDriver) | ينشئ مجموعة بيانات. |
| static [Create](../../aspose.gis/dataset/create/#create_1)(AbstractPath, FileDriver, DriverOptions) | ينشئ مجموعة بيانات. |
| static [Create](../../aspose.gis/dataset/create/#create_3)(string, FileDriver, DriverOptions) | ينشئ مجموعة بيانات. |
| static [Open](../../aspose.gis/dataset/open/#open)(AbstractPath, FileDriver) | يفتح مجموعة البيانات. |
| static [Open](../../aspose.gis/dataset/open/#open_2)(IDbConnection, DatabaseDriver) | يفتح مجموعة البيانات. |
| static [Open](../../aspose.gis/dataset/open/#open_3)(string, FileDriver) | يفتح مجموعة البيانات. |
| static [Open](../../aspose.gis/dataset/open/#open_1)(AbstractPath, FileDriver, DriverOptions) | يفتح مجموعة البيانات. |
| static [Open](../../aspose.gis/dataset/open/#open_4)(string, FileDriver, DriverOptions) | يفتح مجموعة البيانات. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer)() | ينشئ طبقة متجهة جديدة ويفتحها للإلحاق. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_2)(SpatialReferenceSystem) | ينشئ طبقة متجهة جديدة ويفتحها للإلحاق. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_1)(DriverOptions, SpatialReferenceSystem) | ينشئ طبقة متجهة جديدة ويفتحها للإلحاق. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_4)(string, SpatialReferenceSystem) | ينشئ طبقة متجهة جديدة بالاسم المحدد ويفتحها للإلحاق. |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_3)(string, DriverOptions, SpatialReferenceSystem) | ينشئ طبقة متجهة جديدة بالاسم المحدد ويفتحها للإلحاق. |
| [Dispose](../../aspose.gis/dataset/dispose/)() | يطلق الموارد المستخدمة من قبل `Dataset`. |
| abstract [EditLayer](../../aspose.gis/dataset/editlayer/)(string, DriverOptions, SpatialReferenceSystem) | يفتح الطبقة بالاسم المحدد للتحرير. |
| abstract [EditLayerAt](../../aspose.gis/dataset/editlayerat/)(int, DriverOptions, SpatialReferenceSystem) | يفتح الطبقة بالاسم المحدد للتحرير. |
| abstract [GetLayerName](../../aspose.gis/dataset/getlayername/)(int) | يحصل على اسم الطبقة في الفهرس المحدد. |
| virtual [HasLayerWithName](../../aspose.gis/dataset/haslayerwithname/)(string) | تحقق مما إذا كانت مجموعة البيانات الحالية تحتوي على طبقة بالاسم المحدد |
| abstract [OpenLayer](../../aspose.gis/dataset/openlayer/)(string, DriverOptions) | يفتح الطبقة بالاسم المحدد للقراءة. |
| abstract [OpenLayerAt](../../aspose.gis/dataset/openlayerat/)(int, DriverOptions) | يفتح الطبقة في الفهرس المحدد للقراءة. |
| virtual [RemoveLayer](../../aspose.gis/dataset/removelayer/)(string) | يزيل الطبقة المتجهة بالاسم المحدد. |
| virtual [RemoveLayerAt](../../aspose.gis/dataset/removelayerat/)(int) | يزيل الطبقة المتجهة في الفهرس المحدد. |
| virtual [RenameLayer](../../aspose.gis/dataset/renamelayer/)(string, string) | إعادة تسمية الطبقة في مجموعة البيانات |

### انظر أيضًا

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


