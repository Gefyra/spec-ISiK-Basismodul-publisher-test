# ISiKTerminExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKTerminExample**

## Example Appointment: ISiKTerminExample

Profile: [ISiKTermin](StructureDefinition-ISiKTermin.md)

Tag: External (Details: CS Basisprofil Common Meta Tag DE code external = 'External')

**status**: Proposed

**serviceType**: General Practice

**specialty**: Allgemeinmedizin

**priority**: `ISiKTerminPriorityExtension:`Emergency

**start**: 2022-12-10 09:00:00+0000

**end**: 2022-12-10 11:00:00+0000

**slot**: [Slot: status = busy; start = 2022-12-10 09:00:00+0000; end = 2022-12-10 11:00:00+0000](Slot-ISiKTerminblockExample.md)

### Participants

| | | |
| :--- | :--- | :--- |
| - | **Actor** | **Status** |
| * | [Test Patient](Patient-ISiKPatientTest.md) | Accepted |



## Resource Content

```json
{
  "resourceType" : "Appointment",
  "id" : "ISiKTerminExample",
  "meta" : {
    "profile" : ["http://gefyra.info/training/StructureDefinition/ISiKTermin"],
    "tag" : [
      {
        "system" : "http://fhir.de/CodeSystem/common-meta-tag-de",
        "code" : "external"
      }
    ]
  },
  "status" : "proposed",
  "serviceType" : [
    {
      "coding" : [
        {
          "system" : "http://terminology.hl7.org/CodeSystem/service-type",
          "code" : "124"
        }
      ]
    }
  ],
  "specialty" : [
    {
      "coding" : [
        {
          "system" : "http://ihe-d.de/CodeSystems/AerztlicheFachrichtungen",
          "code" : "ALLG"
        }
      ]
    }
  ],
  "_priority" : {
    "extension" : [
      {
        "url" : "http://gefyra.info/training/StructureDefinition/ISiKTerminPriorityExtension",
        "valueCodeableConcept" : {
          "coding" : [
            {
              "system" : "http://snomed.info/sct",
              "code" : "25876001"
            }
          ]
        }
      }
    ]
  },
  "start" : "2022-12-10T09:00:00Z",
  "end" : "2022-12-10T11:00:00Z",
  "slot" : [
    {
      "reference" : "Slot/ISiKTerminblockExample"
    }
  ],
  "participant" : [
    {
      "actor" : {
        "reference" : "Patient/ISiKPatientTest",
        "display" : "Test Patient"
      },
      "status" : "accepted"
    }
  ]
}

```
