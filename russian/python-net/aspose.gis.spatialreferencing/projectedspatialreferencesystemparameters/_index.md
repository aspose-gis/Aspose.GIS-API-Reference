---
title: "Класс ProjectedSpatialReferenceSystemParameters"
type: docs
weight: 160
url: /ru/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Создаёт новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Порядок осей. По умолчанию [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | Базовая географическая SRS (SRS, к которой применяется проекция).<br/>            Вы ДОЛЖНЫ установить это свойство не в значение <see langword="null" />, чтобы создать корректную SRS,<br/>            у этого свойства нет значения по умолчанию. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Единицы, используемые в этой SRS. По умолчанию [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| имя | string | r/w | Имя проецируемой SRS. По умолчанию "Unnamed". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Идентификатор метода проекции. Значение по умолчанию отсутствует, вы можете установить этот параметр не в значение <see langword="null" />,<br/>            если хотите присвоить идентификатор проекции. Если вы сделаете это — вам необходимо обеспечить согласованность идентификатора с методом проекции<br/>            (имя метода проекции не изменится при установке этого свойства). |
| projection_method_name | string | r/w | Имя метода проекции. Значение по умолчанию отсутствует, и вы ДОЛЖНЫ установить этот параметр не равным <see langword="null" />, поскольку<br/>            проецированная СРС без имени проекции бесполезна. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Ось, описывающая измерение X (горизонтальное). По умолчанию — ось, направленная на восток. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Ось, описывающая измерение Y (вертикальное). По умолчанию — ось, направленная на север. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Добавляет параметр проекции в эту СРС. Если параметр с таким именем уже был добавлен — обновить его. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Получает параметр проекции с указанным именем. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Создаёт новый экземпляр.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Добавляет параметр проекции в эту СРС. Если параметр с таким именем уже был добавлен — обновить его.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| parameter_name | string | Имя параметра проекции. |
| value | double | Значение параметра. Единица измерения должна быть в [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            или [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) свойства [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Получает параметр проекции с указанным именем.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| parameter_name | string | Имя параметра. |

**Returns**

| Тип | Описание |
| :- | :- |
| double | Значение параметра проекции. |


