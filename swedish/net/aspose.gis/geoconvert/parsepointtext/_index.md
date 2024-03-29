---
title: GeoConvert.ParsePointText
second_title: Aspose.GIS för .NET API Referens
description: GeoConvert metod. Konverterar strängen som innehåller сordinater till IPointobjekt.
type: docs
weight: 20
url: /sv/net/aspose.gis/geoconvert/parsepointtext/
---
## GeoConvert.ParsePointText method

Konverterar strängen som innehåller сordinater till IPoint-objekt.

```csharp
public static IPoint ParsePointText(string text)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | String | En sträng som innehåller koordinater att konvertera. Strängen bör innehålla både koordinatlatitud och longitud. Koordinater ska avgränsas med blanksteg, komma eller semikolon. |

### Returvärde

IPoint-objekt med koordinater som motsvarar inmatningssträngen.

### Undantag

| undantag | skick |
| --- | --- |
| [GisException](../../gisexception/) |  |

### Anmärkningar

Exempel: "80° 151°", "74°50.82', 172°08.21'", "80°;151°", "2CMB", "2CMB6682893142", "2C MB 66828 93142", "050305_d4".

### Se även

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [GeoConvert](../)
* namnutrymme [Aspose.Gis](../../geoconvert/)
* hopsättning [Aspose.GIS](../../../)


