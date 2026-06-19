---
title: "FileGdbCoordinatePrecisionGrid فئة"
type: docs
weight: 10
url: /ar/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | يُنشئ مثيلاً جديدًا لفئة FileGdbCoordinatePrecisionGrid |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | قراءة/كتابة | يحصل أو يعيّن أصل إحداثية M. إذا تم تعيينه إلى <see langword=\"null\" /> يتم استخدام القيمة الافتراضية. |
| m_scale | Nullable<double> | قراءة/كتابة | يحصل أو يعيّن مقياس إحداثية M. إذا تم تعيينه إلى <see langword=\"null\" /> يتم استخدام القيمة الافتراضية. |
| x_origin | Nullable<double> | قراءة/كتابة | يسترجع أو يعيّن أصل إحداثي X. إذا تم تعيينه إلى <see langword="null" /> يتم استخدام القيمة الافتراضية. |
| xy_scale | Nullable<double> | قراءة/كتابة | يسترجع أو يعيّن مقياس إحداثيات X و Y. إذا تم تعيينه إلى <see langword="null" /> يتم استخدام القيمة الافتراضية. |
| y_origin | Nullable<double> | قراءة/كتابة | يسترجع أو يعيّن أصل إحداثي Y. إذا تم تعيينه إلى <see langword="null" /> يتم استخدام القيمة الافتراضية. |
| z_origin | Nullable<double> | قراءة/كتابة | يسترجع أو يعيّن أصل إحداثي Z. إذا تم تعيينه إلى <see langword="null" /> يتم استخدام القيمة الافتراضية. |
| z_scale | Nullable<double> | قراءة/كتابة | يسترجع أو يعيّن مقياس إحداثي Z. إذا تم تعيينه إلى <see langword="null" /> يتم استخدام القيمة الافتراضية. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | ينشئ <c>FileGdbCoordinatePrecisionGrid</c> جديد بحيث تكون جميع القيم داخل المستطيل قابلة للتمثيل. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

يُنشئ مثيلاً جديدًا لفئة FileGdbCoordinatePrecisionGrid

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

ينشئ <c>FileGdbCoordinatePrecisionGrid</c> جديد بحيث تكون جميع القيم داخل المستطيل قابلة للتمثيل.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | إحدى زوايا المستطيل. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | الزاوية المقابلة للمستطيل. يجب أن تكون ذات أبعاد مماثلة لـ <paramref name="p1" />. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | الـ <c>FileGdbCoordinatePrecisionGrid</c> بحيث تكون جميع القيم داخل المستطيل قابلة للتمثيل.<br/>            القيم خارج المستطيل غير قابلة للتمثيل، لذا يجب أن تكون جميع الإحداثيات التي سيتم كتابتها إلى طبقة FileGDB<br/>            داخل المستطيل. |


