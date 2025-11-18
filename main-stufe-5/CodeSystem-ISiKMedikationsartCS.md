# ISiK Medikationsart - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiK Medikationsart**

## CodeSystem: ISiK Medikationsart 

| | |
| :--- | :--- |
| *Official URL*:http://gefyra.info/training/CodeSystem/ISiKMedikationsartCS | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:ISiKMedikationsartCS |

 
ISiK Therapiearten für Medikation 

 This Code system is referenced in the content logical definition of the following value sets: 

* [ISiKMedikationsartVS](ValueSet-ISiKMedikationsartVS.md)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "ISiKMedikationsartCS",
  "url" : "http://gefyra.info/training/CodeSystem/ISiKMedikationsartCS",
  "version" : "0.1.0",
  "name" : "ISiKMedikationsartCS",
  "title" : "ISiK Medikationsart",
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
  "caseSensitive" : true,
  "content" : "complete",
  "count" : 2,
  "concept" : [
    {
      "code" : "akut",
      "display" : "Akutmedikation"
    },
    {
      "code" : "dauer",
      "display" : "Dauermedikation"
    }
  ]
}

```
