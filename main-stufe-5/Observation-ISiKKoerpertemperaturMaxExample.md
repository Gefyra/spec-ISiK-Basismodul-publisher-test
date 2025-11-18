# ISiKKoerpertemperaturMaxExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKKoerpertemperaturMaxExample**

## Example Observation: ISiKKoerpertemperaturMaxExample

Profile: [ISiKKoerpertemperatur](StructureDefinition-ISiKKoerpertemperatur.md)

**status**: Final

**category**: Vital Signs

**code**: Körpertemperatur - Fiebermessung

**subject**: [Anna Müller (official) Female, DoB: 1957-08-12 ( Krankenversichertennummer)](Patient-PatientinNormal.md)

**effective**: 2024-01-15 20:15:00+0100

**performer**: [Practitioner Walter Arzt(official)](Practitioner-PractitionerWalterArzt.md)

**value**: 41.2 °C(Details: UCUM codeCel = 'Cel')

**interpretation**: High

**note**: 

> 

Hyperthermie bei schwerer Sepsis - kontinuierliches Monitoring erforderlich


**bodySite**: Tongue structure

**method**: Digital thermometry

**device**: [Device: status = active](Device-ExampleDevice.md)



## Resource Content

```json
{
  "resourceType" : "Observation",
  "id" : "ISiKKoerpertemperaturMaxExample",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKKoerpertemperatur"
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
        "code" : "386725007",
        "display" : "Body temperature"
      },
      {
        "system" : "urn:iso:std:iso:11073:10101",
        "code" : "150364",
        "display" : "MDC_TEMP_BODY"
      },
      {
        "system" : "http://loinc.org",
        "code" : "8310-5",
        "display" : "Body temperature"
      }
    ],
    "text" : "Körpertemperatur - Fiebermessung"
  },
  "subject" : {
    "reference" : "Patient/PatientinNormal"
  },
  "effectiveDateTime" : "2024-01-15T20:15:00+01:00",
  "performer" : [
    {
      "reference" : "Practitioner/PractitionerWalterArzt"
    }
  ],
  "valueQuantity" : {
    "value" : 41.2,
    "unit" : "°C",
    "system" : "http://unitsofmeasure.org",
    "code" : "Cel"
  },
  "interpretation" : [
    {
      "coding" : [
        {
          "system" : "http://terminology.hl7.org/CodeSystem/v3-ObservationInterpretation",
          "code" : "H",
          "display" : "High"
        }
      ]
    }
  ],
  "note" : [
    {
      "text" : "Hyperthermie bei schwerer Sepsis - kontinuierliches Monitoring erforderlich"
    }
  ],
  "bodySite" : {
    "coding" : [
      {
        "system" : "http://snomed.info/sct",
        "code" : "21974007",
        "display" : "Tongue structure"
      }
    ]
  },
  "method" : {
    "coding" : [
      {
        "system" : "http://snomed.info/sct",
        "code" : "448169003",
        "display" : "Digital thermometry"
      }
    ]
  },
  "device" : {
    "reference" : "Device/ExampleDevice"
  }
}

```
