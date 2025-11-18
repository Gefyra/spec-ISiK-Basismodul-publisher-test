# ISiK Medikation TransactionBundle-Response - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK Medikation TransactionBundle-Response**

## Resource Profile: ISiK Medikation TransactionBundle-Response 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKMedikationTransactionResponse | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKMedikationTransactionResponse |

 
Dieses Profil definiert die Server-Antwort auf Transaktions-Bundles im Rahmen von ISiK-Medikations-Szenarien. 

**Usages:**

* Examples for this Profile: [Bundle/ExampleISiKMedikationTransactionResponse](Bundle-ExampleISiKMedikationTransactionResponse.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKMedikationTransactionResponse)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKMedikationTransactionResponse.csv), [Excel](StructureDefinition-ISiKMedikationTransactionResponse.xlsx), [Schematron](StructureDefinition-ISiKMedikationTransactionResponse.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKMedikationTransactionResponse",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationTransactionResponse",
  "version" : "0.1.0",
  "name" : "ISiKMedikationTransactionResponse",
  "title" : "ISiK Medikation TransactionBundle-Response",
  "status" : "active",
  "experimental" : false,
  "date" : "2025-10-23",
  "publisher" : "Gefyra GmbH",
  "contact" : [
    {
      "name" : "Gefyra GmbH",
      "telecom" : [
        {
          "system" : "url",
          "value" : "https://gefyra.info/"
        }
      ]
    }
  ],
  "description" : "Dieses Profil definiert die Server-Antwort auf Transaktions-Bundles im Rahmen von ISiK-Medikations-Szenarien.",
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "v2",
      "uri" : "http://hl7.org/v2",
      "name" : "HL7 v2 Mapping"
    },
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    },
    {
      "identity" : "cda",
      "uri" : "http://hl7.org/v3/cda",
      "name" : "CDA (R2)"
    },
    {
      "identity" : "w5",
      "uri" : "http://hl7.org/fhir/fivews",
      "name" : "FiveWs Pattern Mapping"
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Bundle",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Bundle",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Bundle",
        "path" : "Bundle"
      },
      {
        "id" : "Bundle.id",
        "path" : "Bundle.id",
        "short" : "serverseitige, interne ID des Datensatzes",
        "comment" : "**bedingtes Pflichtfeld/bedingtes MS:** Alle von einem Server bereitgestellten Ressourcen MÜSSEN über eine `id` verfügen.\n  Von Clients erzeugte Ressourcen, die im Kontext einer CREATE-Interaktion übermittelt werden, MÜSSEN NICHT über eine `id`verfügen. ",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.meta.versionId",
        "path" : "Bundle.meta.versionId",
        "short" : "Eindeutiger Name der serverseitigen Version des Datensatzes",
        "comment" : "Alle von einem Server bereitgestellten Ressourcen SOLLEN über eine `versionID` verfügen.\n  Von Clients erzeugte Ressourcen, die im Kontext einer CREATE-Interaktion übermittelt werden, MÜSSEN NICHT über eine `versionID`verfügen. "
      },
      {
        "id" : "Bundle.meta.lastUpdated",
        "path" : "Bundle.meta.lastUpdated",
        "short" : "Zeitpunkt der letzten Änderung",
        "comment" : "Alle von einem Server bereitgestellten Ressourcen SOLLEN über ein `lastUpdate` verfügen.\n  Von Clients erzeugte Ressourcen, die im Kontext einer CREATE-Interaktion übermittelt werden, MÜSSEN NICHT über ein `lastUpdate`verfügen. "
      },
      {
        "id" : "Bundle.type",
        "path" : "Bundle.type",
        "short" : "Type des Bundles",
        "comment" : "fix: transaction-response",
        "fixedCode" : "transaction-response",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry",
        "path" : "Bundle.entry",
        "short" : "Der einzelne Eintrag zur Interaktion",
        "min" : 1,
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry.link",
        "path" : "Bundle.entry.link",
        "max" : "0"
      },
      {
        "id" : "Bundle.entry.fullUrl",
        "path" : "Bundle.entry.fullUrl",
        "short" : "vollständige URL der Ressource",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry.resource",
        "path" : "Bundle.entry.resource",
        "short" : "Die Ressourcen-Instanz der Interaktion",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry.search",
        "path" : "Bundle.entry.search",
        "max" : "0"
      },
      {
        "id" : "Bundle.entry.request",
        "path" : "Bundle.entry.request",
        "max" : "0"
      },
      {
        "id" : "Bundle.entry.response",
        "path" : "Bundle.entry.response",
        "short" : "HTTP-Response des Servers innerhalb der Transaktions-Antwort",
        "min" : 1,
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry.response.status",
        "path" : "Bundle.entry.response.status",
        "short" : "HTTP-Statuscode",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry.response.location",
        "path" : "Bundle.entry.response.location",
        "short" : "Location der Ressource (URL) auf dem Server",
        "comment" : "Gemäß FHIR-Spezifikation MUSS hier der Pfad zur exakten Version (History) enthalten sein, wenn der Server History unterstützt.",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry.response.outcome",
        "path" : "Bundle.entry.response.outcome",
        "short" : "OperationOutcome-Ressource zur Rückgabe von Fehler-Details sowie Informationen.",
        "mustSupport" : true
      }
    ]
  }
}

```
