---
title: "فئة MultiStreamPath"
type: docs
weight: 2760
url: /ar/python-net/aspose.gis/multistreampath/
---

**Summary:** This class works with formats which contains several files.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.MultiStreamPath

**Inheritance:** AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MultiStreamPath(entry_file_name, file_names, streams)](#MultiStreamPath_entry_file_name_file_names_streams_1) | يُنشئ مثلاً جديداً من الفئة [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| الموقع | string | r | يحصل على تمثيل نصي للموقع لهذا <c>AbstractPath</c>. |
| separator | char | r | يحصل على حرف الفاصل المستخدم لفصل مستويات الدليل في سلسلة [MultiStreamPath.location](/psd/python-net/aspose.gis/multistreampath/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [combine(location)](#combine_location_1) | يجمع هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) مع مكوّنات المسار المحددة. |
| delete() | يحذف ملفًا يشير إليه هذا المسار. |
| [from_local_path(path)](#from_local_path_path_2) | ينشئ [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) يمثل موقعًا على نظام الملفات المحلي. |
| [from_stream(stream)](#from_stream_stream_3) | ينشئ [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) من تدفق. |
| [get_extension()](#get_extension__4) | يعيد امتداد هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name()](#get_file_name__5) | يعيد اسم الملف والامتداد لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | يعيد اسم الملف لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) بدون الامتداد. |
| [is_file()](#is_file__7) | يحصل على قيمة تشير إلى ما إذا كان هذا المسار يشير إلى ملف موجود يمكن فتحه للقراءة. |
| [list_directory()](#list_directory__8) | يعيد المسارات الموجودة داخل هذا <c>AbstractPath</c>، إذا كان دليلًا. |
| [open(access)](#open_access_9) | يُجرد مجموعة من صيغ الملفات المتعددة المفتوحة المتدفقة كمسار للوصول إلى البيانات. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | يعيد [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) جديدًا مع تغيير امتداد الملف إلى القيمة المحددة. |


### Constructor: MultiStreamPath(entry_file_name, file_names, streams) {#MultiStreamPath_entry_file_name_file_names_streams_1}


```
 MultiStreamPath(entry_file_name, file_names, streams) 
```

يُنشئ مثلاً جديداً من الفئة [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| entry_file_name | string | اسم ملف الإدخال. |
| file_names | string | أسماء الملفات. |
| التدفقات | _io.BufferedRandom[] | التدفقات. |

### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

يجمع هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) مع مكوّنات المسار المحددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| location | string | مكوّن مسار لإضافته إلى هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |

**Returns**

| نوع | وصف |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) جديد يشير إلى [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) وهو مزيج من مواقع هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) و<br/>            الوسيطة. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

ينشئ [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) يمثل موقعًا على نظام الملفات المحلي.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | مسار على نظام الملفات المحلي، مثل <c>"C:\\file.shp"</c> أو <c>"D:\\directory\\"</c>. |

**Returns**

| نوع | وصف |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) يمثل الموقع المحدد بواسطة <paramref name="path" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

ينشئ [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) من تدفق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| stream | _io.BufferedRandom | دفق لإنشاء [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) منه. <c>Aspose.GIS</c> لا يقوم بتحرير الدفق. |

**Returns**

| نوع | وصف |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | كائن من [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) يحتوي على الدفق المحدد كمحتواه. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

يعيد امتداد هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| نوع | وصف |
| :- | :- |
| string | امتداد هذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (بما في ذلك النقطة ".") أو<br/>            سلسلة فارغة إذا كان [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) لا يحتوي على امتداد. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

يعيد اسم الملف والامتداد لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| نوع | وصف |
| :- | :- |
| string | الأحرف التي تلي آخر حرف [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) في [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). إذا كان<br/>            الحرف الأخير هو حرف [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/)، تُرجع سلسلة فارغة. إذا لم يكن هناك<br/>            أحرف [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) في [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/)، تُرجع [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) نفسه. |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

يعيد اسم الملف لهذا [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) بدون الامتداد.

**Returns**

| نوع | وصف |
| :- | :- |
| string | السلسلة التي تُرجعها [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) بعد حذف آخر نقطة وجميع الأحرف التي تليها. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

يحصل على قيمة تشير إلى ما إذا كان هذا المسار يشير إلى ملف موجود يمكن فتحه للقراءة.

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان الموقع يشير إلى ملف؛ <see langword="false" /> غير ذلك. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

يعيد المسارات الموجودة داخل هذا <c>AbstractPath</c>، إذا كان دليلًا.

**Returns**

| نوع | وصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | المسارات الموجودة داخل هذا <c>AbstractPath</c>. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

يُجرد مجموعة من صيغ الملفات المتعددة المفتوحة المتدفقة كمسار للوصول إلى البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الوصول | System.IO.FileAccess | يحدد مجموعة فرعية من العمليات التي يمكن إجراؤها على دفق. |

**Returns**

| نوع | وصف |
| :- | :- |
| _io.BufferedRandom | يمكن أن يكون هذا إما   أو الدفق الذي تم تمريره أصلاً من قبل العميل. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

يعيد [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) جديدًا مع تغيير امتداد الملف إلى القيمة المحددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| new_extension | string | امتداد جديد. |

**Returns**

| نوع | وصف |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) جديد، يشير إلى ملف في نفس الدليل، ولكن بامتداد جديد. |


