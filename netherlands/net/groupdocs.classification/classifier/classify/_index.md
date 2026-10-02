---
title: "Classify"
second_title: "GroupDocs.Classification voor .NET API-referentie"
description: "Classificeert tekst."
type: docs
weight: 20
url: /nl/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

Classificeert tekst.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | String | Ruwe tekst om te classificeren. |
| bestClassesCount | Int32 | Aantal van de beste klassen om terug te geven. |
| taxonomy | Taxonomie | Taxonomie om te gebruiken voor classificatie. |
| precisionRecallBalance | PrecisionRecallBalance | Balans tussen precisie en recall: precisie, recall of standaard. |

### Retourwaarde

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Er is een API‑uitzondering opgetreden. |

### Zie ook

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

Classificeert document op bestandsnaam en mapnaam.

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bestandsnaam | String | Documentnaam. |
| map | String | Documentmap. |
| bestClassesCount | Int32 | Aantal van de beste klassen om terug te geven. |
| taxonomy | Taxonomie | Taxonomie om te gebruiken voor classificatie. |
| precisionRecallBalance | PrecisionRecallBalance | Balans tussen precisie en recall: precisie, recall of standaard. |
| wachtwoord | String | Documentwachtwoord. |

### Retourwaarde

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Er is een API‑uitzondering opgetreden. |

### Zie ook

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

Classificeert document vanuit stream.

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Bestandsstroom. |
| bestandsnaam | String | Bestandsnaam (voor optionele bestandstype-identificatie). |
| bestClassesCount | Int32 | Aantal van de beste klassen om terug te geven. |
| taxonomy | Taxonomie | Taxonomie om te gebruiken voor classificatie. |
| precisionRecallBalance | PrecisionRecallBalance | Balans tussen precisie en recall: precisie, recall of standaard. |
| wachtwoord | String | Documentwachtwoord. |

### Retourwaarde

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Er is een API‑uitzondering opgetreden. |

### Zie ook

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.Classification.dll -->
