# ISiK MedicationRequestReplaces - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK MedicationRequestReplaces**

## Extension: ISiK MedicationRequestReplaces 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ExtensionISiKMedicationRequestReplaces | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ExtensionISiKMedicationRequestReplaces |

Extension zur Verlinkung der Medikationsverordnung die ersetzt wurde

**Context of Use**

**Usage info**

**Usages:**

* Use this Extension: [ISiKMedikationsVerordnung](StructureDefinition-ISiKMedikationsVerordnung.md)
* Examples for this Extension: [MedicationRequest/ExampleISiKMedikationsVerordnung2](MedicationRequest-ExampleISiKMedikationsVerordnung2.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ExtensionISiKMedicationRequestReplaces)

### Formal Views of Extension Content

 [Description of Profiles, Differentials, Snapshots, and how the XML and JSON presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ExtensionISiKMedicationRequestReplaces.csv), [Excel](StructureDefinition-ExtensionISiKMedicationRequestReplaces.xlsx), [Schematron](StructureDefinition-ExtensionISiKMedicationRequestReplaces.sch) 

#### Terminology Bindings

#### Constraints



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ExtensionISiKMedicationRequestReplaces",
  "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKMedicationRequestReplaces",
  "version" : "0.1.0",
  "name" : "ExtensionISiKMedicationRequestReplaces",
  "title" : "ISiK MedicationRequestReplaces",
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
  "description" : "Extension zur Verlinkung der Medikationsverordnung die ersetzt wurde",
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
        "short" : "ISiK MedicationRequestReplaces",
        "definition" : "Extension zur Verlinkung der Medikationsverordnung die ersetzt wurde"
      },
      {
        "id" : "Extension.extension",
        "path" : "Extension.extension",
        "max" : "0"
      },
      {
        "id" : "Extension.url",
        "path" : "Extension.url",
        "fixedUri" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKMedicationRequestReplaces"
      },
      {
        "id" : "Extension.value[x]",
        "path" : "Extension.value[x]",
        "min" : 1,
        "type" : [
          {
            "code" : "Reference",
            "targetProfile" : ["http://hl7.org/fhir/StructureDefinition/MedicationRequest"]
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
