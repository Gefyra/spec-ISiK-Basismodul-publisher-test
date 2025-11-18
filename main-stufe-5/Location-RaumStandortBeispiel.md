# RaumStandortBeispiel - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **RaumStandortBeispiel**

## Example Location: RaumStandortBeispiel

Profile: [ISiKStandortRaum](StructureDefinition-ISiKStandortRaum.md)

**physicalType**: Room

**managingOrganization**: [Organization Allgemeinchirurgie](Organization-AbteilungAllgemeinchirurgieOrganisationBeispiel.md)



## Resource Content

```json
{
  "resourceType" : "Location",
  "id" : "RaumStandortBeispiel",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKStandortRaum"
    ]
  },
  "physicalType" : {
    "coding" : [
      {
        "system" : "http://terminology.hl7.org/CodeSystem/location-physical-type",
        "code" : "ro",
        "display" : "Room"
      }
    ]
  },
  "managingOrganization" : {
    "reference" : "Organization/AbteilungAllgemeinchirurgieOrganisationBeispiel"
  }
}

```
