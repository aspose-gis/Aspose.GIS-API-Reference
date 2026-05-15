---
title: "FeatureAttribute 类"
type: docs
weight: 840
url: /zh/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | 初始化 [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) 类的新实例。 |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | 初始化 [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | 获取一个值，指示此实例是否可以为 null。 |
| can_be_unset | bool | r/w | 获取或设置一个值，指示此属性的值是否可以省略。 |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | 获取属性的数据类型。 |
| default_value | object | r/w | 获取或设置属性的值，以指示缺失的数据。 |
| has_custom_default_value | bool | r | 获取一个值，指示此属性的预定义默认值是否已被自定义值覆盖。 |
| is_locked | bool | r | 获取一个值，指示此属性是否被锁定。 |
| 名称 | string | r/w | 获取属性的名称。 |
| precision | Nullable<int> | r/w | 获取或设置要存储的最大小数位数。 |
| type_name | string | r/w | 属性的类型名称。 |
| width | Nullable<int> | r/w | 获取或设置属性字符表示的最大允许宽度。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| lock() | 锁定此属性。 |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

初始化 [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 属性的名称。 |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 属性的数据类型。 |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

初始化 [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 属性的名称。 |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 属性的数据类型。 |
| can_be_null | bool | <see langword="true" /> 如果此实例可以为 null；否则 <see langword="false" />。 |

