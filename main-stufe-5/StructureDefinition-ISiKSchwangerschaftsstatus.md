# ISiK Schwangerschaftsstatus - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK Schwangerschaftsstatus**

## Resource Profile: ISiK Schwangerschaftsstatus 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKSchwangerschaftsstatus | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKSchwangerschaftsstatus |

 
Schwangerschaftsstatus einer Patientin 

**Usages:**

* Examples for this Profile: [Observation/ISiKSchwangerschaftsstatusBeispiel](Observation-ISiKSchwangerschaftsstatusBeispiel.md)
* CapabilityStatements using this Profile: [CapabilityStatement für Rolle "ISiKCapabilityStatementGesundheitsstatusRolle"](CapabilityStatement-ISiKCapabilityStatementGesundheitsstatusRolle.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKSchwangerschaftsstatus)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKSchwangerschaftsstatus.csv), [Excel](StructureDefinition-ISiKSchwangerschaftsstatus.xlsx), [Schematron](StructureDefinition-ISiKSchwangerschaftsstatus.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKSchwangerschaftsstatus",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKSchwangerschaftsstatus",
  "version" : "0.1.0",
  "name" : "ISiKSchwangerschaftsstatus",
  "title" : "ISiK Schwangerschaftsstatus",
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
  "description" : "Schwangerschaftsstatus einer Patientin",
  "fhirVersion" : "4.0.1",
  "mapping" : [
    {
      "identity" : "workflow",
      "uri" : "http://hl7.org/fhir/workflow",
      "name" : "Workflow Pattern"
    },
    {
      "identity" : "sct-concept",
      "uri" : "http://snomed.info/conceptdomain",
      "name" : "SNOMED CT Concept Domain Binding"
    },
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
      "identity" : "w5",
      "uri" : "http://hl7.org/fhir/fivews",
      "name" : "FiveWs Pattern Mapping"
    },
    {
      "identity" : "sct-attr",
      "uri" : "http://snomed.org/attributebinding",
      "name" : "SNOMED CT Attribute Binding"
    }
  ],
  "kind" : "resource",
  "abstract" : false,
  "type" : "Observation",
  "baseDefinition" : "http://gefyra.info/training/StructureDefinition/ISiKLebensZustand",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Observation",
        "path" : "Observation"
      },
      {
        "id" : "Observation.code",
        "path" : "Observation.code",
        "patternCodeableConcept" : {
          "coding" : [
            {
              "system" : "http://loinc.org",
              "code" : "82810-3"
            }
          ]
        }
      },
      {
        "id" : "Observation.value[x]",
        "path" : "Observation.value[x]",
        "slicing" : {
          "discriminator" : [
            {
              "type" : "type",
              "path" : "$this"
            }
          ],
          "ordered" : false,
          "rules" : "open"
        }
      },
      {
        "id" : "Observation.value[x]:valueCodeableConcept",
        "path" : "Observation.value[x]",
        "sliceName" : "valueCodeableConcept",
        "comment" : "Motivation: Harmonisierung mit KBV (KBV_PR_Base_RelatedPerson)",
        "min" : 1,
        "max" : "1",
        "type" : [
          {
            "code" : "CodeableConcept"
          }
        ],
        "mustSupport" : true,
        "binding" : {
          "strength" : "required",
          "valueSet" : "http://gefyra.info/training/ValueSet/SchwangerschaftsstatusVS"
        }
      },
      {
        "id" : "Observation.hasMember",
        "path" : "Observation.hasMember",
        "short" : "Erwartetes Geburtsdatum",
        "comment" : "Eine Referenz auf die ErwartetesGeburtsdatum Observation",
        "max" : "1",
        "type" : [
          {
            "code" : "Reference",
            "targetProfile" : [
              "http://gefyra.info/training/StructureDefinition/ISiKSchwangerschaftErwarteterEntbindungstermin"
            ]
          }
        ],
        "mustSupport" : true
      },
      {
        "id" : "Observation.hasMember.reference",
        "path" : "Observation.hasMember.reference",
        "min" : 1,
        "mustSupport" : true
      }
    ]
  }
}

```
