---
title: "SetLicense"
second_title: "GroupDocs.Classification für .NET API-Referenz"
description: "Lizenziert die Komponente."
type: docs
weight: 20
url: /de/net/groupdocs.classification/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Lizenziert die Komponente.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| licenseName | String | Kann ein voller oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie eine leere Zeichenfolge, um in den Evaluierungsmodus zu wechseln. |

### Hinweise

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner, der die Aspose-Komponentenassembly enthält.

3. Der Ordner, der die Aufruf-Assembly des Clients enthält.

4. Der Ordner, der die Einstieg (Startup) Assembly enthält.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

### Siehe auch

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

---

## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream, der die Lizenz enthält. |

### Hinweise

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

### Siehe auch

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

<!-- NICHT BEARBEITEN: generiert von xmldocmd für GroupDocs.Classification.dll -->
