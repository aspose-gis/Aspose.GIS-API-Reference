---
title: "فئة FileGdbOptions"
type: docs
weight: 30
url: /ar/python-net/aspose.gis.formats.filegdb/filegdboptions/
---

**Summary:** Driver-specific options for FileGDB format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [FileGdbOptions()](#FileGdbOptions__1) | إنشاء مثال جديد. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | يحدد ما إذا كان سيغلق حلقة خطية غير مغلقة [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| coordinate_precision_grid | [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | r/w | شبكة دقة إحداثيات للاستخدام في طبقة جديدة. |
| create_midpoints | bool | r/w | يحدد ما إذا كان سيضيف نقطة جديدة في الوسط لكل مقطع من الشكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points | bool | r/w | يحدد ما إذا كان سيحذف النقاط القريبة في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points_distance | double | r/w | يحدد المسافة لـ [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword="0" />. |
| ensure_valid_coordinates_range | bool | r/w | ما إذا كان يجب أن تكون الإحداثيات ضمن النطاق الصحيح. |
| expected_geometry_type | Nullable<Aspose.Gis.Geometries.GeometryType> | r/w | نوع الهندسة المتوقع للطبقة. إذا تم تعيين هذا الخيار فسنسمح بإضافة فقط الهندسات من هذا النوع. |
| geometry_field_name | string | r/w | اسم حقل الهندسة. |
| has_m | bool | r/w | هل يمكن للهندسات في الطبقة أن تحتوي على إحداثي 'm'. القيمة الافتراضية هي true |
| has_z | bool | r/w | هل يمكن للهندسات في الطبقة أن تحتوي على إحداثي 'z'. القيمة الافتراضية هي true |
| linearization_tolerance | double | r/w | هامش يُستخدم لتقويم الأشكال الهندسية المنحنية. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) سيُطبق على إحداثي M<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| m_tolerance | Nullable<double> | r/w | تحمل الالتقاط M. |
| object_id_field_name | string | r/w | اسم حقل معرف الكائن. |
| simplify_segments | bool | r/w | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي <see langword="false" />. |
| simplify_segments_distance | double | r/w | يحدد المسافة لـ [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة.<br/>            إذا تم تعيينه إلى <see langword="true" />, يتم استدعاء [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) لكل<br/>            شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) هو <see langword="false" />)، يتم رمي [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط مسار مسموحًا به. القيمة الافتراضية هي <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| xy_tolerance | Nullable<double> | r/w | تحمل الالتقاط X و Y. |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) سيُطبق على إحداثي Z<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_tolerance | Nullable<double> | r/w | تحمل الالتقاط Z. |


### Constructor: FileGdbOptions() {#FileGdbOptions__1}


```
 FileGdbOptions() 
```

إنشاء مثال جديد.

