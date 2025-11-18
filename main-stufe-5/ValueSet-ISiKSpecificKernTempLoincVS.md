# ISiK Specific Kerntemperatur LOINC ValueSet - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK Specific Kerntemperatur LOINC ValueSet**

## ValueSet: ISiK Specific Kerntemperatur LOINC ValueSet 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/ValueSet/ISiKSpecificKernTempLoincVS | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKSpecificKernTempLoincVS |

 
ValueSet der spezifischen Körperkerntemperatur LOINC Konzepte 

 **References** 

* [ISiKKoerperkerntemperatur](StructureDefinition-ISiKKoerperkerntemperatur.md)

### Logical Definition (CLD)

 

### Expansion

Expansion from tx.fhir.org based on Loinc v2.81

This value set contains 8 concepts

-------

 Explanation of the columns that may appear on this page: 

| | |
| :--- | :--- |
| Level | A few code lists that FHIR defines are hierarchical - each code is assigned a level. In this scheme, some codes are under other codes, and imply that the code they are under also applies |
| System | The source of the definition of the code (when the value set draws in codes defined elsewhere) |
| Code | The code (used as the code in the resource instance) |
| Display | The display (used in the*display*element of a[Coding](http://hl7.org/fhir/R4/datatypes.html#Coding)). If there is no display, implementers should not simply display the code, but map the concept into their application |
| Definition | An explanation of the meaning of the concept |
| Comments | Additional notes about how to use the code |



## Resource Content

```json
{
  "resourceType" : "ValueSet",
  "id" : "ISiKSpecificKernTempLoincVS",
  "url" : "http://gefyra.info/training/ValueSet/ISiKSpecificKernTempLoincVS",
  "version" : "0.1.0",
  "name" : "ISiKSpecificKernTempLoincVS",
  "title" : "ISiK Specific Kerntemperatur LOINC ValueSet",
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
  "description" : "ValueSet der spezifischen Körperkerntemperatur LOINC Konzepte",
  "compose" : {
    "include" : [
      {
        "system" : "http://loinc.org",
        "concept" : [
          {
            "code" : "8328-7",
            "display" : "Axillary temperature"
          },
          {
            "code" : "60834-9",
            "display" : "Blood temperature"
          },
          {
            "code" : "8334-5",
            "display" : "Body temperature - Urinary bladder"
          },
          {
            "code" : "104063-3",
            "display" : "Body temperature - Groin"
          },
          {
            "code" : "8331-1",
            "display" : "Oral temperature"
          },
          {
            "code" : "8332-9",
            "display" : "Rectal temperature"
          },
          {
            "code" : "60836-4",
            "display" : "Esophageal temperature"
          },
          {
            "code" : "8333-7",
            "display" : "Tympanic membrane temperature"
          }
        ]
      }
    ]
  }
}

```
