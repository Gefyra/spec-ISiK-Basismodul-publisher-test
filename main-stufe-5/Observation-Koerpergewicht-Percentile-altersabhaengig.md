# Koerpergewicht-Percentile-altersabhaengig - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Koerpergewicht-Percentile-altersabhaengig**

## Example Observation: Koerpergewicht-Percentile-altersabhaengig

Profile: [SD MII ICU Koerpergewicht Percentil Altersabhaengig](StructureDefinition-sd-mii-icu-koerpergewicht-percentil-altersabhaengig.md)

**status**: Final

**category**: Vital Signs

**code**: Body weight [Percentile] Per age

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**effective**: 2019-12-23 09:30:10+0100 --> 2019-12-23 10:30:10+0100

**value**: 50 percent(Details: UCUM code% = '%')



## Resource Content

```json
{
  "resourceType" : "Observation",
  "id" : "Koerpergewicht-Percentile-altersabhaengig",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpergewicht-percentil-altersabhaengig"
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
        "code" : "8336-0",
        "display" : "Body weight [Percentile] Per age"
      },
      {
        "system" : "http://snomed.info/sct",
        "code" : "1153592008",
        "display" : "Weight for age percentile"
      }
    ]
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "effectivePeriod" : {
    "start" : "2019-12-23T09:30:10+01:00",
    "end" : "2019-12-23T10:30:10+01:00"
  },
  "valueQuantity" : {
    "value" : 50,
    "unit" : "percent",
    "system" : "http://unitsofmeasure.org",
    "code" : "%"
  }
}

```
