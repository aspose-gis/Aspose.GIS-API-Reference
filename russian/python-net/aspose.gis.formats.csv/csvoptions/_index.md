---
title: "CsvOptions Класс"
type: docs
weight: 20
url: /ru/python-net/aspose.gis.formats.csv/csvoptions/
---

**Summary:** Driver-specific options for CSV format.

**Module:** [aspose.gis.formats.csv](/psd/python-net/aspose.gis.formats.csv/)

**Full Name:** aspose.gis.formats.csv.CsvOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CsvOptions()](#CsvOptions__1) | Создать новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Определяет, закрывать ли незакрытый [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) в каждой геометрии. По умолчанию <see langword="false" />. |
| column_m | string | r/w | Получает или задает имя столбца, содержащего значение координаты M.<br/>            По умолчанию <see langword="null" />. |
| column_wkt | string | r/w | Получает или задает имя столбца, содержащего Well-Known Text для представления геометрии.<br/>            По умолчанию <see langword="null" />. |
| column_x | string | r/w | Получает или задает имя столбца, содержащего значение координаты X.<br/>            По умолчанию <see langword="null" />. |
| column_y | string | r/w | Получает или задает имя столбца, содержащего значение координаты Y.<br/>            По умолчанию <see langword="null" />. |
| column_z | string | r/w | Получает или задает имя столбца, содержащего значение координаты Z.<br/>            По умолчанию <see langword="null" />. |
| create_midpoints | bool | r/w | Определяет, добавлять ли новую точку посередине каждого сегмента геометрии. По умолчанию <see langword="false" />. |
| delete_near_points | bool | r/w | Определяет, удалять ли близлежащие точки в каждой геометрии. По умолчанию <see langword="false" />. |
| delete_near_points_distance | double | r/w | Определяет расстояние для [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). По умолчанию <see langword="0" />. |
| delimiter | char | r/w | Получает или задает символ, используемый в качестве разделителя для разделения значений.<br/>            По умолчанию ','. |
| double_quote_escape | char | r/w | Получает или задает символ, используемый как экранирующий символ для двойных кавычек.<br/>            По умолчанию '"'. |
| has_attribute_names | bool | r/w | Определяет, существует ли строка заголовка с именами атрибутов.<br/>            По умолчанию <see langword="true" />. |
| linearization_tolerance | double | r/w | Допустимое отклонение, используемое для линеаризации криволинейных геометрий. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координате M<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | r/w | Определяет, удалять ли точки, лежащие на одном сегменте в каждой геометрии. По умолчанию <see langword="false" />. |
| simplify_segments_distance | double | r/w | Определяет расстояние для [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). По умолчанию <see langword="0" />. |
| start_line_number | int | r/w | Получает или задает нумерацию строк, начинающуюся с нуля, которая будет первой при чтении данных.<br/>            По умолчанию 0. |
| validate_geometries_on_write | bool | r/w | Определяет, следует ли проверять геометрии при их добавлении в слой.<br/>            Если установлено в <see langword="true" />, вызывается [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) для каждой<br/>            геометрии при её добавлении в слой, и если проверка не проходит ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) возвращает <see langword="false" />), бросается [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Определяет, разрешено ли преобразование полигонов или мультиполигонов в линию. По умолчанию <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координатам X и Y<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координате Z<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: CsvOptions() {#CsvOptions__1}


```
 CsvOptions() 
```

Создать новый экземпляр.

