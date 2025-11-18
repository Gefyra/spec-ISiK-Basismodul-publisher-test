# AbrechnungsfallGonarthrose - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **AbrechnungsfallGonarthrose**

## Example Account: AbrechnungsfallGonarthrose

Profile: [ISiKAbrechnungsfall](StructureDefinition-ISiKAbrechnungsfall.md)

**identifier**: Account number/1234567891

**status**: Active

**type**: inpatient encounter

**subject**: [Anna Müller (official) Female, DoB: 1957-08-12 ( Krankenversichertennummer)](Patient-PatientinNormal.md)



## Resource Content

```json
{
  "resourceType" : "Account",
  "id" : "AbrechnungsfallGonarthrose",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKAbrechnungsfall"
    ]
  },
  "identifier" : [
    {
      "type" : {
        "coding" : [
          {
            "system" : "http://terminology.hl7.org/CodeSystem/v2-0203",
            "code" : "AN"
          }
        ]
      },
      "system" : "https://test.krankenhaus.de/fhir/sid/abrechnungsnummer",
      "value" : "1234567891"
    }
  ],
  "status" : "active",
  "type" : {
    "coding" : [
      {
        "system" : "http://terminology.hl7.org/CodeSystem/v3-ActCode",
        "code" : "IMP"
      }
    ]
  },
  "subject" : [
    {
      "reference" : "Patient/PatientinNormal"
    }
  ]
}

```
