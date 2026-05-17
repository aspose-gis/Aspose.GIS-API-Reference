---
title: "Clase ConversionOptions"
type: docs
weight: 380
url: /es/python-net/aspose.gis/conversionoptions/
---

**Summary:** Options for converting data between formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.ConversionOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ConversionOptions()](#ConversionOptions__1) | Inicializa una nueva instancia de la clase ConversionOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| attributes_converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | r/w | Un conversor personalizado para atributos. Permite renombrar o excluir atributos de destino.<br/>            Si no es <see langword=\"null\" />, se llama para cada atributo de la capa de origen y se espera que lo modifique si es necesario. |
| destination_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | Opciones específicas del controlador para la capa de destino. |
| destination_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Sistema de referencia espacial para asignar a la capa de destino. |
| source_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | Opciones específicas del controlador para la capa de origen. |


### Constructor: ConversionOptions() {#ConversionOptions__1}


```
 ConversionOptions() 
```

Inicializa una nueva instancia de la clase ConversionOptions

