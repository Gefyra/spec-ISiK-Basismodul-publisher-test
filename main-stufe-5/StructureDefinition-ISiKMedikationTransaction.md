# ISiK Medikation Transactionbundle - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK Medikation Transactionbundle**

## Resource Profile: ISiK Medikation Transactionbundle 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKMedikationTransaction | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKMedikationTransaction |

 
Dieses Profil definiert die Transaktions-Bundles im Rahmen von ISiK-Medikations-Szenarien. 

**Usages:**

* Examples for this Profile: [Bundle/ExampleISiKMedikationTransaction](Bundle-ExampleISiKMedikationTransaction.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKMedikationTransaction)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKMedikationTransaction.csv), [Excel](StructureDefinition-ISiKMedikationTransaction.xlsx), [Schematron](StructureDefinition-ISiKMedikationTransaction.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKMedikationTransaction",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKMedikationTransaction",
  "version" : "0.1.0",
  "name" : "ISiKMedikationTransaction",
  "title" : "ISiK Medikation Transactionbundle",
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
  "description" : "Dieses Profil definiert die Transaktions-Bundles im Rahmen von ISiK-Medikations-Szenarien.",
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
        "comment" : "fix: transaction",
        "fixedCode" : "transaction",
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
        "comment" : "auch die Verwendung von UUIDs in der Form ';urn:uuid:.....' ist möglich.",
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
        "short" : "HTTP-Request innerhalb der Transaktion",
        "min" : 1,
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry.request.method",
        "path" : "Bundle.entry.request.method",
        "short" : "HTTP-Verb",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry.request.url",
        "path" : "Bundle.entry.request.url",
        "short" : "Request-URL",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry.response",
        "path" : "Bundle.entry.response",
        "max" : "0"
      }
    ]
  }
}

```
