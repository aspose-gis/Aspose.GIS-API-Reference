---
title: "Класс GeographicSpatialReferenceSystemParameters"
type: docs
weight: 90
url: /ru/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/
---

**Summary:** Parameters to create geographic SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GeographicSpatialReferenceSystemParameters()](#GeographicSpatialReferenceSystemParameters__1) | Инициализирует новый экземпляр класса GeographicSpatialReferenceSystemParameters. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Единицы измерения, используемые в этой СКС. По умолчанию — [Unit.degree](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r/w | Порядок осей. По умолчанию — [GeographicAxisesOrder.LONGITUDE_LATITUDE](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Датум географической СКС. По умолчанию — [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| latitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Ось, описывающая широту. По умолчанию — ось, направленная на север. |
| longitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Ось, описывающая долготу. По умолчанию — ось, направленная на восток. |
| имя | string | r/w | Название географической СКС. По умолчанию — "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Главный меридиан этой SRS. По умолчанию [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |


### Constructor: GeographicSpatialReferenceSystemParameters() {#GeographicSpatialReferenceSystemParameters__1}


```
 GeographicSpatialReferenceSystemParameters() 
```

Инициализирует новый экземпляр класса GeographicSpatialReferenceSystemParameters.

