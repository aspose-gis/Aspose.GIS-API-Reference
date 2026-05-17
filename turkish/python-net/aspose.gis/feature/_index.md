---
title: "Feature Sınıfı"
type: docs
weight: 830
url: /tr/python-net/aspose.gis/feature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Özelliğin geometrisini alır veya ayarlar.<br/>            <see langword="null" /> olamaz, eksik geometriyi göstermek için [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) kullanın. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Başka bir özelliğin nitelik değerlerini kopyalar. |
| [get_value(attribute_name)](#get_value_attribute_name_2) | Bir niteliğin değerini alır. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_3) | Bir niteliğin değerini alır, değer ayarlanmamışsa veya <c>null</c> ise [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) döner. |
| [get_values(values, default_value)](#get_values_values_default_value_4) | Tüm niteliklerin değerlerini bir dizi olarak döndürür. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_5) | Tüm niteliklerin değerlerini bir dizi olarak döndürür. |
| [get_values_dump(default_value)](#get_values_dump_default_value_6) | Tüm niteliklerin değerlerini bir dizi olarak döndürür.<br/>            Ek bellek tahsisinden kaçınmak için Aspose.Gis.Feature.GetValues(int,System.Object) yöntemini kullanmayı düşünün. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_7) | Değerler listesini alır. List T GetValuesList'in jenerik olmayan analoğu |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_8) | Belirtilen özelliğin açıkça <c>null</c> değerine ayarlanıp ayarlanmadığını belirler. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_9) | Bu özellikte öznitelik değerinin ayarlanıp ayarlanmadığını denetler. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_10) | Değeri ayarlar. void SetValue (string attributeName, T value) metodunun jenerik olmayan analoğu |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_11) | Öznitelik değerini <c>null</c> olarak ayarlar. |
| [set_values(values)](#set_values_values_12) | Tüm öznitelikler için yeni değerler ayarlar.<br/>            Ayrıca değerleri tek bir çağrıda ayarlamayı kolaylaştırmak için [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) yöntemini kullanmayı düşünün. |
| [unset_value(attribute_name)](#unset_value_attribute_name_13) | Bu özelliğin öznitelik değerini kaldırır. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Başka bir özelliğin nitelik değerlerini kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | Değerlerin kopyalanacağı özellik. |

### Method: get_value(attribute_name) {#get_value_attribute_name_2}


```
 get_value(attribute_name) 
```

Bir niteliğin değerini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Öznitelik adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| object | Öznitelik değeri. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_3}


```
 get_value_or_default(attribute_name, default_value) 
```

Bir niteliğin değerini alır, değer ayarlanmamışsa veya <c>null</c> ise [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) döner.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Öznitelik adı. |
| default_value | object | Öznitelik değeri eksikse döndürülecek değer. Varsayılan değer <see langword="null" />'dır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| object | Öznitelik değeri. |


### Method: get_values(values, default_value) {#get_values_values_default_value_4}


```
 get_values(values, default_value) 
```

Tüm niteliklerin değerlerini bir dizi olarak döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değerler | object |  |
| default_value | object | Öznitelik değeri eksik (ayarlanmamış) ise döndürülecek değer. Varsayılan değer <see langword="null" />'dır.<br/>            'unset' ve '<see langword="null" />' değerlerini ayırmak için '.Value' kullanılmasını düşünün. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Kopyalanan öznitelik sayısı. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_5}


```
 get_values(values_count, default_value) 
```

Tüm niteliklerin değerlerini bir dizi olarak döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| values_count | int | Değer sayısı. |
| default_value | object | Öznitelik değeri eksik (ayarlanmamış) ise döndürülecek değer. Varsayılan değer <see langword="null" />'dır.<br/>            'unset' ve '<see langword="null" />' değerlerini ayırmak için '.Value' kullanılmasını düşünün. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| object | Kopyalanan öznitelik sayısı. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_6}


```
 get_values_dump(default_value) 
```

Tüm niteliklerin değerlerini bir dizi olarak döndürür.<br/>            Ek bellek tahsisinden kaçınmak için Aspose.Gis.Feature.GetValues(int,System.Object) yöntemini kullanmayı düşünün.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| default_value | object | Öznitelik değeri eksik (ayarlanmamış) ise döndürülecek değer. Varsayılan değer <see langword="null" />'dır.<br/>            'unset' ve '<see langword="null" />' değerlerini ayırmak için '.Value' kullanılmasını düşünün. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| object | Öznitelik değerlerinin kopyalanacağı yeni bir dizi. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_7}


```
 get_values_list(attribute_name, separator, count) 
```

Değerler listesini alır. List T GetValuesList'in jenerik olmayan analoğu

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Öznitelik adı. |
| separator | string | Dizinin öznitelik adı ve indeks değerini ayırmak için kullanılan bir dize. |
| sayım | int | Döndürülecek değer sayısı (eksik değerler null olarak doldurulur) |

**Returns**

| Tür | Açıklama |
| :- | :- |
| object | Dizi indeks değerine göre farklı isimlere sahip özniteliklerin değer listesi. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_8}


```
 is_value_null(attribute_name) 
```

Belirtilen özelliğin açıkça <c>null</c> değerine ayarlanıp ayarlanmadığını belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Öznitelik adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword="true" /> eğer öznitelik değeri <c>null</c>; aksi takdirde <see langword="false" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_9}


```
 is_value_set(attribute_name) 
```

Bu özellikte öznitelik değerinin ayarlanıp ayarlanmadığını denetler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Öznitelik adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword="true" /> eğer belirtilen öznitelik değeri ayarlanmışsa; aksi takdirde <see langword="false" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_10}


```
 set_value(attribute_name, value) 
```

Değeri ayarlar. void SetValue (string attributeName, T value) metodunun jenerik olmayan analoğu

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Özniteliğin adı. |
| value | object | Öznitelik değeri. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_11}


```
 set_value_null(attribute_name) 
```

Öznitelik değerini <c>null</c> olarak ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Özniteliğin adı. |

### Method: set_values(values) {#set_values_values_12}


```
 set_values(values) 
```

Tüm öznitelikler için yeni değerler ayarlar.<br/>            Ayrıca değerleri tek bir çağrıda ayarlamayı kolaylaştırmak için [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) yöntemini kullanmayı düşünün.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| değerler | object | Yeni değerlerin dizisi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Ayarlanan öznitelik değerlerinin sayısı. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_13}


```
 unset_value(attribute_name) 
```

Bu özelliğin öznitelik değerini kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Öznitelik adı. |

