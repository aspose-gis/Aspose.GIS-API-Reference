---
title: "فئة CsvOptions"
type: docs
weight: 20
url: /ar/python-net/aspose.gis.formats.csv/csvoptions/
---

**Summary:** Driver-specific options for CSV format.

**Module:** [aspose.gis.formats.csv](/psd/python-net/aspose.gis.formats.csv/)

**Full Name:** aspose.gis.formats.csv.CsvOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [CsvOptions()](#CsvOptions__1) | إنشاء مثال جديد. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | يحدد ما إذا كان سيغلق حلقة خطية غير مغلقة [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| column_m | string | r/w | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي M.<br/>            القيمة الافتراضية هي <see langword=\"null\" />. |
| column_wkt | string | r/w | يحصل أو يعيّن اسم العمود الذي يحتوي على النص المعروف جيدًا (Well-Known Text) لتمثيل الهندسة.<br/>            القيمة الافتراضية هي <see langword=\"null\" />. |
| column_x | string | r/w | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي X.<br/>            القيمة الافتراضية هي <see langword=\"null\" />. |
| column_y | string | r/w | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي Y.<br/>            القيمة الافتراضية هي <see langword=\"null\" />. |
| column_z | string | r/w | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي Z.<br/>            القيمة الافتراضية هي <see langword=\"null\" />. |
| create_midpoints | bool | r/w | يحدد ما إذا كان سيضيف نقطة جديدة في الوسط لكل مقطع من الشكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points | bool | r/w | يحدد ما إذا كان سيحذف النقاط القريبة في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points_distance | double | r/w | يحدد المسافة لـ [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword="0" />. |
| فاصل | char | r/w | يحصل أو يعيّن حرفًا يُستخدم كفاصل لتقسيم القيم.<br/>            القيمة الافتراضية هي ','. |
| double_quote_escape | char | r/w | يحصل أو يعيّن حرفًا يُستخدم كحرف هروب للاقتباسات المزدوجة.<br/>            القيمة الافتراضية هي '\"'. |
| has_attribute_names | bool | r/w | يحدد ما إذا كان هناك صف رأس يحتوي على أسماء السمات.<br/>            القيمة الافتراضية هي <see langword=\"true\" />. |
| linearization_tolerance | double | r/w | هامش يُستخدم لتقويم الأشكال الهندسية المنحنية. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) سيُطبق على إحداثي M<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | r/w | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي <see langword="false" />. |
| simplify_segments_distance | double | r/w | يحدد المسافة لـ [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword="0" />. |
| start_line_number | int | r/w | يحصل أو يضبط رقم سطر يبدأ من الصفر سيكون الأول عند قراءة البيانات.<br/>            القيمة الافتراضية هي 0. |
| validate_geometries_on_write | bool | r/w | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة.<br/>            إذا تم تعيينه إلى <see langword="true" />, يتم استدعاء [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) لكل<br/>            شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) هو <see langword="false" />)، يتم رمي [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط مسار مسموحًا به. القيمة الافتراضية هي <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) سيُطبق على إحداثيات X و Y<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) سيُطبق على إحداثي Z<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: CsvOptions() {#CsvOptions__1}


```
 CsvOptions() 
```

إنشاء مثال جديد.

