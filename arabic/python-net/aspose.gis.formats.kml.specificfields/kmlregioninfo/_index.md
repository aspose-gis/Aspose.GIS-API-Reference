---
title: "KmlRegionInfo فئة"
type: docs
weight: 70
url: /ar/python-net/aspose.gis.formats.kml.specificfields/kmlregioninfo/
---

**Summary:** Specifies object from Kml 'Region' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlRegionInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | يحصل على الأطفال. |
| id | string | r/w | Id من عقدة 'Region'. |
| lat_lon_alt_box | [KmlLatLonAltBox](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllatlonaltbox) | r/w | يحدد الكائن من عقدة Kml 'LatLonAltBox'. |
| lod | [KmlLodSettings](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllodsettings) | r/w | يحدد الكائن من عقدة Kml 'Lod'. |
| name_without_prefix | string | r | يحصل على الاسم بدون البادئة. |
| node_name | string | r/w | يحصل أو يعيّن الاسم. |
| node_value | string | r/w | يحصل أو يعيّن القيمة. |
| بادئة | string | r | يحصل على البادئة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | يضيف الطفل. |
| [as_bool()](#as_bool__2) | يرجع القيمة محوّلة إلى bool |
| [as_double()](#as_double__3) | يرجع القيمة محوّلة إلى double. |
| [as_int()](#as_int__4) | يعيد القيمة محوَّلة إلى int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | يبحث عن عقد XML بالاسم |
| [get_node_by_name(name)](#get_node_by_name_name_6) | يحصل على العقدة بالاسم. يرجى ملاحظة أن هذه الطريقة ستعيد أول عقدة تم العثور عليها.<br/>            لا يهم في أي مستوى سيتم العثور عليها |
| [get_node_content()](#get_node_content__7) | يحصل على محتوى العقدة. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | يحصل على جميع العقد بالاسم المحدد. <br/>            لا يهم في أي مستوى سيتم العثور عليها |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

يضيف الطفل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | العنصر الفرعي. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

يرجع القيمة محوّلة إلى bool

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | القيمة المنطقية للعقدة |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

يرجع القيمة محوّلة إلى double.

**Returns**

| نوع | الوصف |
| :- | :- |
| double | القيمة double للعقدة |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

يعيد القيمة محوَّلة إلى int.

**Returns**

| نوع | الوصف |
| :- | :- |
| int | القيمة int للعقدة |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

يبحث عن عقد XML بالاسم

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم العقدة |

**Returns**

| نوع | الوصف |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | مصفوفة من عقد XML بالاسم |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

يحصل على العقدة بالاسم. يرجى ملاحظة أن هذه الطريقة ستعيد أول عقدة تم العثور عليها.<br/>            لا يهم في أي مستوى سيتم العثور عليها

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم العقدة التي تريد العثور عليها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | العقدة التي تم العثور عليها باستخدام واجهة NodeLink API |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

يحصل على محتوى العقدة.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | محتوى العقدة |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

يحصل على جميع العقد بالاسم المحدد. <br/>            لا يهم في أي مستوى سيتم العثور عليها

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الأسماء | string | الأسماء. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | مصفوفة العقد التي تم العثور عليها. |


