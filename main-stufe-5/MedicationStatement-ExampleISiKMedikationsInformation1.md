# ExampleISiKMedikationsInformation1 - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ExampleISiKMedikationsInformation1**

## Example MedicationStatement: ExampleISiKMedikationsInformation1

Profile: [ISiKMedikationsInformation](StructureDefinition-ISiKMedikationsInformation.md)

**ISiK Accepted Risk**: Erhöhtes Blutungsrisiko ist in diesem Fall vertretbar.

**ISiK Medikationsart**: [ISiK Medikationsart: akut](CodeSystem-ISiKMedikationsartCS.md#ISiKMedikationsartCS-akut) (Akutmedikation)

**ISiK Selbstmedikation**: true

**ISiK Behandlungsziel**: Schmerztherapie postoperativ

**status**: Active

**medication**: [Medication Acetylcystein](Medication-ExampleISiKMedikament1.md)

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**context**: [Encounter: identifier = Visit number; status = unknown; class = inpatient encounter (ActCode#IMP); type = Operation,Abteilungskontakt; serviceType = Innere Medizin; period = 2022-05-03 --> 2022-05-05](Encounter-FachabteilungskontaktMinimal.md)

**effective**: 2021-07-01 --> (ongoing)

**dateAsserted**: 2021-07-01

**reasonReference**: [Condition](Condition-BehandlungsDiagnoseFreitext.md)

> **dosage****timing**: Morning, Noon, Evening, Once

### DoseAndRates

| | |
| :--- | :--- |
| - | **Dose[x]** |
| * | 1 Brausetablette(Details: UCUM code1 = '1') |




## Resource Content

```json
{
  "resourceType" : "MedicationStatement",
  "id" : "ExampleISiKMedikationsInformation1",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKMedikationsInformation"
    ]
  },
  "extension" : [
    {
      "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKAcceptedRisk",
      "valueString" : "Erhöhtes Blutungsrisiko ist in diesem Fall vertretbar."
    },
    {
      "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKMedikationsart",
      "valueCoding" : {
        "system" : "http://gefyra.info/training/CodeSystem/ISiKMedikationsartCS",
        "code" : "akut"
      }
    },
    {
      "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKSelbstmedikation",
      "valueBoolean" : true
    },
    {
      "url" : "http://gefyra.info/training/StructureDefinition/ExtensionISiKBehandlungsziel",
      "valueString" : "Schmerztherapie postoperativ"
    }
  ],
  "status" : "active",
  "medicationReference" : {
    "reference" : "Medication/ExampleISiKMedikament1"
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "context" : {
    "reference" : "Encounter/FachabteilungskontaktMinimal"
  },
  "effectivePeriod" : {
    "start" : "2021-07-01"
  },
  "dateAsserted" : "2021-07-01",
  "reasonReference" : [
    {
      "reference" : "Condition/BehandlungsDiagnoseFreitext"
    }
  ],
  "dosage" : [
    {
      "timing" : {
        "repeat" : {
          "when" : ["MORN", "NOON", "EVE"]
        }
      },
      "doseAndRate" : [
        {
          "doseQuantity" : {
            "value" : 1,
            "unit" : "Brausetablette",
            "system" : "http://unitsofmeasure.org",
            "code" : "1"
          }
        }
      ]
    }
  ]
}

```
