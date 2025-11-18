# Rechtsatrialer-Druck - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **Rechtsatrialer-Druck**

## Example Observation: Rechtsatrialer-Druck

Profile: [SD MII ICU Rechtsatrialer Druck](StructureDefinition-sd-mii-icu-rechtsatrialer-druck.md)

**status**: Final

**category**: Vital Signs

**code**: Right atrial pressure

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**effective**: 2019-12-23 09:30:10+0100

**bodySite**: Right atrial structure

> **component****code**:Right atrial pressure Systolic**value**: 5 millimeter Mercury column(Details: UCUM codemm[Hg] = 'mm[Hg]')

> **component****code**:Right atrial Intrachamber mean pressure**value**: 4 millimeter Mercury column(Details: UCUM codemm[Hg] = 'mm[Hg]')

> **component****code**:Right atrial pressure Diastolic**value**: 3 millimeter Mercury column(Details: UCUM codemm[Hg] = 'mm[Hg]')



## Resource Content

```json
{
  "resourceType" : "Observation",
  "id" : "Rechtsatrialer-Druck",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/sd-mii-icu-rechtsatrialer-druck"
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
        "system" : "http://snomed.info/sct",
        "code" : "276755008",
        "display" : "Right atrial pressure"
      },
      {
        "system" : "http://loinc.org",
        "code" : "60996-6",
        "display" : "Right atrial pressure"
      },
      {
        "system" : "urn:iso:std:iso:11073:10101",
        "code" : "150068",
        "display" : "MDC_PRESS_BLD_ATR_RIGHT"
      },
      {
        "system" : "http://snomed.info/sct",
        "code" : "75367002"
      }
    ]
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "effectiveDateTime" : "2019-12-23T09:30:10+01:00",
  "bodySite" : {
    "coding" : [
      {
        "system" : "http://snomed.info/sct",
        "code" : "73829009",
        "display" : "Right atrial structure"
      }
    ]
  },
  "component" : [
    {
      "code" : {
        "coding" : [
          {
            "system" : "http://loinc.org",
            "code" : "8480-6"
          },
          {
            "system" : "http://loinc.org",
            "code" : "60998-2",
            "display" : "Right atrial pressure Systolic"
          },
          {
            "system" : "urn:iso:std:iso:11073:10101",
            "code" : "150069",
            "display" : "Systolic right atrial pressure"
          }
        ]
      },
      "valueQuantity" : {
        "value" : 5,
        "unit" : "millimeter Mercury column",
        "system" : "http://unitsofmeasure.org",
        "code" : "mm[Hg]"
      }
    },
    {
      "code" : {
        "coding" : [
          {
            "system" : "http://loinc.org",
            "code" : "8478-0"
          },
          {
            "system" : "http://loinc.org",
            "code" : "8400-4",
            "display" : "Right atrial Intrachamber mean pressure"
          },
          {
            "system" : "http://snomed.info/sct",
            "code" : "276775004",
            "display" : "Mean right atrial pressure"
          },
          {
            "system" : "urn:iso:std:iso:11073:10101",
            "code" : "150071",
            "display" : "Mean right atrial pressure"
          }
        ]
      },
      "valueQuantity" : {
        "value" : 4,
        "unit" : "millimeter Mercury column",
        "system" : "http://unitsofmeasure.org",
        "code" : "mm[Hg]"
      }
    },
    {
      "code" : {
        "coding" : [
          {
            "system" : "http://loinc.org",
            "code" : "8462-4"
          },
          {
            "system" : "http://loinc.org",
            "code" : "60997-4",
            "display" : "Right atrial pressure Diastolic"
          },
          {
            "system" : "urn:iso:std:iso:11073:10101",
            "code" : "150070",
            "display" : "Diastolic right atrial pressure"
          }
        ]
      },
      "valueQuantity" : {
        "value" : 3,
        "unit" : "millimeter Mercury column",
        "system" : "http://unitsofmeasure.org",
        "code" : "mm[Hg]"
      }
    }
  ]
}

```
