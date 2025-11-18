# ISiKATCCoding - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKATCCoding**

## Data Type Profile: ISiKATCCoding 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/StructureDefinition/ISiKATCCoding | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKATCCoding |

 
Data Type profile for ATC Codings in ISiK 

**Usages:**

* Use this DataType Profile: [ISiKMedikament](StructureDefinition-ISiKMedikament.md), [ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md), [ISiKMedikationsVerabreichung](StructureDefinition-ISiKMedikationsVerabreichung.md) and [ISiKMedikationsVerordnung](StructureDefinition-ISiKMedikationsVerordnung.md)

You can also check for [usages in the FHIR IG Statistics](https://packages2.fhir.org/xig/info.gefyra.training|current/StructureDefinition/ISiKATCCoding)

### Formal Views of Profile Content

 [Description of Profiles, Differentials, Snapshots and how the different presentations work](http://build.fhir.org/ig/FHIR/ig-guidance/readingIgs.html#structure-definitions). 

 

Other representations of profile: [CSV](StructureDefinition-ISiKATCCoding.csv), [Excel](StructureDefinition-ISiKATCCoding.xlsx), [Schematron](StructureDefinition-ISiKATCCoding.sch) 



## Resource Content

```json
{
  "resourceType" : "StructureDefinition",
  "id" : "ISiKATCCoding",
  "url" : "http://gefyra.info/training/StructureDefinition/ISiKATCCoding",
  "version" : "0.1.0",
  "name" : "ISiKATCCoding",
  "title" : "ISiKATCCoding",
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
  "description" : "Data Type profile for ATC Codings in ISiK",
  "fhirVersion" : "4.0.1",
  "kind" : "complex-type",
  "abstract" : false,
  "type" : "Coding",
  "baseDefinition" : "http://fhir.de/StructureDefinition/CodingATC",
  "derivation" : "constraint",
  "differential" : {
    "element" : [
      {
        "id" : "Coding",
        "path" : "Coding"
      },
      {
        "id" : "Coding.system",
        "path" : "Coding.system",
        "short" : "System",
        "comment" : "Motivation MS: URL des CodeSystems des kodierten Wertes.",
        "mustSupport" : true
      },
      {
        "id" : "Coding.code",
        "path" : "Coding.code",
        "short" : "Code",
        "comment" : "Motivation MS: Kodierter Wert aus einem CodeSystem.",
        "mustSupport" : true
      },
      {
        "id" : "Coding.display",
        "path" : "Coding.display",
        "short" : "Display",
        "comment" : "Motivation MS: Anzeigename des kodierten Wertes.",
        "mustSupport" : true
      }
    ]
  }
}

```
