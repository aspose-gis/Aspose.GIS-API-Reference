---
title: Feature.GetValuesDump
second_title: Αναφορά Aspose.GIS για .NET API
description: Feature μέθοδος. Επιστρέφει τις τιμές για όλα τα χαρακτηριστικά ενός πίνακα. Εξετάστε το ενδεχόμενο να χρησιμοποιήσετεGetValues μέθοδος αποφυγής πρόσθετης εκχώρησης μνήμης.
type: docs
weight: 60
url: /el/net/aspose.gis/feature/getvaluesdump/
---
## Feature.GetValuesDump method

Επιστρέφει τις τιμές για όλα τα χαρακτηριστικά ενός πίνακα. Εξετάστε το ενδεχόμενο να χρησιμοποιήσετε[`GetValues`](../getvalues/) μέθοδος αποφυγής πρόσθετης εκχώρησης μνήμης.

```csharp
public object[] GetValuesDump(object defaultValue = null)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| defaultValue | Object | Η τιμή που πρέπει να επιστραφεί εάν η τιμή του χαρακτηριστικού λείπει (δεν έχει οριστεί). Η προεπιλεγμένη τιμή είναι`null`. Σκεφτείτε να χρησιμοποιήσετε το 'DBNull.Τιμή' για τον διαχωρισμό των 'unset' και '`null` τιμές. |

### Επιστρεφόμενη Αξία

Ένας νέος πίνακας στον οποίο θα αντιγραφούν οι τιμές των χαρακτηριστικών.

### Εξαιρέσεις

| εξαίρεση | κατάσταση |
| --- | --- |
| ArgumentNullException | Το επιχείρημα είναι`null`. |
| InvalidOperationException | Το χαρακτηριστικό δεν είναι κλειδωμένο. |

### Παρατηρήσεις

Τα χαρακτηριστικά τιμών του χαρακτηριστικού αντιγράφονται στον πίνακα τιμών που μεταβιβάζεται ως παράμετρος. Για χαρακτηριστικά με μη καθορισμένη τιμή, επιστρέφεται η καθορισμένη παράμετρος 'unsetValue'.

### Δείτε επίσης

* class [Feature](../)
* χώρος ονομάτων [Aspose.Gis](../../feature/)
* συνέλευση [Aspose.GIS](../../../)


