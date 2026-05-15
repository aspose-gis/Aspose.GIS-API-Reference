---
title: "Classe ConversionOptions"
type: docs
weight: 380
url: /fr/python-net/aspose.gis/conversionoptions/
---

**Summary:** Options for converting data between formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.ConversionOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ConversionOptions()](#ConversionOptions__1) | Initialise une nouvelle instance de la classe ConversionOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes_converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | r/w | Un convertisseur personnalisé pour les attributs. Il nous permet de renommer ou d'exclure les attributs de destination.<br/>            Si ce n'est pas <see langword=\"null\" />, il est appelé pour chaque attribut de la couche source et doit le modifier si nécessaire. |
| destination_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | Options spécifiques au pilote pour la couche de destination. |
| destination_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Système de référence spatiale à attribuer à la couche de destination. |
| source_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | Options spécifiques au pilote pour la couche source |


### Constructor: ConversionOptions() {#ConversionOptions__1}


```
 ConversionOptions() 
```

Initialise une nouvelle instance de la classe ConversionOptions

