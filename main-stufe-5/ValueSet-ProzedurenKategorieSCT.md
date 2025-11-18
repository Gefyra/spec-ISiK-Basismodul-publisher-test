# ProzedurenKategorieSCT - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ProzedurenKategorieSCT**

## ValueSet: ProzedurenKategorieSCT 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/ValueSet/ProzedurenKategorieSCT | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ProzedurenKategorieSCT |

 
Enthaelt alle SNOMED Codes für ein Mapping der OPS Klassentitel 

 **References** 

This value set is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)

### Logical Definition (CLD)

 

### Expansion

Expansion from tx.fhir.org based on SNOMED CT International edition 01-Feb 2025

This value set contains 6 concepts

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
  "id" : "ProzedurenKategorieSCT",
  "url" : "http://gefyra.info/training/ValueSet/ProzedurenKategorieSCT",
  "version" : "0.1.0",
  "name" : "ProzedurenKategorieSCT",
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
  "description" : "Enthaelt alle SNOMED Codes für ein Mapping der OPS Klassentitel",
  "compose" : {
    "include" : [
      {
        "system" : "http://snomed.info/sct",
        "concept" : [
          {
            "code" : "165197003",
            "display" : "Diagnostic assessment"
          },
          {
            "code" : "363679005",
            "display" : "Imaging"
          },
          {
            "code" : "387713003",
            "display" : "Surgical procedure"
          },
          {
            "code" : "18629005",
            "display" : "Administration of medicine"
          },
          {
            "code" : "277132007",
            "display" : "Therapeutic procedure"
          },
          {
            "code" : "394841004",
            "display" : "Other category"
          }
        ]
      }
    ]
  }
}

```
