# VS MII ICU Method Observation Blutdruck - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **VS MII ICU Method Observation Blutdruck**

## ValueSet: VS MII ICU Method Observation Blutdruck 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/ValueSet/vs-mii-icu-method-observation-blutdruck | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:VS_MII_ICU_Method_Observation_Blutdruck |

 
Dieses ValueSet enthält Codes zur Angabe, ob ein Blutdruck invasiv oder nicht-invasiv gemessen ist. 

 **References** 

* [SD MII ICU Sonstige pulsatile Druecke Generisch](StructureDefinition-sd-mii-icu-sonstige-pulsatile-druecke-generisch.md)

### Logical Definition (CLD)

 

### Expansion

Expansion from tx.fhir.org based on SNOMED CT International edition 01-Feb 2025

This value set contains 2 concepts

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
  "id" : "vs-mii-icu-method-observation-blutdruck",
  "url" : "http://gefyra.info/training/ValueSet/vs-mii-icu-method-observation-blutdruck",
  "version" : "0.1.0",
  "name" : "VS_MII_ICU_Method_Observation_Blutdruck",
  "title" : "VS MII ICU Method Observation Blutdruck",
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
  "description" : "Dieses ValueSet enthält Codes zur Angabe, ob ein Blutdruck invasiv oder nicht-invasiv gemessen ist. ",
  "compose" : {
    "include" : [
      {
        "system" : "http://snomed.info/sct",
        "concept" : [
          {
            "code" : "10179008"
          },
          {
            "code" : "22762002"
          }
        ]
      }
    ]
  }
}

```
