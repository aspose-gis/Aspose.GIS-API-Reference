---
title: NumericFormat.Flat
second_title: Aspose.GIS for .NET API Reference
description: NumericFormat method. Converts a number to a fixedpoint text without a scientific notation
type: docs
weight: 20
url: /net/aspose.gis/numericformat/flat/
---
## NumericFormat.Flat method

Converts a number to a fixed-point text without a scientific notation.

```csharp
public static NumericFormat Flat(int significantDigits)
```

| Parameter | Type | Description |
| --- | --- | --- |
| significantDigits | Int32 | Number of significant digits. The maximum available precision is "308" |

### Return Value

The Rounding Precision Specifier.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Number of significant digits is less then 0 or more than 308. |

## Remarks

Internally code is generating number strings for WKT via: coordinate.ToString("0.##..", CultureInfo.InvariantCulture) decision.

### See Also

* class [NumericFormat](../)
* namespace [Aspose.Gis](../../numericformat/)
* assembly [Aspose.GIS](../../../)


