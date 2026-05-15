---
title: "GeoJsonSeqOptions فئة"
type: docs
weight: 20
url: /ar/python-net/aspose.gis.formats.geojsonseq/geojsonseqoptions/
---

**Summary:** Driver-specific options for GeoJsonSeq.

**Module:** [aspose.gis.formats.geojsonseq](/psd/python-net/aspose.gis.formats.geojsonseq/)

**Full Name:** aspose.gis.formats.geojsonseq.GeoJsonSeqOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GeoJsonSeqOptions()](#GeoJsonSeqOptions__1) | إنشاء مثال جديد. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| array_as_string | bool | r/w | ما إذا كان يجب عرض مصفوفات JSON من السلاسل أو الأعداد الصحيحة أو القيم الحقيقية كسلسلة. |
| attributes_skip | bool | r/w | يتحكم في ترجمة السمات: نعم - تخطي جميع السمات |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | إنشاء معرّفات تلقائيًا |
| close_linear_ring | bool | r/w | يحدد ما إذا كان سيغلق حلقة خطية غير مغلقة [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| create_midpoints | bool | r/w | يحدد ما إذا كان سيضيف نقطة جديدة في الوسط لكل مقطع من الشكل. القيمة الافتراضية هي <see langword="false" />. |
| date_as_string | bool | r/w | ما إذا كان يجب عرض تاريخ/وقت/تاريخ-وقت JSON كسلسلة. |
| delete_near_points | bool | r/w | يحدد ما إذا كان سيحذف النقاط القريبة في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points_distance | double | r/w | يحدد المسافة لـ [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword="0" />. |
| geometry_as_collection | bool | r/w | التحكم في ترجمة الأشكال الهندسية: نعم - غلف الأشكال الهندسية بنوع GeometryCollection |
| linearization_tolerance | double | r/w | هامش يُستخدم لتقويم الأشكال الهندسية المنحنية. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) سيُطبق على إحداثي M<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | r/w | يحصل أو يعيّن سلسلة تُستخدم لفصل مكونات السمات المتداخلة.<br/>            القيمة الافتراضية هي "_". |
| simplify_segments | bool | r/w | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي <see langword="false" />. |
| simplify_segments_distance | double | r/w | يحدد المسافة لـ [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة.<br/>            إذا تم تعيينه إلى <see langword="true" />, يتم استدعاء [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) لكل<br/>            شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) هو <see langword="false" />)، يتم رمي [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط مسار مسموحًا به. القيمة الافتراضية هي <see langword="false" />. |
| write_unset_attribute | bool | r/w | ما إذا كان سيتم كتابة السمات غير المحددة بإضافة قيمة 'null' |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) سيُطبق على إحداثي Z<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GeoJsonSeqOptions() {#GeoJsonSeqOptions__1}


```
 GeoJsonSeqOptions() 
```

إنشاء مثال جديد.

