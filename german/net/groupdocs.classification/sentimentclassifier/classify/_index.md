---
title: "Classify"
second_title: "GroupDocs.Classification für .NET API-Referenz"
description: "Sentiment‑Klassifizierung für einen Text."
type: docs
weight: 20
url: /de/net/groupdocs.classification/sentimentclassifier/classify/
---
## SentimentClassifier.Classify method

Sentiment‑Klassifizierung für einen Text.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Sentiment)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | String | Rohtext zum Klassifizieren. |
| bestClassesCount | Int32 | Anzahl der zurückzugebenden besten Klassen. |
| taxonomy | Taxonomie | Sentiment-Taxonomie (Sentiment oder Sentiment3). |

### Rückgabewert

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Eine API-Ausnahme ist aufgetreten. |

### Siehe auch

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* class [SentimentClassifier](../../sentimentclassifier)
* namespace [GroupDocs.Classification](../../sentimentclassifier)
* assembly [GroupDocs.Classification](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Classification.dll -->
