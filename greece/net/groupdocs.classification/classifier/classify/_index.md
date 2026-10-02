---
title: "Classify"
second_title: "GroupDocs.Classification για .NET Αναφορά API"
description: "Κατηγοριοποιεί κείμενο."
type: docs
weight: 20
url: /el/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

Κατηγοριοποιεί κείμενο.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | String | Ακατέργαστο κείμενο για ταξινόμηση. |
| bestClassesCount | Int32 | Αριθμός των καλύτερων κλάσεων που θα επιστραφούν. |
| taxonomy | Ταξινομία | Ταξινομία για χρήση στην ταξινόμηση. |
| precisionRecallBalance | PrecisionRecallBalance | Ισορροπία μεταξύ ακρίβειας και ανάκλησης: ακρίβεια, ανάκληση ή προεπιλογή. |

### Τιμή Επιστροφής

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Παρουσιάστηκε μια εξαίρεση API. |

### Δείτε επίσης

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

Κατηγοριοποιεί έγγραφο με βάση το όνομα αρχείου και το όνομα καταλόγου.

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| όνομα αρχείου | String | Όνομα εγγράφου. |
| κατάλογος | String | Κατάλογος εγγράφου. |
| bestClassesCount | Int32 | Αριθμός των καλύτερων κλάσεων που θα επιστραφούν. |
| taxonomy | Ταξινομία | Ταξινομία για χρήση στην ταξινόμηση. |
| precisionRecallBalance | PrecisionRecallBalance | Ισορροπία μεταξύ ακρίβειας και ανάκλησης: ακρίβεια, ανάκληση ή προεπιλογή. |
| κωδικός | String | Κωδικός εγγράφου. |

### Τιμή Επιστροφής

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Παρουσιάστηκε μια εξαίρεση API. |

### Δείτε επίσης

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

Κατηγοριοποιεί έγγραφο από ροή.

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ροή | Ροή | Ροή αρχείου. |
| όνομα αρχείου | String | Όνομα αρχείου (για προαιρετική ταυτοποίηση τύπου αρχείου). |
| bestClassesCount | Int32 | Αριθμός των καλύτερων κλάσεων που θα επιστραφούν. |
| taxonomy | Ταξινομία | Ταξινομία για χρήση στην ταξινόμηση. |
| precisionRecallBalance | PrecisionRecallBalance | Ισορροπία μεταξύ ακρίβειας και ανάκλησης: ακρίβεια, ανάκληση ή προεπιλογή. |
| κωδικός | String | Κωδικός εγγράφου. |

### Τιμή Επιστροφής

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Παρουσιάστηκε μια εξαίρεση API. |

### Δείτε επίσης

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

<!-- ΜΗ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Classification.dll -->
