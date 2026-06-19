---
title: "الفئة GmlDriver"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Formats.Gml.GmlDriver. سائق لتنسيق GML"
type: docs
weight: 1950
url: /ar/net/aspose.gis.formats.gml/gmldriver/
---
## GmlDriver class

برنامج تشغيل لتنسيق GML.

```csharp
public sealed class GmlDriver : FileDriver
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [CanCreateDatasets](../../aspose.gis.formats.gml/gmldriver/cancreatedatasets/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه إنشاء مجموعات البيانات. |
| override [CanCreateLayers](../../aspose.gis.formats.gml/gmldriver/cancreatelayers/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه إنشاء طبقات متجهية. |
| virtual [CanOpenDatasets](../../aspose.gis/filedriver/canopendatasets/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه فتح مجموعات البيانات. |
| override [CanOpenLayers](../../aspose.gis.formats.gml/gmldriver/canopenlayers/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا البرنامج تشغيل يمكنه فتح طبقات متجهية. |

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
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis.formats.gml/gmldriver/createlayer/#createlayer_7)(string, GmlOptions) | ينشئ طبقة ويفتحها لإضافة ميزات جديدة. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| override [CreateLayer](../../aspose.gis.formats.gml/gmldriver/createlayer/#createlayer_2)(AbstractPath, DriverOptions, SpatialReferenceSystem) | ينشئ طبقة ويفتحها لإضافة ميزات جديدة. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| [CreateLayer](../../aspose.gis.formats.gml/gmldriver/createlayer/#createlayer_8)(string, GmlOptions, SpatialReferenceSystem) | ينشئ طبقة ويفتحها لإضافة ميزات جديدة. |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer/)(AbstractPath, DriverOptions) | يفتح طبقة للتحرير. |
| [EditLayer](../../aspose.gis/filedriver/editlayer/)(string, DriverOptions) | يفتح طبقة للتحرير. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath) | يفتح مجموعة البيانات. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string) | يفتح مجموعة البيانات. |
| virtual [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath, DriverOptions) | يفتح مجموعة البيانات. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string, DriverOptions) | يفتح مجموعة البيانات. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(AbstractPath) | يفتح الطبقة للقراءة. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string) | يفتح الطبقة للقراءة. |
| override [OpenLayer](../../aspose.gis.formats.gml/gmldriver/openlayer/#openlayer_1)(AbstractPath, DriverOptions) | يفتح طبقة للقراءة. |
| [OpenLayer](../../aspose.gis.formats.gml/gmldriver/openlayer/#openlayer_2)(AbstractPath, GmlOptions) | يفتح طبقة للقراءة. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string, DriverOptions) | يفتح الطبقة للقراءة. |
| [OpenLayer](../../aspose.gis.formats.gml/gmldriver/openlayer/#openlayer_5)(string, GmlOptions) | يفتح طبقة للقراءة. |
| override [SupportsSpatialReferenceSystem](../../aspose.gis.formats.gml/gmldriver/supportsspatialreferencesystem/)(SpatialReferenceSystem) | يحدد ما إذا كان نظام الإحداثيات المكانية المحدد مدعومًا من قبل البرنامج تشغيل. |

### انظر أيضًا

* class [FileDriver](../../aspose.gis/filedriver/)
* namespace [Aspose.Gis.Formats.Gml](../../aspose.gis.formats.gml/)
* assembly [Aspose.GIS](../../)


