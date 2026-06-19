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
| **Name** | **Description** |
| :- | :- |
| [CsvOptions()](#CsvOptions__1) | إنشاء مثال جديد. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | يحدد ما إذا كان سيتم إغلاق [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) غير المغلق في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| column_m | string | قراءة/كتابة | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي M.<br/>            القيمة الافتراضية هي <see langword="null" />. |
| column_wkt | string | قراءة/كتابة | يحصل أو يعيّن اسم العمود الذي يحتوي على النص المعروف (Well-Known Text) لتمثيل الهندسة.<br/>            القيمة الافتراضية هي <see langword="null" />. |
| column_x | string | قراءة/كتابة | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي X.<br/>            القيمة الافتراضية هي <see langword="null" />. |
| column_y | string | قراءة/كتابة | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي Y.<br/>            القيمة الافتراضية هي <see langword="null" />. |
| column_z | string | قراءة/كتابة | يحصل أو يعيّن اسم العمود الذي يحتوي على قيمة إحداثي Z.<br/>            القيمة الافتراضية هي <see langword="null" />. |
| create_midpoints | bool | قراءة/كتابة | يحدد ما إذا كان سيتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points | bool | قراءة/كتابة | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points_distance | double | r/w | يحدد المسافة لـ [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword=\"0\" />. |
| الفاصل | حرف | قراءة/كتابة | يحصل أو يعيّن الحرف المستخدم كفاصل لتقسيم القيم.<br/>            القيمة الافتراضية هي ','. |
| double_quote_escape | حرف | قراءة/كتابة | يحصل أو يعيّن الحرف المستخدم كحرف هروب للاقتباسات المزدوجة.<br/>            القيمة الافتراضية هي '"'. |
| has_attribute_names | bool | قراءة/كتابة | يحدد ما إذا كان هناك صف رأس يحتوي على أسماء السمات.<br/>            القيمة الافتراضية هي <see langword="true" />. |
| linearization_tolerance | double | قراءة/كتابة | هامش يُستخدم لتقويم الأشكال الهندسية المنحنية. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) الذي سيُطبق على إحداثي M<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | قراءة/كتابة | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | يحدد المسافة لـ [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword=\"0\" />. |
| start_line_number | int | قراءة/كتابة | يحصل أو يعيّن رقم سطر يبدأ من الصفر سيكون هو الأول عند قراءة البيانات.<br/>            القيمة الافتراضية هي 0. |
| validate_geometries_on_write | bool | r/w | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة.<br/>            إذا تم تعيينها إلى <see langword=\"true\" />, يتم استدعاء [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) لكل<br/>            شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) هو <see langword=\"false\" />)، يتم رمي [GisException](/psd/python-net/aspose.gis/gisexception/) . |
| write_polygons_as_lines | bool | قراءة/كتابة | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) الذي سيُطبق على إحداثيات X و Y<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) الذي سيُطبق على إحداثي Z<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: CsvOptions() {#CsvOptions__1}


```
 CsvOptions() 
```

إنشاء مثال جديد.

