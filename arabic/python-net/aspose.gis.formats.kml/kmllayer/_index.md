---
title: "فئة KmlLayer"
type: docs
weight: 140
url: /ar/python-net/aspose.gis.formats.kml/kmllayer/
---

**Summary:** Represents a Kml layer with non-destructive behavior that supports read and writing of features and attributes at one time.<br/>            A Kml layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlLayer

**Inheritance:** VectorLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | يحصل على مجموعة السمات المخصصة للميزات في هذا [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| العدد | int | r | يحصل على عدد الميزات في هذه الطبقة. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | يحصل على [KmlLayer.driver](/psd/python-net/aspose.gis.formats.kml/kmllayer/) الذي أنشأ هذه الطبقة. |
| features | [Feature[]](/psd/python-net/aspose.gis/feature) | r | يحصل على قائمة الميزات. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | يحصل على نوع الهندسة للطبقة. |
| ground_overlay_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlGroundOverlayInfo> | r | قائمة KmlGroundOverlayInfo من عقد GroundOverlay |
| network_link_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlNetworkLinkInfo> | r | قائمة KmlNetworkLinkInfo من عقد NetworkLink |
| region_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlRegionInfo> | r | قائمة KmlRegionInfo من عقد Region |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | احصل على نظام الإحداثيات المكانية لهذه الطبقة. بالنسبة إلى KML يكون دائمًا WGS84. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(feature)](#add_feature_1) | يضيف ميزة جديدة إلى الطبقة، إذا كان ذلك مدعومًا من قبل [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [add(feature, style)](#add_feature_style_2) | يضيف ميزة جديدة مع النمط المحدد إلى الطبقة، إذا كان ذلك مدعومًا من قبل [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [as_in_memory()](#as_in_memory__3) | إنشاء نسخة من الطبقة بتنسيق InMemory. |
| [construct_feature()](#construct_feature__4) | ينشئ (ولكن لا يضيف إلى الطبقة) ميزة جديدة بسمات مطابقة لمجموعة سمات هذه الطبقة.<br/>            عند الانتهاء من إعداد البيانات للميزة، استخدم [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) لإضافة الميزة إلى الطبقة. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | تحويل طبقة إلى تنسيق مختلف. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | تحويل طبقة إلى تنسيق مختلف. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | تحويل طبقة إلى تنسيق مختلف. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | تحويل طبقة إلى تنسيق مختلف. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | ينسخ سمات [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) الأخرى إلى هذه. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | ينسخ سمات [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) الأخرى إلى هذه. |
| [create(path, driver)](#create_path_driver_11) | ينشئ الطبقة ويفتحها لإضافة ميزات جديدة. |
| [create(path, driver)](#create_path_driver_12) | ينشئ الطبقة ويفتحها لإضافة ميزات جديدة. |
| [create(path, driver, options)](#create_path_driver_options_13) | ينشئ الطبقة ويفتحها لإضافة ميزات جديدة. |
| [create(path, driver, options)](#create_path_driver_options_14) | ينشئ الطبقة ويفتحها لإضافة ميزات جديدة. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | ينشئ الطبقة ويفتحها للإلحاق. |
| [get_extent()](#get_extent__19) | يحصل على الامتداد المكاني لهذه الطبقة. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | تقاطع طبقة مع الطبقة الحالية باستخدام الهندسة. |
| [join(layer, options)](#join_layer_options_21) | ينضم طبقة إلى الطبقة الحالية. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | ينضم طبقة إلى الطبقة الحالية باستخدام الهندسة. |
| [nearest_to(point)](#nearest_to_point_23) | يحصل على أقرب ميزة إلى النقطة المقدمة. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | يحصل على أقرب ميزة إلى الإحداثي المقدم. |
| [open(path, driver)](#open_path_driver_25) | فتح الطبقة للقراءة. |
| [open(path, driver)](#open_path_driver_26) | فتح الطبقة للقراءة. |
| [open(path, driver, options)](#open_path_driver_options_27) | فتح الطبقة للقراءة. |
| [open(path, driver, options)](#open_path_driver_options_28) | فتح الطبقة للقراءة. |
| [remove_at(index)](#remove_at_index_29) | إزالة [Feature](/psd/python-net/aspose.gis/feature/) عند الفهرس المحدد. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | استبدال [Feature](/psd/python-net/aspose.gis/feature/) عند الفهرس المحدد. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | يحفظ تسلسل الميزات إلى الطبقة. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | يحفظ تسلسل الميزات إلى الطبقة. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | يحفظ تسلسل الميزات إلى الطبقة. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | يحفظ تسلسل الميزات إلى الطبقة. |
| [split_to()](#split_to__35) | تقسيم الميزات حسب نوع الهندسة. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | يحمّل فهرس السمات لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            إذا لم يكن الفهرس موجودًا، ينشئه أولاً. استخدم <paramref name=\"forceRebuild\" /> لإجبار إعادة إنشاء الفهرس. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | يحمّل فهرس السمات لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            إذا لم يكن الفهرس موجودًا، ينشئه أولاً. استخدم <paramref name=\"forceRebuild\" /> لإجبار إعادة إنشاء الفهرس. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | يحمّل فهرسًا مكانيًا لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            و Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            إذا لم يكن الفهرس موجودًا، ينشئه أولاً. استخدم <paramref name=\"forceRebuild\" /> لإجبار إعادة إنشاء الفهرس. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | يحمّل فهرسًا مكانيًا لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            و Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            إذا لم يكن الفهرس موجودًا، ينشئه أولاً. استخدم <paramref name=\"forceRebuild\" /> لإجبار إعادة إنشاء الفهرس. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | يختار الميزات التي تكون قيمة السمة فيها مساوية للقيمة المقدمة. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | يختار الميزات التي تكون قيمة السمة فيها أكبر من القيمة المقدمة. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | يختار الميزات التي تكون قيمة السمة فيها أكبر أو مساوية للقيمة المقدمة. |
| [where_intersects(extent)](#where_intersects_extent_43) | يقوم بتصفية المعالم بناءً على النطاق. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | يقوم بتصفية المعالم بناءً على الهندسة المقدمة. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | يقوم بتصفية المعالم بناءً على اتحاد جميع الهندسات في تسلسل المعالم الأخرى. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | يختار المعالم التي قيمة الخاصية فيها لا تساوي القيمة المقدمة. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | يختار المعالم التي الخاصية فيها لا تساوي null. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | يختار المعالم التي الخاصية فيها تساوي null. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | يختار المعالم التي تم تعيين الخاصية لها. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | يختار المعالم التي قيمة الخاصية فيها أصغر من القيمة المقدمة. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | يختار المعالم التي قيمة الخاصية فيها أصغر أو تساوي القيمة المقدمة. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | يختار المعالم التي الخاصية المحددة لم يتم تعيينها. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

يضيف ميزة جديدة إلى الطبقة، إذا كان ذلك مدعومًا من قبل [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | الميزة لإضافتها. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

يضيف ميزة جديدة مع النمط المحدد إلى الطبقة، إذا كان ذلك مدعومًا من قبل [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | الميزة لإضافتها. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | نمط الميزة. استخدم <see langword="null" /> للإشارة إلى نمط مفقود. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

إنشاء نسخة من الطبقة بتنسيق InMemory.

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | الطبقة InMemory. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

ينشئ (ولكن لا يضيف إلى الطبقة) ميزة جديدة بسمات مطابقة لمجموعة سمات هذه الطبقة.<br/>            عند الانتهاء من إعداد البيانات للميزة، استخدم [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) لإضافة الميزة إلى الطبقة.

**Returns**

| نوع | وصف |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | ميزة جديدة. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

تحويل طبقة إلى تنسيق مختلف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| source_path | string | المسار إلى الطبقة التي سيتم تحويلها. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة للطبقة المصدر. |
| destination_path | string | المسار إلى الطبقة التي سيتم إنشاؤها نتيجةً للتحويل. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة للطبقة الوجهة. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

تحويل طبقة إلى تنسيق مختلف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الطبقة التي سيتم تحويلها. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة للطبقة المصدر. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الطبقة التي سيتم إنشاؤها نتيجةً للتحويل. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة للطبقة الوجهة. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

تحويل طبقة إلى تنسيق مختلف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| source_path | string | المسار إلى الطبقة التي سيتم تحويلها. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة للطبقة المصدر. |
| destination_path | string | المسار إلى الطبقة التي سيتم إنشاؤها نتيجةً للتحويل. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة للطبقة الوجهة. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | خيارات إجراء التحويل. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

تحويل طبقة إلى تنسيق مختلف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الطبقة التي سيتم تحويلها. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة للطبقة المصدر. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الطبقة التي سيتم إنشاؤها نتيجةً للتحويل. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة للطبقة الوجهة. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | خيارات إجراء التحويل. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

ينسخ سمات [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) الأخرى إلى هذه.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل المعالم لنسخ الخصائص منه. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

ينسخ سمات [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) الأخرى إلى هذه.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل المعالم لنسخ الخصائص منه. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | مثال على كائن مخصص من [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) سيعالج الخصائص واحدةً تلو الأخرى. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

ينشئ الطبقة ويفتحها لإضافة ميزات جديدة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للكتابة فقط. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

ينشئ الطبقة ويفتحها لإضافة ميزات جديدة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للكتابة فقط. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

ينشئ الطبقة ويفتحها لإضافة ميزات جديدة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للكتابة فقط. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

ينشئ الطبقة ويفتحها لإضافة ميزات جديدة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للكتابة فقط. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

يحصل على الامتداد المكاني لهذه الطبقة.

**Returns**

| نوع | وصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | نطاق مكاني لهذه الطبقة. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

تقاطع طبقة مع الطبقة الحالية باستخدام الهندسة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للتقاطع. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة جديدة نتيجة تقاطع طبقتين. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

ينضم طبقة إلى الطبقة الحالية.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للانضمام. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | معلمات الانضمام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة جديدة نتيجة دمج طبقتين. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

ينضم طبقة إلى الطبقة الحالية باستخدام الهندسة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للانضمام. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | معلمات الانضمام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة جديدة نتيجة دمج طبقتين. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

يحصل على أقرب ميزة إلى النقطة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | النقطة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | أقرب عنصر إلى النقطة المقدمة. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

يحصل على أقرب ميزة إلى الإحداثي المقدم.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| x | double | X للإحداثي. |
| y | double | Y للإحداثي. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | أقرب عنصر إلى الإحداثي المقدم. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

فتح الطبقة للقراءة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للقراءة فقط. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

فتح الطبقة للقراءة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للقراءة فقط. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

فتح الطبقة للقراءة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للقراءة فقط. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

فتح الطبقة للقراءة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة للقراءة فقط. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

إزالة [Feature](/psd/python-net/aspose.gis/feature/) عند الفهرس المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس العنصر. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

استبدال [Feature](/psd/python-net/aspose.gis/feature/) عند الفهرس المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس العنصر. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | العنصر لتعيينه. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

يحفظ تسلسل الميزات إلى الطبقة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| destination_path | string | المسار إلى طبقة الإخراج. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة لطبقة الإخراج. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

يحفظ تسلسل الميزات إلى الطبقة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى طبقة الإخراج. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة لطبقة الإخراج. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

يحفظ تسلسل الميزات إلى الطبقة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| destination_path | string | المسار إلى طبقة الإخراج. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة لطبقة الإخراج. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | خيارات عملية الحفظ. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

يحفظ تسلسل الميزات إلى الطبقة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى طبقة الإخراج. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة لطبقة الإخراج. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | خيارات عملية الحفظ. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

تقسيم الميزات حسب نوع الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | طبقات بنفس نوع الهندسة. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

يحمّل فهرس السمات لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            إذا لم يكن الفهرس موجودًا، ينشئه أولاً. استخدم <paramref name=\"forceRebuild\" /> لإجبار إعادة إنشاء الفهرس.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| index_path | string | المسار إلى ملف الفهرس. |
| attribute_name | string | اسم السمة لبناء الفهرس عليها. |
| force_rebuild | bool | ما إذا كان يجب إعادة إنشاء الفهرس حتى إذا كان موجودًا بالفعل. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

يحمّل فهرس السمات لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            إذا لم يكن الفهرس موجودًا، ينشئه أولاً. استخدم <paramref name=\"forceRebuild\" /> لإجبار إعادة إنشاء الفهرس.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى ملف الفهرس. |
| attribute_name | string | اسم السمة لبناء الفهرس عليها. |
| force_rebuild | bool | ما إذا كان يجب إعادة إنشاء الفهرس حتى إذا كان موجودًا بالفعل. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

يحمّل فهرسًا مكانيًا لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            و Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            إذا لم يكن الفهرس موجودًا، ينشئه أولاً. استخدم <paramref name=\"forceRebuild\" /> لإجبار إعادة إنشاء الفهرس.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| index_path | string | المسار إلى ملف الفهرس. |
| force_rebuild | bool | ما إذا كان يجب إعادة إنشاء الفهرس حتى إذا كان موجودًا بالفعل. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

يحمّل فهرسًا مكانيًا لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            و Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            إذا لم يكن الفهرس موجودًا، ينشئه أولاً. استخدم <paramref name=\"forceRebuild\" /> لإجبار إعادة إنشاء الفهرس.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى ملف الفهرس. |
| force_rebuild | bool | ما إذا كان يجب إعادة إنشاء الفهرس حتى إذا كان موجودًا بالفعل. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

يختار الميزات التي تكون قيمة السمة فيها مساوية للقيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | عناصر ذات قيمة السمة مساوية للقيمة المقدمة. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

يختار الميزات التي تكون قيمة السمة فيها أكبر من القيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | عناصر ذات قيمة السمة أكبر من القيمة المقدمة. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

يختار الميزات التي تكون قيمة السمة فيها أكبر أو مساوية للقيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | عناصر ذات قيمة السمة أكبر أو مساوية للقيمة المقدمة. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

يقوم بتصفية المعالم بناءً على النطاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | تصفية النطاق. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي تتقاطع مع الهندسة المقدمة. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

يقوم بتصفية المعالم بناءً على الهندسة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | تصفية الهندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي تتقاطع مع الهندسة المقدمة. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

يقوم بتصفية المعالم بناءً على اتحاد جميع الهندسات في تسلسل المعالم الأخرى.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل العناصر الأخرى. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي تتقاطع مع اتحاد جميع الهندسات في تسلسل العناصر الأخرى. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

يختار المعالم التي قيمة الخاصية فيها لا تساوي القيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها لا تساوي القيمة المقدمة. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

يختار المعالم التي الخاصية فيها لا تساوي null.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها لا تساوي null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

يختار المعالم التي الخاصية فيها تساوي null.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها تساوي null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

يختار المعالم التي تم تعيين الخاصية لها.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي لديها قيمة خاصية محددة. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

يختار المعالم التي قيمة الخاصية فيها أصغر من القيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها أصغر من القيمة المقدمة. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

يختار المعالم التي قيمة الخاصية فيها أصغر أو تساوي القيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها أصغر أو تساوي القيمة المقدمة. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

يختار المعالم التي الخاصية المحددة لم يتم تعيينها.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها غير محددة. |


