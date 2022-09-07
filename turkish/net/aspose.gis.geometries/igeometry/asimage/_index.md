---
title: AsImage
second_title: Aspose.GIS for .NET API Referansı
description: Bu geometriyi bir görüntü temsiline aktarın.
type: docs
weight: 110
url: /tr/net/aspose.gis.geometries/igeometry/asimage/
---
## AsImage(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_1}

Bu geometriyi bir görüntü temsiline aktarın.

```csharp
public void AsImage(AbstractPath outputPath, Measurement width, Measurement height, 
    Renderer renderer, VectorSymbolizer symbolizer = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputPath | AbstractPath | Çıktı görüntüsünün yolu. |
| width | Measurement | Haritanın genişliği. |
| height | Measurement | Haritanın yüksekliği. |
| renderer | Renderer | Kullanılacak oluşturucu. |
| symbolizer | VectorSymbolizer | Render için kullanılacak bir sembolleştirici. Eğer`null`, varsayılan sembolleştirici kullanılır. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | herhangi bir argüman`null`. |
| IOException | Bir G/Ç hatası oluştu. |
| [GisException](../../../aspose.gis/gisexception) | GIS verileri işlenirken veya okunurken bir hata oluştu. |
| ArgumentException | Genişlik veya yükseklik birimi!:SpatialReferencing.Unit.MapUnits . |
| ArgumentOutOfRangeException | Genişlik veya yükseklik negatif veya sıfırdır. |

### Ayrıca bakınız

* class [AbstractPath](../../../aspose.gis/abstractpath)
* struct [Measurement](../../../aspose.gis.rendering/measurement)
* class [Renderer](../../../aspose.gis.rendering/renderer)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* interface [IGeometry](../../igeometry)
* ad alanı [Aspose.Gis.Geometries](../../igeometry)
* toplantı [Aspose.GIS](../../../)

---

## AsImage(string, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_2}

Bu geometriyi bir görüntü temsiline aktarın.

```csharp
public void AsImage(string outputPath, Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| outputPath | String | Çıktı görüntüsünün yolu. |
| width | Measurement | Haritanın genişliği. |
| height | Measurement | Haritanın yüksekliği. |
| renderer | Renderer | Kullanılacak oluşturucu. |
| symbolizer | VectorSymbolizer | Render için kullanılacak bir sembolleştirici. Eğer`null`, varsayılan sembolleştirici kullanılır. |

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | herhangi bir argüman`null`. |
| IOException | Bir G/Ç hatası oluştu. |
| [GisException](../../../aspose.gis/gisexception) | GIS verileri işlenirken veya okunurken bir hata oluştu. |
| ArgumentException | Genişlik veya yükseklik birimi!:SpatialReferencing.Unit.MapUnits . |
| ArgumentOutOfRangeException | Genişlik veya yükseklik negatif veya sıfırdır. |

### Ayrıca bakınız

* struct [Measurement](../../../aspose.gis.rendering/measurement)
* class [Renderer](../../../aspose.gis.rendering/renderer)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* interface [IGeometry](../../igeometry)
* ad alanı [Aspose.Gis.Geometries](../../igeometry)
* toplantı [Aspose.GIS](../../../)

---

## AsImage(Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage}

Bu geometriyi bir görüntü temsiline aktarın.

```csharp
public Stream AsImage(Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| width | Measurement | Haritanın genişliği. |
| height | Measurement | Haritanın yüksekliği. |
| renderer | Renderer | Kullanılacak oluşturucu. |
| symbolizer | VectorSymbolizer | Render için kullanılacak bir sembolleştirici. Eğer`null`, varsayılan sembolleştirici kullanılır. |

### Geri dönüş değeri

Akış olarak görüntü

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | herhangi bir argüman`null`. |
| IOException | Bir G/Ç hatası oluştu. |
| [GisException](../../../aspose.gis/gisexception) | GIS verileri işlenirken veya okunurken bir hata oluştu. |
| ArgumentException | Genişlik veya yükseklik birimi!:SpatialReferencing.Unit.MapUnits . |
| ArgumentOutOfRangeException | Genişlik veya yükseklik negatif veya sıfırdır. |

### Ayrıca bakınız

* struct [Measurement](../../../aspose.gis.rendering/measurement)
* class [Renderer](../../../aspose.gis.rendering/renderer)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer)
* interface [IGeometry](../../igeometry)
* ad alanı [Aspose.Gis.Geometries](../../igeometry)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->