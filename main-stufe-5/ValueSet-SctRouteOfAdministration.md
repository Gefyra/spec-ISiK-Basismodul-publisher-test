# SctRouteOfAdministration - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **SctRouteOfAdministration**

## ValueSet: SctRouteOfAdministration 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/ValueSet/SctRouteOfAdministration | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:SctRouteOfAdministration |

 
Enthaelt alle SNOMED CT Administrationsarten 

 **References** 

* [ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md)
* [ISiKMedikationsVerabreichung](StructureDefinition-ISiKMedikationsVerabreichung.md)
* [ISiKMedikationsVerordnung](StructureDefinition-ISiKMedikationsVerordnung.md)

### Logical Definition (CLD)

* Include codes from[`http://snomed.info/sct`](http://www.snomed.org/)version Not Stated (use latest from terminology server) where concept is-a 284009009 (Route of administration values)

 

### Expansion

Expansion from tx.fhir.org based on SNOMED CT International edition 01-Feb 2025

This value set expansion contains 161 concepts.

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
  "id" : "SctRouteOfAdministration",
  "url" : "http://gefyra.info/training/ValueSet/SctRouteOfAdministration",
  "version" : "0.1.0",
  "name" : "SctRouteOfAdministration",
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
  "description" : "Enthaelt alle SNOMED CT Administrationsarten",
  "compose" : {
    "include" : [
      {
        "system" : "http://snomed.info/sct",
        "filter" : [
          {
            "property" : "concept",
            "op" : "is-a",
            "value" : "284009009"
          }
        ]
      }
    ]
  }
}

```
