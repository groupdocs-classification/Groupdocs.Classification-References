---
title: "SetLicense"
second_title: "GroupDocs.Classification για .NET Αναφορά API"
description: "Παρέχει άδεια στο στοιχείο."
type: docs
weight: 20
url: /el/net/groupdocs.classification/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Παρέχει άδεια στο στοιχείο.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| licenseName | String | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου. Χρησιμοποιήστε μια κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |

### Παρατηρήσεις

Προσπαθεί να βρει την άδεια στις ακόλουθες τοποθεσίες:

1. Ρητή διαδρομή.

2. Ο φάκελος που περιέχει τη συναρμολόγηση του στοιχείου Aspose.

3. Ο φάκελος που περιέχει τη συναρμολόγηση κλήσης του πελάτη.

4. Ο φάκελος που περιέχει τη συναρμολόγηση εκκίνησης.

5. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Ρητή διαδρομή.

2. Ένας ενσωματωμένος πόρος στη συναρμολόγηση κλήσης του πελάτη.

### Δείτε επίσης

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

---

## SetLicense(Stream) {#setlicense}

Παρέχει άδεια στο στοιχείο.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Μια ροή που περιέχει την άδεια. |

### Παρατηρήσεις

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από μια ροή.

### Δείτε επίσης

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

<!-- ΜΗ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Classification.dll -->
