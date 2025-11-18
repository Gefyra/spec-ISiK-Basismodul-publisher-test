# ISiKMDRRelevanzFormularExtension - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKMDRRelevanzFormularExtension**

## Extension: ISiKMDRRelevanzFormularExtension 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKMDRRelevanzFormularExtension | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKMDRRelevanzFormularExtension |

Mit der Extension wird die Medizinprodukt-Relevanz angegeben. Ist die Extension nicht vorhanden, ist nichts in Richtung der MDR zu beachten. Sobald sie vorhanden ist, müssen ggf. Voraussetzung zur Befüllung oder Anzeige erfüllt sein. Im aktuellen Rahmen des Moduls sind diese aber nicht weiter spezifizert.

**Context of Use**

**Usage info**

**Usages:**

* Use this Extension: [Ausgefülltes ISiK-Formular](StructureDefinition-ISiKFormularDaten.md) and [ISiKFormularDefinition](StructureDefinition-ISiKFormularDefinition.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKMDRRelevanzFormularExtension)

### Formal Views of Extension Content

 [Description of Profiles, Differentials, Snapshots, and how the XML and JSON presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKMDRRelevanzFormularExtension.csv), [Excel](StructureDefinition-ISiKMDRRelevanzFormularExtension.xlsx), [Schematron](StructureDefinition-ISiKMDRRelevanzFormularExtension.sch) 

#### Terminology Bindings

#### Constraints



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKMDRRelevanzFormularExtension",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKMDRRelevanzFormularExtension",
  "version" : "0.1.0",
  "name" : "ISiKMDRRelevanzFormularExtension",
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
  "description" : "Mit der Extension wird die Medizinprodukt-Relevanz angegeben. Ist die Extension nicht vorhanden, ist nichts in Richtung der MDR zu beachten. Sobald sie vorhanden ist, müssen ggf. Voraussetzung zur Befüllung oder Anzeige erfüllt sein. Im aktuellen Rahmen des Moduls sind diese aber nicht weiter spezifizert.",
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
      "expression" : "Questionnaire"
    },
    {
      "type" : "element",
      "expression" : "QuestionnaireResponse"
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
        "definition" : "Mit der Extension wird die Medizinprodukt-Relevanz angegeben. Ist die Extension nicht vorhanden, ist nichts in Richtung der MDR zu beachten. Sobald sie vorhanden ist, müssen ggf. Voraussetzung zur Befüllung oder Anzeige erfüllt sein. Im aktuellen Rahmen des Moduls sind diese aber nicht weiter spezifizert.",
        "isModifier" : true,
        "isModifierReason" : "Ist in dieser Extension nicht der Code 'none' gesetzt, muss die Anzeige rechtlich geprüft werden, weil der FormularDefinitionErsteller eine Relevanz im Rahmen der MDR identifiziert hat."
      },
      {
        "id" : "Extension.extension",
        "path" : "Extension.extension",
        "max" : "0"
      },
      {
        "id" : "Extension.url",
        "path" : "Extension.url",
        "fixedUri" : "http://gefyra.info/training/StructureDefinition/ISiKMDRRelevanzFormularExtension"
      },
      {
        "id" : "Extension.value[x]",
        "path" : "Extension.value[x]",
        "min" : 1,
        "type" : [
          {
            "code" : "Coding"
          }
        ],
        "binding" : {
          "strength" : "extensible",
          "valueSet" : "http://gefyra.info/training/ValueSet/ISiKMDRRelevanzFormularVS"
        }
      }
    ]
  }
}

```
