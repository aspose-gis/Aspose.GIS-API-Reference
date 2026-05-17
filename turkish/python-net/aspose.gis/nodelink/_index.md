---
title: "NodeLink Sınıfı"
type: docs
weight: 2800
url: /tr/python-net/aspose.gis/nodelink/
---

**Summary:** Node-based link to the parts of resources

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Çocukları alır. |
| node_name | string | r/w | Adı alır veya ayarlar. |
| node_value | string | r/w | Değeri alır veya ayarlar. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Çocuğu ekler. |
| [as_bool()](#as_bool__2) | Değeri bool tipine dönüştürerek döndürür |
| [as_double()](#as_double__3) | Değeri double tipine dönüştürerek döndürür. |
| [as_int()](#as_int__4) | Tam sayıya dönüştürülmüş değeri döndürür. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Düğümleri ada göre bulur |
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

Düğümleri ada göre bulur

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Düğümün adı |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Ada göre biçimlendirilmiş Düğümler dizisi |


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


