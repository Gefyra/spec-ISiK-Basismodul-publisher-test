# SZ2Patient - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **SZ2Patient**

## Example Patient: SZ2Patient

Profile: [ISiKPatient](StructureDefinition-ISiKPatient.md)

Friedlinde Musterfrau (official) Female, DoB: 1924-01-01 ( Krankenversichertennummer)

-------

| | |
| :--- | :--- |
| Active: | true |
| Other Id: | Medical record number/222222 |



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "SZ2Patient",
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
      "value" : "A222222222"
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
      "system" : "http://beispiel-krankenhaus.de/sid/Patienten",
      "value" : "222222"
    }
  ],
  "active" : true,
  "name" : [
    {
      "use" : "official",
      "family" : "Musterfrau",
      "given" : ["Friedlinde"]
    }
  ],
  "gender" : "female",
  "birthDate" : "1924-01-01"
}

```
