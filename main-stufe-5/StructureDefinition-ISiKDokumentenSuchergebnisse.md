# Suchergebnisse einer Dokumentensuche - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Suchergebnisse einer Dokumentensuche**

## Resource Profile: Suchergebnisse einer Dokumentensuche 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKDokumentenSuchergebnisse | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKDokumentenSuchergebnisse |

**Usages:**

* Examples for this Profile: [Bundle/Suchergebnis-Beispiel](Bundle-Suchergebnis-Beispiel.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKDokumentenSuchergebnisse)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKDokumentenSuchergebnisse.csv), [Excel](StructureDefinition-ISiKDokumentenSuchergebnisse.xlsx), [Schematron](StructureDefinition-ISiKDokumentenSuchergebnisse.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKDokumentenSuchergebnisse",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKDokumentenSuchergebnisse",
  "version" : "0.1.0",
  "name" : "ISiKDokumentenSuchergebnisse",
  "title" : "Suchergebnisse einer Dokumentensuche",
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
        "short" : "Bundle-Typ",
        "comment" : "Fix: `searchset`",
        "fixedCode" : "searchset",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.total",
        "path" : "Bundle.total",
        "short" : "Gesamtzahl der Suchtreffer",
        "comment" : "Gesamtzahl der Suchtreffer auf dem Server, unabhängig vom Page-Size des aktuellen Bundles",
        "min" : 1
      },
      {
        "id" : "Bundle.entry",
        "path" : "Bundle.entry",
        "slicing" : {
          "discriminator" : [
            {
              "type" : "profile",
              "path" : "resource"
            }
          ],
          "rules" : "open"
        },
        "short" : "Ergebnisse der Dokumentensuche",
        "comment" : "Jedes Suchergebnis wird in einer separaten `entry` abgebildet. Bundles mit `total = 0` haben keine `entry`",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry:DocumentReference",
        "path" : "Bundle.entry",
        "sliceName" : "DocumentReference",
        "short" : "Suchergebnis",
        "min" : 0,
        "max" : "*",
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry:DocumentReference.fullUrl",
        "path" : "Bundle.entry.fullUrl",
        "short" : "Serverseitige URL der Ressource",
        "comment" : "Serverseitige URL der Ressource in `entry.resource`",
        "min" : 1,
        "mustSupport" : true
      },
      {
        "id" : "Bundle.entry:DocumentReference.resource",
        "path" : "Bundle.entry.resource",
        "short" : "Eingebettete Ressource",
        "comment" : "Eingebettete Ressource (hier: DocumentReference, die den Suchkriterien entspricht)",
        "min" : 1,
        "type" : [
          {
            "code" : "DocumentReference",
            "profile" : [
              "http://gefyra.info/training/StructureDefinition/ISiKDokumentenMetadaten"
            ]
          }
        ],
        "mustSupport" : true
      }
    ]
  }
}

```
