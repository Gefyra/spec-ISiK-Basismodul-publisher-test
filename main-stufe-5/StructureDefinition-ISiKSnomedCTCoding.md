# ISiKSnomedCTCoding - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKSnomedCTCoding**

## Data Type Profile: ISiKSnomedCTCoding 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKSnomedCTCoding | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKSnomedCTCoding |

 
Data Type profile for Snomed-CT Codings in ISiK 

**Usages:**

* Use this DataType Profile: [ISiKAllergieUnvertraeglichkeit](StructureDefinition-ISiKAllergieUnvertraeglichkeit.md), [ISiKDiagnose](StructureDefinition-ISiKDiagnose.md), [ISiKLebensZustand](StructureDefinition-ISiKLebensZustand.md), [ISiKMedikament](StructureDefinition-ISiKMedikament.md)...Show 4 more,[ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md),[ISiKMedikationsVerabreichung](StructureDefinition-ISiKMedikationsVerabreichung.md),[ISiKMedikationsVerordnung](StructureDefinition-ISiKMedikationsVerordnung.md)and[ISiKProzedur](StructureDefinition-ISiKProzedur.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKSnomedCTCoding)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKSnomedCTCoding.csv), [Excel](StructureDefinition-ISiKSnomedCTCoding.xlsx), [Schematron](StructureDefinition-ISiKSnomedCTCoding.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKSnomedCTCoding",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKSnomedCTCoding",
  "version" : "0.1.0",
  "name" : "ISiKSnomedCTCoding",
  "title" : "ISiKSnomedCTCoding",
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
  "description" : "Data Type profile for Snomed-CT Codings in ISiK",
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
      "identity" : "orim",
      "uri" : "http://hl7.org/orim",
      "name" : "Ontological RIM Mapping"
    }
  ],
  "kind" : "complex-type",
  "abstract" : false,
  "type" : "Coding",
  "baseDefinition" : "http://gefyra.info/training/StructureDefinition/ISiKCoding",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Coding.system",
        "path" : "Coding.system",
        "patternUri" : "http://snomed.info/sct"
      },
      {
        "id" : "Coding.version",
        "path" : "Coding.version",
        "short" : "Version",
        "comment" : "Motivation MS: Version des kodierten Wertes.",
        "constraint" : [
          {
            "key" : "sct-version-de",
            "severity" : "error",
            "human" : "Die SnomedCT-Version muss sich auf eine konkrete deutsche Edition beziehen",
            "expression" : "startsWith('http://snomed.info/sct/11000274103/')",
            "source" : "http://gefyra.info/training/StructureDefinition/ISiKSnomedCTCoding"
          }
        ],
        "mustSupport" : true
      }
    ]
  }
}

```
