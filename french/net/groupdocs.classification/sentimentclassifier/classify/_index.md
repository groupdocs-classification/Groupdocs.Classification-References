---
title: "Classer"
second_title: "Référence API GroupDocs.Classification pour .NET"
description: "Classification de sentiment pour un texte."
type: docs
weight: 20
url: /fr/net/groupdocs.classification/sentimentclassifier/classify/
---
## SentimentClassifier.Classify method

Classification de sentiment pour un texte.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Sentiment)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| texte | String | Texte brut à classer. |
| bestClassesCount | Int32 | Nombre des meilleures classes à retourner. |
| taxonomie | Taxonomie | Taxonomie de sentiment (Sentiment ou Sentiment3). |

### Valeur de retour

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Une exception d'API s'est produite. |

### Voir aussi

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* class [SentimentClassifier](../../sentimentclassifier)
* namespace [GroupDocs.Classification](../../sentimentclassifier)
* assembly [GroupDocs.Classification](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Classification.dll -->
