---
title: "Class MapInfoTabDriver"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.Formats.MapInfoTab.MapInfoTabDriver. برنامج تشغيل لتنسيق MapInfo Tab"
type: docs
weight: 2240
url: /ar/net/aspose.gis.formats.mapinfotab/mapinfotabdriver/
---
## MapInfoTabDriver class

محرك لتنسيق MapInfo Tab.

```csharp
public sealed class MapInfoTabDriver : FileDriver
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CanCreateDatasets](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/cancreatedatasets/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه إنشاء مجموعات البيانات. |
| override [CanCreateLayers](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/cancreatelayers/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه إنشاء طبقات متجهية. |
| virtual [CanOpenDatasets](../../aspose.gis/filedriver/canopendatasets/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه فتح مجموعات البيانات. |
| override [CanOpenLayers](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/canopenlayers/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه فتح طبقات متجهية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(AbstractPath) | ينشئ مجموعة بيانات. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(string) | ينشئ مجموعة بيانات. |
| virtual [CreateDataset](../../aspose.gis/filedriver/createdataset/)(AbstractPath, DriverOptions) | ينشئ مجموعة بيانات. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(string, DriverOptions) | ينشئ مجموعة بيانات. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath, DriverOptions) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/createlayer/#createlayer_3)(AbstractPath, MapInfoTabOptions) | ينشئ طبقة ويفتحها لإضافة ميزات جديدة. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/createlayer/#createlayer_9)(string, MapInfoTabOptions) | ينشئ طبقة ويفتحها لإضافة ميزات جديدة. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| override [CreateLayer](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/createlayer/#createlayer_2)(AbstractPath, DriverOptions, SpatialReferenceSystem) | ينشئ طبقة ويفتحها لإضافة ميزات جديدة. |
| [CreateLayer](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/createlayer/#createlayer_4)(AbstractPath, MapInfoTabOptions, SpatialReferenceSystem) | ينشئ طبقة ويفتحها لإضافة ميزات جديدة. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer/)(AbstractPath, DriverOptions) | يفتح طبقة للتحرير. |
| [EditLayer](../../aspose.gis/filedriver/editlayer/)(string, DriverOptions) | يفتح طبقة للتحرير. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath) | يفتح مجموعة البيانات. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string) | يفتح مجموعة البيانات. |
| virtual [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath, DriverOptions) | يفتح مجموعة البيانات. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string, DriverOptions) | يفتح مجموعة البيانات. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(AbstractPath) | يفتح الطبقة للقراءة. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string) | يفتح الطبقة للقراءة. |
| override [OpenLayer](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/openlayer/#openlayer_1)(AbstractPath, DriverOptions) | يفتح طبقة للقراءة. |
| [OpenLayer](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/openlayer/#openlayer_2)(AbstractPath, MapInfoTabOptions) | يفتح طبقة للقراءة. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string, DriverOptions) | يفتح الطبقة للقراءة. |
| [OpenLayer](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/openlayer/#openlayer_5)(string, MapInfoTabOptions) | يفتح طبقة للقراءة. |
| override [SupportsSpatialReferenceSystem](../../aspose.gis.formats.mapinfotab/mapinfotabdriver/supportsspatialreferencesystem/)(SpatialReferenceSystem) | يحدد ما إذا كان نظام الإحداثيات المكانية المحدد مدعومًا من قبل البرنامج تشغيل. |

### انظر أيضًا

* class [FileDriver](../../aspose.gis/filedriver/)
* namespace [Aspose.Gis.Formats.MapInfoTab](../../aspose.gis.formats.mapinfotab/)
* assembly [Aspose.GIS](../../)


