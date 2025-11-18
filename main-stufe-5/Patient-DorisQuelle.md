# DorisQuelle - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **DorisQuelle**

## Example Patient: DorisQuelle

Profile: [ISiKPatient](StructureDefinition-ISiKPatient.md)

Doris Duplikat (official) Female, DoB: 1964-08-12 ( Krankenversichertennummer)

-------

| | |
| :--- | :--- |
| Active: | false |
| Other Id: | Medical record number/654321 |



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "DorisQuelle",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKPatient"
    ]
  },
  "identifier" : [
    {
      "type" : {
        "coding" : [
          {
            "system" : "http://fhir.de/CodeSystem/identifier-type-de-basis",
            "code" : "KVZ10"
          }
        ]
      },
      "system" : "http://fhir.de/sid/gkv/kvid-10",
      "value" : "A123456789"
    },
    {
      "type" : {
        "coding" : [
          {
            "system" : "http://terminology.hl7.org/CodeSystem/v2-0203",
            "code" : "MR"
          }
        ]
      },
      "system" : "https://fhir.krankenhaus.example/sid/PID",
      "value" : "654321"
    }
  ],
  "active" : false,
  "name" : [
    {
      "use" : "official",
      "family" : "Duplikat",
      "given" : ["Doris"]
    }
  ],
  "gender" : "female",
  "birthDate" : "1964-08-12"
}

```
