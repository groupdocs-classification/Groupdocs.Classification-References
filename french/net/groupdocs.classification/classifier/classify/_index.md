---
title: "Classer"
second_title: "Référence API GroupDocs.Classification pour .NET"
description: "Classifie le texte."
type: docs
weight: 20
url: /fr/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

Classifie le texte.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| texte | String | Texte brut à classer. |
| bestClassesCount | Int32 | Nombre des meilleures classes à retourner. |
| taxonomie | Taxonomie | Taxonomie à utiliser pour la classification. |
| precisionRecallBalance | PrecisionRecallBalance | Équilibre entre la précision et le rappel : précision, rappel ou défaut. |

### Valeur de retour

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Une exception d'API s'est produite. |

### Voir aussi

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

Classifie le document par nom de fichier et nom de répertoire.

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filename | String | Nom du document. |
| directory | String | Répertoire du document. |
| bestClassesCount | Int32 | Nombre des meilleures classes à retourner. |
| taxonomie | Taxonomie | Taxonomie à utiliser pour la classification. |
| precisionRecallBalance | PrecisionRecallBalance | Équilibre entre la précision et le rappel : précision, rappel ou défaut. |
| password | String | Mot de passe du document. |

### Valeur de retour

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Une exception d'API s'est produite. |

### Voir aussi

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

Classifie le document depuis le flux.

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Flux de fichier. |
| filename | String | Nom de fichier (pour l'identification facultative du type de fichier). |
| bestClassesCount | Int32 | Nombre des meilleures classes à retourner. |
| taxonomie | Taxonomie | Taxonomie à utiliser pour la classification. |
| precisionRecallBalance | PrecisionRecallBalance | Équilibre entre la précision et le rappel : précision, rappel ou défaut. |
| password | String | Mot de passe du document. |

### Valeur de retour

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Une exception d'API s'est produite. |

### Voir aussi

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Classification.dll -->
