---
title: Geometry.AsBinary
second_title: Αναφορά Aspose.GIS για .NET API
description: Geometry μέθοδος. Μεταφράζει αυτή τη γεωμετρία στη γνωστή δυαδική αναπαράστασή της.
type: docs
weight: 110
url: /el/net/aspose.gis.geometries/geometry/asbinary/
---
## AsBinary() {#asbinary}

Μεταφράζει αυτή τη γεωμετρία στη γνωστή δυαδική αναπαράστασή της.

```csharp
public byte[] AsBinary()
```

### Επιστρεφόμενη Αξία

Γνωστή δυαδική αναπαράσταση αυτής της γεωμετρίας.

### Παρατηρήσεις

Η έξοδος αυτής της μεθόδου είναι μέσαIso Παραλλαγή WKB.

### Δείτε επίσης

* class [Geometry](../)
* χώρος ονομάτων [Aspose.Gis.Geometries](../../geometry/)
* συνέλευση [Aspose.GIS](../../../)

---

## AsBinary(WkbVariant) {#asbinary_1}

Μεταφράζει αυτή τη γεωμετρία στη γνωστή δυαδική αναπαράστασή της.

```csharp
public byte[] AsBinary(WkbVariant variant)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| variant | WkbVariant | Γνωστή δυαδική παραλλαγή προς χρήση. |

### Επιστρεφόμενη Αξία

Γνωστή δυαδική αναπαράσταση αυτής της γεωμετρίας.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| NotSupportedException | Η γεωμετρία δεν μπορεί να αναπαρασταθεί στην παραλλαγή WKB που ζητήθηκε. Προς το παρόν αυτό συμβαίνει όταν [`HasCurveGeometry`](../hascurvegeometry/) της γεωμετρίας είναι`true` και η παραλλαγή WKB είναι SimpleFeatureAccessOutdated . |
| ArgumentOutOfRangeException | *variant* δεν είναι έγκυρο[`WkbVariant`](../../wkbvariant/). |

### Δείτε επίσης

* enum [WkbVariant](../../wkbvariant/)
* class [Geometry](../)
* χώρος ονομάτων [Aspose.Gis.Geometries](../../geometry/)
* συνέλευση [Aspose.GIS](../../../)


