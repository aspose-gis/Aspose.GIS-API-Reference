---
title: IGeometry.Relate
second_title: Αναφορά Aspose.GIS για .NET API
description: IGeometry μέθοδος. Καθορίζει εάν ο πίνακας τομής DE9IM αυτής της γεωμετρίας και μια καθορισμένη γεωμετρία ταιριάζει με το παρεχόμενο μοτίβο.
type: docs
weight: 290
url: /el/net/aspose.gis.geometries/igeometry/relate/
---
## IGeometry.Relate method

Καθορίζει εάν ο πίνακας τομής DE-9IM αυτής της γεωμετρίας και μια καθορισμένη γεωμετρία ταιριάζει με το παρεχόμενο μοτίβο.

```csharp
public bool Relate(IGeometry other, string intersectionPatternMatrix)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | IGeometry | Μια γεωμετρία. |
| intersectionPatternMatrix | String | Ένα μοτίβο που ταιριάζει με. Αυτή θα πρέπει να είναι μια συμβολοσειρά με μήκος ίσο με 9. Κάθε χαρακτήρας της συμβολοσειράς αντιπροσωπεύει την αναμενόμενη διάσταση μιας τομής: χαρακτήρας 0 - μεταξύ των εσωτερικών χώρων των γεωμετριών.χαρακτήρας 1 - μεταξύ του εσωτερικού αυτής της γεωμετρίας και των ορίων μιας άλλης γεωμετρίας.χαρακτήρας 2 - μεταξύ του εσωτερικού αυτής της γεωμετρίας και του εξωτερικού μιας άλλης γεωμετρίας.χαρακτήρας 3 - μεταξύ ορίου αυτής της γεωμετρίας και εσωτερικού μιας άλλης γεωμετρίας.χαρακτήρας 4 - μεταξύ των ορίων των γεωμετριών.χαρακτήρας 5 - μεταξύ των ορίων αυτής της γεωμετρίας και του εξωτερικού μιας άλλης γεωμετρίας.χαρακτήρας 6 - μεταξύ του εξωτερικού αυτής της γεωμετρίας και του εσωτερικού μιας άλλης γεωμετρίας.χαρακτήρας 7 - μεταξύ του εξωτερικού αυτής της γεωμετρίας και του ορίου μιας άλλης γεωμετρίας.χαρακτήρας 8 - μεταξύ των εξωτερικών όψεων των γεωμετριών. Πιθανές τιμές για κάθε χαρακτήρα είναι: * - οποιαδήποτε τιμή.F - χωρίς διασταύρωση.T - οποιαδήποτε διασταύρωση.0 - διασταύρωση σημείου (π.χ. κοινό σημείο).1 - τομή γραμμής (π.χ. κοινό τμήμα γραμμής).2 - διασταύρωση περιοχής (π.χ. κοινό τμήμα πολυγώνου). Για παράδειγμα, ένα μοτίβο τομής "F0*******" σημαίνει ότι δεν πρέπει να υπάρχει τομή μεταξύ γεωμετριών interiors και η τομή μεταξύ ορίων γεωμετρίας πρέπει να είναι ένα σημείο. Δείτε το OpenGIS Simple Features Specification για περισσότερες λεπτομέρειες σχετικά με τον πίνακα τομής μοτίβο. |

### Επιστρεφόμενη Αξία

`true` εάν αυτός ο πίνακας τομής ταιριάζει με το patter.`false` διαφορετικά.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | *other* είναι`null`. |
| ArgumentException | Μία από τις γεωμετρίες δεν είναι έγκυρη με τέτοιο τρόπο ώστε η λειτουργία να μην μπορεί να ολοκληρωθεί. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) των γεωμετριών δεν είναι ισοδύναμες. Μπορείτε να χρησιμοποιήσετε[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) προκειμένου να μετατραπούν οι γεωμετρίες στο ίδιο σύστημα αναφοράς spatial . |

### Παρατηρήσεις

Αυτή η μέθοδος δημιουργεί τον πίνακα τομής DE-9IM και τον αντιστοιχίζει με το pattern Δείτε το OpenGIS Simple Features Specification για περισσότερες λεπτομέρειες σχετικά με τον πίνακα τομής DE-9IM.

### Παραδείγματα

Ο παρακάτω κωδικός:  Το θα εντοπίσει εάν οι γεωμετρίες είναι χωρικά ίσες.

```csharp
geometry.Relate(other, "T*F**FFF*");
```

### Δείτε επίσης

* interface [IGeometry](../)
* χώρος ονομάτων [Aspose.Gis.Geometries](../../igeometry/)
* συνέλευση [Aspose.GIS](../../../)


