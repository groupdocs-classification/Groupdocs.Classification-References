---
title: "Clasificar"
second_title: "Referencia de API de GroupDocs.Classification para .NET"
description: "Clasificación de sentimiento para un texto."
type: docs
weight: 20
url: /es/net/groupdocs.classification/sentimentclassifier/classify/
---
## SentimentClassifier.Classify method

Clasificación de sentimiento para un texto.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Sentiment)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | String | Texto sin procesar para clasificar. |
| bestClassesCount | Int32 | Cantidad de las mejores clases a devolver. |
| taxonomía | Taxonomía | Taxonomía de sentimientos (Sentiment o Sentiment3). |

### Valor de retorno

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Excepciones

| excepción | condición |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Se produjo una excepción de API. |

### Ver también

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* class [SentimentClassifier](../../sentimentclassifier)
* namespace [GroupDocs.Classification](../../sentimentclassifier)
* assembly [GroupDocs.Classification](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Classification.dll -->
