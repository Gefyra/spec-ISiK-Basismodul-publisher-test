# FachabteilungskontaktMinimal2 - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **FachabteilungskontaktMinimal2**

## Example Encounter: FachabteilungskontaktMinimal2

Profile: [ISiKKontaktGesundheitseinrichtung](StructureDefinition-ISiKKontaktGesundheitseinrichtung.md)

**identifier**: Visit number/0123456789

**status**: Finished

**class**: [ActCode: IMP](http://terminology.hl7.org/7.0.0/CodeSystem-v3-ActCode.html#v3-ActCode-IMP) (inpatient encounter)

**type**: Abteilungskontakt

**subject**: [Anna Müller (official) Female, DoB: 1957-08-12 ( Krankenversichertennummer)](Patient-PatientinNormal.md)



## Resource Content

```json
{
  "resourceType" : "Encounter",
  "id" : "FachabteilungskontaktMinimal2",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKKontaktGesundheitseinrichtung"
    ]
  },
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
      "value" : "0123456789"
    }
  ],
  "status" : "finished",
  "class" : {
    "system" : "http://terminology.hl7.org/CodeSystem/v3-ActCode",
    "code" : "IMP"
  },
  "type" : [
    {
      "coding" : [
        {
          "system" : "http://fhir.de/CodeSystem/Kontaktebene",
          "code" : "abteilungskontakt"
        }
      ]
    }
  ],
  "subject" : {
    "reference" : "Patient/PatientinNormal"
  }
}

```
