---
title: "فئة WarpOptions"
type: docs
weight: 100
url: /ar/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | يُهيئ نسخة جديدة من فئة WarpOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| cell_height | double | r/w | يحدد ارتفاعًا جديدًا لخلية الراستر (بوحدات الإحداثيات المستهدفة).<br/>            إذا تم تعيين القيمة إلى 0، يتم حساب [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) تلقائيًا. القيمة الافتراضية هي "0". |
| cell_width | double | r/w | يحدد عرضًا جديدًا لخلية الراستر (بوحدات الإحداثيات المستهدفة).<br/>            إذا تم تعيين القيمة إلى 0، يتم حساب [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) تلقائيًا. القيمة الافتراضية هي "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | يحدد قيمة للمرجع المكاني المصدر إذا كان مفقودًا. |
| الارتفاع | int | r/w | يحدد ارتفاع الراستر الناتج بالبكسل والأعمدة.<br/>            إذا تم تعيين القيمة إلى 0، يتم حساب الارتفاع تلقائيًا. القيمة الافتراضية هي "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | يحدد حدود طبقة الراستر للالتواء.<br/>            إذا تم تعيينها إلى <see langword="null" />, يتم حساب الامتداد أثناء الالتواء لتضمين جميع الخلايا من الراستر. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | يحدد المرجع المكاني المستهدف.<br/>            إذا تم تعيينه إلى <see langword="null" />, يتم استخدام المرجع المكاني الافتراضي أو المصدر. |
| العرض | int | r/w | يحدد عرض الراستر الناتج بالبكسل والأعمدة.<br/>            إذا تم تعيين القيمة إلى 0، يتم حساب العرض تلقائيًا. القيمة الافتراضية هي "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

يُهيئ نسخة جديدة من فئة WarpOptions

