# SZ1VersicherungSelbstzahler - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **SZ1VersicherungSelbstzahler**

## Example Coverage: SZ1VersicherungSelbstzahler

Profile: [ISiKVersicherungsverhaeltnisSelbstzahler](StructureDefinition-ISiKVersicherungsverhaeltnisSelbstzahler.md)

**status**: Active

**type**: Selbstzahler

**beneficiary**: [Töchterchen Musterfrau (official) Female, DoB: 2010-01-01 ( Krankenversichertennummer)](Patient-SZ1Patient.md)

**payor**: [RelatedPerson Mama Musterfrau (official)](RelatedPerson-SZ1Mutter.md)



## Resource Content

```json
{
  "resourceType" : "Coverage",
  "id" : "SZ1VersicherungSelbstzahler",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisSelbstzahler"
    ]
  },
  "status" : "active",
  "type" : {
    "coding" : [
      {
        "system" : "http://fhir.de/CodeSystem/versicherungsart-de-basis",
        "code" : "SEL"
      }
    ]
  },
  "beneficiary" : {
    "reference" : "Patient/SZ1Patient"
  },
  "payor" : [
    {
      "reference" : "RelatedPerson/SZ1Mutter"
    }
  ]
}

```
