---
title: "Класс MapInfoInterchangeOptions"
type: docs
weight: 20
url: /ru/python-net/aspose.gis.formats.mapinfointerchange/mapinfointerchangeoptions/
---

**Summary:** Driver-specific options for MapInfo Interchange format.

**Module:** [aspose.gis.formats.mapinfointerchange](/psd/python-net/aspose.gis.formats.mapinfointerchange/)

**Full Name:** aspose.gis.formats.mapinfointerchange.MapInfoInterchangeOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [MapInfoInterchangeOptions()](#MapInfoInterchangeOptions__1) | Создать новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| charset | string | r/w | Определяет charset, по умолчанию Neutral |
| close_linear_ring | bool | r/w | Определяет, закрывать ли незакрытый [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) в каждой геометрии. По умолчанию <see langword="false" />. |
| create_midpoints | bool | r/w | Определяет, добавлять ли новую точку посередине каждого сегмента геометрии. По умолчанию <see langword="false" />. |
| delete_near_points | bool | r/w | Определяет, удалять ли близлежащие точки в каждой геометрии. По умолчанию <see langword="false" />. |
| delete_near_points_distance | double | r/w | Определяет расстояние для [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). По умолчанию <see langword="0" />. |
| delimiter | string | r/w | Определяет delimiter для атрибутов в mid file, по умолчанию символ табуляции |
| linearization_tolerance | double | r/w | Допустимое отклонение, используемое для линеаризации криволинейных геометрий. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координате M<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | r/w | Определяет, удалять ли точки, лежащие на одном сегменте в каждой геометрии. По умолчанию <see langword="false" />. |
| simplify_segments_distance | double | r/w | Определяет расстояние для [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). По умолчанию <see langword="0" />. |
| text_string_attribute | string | r/w | Указывает имя атрибута, представляющего текст графического объекта 'Text'. |
| validate_geometries_on_write | bool | r/w | Определяет, следует ли проверять геометрии при их добавлении в слой.<br/>            Если установлено в <see langword="true" />, вызывается [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) для каждой<br/>            геометрии при её добавлении в слой, и если проверка не проходит ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) возвращает <see langword="false" />), бросается [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Определяет, разрешено ли преобразование полигонов или мультиполигонов в линию. По умолчанию <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координатам X и Y<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Модель точности [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), которая будет применяться к координате Z<br/>            когда геометрии добавляются в [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) или читаются из [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Значение по умолчанию — [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: MapInfoInterchangeOptions() {#MapInfoInterchangeOptions__1}


```
 MapInfoInterchangeOptions() 
```

Создать новый экземпляр.

