---
title: IsCompound
second_title: Referencia de API de Aspose.GIS para .NET
description: Devuelve si este SRS es compuesto unión de dos SRS. Se consideran válidas las siguientes combinaciones de SRS en SRS compuesto SRS Geográfico  SRS Vertical en este caso el tipo de SRS compuesto seráGeographic . SRS Proyectado  SRS Vertical en este caso el tipo de SRS compuesto seráProjected . Si la combinación de SRS difiere el tipo de SRS compuesto seráUnknown .
type: docs
weight: 130
url: /es/net/aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/
---
## SpatialReferenceSystem.IsCompound property

Devuelve si este SRS es compuesto (unión de dos SRS). Se consideran válidas las siguientes combinaciones de SRS en SRS compuesto: SRS Geográfico + SRS Vertical, en este caso el tipo de SRS compuesto seráGeographic . SRS Proyectado + SRS Vertical, en este caso el tipo de SRS compuesto seráProjected . Si la combinación de SRS difiere, el tipo de SRS compuesto seráUnknown .

```csharp
public virtual bool IsCompound { get; }
```

### Observaciones

En WKT esto es COMPD_CS.

### Ver también

* class [SpatialReferenceSystem](../../spatialreferencesystem)
* espacio de nombres [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->