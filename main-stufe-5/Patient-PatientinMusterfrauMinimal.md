# PatientinMusterfrauMinimal - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **PatientinMusterfrauMinimal**

## Example Patient: PatientinMusterfrauMinimal

Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Medical record number)

-------



## Resource Content

```json
{
  "resourceType" : "Patient",
  "id" : "PatientinMusterfrauMinimal",
  "identifier" : [
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
      "value" : "TestPID"
    }
  ],
  "name" : [
    {
      "use" : "official",
      "family" : "Fürstin von Musterfrau",
      "given" : ["Erika"],
      "prefix" : ["Dr."]
    }
  ],
  "gender" : "female",
  "birthDate" : "1964-08-12"
}

```
