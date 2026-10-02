---
title: "Classify"
second_title: "GroupDocs.Classification für .NET API-Referenz"
description: "Klassifiziert Text."
type: docs
weight: 20
url: /de/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

Klassifiziert Text.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| text | String | Rohtext zum Klassifizieren. |
| bestClassesCount | Int32 | Anzahl der zurückzugebenden besten Klassen. |
| taxonomy | Taxonomie | Taxonomie, die für die Klassifizierung verwendet wird. |
| precisionRecallBalance | PrecisionRecallBalance | Balance zwischen precision und recall: precision, recall oder default. |

### Rückgabewert

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Eine API-Ausnahme ist aufgetreten. |

### Siehe auch

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

Klassifiziert ein Dokument nach Dateinamen und Verzeichnisnamen.

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filename | String | Dokumentname. |
| directory | String | Dokumentverzeichnis. |
| bestClassesCount | Int32 | Anzahl der zurückzugebenden besten Klassen. |
| taxonomy | Taxonomie | Taxonomie, die für die Klassifizierung verwendet wird. |
| precisionRecallBalance | PrecisionRecallBalance | Balance zwischen precision und recall: precision, recall oder default. |
| password | String | Dokumentpasswort. |

### Rückgabewert

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Eine API-Ausnahme ist aufgetreten. |

### Siehe auch

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

Klassifiziert ein Dokument aus einem Stream.

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| stream | Stream | Dateistream. |
| filename | String | Dateiname (zur optionalen Dateitypidentifizierung). |
| bestClassesCount | Int32 | Anzahl der zurückzugebenden besten Klassen. |
| taxonomy | Taxonomie | Taxonomie, die für die Klassifizierung verwendet wird. |
| precisionRecallBalance | PrecisionRecallBalance | Balance zwischen precision und recall: precision, recall oder default. |
| password | String | Dokumentpasswort. |

### Rückgabewert

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Eine API-Ausnahme ist aufgetreten. |

### Siehe auch

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Classification.dll -->
