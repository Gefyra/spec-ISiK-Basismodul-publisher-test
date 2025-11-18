# SZ1VersicherungGesetzlich - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **SZ1VersicherungGesetzlich**

## Example Coverage: SZ1VersicherungGesetzlich

Profile: [ISiKVersicherungsverhaeltnisGesetzlich](StructureDefinition-ISiKVersicherungsverhaeltnisGesetzlich.md)

**status**: Active

**type**: gesetzliche Krankenversicherung

**subscriber**: [RelatedPerson Mama Musterfrau (official)](RelatedPerson-SZ1Mutter.md)

**beneficiary**: [Töchterchen Musterfrau (official) Female, DoB: 2010-01-01 ( Krankenversichertennummer)](Patient-SZ1Patient.md)

**payor**: TKKG (Identifier: Organization identifier/260326822)



## Resource Content

```json
{
  "resourceType" : "Coverage",
  "id" : "SZ1VersicherungGesetzlich",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKVersicherungsverhaeltnisGesetzlich"
    ]
  },
  "status" : "active",
  "type" : {
    "coding" : [
      {
        "system" : "http://fhir.de/CodeSystem/versicherungsart-de-basis",
        "code" : "GKV"
      }
    ]
  },
  "subscriber" : {
    "reference" : "RelatedPerson/SZ1Mutter",
    "identifier" : {
      "type" : {
        "coding" : [
          {
            "system" : "http://fhir.de/CodeSystem/identifier-type-de-basis",
            "code" : "KVZ10"
          }
        ]
      },
      "system" : "http://fhir.de/sid/gkv/kvid-10",
      "value" : "A987654321"
    }
  },
  "beneficiary" : {
    "reference" : "Patient/SZ1Patient"
  },
  "payor" : [
    {
      "identifier" : {
        "type" : {
          "coding" : [
            {
              "system" : "http://terminology.hl7.org/CodeSystem/v2-0203",
              "code" : "XX"
            }
          ]
        },
        "system" : "http://fhir.de/sid/arge-ik/iknr",
        "value" : "260326822"
      },
      "display" : "TKKG"
    }
  ]
}

```
