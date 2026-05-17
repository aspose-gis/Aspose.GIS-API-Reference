---
title: "ProjectedSpatialReferenceSystemParameters Sınıfı"
type: docs
weight: 160
url: /tr/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Yeni bir örnek oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Eksenlerin sırası. Varsayılan değer [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | Temel coğrafi SRS (projeksiyonun uygulandığı SRS).<br/>            Geçerli bir SRS oluşturmak için bu özelliği <see langword="null" /> olmayan bir değere ayarlamalısınız,<br/>            bu özelliğin varsayılan bir değeri yoktur. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Bu SRS'de kullanılacak birimler. Varsayılan değer [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| ad | string | r/w | Projeksiyon SRS'nin adı. Varsayılan değer "Unnamed". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Projeksiyon yönteminin tanımlayıcısı. Varsayılan bir değer yoktur, bu parametreyi <see langword="null" /> olmayan bir değere ayarlayabilirsiniz,<br/>            eğer projeksiyona bir tanımlayıcı eklemek istiyorsanız. Bunu yaparsanız, tanımlayıcının tutarlı bir projeksiyon yöntemi adıyla eşleşmesini sağlamaktan siz sorumlusunuz<br/>            (bu özelliği ayarladığınızda projeksiyon yöntemi adı değişmez). |
| projection_method_name | string | r/w | Projeksiyon yönteminin adı. Varsayılan bir değer yoktur ve bu parametreyi <see langword="null" /> olmayan bir değere ayarlamanız GEREKLİDİR, çünkü<br/>            projeksiyon adı olmayan projekte edilmiş SRS işe yaramaz. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | X (yatay) boyutunu tanımlayan eksen. Varsayılan olarak doğu yönündeki eksen. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Y (dikey) boyutunu tanımlayan eksen. Varsayılan olarak kuzey yönündeki eksen. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Bu SRS'ye projeksiyon parametresi ekler. Aynı isimde bir parametre zaten eklenmişse - günceller. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Belirtilen isimle projeksiyon parametresini alır. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Yeni bir örnek oluşturur.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Bu SRS'ye projeksiyon parametresi ekler. Aynı isimde bir parametre zaten eklenmişse - günceller.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| parameter_name | string | Projeksiyon parametresinin adı. |
| value | double | Parametrenin değeri. Değer birimi, [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            ya da [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) içinde [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) biriminde olmalıdır. |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Belirtilen isimle projeksiyon parametresini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| parameter_name | string | Parametrenin adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Projeksiyon parametresi değeri. |


