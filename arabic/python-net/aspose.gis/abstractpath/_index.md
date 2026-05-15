---
title: "فئة AbstractPath"
type: docs
weight: 10
url: /ar/python-net/aspose.gis/abstractpath/
---

**Summary:** An <c>AbstractPath</c> is a base class for classes that specify a unique location in an environment similar to a filesystem,<br/>            like a local filesystem, a remote file storage or a ZIP archive, among others.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| الموقع | string | r | يحصل على تمثيل نصي لموقع هذا <c>AbstractPath</c>. |
| separator | char | r | يحصل على حرف الفاصل المستخدم لفصل مستويات الدليل في سلسلة [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [combine(location)](#combine_location_1) | يجمع هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) مع مكوّنات المسار المحددة. |
| delete() | يحذف ملفًا يشير إليه هذا المسار. |
| [from_local_path(path)](#from_local_path_path_2) | ينشئ [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) يمثل موقعًا على نظام الملفات المحلي. |
| [from_stream(stream)](#from_stream_stream_3) | ينشئ [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) من تدفق. |
| [get_extension()](#get_extension__4) | يرجع الامتداد لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name()](#get_file_name__5) | يرجع اسم الملف والامتداد لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | يرجع اسم الملف لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) بدون الامتداد. |
| [is_file()](#is_file__7) | يحصل على قيمة تشير إلى ما إذا كان هذا المسار يشير إلى ملف موجود يمكن فتحه للقراءة. |
| [list_directory()](#list_directory__8) | يرجع المسارات الموجودة داخل هذا <c>AbstractPath</c>، إذا كان دليلًا. |
| [open(access)](#open_access_9) | يفتح هذا <c>AbstractPath</c> كملف. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | يرجع [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) جديدًا مع تغيير امتداد الملف إلى القيمة المحددة. |


### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

يجمع هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) مع مكوّنات المسار المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| location | string | مكوّن مسار لإضافته إلى هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |

**Returns**

| نوع | الوصف |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) جديد يشير إلى [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) وهو مزيج من مواقع هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) و<br/>            الوسيط. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

ينشئ [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) يمثل موقعًا على نظام الملفات المحلي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | مسار على نظام الملفات المحلي، مثل <c>"C:\\file.shp"</c> أو <c>"D:\\directory\\"</c>. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) يمثل الموقع المحدد بواسطة <paramref name="path" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

ينشئ [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) من تدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream | _io.BufferedRandom | دفق لإنشاء [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) منه. <c>Aspose.GIS</c> لا يقوم بتحرير الدفق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | كائن من [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) مع الدفق المحدد كمحتواه. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

يرجع الامتداد لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| نوع | الوصف |
| :- | :- |
| string | امتداد هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (بما في ذلك النقطة ".") أو<br/>            سلسلة فارغة إذا كان [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) لا يحتوي على امتداد. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

يرجع اسم الملف والامتداد لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| نوع | الوصف |
| :- | :- |
| string | الأحرف التي تلي آخر حرف [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) في [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). إذا كان<br/>            الحرف الأخير هو حرف [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/)، تُرجع سلسلة فارغة. إذا لم يكن هناك<br/>            أحرف [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) في [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/)، تُرجع [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) نفسه<br/>            . |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

يرجع اسم الملف لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) بدون الامتداد.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | السلسلة التي تُرجعها [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) بدون آخر نقطة وجميع الأحرف التي تليها. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

يحصل على قيمة تشير إلى ما إذا كان هذا المسار يشير إلى ملف موجود يمكن فتحه للقراءة.

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان الموقع يشير إلى ملف؛ <see langword="false" /> غير ذلك. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

يرجع المسارات الموجودة داخل هذا <c>AbstractPath</c>، إذا كان دليلًا.

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | المسارات الموجودة داخل هذا <c>AbstractPath</c>. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

يفتح هذا <c>AbstractPath</c> كملف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الوصول | System.IO.FileAccess | يحدد مجموعة فرعية من العمليات التي يمكن إجراؤها على دفق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| _io.BufferedRandom | دفق مفتوح باستخدام FileAccess المحدد. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

يرجع [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) جديدًا مع تغيير امتداد الملف إلى القيمة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_extension | string | امتداد جديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) جديد، يشير إلى ملف في نفس الدليل، ولكن بامتداد جديد. |


