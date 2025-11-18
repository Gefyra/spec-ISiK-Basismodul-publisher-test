# Koerpertemperatur-Achsel - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Koerpertemperatur-Achsel**

## Example Observation: Koerpertemperatur-Achsel

Profile: [SD MII ICU Koerpertemperatur Achsel](StructureDefinition-sd-mii-icu-koerpertemperatur-achsel.md)

**status**: Final

**category**: Vital Signs

**code**: Axillary temperature

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**effective**: 2019-12-23 09:30:10+0100 --> 2019-12-23 10:30:10+0100

**value**: 37 degree Celsius(Details: UCUM codeCel = 'Cel')

**bodySite**: Axillary region structure (body structure)



## Resource Content

```json
{
  "resourceType" : "Observation",
  "id" : "Koerpertemperatur-Achsel",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/sd-mii-icu-koerpertemperatur-achsel"
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
        "code" : "8328-7",
        "display" : "Axillary temperature"
      },
      {
        "system" : "http://snomed.info/sct",
        "code" : "415882003",
        "display" : "Estimated core body temperature measured in axillary region"
      },
      {
        "system" : "urn:iso:std:iso:11073:10101",
        "code" : "188452",
        "display" : "MDC_TEMP_AXILLA"
      },
      {
        "system" : "http://loinc.org",
        "code" : "8310-5"
      },
      {
        "system" : "http://loinc.org",
        "code" : "8329-5"
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
    "value" : 37,
    "unit" : "degree Celsius",
    "system" : "http://unitsofmeasure.org",
    "code" : "Cel"
  },
  "bodySite" : {
    "coding" : [
      {
        "system" : "http://snomed.info/sct",
        "code" : "91470000",
        "display" : "Axillary region structure (body structure)"
      }
    ]
  }
}

```
