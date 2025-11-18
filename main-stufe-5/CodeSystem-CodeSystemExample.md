# CodeSystemExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **CodeSystemExample**

## CodeSystem: CodeSystemExample 

| | |
| :--- | :--- |
| *Official URL*:http://example.org/fhir/CodeSystem/TestKatalog | *Version*:0.1.0 |
| Active as of 2025-10-23 | *Computable Name*:TestKatalog |

 This Code system is referenced in the content logical definition of the following value sets: 

* This CodeSystem is not used here; it may be used elsewhere (e.g. specifications and/or implementations that use this content)



## Resource Content

```json
{
  "resourceType" : "CodeSystem",
  "id" : "CodeSystemExample",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKCodeSystem"
    ]
  },
  "url" : "http://example.org/fhir/CodeSystem/TestKatalog",
  "version" : "0.1.0",
  "name" : "TestKatalog",
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
  "caseSensitive" : true,
  "content" : "complete",
  "concept" : [
    {
      "code" : "test",
      "display" : "Test",
      "definition" : "Dies ist ein Test-Code"
    }
  ]
}

```
