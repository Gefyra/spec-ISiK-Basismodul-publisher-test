# ExampleISiKMedikationsInformation2 - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ExampleISiKMedikationsInformation2**

## Example MedicationStatement: ExampleISiKMedikationsInformation2

Profile: [ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md)

**ISiK MedicationStatementReplaces**: [MedicationStatement: extension = Erhöhtes Blutungsrisiko ist in diesem Fall vertretbar.,Akutmedikation (ISiK Medikationsart#akut),true,Schmerztherapie postoperativ; status = active; medication[x] = ->Medication Acetylcystein; effective[x] = 2021-07-01 --> (ongoing); dateAsserted = 2021-07-01](MedicationStatement-ExampleISiKMedikationsInformation1.md)

**status**: Active

**medication**: [Medication](Medication-ExampleISiKMedikament2.md)

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**context**: [Encounter: identifier = Visit number; status = unknown; class = inpatient encounter (ActCode#IMP); type = Operation,Abteilungskontakt; serviceType = Innere Medizin; period = 2022-05-03 --> 2022-05-05](Encounter-FachabteilungskontaktMinimal.md)

**effective**: 2021-07-04 --> (ongoing)

**dateAsserted**: 2021-07-03

> **dosage****timing**: Count 6 times, Once per 3 weeks

### DoseAndRates

| | |
| :--- | :--- |
| - | **Dose[x]** |
| * | 100 mg(Details: UCUM codemg = 'mg') |




## Resource Content

```json
{
  "resourceType" : "MedicationStatement",
  "id" : "ExampleISiKMedikationsInformation2",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
    ]
  },
  "extension" : [
    {
      "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKMedicationStatementReplaces",
      "valueReference" : {
        "reference" : "MedicationStatement/ExampleISiKMedikationsInformation1"
      }
    }
  ],
  "status" : "active",
  "medicationReference" : {
    "reference" : "Medication/ExampleISiKMedikament2"
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "context" : {
    "reference" : "Encounter/FachabteilungskontaktMinimal"
  },
  "effectivePeriod" : {
    "start" : "2021-07-04"
  },
  "dateAsserted" : "2021-07-03",
  "dosage" : [
    {
      "timing" : {
        "repeat" : {
          "count" : 6,
          "frequency" : 1,
          "period" : 3,
          "periodUnit" : "wk"
        }
      },
      "doseAndRate" : [
        {
          "doseQuantity" : {
            "value" : 100,
            "unit" : "mg",
            "system" : "http://unitsofmeasure.org",
            "code" : "mg"
          }
        }
      ]
    }
  ]
}

```
