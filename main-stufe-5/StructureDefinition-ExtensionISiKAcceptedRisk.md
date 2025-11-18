# ISiK Accepted Risk - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK Accepted Risk**

## Extension: ISiK Accepted Risk 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ExtensionISiKAcceptedRisk | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ExtensionISiKAcceptedRisk |

Extension zur Dokumentation eines im Rahmen der AMTS bewusst eingegangenen Risikos. In diesem Freitext kann die Begründung und ggf. zu treffende besondere Maßnahmen dokumentiert werden.

**Context of Use**

**Usage info**

**Usages:**

* Use this Extension: [ISiK AMTS-Bewertung](StructureDefinition-ISiKAMTSBewertung.md), [ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md) and [ISiKMedikationsVerordnung](StructureDefinition-ISiKMedikationsVerordnung.md)
* Examples for this Extension: [Bundle/ExampleISiKMedikationTransaction](Bundle-ExampleISiKMedikationTransaction.md), [Bundle/ExampleISiKMedikationTransactionResponse](Bundle-ExampleISiKMedikationTransactionResponse.md), [MedicationRequest/ExampleISiKMedikationsVerordnung](MedicationRequest-ExampleISiKMedikationsVerordnung.md) and [MedicationStatement/ExampleISiKMedikationsInformation1](MedicationStatement-ExampleISiKMedikationsInformation1.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ExtensionISiKAcceptedRisk)

### Formal Views of Extension Content

 [Description of Profiles, Differentials, Snapshots, and how the XML and JSON presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ExtensionISiKAcceptedRisk.csv), [Excel](StructureDefinition-ExtensionISiKAcceptedRisk.xlsx), [Schematron](StructureDefinition-ExtensionISiKAcceptedRisk.sch) 

#### Constraints



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ExtensionISiKAcceptedRisk",
  "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKAcceptedRisk",
  "version" : "0.1.0",
  "name" : "ExtensionISiKAcceptedRisk",
  "title" : "ISiK Accepted Risk",
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
  "description" : "Extension zur Dokumentation eines im Rahmen der AMTS bewusst eingegangenen Risikos. In diesem Freitext kann die Begründung und ggf. zu treffende besondere Maßnahmen dokumentiert werden.",
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "rim",
      "uri" : "http://hl7.org/v3",
      "name" : "RIM Mapping"
    }
  ],
  "kind" : "complex-type",
  "abstract" : false,
  "context" : [
    {
      "type" : "element",
      "expression" : "RiskAssessment"
    },
    {
      "type" : "element",
      "expression" : "MedicationStatement"
    },
    {
      "type" : "element",
      "expression" : "MedicationRequest"
    }
  ],
  "type" : "Extension",
  "baseDefinition" : "http://hl7.org/fhir/StructureDefinition/Extension",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Extension",
        "path" : "Extension",
        "short" : "ISiK Accepted Risk",
        "definition" : "Extension zur Dokumentation eines im Rahmen der AMTS bewusst eingegangenen Risikos. In diesem Freitext kann die Begründung und ggf. zu treffende besondere Maßnahmen dokumentiert werden."
      },
      {
        "id" : "Extension.extension",
        "path" : "Extension.extension",
        "max" : "0"
      },
      {
        "id" : "Extension.url",
        "path" : "Extension.url",
        "fixedUri" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKAcceptedRisk"
      },
      {
        "id" : "Extension.value[x]",
        "path" : "Extension.value[x]",
        "min" : 1,
        "type" : [
          {
            "code" : "string"
          }
        ]
      }
    ]
  }
}

```
