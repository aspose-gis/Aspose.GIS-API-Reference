---
title: "Kelas KmlNetworkLinkInfo"
type: docs
weight: 60
url: /id/python-net/aspose.gis.formats.kml.specificfields/kmlnetworklinkinfo/
---

**Summary:** Specifies object from Kml 'NetworkLink' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlNetworkLinkInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Mendapatkan anak-anak. |
| link | [LinkInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/linkinfo) | r/w |    |
| name_without_prefix | string | r | Mendapatkan nama tanpa awalan. |
| node_name | string | r/w | Mendapatkan atau mengatur nama. |
| node_value | string | r/w | Mendapatkan atau mengatur nilai. |
| awalan | string | r | Mendapatkan awalan. |
| region | [KmlRegionInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/kmlregioninfo) | r/w |    |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Menambahkan anak. |
| [as_bool()](#as_bool__2) | Mengembalikan nilai yang dikonversi ke bool |
| [as_double()](#as_double__3) | Mengembalikan nilai yang dikonversi ke double. |
| [as_int()](#as_int__4) | Mengembalikan nilai yang dikonversi ke int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Menemukan node XML berdasarkan nama |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Mendapatkan node berdasarkan nama. Harap perhatikan, metode ini akan mengembalikan Node pertama yang ditemukan.<br/>            Tidak peduli pada level apa node tersebut ditemukan |
| [get_node_content()](#get_node_content__7) | Mendapatkan konten node. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Mendapatkan semua node dengan nama yang ditentukan. <br/>            Tidak peduli pada level apa node tersebut ditemukan |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Menambahkan anak.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | Anak. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Mengembalikan nilai yang dikonversi ke bool

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Nilai bool node |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Mengembalikan nilai yang dikonversi ke double.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Nilai double node |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Mengembalikan nilai yang dikonversi ke int.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Nilai int node |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

Menemukan node XML berdasarkan nama

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama node |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Array node XML berdasarkan nama |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Mendapatkan node berdasarkan nama. Harap perhatikan, metode ini akan mengembalikan Node pertama yang ditemukan.<br/>            Tidak peduli pada level apa node tersebut ditemukan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama node yang ingin Anda temukan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Node yang ditemukan dengan NodeLink API |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Mendapatkan konten node.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Konten node |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Mendapatkan semua node dengan nama yang ditentukan. <br/>            Tidak peduli pada level apa node tersebut ditemukan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama-nama. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Array node yang ditemukan. |


