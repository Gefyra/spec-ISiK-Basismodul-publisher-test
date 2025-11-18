# ExampleISiKMedikationsVerabreichung2 - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ExampleISiKMedikationsVerabreichung2**

## Example MedicationAdministration: ExampleISiKMedikationsVerabreichung2

Profile: [ISiKMedikationsVerabreichung](StructureDefinition-ISiKMedikationsVerabreichung.md)

**status**: Completed

**medication**: [Medication](Medication-ExampleISiKMedikament9.md)

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**context**: [Encounter: identifier = Visit number; status = unknown; class = inpatient encounter (ActCode#IMP); type = Operation,Abteilungskontakt; serviceType = Innere Medizin; period = 2022-05-03 --> 2022-05-05](Encounter-FachabteilungskontaktMinimal.md)

**effective**: 2024-01-22

### Dosages

| | |
| :--- | :--- |
| - | **Dose** |
| * | 1 Beutel(Details: UCUM code1 = '1') |



## Resource Content

```json
{
  "resourceType" : "MedicationAdministration",
  "id" : "ExampleISiKMedikationsVerabreichung2",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKMedikationsVerabreichung"
    ]
  },
  "status" : "completed",
  "medicationReference" : {
    "reference" : "Medication/ExampleISiKMedikament9"
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "context" : {
    "reference" : "Encounter/FachabteilungskontaktMinimal"
  },
  "effectiveDateTime" : "2024-01-22",
  "dosage" : {
    "dose" : {
      "value" : 1,
      "unit" : "Beutel",
      "system" : "http://unitsofmeasure.org",
      "code" : "1"
    }
  }
}

```
