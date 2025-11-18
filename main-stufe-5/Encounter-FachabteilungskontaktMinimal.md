# FachabteilungskontaktMinimal - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **FachabteilungskontaktMinimal**

## Example Encounter: FachabteilungskontaktMinimal

**identifier**: Visit number/0123456789

**status**: Unknown

**class**: [ActCode: IMP](http://terminology.hl7.org/7.0.0/CodeSystem-v3-ActCode.html#v3-ActCode-IMP) (inpatient encounter)

**type**: Operation, Abteilungskontakt

**serviceType**: Innere Medizin

**subject**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**period**: 2022-05-03 --> 2022-05-05



## Resource Content

```json
{
  "resourceType" : "Encounter",
  "id" : "FachabteilungskontaktMinimal",
  "identifier" : [
    {
      "type" : {
        "coding" : [
          {
            "system" : "http://terminology.hl7.org/CodeSystem/v2-0203",
            "code" : "VN"
          }
        ]
      },
      "system" : "https://test.krankenhaus.de/fhir/sid/besuchsnummer",
      "value" : "0123456789"
    }
  ],
  "status" : "unknown",
  "class" : {
    "system" : "http://terminology.hl7.org/CodeSystem/v3-ActCode",
    "code" : "IMP"
  },
  "type" : [
    {
      "coding" : [
        {
          "system" : "http://fhir.de/CodeSystem/kontaktart-de",
          "code" : "operation"
        }
      ]
    },
    {
      "coding" : [
        {
          "system" : "http://fhir.de/CodeSystem/Kontaktebene",
          "code" : "abteilungskontakt"
        }
      ]
    }
  ],
  "serviceType" : {
    "coding" : [
      {
        "system" : "http://fhir.de/CodeSystem/dkgev/Fachabteilungsschluessel",
        "code" : "0100"
      }
    ]
  },
  "subject" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "period" : {
    "start" : "2022-05-03",
    "end" : "2022-05-05"
  }
}

```
