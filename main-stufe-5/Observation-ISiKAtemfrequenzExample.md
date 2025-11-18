# ISiKAtemfrequenzExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKAtemfrequenzExample**

## Example Observation: ISiKAtemfrequenzExample

Profile: [ISiKAtemfrequenz](StructureDefinition-ISiKAtemfrequenz.md)

**status**: Final

**category**: Vital Signs

**code**: Atemfrequenz

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**effective**: 2019-07-02

**performer**: [Practitioner Walter Arzt(official)](Practitioner-PractitionerWalterArzt.md)

**value**: 26 Atemzüge pro Minute(Details: UCUM code/min = '/min')



## Resource Content

```json
{
  "resourceType" : "Observation",
  "id" : "ISiKAtemfrequenzExample",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKAtemfrequenz"
    ]
  },
  "status" : "final",
  "category" : [
    {
      "coding" : [
        {
          "system" : "http://terminology.hl7.org/CodeSystem/observation-category",
          "code" : "vital-signs",
          "display" : "Vital Signs"
        }
      ]
    }
  ],
  "code" : {
    "coding" : [
      {
        "system" : "http://snomed.info/sct",
        "code" : "86290005",
        "display" : "Respiratory rate"
      },
      {
        "system" : "urn:iso:std:iso:11073:10101",
        "code" : "151562",
        "display" : "MDC_RESP_RATE"
      },
      {
        "system" : "http://loinc.org",
        "code" : "9279-1",
        "display" : "Respiratory rate"
      }
    ],
    "text" : "Atemfrequenz"
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "effectiveDateTime" : "2019-07-02",
  "performer" : [
    {
      "reference" : "Practitioner/PractitionerWalterArzt"
    }
  ],
  "valueQuantity" : {
    "value" : 26,
    "unit" : "Atemzüge pro Minute",
    "system" : "http://unitsofmeasure.org",
    "code" : "/min"
  }
}

```
