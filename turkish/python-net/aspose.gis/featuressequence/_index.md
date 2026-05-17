---
title: "FeaturesSequence Sınıfı"
type: docs
weight: 870
url: /tr/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Bu [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) içindeki özellikler için özel öznitelik koleksiyonunu alır. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Bu özellik dizisinin uzamsal referans sistemini alır. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_extent()](#get_extent__1) | Bu katmanın uzamsal kapsamını alır. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Özellik dizisini katmana kaydeder. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Özellik dizisini katmana kaydeder. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Özellik dizisini katmana kaydeder. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Özellik dizisini katmana kaydeder. |
| [split_to()](#split_to__6) | Özellikleri geometri tipine göre böl. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Sağlanan değere eşit nitelik değerine sahip özellikleri seçer. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Sağlanan değerden büyük nitelik değerine sahip özellikleri seçer. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Sağlanan değere eşit veya daha büyük nitelik değerine sahip özellikleri seçer. |
| [where_intersects(extent)](#where_intersects_extent_10) | Özellikleri kapsamına göre filtreler. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Sağlanan geometriye göre özellikleri filtreler. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Diğer özellik dizisindeki tüm geometrilerin birleşimine göre özellikleri filtreler. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Sağlanan değere eşit olmayan öznitelik değerine sahip özellikleri seçer. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Öznitelik değeri null olmayan özellikleri seçer. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Öznitelik değeri null olan özellikleri seçer. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Özniteliği ayarlanmış özellikleri seçer. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Sağlanan değerden daha küçük öznitelik değerine sahip özellikleri seçer. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Sağlanan değere eşit veya daha küçük öznitelik değerine sahip özellikleri seçer. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Belirtilen öznitelik ayarlanmamış özellikleri seçer. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Bu katmanın uzamsal kapsamını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Bu katmanın uzamsal kapsamı. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Özellik dizisini katmana kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_path | string | Çıktı katmanının yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Çıktı katmanı için format sürücüsü. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Özellik dizisini katmana kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Çıktı katmanının yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Çıktı katmanı için format sürücüsü. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

Özellik dizisini katmana kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_path | string | Çıktı katmanının yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Çıktı katmanı için format sürücüsü. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Kaydetme prosedürü için seçenekler. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

Özellik dizisini katmana kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Çıktı katmanının yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Çıktı katmanı için format sürücüsü. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Kaydetme prosedürü için seçenekler. |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Özellikleri geometri tipine göre böl.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Aynı geometri tipine sahip katmanlar. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

Sağlanan değere eşit nitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değere eşit öznitelik değerine sahip ögeler. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

Sağlanan değerden büyük nitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değerden büyük öznitelik değerine sahip ögeler. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

Sağlanan değere eşit veya daha büyük nitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değere eşit ya da daha büyük öznitelik değerine sahip ögeler. |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

Özellikleri kapsamına göre filtreler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filtreleme kapsamı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan geometriyle kesişen özellikler. |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

Sağlanan geometriye göre özellikleri filtreler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometriyi filtrele. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan geometriyle kesişen özellikler. |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

Diğer özellik dizisindeki tüm geometrilerin birleşimine göre özellikleri filtreler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Diğer özellikler dizisi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Diğer özellikler dizisindeki tüm geometrilerin birleşimiyle kesişen özellikler. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

Sağlanan değere eşit olmayan öznitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değere eşit olmayan öznitelik değerine sahip özellikler. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

Öznitelik değeri null olmayan özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Öznitelik değeri null olmayan özellikler. |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

Öznitelik değeri null olan özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Öznitelik değeri null olan özellikler. |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

Özniteliği ayarlanmış özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Ayarlanmış öznitelik değerine sahip özellikler. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

Sağlanan değerden daha küçük öznitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değerden daha küçük öznitelik değerine sahip özellikler. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

Sağlanan değere eşit veya daha küçük öznitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değerden daha küçük veya eşit öznitelik değerine sahip özellikler. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

Belirtilen öznitelik ayarlanmamış özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Ayarlanmamış öznitelik değerine sahip özellikler. |


