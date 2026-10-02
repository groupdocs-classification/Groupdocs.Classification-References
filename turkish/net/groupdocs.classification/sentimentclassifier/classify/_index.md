---
title: "Classify"
second_title: "GroupDocs.Classification .NET için API Referansı"
description: "Bir metin için duygu sınıflandırması."
type: docs
weight: 20
url: /tr/net/groupdocs.classification/sentimentclassifier/classify/
---
## SentimentClassifier.Classify method

Bir metin için duygu sınıflandırması.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Sentiment)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | String | Sınıflandırılacak ham metin. |
| bestClassesCount | Int32 | Döndürülecek en iyi sınıfların sayısı. |
| taksonomi | Taksonomi | Duygu taksonomisi (Sentiment veya Sentiment3). |

### Dönüş Değeri

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Bir API istisnası oluştu. |

### Ayrıca Bakınız

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* class [SentimentClassifier](../../sentimentclassifier)
* namespace [GroupDocs.Classification](../../sentimentclassifier)
* assembly [GroupDocs.Classification](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Classification.dll için oluşturuldu -->
