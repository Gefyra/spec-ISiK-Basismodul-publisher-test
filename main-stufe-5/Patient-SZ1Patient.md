# SZ1Patient - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **SZ1Patient**

## Example Patient: SZ1Patient

Profile: [ISiKPatient](StructureDefinition-ISiKPatient.md)

Töchterchen Musterfrau (official) Female, DoB: 2010-01-01 ( Krankenversichertennummer)

-------

| | |
| :--- | :--- |
| Active: | true |
| Other Id: | Medical record number/12345 |



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "SZ1Patient",
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
      "system" : "http://beispiel-krankenhaus.de/sid/Patienten",
      "value" : "12345"
    }
  ],
  "active" : true,
  "name" : [
    {
      "use" : "official",
      "family" : "Musterfrau",
      "given" : ["Töchterchen"]
    }
  ],
  "gender" : "female",
  "birthDate" : "2010-01-01"
}

```
