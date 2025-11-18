# ISiK Kerntemperatur SnomedCT ValueSet - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK Kerntemperatur SnomedCT ValueSet**

## ValueSet: ISiK Kerntemperatur SnomedCT ValueSet 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/ValueSet/ISiKKernTempSctVS | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKKernTempSctVS |

 
ValueSet der Körperkerntemperatur SnomedCT Konzepte 

 **References** 

* [ISiKKoerperkerntemperatur](StructureDefinition-ISiKKoerperkerntemperatur.md)

### Logical Definition (CLD)

 

### Expansion

Expansion from tx.fhir.org based on SNOMED CT International edition 01-Feb 2025

This value set contains 10 concepts

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
  "id" : "ISiKKernTempSctVS",
  "url" : "http://gefyra.info/training/ValueSet/ISiKKernTempSctVS",
  "version" : "0.1.0",
  "name" : "ISiKKernTempSctVS",
  "title" : "ISiK  Kerntemperatur SnomedCT ValueSet",
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
  "description" : "ValueSet der Körperkerntemperatur SnomedCT Konzepte",
  "compose" : {
    "include" : [
      {
        "system" : "http://snomed.info/sct",
        "concept" : [
          {
            "code" : "276885007",
            "display" : "Core body temperature"
          },
          {
            "code" : "415882003",
            "display" : "Estimated core body temperature measured in axillary region"
          },
          {
            "code" : "1222808002",
            "display" : "Core body temperature measured in blood"
          },
          {
            "code" : "698832009",
            "display" : "Core body temperature measured at urinary bladder"
          },
          {
            "code" : "415929009",
            "display" : "Estimated core body temperature measured in inguinal region"
          },
          {
            "code" : "415945006",
            "display" : "Estimated core body temperature measured in sublingual space"
          },
          {
            "code" : "307047009",
            "display" : "Core body temperature measured in rectum"
          },
          {
            "code" : "431598003",
            "display" : "Core body temperature measured in esophagus"
          },
          {
            "code" : "415974002",
            "display" : "Core body temperature measured at tympanic membrane"
          },
          {
            "code" : "364246006",
            "display" : "Core body temperature measured vaginally"
          }
        ]
      }
    ]
  }
}

```
