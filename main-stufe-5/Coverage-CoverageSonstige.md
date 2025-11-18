# CoverageSonstige - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **CoverageSonstige**

## Example Coverage: CoverageSonstige

Profile: [ISiKVersicherungsverhaeltnisSonstige](StructureDefinition-ISiKVersicherungsverhaeltnisSonstige.md)

**status**: Active

**type**: Sozialamt

**beneficiary**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**payor**: Sozialamt Posemuckel



## Resource Content

```json
{
  "resourceType" : "Coverage",
  "id" : "CoverageSonstige",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisSonstige"
    ]
  },
  "status" : "active",
  "type" : {
    "coding" : [
      {
        "system" : "http://fhir.de/CodeSystem/versicherungsart-de-basis",
        "code" : "SOZ"
      }
    ]
  },
  "beneficiary" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "payor" : [
    {
      "display" : "Sozialamt Posemuckel"
    }
  ]
}

```
