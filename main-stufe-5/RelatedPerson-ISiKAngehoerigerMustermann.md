# ISiKAngehoerigerMustermann - v0.1.0

* [**Table of Contents**](toc.md)
* [**Artifacts Summary**](artifacts.md)
* **ISiKAngehoerigerMustermann**

## Example RelatedPerson: ISiKAngehoerigerMustermann

Profile: [ISiKAngehoeriger](StructureDefinition-ISiKAngehoeriger.md)

**patient**: [Erika Fürstin von Musterfrau (official) Female, DoB: 1964-08-12 ( Private Krankenversicherung (use: secondary, ))](Patient-PatientinMusterfrau.md)

**relationship**: daughter

**name**: Maxine Mustermann (Official)

**address**: Milchstr. 42 Beispielstadt 78143 DE 



## Resource Content

```json
{
  "resourceType" : "RelatedPerson",
  "id" : "ISiKAngehoerigerMustermann",
  "meta" : {
    "profile" : [
      "http://gefyra.info/training/StructureDefinition/ISiKAngehoeriger"
    ]
  },
  "patient" : {
    "reference" : "Patient/PatientinMusterfrau"
  },
  "relationship" : [
    {
      "coding" : [
        {
          "system" : "http://terminology.hl7.org/CodeSystem/v3-RoleCode",
          "code" : "DAUC"
        }
      ]
    }
  ],
  "name" : [
    {
      "use" : "official",
      "family" : "Mustermann",
      "given" : ["Maxine"]
    }
  ],
  "address" : [
    {
      "type" : "both",
      "line" : ["Milchstr. 42"],
      "city" : "Beispielstadt",
      "postalCode" : "78143",
      "country" : "DE"
    }
  ]
}

```
