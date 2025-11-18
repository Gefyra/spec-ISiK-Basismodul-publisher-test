# ISiKKopfumfangMaxExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKKopfumfangMaxExample**

## Example Observation: ISiKKopfumfangMaxExample

Profile: [ISiKKopfumfang](StructureDefinition-ISiKKopfumfang.md)

**status**: Final

**category**: Vital Signs

**code**: Kopfumfang - Pädiatrische Verlaufskontrolle

**subject**: [Anna Müller (official) Female, DoB: 1957-08-12 ( Krankenversichertennummer)](Patient-PatientinNormal.md)

**effective**: 2024-01-15 11:00:00+0100

**performer**: [Practitioner Walter Arzt(official)](Practitioner-PractitionerWalterArzt.md)

**value**: 60.5 Centimeter(Details: UCUM codecm = 'cm')

**interpretation**: Normal

**note**: 

> 

Kopfumfang im normalen Bereich für Alter und Geschlecht - Wachstumsperzentile P50


**bodySite**: Head structure

**method**: Action - using tape measure



## Resource Content

```json
{
  "resourceType" : "Observation",
  "id" : "ISiKKopfumfangMaxExample",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKKopfumfang"
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
        "code" : "363812007",
        "display" : "Head circumference"
      },
      {
        "system" : "urn:iso:std:iso:11073:10101",
        "code" : "153856",
        "display" : "MDC_CIRCUM_HEAD"
      },
      {
        "system" : "http://loinc.org",
        "code" : "9843-4",
        "display" : "Head Occipital-frontal circumference"
      }
    ],
    "text" : "Kopfumfang - Pädiatrische Verlaufskontrolle"
  },
  "subject" : {
    "reference" : "Patient/PatientinNormal"
  },
  "effectiveDateTime" : "2024-01-15T11:00:00+01:00",
  "performer" : [
    {
      "reference" : "Practitioner/PractitionerWalterArzt"
    }
  ],
  "valueQuantity" : {
    "value" : 60.5,
    "unit" : "Centimeter",
    "system" : "http://unitsofmeasure.org",
    "code" : "cm"
  },
  "interpretation" : [
    {
      "coding" : [
        {
          "system" : "http://terminology.hl7.org/CodeSystem/v3-ObservationInterpretation",
          "code" : "N",
          "display" : "Normal"
        }
      ]
    }
  ],
  "note" : [
    {
      "text" : "Kopfumfang im normalen Bereich für Alter und Geschlecht - Wachstumsperzentile P50"
    }
  ],
  "bodySite" : {
    "coding" : [
      {
        "system" : "http://snomed.info/sct",
        "code" : "69536005",
        "display" : "Head structure"
      }
    ]
  },
  "method" : {
    "coding" : [
      {
        "system" : "http://snomed.info/sct",
        "code" : "129264002",
        "display" : "Action - using tape measure"
      }
    ]
  }
}

```
