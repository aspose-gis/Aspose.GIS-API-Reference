---
title: "الفئة FileDriver"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.FileDriver. برنامج تشغيل لتنسيق مبني على ملف محدد"
type: docs
weight: 1670
url: /ar/net/aspose.gis/filedriver/
---
## FileDriver class

محرك لتنسيق مبني على ملف محدد.

```csharp
public abstract class FileDriver : Driver
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [CanCreateDatasets](../../aspose.gis/filedriver/cancreatedatasets/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه إنشاء مجموعات البيانات. |
| abstract [CanCreateLayers](../../aspose.gis/filedriver/cancreatelayers/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه إنشاء طبقات متجهية. |
| virtual [CanOpenDatasets](../../aspose.gis/filedriver/canopendatasets/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه فتح مجموعات البيانات. |
| abstract [CanOpenLayers](../../aspose.gis/filedriver/canopenlayers/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه فتح طبقات متجهية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/#createdataset)(AbstractPath) | ينشئ مجموعة بيانات. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/#createdataset_2)(string) | ينشئ مجموعة بيانات. |
| virtual [CreateDataset](../../aspose.gis/filedriver/createdataset/#createdataset_1)(AbstractPath, DriverOptions) | ينشئ مجموعة بيانات. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/#createdataset_3)(string, DriverOptions) | ينشئ مجموعة بيانات. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer)(AbstractPath) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_4)(string) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_1)(AbstractPath, DriverOptions) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_3)(AbstractPath, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_5)(string, DriverOptions) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_7)(string, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| abstract [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_2)(AbstractPath, DriverOptions, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_6)(string, DriverOptions, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer/#editlayer)(AbstractPath, DriverOptions) | يفتح طبقة للتحرير. |
| [EditLayer](../../aspose.gis/filedriver/editlayer/#editlayer_1)(string, DriverOptions) | يفتح طبقة للتحرير. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/#opendataset)(AbstractPath) | يفتح مجموعة البيانات. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/#opendataset_2)(string) | يفتح مجموعة البيانات. |
| virtual [OpenDataset](../../aspose.gis/filedriver/opendataset/#opendataset_1)(AbstractPath, DriverOptions) | يفتح مجموعة البيانات. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/#opendataset_3)(string, DriverOptions) | يفتح مجموعة البيانات. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/#openlayer)(AbstractPath) | يفتح الطبقة للقراءة. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/#openlayer_2)(string) | يفتح الطبقة للقراءة. |
| abstract [OpenLayer](../../aspose.gis/filedriver/openlayer/#openlayer_1)(AbstractPath, DriverOptions) | يفتح الطبقة للقراءة. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/#openlayer_3)(string, DriverOptions) | يفتح الطبقة للقراءة. |
| abstract [SupportsSpatialReferenceSystem](../../aspose.gis/filedriver/supportsspatialreferencesystem/)(SpatialReferenceSystem) | يحدد ما إذا كان نظام الإحداثيات المكانية المحدد مدعومًا من قبل البرنامج تشغيل. |

### انظر أيضًا

* class [Driver](../driver/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


