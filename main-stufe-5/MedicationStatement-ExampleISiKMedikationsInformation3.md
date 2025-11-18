# ExampleISiKMedikationsInformation3 - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ExampleISiKMedikationsInformation3**

## Example MedicationStatement: ExampleISiKMedikationsInformation3

Profile: [ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md)

**status**: Active

**medication**: [Medication](Medication-ExampleISiKMedikament8.md)

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**context**: [Encounter: identifier = Visit number; status = unknown; class = inpatient encounter (ActCode#IMP); type = Operation,Abteilungskontakt; serviceType = Innere Medizin; period = 2022-05-03 --> 2022-05-05](Encounter-FachabteilungskontaktMinimal.md)

**effective**: 2024-01-22 --> 2024-02-26

**dateAsserted**: 2024-01-17

> **dosage****timing**: Count 6 times, Duration 6weeks , Once per 1 week

### DoseAndRates

| | |
| :--- | :--- |
| - | **Dose[x]** |
| * | 500 ml Infusionslösung(Details: UCUM codemL = 'mL') |




## Resource Content

```json
{
  "resourceType" : "MedicationStatement",
  "id" : "ExampleISiKMedikationsInformation3",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
    ]
  },
  "status" : "active",
  "medicationReference" : {
    "reference" : "Medication/ExampleISiKMedikament8"
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "context" : {
    "reference" : "Encounter/FachabteilungskontaktMinimal"
  },
  "effectivePeriod" : {
    "start" : "2024-01-22",
    "end" : "2024-02-26"
  },
  "dateAsserted" : "2024-01-17",
  "dosage" : [
    {
      "timing" : {
        "repeat" : {
          "count" : 6,
          "duration" : 6,
          "durationUnit" : "wk",
          "frequency" : 1,
          "period" : 1,
          "periodUnit" : "wk"
        }
      },
      "doseAndRate" : [
        {
          "doseQuantity" : {
            "value" : 500,
            "unit" : "ml Infusionslösung",
            "system" : "http://unitsofmeasure.org",
            "code" : "mL"
          }
        }
      ]
    }
  ]
}

```
