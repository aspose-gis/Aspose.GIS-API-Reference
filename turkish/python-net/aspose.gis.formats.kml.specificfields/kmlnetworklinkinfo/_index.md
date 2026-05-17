---
title: "KmlNetworkLinkInfo Sınıfı"
type: docs
weight: 60
url: /tr/python-net/aspose.gis.formats.kml.specificfields/kmlnetworklinkinfo/
---

**Summary:** Specifies object from Kml 'NetworkLink' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlNetworkLinkInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Çocukları alır. |
| link | [LinkInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/linkinfo) | r/w |    |
| name_without_prefix | string | r | Ön ek olmadan adı alır. |
| node_name | string | r/w | Adı alır veya ayarlar. |
| node_value | string | r/w | Değeri alır veya ayarlar. |
| ön ek | string | r | Ön eki alır. |
| region | [KmlRegionInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/kmlregioninfo) | r/w |    |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Çocuğu ekler. |
| [as_bool()](#as_bool__2) | Değeri bool tipine dönüştürerek döndürür |
| [as_double()](#as_double__3) | Değeri double tipine dönüştürerek döndürür. |
| [as_int()](#as_int__4) | Tam sayıya dönüştürülmüş değeri döndürür. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | İsme göre XML düğümlerini bulur. |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Düğümü ada göre alır. Lütfen unutmayın, bu yöntem bulunan ilk Düğümü döndürür.<br/>            Hangi seviyede bulunursa bulunsun fark etmez |
| [get_node_content()](#get_node_content__7) | Düğümün içeriğini alır. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Belirtilen ada sahip tüm düğümleri alır. <br/>            Hangi seviyede bulunursa bulunsun fark etmez |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Çocuğu ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | Çocuk. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Değeri bool tipine dönüştürerek döndürür

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Düğümün bool değeri |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Değeri double tipine dönüştürerek döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Düğümün double değeri |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Tam sayıya dönüştürülmüş değeri döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Düğümün int değeri |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

İsme göre XML düğümlerini bulur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Düğümün adı |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | İsme göre XML Düğümleri dizisi. |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Düğümü ada göre alır. Lütfen unutmayın, bu yöntem bulunan ilk Düğümü döndürür.<br/>            Hangi seviyede bulunursa bulunsun fark etmez

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Bulmak istediğiniz düğümün adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | NodeLink API ile bulunan düğüm |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Düğümün içeriğini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Düğümün içeriği |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Belirtilen ada sahip tüm düğümleri alır. <br/>            Hangi seviyede bulunursa bulunsun fark etmez

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| adlar | string | İsimler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Bulunan düğümlerin dizisi. |


