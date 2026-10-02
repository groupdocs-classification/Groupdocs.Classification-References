---
title: "Messbasiert"
second_title: "GroupDocs.Classification für .NET API-Referenz"
description: "Stellt Methoden zum Festlegen des Metered‑Schlüssels bereit."
type: docs
weight: 750
url: /de/net/groupdocs.classification/metered/
---
## Metered class

Stellt Methoden zum Festlegen des Metered‑Schlüssels bereit.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetMeteredKey](../../groupdocs.classification/metered/setmeteredkey)(string, string) | Setzt den messbasierten öffentlichen und privaten Schlüssel |
| static [GetConsumptionCredit](../../groupdocs.classification/metered/getconsumptioncredit)() | Liest das Verbrauchsguthaben ab |
| static [GetConsumptionQuantity](../../groupdocs.classification/metered/getconsumptionquantity)() | Liest die Verbrauchsdateigröße ab |

### Beispiele

In diesem Beispiel wird versucht, den messbasierten öffentlichen und privaten Schlüssel zu setzen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Siehe auch

* namespace [GroupDocs.Classification](../../groupdocs.classification)
* assembly [GroupDocs.Classification](../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Classification.dll -->
