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
| **Name** | **Description** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | ينشئ مثلاً جديداً. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | ترتيب المحاور. القيمة الافتراضية هي [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | نظام الإحداثيات الجغرافي الأساسي (SRS الذي يُطبق عليه الإسقاط).<br/>            يجب عليك تعيين هذه الخاصية إلى قيمة ليست <see langword=\"null\" /> لإنشاء SRS صالح،<br/>            هذه الخاصية لا تحتوي على أي قيمة افتراضية. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | الوحدات المستخدمة في هذا SRS. القيمة الافتراضية هي [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| الاسم | string | قراءة/كتابة | اسم SRS المُسقَط. القيمة الافتراضية هي \"Unnamed\". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | معرف طريقة الإسقاط. لا توجد قيمة افتراضية، يمكنك تعيين هذا المعامل إلى قيمة ليست <see langword=\"null\" /> ،<br/>            إذا كنت تريد إرفاق معرف بالإسقاط. إذا فعلت ذلك - الأمر متروك لك لضمان أن المعرف في طريقة إسقاط متسقة<br/>            الاسم (اسم طريقة الإسقاط لن يتغير عندما تقوم بتعيين هذه الخاصية). |
| projection_method_name | string | قراءة/كتابة | اسم طريقة الإسقاط. لا يوجد قيمة افتراضية ويجب عليك تعيين هذا المعامل إلى قيمة ليست <see langword="null" />، لأن<br/>            نظام الإحداثيات الموجه (SRS) المُسقَّط بدون اسم طريقة إسقاط لا فائدة منه. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | المحور الذي يصف البُعد X (الأفقي). القيمة الافتراضية هي المحور المتجه نحو الشرق. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | المحور الذي يصف البُعد Y (العمودي). القيمة الافتراضية هي المحور المتجه نحو الشمال. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | يضيف معامل إسقاط إلى هذا الـ SRS. إذا كان معامل بهذا الاسم مضافًا بالفعل - يتم تحديثه. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | يحصل على معامل الإسقاط بالاسم المحدد. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

ينشئ مثلاً جديداً.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

يضيف معامل إسقاط إلى هذا الـ SRS. إذا كان معامل بهذا الاسم مضافًا بالفعل - يتم تحديثه.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| parameter_name | string | اسم معامل الإسقاط. |
| value | double | قيمة المعامل. يجب أن تكون وحدة القيمة في [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            أو [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) الخاصة بـ [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

يحصل على معامل الإسقاط بالاسم المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| parameter_name | string | اسم المعامل. |

**Returns**

| نوع | وصف |
| :- | :- |
| double | قيمة معامل الإسقاط. |


