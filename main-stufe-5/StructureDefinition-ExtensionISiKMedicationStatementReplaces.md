# ISiK MedicationStatementReplaces - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK MedicationStatementReplaces**

## Extension: ISiK MedicationStatementReplaces 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ExtensionISiKMedicationStatementReplaces | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ExtensionISiKMedicationStatementReplaces |

Mit dieser Erweiterung kann festgelegt werden, welche vorherige Medikation durch die aktuelle Verordnung ersetzt wird. Sie erleichtert die Nachverfolgung von Therapieänderungen, sorgt für Transparenz im Medikationsprozess.

**Context of Use**

**Usage info**

**Usages:**

* Use this Extension: [ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md)
* Examples for this Extension: [MedicationStatement/ExampleISiKMedikationsInformation2](MedicationStatement-ExampleISiKMedikationsInformation2.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ExtensionISiKMedicationStatementReplaces)

### Formal Views of Extension Content

 [Description of Profiles, Differentials, Snapshots, and how the XML and JSON presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ExtensionISiKMedicationStatementReplaces.csv), [Excel](StructureDefinition-ExtensionISiKMedicationStatementReplaces.xlsx), [Schematron](StructureDefinition-ExtensionISiKMedicationStatementReplaces.sch) 

#### Terminology Bindings

#### Constraints



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ExtensionISiKMedicationStatementReplaces",
  "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKMedicationStatementReplaces",
  "version" : "0.1.0",
  "name" : "ExtensionISiKMedicationStatementReplaces",
  "title" : "ISiK MedicationStatementReplaces",
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
  "description" : "Mit dieser Erweiterung kann festgelegt werden, welche vorherige Medikation durch die aktuelle Verordnung ersetzt wird. Sie erleichtert die Nachverfolgung von Therapieänderungen, sorgt für Transparenz im Medikationsprozess.",
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
        "short" : "ISiK MedicationStatementReplaces",
        "definition" : "Mit dieser Erweiterung kann festgelegt werden, welche vorherige Medikation durch die aktuelle Verordnung ersetzt wird. Sie erleichtert die Nachverfolgung von Therapieänderungen, sorgt für Transparenz im Medikationsprozess."
      },
      {
        "id" : "Extension.extension",
        "path" : "Extension.extension",
        "max" : "0"
      },
      {
        "id" : "Extension.url",
        "path" : "Extension.url",
        "fixedUri" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKMedicationStatementReplaces"
      },
      {
        "id" : "Extension.value[x]",
        "path" : "Extension.value[x]",
        "min" : 1,
        "type" : [
          {
            "code" : "Reference",
            "targetProfile" : [
              "http://hl7.org/fhir/StructureDefinition/MedicationStatement"
            ]
          }
        ]
      },
      {
        "id" : "Extension.value[x].reference",
        "path" : "Extension.value[x].reference",
        "min" : 1
      }
    ]
  }
}

```
