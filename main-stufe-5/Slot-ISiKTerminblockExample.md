# ISiKTerminblockExample - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKTerminblockExample**

## Example Slot: ISiKTerminblockExample

Profile: [ISiKTerminblock](StructureDefinition-ISiKTerminblock.md)

**schedule**: [Schedule: serviceType = General Practice; specialty = Allgemeinmedizin](Schedule-ISiKKalenderExample.md)

**status**: Busy

**start**: 2022-12-10 09:00:00+0000

**end**: 2022-12-10 11:00:00+0000



## Resource Content

```json
{
  "resourceType" : "Slot",
  "id" : "ISiKTerminblockExample",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKTerminblock"
    ]
  },
  "schedule" : {
    "reference" : "Schedule/ISiKKalenderExample"
  },
  "status" : "busy",
  "start" : "2022-12-10T09:00:00Z",
  "end" : "2022-12-10T11:00:00Z"
}

```
