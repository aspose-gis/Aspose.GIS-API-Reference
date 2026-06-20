---
title: "SimpleLabeling 类"
type: docs
weight: 80
url: /zh/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | 初始化 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 类的新实例。 |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | 初始化 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 类的新实例。 |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | 初始化 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | 确定文本的颜色。 |
| font_family | string | r/w | 用于渲染文本的字体族。默认值取决于系统。 |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 文本的大小。 |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | 应用于文本的样式。 |
| halo_color | System.Drawing.Color | r/w | 文本周围光晕（描边）的颜色。 |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 文本周围光晕（描边）的大小。 |
| label_attribute | string | r/w | 用于作为标签来源的属性名称。如果设置了 [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/)，则忽略。<br/> 必须在渲染之前设置 [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 或 [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/)，否则会抛出 InvalidOperationException。 |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | 指定多段几何体的渲染行为。默认是 [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/)。 |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | 获取 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) 的实例。 |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | 标签放置指定标签相对于要素几何体的放置方式。 |
| 优先级 | 整数 | r/w | 指示此标签在与其他标签重叠时的优先级。优先级较低的标签不会被渲染。<br/> 默认值为 1000。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

初始化 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 类的新实例。

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

初始化 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| label_attribute | string | 用于作为标签来源的属性名称。 |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

初始化 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | 要从中复制数据的另一个 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/)。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | 此实例的克隆。 |


