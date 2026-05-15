---
title: "BaseFeatureAttributeCollection 类"
type: docs
weight: 90
url: /zh/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| count | int | r | 获取 [Feature](/psd/python-net/aspose.gis/feature/) 中属性的数量。 |
| is_locked | bool | r | 获取一个值，指示此属性集合是否已锁定。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | 向集合中添加属性。 |
| [contains(name)](#contains_name_2) | 确定属性集合是否包含具有指定名称的属性。 |
| [index_of(name)](#index_of_name_3) | 搜索属性并返回其零基索引。 |
| lock() | 锁定此属性集合以防止进一步修改。 |
| [remove(index)](#remove_index_4) | 从集合中移除属性。 |
| [remove(name)](#remove_name_5) | 从集合中移除属性。 |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

向集合中添加属性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | 要添加的属性。 |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

确定属性集合是否包含具有指定名称的属性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 属性的名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果属性集合包含具有指定名称的属性；否则，<see langword=\"false\" />。 |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

搜索属性并返回其零基索引。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 属性的名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 属性在集合中的零基索引（如果找到）；否则为 –1。 |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

从集合中移除属性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 属性的索引。 |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

从集合中移除属性。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 属性的名称。 |

