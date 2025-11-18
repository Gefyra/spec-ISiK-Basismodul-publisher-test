# ISiK Selbstmedikation - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK Selbstmedikation**

## Extension: ISiK Selbstmedikation 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ExtensionISiKSelbstmedikation | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ExtensionISiKSelbstmedikation |

Mit dieser Erweiterung kann kenntlich gemacht werden, ob ein Arzneimittel als Selbstmedikation (d. h. ohne ärztliche Verordnung) eingenommen wird. Sie trägt zur vollständigen Erfassung der aktuellen Medikation und zur Erhöhung der Therapiesicherheit bei.

**Context of Use**

**Usage info**

**Usages:**

* Use this Extension: [ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md)
* Examples for this Extension: [Bundle/ExampleISiKMedikationTransaction](Bundle-ExampleISiKMedikationTransaction.md), [Bundle/ExampleISiKMedikationTransactionResponse](Bundle-ExampleISiKMedikationTransactionResponse.md) and [MedicationStatement/ExampleISiKMedikationsInformation1](MedicationStatement-ExampleISiKMedikationsInformation1.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ExtensionISiKSelbstmedikation)

### Formal Views of Extension Content

 [Description of Profiles, Differentials, Snapshots, and how the XML and JSON presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ExtensionISiKSelbstmedikation.csv), [Excel](StructureDefinition-ExtensionISiKSelbstmedikation.xlsx), [Schematron](StructureDefinition-ExtensionISiKSelbstmedikation.sch) 

#### Constraints



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ExtensionISiKSelbstmedikation",
  "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKSelbstmedikation",
  "version" : "0.1.0",
  "name" : "ExtensionISiKSelbstmedikation",
  "title" : "ISiK Selbstmedikation",
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
  "description" : "Mit dieser Erweiterung kann kenntlich gemacht werden, ob ein Arzneimittel als Selbstmedikation (d. h. ohne ärztliche Verordnung) eingenommen wird. Sie trägt zur vollständigen Erfassung der aktuellen Medikation und zur Erhöhung der Therapiesicherheit bei.",
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
      "expression" : "MedicationStatement"
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
        "short" : "ISiK Selbstmedikation",
        "definition" : "Mit dieser Erweiterung kann kenntlich gemacht werden, ob ein Arzneimittel als Selbstmedikation (d. h. ohne ärztliche Verordnung) eingenommen wird. Sie trägt zur vollständigen Erfassung der aktuellen Medikation und zur Erhöhung der Therapiesicherheit bei."
      },
      {
        "id" : "Extension.extension",
        "path" : "Extension.extension",
        "max" : "0"
      },
      {
        "id" : "Extension.url",
        "path" : "Extension.url",
        "fixedUri" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKSelbstmedikation"
      },
      {
        "id" : "Extension.value[x]",
        "path" : "Extension.value[x]",
        "min" : 1,
        "type" : [
          {
            "code" : "boolean"
          }
        ]
      }
    ]
  }
}

```
