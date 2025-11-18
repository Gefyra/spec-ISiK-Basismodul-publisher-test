# ISiKLoincCoding - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKLoincCoding**

## Data Type Profile: ISiKLoincCoding 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKLoincCoding | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKLoincCoding |

 
Data Type profile for LOINC Codings in ISiK 

**Usages:**

* Use this DataType Profile: [ISiKLebensZustand](StructureDefinition-ISiKLebensZustand.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKLoincCoding)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKLoincCoding.csv), [Excel](StructureDefinition-ISiKLoincCoding.xlsx), [Schematron](StructureDefinition-ISiKLoincCoding.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKLoincCoding",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKLoincCoding",
  "version" : "0.1.0",
  "name" : "ISiKLoincCoding",
  "title" : "ISiKLoincCoding",
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
  "description" : "Data Type profile for LOINC Codings in ISiK",
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
        "patternUri" : "http://loinc.org"
      },
      {
        "id" : "Coding.version",
        "path" : "Coding.version",
        "short" : "Version",
        "comment" : "Motivation MS: Version des kodierten Wertes.",
        "mustSupport" : true
      }
    ]
  }
}

```
