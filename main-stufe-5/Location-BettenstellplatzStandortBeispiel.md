# BettenstellplatzStandortBeispiel - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **BettenstellplatzStandortBeispiel**

## Example Location: BettenstellplatzStandortBeispiel

Profile: [ISiKStandortBettenstellplatz](StructureDefinition-ISiKStandortBettenstellplatz.md)

**physicalType**: Bed

**managingOrganization**: [Organization Allgemeinchirurgie](Organization-AbteilungAllgemeinchirurgieOrganisationBeispiel.md)

**partOf**: [Location: physicalType = Room](Location-RaumStandortBeispiel.md)



## Resource Content

```json
{
  "resourceType" : "Location",
  "id" : "BettenstellplatzStandortBeispiel",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKStandortBettenstellplatz"
    ]
  },
  "physicalType" : {
    "coding" : [
      {
        "system" : "http://terminology.hl7.org/CodeSystem/location-physical-type",
        "code" : "bd",
        "display" : "Bed"
      }
    ]
  },
  "managingOrganization" : {
    "reference" : "Organization/AbteilungAllgemeinchirurgieOrganisationBeispiel"
  },
  "partOf" : {
    "reference" : "Location/RaumStandortBeispiel"
  }
}

```
