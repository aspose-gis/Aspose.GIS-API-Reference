---
title: "فئة KmlGroundOverlayInfo"
type: docs
weight: 20
url: /ar/python-net/aspose.gis.formats.kml.specificfields/kmlgroundoverlayinfo/
---

**Summary:** Specifies object from Kml 'GroundOverlay' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlGroundOverlayInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | يحصل على العناصر الفرعية. |
| draw_order | double | قراءة/كتابة | DrawOrder من عقدة 'GroundOverlay'. |
| icon | [IconInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/iconinfo) | r/w | IconPath من عقدة 'GroundOverlay'. |
| lat_lon_box | [KmlLatLonBox](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllatlonbox) | r/w | يحدد الكائن من عقدة Kml 'LatLonAltBox'. |
| الاسم | string | قراءة/كتابة | اسم Ground Overlay |
| name_without_prefix | string | r | يحصل على الاسم بدون البادئة. |
| node_name | string | قراءة/كتابة | يحصل أو يضبط الاسم. |
| node_value | string | قراءة/كتابة | يحصل أو يضبط القيمة. |
| بادئة | string | r | يحصل على البادئة. |
| visibility | bool | قراءة/كتابة | رؤية Ground Overlay |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | يضيف العنصر الفرعي. |
| [as_bool()](#as_bool__2) | يعيد القيمة محوّلة إلى النوع bool |
| [as_double()](#as_double__3) | يعيد القيمة محوّلة إلى النوع double. |
| [as_int()](#as_int__4) | يعيد القيمة محوّلة إلى int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | يبحث عن عقد XML بالاسم |
| [get_node_by_name(name)](#get_node_by_name_name_6) | يحصل على العقدة بالاسم. يرجى ملاحظة أن هذه الطريقة ستعيد أول عقدة تم العثور عليها.<br/>            لا يهم في أي مستوى تم العثور عليها |
| [get_node_content()](#get_node_content__7) | يحصل على محتوى العقدة. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | يحصل على جميع العقد بالاسم المحدد. <br/>            لا يهم في أي مستوى تم العثور عليها |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

يضيف العنصر الفرعي.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | الطفل. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

يعيد القيمة محوّلة إلى النوع bool

**Returns**

| نوع | وصف |
| :- | :- |
| bool | قيمة bool للعقدة |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

يعيد القيمة محوّلة إلى النوع double.

**Returns**

| نوع | وصف |
| :- | :- |
| double | قيمة double للعقدة |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

يعيد القيمة محوّلة إلى int.

**Returns**

| نوع | وصف |
| :- | :- |
| int | قيمة int للعقدة |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

يبحث عن عقد XML بالاسم

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم العقدة |

**Returns**

| نوع | وصف |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | مصفوفة من عقد XML بالاسم |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

يحصل على العقدة بالاسم. يرجى ملاحظة أن هذه الطريقة ستعيد أول عقدة تم العثور عليها.<br/>            لا يهم في أي مستوى تم العثور عليها

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم العقدة التي تريد العثور عليها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | العقدة التي تم العثور عليها باستخدام NodeLink API |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

يحصل على محتوى العقدة.

**Returns**

| نوع | وصف |
| :- | :- |
| string | محتوى العقدة |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

يحصل على جميع العقد بالاسم المحدد. <br/>            لا يهم في أي مستوى تم العثور عليها

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الأسماء | string | الأسماء. |

**Returns**

| نوع | وصف |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | مصفوفة العقد التي تم العثور عليها. |


