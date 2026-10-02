---
title: "Classify"
second_title: "GroupDocs.Classification για .NET Αναφορά API"
description: "Κατηγοριοποίηση συναισθήματος για κείμενο."
type: docs
weight: 20
url: /el/net/groupdocs.classification/sentimentclassifier/classify/
---
## SentimentClassifier.Classify method

Κατηγοριοποίηση συναισθήματος για κείμενο.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Sentiment)
```

| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| text | String | Ακατέργαστο κείμενο για ταξινόμηση. |
| bestClassesCount | Int32 | Αριθμός των καλύτερων κλάσεων που θα επιστραφούν. |
| taxonomy | Ταξινομία | Ταξινομία συναισθήματος (Sentiment ή Sentiment3). |

### Τιμή Επιστροφής

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Εξαιρέσεις

| εξαίρεση | συνθήκη |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Παρουσιάστηκε μια εξαίρεση API. |

### Δείτε επίσης

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* class [SentimentClassifier](../../sentimentclassifier)
* namespace [GroupDocs.Classification](../../sentimentclassifier)
* assembly [GroupDocs.Classification](../../../)

<!-- ΜΗ ΕΠΕΞΕΡΓΑΣΙΑ: δημιουργήθηκε από xmldocmd για GroupDocs.Classification.dll -->
