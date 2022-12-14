---
title: Classify
second_title: Référence de l'API GroupDocs.Classification pour .NET
description: Classe le texte.
type: docs
weight: 20
url: /fr/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

Classe le texte.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| text | String | Texte brut à classer. |
| bestClassesCount | Int32 | Décompte des meilleures classes à rentrer. |
| taxonomy | Taxonomy | Taxonomie à utiliser pour la classification. |
| precisionRecallBalance | PrecisionRecallBalance | Équilibre entre précision et rappel : précision, rappel ou défaut. |

### Return_Value

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse/) avec les résultats du classement.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception/) | Une exception d'API s'est produite. |

### Voir également

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse/)
* enum [Taxonomy](../../taxonomy/)
* enum [PrecisionRecallBalance](../../precisionrecallbalance/)
* class [Classifier](../)
* espace de noms [GroupDocs.Classification](../../classifier/)
* Assemblée [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

Classe le document par nom de fichier et nom de répertoire.

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filename | String | Nom du document. |
| directory | String | Répertoire de documents. |
| bestClassesCount | Int32 | Décompte des meilleures classes à rentrer. |
| taxonomy | Taxonomy | Taxonomie à utiliser pour la classification. |
| precisionRecallBalance | PrecisionRecallBalance | Équilibre entre précision et rappel : précision, rappel ou défaut. |
| password | String | Mot de passe du document. |

### Return_Value

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse/) avec les résultats du classement.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception/) | Une exception d'API s'est produite. |

### Voir également

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse/)
* enum [Taxonomy](../../taxonomy/)
* enum [PrecisionRecallBalance](../../precisionrecallbalance/)
* class [Classifier](../)
* espace de noms [GroupDocs.Classification](../../classifier/)
* Assemblée [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

Classe le document du flux.

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| stream | Stream | Flux de fichiers. |
| filename | String | Nom de fichier (pour l'identification facultative du type de fichier). |
| bestClassesCount | Int32 | Décompte des meilleures classes à rentrer. |
| taxonomy | Taxonomy | Taxonomie à utiliser pour la classification. |
| precisionRecallBalance | PrecisionRecallBalance | Équilibre entre précision et rappel : précision, rappel ou défaut. |
| password | String | Mot de passe du document. |

### Return_Value

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse/) avec les résultats du classement.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception/) | Une exception d'API s'est produite. |

### Voir également

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse/)
* enum [Taxonomy](../../taxonomy/)
* enum [PrecisionRecallBalance](../../precisionrecallbalance/)
* class [Classifier](../)
* espace de noms [GroupDocs.Classification](../../classifier/)
* Assemblée [GroupDocs.Classification](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Classification.dll -->
