# ExampleISiKAMTSBewertung1 - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ExampleISiKAMTSBewertung1**

## Example RiskAssessment: ExampleISiKAMTSBewertung1

Beispiel für eine AMTS Risikobewertung.



## Resource Content

```json
{
  "resourceType" : "RiskAssessment",
  "id" : "ExampleISiKAMTSBewertung1",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKAMTSBewertung"
    ]
  },
  "status" : "final",
  "code" : {
    "text" : "AMTS Risikobewertung"
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "encounter" : {
    "reference" : "Encounter/Fachabteilungskontakt"
  },
  "occurrenceDateTime" : "2024-02-20T13:14:32+01:00",
  "condition" : {
    "reference" : "Condition/BehandlungsDiagnoseFreitext"
  },
  "reasonReference" : [
    {
      "reference" : "DocumentReference/AnamnesebogenScan123456"
    }
  ],
  "basis" : [
    {
      "reference" : "Observation/Koerpergewicht7777"
    }
  ],
  "prediction" : [
    {
      "outcome" : {
        "text" : "Niereninsuffizienz"
      },
      "qualitativeRisk" : {
        "coding" : [
          {
            "system" : "http://terminology.hl7.org/CodeSystem/risk-probability",
            "code" : "high"
          }
        ]
      }
    }
  ],
  "mitigation" : "Substitution der Stalevo Dauermedikation",
  "note" : [
    {
      "text" : "Abklärung in der Frühbesprechung am 21.02.2024"
    }
  ]
}

```
