---
title: "Classify"
second_title: "GroupDocs.Classification voor .NET API-referentie"
description: "Sentimentclassificatie voor een tekst."
type: docs
weight: 20
url: /nl/net/groupdocs.classification/sentimentclassifier/classify/
---
## SentimentClassifier.Classify method

Sentimentclassificatie voor een tekst.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Sentiment)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | String | Ruwe tekst om te classificeren. |
| bestClassesCount | Int32 | Aantal van de beste klassen om terug te geven. |
| taxonomy | Taxonomie | Sentimenttaxonomie (Sentiment of Sentiment3). |

### Retourwaarde

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Er is een API‑uitzondering opgetreden. |

### Zie ook

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* class [SentimentClassifier](../../sentimentclassifier)
* namespace [GroupDocs.Classification](../../sentimentclassifier)
* assembly [GroupDocs.Classification](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.Classification.dll -->
