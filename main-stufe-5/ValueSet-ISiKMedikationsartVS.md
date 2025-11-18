# ISiKMedikationsartVS - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKMedikationsartVS**

## ValueSet: ISiKMedikationsartVS 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/ValueSet/ISiKMedikationsartVS | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKMedikationsartVS |

 
ISiK Therapiearten für Medikation 

 **References** 

* [ISiK Medikationsart](StructureDefinition-ExtensionISiKMedikationsart.md)

### Logical Definition (CLD)

* Include all codes defined in [`http://gefyra.info/training/CodeSystem/ISiKMedikationsartCS`](CodeSystem-ISiKMedikationsartCS.md)version 📦0.1.0

 

### Expansion

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
  "id" : "ISiKMedikationsartVS",
  "url" : "http://gefyra.info/training/ValueSet/ISiKMedikationsartVS",
  "version" : "0.1.0",
  "name" : "ISiKMedikationsartVS",
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
  "description" : "ISiK Therapiearten für Medikation",
  "compose" : {
    "include" : [
      {
        "system" : "http://gefyra.info/training/CodeSystem/ISiKMedikationsartCS"
      }
    ]
  }
}

```
