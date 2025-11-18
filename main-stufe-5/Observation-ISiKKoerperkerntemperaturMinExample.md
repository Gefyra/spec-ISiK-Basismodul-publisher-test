# ISiKKoerperkerntemperaturMinExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKKoerperkerntemperaturMinExample**

## Example Observation: ISiKKoerperkerntemperaturMinExample

Profile: [ISiKKoerperkerntemperatur](StructureDefinition-ISiKKoerperkerntemperatur.md)

**status**: Final

**category**: Vital Signs

**code**: Body temperature - Core

**subject**: [Anna Müller (official) Female, DoB: 1957-08-12 ( Medical record number)](Patient-PatientinMinimal.md)

**effective**: 2024-01-15

**value**: 34.5 °C(Details: UCUM codeCel = 'Cel')



## Resource Content

```json
{
  "resourceType" : "Observation",
  "id" : "ISiKKoerperkerntemperaturMinExample",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKKoerperkerntemperatur"
    ]
  },
  "status" : "final",
  "category" : [
    {
      "coding" : [
        {
          "system" : "http://terminology.hl7.org/CodeSystem/observation-category",
          "code" : "vital-signs"
        }
      ]
    }
  ],
  "code" : {
    "coding" : [
      {
        "system" : "http://loinc.org",
        "code" : "8329-5",
        "display" : "Body temperature - Core"
      },
      {
        "system" : "http://loinc.org",
        "code" : "8310-5"
      }
    ]
  },
  "subject" : {
    "reference" : "Patient/PatientinMinimal"
  },
  "effectiveDateTime" : "2024-01-15",
  "valueQuantity" : {
    "value" : 34.5,
    "unit" : "°C",
    "system" : "http://unitsofmeasure.org",
    "code" : "Cel"
  }
}

```
