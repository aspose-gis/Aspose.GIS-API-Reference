---
title: "GpxOptions فئة"
type: docs
weight: 20
url: /ar/python-net/aspose.gis.formats.gpx/gpxoptions/
---

**Summary:** Driver-specific options for GPX format.

**Module:** [aspose.gis.formats.gpx](/psd/python-net/aspose.gis.formats.gpx/)

**Full Name:** aspose.gis.formats.gpx.GpxOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GpxOptions()](#GpxOptions__1) | إنشاء مثال جديد. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | يحدد ما إذا كان سيتم إغلاق [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) غير المغلق في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| create_midpoints | bool | قراءة/كتابة | يحدد ما إذا كان سيتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points | bool | قراءة/كتابة | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points_distance | double | r/w | يحدد المسافة لـ [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword=\"0\" />. |
| linearization_tolerance | double | قراءة/كتابة | هامش يُستخدم لتقويم الأشكال الهندسية المنحنية. |
| m_attribute | string | r/w | يحدد أي سمة GPX سيتم تصديرها كإحداثي 'M' لنقاط الطريق، نقاط المسار ونقاط التعقب.<br/>            السلوك هو نفسه مع [GpxOptions.z_attribute](/psd/python-net/aspose.gis.formats.gpx/gpxoptions/), الافتراضي هو <see langword=\"null\" />. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) الذي سيُطبق على إحداثي M<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_attribute_separator | string | r | سلسلة لفصل اسم السمة المتداخلة ومؤشراتها. الافتراضي هو الشرطتين السفلية \"__\". |
| read_nested_attributes | bool | قراءة/كتابة | يحدد ما إذا كانت نقاط GPX، مثل 'trkpt' و 'rtept'، تحتوي على سمات داخلية وما إذا كان يجب قراءتها. الافتراضي هو <see langword=\"false\" />. |
| simplify_segments | bool | قراءة/كتابة | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | يحدد المسافة لـ [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword=\"0\" />. |
| validate_geometries_on_write | bool | r/w | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة.<br/>            إذا تم تعيينها إلى <see langword=\"true\" />, يتم استدعاء [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) لكل<br/>            شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) هو <see langword=\"false\" />)، يتم رمي [GisException](/psd/python-net/aspose.gis/gisexception/) . |
| write_polygons_as_lines | bool | قراءة/كتابة | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) الذي سيُطبق على إحداثيات X و Y<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_attribute | string | قراءة/كتابة | يحدد أي سمة GPX سيتم تصديرها كإحداثي 'Z' لنقاط الطريق، نقاط المسار ونقاط التعقب.<br/>            إذا كان <see langword=\"null\" /> - لن يتم تصدير أي سمة كإحداثي 'Z'.<br/>            الافتراضي هو \"ele\".<br/>            القيم الممكنة هي أسماء جميع سمات XML الخاصة بـ GPX التي يمكن تمثيلها كعدد مزدوج (مثل \"speed\", \"magvar\", \"geoidheight\" وغيرها). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) الذي سيُطبق على إحداثي Z<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GpxOptions() {#GpxOptions__1}


```
 GpxOptions() 
```

إنشاء مثال جديد.

