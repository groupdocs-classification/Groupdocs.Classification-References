---
title: "SetLicense"
second_title: "GroupDocs.Classification voor .NET API-referentie"
description: "Licentieert het component."
type: docs
weight: 20
url: /nl/net/groupdocs.classification/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Licentieert het component.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| licenseName | String | Kan een volledige of korte bestandsnaam of de naam van een ingebedde resource zijn. Gebruik een lege tekenreeks om over te schakelen naar evaluatiemodus. |

### Opmerkingen

Probeert de licentie te vinden op de volgende locaties:

1. Expliciet pad.

2. De map die de Aspose-componentassembly bevat.

3. De map die de aanroepende assembly van de client bevat.

4. De map die de entry (startup) assembly bevat.

5. Een ingebedde resource in de aanroepende assembly van de client.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliciet pad.

2. Een ingebedde resource in de aanroepende assembly van de client.

### Zie ook

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

---

## SetLicense(Stream) {#setlicense}

Licentieert het component.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | Een stream die de licentie bevat. |

### Opmerkingen

Gebruik deze methode om een licentie uit een stream te laden.

### Zie ook

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.Classification.dll -->
