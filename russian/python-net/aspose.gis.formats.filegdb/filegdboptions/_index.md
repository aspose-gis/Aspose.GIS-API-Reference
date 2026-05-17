---
title: "Класс FileGdbOptions"
type: docs
weight: 30
url: /ru/python-net/aspose.gis.formats.filegdb/filegdboptions/
---

**Summary:** Driver-specific options for FileGDB format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [FileGdbOptions()](#FileGdbOptions__1) | Создать новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Определяет, закрывать ли незакрытый [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) в каждой геометрии. По умолчанию <see langword="false" />. |
| coordinate_precision_grid | [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | r/w | Сетка точности координат, используемая в новом слое. |
| create_midpoints | bool | r/w | Определяет, добавлять ли новую точку посередине каждого сегмента геометрии. По умолчанию <see langword="false" />. |
| delete_near_points | bool | r/w | Определяет, удалять ли близлежащие точки в каждой геометрии. По умолчанию <see langword="false" />. |
| delete_near_points_distance | double | r/w | Определяет расстояние для [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). По умолчанию <see langword="0" />. |
| ensure_valid_coordinates_range | bool | r/w | Определяет, должны ли координаты находиться в допустимом диапазоне. |
| expected_geometry_type | Nullable<Aspose.Gis.Geometries.GeometryType> | r/w | Ожидаемый тип геометрии для слоя. Если эта опция установлена, то разрешено добавлять только геометрии этого типа. |
| geometry_field_name | string | r/w | Имя поля геометрии. |
| has_m | bool | r/w | Могут ли геометрии слоя иметь координату 'm'. По умолчанию true. |
| has_z | bool | r/w | Могут ли геометрии слоя иметь координату 'z'. По умолчанию true. |
| linearization_tolerance | double | r/w | Допустимое отклонение, используемое для линеаризации криволинейных геометрий. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координате M<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| m_tolerance | Nullable<double> | r/w | Допуск привязки M. |
| object_id_field_name | string | r/w | Имя поля идентификатора объекта. |
| simplify_segments | bool | r/w | Определяет, удалять ли точки, лежащие на одном сегменте в каждой геометрии. По умолчанию <see langword="false" />. |
| simplify_segments_distance | double | r/w | Определяет расстояние для [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). По умолчанию <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Определяет, следует ли проверять геометрии при их добавлении в слой.<br/>            Если установлено в <see langword="true" />, вызывается [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) для каждой<br/>            геометрии при её добавлении в слой, и если проверка не проходит ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) возвращает <see langword="false" />), бросается [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Определяет, разрешено ли преобразование полигонов или мультиполигонов в линию. По умолчанию <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координатам X и Y<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| xy_tolerance | Nullable<double> | r/w | Допуск привязки X и Y. |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координате Z<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_tolerance | Nullable<double> | r/w | Допуск привязки Z. |


### Constructor: FileGdbOptions() {#FileGdbOptions__1}


```
 FileGdbOptions() 
```

Создать новый экземпляр.

