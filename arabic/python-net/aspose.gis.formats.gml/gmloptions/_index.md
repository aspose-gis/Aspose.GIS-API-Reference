---
title: "فئة GmlOptions"
type: docs
weight: 20
url: /ar/python-net/aspose.gis.formats.gml/gmloptions/
---

**Summary:** Driver-specific options for GML format.

**Module:** [aspose.gis.formats.gml](/psd/python-net/aspose.gis.formats.gml/)

**Full Name:** aspose.gis.formats.gml.GmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GmlOptions()](#GmlOptions__1) | إنشاء مثال جديد. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| application_namespace | string | قراءة/كتابة | هذا يحدد مساحة أسماء مخصصة تُستخدم كمساحة أسماء التطبيق لإنشاء مستند gml. |
| close_linear_ring | bool | r/w | يحدد ما إذا كان سيتم إغلاق [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) غير المغلق في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| create_midpoints | bool | قراءة/كتابة | يحدد ما إذا كان سيتم إضافة نقطة جديدة في الوسط لكل مقطع من الشكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points | bool | قراءة/كتابة | يحدد ما إذا كان سيتم حذف النقاط القريبة في كل شكل. القيمة الافتراضية هي <see langword="false" />. |
| delete_near_points_distance | double | r/w | يحدد المسافة لـ [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword=\"0\" />. |
| linearization_tolerance | double | قراءة/كتابة | هامش يُستخدم لتقويم الأشكال الهندسية المنحنية. |
| load_schemas_from_internet | bool | قراءة/كتابة | يحدد ما إذا كان مسموحًا لـ Aspose.GIS بتحميل مخطط XML من الإنترنت.<br/>            إذا تم تعيينه إلى <see langword=\"false\" />, فإن المخططات ذات عناوين URI المطلقة التي لا تبدأ بـ 'file://' لن يتم تحميلها.<br/>            القيمة الافتراضية هي <see langword=\"false\" />. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) الذي سيُطبق على إحداثي M<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | قراءة/كتابة | يحصل أو يعيّن سلسلة تُستخدم لفصل مكونات السمات المتداخلة.<br/>            القيمة الافتراضية هي \"_\". |
| restore_schema | bool | قراءة/كتابة | يحدد ما إذا كان مسموحًا لـ Aspose.GIS بتحليل السمات في ملف Gml لا يتوفر فيه مخطط XML أو لا يمكن تحميله.<br/>            إذا تم تعيينه إلى <see langword=\"true\" />, فإن قارئ Aspose.GIS لا يتطلب وجود مخطط XML.<br/>            القيمة الافتراضية هي <see langword=\"false\" />. |
| schema_location | string | r/w | قائمة مفصولة بمسافات من أزواج URI. الـ URI الأول في كل زوج هو URI لمساحة الأسماء، والـ URI الثاني هو مسار إلى مخطط XML لمساحة الأسماء.<br/>            إذا تم تعيينه إلى <see langword=\"null\" />, سيحاول [GmlDriver](/psd/python-net/aspose.gis.formats.gml/gmldriver/) قراءة schemaLocation من العنصر الجذر للمستند.<br/>            القيمة الافتراضية هي <see langword=\"null\" />. |
| simplify_segments | bool | قراءة/كتابة | يحدد ما إذا كان سيتم حذف النقاط الواقعة على نفس القطعة في كل شكل هندسي. القيمة الافتراضية هي <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | يحدد المسافة لـ [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). القيمة الافتراضية هي <see langword=\"0\" />. |
| validate_geometries_on_write | bool | r/w | يحدد ما إذا كان يجب التحقق من صحة الأشكال الهندسية عند إضافتها إلى الطبقة.<br/>            إذا تم تعيينها إلى <see langword=\"true\" />, يتم استدعاء [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) لكل<br/>            شكل هندسي عند إضافته إلى الطبقة، وإذا فشل التحقق ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) هو <see langword=\"false\" />)، يتم رمي [GisException](/psd/python-net/aspose.gis/gisexception/) . |
| write_polygons_as_lines | bool | قراءة/كتابة | يحدد ما إذا كان تحويل المضلع أو المضلع المتعدد إلى خط متعدد مسموحًا به. القيمة الافتراضية هي <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) الذي سيُطبق على إحداثيات X و Y<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | نموذج [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) الذي سيُطبق على إحداثي Z<br/>            عندما تُضاف الأشكال الهندسية إلى [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) أو عندما تُقرأ من [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            القيمة الافتراضية هي [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GmlOptions() {#GmlOptions__1}


```
 GmlOptions() 
```

إنشاء مثال جديد.

