---
title: "فئة ProjectedSpatialReferenceSystemParameters"
type: docs
weight: 160
url: /ar/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | ينشئ نسخة جديدة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | ترتيب المحاور. القيمة الافتراضية هي [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | نظام الإحداثيات الجغرافي الأساسي (SRS الذي تُطبق عليه الإسقاط).<br/>            يجب عليك تعيين هذه الخاصية إلى قيمة غير <see langword=\"null\" /> لإنشاء SRS صالح،<br/>            هذه الخاصية لا تحتوي على أي قيمة افتراضية. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | الوحدات المستخدمة في هذا SRS. القيمة الافتراضية هي [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| الاسم | string | r/w | اسم SRS المُسقَّط. القيمة الافتراضية هي "Unnamed". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | معرف طريقة الإسقاط. لا توجد قيمة افتراضية، يمكنك تعيين هذا المعامل إلى قيمة غير <see langword=\"null\" /> ،<br/>            إذا كنت تريد إرفاق معرف بالإسقاط. إذا فعلت ذلك - يعود الأمر لك لضمان أن يكون المعرف في طريقة إسقاط متسقة<br/>            الاسم (اسم طريقة الإسقاط لن يتغير عندما تقوم بتعيين هذه الخاصية). |
| projection_method_name | string | r/w | اسم طريقة الإسقاط. لا يوجد افتراضي ويجب عليك تعيين هذا المعامل بحيث لا يكون <see langword="null" />، لأن<br/>            نظام الإحداثيات المُسقَّط بدون اسم طريقة إسقاط غير مفيد. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | المحور الذي يصف البُعد X (الأفقي). الافتراضي هو المحور المتجه نحو الشرق. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | المحور الذي يصف البُعد Y (العمودي). الافتراضي هو المحور المتجه نحو الشمال. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | يضيف معامل إسقاط إلى نظام الإحداثيات هذا. إذا كان هناك معامل بهذا الاسم مضاف مسبقًا - يتم تحديثه. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | يحصل على معامل الإسقاط بالاسم المحدد. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

ينشئ نسخة جديدة.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

يضيف معامل إسقاط إلى نظام الإحداثيات هذا. إذا كان هناك معامل بهذا الاسم مضاف مسبقًا - يتم تحديثه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| parameter_name | string | اسم معامل الإسقاط. |
| value | double | قيمة المعامل. يجب أن تكون وحدة القيمة في [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            أو [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) الخاصة بـ [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

يحصل على معامل الإسقاط بالاسم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| parameter_name | string | اسم المعامل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| double | قيمة معامل الإسقاط. |


