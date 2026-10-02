---
title: "Μετρημένο"
second_title: "GroupDocs.Classification για .NET Αναφορά API"
description: "Παρέχει μεθόδους για τον ορισμό κλειδιού μετρητή."
type: docs
weight: 750
url: /el/net/groupdocs.classification/metered/
---
## Metered class

Παρέχει μεθόδους για τον ορισμό κλειδιού μετρητή.

```csharp
public class Metered
```

## Κατασκευαστές

| Όνομα | Περιγραφή |
| --- | --- |
| [Metered](metered)() | Αρχικοποιεί μια νέα παρουσία αυτής της κλάσης. |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [SetMeteredKey](../../groupdocs.classification/metered/setmeteredkey)(string, string) | Ορίζει το μετρημένο δημόσιο και ιδιωτικό κλειδί |
| static [GetConsumptionCredit](../../groupdocs.classification/metered/getconsumptioncredit)() | Λαμβάνει πίστωση κατανάλωσης |
| static [GetConsumptionQuantity](../../groupdocs.classification/metered/getconsumptionquantity)() | Λαμβάνει το μέγεθος αρχείου κατανάλωσης |

### Παραδείγματα

Σε αυτό το παράδειγμα, θα γίνει προσπάθεια να οριστεί το μετρημένο δημόσιο και ιδιωτικό κλειδί

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Δείτε επίσης

* namespace [GroupDocs.Classification](../../groupdocs.classification)
* assembly [GroupDocs.Classification](../../)

<!-- ΜΗ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Classification.dll -->
