---
title: "Classify"
second_title: "GroupDocs.Classification .NET için API Referansı"
description: "Metni sınıflandırır."
type: docs
weight: 20
url: /tr/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

Metni sınıflandırır.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metin | String | Sınıflandırılacak ham metin. |
| bestClassesCount | Int32 | Döndürülecek en iyi sınıfların sayısı. |
| taksonomi | Taksonomi | Sınıflandırma için kullanılacak taksonomi. |
| precisionRecallBalance | PrecisionRecallBalance | Kesinlik ve geri çağırma arasındaki denge: kesinlik, geri çağırma veya varsayılan. |

### Dönüş Değeri

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Bir API istisnası oluştu. |

### Ayrıca Bakınız

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

Dosya adı ve dizin adıyla belgeyi sınıflandırır.

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya adı | String | Belge adı. |
| dizin | String | Belge dizini. |
| bestClassesCount | Int32 | Döndürülecek en iyi sınıfların sayısı. |
| taksonomi | Taksonomi | Sınıflandırma için kullanılacak taksonomi. |
| precisionRecallBalance | PrecisionRecallBalance | Kesinlik ve geri çağırma arasındaki denge: kesinlik, geri çağırma veya varsayılan. |
| parola | String | Belge parolası. |

### Dönüş Değeri

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Bir API istisnası oluştu. |

### Ayrıca Bakınız

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

Akıştan belgeyi sınıflandırır.

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Akış | Dosya akışı. |
| dosya adı | String | Dosya adı (isteğe bağlı dosya türü tanımlaması için). |
| bestClassesCount | Int32 | Döndürülecek en iyi sınıfların sayısı. |
| taksonomi | Taksonomi | Sınıflandırma için kullanılacak taksonomi. |
| precisionRecallBalance | PrecisionRecallBalance | Kesinlik ve geri çağırma arasındaki denge: kesinlik, geri çağırma veya varsayılan. |
| parola | String | Belge parolası. |

### Dönüş Değeri

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### İstisnalar

| istisna | koşul |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Bir API istisnası oluştu. |

### Ayrıca Bakınız

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Classification.dll için oluşturuldu -->
