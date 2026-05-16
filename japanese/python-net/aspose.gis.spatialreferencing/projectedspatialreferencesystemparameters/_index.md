---
title: "ProjectedSpatialReferenceSystemParameters クラス"
type: docs
weight: 160
url: /ja/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | 軸の順序。デフォルトは [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) です。 |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | ベースとなる地理的 SRS（投影が適用される SRS）。<br/>            有効な SRS を作成するために、このプロパティを <see langword=\"null\" /> でない値に設定する必要があります。<br/>            このプロパティにはデフォルトがありません。 |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | この SRS で使用される単位。デフォルトは [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) です。 |
| 名前 | string | 読み/書き | 投影された SRS の名前。デフォルトは \"Unnamed\" です。 |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | 投影方式の識別子。デフォルト値はなく、このパラメータを <see langword=\"null\" /> でない値に設定できます、<br/>            投影に識別子を付与したい場合は、そうする場合、識別子が一貫した投影方式にあることを保証するのはあなた次第です。<br/>            名前（このプロパティを設定しても投影方式の名前は変更されません）。 |
| projection_method_name | string | 読み/書き | 投影法の名前。デフォルトはなく、このパラメーターを <see langword="null" /> でない値に設定する必要があります。なぜなら、<br/>            投影名のない投影SRSは無意味だからです。 |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | X（水平）次元を表す軸。デフォルトは東方向の軸です。 |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Y（垂直）次元を表す軸。デフォルトは北方向の軸です。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | このSRSに投影パラメーターを追加します。同名のパラメーターが既に追加されている場合は、更新します。 |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | 指定された名前の投影パラメーターを取得します。 |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

新しいインスタンスを作成します。

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

このSRSに投影パラメーターを追加します。同名のパラメーターが既に追加されている場合は、更新します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| parameter_name | string | 投影パラメーターの名前。 |
| value | double | パラメーターの値。値の単位は [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) <br/>            または [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) の [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) である必要があります。 |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

指定された名前の投影パラメーターを取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| parameter_name | string | パラメーターの名前。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| double | 投影パラメーターの値。 |


