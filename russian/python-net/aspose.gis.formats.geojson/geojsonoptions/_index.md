---
title: "Класс GeoJsonOptions"
type: docs
weight: 20
url: /ru/python-net/aspose.gis.formats.geojson/geojsonoptions/
---

**Summary:** Driver-specific options for GeoJSON format.

**Module:** [aspose.gis.formats.geojson](/psd/python-net/aspose.gis.formats.geojson/)

**Full Name:** aspose.gis.formats.geojson.GeoJsonOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GeoJsonOptions()](#GeoJsonOptions__1) | Создать новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| array_as_string | bool | r/w | Определяет, следует ли представлять массивы JSON строк, целых чисел или вещественных чисел как строки. |
| attributes_skip | bool | r/w | управляет переводом атрибутов: да — пропустить все атрибуты |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | Автоматически генерировать идентификаторы |
| close_linear_ring | bool | r/w | Определяет, закрывать ли незакрытый [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) в каждой геометрии. По умолчанию <see langword="false" />. |
| create_midpoints | bool | r/w | Определяет, добавлять ли новую точку посередине каждого сегмента геометрии. По умолчанию <see langword="false" />. |
| date_as_string | bool | r/w | Определяет, представлять ли даты/время/дата‑время JSON как строки. |
| delete_near_points | bool | r/w | Определяет, удалять ли близлежащие точки в каждой геометрии. По умолчанию <see langword="false" />. |
| delete_near_points_distance | double | r/w | Определяет расстояние для [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). По умолчанию <see langword="0" />. |
| описание | string | r/w | Описание на уровне коллекции объектов (для создания слоя) |
| geometry_as_collection | bool | r/w | управление трансляцией геометрий: yes - обернуть геометрии типом GeometryCollection |
| linearization_tolerance | double | r/w | Допустимое отклонение, используемое для линеаризации криволинейных геометрий. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координате M<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| имя | string | r/w | Имя на уровне коллекции объектов (для создания слоя) |
| nested_properties_separator | string | r/w | Получает или задает строку, используемую для разделения компонентов вложенных атрибутов.<br/>            По умолчанию "_". |
| read_bounding_boxes | bool | r/w | Определяет, должны ли ограничивающие рамки ('bbox') читаться как атрибуты с именем 'bbox_0', 'bbox_1' и т.д.<br/>            Значение по умолчанию — <see langword=\"false\" />.<br/>            Строка [GeoJsonOptions.nested_properties_separator](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions/) используется в именах bbox_0, bbox_1,.. |
| simplify_segments | bool | r/w | Определяет, удалять ли точки, лежащие на одном сегменте в каждой геометрии. По умолчанию <see langword="false" />. |
| simplify_segments_distance | double | r/w | Определяет расстояние для [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). По умолчанию <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Определяет, следует ли проверять геометрии при их добавлении в слой.<br/>            Если установлено в <see langword="true" />, вызывается [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) для каждой<br/>            геометрии при её добавлении в слой, и если проверка не проходит ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) возвращает <see langword="false" />), бросается [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_bounding_boxes | bool | r/w | Определяет, следует ли включать в объекты GeoJSON информацию о диапазоне координат их геометрий.<br/>            Если установлено в <see langword=\"true\" />, для каждой геометрии (не null), добавляемой в слой, создаётся член \"bbox\".<br/>            Значение по умолчанию — <see langword=\"false\" />. |
| write_polygons_as_lines | bool | r/w | Определяет, разрешено ли преобразование полигонов или мультиполигонов в линию. По умолчанию <see langword="false" />. |
| write_unset_attribute | bool | r/w | Записывать ли неустановленные атрибуты, добавляя значение 'null' |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координатам X и Y<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координате Z<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GeoJsonOptions() {#GeoJsonOptions__1}


```
 GeoJsonOptions() 
```

Создать новый экземпляр.

