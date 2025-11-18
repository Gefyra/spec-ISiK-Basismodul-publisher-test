# ExampleISiKMedikationsInformation4 - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ExampleISiKMedikationsInformation4**

## Example MedicationStatement: ExampleISiKMedikationsInformation4

Beispiel für Medikation/Einnahme zu jeder Mahlzeit (auch Zwischenmahlzeiten)



## Resource Content

```json
{
  "resourceType" : "MedicationStatement",
  "id" : "ExampleISiKMedikationsInformation4",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
    ]
  },
  "status" : "active",
  "medicationCodeableConcept" : {
    "coding" : [
      {
        "system" : "http://fhir.de/CodeSystem/ifa/pzn",
        "code" : "10557318",
        "display" : "Sevelamercarbonat AL 800 mg"
      }
    ]
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "context" : {
    "reference" : "Encounter/FachabteilungskontaktMinimal"
  },
  "effectivePeriod" : {
    "start" : "2024-01-22"
  },
  "dateAsserted" : "2024-02-16",
  "dosage" : [
    {
      "patientInstruction" : "auch zu Zwischenmahlzeiten",
      "timing" : {
        "repeat" : {
          "when" : ["C"]
        }
      },
      "doseAndRate" : [
        {
          "doseQuantity" : {
            "value" : 1,
            "unit" : "Tabl.",
            "system" : "http://unitsofmeasure.org",
            "code" : "1"
          }
        }
      ]
    }
  ]
}

```
