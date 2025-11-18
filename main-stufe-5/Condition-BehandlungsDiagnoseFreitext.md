# BehandlungsDiagnoseFreitext - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **BehandlungsDiagnoseFreitext**

## Example Condition: BehandlungsDiagnoseFreitext

Profile: [ISiKDiagnose](StructureDefinition-ISiKDiagnose.md)

**clinicalStatus**: Active

**code**: Behandlungsdiagnose

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**onset**: 2019-09-02

**recordedDate**: 2021-01-01



## Resource Content

```json
{
  "resourceType" : "Condition",
  "id" : "BehandlungsDiagnoseFreitext",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKDiagnose"
    ]
  },
  "clinicalStatus" : {
    "coding" : [
      {
        "system" : "http://terminology.hl7.org/CodeSystem/condition-clinical",
        "code" : "active"
      }
    ]
  },
  "code" : {
    "text" : "Behandlungsdiagnose"
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "onsetDateTime" : "2019-09-02",
  "recordedDate" : "2021-01-01"
}

```
